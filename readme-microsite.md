# kafka-connect
## **Kafka Connect, created with the Micro-Site Builder**

The microsite can be accessed at

Below are some steps to run your new MkDocs site locally, but you do not necessarily have to do this to get started. The main actions to take from here would be:
1. Update your content, which can be done in GitHub
2. Enable GitHub Pages in your repository's [settings]
3. Deploy your site, which [can be done many ways](#deployment)

## Getting Started

### Prerequisites
In order to run your MkDocs page locally, you'll need Python installed on your machine, as well as the Python package manager, pip. You can check if you have these already installed from the command line:

```zsh
python --version
pip --version
```

Install the `mkdocs` package using pip, as well as other dependencies, such as the theme this template uses:

```zsh
pip install -r requirements.txt
```

### Development
To start working on your documentation locally, you will need to clone this repo:

```zsh
git clone https://github.com/raghaviCJanaswamy/kafkaconnect-source-sink-trial.git
cd kafkaconnect-source-sink-trial
```

To start up the server, run this command:

```zsh
mkdocs serve
```

Open http://127.0.0.1:8000 in a browser to see the documentation page you have created! 🎉 

## Project layout
Your repository will resemble the directory structure here: 

    mkdocs.yml    # The configuration file
    docs/
        index.md  # The documentation homepage
        img/      # Image directory
        ...       # Other directories with Markdown pages

## Deployment
Micro-Sites are hosted with GitHub Pages and do not need any other type of infrastructure other than your GitHub repository. MkDocs will build your main branch into a static website that will be pushed to the `gh-pages` branch and your changes are live! You can manually redeploy or configure automation to redeploy with every change to `main`.


### Manually
To manually redeploy your documentation changes:

```zsh
mkdocs gh-deploy
```

This will rebuild your main branch and then push the built website to the `gh-pages` branch.

