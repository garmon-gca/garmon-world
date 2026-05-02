<p align="center">
  <img src="assets/brand/garmon-world-mark.svg" alt="Garmon World" width="120">
</p>

# Garmon World

**Garmon** is an early research prototype for studying how internal state can shape the interpretation of an input before an LLM writes the final answer.

## Plain-Language Version

Garmon studies what happens before an LLM writes a final answer.

In a normal chatbot, the system often starts from the text request and generates a reply.

Garmon explores a different layer: first, the system reads the input as an event through an internal state model, for example calm baseline, stress, fatigue, or recovery, and forms a response direction. Only after that does the LLM turn the direction into words.

This is what this repository calls **body-born meaning before LLM speech**.

This is not meant as a new claim. It is a working term for a pre-generation layer where internal state helps shape how an input is interpreted before the LLM phrases the final answer.

The broader direction is to study how internal state can shape meaning before final LLM speech, while keeping the boundaries between meaning, choice, memory, behavior, truth, and speech explicit.

## Core Idea

In many AI projects, a request is treated mainly as a text task:

```text
request -> analysis -> plan -> answer
