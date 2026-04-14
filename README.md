# Alex Financial Planner

Alex is a multi-agent, enterprise-grade SaaS financial planner designed to automate, optimize, and streamline financial planning for businesses. Leveraging advanced AI agents, Alex provides robust financial analysis, reporting, and planning tools suitable for modern enterprises.

## Features
- **Multi-Agent Architecture:** Modular agents for planning, research, reporting, ingest, and more
- **Enterprise-Grade:** Scalable, secure, and designed for business-critical applications
- **SaaS Ready:** Cloud-native, supports serverless deployment (AWS Lambda, Aurora, S3, etc.)
- **Extensible:** Easily add new agents or integrate with external systems
- **Modern Frontend:** Next.js-based UI for seamless user experience

## Folder Structure
```
backend/      # Python backend, agents, APIs, database, ingest, planner, etc.
frontend/     # Next.js frontend app
scripts/      # Deployment and utility scripts
terraform/    # Infrastructure as code (AWS, S3, Aurora, Lambda, etc.)
guides/       # Step-by-step guides for setup and usage
assets/       # Images and static assets
```

## Getting Started
### Prerequisites
- Python 3.9+
- Node.js 18+
- AWS CLI (for deployment)
- Docker (for packaging Lambdas)

### Backend Setup
```bash
cd backend
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt  # or use poetry/uv as per pyproject.toml
```

### Frontend Setup
```bash
cd frontend
npm install
npm run dev
```

### Infrastructure
- See `terraform/` and `guides/` for infrastructure setup and deployment instructions.

## Usage
- Run backend agents and APIs from the `backend/` folder
- Access the frontend at `http://localhost:3000`
- Use guides in `guides/` for detailed workflows (permissions, ingestion, research, etc.)
