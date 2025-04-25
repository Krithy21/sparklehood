Prerequisites:

# Install Node.js from https://nodejs.org/ (LTS version)
node --version  # Should be 18.0.0 or higher
Clone and setup:

# Clone the repository
git clone <repository-url>

# Navigate to project directory
cd <project-directory>

# Install dependencies
npm install
Development:

# Start development server
npm run dev
The app will be available at http://localhost:5173

Production:

# Create production build
npm run build

# Preview production build locally
npm run preview
Other commands:

# Run linter
npm run lint
The project uses:

React 18 with TypeScript
Vite for build tooling
Tailwind CSS for styling
Lucide React for icons
All necessary configurations are included in the repository:

TypeScript config (tsconfig.json)
Vite config (vite.config.ts)
Tailwind CSS config (tailwind.config.js)
ESLint config (eslint.config.js)
