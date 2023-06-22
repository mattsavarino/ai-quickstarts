# AI Quickstarts

This repo provides starter code for common AI services and tools.

### AI Services

<style>
  table { border-collapse:collapse; border:none; }
  th, td { border: none; }
</style>
<table>
  <tr>
    <td style="width:85px; text-align:center">
        <a href="./notebooks/00-get-started/00-openai.ipynb"><img src="./docs/images/logo-openai-light.png" height="50"/></a>
    </td>
    <td style="width:85px; text-align:center">
        <a href="./notebooks/00-get-started/00-azure-openai.ipynb"><img src="./docs/images/logo-azure.png" height="50"/></a>
    </td>
    <td style="width:85px; text-align:center">
        <a href="./notebooks/00-get-started/00-huggingface.ipynb"><img src="./docs/images/logo-huggingface.png" height="50"/></a>
    </td>
  </tr>
  <tr>
    <td valign="top" style="text-align:center">
        <a href="./notebooks/00-get-started/00-openai.ipynb">OpenAI</a>
    </td>
    <td valign="top" style="text-align:center">
        <a href="./notebooks/00-get-started/00-azure-openai.ipynb">Azure OpenAI</a>
    </td>
    <td valign="top" style="text-align:center">
        <a href="./notebooks/00-get-started/00-huggingface.ipynb">Hugging Face</a>
    </td>
  </tr>
</table>

### AI Tools
<table>
  <tr>
    <td style="width:85px; text-align:center">
        <a href="./notebooks/00-get-started/00-langchain.ipynb"><img src="./docs/images/logo-langchain.png" height="50"/></a>
    </td>
    <td style="width:85px; text-align:center">
        <a href="./notebooks/00-get-started/00-semantic-kernel.ipynb"><img src="./docs/images/logo-semantickernel.png" height="50"/></a>
    </td>
  </tr>
  <tr>
    <td valign="top" style="text-align:center">
        <a href="./notebooks/00-get-started/00-langchain.ipynb">LangChain</a>
    </td>
    <td valign="top" style="text-align:center">
        <a href="./notebooks/00-get-started/00-semantic-kernel.ipynb">Semantic Kernel</a>
    </td>
  </tr>
</table>

### Prerequisites

* Access to [OpenAI API](https://openai.com/product), or [Azure OpenAI](https://azure.microsoft.com/en-us/products/cognitive-services/openai-service/), or [Hugging Face](https://huggingface.co/login)
* Python 3
  * Check version by running `python -v` in a terminal
  * [Download latest here](https://www.python.org/downloads/)

### Initial Setup

1. Clone or download this repo
1. Open a terminal and change directory: `cd ai-tools`
1. Rename [.env.sample](.env.sample) to `.env`
1. Edit `.env` to add your keys for various AI services
1. Create virtual environment: `python3 -m venv env`
1. Activate virtual environment:
    * Windows: `.\env\Scripts\activate`
    * Linux or macOS: `source ./env/bin/activate`
1. Install required packages:
    * Stable: `pip install -r requirements.txt`
    * Lastest: `pip install -r requirements-latest.txt`<br/>

### Sample Notebooks
Get started with AI services:
* [Open AI](./notebooks/00-get-started/00-openai.ipynb)
* [Azure Open AI](./notebooks/00-get-started/00-azure-openai.ipynb)
* [Hugging Face](./notebooks/00-get-started/00-huggingface.ipynb)
* [LangChain](./notebooks/00-get-started/00-langchain.ipynb)
* [Semantic Kernel](./notebooks/00-get-started/00-semantic-kernel.ipynb)

Explore best practices from OpenAI:
* [Prompt Engineering Principles](./notebooks/01-prompt-engineering/01-principles.ipynb)
* [Iterative Prompt Engineering](./notebooks/01-prompt-engineering/02-iterations.ipynb)
* [Summarize Text](./notebooks/01-prompt-engineering/03-summarize.ipynb)
* [Infer Context](./notebooks/01-prompt-engineering/04-infer.ipynb)
* [Transform Data](./notebooks/01-prompt-engineering/05-transform.ipynb)
* [Expand Usage](./notebooks/01-prompt-engineering/06-expand.ipynb)
* [Conversation](./notebooks/01-prompt-engineering/07-conversation.ipynb)

### License

Licensed under the [MIT](./LICENSE.txt) license.

Use only with responsible AI practices and technologies.