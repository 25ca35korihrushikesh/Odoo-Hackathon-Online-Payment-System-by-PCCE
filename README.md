# Odoo-Hackathon-Online-Payment-System-by-PCCE
Here we are making the web application that automatically manages the complete subscription lifecycle - from customer registration to subscription.

Brightloop --- Subscription Management System
Brightloop is a web application project for managing B2B recurring
revenue and subscription operations. The supplied project configuration
identifies React 19, Vite, TypeScript, Tailwind CSS 4, Supabase, and
Google Gemini as its main technologies.
Project status: This README is based on the configuration,
environment template, HTML entry page, and Supabase SQL schema
supplied with the project. The application source directory (src/)
was not included in the supplied files, so individual screens, routes,
and implemented workflows could not be verified.

Project capabilities represented in the database schema
The Supabase schema defines data structures and access policies for:
- User profiles and roles: admin, staff, and customer
- Staff operators and permissions
- Customers and customer records
- Products, product variants, and subscription plans
- Billing intervals: daily, weekly, monthly, quarterly, and yearly
- Taxes and discounts
- Quotations and quotation line items
- Subscriptions and subscription line items
- Invoices and invoice line items
- Payments and payment status
- Discount usage history
- Billing events and activity logs
- User notifications
The schema also includes indexes, row-level security (RLS) policies, a
payment-triggered invoice balance update, and a trigger that creates a
profile when a new Supabase Auth user is registered.

Note: A database schema defines the database structure and policies;
it does not by itself prove that every workflow is connected to the
frontend or to a live payment provider.
Technology stack
  Area                                 Technology
  UI framework                         React 19
Build tool and development server    Vite 8
Language                             TypeScript
Styling                              Tailwind CSS 4
Database and authentication client   Supabase JavaScript client
AI SDK dependency                    Google GenAI
Icons                                Lucide React
Animation                            Motio
Additional server dependency         Express
Prerequisites
Install the following before starting:
- Node.js (use a current version compatible with the installed Vite
  release)
- npm, or Bun if you prefer the included bun.lock
- A Supabase project for database and authentication features
- A Google Gemini API key only if the application uses Gemini-powered
  features

live website link-https://precision-metric.ai.studio/
