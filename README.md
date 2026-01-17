# task-6
Auto Tagging Support Tickets Using LLM
Objective

Automatically tag support tickets into categories using a Large Language Model (LLM).

Dataset

Free-text support tickets (CSV or JSON) with labels like:
Billing, Technical, Account, Feedback, Complaint.

Features

Generates top 3 probable tags per ticket

Supports zero-shot and few-shot learning

Uses prompt engineering for better accuracy

Outputs predictions in CSV format for review

Usage

Load your ticket dataset (tickets.csv)

Run the notebook/script to tag tickets

Get predictions as:

ticket_text -> [tag1, tag2, tag3]

Learning Outcomes

Prompt engineering with LLMs

Multi-class classification

Zero-shot and few-shot learning

LLM-based automation for real-world support tasks

Conclusion

This project demonstrates how to automatically classify support tickets, improving efficiency and response time in real-world applications.
