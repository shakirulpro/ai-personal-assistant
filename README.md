# AI Personal Assistant — Intelligent Email Management Automation

An AI-powered email management system built with n8n that automatically classifies incoming emails and routes them into four categories: Tasks, Questions, Documents, and Ignore.

## Overview

This project uses AI to understand incoming email content and trigger the appropriate action, reducing manual email management and improving productivity.

## Features

- **Task Management:** Identifies task-related emails, creates Google Tasks, and sends Telegram notifications.
- **Question Handling:** Generates draft email replies for review and sends approved responses.
- **Document Management:** Identifies and routes document-related emails for easier organization and processing.
- **Email Filtering:** Categorizes low-priority or irrelevant emails into an Ignore category.

## Workflow Architecture

Incoming Email → n8n Workflow → AI Classification → Category-Based Routing → Automated Actions

## Tech Stack

- n8n — Workflow automation
- OpenAI — AI-powered email understanding and classification
- Gmail — Email processing and replies
- Google Tasks — Task creation and management
- Telegram — Notifications and alerts

## Use Cases

- Personal productivity
- Business email management
- Administrative workflow automation
- AI-powered task management
- Automated customer communication

## Setup

1. Install or access an n8n instance.
2. Import the workflow JSON from the `workflows` folder.
3. Configure your Gmail, OpenAI, Google Tasks, and Telegram credentials.
4. Update any required workflow settings and prompts.
5. Test each email category using sample emails.
6. Activate the workflow after verifying the results.

## Security

Never commit API keys, access tokens, passwords, private emails, or sensitive workflow data. Configure credentials securely within n8n.

## Project Purpose

This project demonstrates how AI and workflow automation can be combined to simplify everyday email management and reduce repetitive manual work.

## Author

AI Automation Projects | n8n | AI Agents | Business Workflow Automation
