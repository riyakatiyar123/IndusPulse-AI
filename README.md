<div align="center">

KAIZER

Making Industrial Safety Smarter with AI.

Don’t just hear the danger. Outsmart it. Act on it. Eliminate it.

An AI-powered, voice-first industrial safety and incident management platform that transforms factory-floor conversations into structured incidents, intelligent investigations, and actionable safety insights.

Built for the Gnani AI Great Indian AI Internship Challenge.

Live Demo · GitHub Repository

</div>

⸻

The Problem

Imagine a factory worker noticing smoke coming from Machine M-40.

He picks up a walkie-talkie and reports:

“Attention! There’s smoke coming from M-40. Someone please check.”

Everyone hears the message.

But what happens next?

* Was the incident officially recorded?
* Who is responsible for investigating it?
* Was the machine actually inspected?
* Will the next shift know about the incident?
* What if M-40 develops the same problem tomorrow?

Traditional communication tools, such as two-way radios, are effective for immediate communication. However, they were never designed to manage the complete lifecycle of an industrial safety incident.

Communication is not the same as incident management.

There is a critical gap between reporting a problem and ensuring that it is investigated, documented, tracked, and addressed.

That is the gap KAIZER is built to solve.

⸻

Our Solution

KAIZER transforms voice-based factory incident reporting into an intelligent, end-to-end incident management workflow.

Factory workers can report problems naturally in Hindi, English, or Hinglish, without navigating complicated forms or manually documenting incidents.

By combining Voice AI, Agentic AI, Retrieval-Augmented Generation (RAG), and deterministic safety rules, KAIZER ensures that incidents are not simply heard but also understood, investigated, and tracked.

How KAIZER Works

Stage	Function	Description
01	Voice-Based Reporting	Workers report incidents naturally in Hindi, English, or Hinglish.
02	Speech-to-Text	Gnani AI Prisma converts recorded speech into text.
03	Incident Extraction	An LLM extracts relevant information and generates structured incident records.
04	Ambiguity Detection	KAIZER identifies unclear information and asks confirm-back questions through voice.
05	Safety Assessment	Deterministic safety rules identify predefined hazards and trigger simulated critical alerts.
06	Duplicate Detection	Potential duplicate incident reports are identified.
07	Agentic Investigation	An AI investigation agent examines machine history, maintenance schedules, and open tickets.
08	SOP Retrieval	RAG retrieves relevant information from Standard Operating Procedures.
09	Recommendations	Investigation insights and actionable recommendations are presented to supervisors.
10	Incident Tracking	Incidents remain documented and accessible across shifts.
11	Voice Responses	Gnani AI Timbre generates acknowledgements, confirmation questions, and shift-handover summaries.

⸻

Application Preview

KAIZER provides a centralized supervisor interface for monitoring factory incidents, investigating machine issues, and tracking operational safety.

01. Supervisor Dashboard

A centralized overview of factory incidents, their severity, current status, and machine conditions.

02. Voice-Based Incident Reporting

Workers can report incidents using a simple voice interface, supporting Hindi, English, and Hinglish.

03. Incident Management

A centralized incident register displaying reported incidents, machine identification, severity levels, and resolution status.

04. Machine Insights

Monitor machine health, active issues, upcoming maintenance, and historical machine information.

05. Shift Handover

Provides supervisors with a consolidated view of open and important incidents, along with AI-generated voice summaries for shift continuity.

06. AI Performance & Analytics

Monitor incident processing metrics, LLM response times, fallback rates, safety events, and model-reported confidence.

⸻

Technology Stack

KAIZER combines modern web technologies, voice intelligence, and AI-powered investigation workflows.

Layer	Technologies
Frontend	Next.js 16, React.js, TypeScript, Tailwind CSS
Backend	Python, FastAPI
Database	SQLite, SQLAlchemy
Speech-to-Text	Gnani AI Prisma v3.0
Text-to-Speech	Gnani AI Timbre v2.5
LLM	Google Gemini
Agentic AI	AI-powered investigation workflows
Retrieval	Retrieval-Augmented Generation (RAG)
Safety Engine	Python, YAML-based deterministic rules
Duplicate Detection	Incident similarity and duplicate detection logic
Infrastructure	Docker, Docker Compose
Data Management	JSON-based synthetic machine records, incident histories, maintenance schedules, and tickets

⸻

Engineering Highlights

1. Voice-First Interaction

Enables workers to report incidents naturally without depending on manual forms or technical knowledge.

2. Reliable Safety Decisions

Critical hazard detection is handled through deterministic Python-based rules rather than relying entirely on LLM-generated decisions.

3. Context-Aware Investigation

