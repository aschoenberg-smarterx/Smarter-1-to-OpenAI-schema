# Smarter-1-to-OpenAI-schema

This Github provides the necessary documentation to create a GPT action to connect to and retrieve any/all classifications from Smarter-1 in the ChatGPT interface.

1. Action schema on GPT backend - no changes needed for different use cases.
2. API Key - get from api.smarterx.com. Set authentication to Bearer on GPT Action backend.
3. Prompt format - do not change product attributes section of schema defined in prompt. Can adjust which rules you wish to evaluate. Adjust remainder of the prompt (outside of the schema to send to Smarter-1) as needed for your use case.
