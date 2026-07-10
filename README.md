SmartHire is a modern, production-ready full-stack application designed to revolutionize the recruitment process. Moving away from rigid, keyword-based search algorithms, the platform leverages applied Artificial Intelligence to bridge the gap between job seekers and employers through contextual understanding.

By integrating a robust Java (Spring Boot) microservices backend with an intuitive, dynamic React frontend, SmartHire delivers seamless workflows for profile management, role-based access control, secure resume ingestion, and real-time analytical match telemetry.


🧠 Core AI Architecture & Enhancements
Semantic Resume Filtering: Integrated Spring AI to extract data from multipart resume uploads and convert unstructured candidate profiles into high-dimensional vector embeddings.

Vector Search Engine: Utilized a vector database (pgvector / Pinecone) to run mathematical Cosine Similarity and K-Nearest Neighbors (KNN) matching algorithms, ranking the best-fitting roles based on candidate capabilities rather than literal string matches.

Intelligent Corporate Suggestions: Developed a data pipeline that automatically matches job seekers to companies whose active job postings tightly align with their tech stacks and career vectors.

Predictive Match Metrics: Deployed responsive React components featuring dynamic match percentage badges and interactive visualizations to deliver transparency directly to user dashboards.


🛠️ Tech Stack & Keywords
Frontend: React, React Router, Axios, Context API, Tailwind CSS / UI Components

Backend: Java, Spring Boot, Spring Security (JWT / Role-Based Access), Spring Data JPA

AI Layer: Spring AI, Vector Databases (pgvector/Pinecone), OpenAI Embeddings / Ollama Local Models

Database: MySQL (Relational Core), PostgreSQL (Vector Core)

Tools: Maven, Git, Docker, RESTful APIs