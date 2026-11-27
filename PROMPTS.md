# Agentic Engineering — Prompt Library

## 1. Business Problem Analysis

Analyze the business challenge.

Identify:
- Business objective
- Target users
- Inputs and expected outputs
- Functional requirements
- Constraints and assumptions
- Measurable success criteria

Identify ambiguities and ask clarifying questions.
Do not implement anything yet.

## 2. Architecture Selection

Compare the following approaches:
- Deterministic workflow
- Single-agent architecture
- Multi-agent architecture

Recommend the simplest sufficient architecture.

Explain:
- Why this architecture is appropriate
- Where an LLM is necessary
- Where deterministic logic is sufficient
- Trade-offs and risks
- Required tools and integrations

Avoid unnecessary complexity.

## 3. MVP Definition

Define the smallest end-to-end MVP that
demonstrates business value within the
available time.

Separate:
- Must-have features
- Nice-to-have features
- Out-of-scope features

Define clear acceptance criteria.

## 4. Specification

Create a technical specification covering:
- Functional requirements
- System architecture
- Data flow
- Component responsibilities
- Input and output schemas
- API contracts
- Error handling
- Acceptance criteria

Save the specification in docs/spec.md.

Do not implement the solution yet.

## 5. Team Work Distribution

Decompose the implementation into independent
workstreams that developers can execute
in parallel.

Define:
- Component ownership
- Shared interfaces
- Data contracts
- Dependencies
- Integration checkpoints

Minimize merge conflicts and duplicated work.

## 6. Implementation Plan

Based on the approved specification,
create an incremental implementation plan.

For each task, define:
- Objective
- Files to create or modify
- Dependencies
- Acceptance criteria
- Verification steps

Save the plan in docs/plan.md.

Wait for approval before implementation.

## 7. Implementation

Implement the assigned task according to
the approved specification and plan.

Follow these principles:
- Keep the implementation simple.
- Respect existing component contracts.
- Do not modify unrelated files.
- Handle errors explicitly.
- Never hardcode secrets.
- Write and run relevant tests.

Report changes, test results, and limitations.

## 8. LLM Integration

Design and implement the LLM integration.

Consider:
- Model selection
- Prompt design
- Structured output
- Output validation
- Timeouts and retries
- Token usage and cost
- Failure handling
- Prompt injection risks

Use environment variables for credentials.

## 9. Evaluation

Create an evaluation strategy for the AI system.

Include:
- Representative test cases
- Expected outputs
- Edge cases
- Failure scenarios
- Quality metrics
- Automated evaluation where practical

Distinguish deterministic tests from
LLM output evaluations.

## 10. Code Review

Review the implementation against
the approved specification.

Check:
- Correctness
- Architecture compliance
- Security
- Error handling
- Test coverage
- Unnecessary complexity
- Integration issues

Prioritize findings by severity.
Do not modify code until findings are reviewed.

## 11. Demo Preparation

Prepare a concise demonstration covering:
- Business problem
- Proposed solution
- Architecture
- End-to-end workflow
- Evaluation results
- Business value
- Current limitations
- Future improvements

Prioritize a working demonstration over
additional unfinished features.