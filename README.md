# auto_agency

AUTONOMOUS DIGITAL AGENCY

MASTER BUILD PROMPT PACK

VERSION 1.0

OBJECTIVE

Build a production-grade autonomous agency platform that:

1. Discovers local businesses.
2. Scores digital maturity.
3. Identifies revenue opportunities.
4. Generates personalized website previews.
5. Creates outreach campaigns.
6. Sends personalized emails.
7. Tracks engagement.
8. Creates CRM opportunities.
9. Books appointments.
10. Produces proposals.
11. Creates fulfillment projects.
12. Converts clients into recurring revenue.

The end state is a system that can continuously generate qualified business opportunities with minimal manual intervention while maintaining compliance, deliverability, and operational visibility.

⸻

PROMPT 01

SYSTEM ARCHITECT

You are a senior systems architect.

Design the complete architecture for an autonomous digital agency platform.

Requirements:

Data Layer:

* PostgreSQL
* Lead database
* Client database
* Opportunity database
* Outreach tracking
* Preview tracking

Application Layer:

* Next.js App Router
* TypeScript
* Tailwind
* Server Actions

Automation Layer:

* n8n
* Queue processing
* Scheduled jobs

Infrastructure Layer:

* Docker
* VPS deployment
* Reverse proxy
* SSL

Communication Layer:

* Email
* SMS
* CRM

Output:

* Complete architecture diagram
* Folder structure
* Service boundaries
* Database relationships
* API flow
* Queue flow
* Security model
* Deployment model

Acceptance Criteria:

Every system component must have:

* Purpose
* Inputs
* Outputs
* Dependencies
* Failure handling

⸻

PROMPT 02

DATABASE ENGINEER

Design the complete PostgreSQL schema.

Required tables:

businesses
business_locations
business_contacts
business_reviews
business_scores
websites
website_audits
website_previews
prospecting_campaigns
prospects
email_sequences
email_events
email_opens
email_clicks
email_replies
crm_opportunities
proposals
projects
tasks
automation_logs

Requirements:

* Proper indexes
* Foreign keys
* Cascading strategy
* Audit timestamps
* Soft deletes

Output:

* SQL migrations
* ERD
* Relationships
* Query optimization notes

⸻

PROMPT 03

GOOGLE MAPS DISCOVERY ENGINE

Build the lead discovery system.

Goal:

Find local businesses by category and city.

Inputs:

Industry:

* Roofer
* HVAC
* Plumber
* Electrician
* Remodeler
* Dentist
* Med Spa

Location:

* City
* State

Extract:

* Business Name
* Address
* Website
* Phone
* Rating
* Reviews
* Category
* Hours
* Maps URL

Store results in PostgreSQL.

Output:

Production-ready service.

Include:

* Rate limiting
* Retry logic
* Logging
* Duplicate detection

⸻

PROMPT 04

DIGITAL MATURITY SCORING ENGINE

Create a scoring algorithm.

Evaluate:

Website Exists
Website Speed
Mobile Friendly
Reviews Present
Call To Action
Contact Form
Booking Capability
Trust Signals
Analytics
Pixel Detection
CRM Detection
Email Capture

Score:

0–100

Output:

Digital Maturity Score

Classify:

Invisible
Weak
Average
Strong
Advanced

Generate reasoning for every score.

Store findings.

⸻

PROMPT 05

WEBSITE AUDIT AGENT

Create an AI audit engine.

Input:

Website URL

Analyze:

Design Quality
Conversion Flow
CTA Placement
Navigation
Speed
Trust
Social Proof
Lead Capture
Mobile UX

Generate:

Executive Summary
Strengths
Weaknesses
Revenue Opportunities
Infrastructure Gaps

Store audit results.

⸻

PROMPT 06

OPPORTUNITY CLASSIFIER

Create business opportunity categories.

Categories:

NO_WEBSITE

BAD_WEBSITE

GOOD_WEBSITE_NO_CRM

GOOD_WEBSITE_NO_AUTOMATION

HIGH_REVIEW_LOW_CONVERSION

HIGH_VALUE_TARGET

Generate:

Opportunity Score
Recommended Offer
Revenue Potential

Store results.

⸻

PROMPT 07

WEBSITE PREVIEW GENERATOR

Build preview generation.

Input:

Business Information

Generate:

Homepage
Hero Section
Services
Review Section
Contact Form
CTA

Requirements:

Responsive

Professional

Industry-Specific

Output:

Unique Preview URL

Store Preview Metadata.

⸻

PROMPT 08

TEMPLATE ENGINE

Create reusable templates.

Required Templates:

Roofing

HVAC

Plumbing

Electrical

Remodeling

Dental

Med Spa

Landscaping

Pool Builder

Cabinet Company

Each template must support:

Dynamic Content

Dynamic Reviews

Dynamic Colors

Dynamic Images

Dynamic Contact Information

⸻

PROMPT 09

REVIEW IMPORT ENGINE

Build review extraction.

Input:

Google Review Data

Generate:

Review Highlights

Featured Testimonials

Average Rating Block

Review Summary

Store results.

⸻

PROMPT 10

EMAIL ENRICHMENT ENGINE

Discover:

Owner Name

Decision Maker

Public Contact Emails

Business Emails

Domain Contacts

Requirements:

Compliance aware.

Store confidence scores.

⸻

PROMPT 11

