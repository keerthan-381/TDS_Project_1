## 📋 Requirements  
Ensure you have the following installed:  
- **Docker** – For containerization and deployment.  
- **AI Proxy Token** – Necessary for accessing LLM functionalities.
---



### 1. Clone the Repository  
```sh
git clone https://github.com/keerthan-381/TDS_Project_1.git
```

### 2. Install Dependencies  
```
pip install -r requirements.txt  
```

### 3. Setup Environment Variables  
### Create a .env file in the project root  
```
echo "AIPROXY_TOKEN=your_token_here" > .env  
```

### 4. Run Locally  
```
python run.py  
```

### 5. Using Docker  
### Build the image  
```
docker build -t llm-agent .  
```

### Run the container  
```
docker run --env-file .env -p 8000:8000 llm-agent  
```
