# AgentDemo

An Agent Demo.

## Components

1. **LLMs** which are able to generate function callings given instruction and function_list.
2. **Function repository**. Each function has description, name and parameters.
3. **Tool retriever** that can retieve needed functions from function repository given instruction. Implemented by an embedding model.
4. **Agent** which is activated by prompt, LLMs and function_list.

## Workflow
