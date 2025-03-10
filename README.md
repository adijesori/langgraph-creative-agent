This is a simple creative agent can be used as a remote graph.
For reference use this repo: 

1. Clone the repository
2. Run `npm i`
3. Add `.env` file in the root directory with the following content:
```
LANGSMITH_API_KEY=${YOU_LANGSMITH_API_KEY}
LANGSMITH_TRACING=true
```
4. Run it locally with LangGraph platform using `npx @langchain/langgraph-cli dev`
5. In order to deploy it as a docker image:
   - run `npx @langchain/langgraph-cli build -t creative-agent`
   - run `docker compose up`
