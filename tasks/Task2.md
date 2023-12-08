# Workshop 2: Work with Chains in LangChain

## Overview
This workshop offers hands-on experience in creating and manipulating chains using LangChain, covering various components and integrating different models for real-world applications.

## Practical Tasks

### Task 1: Basic Chain Creation
- Initialize a basic LangChain project.
- Create a `PromptTemplate` for a simple query.
- Pipe the template to a `ChatOpenAI` model.
- Test the chain with a predefined input calling invoke.

### Task 2: Chain Streaming and Batch Processing
- Modify the existing chain to use a streaming function.
- Call and check the results of the streaming function.
- Modify the chain to use with a batch of inputs.
- Checke the results of the batch function.
- 
### Task 3: Chaining Multiple OpenAI Calls
- Create prompt for describing a dish in a restaurant.
- Create a prompt that accepts that description and reacts somehow to it.
- Create a chain that used first prompt to generate a description and formant resonse from model as string.
- Create runnable object that use response from first chain as input for second chain.

### Task 4: Chaining Multiple Models Calls
- Use the same prompt as in previous task.
- Create a chain that used first prompt to generate a description and formant resonse from model as string.
- Create runnable object that use response from first chain as input for second chain.

<details>
  <summary>Hint</summary>
  
 You can use ''stabilityai/stable-diffusion-2'' model for image generation.

</details>

### Task 5: Get Fun
- Create different chains with different models.
- Try to generate voice from text.
- Try to generate image from text.
