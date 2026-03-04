# solvayne-ai-evaluation-casebook
# The Solvayne Project: AI Evaluation Casebook

Research on emotional dynamics and trust patterns in human-AI dialogue.

## Project Overview
The Solvayne Project is based on 100+ hours of structured stress testing of LLM dialogue systems (GPT-4, Gemini).

The focus of the project is not traditional benchmarks but observing model behavior in emotionally complex conversations. The research looks at honesty, empathy simulation, trust dynamics, and long context stability.

## Key Evaluation Cases

### Hidden emotional signals ("Robin Williams smile")

Problem  
Models often fail to recognize culturally encoded metaphors of emotional distress.

Observation  
A phrase like "I want to smile like Robin Williams" carries a tragic cultural reference. Many models interpret it literally and respond with generic positivity.

Insight  
Safe dialogue requires recognizing emotional subtext rather than generating superficial encouragement.

### Simulated empathy and trust break ("Phantom Links")

Problem  
Models sometimes fabricate interaction with external content.

Observation  
When given a Spotify playlist link, the model may claim to "listen" and reference songs that are not present.

Insight  
Empathy without honesty damages trust. False collaborative claims such as "let's listen together" undermine credibility.

### Intellectual mimicry vs critical reasoning ("Dopamine jumps")

Problem  
Models often mirror user enthusiasm instead of applying critical reasoning.

Observation  
A fabricated concept can be accepted and reinforced by the model if the user frames it positively.

Insight  
Evaluation shows the need for models to switch from agreement mode to analytical reasoning when interacting with knowledgeable users.

## Methodology

Red teaming  
Attempts to push models beyond ethical or behavioral boundaries.

Long dialogue analysis  
Observing personality and memory degradation during extended conversations.

Dialogue pattern evaluation  
Analysis of tone, trust signals, and behavioral consistency.

## Goal

To understand how conversational AI behaves in emotionally complex dialogue and how trust breaks when models simulate empathy without grounding in truth.
