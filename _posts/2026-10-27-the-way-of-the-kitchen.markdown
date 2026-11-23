---
layout: posts
title: "The Way of the Kitchen: Agile for Technical Publications"
date: 2026-10-27 12:00:00 -0500
tags: [process, agile]
author_profile: true
author: Andrew Johnston
categories: [article]
highlight_home: true
tagline: "Service. Flow. Craft."
header:
  overlay_image: /assets/images/agile-kitchen-cover-clean.jpg
  teaser: /assets/images/agile-kitchen-cover-clean.jpg
description: "How Scrum and Kanban help technical publications teams prioritize work, visualize flow, and improve delivery."
event_name: "Write the Docs Ottawa"
event_date: 2026-10-27
event_url: "https://www.meetup.com/write-the-docs-ottawa/events/316965616/"
event_image: "/assets/images/wtd events/event-flyer-10-27-2026.jpg"
---

## Background

The Technical Publications team wanted to adopt a more structured approach to managing project work. The change formalized Agile practices already in use and integrated them more closely with Jira.

The goal was to improve visibility into project progress, identify bottlenecks earlier, reduce process inefficiencies, and make better use of existing tools.

The team identified several opportunities for improvement:

- Project work sometimes began without a clear view of the full workload.
- Bottlenecks were not always visible until late in the development cycle.
- Agile was being practiced in an ad hoc way without consistently using Agile tools and reporting.
- Project tracking required manual effort and often existed outside Jira.

This initiative was not a fundamental change in how the team works. It built on an existing Agile mindset and focused on implementing those practices more consistently.

<figure class="article-visual">
  <img src="{{ '/assets/images/kitchen-slides/kitchen-02.jpg' | relative_url }}" alt="Welcome to the kitchen slide from The Way of the Kitchen presentation">
  <figcaption>Technical writing is service work.</figcaption>
</figure>

### Why Scrumban?

I used **Scrumban**, a hybrid of Scrum and Kanban to meet the project requirements:

- **Scrum** provides planning, communication, and lightweight ceremonies.
- **Kanban** provides workflow visualization and visibility into continuous service work.

Scrumban maintains flexibility, supports ongoing requests and maintenance, adds practical planning and accountability, and reduces the risk of introducing excessive process overhead.

<figure class="article-visual">
  <img src="{{ '/assets/images/kitchen-slides/kitchen-08.jpg' | relative_url }}" alt="Diagram comparing Scrum, Kanban, and Scrumban">
  <figcaption>Scrum provides the rhythm; Kanban provides the live rail.</figcaption>
</figure>

## Approach

### Mise en Place: Prepare the Kitchen

Technical publications is service work. Like a kitchen, the team receives orders, shifts priorities, hands work across stations, and prepares a final experience for a customer who sees only the complete result.
The rush is won before the rush. Mise en place means preparing the system so the team can respond quickly when work arrives.

The process starts by capturing expected work, clarifying Jira issues, setting priorities, applying labels and filters, identifying dependencies, and preparing the board. The project backlog is the menu: the work that needs to be completed. The Product Owner maintains its priority and keeps it current.

<figure class="article-visual">
  <img src="{{ '/assets/images/kitchen-slides/kitchen-10.jpg' | relative_url }}" alt="Mise en place slide showing preparation steps for the kitchen">
  <figcaption>Good service begins with preparation.</figcaption>
</figure>

### Backlog Organization

Backlog organization keeps the order book understandable. It ensures that work is clearly defined, appropriately prioritized, and ready to move without anything falling through the cracks.

### Project Planning

Project planning replaces traditional sprint planning. It is the pre-service meeting where the team grooms the backlog, captures expected work, aligns on priorities, and confirms how work will be tracked.

Planning gives special attention to Jira labels, filters, and board organization so that reporting remains meaningful throughout the project.

### Weekly Standups

Instead of frequent status meetings, team members provide asynchronous weekly updates. Each update is like calling out to the next station:

1. What did I do last week?
2. What do I plan to do this week?
3. Are there any obstacles or blockers?

The updates also make it easier to identify work lingering in Analysis or Review, surface bottlenecks, and coordinate additional help.

### Project Retrospectives

At the conclusion of major milestones or projects, the team steps back from the pass and reviews what worked, what did not, and what it should start, stop, or continue doing.

The goal is continuous improvement rather than assigning blame.

### Using Jira

I changed the way the team uses Jira as the primary system for tracking, managing, and visualizing work. It became the kitchen rail: the place where every order is visible and where work moves from waiting, to working, to finished.

