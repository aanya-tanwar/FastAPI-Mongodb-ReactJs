# Backend - FastAPI and MongoDB Setup

This is the backend for the FastAPI and MongoDB project. The backend is built with **FastAPI** for creating RESTful APIs and **MongoDB** as the database.

## Prerequisites

Before you begin, ensure you have the following installed on your local machine:

- **Python 3.8 or higher**
- **MongoDB** (for local development) or access to a MongoDB Atlas instance
- **Node Version Manager (NVM)** for managing Node.js versions (optional, for managing Node.js version 18)
- **Mongo Shell** (`mongosh`) for interacting with MongoDB
- **pip** (for installing Python dependencies)

## Step 1: Set up the environment

### 1.1 Install Node Version Manager (NVM)

```bash
# Install NVM
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.3/install.sh | bash

# Install Node.js version 18
nvm install 18
nvm use 18

