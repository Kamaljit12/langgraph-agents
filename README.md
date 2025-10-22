# Agents planing

### There will be three agents:
1. Finance Agent
2. Reasoning Agent
3. General Agent

### I have once pdf docs of finance:
Steps:
- Extract text from pdf docs
- Split text into chunks
- Create documents of the chunks
- Create vectordb [FAISS oe Chroma]
- Create vector retriever


### Create Agent 3 for:
- Finance Agent: It will retriever response from the vercordb based on the user query
- Reasoning Agent: If user will ask any query, if it requeires reasoning ability then it wil be triggered
- General Agent: If use will ask any general query the like Hello, Hii, Goodbye or for greeting

### Create a router for orchestation