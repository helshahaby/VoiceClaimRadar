# VoiceClaimRadar
ClaimRadar uses a professional voice agent to search the live web, verify opportunities, rank them by fit and urgency, and prepare the user’s next action.
# ClaimRadar

ClaimRadar is a voice-first opportunity intelligence agent for students, job seekers, researchers, founders, and builders.

It helps users discover time-sensitive opportunities such as hackathons, internships, grants, scholarships, startup programs, certification vouchers, fellowships, and research calls. The agent searches the live web, verifies source details, ranks results by fit and urgency, and prepares the next action.

## Short Description

ClaimRadar is a voice-first opportunity radar that helps users find verified hackathons, internships, grants, fellowships, and scholarships, then ranks each result and prepares the next action before deadlines disappear.

## Demo

- Lovable app: https://ai-palette-chooser.lovable.app/
- Demo video: https://youtu.be/wzWk1DUPPvc

## Problem

Good opportunities are scattered across event pages, job boards, university pages, PDFs, newsletters, and social posts. People often miss deadlines because discovery, verification, and application preparation are manual.

## Solution

ClaimRadar lets the user speak or type a goal. The agent then searches live sources, extracts key details, scores each opportunity, and creates an action plan.

Example prompt:

```text
Find AI, robotics, automotive, and hackathon opportunities in Sweden, Europe, or online this month.
```

## Main Features

- Professional voice-agent interface
- Mic, mute, captions, and transcript controls
- Secure setup for Nebius Token Factory, Tavily, and ElevenLabs API keys
- Live opportunity search and extraction
- Fit, urgency, impact, effort, and confidence scoring
- Saved opportunities and application status tracking
- Call history with transcripts and follow-up tasks
- Draft email and draft application answer actions

## Technology Plan

| Service | Role |
| --- | --- |
| Tavily | Live search, extraction, crawling, and source verification |
| Nebius Token Factory | Open-model reasoning, ranking, summarization, scoring, and drafting |
| ElevenLabs | Professional voice-agent interaction |

## Demo Profile

Name: Hossam Elshahaby  
Location: Gothenburg, Sweden  
Background: Electrical and Software Engineer with embedded systems, automotive, robotics, AI, C/C++, Python, ADAS, AUTOSAR, ISO 26262, and hackathon experience.

## Opportunity Scoring

Each opportunity receives:

- Fit score from 0 to 100
- Urgency score from 0 to 100
- Impact score from 0 to 100
- Effort level: Low, Medium, or High
- Confidence level: Low, Medium, or High

## Impact

ClaimRadar helps people act on opportunities before deadlines disappear. It is especially useful for students, immigrants, researchers, and builders who do not already have strong networks or dedicated opportunity scouts.

## Business Model

- Free personal search
- Pro monitoring and application support
- University and career-center dashboards
- Community and accelerator opportunity intelligence

## Status

Prototype prepared for the Builders & Brews / Nebius + Tavily AI builder event.
