# Slack Workflow

## Step 1

User sends a request.

Example:
"Analyze this dataset"

## Step 2

Hermes receives the request in #orchestrator.

Hermes creates tasks.

## Step 3

Hermes sends coding tasks to #coding.

OpenClaw receives the tasks.

## Step 4

OpenClaw completes the task and shares the result.

## Step 5

QA Agent receives the result in #qa.

QA checks if the result is correct.

## Step 6

Reporting Agent creates a summary in #reports.

## Step 7

Human reviews the final result in #human-review.

## Workflow Diagram

User
↓
Hermes
↓
OpenClaw
↓
QA Agent
↓
Reporting Agent
↓
Human Approval
