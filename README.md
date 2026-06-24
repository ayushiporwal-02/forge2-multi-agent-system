# Forge 2 Multi-Agent System

## Problem Statement

Build a multi-agent AI system using Hermes as the orchestrator and OpenClaw as the coding agent. Agents communicate through Slack, use GitHub for version control, and follow a CI/CD workflow.

## Architecture

User → Hermes → Worker Agents → Slack → GitHub → CI/CD → Human Approval

## Agents

### Hermes (Orchestrator)

* Breaks tasks into subtasks
* Assigns work to agents
* Tracks progress

### OpenClaw (Coding Agent)

* Writes code
* Fixes bugs
* Runs tests

### QA Agent

* Validates outputs
* Reports failures

### Reporting Agent

* Creates status reports
* Summarizes project progress

## Tech Stack

* Hermes Agent
* OpenClaw
* Slack
* GitHub
* Python
* Node.js

## Workflow

1. User submits a request
2. Hermes analyzes the request
3. Hermes assigns tasks
4. Agents communicate through Slack
5. OpenClaw writes code
6. QA validates results
7. Human reviews and approves

## Project Structure

agents/
docs/
slack/
.github/workflows/

## How to Run

Instructions will be added during development.

## Team

Forge 2 Competition Submission
