
## Lang Chain Expression Language

```bash
Prompt             -->       Model       -->     Parser 
(input formating)      (LLM Processing)        (Extract text)

```

💡 Concept:
#### Sequential Chains - The Pipeline Pattern
LCEL uses the pipe operator | to chain components. Data flows left to right: input → prompt → model → parser → output.



