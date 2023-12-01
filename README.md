# LangChainWorkshop
Learning Week LangChain Workshop

## Instruction
- Install python dependencies: `pip install -r requrements.txt`
- Create `.env` file in the current directory
- Set OpenAI key
	- generate a key: https://platform.openai.com/account/api-keys
    - add `OPENAI_API_KEY` to the `.env` file with the key as a value: `OPENAI_API_KEY=your-api-key`
- Set [Hugging Face](https://huggingface.co/) key
	- generate a key: https://huggingface.co/settings/tokens
	- add `HUGGINGFACEHUB_API_TOKEN` to the `.env` file with the key as a value: `HUGGINGFACEHUB_API_TOKEN=your-api-key`
- Get Access to Google Custom Search API
	- Create a new project at https://console.developers.google.com/apis/dashboard
	- Create a new API key at https://console.developers.google.com/apis/credentials
	- Enable the Custom Search API at https://console.developers.google.com/apis/library/customsearch.googleapis.com
	- Create a new Custom Search Engine at https://cse.google.com/cse/all
	- Add your API Key as `GCS_DEVELOPER_KEY` and your Custom Search Engine ID as `GCS_CX` to your .env file

