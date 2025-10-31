Objective

Train a model to generate coherent and contextually relevant text based on a given prompt using GPT-2, a transformer-based language model developed by OpenAI.

Description

This project demonstrates fine-tuning and text generation using GPT-2.
The model learns from custom text data to produce realistic and meaningful sentences that mimic the writing style of the training dataset.
Once trained, it can generate new text automatically from any starting prompt.

This project is part of ProDigy Infotech – Task 1 (Comillas Negras).

Features

Uses GPT-2 (pre-trained Transformer model by OpenAI)

Supports fine-tuning on custom text datasets

Generates coherent text sequences based on input prompts

Runs easily on Google Colab

How to Run

Open the notebook Task_01_GPT2_Text_Generation.ipynb in Google Colab.

Ensure required libraries are installed:

pip install transformers torch datasets


Run all cells in order.

When prompted, enter a text prompt (for example: "Artificial Intelligence will")

The model will generate and print a continuation of that text.

Sample Output
Enter your prompt: Artificial Intelligence will
Generated Text: Artificial Intelligence will transform industries, improve healthcare, and create new opportunities for innovation and automation across the world.

Libraries Used

transformers – for loading GPT-2 model

torch – for model training and inference

datasets – for managing text datasets

Installation

If running locally, install dependencies using:

pip install torch transformers datasets


(No manual installation needed when using Google Colab.)

Author
Yash Tondlekar
Final Year Engineering Student
Project: Text Generation using GPT-2
Organization: ProDigy Infotech
