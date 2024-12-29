# FunnyBOT-7B
Llama-2 7B model trained using transcripts of data from a popular comedic podcast by Adam Freidland, Stavros Halkias, and Nick Mullen.

## Features

Creates jokes and witty responses in the style of the original podcast. Current iteration designed for casual, engaging dialogue with a comedic edge.

## Base Model

LLaMA-2 7B

Training Data: 

Podcast transcripts via a CSV file linked in the repo.

## Optimization for GPUs

NVIDIA T4/RTX 30xx:

Use bitsandbytes for 8-bit quantization to save memory.

## License

This model is a fine-tuned version of LLaMA-2, subject to the LLaMA-2 License Agreement.

Further improvements will be made, and overall model will be fine-tuned for clarity and accuracy (speaker labels, further data cleaning, etc).
