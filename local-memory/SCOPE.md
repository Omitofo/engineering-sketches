# local-memory

Tiny local-first memory system for agents.

## Core Goals
- Give agents a simple, reliable way to store and retrieve knowledge locally
- Keep the API small and elegant
- Demonstrate clean data modeling and architecture

## Possible Features (MVP → Nice-to-have)

### MVP
- Store notes / facts with optional tags
- Retrieve by ID or simple search
- Persistent storage (SQLite recommended)
- Clean TypeScript or Python API

### Nice-to-have
- Tag-based filtering
- Simple full-text search
- Embeddings support (optional)
- Export / import
- Soft deletes or versioning

## Tech Direction (suggestion)
- TypeScript + better-sqlite3, or Python + sqlite
- Very small public API surface
- Clear separation between storage and query layer

## Definition of Done
- Easy to install and use in another project
- Good README with real usage examples
- Basic tests
- Feels like a thoughtful little system, not a toy
