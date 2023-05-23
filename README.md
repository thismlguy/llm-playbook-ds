# llm-playbook-ds
---------

This repository lists helpful resources for data scientists to start incorporating LLMs into their daily workflows. Engineers have been using
Github-Copilot to increase their efficiency by more than 50%, why should data scientists be left behind?

The resources are structured into 2 formats:
- [Examples](/examples) in the form of jupyter notebooks
- [Code Snippets](/src) in the form of python files which contain utility functions that you can use in your own projects
- [Learning Path](/LEARNING-PATH.md) which lists the steps you can take to start using LLMs in your daily workflow

## Examples


## Code Snippets



### Environment Setup
Use the `requirements.txt` file to install the required dependencies. You can install them using the following command:

```bash
pip install -r requirements.txt
```

## Contributing

Contributions are welcome! You could contribute both notebooks and code snippets.

### Notebooks

Please use the template followed in existing notebooks.
- Start with a title section with a summary of analysis being performed
- Add a `Data Sources` section with links/details to the data files required to replicate the notebook
- Add a `Environment Setup` section with instructions to setup the environment required to run the notebook. List down the packages used along with
versions

### Source

- Add all files under the `/src` directory.
- If any additional packages are required, please add them to the `requirements.txt` file.
    - If you make any changes to existing packages, you'll need to test that existing code doesn't break.
    - Unit tests coming soon!
