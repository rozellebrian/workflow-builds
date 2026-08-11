# workflow-builds

Process automation built on SharePoint Lists and Power Automate to eliminate manual tracking and notification gaps in surgical supply operations. No AI/LLM component — pure workflow engineering.

Expired Supply Waste Tracker

Mobile-first SharePoint List + Power Apps canvas app for tracking expired medical supply waste.

Two-phase capture/pricing workflow with multi-user access
Grouped monthly view for reporting
Status: In production
Value Analysis (VA) Submission Tracker

SharePoint List with two Power Automate flows automating the value analysis submission and review pipeline.

Flow 1: On new submission, emails the business director with Description, Surgeon, Additional Info, and submitter
Flow 2: On director decision (Approved/Denied), emails the original coordinator with Status, Comments, and Trial Info
Coordinator submits → business director reviews and decides → may advance to full committee
Status: Built and tested; pending business director sign-off
OR Backorder & Arrival Notifications

Power Automate flows flagging overdue OR supply orders and notifying on arrival.

Backorder alert is time-based (flags items not arrived within 7 days), not tied to Workday's backorder status field
Rebuilt from scratch after the original system broke
Status: In production
Background

Built by Brian Rozelle, Lead Surgical Supply Coordinator at AHC Shady Grove Medical Center, to close gaps in manual coordination across implant tracking, supply ordering, and review processes spanning Cerner/Discern, Workday, and SharePoint.
