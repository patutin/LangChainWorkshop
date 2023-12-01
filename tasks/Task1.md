# Session 1: Introduction to LangChain

## Prerequisite
Before starting this session, ensure you have received the Azure OpenAI API keys via email.

## Task Steps

### Step 1: Project Setup
- **1.1 Create a new project directory**:
  - Use the command line or terminal to create a new folder.

### Step 2: Install Python dependencies
- **2.1 Install LangChain and other dependencies**:
  - Copy `requrements.txt` to your directory.
  - Run `pip install -r requirements.txt`.

### Step 3: Azure OpenAI API Integration
- **3.1 Configure .env file**:
  - Create a `.env` file in your project root.
  - Add your Azure OpenAI API keys and endpoint to the `.env` file for secure access.
- **3.2 Create your first call to Azure OpenAI LLM model**:
  -  Develop Python code to make the initial request to the Azure OpenAI LLM model using LangChain
  -  Replace LLM Model With Chat Model, and check that it works as expected.
  -  With the same PromptTemplate, change the Temperature to see how the output changes.


### Step 4: Register on HuggingFace and Get an API Key

- **4.1 Register or Login:**
  - Visit the Hugging Face website: [https://huggingface.co/](https://huggingface.co/)

- **4.2 Generate an API Token:**
  - Log in to Hugging Face.
  - Click on your username and select "Settings".
  - In the "Access Tokens" tab, click the "New Token" button.
  - Enter a descriptive name for your token.
  - Select the appropriate permissions for your token.
  - Click the "Generate token" button.
  - Copy the generated API token and save it securely.
  - Add your Hugging Face API token to the `.env` file.

### Step 5: HuggingFace Model Call
- **5.1 Integrate HuggingFace model**:
  - Replace the Azure OpenAI model with a HuggingFace model.
  - Check that code with new model works as expected.

### Step 6: Work with Output Parsers
- **6.1 Implement Output Formatters**:
  - Configure LangChain for using string output formatting.
  - Configure LangChain for using StructuredOutputParser.
  - 
### Final Steps
- **Lets Play with different models**: [https://huggingface.co/models](https://huggingface.co/models) 
