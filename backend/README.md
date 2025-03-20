# Project Title

## Description

Provide a brief overview of your project, including its purpose and any relevant background information.

## Prerequisites

List any software, tools, or libraries that need to be installed before setting up your project. For example:

- **Python**: Version 3.8 or higher
- **MongoDB**: Installed and running
- **Node.js**: Version 18 (if applicable)

## Installation

Outline the steps required to install and set up your project. For example:

1. **Clone the repository**:

   ```bash
   git clone https://github.com/yourusername/yourprojectname.git

2. **setup**:

   ```bash
   cd backend/
   python -m venv venv
   source venv/bin/activate
   pip install -r requirements.txt

 3. **.env**:
     
     Set up environment variables
     Create a .env file in the root directory and add necessary configurations
     
    ```bash
    touch .env
  4. **Ensure MongoDB is installed and running**:
     ```bash
      wget -qO - https://www.mongodb.org/static/pgp/server-5.0.asc | sudo apt-key add -
     echo "deb [ arch=amd64,arm64 ] https://repo.mongodb.org/apt/ubuntu focal/mongodb-org/5.0 multiverse" | 
     sudo tee /etc/apt/sources.list.d/mongodb-org-5.0.list
     
      sudo apt-get update
      sudo apt-get install -y mongodb-org
      sudo systemctl start mongod

       sudo systemctl enable mongod
      sudo systemctl status mongod
      mongosh

    
    
 5. **Run the FastAPI application**:
    ```bash
    uvicorn main:app --reload
 6. **install manually**:
    ```bash
    pip install python-dotenv
    
    pip install motor
