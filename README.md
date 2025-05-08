# JobRaidy: AI-Powered Interview Preparation Assistant

JobRaidy is a generative AI-based application designed to support job applicants with personalized interview preparation. It evaluates resumes, simulates job-specific interview questions, provides feedback, and helps users gain company insights—all within one streamlined platform.

## Project Overview

Job seekers today face a competitive hiring landscape, investing several hours into each application without personalized guidance. While platforms like Glassdoor and LinkedIn offer preparation resources, few provide tailored, end-to-end support. JobRaidy fills this gap using large language models to deliver dynamic, job-specific coaching.

## Features

- **CV Scoring**: Upload a CV and get a tailored match score against a selected job description.
- **Simulated Interviews**: Answer AI-generated questions tailored to the role and receive feedback.
- **Peer Comparison**: Benchmark your responses with others for continuous improvement.
- **Company Insights**: Use a conversational interface to research your target employer.
- **Streamlit Interface**: Simple front-end for interactive user experience.

## Technical Approach

- **LLM Integration**: Uses Gemini 1.5 Pro to interpret user inputs and job descriptions.
- **LangChain Orchestration**: Coordinates communication between data sources and the LLM.
- **Adzuna API**: Ingests real-time job postings for context-aware analysis.
- **Prompt Engineering**: Structured prompts deliver instant feedback without retrieval augmentation (RAG).
- **Frontend**: Streamlit app for CV upload, Q&A, and job interaction.

## Future Work

- **User Login & Tracking**: Collect applicant data for performance feedback and B2B use.
- **Company-Facing Dashboard**: Enable hiring teams to automate early-stage candidate screening.
- **AI Redirection Logic**: Incorporate reinforcement learning to adapt follow-up questions.
- **Ethical Design**: Prioritize fairness, explainability, and privacy in model outputs.

## Limitations

- Model generalization for niche roles
- Token limit constraints from API usage
- Data privacy considerations for user uploads

## Try the App

Interact with JobRaidy live:

[Launch App](ADD LINK)
