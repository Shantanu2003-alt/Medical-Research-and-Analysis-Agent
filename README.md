# Medical-Research-Agent

An AI-powered Medical Research Agent that turns complex medical text into clear insights. 

It extracts symptoms, causes and treatments and gives accurate medical definitions using RAG.

The agent produces easy-to-understand and structured outputs for research use and for communication with patients.

# To maintain a clear and consistent development workflow, I followed a plan-wise code upload approach where I uploaded Plan-wise code files:

So I followed a plan-wise, incremental approach, uploading a new notebook after each stage of development.

To make sure about regular commits, I first uploaded the initial code parts, then added new sections to the previous code parts and then merged them into the next plans.

This helped me to show consistent progress, as each plan contained all previous work plus the newly implemented features too.

Finally, Plan 6 became the complete and ready-to-run project and it shows the full evolution of my work from start to finish.

# Features of this Project

1. Prompting Framework- Uses multiple structured prompts for consistent medical reasoning.

2. Structured Output with Pydantic- Ensures clean, validated, schema-based medical information extraction.

3. Semantic Search Integration- Fetches context using Tavily and Wikipedia queries.

4. Retrieval-Augmented Generation (RAG)- Uses retrieved medical evidence to answer accurately.

5. Tool Calling System- Invokes search tools and LLMs programmatically within workflow.

6. LangGraph Workflow Architecture- Implements multi-node graphs with conditional routing logic.

7. Medical Analyst Generation- Creates specialized analyst personas for deeper medical insights.

8. Automated Interview Engine- Generates multi-turn question-answer interviews dynamically.

9. Evidence-Backed Expert Answering- Produces medical responses strictly based on verified sources.

10. Structured Medical Report Writer- Creates well-organized medical sections with citations and clarity.

11. Final Report Compilation System- Combines all sections into a complete and detailed medical document.

12. PDF Export of Final Report- The users get a ready-to-use PDF document as the output.

# Reasons for Picking Up This Project

1) On a personal level, I have often struggled to understand complex medical terms and it takes me time to search about that from various websites, so I thought that this project would help me with that.

The medical text analysis requires deep reading, research and information organization, so this domain shows how the techniques learned in this course can be used to solve real-world problems that feel time-consuming and difficult.

2) This project consists of the concepts that were covered in the course MAT496 taught by Ajit Sir. 

These are the concepts from the course that I have used in this project:

Prompting

Structured Output

Semantic Search

Retrieval-Augmented Generation (RAG)

Tool Calling

LangGraph Workflow (state, nodes, transitions)

These are the additional concepts I have also implemented:

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

# Workflow of this Project

Environment setup & dependencies

Data preprocessing + input handling

Pydantic data models (structured schemas)

Prompt design and refinement

Text summarization node

Information-extraction node (symptoms, causes, treatments)

RAG retrieval node (Tavily + Wikipedia)

Structured output generator (assemble final results)

LangGraph workflow integration (state, nodes, flow)

PDF export, testing and final documentation

# Screenshots of the Output Example Report of the Project

1) <img width="579" height="759" alt="image" src="https://github.com/user-attachments/assets/97d2710e-73f7-4b4e-8c76-46f79e6d0482" />

2) <img width="532" height="804" alt="image" src="https://github.com/user-attachments/assets/5e195c70-f02c-4cef-90e1-9990ac931065" />

3) <img width="532" height="804" alt="image" src="https://github.com/user-attachments/assets/ca892b77-e5e5-4853-a283-aa59a632b694" />

4) <img width="539" height="360" alt="image" src="https://github.com/user-attachments/assets/65b65c89-0054-4036-b035-6abef91426d9" />

# Conclusion

When I got this idea about this Capstone Project, then I had planned to build a complete multi-step medical processing system using LangGraph which can combine text summarization, medical information extraction, retrieval-augmented generation, structured outputs and final report creation.

After completing the project, I believe I have fully achieved the goals I set in the plan.

I followed each planned step: from the environment setup, model design, prompt engineering, RAG integration, workflow graph creation, multi-agent interview system to final PDF report generation.

So this final system is able to take a medical query, generate analyst personas, run interviews with web-verified medical information, extract structured fields, summarize content, retrieve definitions and produce a complete medical report in a clean and downloadable format.

I am satisfied with the outcome because the project has all the core concepts which were taught in the course by Ajit Sir and I have also tried to extend those concepts with additional advanced features like the multi-agent coordination, safety-aware answer generation and automated PDF export.

Overall, this project was genuinely a learning experience for me and I would like to thank Ajit Sir for giving this opportunity to work on it. Thank you!
