# FlowgenAi
FlowgenAI – AI Workflow Generator

FlowgenAI is an AI-powered web application that converts natural language descriptions into structured workflows and flowcharts.
It simplifies workflow creation for both technical and non-technical users by combining Generative AI, blockchain integration, and modern web technologies.

🚀 Features
🧠 AI Workflow Generation – Convert plain text into structured workflows
📊 Flowchart Visualization – Generate clear diagrams dynamically
🌐 Modern Web App (Next.js) – Fast and scalable UI
🔗 Blockchain Integration (Flow) – Smart contract-based workflow storage
🗄️ Database Support – Persistent storage with PostgreSQL
☁️ Cloud Storage (Web3.storage) – Decentralized file handling
🤖 OpenAI Integration – AI-powered logic generation
🏗️ Tech Stack
Frontend & Backend: Next.js (TypeScript)
AI Integration: OpenAI API
Blockchain: Flow Blockchain (Cadence)
Database: PostgreSQL (Neon / Supabase)
Storage: Web3.storage
Deployment: Vercel
📂 Project Structure
FlowgenAi/
│── app/                  # Next.js app directory
│── commands/             # CLI / automation scripts
│── cadence/              # Flow smart contracts
│── db/                   # Database schema & config
│── lib/                  # Utility functions
│── public/               # Static assets
│── docs/                 # Documentation
│── .env.local            # Environment variables
│── package.json          # Dependencies
⚙️ Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/Revanthsanga/FlowgenAi.git
cd FlowgenAi
2️⃣ Install Dependencies
npm install
# or
pnpm install
3️⃣ Environment Variables

Create a .env.local file and add:

# OpenAI
OPENAI_API_KEY=your_api_key

# Database
DATABASE_URL=your_postgres_url

# Web3 Storage
W3_DELEGATED_DID=
W3_STORAGE_AUTH_HEADER=
W3_STORAGE_AUTH_SECRET=

# Flow Blockchain
NEXT_PUBLIC_FLOW_ENDPOINT_URL=
NEXT_PUBLIC_FLOW_NETWORK=
FLOW_CONTRACT_ADDRESS=
NEXT_PUBLIC_FLOW_ADMIN_ADDRESS=
▶️ Running the Project

Start the development server:

npm run dev

Open 👉 http://localhost:3000

🔗 Flow Blockchain Setup
Install Flow CLI
Generate keys
Start emulator:
flow emulator start
Run dev wallet:
flow dev-wallet
Deploy contracts:
pnpm flow:deploy:emulator
Seed data:
pnpm db:seed
🧠 How It Works
User inputs a workflow description
OpenAI processes the text and generates structured steps
Backend formats it into workflow logic
Flow blockchain stores or verifies workflows
UI renders the workflow as a visual diagram
📊 Use Cases
📈 Business process automation
🧑‍💻 Software workflow design
🎓 Educational tools
🏢 Project planning & management
🤖 AI-assisted diagram generation
