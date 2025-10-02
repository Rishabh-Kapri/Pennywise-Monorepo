# Pennywise

A full-stack personal finance management application inspired by YNAB, built to solve the problem of automatic transaction tracking in India where such services aren't readily available.

## Overview

Pennywise automatically extracts and categorizes financial transactions from email notifications, eliminating manual data entry. The project evolved from a Firebase-backed frontend-only application to a distributed system with Golang backend services and PostgreSQL database.

## Key Features

- **Email-based Transaction Parsing**: Automatically extracts transaction details from bank notification emails
- **ML-powered Categorization**: Custom-trained neural network (MLP) that predicts account, payee, and category from transaction data
- **Multi-budget Management**: Support for tracking multiple budgets simultaneously
- **Visualization**: Pie charts and table reports for expense analysis

## Technical Stack

- **Backend**: Golang, Python
- **Database**: PostgreSQL (migrated from Firebase)
- **Machine Learning**: Custom MLP model trained on personal transaction data
- **Frontend**: Angular

## Roadmap

- [ ] Multi-user support with authentication
- [ ] Real-time sync with conflict resolution using ETags and sync logs
- [ ] Undo functionality leveraging sync architecture
- [ ] Health monitoring for self-hosted deployment
- [ ] Mobile-responsive interface
- [ ] PDF report generation
- [ ] Model retraining pipeline for improving prediction accuracy
- [ ] Category-based financial goals and tracking
