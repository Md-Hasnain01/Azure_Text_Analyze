# Azure Text Analytics

This project uses Azure's Text Analytics API to analyze text files containing reviews. It extracts various insights, including language detection, sentiment analysis, key phrases, entities, and linked entities.

## Prerequisites

Before you begin, ensure you have the following installed:

- Python 3.6 or later
- pip (Python package installer)


## Install the required packages:

You can install the necessary libraries using pip.
```
pip install azure-ai-textanalytics python-dotenv
```


## Set up environment variables:

Create a `.env` file in the root directory of your project and add your Azure Text Analytics credentials:

```
AI_SERVICE_ENDPOINT=<your-ai-service-endpoint>
AI_SERVICE_KEY=<your-ai-service-key>
```

Replace `<your-ai-service-endpoint> and <your-ai-service-key>` with your actual Azure Text Analytics service endpoint and key.


# OUTPUT

## Analyze text file in the reviews folder

![Screenshot 2024-11-11 124758](https://github.com/user-attachments/assets/56ee367c-e345-4c26-be91-a3fbd28d4ec8)

![Screenshot 2024-11-11 124739](https://github.com/user-attachments/assets/de1de66f-4b74-49ca-9faf-80a545acf4aa)

![Screenshot 2024-11-11 124632](https://github.com/user-attachments/assets/d7b82840-935d-4a94-bae1-29bd72d812b0)