Kanban boards visualize the documentation lifecycle with status columns, swimlanes, quick filters, work-in-progress limits, reporting dashboards, and estimates on Jira issues. Scrum boards remain available for reference but are not the primary tracking mechanism.

<figure class="article-visual">
  <img src="{{ '/assets/images/kitchen-slides/kitchen-11.jpg' | relative_url }}" alt="Kanban board slide showing work moving through documentation stages">
  <figcaption>One shared board shows what is waiting, moving, backed up, and done.</figcaption>
</figure>

### Team Responsibilities

Team members maintain Jira issues by applying labels, updating issue information, moving work through the workflow, and estimating work directly on issues. Each person owns a station and keeps its tickets current.

They provide weekly updates and monitor flow for stalled or blocked work. As release dates approach, project planning may occur more frequently to keep work aligned with delivery goals.

### Improving on the Existing System

The team's existing documentation plans already tracked workflow stages, bottlenecks, effort, ownership, functional areas, maintenance and feature work, and documentation types.

However, some of this information was maintained separately from Jira issues. The new system brings estimates, workflow status, workload views, and reporting into one kitchen, reducing manual updates and improving teamwork.

<figure class="article-visual">
  <img src="{{ '/assets/images/kitchen-slides/kitchen-05.jpg' | relative_url }}" alt="Slide showing the previous handwritten documentation order book">
  <figcaption>The old system worked, but it required the team to maintain the kitchen view by hand.</figcaption>
</figure>

## Results

The approach provides several improvements:

- Swimlanes separate Jira work types.
- Quick filters support product-area views.
- Workflow status is visible directly on the board.
- Reports update automatically as work progresses.
- Cumulative flow reports, workload reports, and completion trends expose bottlenecks.
- Estimates remain directly on issues.
- Real-time dashboards reduce administrative work.

### Work-in-Progress Limits

WIP limits prevent the kitchen from accepting more orders than it can complete. When a bottleneck occurs, the team works together to move blocked work forward before starting new work.

This creates a pull-based workflow rather than a push-based one and makes collaboration part of normal delivery.

### Fewer Meetings

Jira dashboards and weekly updates provide visibility into project health. Managers can review reports, identify trends, and intervene when needed rather than relying on frequent status meetings.

The new process will be introduced during the SDP 8.0.4 and SDP 8.0.5 project cycles and refined as the team gains experience with the workflow.

<figure class="article-visual">
  <img src="{{ '/assets/images/kitchen-slides/kitchen-06.jpg' | relative_url }}" alt="Slide explaining what Scrum gives technical publications teams">
  <figcaption>Scrum creates a repeatable rhythm for planning and reflection.</figcaption>
</figure>

<figure class="article-visual">
  <img src="{{ '/assets/images/kitchen-slides/kitchen-07.jpg' | relative_url }}" alt="Slide explaining what Kanban gives technical publications teams">
  <figcaption>Kanban exposes flow, limits, and bottlenecks across the kitchen.</figcaption>
</figure>

## Next Steps

- Continue refining the backlog: the menu should remain clear and prioritized.
- Use cumulative flow, workload, and completion reports to find recurring bottlenecks.
- Improve WIP limits and pull-based coordination so stations do not become overwhelmed.
- Extend the shared operating model to additional product areas and release milestones.
- Retain ceremonies only while they improve service.

## Resources

<div class="resource-gallery" aria-label="Presentation resources">
  <a class="resource-gallery__card" href="{{ '/assets/pdfs/Agile_Project_Management_The_Way_of_the_Kitchen_Ink_Expanded.pdf' | relative_url }}" target="_blank" rel="noopener">
    <img src="{{ '/assets/images/agile-kitchen-cover-clean.jpg' | relative_url }}" alt="The Way of the Kitchen presentation cover">
    <span class="resource-gallery__content">
      <span class="resource-gallery__eyebrow">Slide deck</span>
      <span class="resource-gallery__title">View the presentation</span>
      <span class="resource-gallery__action">Open PDF &rarr;</span>
    </span>
  </a>

  <a class="resource-gallery__card" href="https://www.meetup.com/write-the-docs-ottawa/events/316965616/" target="_blank" rel="noopener">
    <img src="{{ '/assets/images/wtd events/event-flyer-10-27-2026.jpg' | relative_url }}" alt="Write the Docs Ottawa event flyer">
    <span class="resource-gallery__content">
      <span class="resource-gallery__eyebrow">Write the Docs Ottawa</span>
      <span class="resource-gallery__title">View the meetup event</span>
      <span class="resource-gallery__action">Open Meetup &rarr;</span>
    </span>
  </a>
</div>
