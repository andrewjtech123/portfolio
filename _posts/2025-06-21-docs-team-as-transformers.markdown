---
layout: posts
title:  "Docs team as transformers"
date:   2025-06-21 19:15:27 -0500
tags: [write the docs]
author_profile: true
author: Andrew Johnston
categories: [article]
highlight_home: true
tagline: "More than meets the eye"
header:
  overlay_image: https://images.unsplash.com/photo-1618945524163-32451704cbb8?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxzZWFyY2h8Nnx8dGhlJTIwdHJhbnNmb3JtZXJzfGVufDB8fDB8fHww
  teaser:  https://images.unsplash.com/photo-1618945524163-32451704cbb8?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxzZWFyY2h8Nnx8dGhlJTIwdHJhbnNmb3JtZXJzfGVufDB8fDB8fHww
  caption: "Photo credit: [**Unsplash: Aditya Vyas**](https://unsplash.com/@aditya1702)"
description: This project demonstrates how technical documentation teams can act as “transformers”—bridging systems, teams, and user needs to turn fragmented content into cohesive, user-centered experiences.
---
# Transforming BSP Documentation into a User-Centered Web Experience

## Background

![bumblebee](https://images.unsplash.com/photo-1730130856221-e44ff6dd519a?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxzZWFyY2h8N3x8dGhlJTIwdHJhbnNmb3JtZXJzfGVufDB8fDB8fHww)

The QNX documentation team was tasked with modernizing Board Support Package (BSP) documentation by migrating from a legacy PDF-centered model to a web-based help system.

The existing experience had several structural and usability challenges:

- Documentation was presented as a flat list of user guides, with little hierarchy or discoverability.
- Release notes were authored separately in HTML and then converted to PDF, creating duplication and inefficiencies.
- Content types were dispersed and poorly connected, making it difficult for users to find related information.
- Search capabilities were limited, reducing the effectiveness of the documentation for real-world troubleshooting and exploration.

Although an initial web-based solution improved searchability, it lacked meaningful structure and contextual connections between content.

This project became an opportunity not just to migrate content, but to rethink how users discover and interact with documentation.

---

## Approach

![optimus prime](https://images.unsplash.com/photo-1774874646317-ffcee483d875?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxzZWFyY2h8N3x8b3B0aW11cyUyMHByaW1lfGVufDB8fDB8fHww)

Rather than treating this as a straightforward migration, I helped drive a user-centered redesign of the documentation experience, combining UX research, information architecture, and automation.

### 1. Challenging Assumptions Through User Research

Early internal discussions produced a proposed structure, but we recognized a critical risk:

> The team's internal mental model might not match how customers actually think.

To address this, we:

- Conducted kick-off sessions with FAEs (Field Application Engineers), who are closest to customers.
- Validated assumptions about user goals and mental models.
- Used structured discussions and feedback loops to uncover gaps in our understanding.

### 2. Using UX Methods to Design the Information Architecture

We applied UX techniques that are not traditionally part of documentation workflows:

- Created Figma prototypes to visualize potential solutions and gather feedback.
- Ran a card-sorting exercise to understand how users categorize concepts and tasks.

This revealed a key insight:

> There was no single, agreed-upon mental model among users.

Different users approached the documentation with different goals and perspectives.

This finding directly shaped the final design approach.

### 3. Designing a Flexible, Hybrid Solution

Because users thought differently, a rigid hierarchy would fail.

We implemented a hybrid information architecture that combined:

- A vendor-based organizational model for predictable structure.
- Enhanced navigation and labeling through structured DITA maps.
- Faceted search, allowing users to filter and explore content dynamically.

I also contributed to:

- Defining TOC labels and navigation structure.
- Debugging build and output issues.
- Translating IA concepts into DITA-based implementation.

### 4. Automating Large-Scale Content Migration

A major challenge was migrating hundreds of release notes from inconsistent HTML into structured DITA.

To solve this efficiently and safely, I:

- Designed reusable DITA templates with variable placeholders.
- Extracted structured data from an internal database into CSV format.
- Built a Python-based workflow to:
  - Generate files from templates.
  - Populate variables from spreadsheet data.
  - Output standardized, ready-to-build DITA files.

This approach minimized manual editing risk while ensuring consistency and scalability.

### 5. Enhancing the Platform with Modern Tooling

To complete the experience, we integrated:

- Oxygen Feedback (SaaS) for user engagement and commenting.
- A faceted search system powered by custom classification and key mappings.

---

## Results

![starscream](https://images.unsplash.com/photo-1632332425665-44ebd7f31afe?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxzZWFyY2h8OHx8c3RhcnNjcmVhbXxlbnwwfHwwfHx8MA%3D%3D)

The project delivered both technical improvements and user experience gains.

### Improved Usability and Discoverability

- Users can now navigate content through multiple pathways, including navigation, search, and filtering.
- Faceted search supports task-based exploration rather than simple keyword lookup.

### Scalable, Structured Content System

- Migration to DITA created a consistent, reusable content model.
- Release notes were standardized and aligned with the broader documentation ecosystem.

### Efficient, Low-Risk Migration

- Automation reduced manual effort and minimized data integrity risks.
- Large volumes of content were migrated with high consistency and accuracy.

### Stronger Alignment with User Needs

- UX research ensured that the final design reflects real user workflows rather than internal assumptions.
- The hybrid information architecture accommodates multiple mental models, improving accessibility for diverse audiences.

---

## Next Steps

![megatron](https://images.unsplash.com/photo-1771667176821-0baebf99e2b3?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxzZWFyY2h8Nnx8bWVnYXRyb258ZW58MHx8MHx8fDA%3D)

This project established a strong foundation, but there are clear opportunities to extend its impact.

### Iterate on Analytics and Feedback

- Use search data and user feedback (via Oxygen Feedback) to continuously refine navigation and content structure.

### Expand Faceted Search Capabilities

- Introduce additional filters and metadata to better support advanced use cases.

### Standardize UX-Driven Documentation Practices

- Apply card sorting, prototyping, and user validation techniques to future documentation projects.

### Increase Automation Coverage

- Extend template- and data-driven workflows to additional content types beyond release notes.

### Improve Cross-Product Integration

- Connect BSP documentation more seamlessly with the broader QNX ecosystem.