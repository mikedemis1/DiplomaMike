# System Architecture

## High-Level Diagram
[Frontend Panel] ↔ [Backend API] ↔ [Database]
                            ↕
                   [ML Recommendation Module]

## Technologies (planned)
- **Frontend**: React (or Next.js)
- **Backend**: Node.js + Express (or Django)
- **Database**: PostgreSQL + PostGIS (or SQLite for local dev)
- **ML Module**: Python + Scikit-learn (or simple rule-based initially)
- **Security**: JWT authentication, access control

## Design Notes
- Modular structure: separation between logic (ads/matches), machine learning logic, and visualization
- Real-time simulation of different viewer perspectives
- The project will evolve iteratively — structure may change.
