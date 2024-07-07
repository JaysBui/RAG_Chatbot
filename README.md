# RETRIEVAL AUGMENTED GENERATION (RAG) on PDF file using LLM, Chainlit and Ngrok

## 1. Abstract:
Large Language Model(s) is/are most well-known from one of the prominent contemporary chatbots in 2024, namely Chatgpt, Gemine, Claude, etcetera... However, they are likely commercial products that require a charge from end-users with it's worthy for personal or enterprise purposes. In today's society, We acknowledge that there are more and more products suiting people's needs which means free-to-use and resulting the approximate productivity as opposed to well-known chatbots. Therefore, in this project, we shall illustrate the RAG on a PDF file using the Vicuna for chatbot, collab Google for free-gpu environment, chainlit for expressing application at our convenience.

## 2. Preparation

To achieve the goals outlined in the abstract, the following tools and platforms are required:
* Google cobllab
* Vicuna
* Langchain
* Hugging face
* Chainlit
* ngrok

Some of these tools may be unfamiliar, but they will be explained in detail during the setup and execution process.

---

## 3. Setup and excution

### a. Clone the repository
Clonning the repository to your Google Colab environment:
```bash
!git clone <repository_url>
```
---
### b. Open google collab
Load file named: `RAG_Chatbot_Chainlit.ipynb` from the cloned repository into Google Colab.

### c. Install Required Libraries

Run the installation command in the first cell to ensure all dependencies are installed.
```python
!pip install -r requirements.txt
```
### d. Detailed steps
Follow the detailed steps provided in the following cell of the notebook. Use `Ctrl+Shift+Enter` to run and excute.
### e. Run chainlit
To run the application, execute the last cell in the notebook with the following command:

```bash
!chainlit run app.py
```

This will display the message:

```
Your app is available at http://localhost:8000
```
Access the application via the provided URL.


