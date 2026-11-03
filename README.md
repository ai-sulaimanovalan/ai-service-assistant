# AI Service Assistant

### AI-Powered Telegram Bot | Customer Support Automation | AI Agents

An intelligent Telegram assistant built with **Make.com and OpenAI API** to automate customer support and repair request management for a technical service center.

## Project Overview

AI Service Assistant is an educational prototype designed to help businesses automate customer communication, collect repair requests, and transfer complex issues to human managers.

The system combines AI-powered responses with structured workflow automation.

## Key Features

### 1. AI Customer Support
- Answers customer questions in Russian and Turkish.
- Uses a structured knowledge base.
- Avoids inventing unknown prices or repair times.

### 2. Automated Repair Requests
- Extracts device, model, and problem details from customer messages.
- Registers repair requests in Google Sheets.
- Supports one-message request submission.

### 3. Conversation Memory
- Stores conversation states using Make Data Store.
- Collects missing information step by step.
- Allows customers to confirm or cancel requests.

### 4. Human Handoff
- Transfers complex customer inquiries to a manager.
- Collects a description of the customer's problem.
- Sends Telegram notifications to the manager.

### 5. Error Handling
- Handles Telegram notification failures.
- Preserves customer issue descriptions when delivery fails.
- Supports retrying the handoff after recovery.

## Technologies

- Make.com
- OpenAI API
- Telegram Bot API
- Google Sheets
- Make Data Store
- JSON
- Routers & Filters
- Error Handlers

## System Architecture

Telegram Bot → Make.com → Router → OpenAI / Data Store / Google Sheets → Telegram Bot

## Testing

The following functionality was successfully tested:

- AI consultations
- Telegram commands and main menu
- Automatic request registration
- Multi-step conversations
- Request confirmation and cancellation
- Human handoff
- Error handling
- Recovery after notification failure

## Project Status

**Completed educational prototype — November 2026.**

Core functionality has been tested successfully.

Additional security, privacy, and reliability testing is required before production deployment.

## Author

**Alan Sulaimanov**

Junior AI Automation Developer

GitHub: [ai-sulaimanovalan](https://github.com/ai-sulaimanovalan)

## Project Documentation

[View Project Portfolio (PDF)](<./AI Service Assistant - Описание проекта.pdf>)
