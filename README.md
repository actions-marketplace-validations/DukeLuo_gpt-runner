# GPT Runner

This composite action allows you to run GPT Prompt from GitHub Actions.

## How to start

Firstly, you need to set OpenAI API Key with a action secret named `OPENAI_API_KEY` for this action. You can find more information about how to do it [here](https://docs.github.com/en/actions/reference/encrypted-secrets#creating-encrypted-secrets-for-a-repository).

To use this action in your workflow, you can add the following step:

```yaml
- name: Run GPT Prompt
  uses: <owner>/<repo>/action.yml@<ref>
  with:
    cmd: promptr -p "Cleanup the code in src/index.js" # Specify your desired GPT Prompt command
```

### Further Reading

- [Promptr](https://github.com/ferrislucas/promptr)
