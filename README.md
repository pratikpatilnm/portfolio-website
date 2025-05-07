# portfolio-website
This repository contains the source code for my personal portfolio website, built using React.js for the frontend and Express.js for the backend. It's designed to showcase my skills, projects, and professional journey in a sleek and interactive way.

# Download and install nvm:
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.40.3/install.sh | bash

# in lieu of restarting the shell
\. "$HOME/.nvm/nvm.sh"

# Download and install Node.js:
nvm install 22

# Verify the Node.js version:
node -v # Should print "v22.15.0".
nvm current # Should print "v22.15.0".

# Verify npm version:
npm -v # Should print "10.9.2".

# Create frontend
npx create-react-app frontend
cd frontend
npm start

# Create backend
mkdir backend
cd backend
npm init -y

npm install express cors dotenv