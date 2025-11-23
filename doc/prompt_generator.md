# Prompt Generator

This document explains how to design clear, effective prompts for AI agents and Copilot-powered workflows. It covers structure, examples, and best practices so prompts are reproducible, actionable, and safe.

## Goals
- Produce concise prompts that give the AI enough context to act.
- Prefer structured instructions with explicit inputs and expected outputs.
- Include examples and constraints so results are predictable.

## Prompt Structure (recommended)
1. Purpose: 1-line summary of the task.
2. Inputs: required files, variables, or environment facts.
3. Steps: numbered actions the agent should perform (in order).
4. Output: exactly what should be returned or created (format, file paths).
5. Constraints: time limits, security rules, or forbidden behaviors.
6. Example: a short input → expected output pair.

Example template:
