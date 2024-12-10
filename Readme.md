# Cold Email Generator

A Cold Email Generator built for service-based companies, leveraging **Groq**, **LangChain**, and **Streamlit**. The tool extracts job listings from a company’s careers page via a URL input and generates personalized cold emails. These emails are tailored to specific job descriptions and include relevant portfolio links sourced from a vector database.

By automating the email outreach process, this tool enables business development teams to efficiently craft compelling, personalized emails that increase engagement with potential clients or partners.

## Setup Instructions

1. Obtain an **API_KEY** from the [Groq API Console](https://console.groq.com/keys).
2. Update the `GROQ_API_KEY` in the `.env` file located in the `app/` directory with your API key.
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
