# Smarter-1-to-OpenAI-schema

This Github provides the necessary documentation to create a GPT action to connect to and retrieve any/all classifications from Smarter-1 in the ChatGPT interface.

****v2beta versus v3beta****

To move from v2beta to v3beta before deprecation, simply replace the v2beta action schema in your backend with the v3beta version provided here. You might need to re-enter your API key in the update.

**YOU WILL NEED TO SLIGHTLY UPDATE THE SYSTEM PROMPT in order for this new schema to connect correctly to the API**:
change "rules_to_evaluate" to "decisions_to_evaluate" and rename the rules/decisions to the correct name for the entire ruleset. For example: RCRA001, RCRA002 --> RCRA_WASTE


1. Action schema on GPT backend - no changes needed for different use cases.
2. API Key - get from api.smarterx.com. Set authentication to Bearer on GPT Action backend.
3. Prompt format - do not change product attributes section of schema defined in prompt. Can adjust which rules/decisions you wish to evaluate. Adjust remainder of the prompt (outside of the schema to send to Smarter-1) as needed for your use case.
