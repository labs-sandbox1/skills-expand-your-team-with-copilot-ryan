# Issue Templates Guide for Teachers

This guide explains how to use the issue templates to request changes to the Mergington High School Activities website.

## Why Use Issue Templates?

Issue templates help you clearly communicate what you need without having to know technical details. Each template guides you through providing all the information needed so that GitHub Copilot coding agent can implement your request without further clarification.

## Available Templates

When you create a new issue, you'll see these template options:

### 1. 📝 Add New Activity
**Use this when:** You want to add a new extracurricular activity to the system.

**You'll provide:**
- Activity name (e.g., "Photography Club")
- Description of what students will do
- Days it meets (Monday through Sunday)
- Start and end times
- Maximum number of participants
- Difficulty level (optional)
- Any students already signed up (optional)

**What gets created:** A new activity card on the website that students can sign up for.

---

### 2. ✏️ Modify Existing Activity
**Use this when:** You need to change details of an activity that's already in the system.

**You'll provide:**
- Which activity to modify
- What needs to change (schedule, description, etc.)
- Current value
- New value
- Reason for the change

**Common uses:**
- Change meeting times
- Update activity description
- Adjust participant limits
- Add or change difficulty level

---

### 3. 🐛 Bug Report
**Use this when:** Something isn't working correctly on the website.

**You'll provide:**
- What's not working
- What should happen instead
- Steps to reproduce the problem
- Which area is affected
- How severe the issue is

**Examples:**
- Students can't sign up for activities
- Filters don't work correctly
- Activities show wrong times
- Colors look wrong

---

### 4. 🎨 UI/Design Improvement
**Use this when:** You want to improve how the website looks or how easy it is to use.

**You'll provide:**
- Which area to improve
- Current appearance or experience
- What you'd like changed
- Why this would be better
- Priority level

**Examples:**
- Change colors to match school branding
- Make buttons easier to see
- Improve layout on mobile devices
- Add school mascots or images

---

### 5. ✨ Feature Request
**Use this when:** You want to add new functionality to the website.

**You'll provide:**
- Feature name
- Detailed description
- What problem it solves
- Who would benefit
- Example of how it would be used
- Priority level

**Examples:**
- Add email notifications when students sign up
- Create a waitlist for full activities
- Export activity schedules to PDF
- Add comments or notes to activities

---

## How to Create an Issue

1. Go to the **Issues** tab in GitHub
2. Click **New Issue**
3. Choose the template that matches your need
4. Fill out all required fields (marked with a red asterisk)
5. Optional fields can help provide more context
6. Click **Submit new issue**

## What Happens Next?

Once you submit an issue:
1. GitHub Copilot coding agent can be assigned to the issue
2. The agent will read all the information you provided
3. It will implement the changes following the acceptance criteria
4. The changes will be tested and reviewed
5. You'll be notified when the work is complete

## Tips for Writing Good Issues

### ✅ DO:
- Be specific and clear
- Provide all requested information
- Include examples when helpful
- Explain why the change is needed
- Use simple, non-technical language

### ❌ DON'T:
- Leave required fields blank
- Use technical jargon unnecessarily
- Assume the reader knows what you mean
- Combine multiple unrelated requests in one issue
- Skip the "why" - always explain the reason

## Template Sections Explained

Each template includes these key sections:

### Problem Description
Clearly explain what you need or what's wrong. Be specific!

### Acceptance Criteria
These automatically show what "done" looks like. The agent uses these to know when the work is complete.

### Implementation Hints
Technical guidance for the coding agent. You don't need to understand these - they help the agent know where to make changes.

### Context and Limitations
Important information about how the system works and any restrictions. This helps ensure solutions fit within existing constraints.

## Need Help?

- **Development Guide**: See [how-to-develop.md](../docs/how-to-develop.md) for technical setup information
- **GitHub Copilot**: Learn more at [GitHub Copilot Documentation](https://docs.github.com/en/copilot)
- **Questions**: Create a blank issue (not using a template) to ask questions

## Example: Adding a New Activity

Let's walk through an example:

**Scenario**: You want to add a "Gardening Club" that meets on Thursdays after school.

1. Click **New Issue** → Select **Add New Activity**
2. Fill in the form:
   - **Activity Name**: Gardening Club
   - **Description**: Learn about plants, grow vegetables, and maintain the school garden
   - **Days**: Thursday (select from dropdown)
   - **Start Time**: 15:30 (for 3:30 PM)
   - **End Time**: 17:00 (for 5:00 PM)
   - **Max Participants**: 15
   - **Difficulty**: Beginner
3. Click **Submit new issue**

That's it! The issue now has all the information needed for implementation.

---

## Time Format Guide

The system uses 24-hour time format internally:
- Morning: 7:00 AM = 07:00, 8:30 AM = 08:30
- Afternoon: 3:30 PM = 15:30, 5:00 PM = 17:00
- Evening: 7:00 PM = 19:00, 8:00 PM = 20:00

**Quick conversion**: For PM times, add 12 to the hour (3 PM → 15:00, 4 PM → 16:00)

---

*Last updated: December 2024*
