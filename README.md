
# AI-Powered News Query Generator

The AI-Powered News Query Generator is a project designed to assist professionals, entrepreneurs, and individuals in obtaining highly relevant and tailored news articles based on their specific roles, business stage, industry, location, and business objectives. The project utilizes the OpenAI GPT-3.5-turbo engine to dynamically generate news queries from user-provided information. Users can input their details, and the system crafts a comprehensive news query, enhancing the efficiency of information retrieval. This tool is particularly valuable for those seeking curated news content aligned with their professional roles and business goals, providing a personalized and time-saving approach to staying informed.
.
.
.
.
.
.
Technology Stack:

OpenAI GPT-3.5-turbo: The core of the project relies on the GPT-3.5-turbo language model from OpenAI. This powerful language model is utilized to understand user inputs, generate dynamic news query prompts, and provide context-aware responses.

OpenAI API: The OpenAI API serves as the bridge between the application and the GPT-3.5-turbo model. It allows seamless integration, enabling the system to send prompts and receive generated text from the language model.

gnews Python Library: The project leverages the gnews Python library to fetch news articles from Google News based on the dynamically generated queries. This library simplifies the process of interacting with the Google News API. (for Reference https://github.com/ranahaani/GNews?tab=readme-ov-file#acknowledgements)

How It Works:

User Input: Users provide their role, business stage, industry, location, and business objectives as input to the system. This information is structured into a dictionary named user_message.

Query Generation: The system uses the OpenAI GPT-3.5-turbo engine to generate a news query based on the user's input. The GPT-3.5-turbo engine excels in natural language understanding and context-aware text generation.

Dynamic Prompting: The OpenAI API is employed to send a prompt to the GPT-3.5-turbo engine, instructing it to create a news query that encapsulates the user's details. The response from the engine is then processed to extract the generated news query.

News Retrieval: The generated news query is used to fetch relevant news articles from Google News using the gnews Python library. The library interacts with the Google News API, returning a list of articles based on the query.

Presentation: The system presents the user with information from the first retrieved news article, including the title and URL. If no articles are found, a corresponding message is displayed.

Benefits and Target Audience:

Personalized Information Retrieval: Tailored news queries ensure that users receive information relevant to their specific roles, business context, and objectives.
Time Efficiency: The automated process eliminates the need for manual search queries, saving users time and effort.
Professionals and Entrepreneurs: The tool caters to professionals, entrepreneurs, and individuals seeking a streamlined way to stay informed about industry trends and developments.
## Installation

To get the project working.

```bash
  Install gnews
  install openai
  GET AN OPENAI AI KEY

```
    