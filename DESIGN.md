# Design Document

> Work In Progress!

## Title

Builder

## Overview

Making it easy for developers to deploy applications and services without the need to reach out to DevOps or System Admin teams to provision infrastructure!

### Problem Statement

We are starting to see more and more tools aim at improving the developer experience when it comes to provisioning applications on the cloud. One thing i've noticed is that they are almost always require Kubernetes to make this happen. Maybe i'm a bit crazy or lost, but I feel we need something that doesn't require Kubernetes. I do appreciate and see the value in a Kubernetes backed solution, but I can't help but think about the little people that don't have the need or experience to run Kubernetes. Whether you want to be in the cloud or on prem, it should be easy to spin up applications and move them back and forth between on and prem or cloud providers!

### Goals & Non Goals

#### Goals

- Be able to easily migrate between cloud providers without having to change `app_config.yml` to match provider specific configuration
- Easily switch between infrastructure (terraform) and config management tools (saltstack)
- Currently focus on providing Terraform and SaltStack support but easily be able to add new ones later on
- Github Actions as the orchestration host

#### Non Goals

- Kubernetest backed solution
- Cloud Run as the orchestration host

## Proposed Solution

### Architecture

### Workflow

## Key Decisions

## Trade-offs & Alternatives

## Risks and Mitigations

## Next Steps

## Open Questions
