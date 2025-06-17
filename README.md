# LangChain and Anthropic Integration Example

This notebook demonstrates how to integrate LangChain with the Anthropic Claude 3 Opus model in a Google Colab environment. It covers basic usage, creating prompts, chaining components, and streaming responses.

## Prerequisites

- Google Colab environment
- Python 3.x
- An Anthropic API Key

## Setup

1.  **Open the notebook in Google Colab.**
2.  **Install the necessary libraries:**
3.  **Set your Anthropic API Key.** Replace `"....."` with your actual API key in the following code cell:

## Usage

The notebook walks through several examples:

-   Basic interaction with the `ChatAnthropic` model.
-   Creating and using `ChatPromptTemplate` for structured prompts.
-   Chaining prompts with the language model using the `|` operator.
-   Parsing model output with `StrOutputParser`.
-   Streaming responses using the `stream` method.
-   Providing context to the model using prompt templates (e.g., the current date or a provided source).
-   Debugging LangChain components using `set_debug(True)`.
-   Streaming events from a chain using `astream_events`.

Simply run the cells sequentially in the notebook to execute the examples.

## Examples Covered

-   Invoking the model with a simple string message.
-   Invoking the model with a list of `HumanMessage`.
-   Creating and invoking a prompt template with dynamic variables.
-   Creating and invoking a chain of a prompt template and the chat model.
-   Parsing the output of the chain to a string.
-   Streaming the output of the chain.
-   Providing external context (current date) to the model via the prompt.
-   Providing source data to the model for RAG-like scenarios.
-   Enabling and disabling debug mode for LangChain.
-   Asynchronously streaming events from a chain.

