# Day 03: Branching Strategies

## Three strategies I learned:
1. GitFlow: legacy, too complex for CI/CD
2. GitHub Flow - simple, good starting point
3. Trunk-Based - best for CI/CD and AI/ML teams

## Key insight:
Short-lived branches + frequent merges = true CI
long-lived branches + rare merges = broken CI

## Feature Flags
Feature flags let you merge incomplete features to main.
Code is deployed but hidden behind if/else switch.
Flip the flag to enable - no redeployment needed.

