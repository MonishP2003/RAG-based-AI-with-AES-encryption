# RAG-based-AI-with-AES-encryption
This project integrates Retrieval-Augmented Generation (RAG) based AI with Advanced Encryption Standard (AES) encryption. It demonstrates configuring a language model using HuggingFace transformers, quantizing it for optimized performance, and implementing AES encryption.

<br/>

Introduction

This project combines state-of-the-art AI techniques with robust encryption methods. By utilizing a RAG-based AI model, the system can generate contextually relevant responses while ensuring data security through AES encryption. The model is configured to optimize performance using quantization techniques.

<br/>

Model Configuration

The model is configured using HuggingFace transformers with specific quantization to enable efficient processing:

Quantization Configuration: Uses BitsAndBytesConfig to load the model in 4-bit mode, balancing speed and memory usage.

Language Model: The HuggingFaceLLM class is used to initialize and configure the model, ready to process input text and generate outputs.

<br/>

Encryption with AES

The project also includes AES encryption to ensure data security:

Key Generation: A random 16-byte key is generated for encryption.
Encryption & Decryption: The AES algorithm is used in ECB mode to encrypt and decrypt data.
