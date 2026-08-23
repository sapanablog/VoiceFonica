# VoiceFonica

## Telecom Billing, Recharge and Customer Self-Service Platform

VoiceFonica is a full-stack telecom application designed to centralize customer and administrative operations in one web platform.

The project addresses common telecom service challenges such as manual billing, recharge processing, payment reminders, customer queries, account management, and fragmented legacy workflows.

The application combines a Spring Boot backend, Oracle database, and Angular frontend to provide customer-facing and administrative functionality through a web-based interface.

## Project Motivation

Telecom customers often need separate or manual processes for activities such as:

- Checking available plans
- Managing their account
- Recharging their mobile number
- Paying bills
- Viewing recharge history
- Contacting customer support

These fragmented workflows can increase manual effort and make customer service slower and less convenient.

VoiceFonica was developed to provide a centralized self-service platform where customers can manage common telecom activities through one web application.

## Key Features

### Customer Features

- Customer registration and login
- Customer account management
- Prepaid plan browsing
- Online recharge workflow
- Recharge history
- Bill-related workflows
- Online bill payment workflow
- Payment reminder workflow
- Customer queries and support requests
- Centralized customer navigation

### Administrative Features

- Customer management
- Plan and offer management
- Administrative login and registration
- Customer query management
- Telecom service administration
- Support for customer and account operations

### Automation-Oriented Workflows

- Automated bill generation
- Bill notification workflow
- Payment reminder workflow
- Recharge processing
- Customer support workflow
- Number-portability support workflow

> Feature availability depends on the corresponding module and local project configuration.

## Technical Architecture
```text
Angular Frontend
        |
        | HTTP / REST API integration
        v
Spring Boot Backend
        |
        | Business logic and validation
        v
Spring Data JPA / JDBC
        |
        v
Oracle Database
