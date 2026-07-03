### SmartNotes — AI-Powered Note Management System

SmartNotes is a full-stack web application that helps users organize, search, and summarize their notes efficiently. The platform allows users to create, edit, categorize, and manage notes through a clean and responsive interface.

The most interesting part of the project was building the semantic search and AI summary pipeline. Instead of relying only on keyword matching, notes are converted into vector embeddings, enabling users to find relevant content even when the exact words are not present in the query. An AI-powered summarization module generates concise summaries for long notes, making information retrieval significantly faster.

On the backend, I implemented authentication, REST APIs, search indexing, and optimized database queries for faster retrieval. The application also includes pagination, tagging, and real-time note updates.

Stack: React, Node.js, Express.js, MongoDB, JWT Authentication, Docker
