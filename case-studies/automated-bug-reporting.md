# Automated Bug Reporting

## Overview

### Context

As part of improving the development and testing workflow, I worked on an automated bug reporting flow for **developer mode**.

The functionality was intended for internal development and QA use and was not available to regular application users.

The goal was to reduce the manual effort required to collect screenshots and technical information and make issue reporting faster and more consistent.

### Objective

The main objective was to create a simple internal tool that allowed developers and QA to report an issue directly from the application while automatically including relevant diagnostic information.

Because the functionality was restricted to developer mode, the reporting flow was designed specifically for internal development and testing workflows rather than end users.

The workflow was designed to:

* Capture the current application state
* Take a screenshot when an issue was reported
* Include relevant information from the App Health Dashboard
* Allow the user to add additional context when needed
* Combine the information into a single report
* Send the report directly to the team's Microsoft Teams channel

---

## User Flow

The reporting flow was designed to be simple and require only a few actions:

**Shake Screen → Screenshot → Preview → Add Details (Optional) → Send → Teams**

When the user shakes the device, the application automatically takes a screenshot and opens a preview screen.

From the preview, the user can:

* Review the captured screenshot
* Add a title
* Add a description
* Send the report

The title and description are optional, allowing the user to provide additional context when needed.

The functionality was available only in developer mode, so the flow was intended for developers and QA rather than regular application users.

---

## Requirements Analysis

I analyzed what information would be useful when reporting a bug and how the information could be collected automatically.

The reporting flow needed to:

* Detect the user's reporting action
* Capture a screenshot
* Collect relevant application and diagnostic information
* Present the captured information for review
* Allow the user to add additional details
* Combine the information into a structured report
* Send the report to the team's communication channel

The solution was designed to build on the information already available through the App Health Dashboard.

---

## Automated Bug Report

When the user triggers the reporting action by shaking the device, the application automatically captures a screenshot and opens a preview screen.

The preview also contains relevant information collected from the App Health Dashboard.

Before sending the report, the user can optionally add a title and description to provide additional context about the issue.

Once the user presses **Send**, the report is sent directly to the team's Microsoft Teams channel through a webhook.

The complete workflow is:

**Issue Occurs → Shake Screen → Screenshot + Diagnostic Information → Preview → Optional Title & Description → Send → Teams**

This provided developers and QA with a structured report containing both visual and technical context without requiring them to collect the information manually.

---

## Teams Integration

The generated report was sent directly to Microsoft Teams using a webhook.

This allowed the report to reach the team without requiring the user to manually prepare a message, attach a screenshot, and copy diagnostic information.

Instead, the user could review the generated report, add any additional context if needed, and press **Send**.

This created a direct connection between the application and the team's communication channel.

---

## Development & Implementation

I was responsible for implementing the reporting flow and integrating it with the existing application functionality.

The implementation connected several pieces of functionality:

* User-triggered bug reporting
* Screenshot capture
* App Health Dashboard information
* Preview functionality
* Optional title and description
* Report generation
* Teams webhook integration

The solution was designed to reuse information already available within the application rather than requiring the user to enter the information manually.

---

## Testing & Validation

I tested the reporting flow to verify that:

* The reporting action was triggered correctly
* The screenshot was captured
* The preview was displayed correctly
* The expected application information was included
* The title and description could be added when needed
* The report was generated correctly
* The report was successfully sent to Teams
* The overall flow worked as expected from the user's perspective

I also validated the final behavior as part of the overall application testing and UAT process.

---

## Business & Product Value

The main value of the solution was reducing friction in the bug reporting process.

Instead of manually collecting information from different places, the team could receive a report containing relevant context automatically.

This helped make issue reporting:

* Faster
* More consistent
* Easier to investigate
* Less dependent on manual information collection

The optional title and description also gave developers and QA the flexibility to provide additional context when the automatically collected information was not enough.

Because the functionality was restricted to developer mode, it could provide detailed technical information without exposing internal diagnostic functionality to regular application users.

The project demonstrates how a technical solution can be designed around a practical workflow problem rather than simply adding another application feature.

---

## What This Experience Demonstrates

* Requirements analysis
* Problem identification
* Workflow analysis
* Technical-to-business translation
* User-focused solution design
* Process improvement
* Automation
* API/webhook integration
* Testing and validation
* User experience thinking
* Product-oriented thinking
