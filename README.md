# Virtual Assistant using Python and OpenAI GPT API

This project is a AI based voice assistant that used OpenAI GPT API to answer user queries, as well as returning live weaher dat and controlling the lights using multiple sensors and microprocessors.

## Getting Started

To use this tool, you will need to sign up for an API key from OpenAI. Instructions on how to sign up for an API key can be found in the [OpenAI API documentation](https://beta.openai.com/docs/api-reference/introduction).

### Usage

To use the tool, run the following command:

```
python main.py
```

You will have to use the wake up command, which is `hello`. When the assistant responds with `I'm listening`, you can ask your query or give some basic commands. The asssiant will return an answer or perform the commands based on your input.

## Model Architecture

The model used in this project is OpenAI GPT, a state-of-the-art language model that is capable of generating human-like text. The API allows us to get answers by sending a prompt to the API. The generated response can be further improved by fine-tuning the GPT model on a specific dataset. A weather API has also ben used to provide live weather readings.

The GPT model is a transformer-based language model that was trained on a large amount of text data. It uses a self-attention mechanism to capture the context of the input text and generate text that is contextually relevant. The GPT model has been used in various natural language processing tasks, including language translation, text summarization, and text generation.

The weather API was provided by the IoT team, who implemented sensors on the rooftop to get live weather data.

## Basic Commands

- `switch on` : To switch on the lights
- `switch off` : To switch off the lights
- `time` : To return the current time
- `date` : To return the current date
- `weather` : To provide live weather readings
- `terminate` : To turn the voice assistant off

## Results

The generated response have been found out to be accurate and relevantto the user's query. 


This project was done under `IoT Labs, KIIT` to help automate some basic tasks. The project now serves as a virtual assistant for the lab and is used to get quick answers or perform some basic commands. This project is still under developement and more feathers might be added in the future based on the requirements of the lab.
