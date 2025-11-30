# Medical-Research-Agent
An AI-powered Medical Research Agent that turns complex medical text into clear insights. It extracts symptoms, causes and treatments and gives accurate medical definitions using RAG.

The agent produces easy-to-understand and structured outputs for research use and for communication with patients.

# Features to be covered in this project:

Prompting (4+ different types)

Structured Output (Pydantic models)

Semantic Search (Tavily + Wikipedia)

RAG (Retrieval Augmented Generation)

Tool Calling (Multiple APIs)

LangGraph (2 complex graphs, 8+ nodes, conditional edges)

# Steps followed in this project:

Step 1: Environment Setup

Step 2: Data Models

Step 3: Text Summarization Node

Step 4: Information Extraction Node

Step 5: Retrieval Node (RAG)

Step 6: Structured Output Generator

Step 7: Workflow Graph (LangGraph)

Step 8: Helper Functions

Step 9: End-to-End Workflow Testing

Step 10: Interface / API Integration

Step 11: Final Documentation and Integration with Word Document

Step 12: Final Testing & Debugging

# Reason for Picking Up This Project

This project consists of the concepts that were covered in the course MAT496 taught by Ajit Sir.

So I have used the concepts like prompting, structured output, semantic search, RAG and tool-calling to build this multi-step automated agent.

The node-based workflow of Langraph is ideal for chaining tasks like summarization, extraction, retrieval and structured generation.

On a personal level, I have often struggled to understand complex medical terms and it takes me time to search about that from various websites, so I thought that this project would help in that sense as well.

The medical text analysis requires deep reading, research and information organization, so this domain shows how the techniques learned in this course can be used to solve real-world problems that feel time-consuming and difficult.

# My plans for this project

[TODO] Step 1: Setting up the project structure, environment and baseline LangGraph pipeline.

This includes installing dependencies, organizing files, adding my Open API and Tavily API keys and preparing the initial workflow skeleton to support all upcoming components.

[TODO] Step 2: Building the text summarization and information-extraction nodes (symptoms, causes, treatments).

These nodes will use the LLM prompts to simplify complex medical text and extract structured fields like symptoms, causes and treatment options for the later stags of the workflow.

[TODO] Step 3: Implementing the RAG-based retrieval system for accurate medical definitions.

This step sets up a retrieval pipeline that searches the trusted medical sources and returns precise definitions for medical terms detected in the input.

[TODO] Step 4: Creating the structured output generator to combine all results into a clean final format.

The generator takes the summaries, extracted fields and retrieved definitions, and then it combines them into a clear and organized final output that is easy to read and that is suitable for the patient use or for research documentation.

[TODO] Step 5: Integrating all nodes into a unified LangGraph workflow and building the interface/API.

This step involves connecting each node inside LangGraph, defining state transitions, and creating a simple UI or API endpoint so users can input medical text and receive processed output.

[TODO] Step 6: Performing end-to-end testing, debugging, refinement and the final documentation.

I will test the full pipeline on many medical texts, I will fix errors, refine prompts and prepare the final documentation that can explain the workflow and usage.



