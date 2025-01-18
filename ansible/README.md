# Ansible Playbooks Collection

## Overview

This repository contains Ansible playbooks for automating system configuration and deployment tasks.

## Prerequisites

- Ansible 2.9 or higher
- SSH access to target hosts
- Inventory file configured with target hosts

## Directory Structure

- services.json - file describing all the docker services
- inventory.ini - file describing all the hosts and groups

## Commands

`ansible-playbook -i inventory.ini update_vps.yml`
Update the OS of all VPS servers.

`ansible-playbook -i inventory.ini update_docker_all.yml`
Update all docker hosts and docker images
