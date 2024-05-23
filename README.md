# Web Audio/PDF ChatGPT

## Overview
Web Audio/PDF ChatGPT is a full-stack web-based Q&A AI agent that allows users to ask questions through both voice and text, using PDF documents as the context for generating responses. The application combines modern web technologies with advanced AI to provide an interactive conversational user interface.

## Key Features
- **Conversational UI:** Developed using React and Ant Design, the interface supports real-time voice and text interactions.
- **Advanced AI Agent:** Utilizes OpenAI's GPT-3.5 Turbo API and LangChain to handle document-related operations such as loading, splitting, and storage.
- **Efficient Data Handling:** RESTful APIs built with Express and Node.js ensure efficient management of large data volumes in real-time.
- **Optimized Data Retrieval:** Integrates a memory vector store for caching embeddings, significantly enhancing retrieval speeds.

## Technologies Used
- **Frontend:**
  - **React:** For building the interactive UI components.
  - **Ant Design:** Provides the design framework for a sleek and modern user interface.

- **Backend:**
  - **Node.js/Express:** Used for creating scalable and high-performance RESTful APIs.
  - **OpenAI GPT-3.5 Turbo:** Powers the AI-driven responses.
  - **LangChain:** Manages document operations and memory vector caching.

- **Data Management:**
  - **Memory Vector Store:** Optimizes caching processes to improve response times for data retrieval.