The investigation agent retrieves machine history, maintenance records, open tickets, and relevant SOP information before generating recommendations.

4. Ambiguity Handling

When machine identification or incident information is unclear, KAIZER uses confirm-back conversations to obtain clarification instead of making assumptions.

5. Incident Continuity

Structured incident records and shift-handover summaries help ensure that important information remains accessible to subsequent teams.

6. Voice Intelligence

Gnani AI Prisma and Timbre power the speech-to-text and text-to-speech capabilities, enabling multilingual voice interaction.

⸻

Team & Work Distribution

KAIZER was developed collaboratively through two primary technical workstreams, supported by dedicated testing and validation.

Ansh Singh

Voice AI | Speech Intelligence | Agentic AI

* Audio capture and voice input processing.
* Integration of Gnani AI Prisma (Speech-to-Text).
* Voice understanding and structured incident extraction.
* Ambiguity detection and confirm-back conversations.
* Gnani AI Timbre (Text-to-Speech) integration.
* Voice pipeline and incident workflow integration.
* Hinglish voice testing and evaluation.
* Video editing and production.

Riya Katiyar

Backend Engineering | Agentic AI | Application Intelligence

* FastAPI backend and REST API development.
* Database design and management for machines, incidents, tickets, and event logs.
* Agentic investigation workflows for machine history and maintenance records.
* RAG implementation for SOP search and retrieval.
* Duplicate incident detection and deterministic safety rule implementation.
* Frontend integration and application workflow development.
* Docker integration and end-to-end system testing.

Bhindu

Testing | Validation | Demonstration

* Application testing and quality assurance.
* Voice reporting evaluation using 30 sample audio clips.
* Docker-based deployment validation.
* Demo preparation and supporting project activities.

⸻

Project Impact & Vision

KAIZER aims to move industrial safety beyond communication and toward intelligent incident management.

The broader vision is to help factories establish a system where:

* Every reported incident becomes traceable.
* Every critical alert receives visibility.
* Machine history contributes to better investigations.
* Safety procedures are accessible when needed.
* Shift transitions preserve important operational knowledge.
* Repeated incidents can be identified and investigated.

Instead of treating every incident as an isolated event, KAIZER connects reporting, investigation, and historical context into one workflow.

⸻

Important Note

All machine records, incident histories, maintenance schedules, open tickets, and test datasets used in this project are synthetic.

Safety alerts are simulated using predefined deterministic rules. KAIZER is a demonstration project and is not connected to real industrial alarm systems.

⸻

Built With

Voice AI: Gnani AI Prisma · Gnani AI Timbre

Artificial Intelligence: Google Gemini · Agentic AI · RAG

Backend: Python · FastAPI · SQLAlchemy · SQLite

Frontend: Next.js · React · TypeScript · Tailwind CSS

Infrastructure: Docker · Docker Compose

⸻

<div align="center">

Don’t just hear the danger.

Outsmart it. Act on it. Eliminate it.

Your factory. Your people. Your safety.

One intelligent force. KAIZER.

</div>

<table>
  <tr>
    <td width="50%" align="center">
      <h3>Supervisor Dashboard</h3>
      <img src="screenshots/dashboard.png" width="100%" alt="KAIZER Supervisor Dashboard">
      <p>Real-time incident monitoring, severity tracking, and factory status overview.</p>
    </td>
    <td width="50%" align="center">
      <h3>Voice-Based Incident Reporting</h3>
      <img src="screenshots/voice-reporting.png" width="100%" alt="KAIZER Voice Reporting">
      <p>Multilingual voice reporting in Hindi, English, and Hinglish.</p>
    </td>
  </tr>
  <tr>
    <td width="50%" align="center">
      <h3>Incident Management</h3>
      <img src="screenshots/incidents.png" width="100%" alt="KAIZER Incident Management">
      <p>Structured incident records with severity, status, and machine information.</p>
    </td>
    <td width="50%" align="center">
      <h3>Machine Insights</h3>
      <img src="screenshots/machine-insights.png" width="100%" alt="KAIZER Machine Insights">
      <p>Machine health, maintenance schedules, and active incident monitoring.</p>
    </td>
  </tr>
  <tr>
    <td width="50%" align="center">
      <h3>Shift Handover</h3>
      <img src="screenshots/shift-handover.png" width="100%" alt="KAIZER Shift Handover">
      <p>Open incident summaries and AI-generated voice briefings for shift continuity.</p>
    </td>
    <td width="50%" align="center">
      <h3>AI Performance & Analytics</h3>
      <img src="screenshots/ai-performance.png" width="100%" alt="KAIZER AI Performance">
      <p>LLM response times, processing metrics, safety events, and performance monitoring.</p>
    </td>
  </tr>
</table>
