# Medical-Research-Agent
An AI-powered Medical Research Agent that turns complex medical text into clear insights. It extracts symptoms, causes and treatments and gives accurate medical definitions using RAG.

The agent produces easy-to-understand and structured outputs for research use and for communication with patients.

# Features of this Project



# Reasons for Picking Up This Project

# 1) On a personal level, I have often struggled to understand complex medical terms and it takes me time to search about that from various websites, so I thought that this project would help me with that.

The medical text analysis requires deep reading, research and information organization, so this domain shows how the techniques learned in this course can be used to solve real-world problems that feel time-consuming and difficult.

# 2) This project consists of the concepts that were covered in the course MAT496 taught by Ajit Sir. These are the concepts from the course that I have used in this project:

Prompting

Structured Output

Semantic Search

Retrieval-Augmented Generation (RAG)

Tool Calling

LangGraph Workflow (state, nodes, transitions)

# These are the additional concepts I have also implemented:

Multi-Expert Medical Interview System

Dynamic Question Generation using Personas

Evidence Combination + Web & Wikipedia Fusion

Safety Guardrails & Medical Disclaimers

Automated PDF Report Generation

# My plans for this project

[DONE] Step 1: Setting up the project structure, environment and baseline LangGraph pipeline.

In this step, I installed dependencies, organized files, added my Open API and Tavily API keys and prepared the initial workflow skeleton to support all upcoming components.

[DONE] Step 2: Building the text summarization and medical information-extraction nodes (symptoms, causes, treatments).

This step includes the nodes that use the LLM prompts to simplify complex medical text and extract the fields like symptoms, causes and treatment options - integrated in the interview and the report workflow.

[DONE] Step 3: Implementing the RAG-based retrieval system using Tavily and Wikipedia for accurate medical definitions.

This step sets up a RAG-based pipeline that searches the trusted medical sources and returns correct definitions for the medical terms detected in the input.

[DONE] Step 4: Creating the structured output generator to combine all medical reports into a clean final format.

The generator takes the summaries, extracted fields and retrieved definitions, and then it combines them into a organized final output that is easy to read and that is suitable for the patient use or for research documentation.

[DONE] Step 5: Integrating all nodes into a unified LangGraph workflow with full interview and report generation.

For this step, I connected each node inside LangGraph, defined state transitions and I made the direct text input convert into a downloadable PDF output format.

[DONE] Step 6: Running end-to-end testing, refining the prompts and completing the final documentation.

In this step, I tested the full pipeline on many medical texts, I fixed errors, refined prompts and prepared the final documentation that can explain the workflow and usage.



