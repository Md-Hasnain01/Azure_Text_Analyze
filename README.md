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

## Getting Language

![Screenshot 2024-11-11 125411](https://github.com/user-attachments/assets/905cbc56-5007-4469-ab38-c425a0b5d96f)

## Sentiment and key phrases

![Screenshot 2024-11-11 125652](https://github.com/user-attachments/assets/445287f4-a383-4255-9f46-d74bead2d9a6)

![Screenshot 2024-11-11 125816](https://github.com/user-attachments/assets/92ccc4dc-72c8-4bad-8dcf-a549acdbdcef)

![Screenshot 2024-11-11 125835](https://github.com/user-attachments/assets/0df9f3b0-1686-4fde-807c-4c7c44e015f7)

![Screenshot 2024-11-11 125904](https://github.com/user-attachments/assets/011f1c3e-1008-4ad9-af71-506d7a6984ea)

## Getting Entities

![Screenshot 2024-11-11 125927](https://github.com/user-attachments/assets/33fcf2b6-e003-487f-a95b-7d6677cc1be1)

![Screenshot 2024-11-11 125943](https://github.com/user-attachments/assets/d22571a0-5f5f-4f65-8921-a7323027e53c)

![Screenshot 2024-11-11 130010](https://github.com/user-attachments/assets/67a2eaee-a685-498c-91c1-952a12564902)

## Link Entities

![Screenshot 2024-11-11 130415](https://github.com/user-attachments/assets/23088874-30c9-46ba-9bc3-c9967c0f9585)



## Usage

Run the script to analyze the text files in the reviews folder:

```
python your_script_name.py
```

Replace `ur_script_name.py` with the actual name of your Python script.

## Example

When running the script, you will see output similar to:

```
-------------
example_review.txt

This is an example review text.

Language: English

Sentiment: Positive

Key Phrases:
    - example
    - review

Entities
    - example_entity (Category)

Links
    - example_link (http://example.com)
```