OUTREACH STRATEGY ENGINE

Determine:

Best Offer

Best Messaging Angle

Best Subject Line

Best CTA

Based on:

Website Quality

Review Count

Industry

Business Size

Output:

Campaign Strategy Object

⸻

PROMPT 12

EMAIL COPYWRITER AGENT

Generate outreach emails.

Requirements:

Personalized

Natural

Short

Relevant

No spam language

Include:

Business Name

Observed Issue

Preview Link

CTA

Generate:

Email 1

Email 2

Email 3

Email 4

⸻

PROMPT 13

DELIVERABILITY SYSTEM

Design outbound infrastructure.

Requirements:

SPF

DKIM

DMARC

Tracking Domains

Bounce Management

Suppression Lists

Reply Detection

Warmup Process

Output:

Deployment Guide

Monitoring System

⸻

PROMPT 14

CAMPAIGN ENGINE

Build campaign orchestration.

Workflow:

Lead Added

Score Lead

Audit Website

Generate Preview

Generate Email

Queue Email

Track Events

Update CRM

Requirements:

Retry Logic

Error Handling

Observability

⸻

PROMPT 15

CRM SYSTEM

Build CRM.

Stages:

Discovered

Qualified

Preview Generated

Email Sent

Opened

Clicked

Replied

Booked

Proposal Sent

Won

Lost

Client

Retainer

Generate:

Pipeline Logic

Automations

Task Creation Rules

⸻

PROMPT 16

ENGAGEMENT TRACKER

Track:

Email Opens

Email Clicks

Replies

Meetings

Preview Visits

Generate:

Lead Engagement Score

Store activity history.

⸻

PROMPT 17

APPOINTMENT BOOKING ENGINE

Create scheduling flow.

Requirements:

Calendar Integration

Availability Rules

Timezone Handling

Lead Attribution

Reminder Sequences

Store booking history.

⸻

PROMPT 18

AI SALES ASSISTANT

When a meeting is booked:

Generate:

Prospect Summary

Website Findings

Review Analysis

Talking Points

Recommended Offer

Objections

Close Strategy

⸻

PROMPT 19

PROPOSAL GENERATOR

Generate proposals automatically.

Inputs:

Business Type

Opportunity Type

Services

Pricing

Outputs:

PDF Proposal

Scope

Timeline

Pricing

Terms

Acceptance Section

⸻

PROMPT 20

CLIENT ONBOARDING ENGINE

After payment:

Create:

Client Record

Project

Tasks

Credentials Checklist

Kickoff Checklist

Asset Request Form

Automation Checklist

⸻

PROMPT 21

FULFILLMENT OS

Generate fulfillment workflows.

Website Build

CRM Setup

Automation Setup

Review Automation

SMS Automation

Pipeline Setup

Reporting Setup

Create:

Task Templates

Dependencies

Milestones

⸻

PROMPT 22

REPORTING DASHBOARD

Create executive dashboard.

Metrics:

Leads Found

Qualified Leads

Previews Generated

Emails Sent

Open Rate

Reply Rate

Bookings

Deals Won

Revenue

MRR

Pipeline Value

⸻

PROMPT 23

CLIENT SUCCESS SYSTEM

Automate:

Check-ins

Review Requests

Renewals

Upsells

Referral Requests

Health Scores

Retention Monitoring

⸻

PROMPT 24

PRODUCTIZATION ENGINE

Convert services into repeatable products.

Create:

Website Package

Growth Package

Automation Package

Revenue Infrastructure Package

AI Package

For each:

Deliverables

Pricing

Timeline

Margin Analysis

⸻

PROMPT 25

SCALE ENGINE

Design scaling plan.

Phase 1:
100 Leads

Phase 2:
1,000 Leads

Phase 3:
10,000 Leads

Phase 4:
100,000 Leads

Include:

Infrastructure Growth

Cost Analysis

Human Requirements

Automation Requirements

⸻

PROMPT 26

EXECUTIVE COMMAND CENTER

Build internal admin portal.

Features:

Lead Search

Campaign Management

Preview Management

CRM

Projects

Automation Logs

Financial Reporting

User Management

Permissions

⸻

PROMPT 27

AI AGENCY OPERATOR

Design a supervisory AI.

Responsibilities:

Monitor Campaigns

Monitor Deliverability

Monitor Lead Flow

Monitor Conversion Rates

Identify Bottlenecks

Recommend Improvements

Generate Daily Reports

Generate Weekly Reports

Generate Monthly Reports

⸻

PROMPT 28

COMPLETE DEPLOYMENT PLAN

Generate:

Day 1 Build Plan

Day 7 Milestones

Day 14 Milestones

Day 30 Milestones

Day 60 Milestones

Day 90 Milestones

Include:

Technical Tasks

Business Tasks

Sales Tasks

Operations Tasks

Success Metrics

Failure Metrics

Risk Analysis

Contingency Plans

Final Deliverable:

A complete autonomous digital agency platform capable of discovering prospects, generating opportunities, producing personalized assets, managing outreach, tracking engagement, converting prospects, fulfilling projects, and generating recurring revenue through infrastructure installations rather than one-time website sales.

This is the full master prompt pack we originally evolved toward: not a website agency, but a Digital Infrastructure Acquisition Machine where discovery, scoring, preview generation, outreach, CRM, sales, fulfillment, retention, and recurring revenue are all connected into a single operating system.