# WooCommerce-Order-Automation-with-n8n
This project implements a complete order processing and notification system for a WooCommerce store using n8n. It automates order intake, validation, notifications, storage, and shipping follow-ups.
WooCommerce Order Automation (n8n)

This project automates the entire WooCommerce order workflow using n8n, from real-time order capture to customer shipping notifications.

What it does

Automatically receives new WooCommerce orders via webhook

Validates that the order is paid (processing/completed only)

Extracts and cleans customer, product, and payment details

Saves every order into Google Sheets as an order database

Sends instant admin alerts via Telegram

Sends admin email notifications for record keeping

Sends order confirmation emails to customers

Periodically checks dispatched orders

Automatically emails customers with courier and tracking details

Prevents duplicate shipping emails using tracking status flags

Why it’s useful

Eliminates manual order monitoring

Reduces missed or delayed customer communication

Centralizes order tracking in Google Sheets

Provides real-time visibility into new orders

Scales easily for small and growing WooCommerce stores

Tech Stack

n8n

WooCommerce REST API & Webhooks

Google Sheets

Telegram Bot

Gmail API

Outcome

A fully automated, reliable, and production-ready order management and notification system for WooCommerce stores.
