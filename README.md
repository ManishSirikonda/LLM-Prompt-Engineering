# LLM-Prompt-Engineering

## Overview

This project explores the use of **prompt engineering** to improve dialogue summarization using large language models (LLMs). It evaluates the impact of different inference methods—zero-shot, one-shot, and few-shot—on the quality of model-generated summaries. By experimenting with various prompt strategies, the project aims to enhance the accuracy and relevance of outputs from LLMs.

## Table of Contents

1. [Introduction](#introduction)
2. [Installation](#installation)
3. [Usage](#usage)
4. [Project Structure](#project-structure)
5. [Methods Explored](#methods-explored)
    - [Zero-Shot Inference](#zero-shot-inference)
    - [One-Shot Inference](#one-shot-inference)
    - [Few-Shot Inference](#few-shot-inference)
6. [Results](#results)

## Introduction

Large language models have shown great potential in understanding and generating human-like text. However, their performance heavily depends on how tasks are framed. This project focuses on **prompt engineering**—the technique of crafting specific prompts to direct the behavior of LLMs—and its impact on summarizing dialogues. By comparing different prompt strategies, we aim to uncover methods that yield the most accurate and contextually rich summaries.

## Installation

To set up the environment for this project, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/LLM-Prompt-Engineering.git
    cd LLM-Prompt-Engineering
    ```

2. Install the required Python packages:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

After installing the dependencies, you can run the Jupyter notebook to see the experiments and results:

1. Open the Jupyter notebook:
    ```bash
    jupyter notebook
    ```
2. Navigate to `Prompt_engineering_project.ipynb` and run the cells to see different prompt engineering methods in action.

## Project Structure

- `Prompt_engineering_project.ipynb`: Jupyter notebook containing the code for running different prompt engineering techniques on dialogue summarization.
- `requirements.txt`: File containing the list of Python packages required to run the project.
- `data/`: Directory for storing dataset files used in the project.

## Methods Explored

### Zero-Shot Inference

In this approach, the model is asked to summarize dialogues without any example or specific instruction. It relies solely on its pre-trained knowledge, often leading to generic outputs.

### One-Shot Inference

Here, the model is provided with one example of a summarized dialogue along with an instruction. This single reference helps guide the model to understand the expected output format.

### Few-Shot Inference

Few-shot inference involves providing multiple examples to the model, offering a broader context and better generalization for the task. This method has been found to produce the most accurate and nuanced summaries.

## Results

The project demonstrates that prompt engineering significantly affects the quality of LLM-generated summaries. Few-shot inference with well-crafted prompts yields the most reliable and human-like summaries, highlighting the importance of providing context and examples in guiding model behavior.


