# Real-Time Agentic Voice AI

## Problem

A production voice agent is more than speech-to-text plus an LLM. It must manage telephony, streaming audio, conversation state, business grounding, tool permissions, latency and failure behavior in real time.

## What I built

A conversational architecture connecting:

```text
phone / SIP
  -> streaming audio
  -> speech processing
  -> LLM reasoning
  -> grounded business knowledge
  -> permissioned tool execution
  -> spoken response
```

The system includes explicit controls for:

- conversation state
- business-fact access
- tool authorization
- preflight checks
- human / safe routing boundaries
- no-call and standby modes
- production failure handling

## Performance work

A representative commerce read path improved from approximately:

- **103.6 ms cold**
- to approximately **13 ms warm**

The point of the optimization was end-to-end conversational responsiveness, not an isolated microbenchmark.

## Production engineering

The voice system is integrated with Oracle-hosted services and Docker-based infrastructure. Deployment work includes service-principal boundaries, health checks, canary/standby flows and explicit release gates.

## Engineering themes

- latency as a product constraint
- tool use with authorization boundaries
- grounding before action
- separation of model capability from business authority
- fail-closed preflight behavior
- production observability and rollback
