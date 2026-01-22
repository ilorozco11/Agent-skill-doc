# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Purpose

This is a documentation repository containing a comprehensive guide for evaluating and adopting GitHub Copilot agent skills in software development teams. The repository contains educational/reference material rather than executable code.

## Repository Structure

The repository consists of two primary markdown documents:

- **`github-copilot-agent-skills-guide.md`** - The main 3,000+ word guide covering agent skills introduction, decision frameworks, implementation roadmaps, best practices, and decision matrices
- **`README.md`** - Repository overview with table of contents, quick start guide, and navigation to the main content

## Content Architecture

### Main Guide Organization

The `github-copilot-agent-skills-guide.md` follows a structured decision-making framework:

1. **Introduction** - Defines agent skills and their evolution from basic code completion
2. **Understanding Agent Skills** - Catalogs 8 skill categories (Code Generation, Code Review, Testing, Documentation, Refactoring, Debugging, Architecture, Security)
3. **Decision Framework** - Multi-dimensional evaluation framework covering:
   - Project assessment (type, codebase characteristics, development phase)
   - Team considerations (size, experience mix, AI readiness)
   - Organizational context (budget, security, integration requirements)
   - Use case prioritization (quick wins matrix, pain point analysis)
4. **Implementation Roadmap** - Three-phase adoption approach (Weeks 1-4, 5-12, 13+)
5. **Best Practices** - Seven key recommendations with common pitfalls
6. **Decision Matrix Template** - Scoring system with three real-world scenarios
7. **Conclusion** - Actionable checklists and resource links

### Target Audience

The guide addresses a mixed audience:
- Technical leaders and architects (strategic decisions)
- Engineering managers (team enablement, ROI)
- Senior developers (technical evaluation)
- DevOps teams (integration considerations)
- Security teams (risk assessment)

## Working with This Repository

### Document Updates

When updating the guide or README:

- **Maintain consistency** - Both documents reference the same core concepts (8 agent skills, 3-phase implementation, decision framework)
- **Keep cross-references aligned** - README summarizes the guide structure; ensure they match
- **Preserve the framework structure** - The decision matrix scoring (1-5 scale), phase timelines, and sample scenarios are interconnected
- **Update version numbers** - Both documents include version metadata at the bottom

### Content Guidelines

- **Audience balance** - Content must be accessible to both technical and leadership audiences
- **Actionability focus** - Every section should provide concrete frameworks, not just theory
- **No time estimates** - The guide deliberately avoids phrases like "this takes 5 minutes" (uses week ranges for phases instead)
- **Evidence-based recommendations** - Specific metrics (e.g., "80%+ pilot satisfaction", "+15% test coverage")

### Key Content Elements to Preserve

- **8 Agent Skill Categories** - Code Generation, Code Review, Testing, Documentation, Refactoring, Debugging, Architecture, Security
- **3-Phase Implementation** - Foundation (1-4 weeks), Enhancement (5-12 weeks), Advanced (13+ weeks)
- **Decision Matrix Scoring** - 1-5 scale across 5 criteria (Project Fit, Team Readiness, ROI Potential, Implementation Effort, Risk Level)
- **3 Sample Scenarios** - Startup MVP, Enterprise Legacy, High-Security Financial
- **7 Common Pitfalls** - Over-reliance, neglecting review, ignoring edge cases, configuration drift, security blindness, loss of learning, documentation complacency

## Git Workflow

This repository uses:
- **Default branch**: `main`
- **Remote**: `git@github.com:ilorozco11/Agent-skill-doc.git`
- **Commit convention**: Descriptive commit messages with `Co-Authored-By: Claude <noreply@anthropic.com>`

When making changes:
1. Edit the relevant markdown file(s)
2. Stage changes: `git add <file>`
3. Commit with descriptive message
4. Push to main: `git push origin main`
