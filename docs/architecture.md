
---

## 🖼️ Mermaid Architecture Diagram (docs/architecture.md)

```markdown
# System Architecture

```mermaid
flowchart TD
    User -->|Web| Frontend[React + Tailwind]
    Frontend -->|REST API| Backend[Django REST API]
    Backend -->|Store & Query| DB[(PostgreSQL)]
    Backend -->|Files| Storage[(Azure Blob Storage)]
    Backend -->|Async Jobs| Worker[Celery + Redis]
    Worker -->|Embeddings| VectorDB[(Faiss / Azure Cognitive Search)]
    Worker -->|LLM Calls| AI[Azure OpenAI Service]
    Backend -->|Results| Frontend
