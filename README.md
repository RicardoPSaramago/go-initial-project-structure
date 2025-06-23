# go-initial-project-structure
Grants the initial folder structure for a GO project

Estrutura de pastas para projetos GO

your-app/
├── cmd/               # Entry points (main packages)
│   └── your-app/      # e.g., main.go
├── internal/          # Private application code (not importable by other modules)
│   ├── service/       # Business logic
│   └── data/          # Persistence, DB access
├── pkg/               # Public reusable code (can be imported by other projects)
├── api/               # API definitions, OpenAPI/Protobuf/etc.
├── web/               # Static files, templates, frontend
├── configs/           # Configuration files (YAML, JSON, etc.)
├── scripts/           # Bash, setup, CI/CD helper scripts
├── test/              # Test data or helper packages
├── go.mod
├── go.sum
└── README.md
