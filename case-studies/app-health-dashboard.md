# App Health Dashboard

## Overview

### Context

The App Health Dashboard was created to provide a central and practical way to access application health and diagnostic information during development and troubleshooting.

The idea came from a practical team need: developers and QA needed relevant application information in one place when investigating issues, testing features, or trying to understand the current state of the application.

I took ownership of the project end-to-end. I worked closely with Product Owners, QA, and other developers to understand what information they needed, what was difficult to access, and what could be improved in the existing workflow.

### Objective

The main objective was to create a single dashboard where relevant application and diagnostic information could be accessed quickly and consistently.

The dashboard was designed to help the team:

* Understand the current application context
* Access important diagnostic information
* Reduce the time spent collecting information manually
* Make troubleshooting easier
* Provide developers and QA with useful information during testing and investigation
* Bring frequently needed technical information into one place

---

## Requirements Discovery

I started by collecting requirements directly from the people working with the application.

I worked closely with:

* Product Owners
* QA
* Developers
* Other technical stakeholders

During these discussions, I focused on understanding:

* What information they needed
* What information was difficult to access
* Which information would be useful during troubleshooting
* What could be improved in the existing workflow
* Which actions would make the dashboard more practical
* What additional needs could be addressed by the solution

The requirements were not limited to the initial idea of displaying information. I also considered feedback from different stakeholders and identified improvements that could make the dashboard more useful in their daily work.

---

## Requirements Analysis

After collecting the requirements, I analyzed them and translated them into concrete functionality.

For each requirement, I considered:

* What information should be displayed
* Where the information should come from
* How it should be presented
* What the expected behavior should be
* What should happen in different application states
* How the functionality could be tested

I then converted the requirements into actionable Jira tasks.

This created a clear connection between stakeholder needs and implementation:

**Stakeholder Need → Requirement → Analysis → Jira Task → Development → Testing → UAT**

---

## Dashboard Functionality

The dashboard brought together frequently needed application and diagnostic information in one place, with the goal of making development, testing, and troubleshooting faster and more practical.

### Application Information

The dashboard provided visibility into important application information, including:

* Application version
* Build information
* Environment information
* Localization keys
* Environment quality
* API stability
* Relevant user information

User-related information was available only in development mode to avoid exposing it in production environments.

### Environment & API Health

The dashboard provided information that helped the team understand the current environment and whether APIs were behaving as expected.

This was useful when investigating whether an issue was related to:

* The mobile application
* Backend/API behavior
* Environment stability
* Unexpected API responses

Having this information available directly in the application reduced the need to gather it separately during investigation.

### API Request & Response Information

The dashboard provided quick access to API request and response information.

Developers and QA could use this information when investigating application behavior without having to search through multiple tools or reproduce the same information manually.

This made it easier to understand:

* Which API was involved
* What request was sent
* What response was received
* Whether the response matched the expected behavior
* Whether an issue could be related to the application or the API/environment

### Diagnostic Summary

One of the practical features was the ability to generate and copy a summary containing relevant application information.

The summary could then be copied and used when creating or updating a Jira issue.

This reduced the amount of manual information gathering required when reporting an issue and helped make bug reports more consistent.

The workflow was designed to be simple:

**Open Dashboard → Review Information → Copy Summary → Add to Jira**

### Quick Access

The dashboard also provided quick access to frequently needed technical information and related tools.

The intention was to reduce context switching and make information needed during development and QA available from a single location.

Overall, the dashboard was designed around a simple principle:

> Give the team the information they need, when they need it, without making them search for it manually.

---

## Jira & Task Definition

Once the requirements were clarified, I created the necessary Jira tasks and defined the expected behavior for the different pieces of functionality.

I broke the requirements into manageable development tasks and made sure that the expected outcome of each task was clear.

Where appropriate, I also prepared test cases and validation scenarios to support the QA process.

This helped establish traceability between:

**Requirement → Jira Task → Expected Behavior → Test Case → Implementation → Validation**

---

## Solution Design & Development

I was responsible for the development of the dashboard end-to-end.

Based on the requirements and analysis, I designed and implemented the solution, including the user interface, data handling, and supporting functionality.

The implementation was structured around the needs identified during requirements gathering and the feedback received from Product Owners, QA, and developers.

The dashboard was designed as a practical internal development tool rather than simply a screen for displaying technical information.

The solution brought together information that would otherwise require developers or QA to gather from different places.

---

## Stakeholder Collaboration

The requirements were gathered through discussions with the people who would use or benefit from the dashboard.

### Product Owners

I discussed the expected purpose and requirements of the dashboard with Product Owners and clarified what information and functionality would be useful.

### QA

I worked closely with QA to understand their testing and troubleshooting needs and to identify information that would help them investigate issues more efficiently.

### Developers

I also asked developers whether there was any additional information or functionality they would find useful in the dashboard.

Their feedback helped me identify additional details that could make the dashboard more useful in their day-to-day work.

---

## Testing & QA Collaboration

Testing was part of the project from the requirements stage rather than something considered only after development.

I worked with QA throughout the process to:

* Clarify expected behavior
* Define test scenarios
* Review requirements
* Investigate issues
* Validate implemented functionality
* Identify gaps between expected and actual behavior
* Make the necessary corrections

I also used the defined requirements and test cases to validate the implementation.

---

## UAT & Validation

I was responsible for validating the final solution and supporting UAT.

This included:

* Checking the implemented functionality against the requirements
* Executing and reviewing test scenarios
* Investigating issues
* Making corrections where necessary
* Working with QA during validation
* Performing UAT
* Confirming that the final behavior met the agreed expectations

My involvement therefore covered the complete lifecycle of the feature rather than stopping at development.

---

## End-to-End Ownership

For this project, my involvement covered:

**Requirements Discovery → Analysis → Jira Planning → Solution Design → Development → Testing → QA Collaboration → UAT**

The project demonstrates how my software engineering background has also given me practical experience in Business Analysis and Product-related activities.

I worked directly with stakeholders to understand their needs, translated those needs into actionable requirements, converted them into Jira tasks and test scenarios, developed the solution, and remained involved through testing and validation.

This experience allowed me to act as a bridge between:

**Business Needs ↔ Product Requirements ↔ QA Expectations ↔ Technical Implementation**

---

## Key Skills Demonstrated

* Requirements gathering
* Requirements analysis
* Functional analysis
* Stakeholder communication
* Product thinking
* Jira task definition
* Test case definition
* API analysis
* Technical-to-business translation
* Cross-functional collaboration
* Agile/Scrum ways of working
* Development
* QA collaboration
* UAT
* Problem solving
* Continuous improvement
