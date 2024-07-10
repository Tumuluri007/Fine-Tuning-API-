**Star Trek: TNG Data Character Fine-Tuning with GPT-3.5 Turbo**
This repository demonstrates the process of **fine-tuning OpenAI's GPT-3.5 Turbo model **to emulate the **character of Data from Star Trek:** The Next Generation. The project showcases the entire pipeline from data preparation to model fine-tuning and evaluation.
**Key Components:**
Data Extraction and Preprocessing
Extracts Data's dialogues from Star Trek: TNG scripts
Implements custom text processing functions (e.g., strip_parentheses, is_single_word_all_caps)
Generates a JSONL file with formatted conversations
Data Splitting
Splits the dataset into training and evaluation sets
Implements randomization for unbiased splitting
Allows customization of split ratio and maximum number of lines
Fine-Tuning Process
Utilizes OpenAI's latest API for fine-tuning GPT-3.5 Turbo
Uploads training and evaluation files to OpenAI
Initiates and monitors the fine-tuning job
**Model Evaluation**
Compares responses between the base GPT-3.5 Turbo and the fine-tuned model
Demonstrates improved context-awareness and character-specific responses
**Technical Details:**
Language: Python
APIs: OpenAI API (latest version)
Models: GPT-3.5 Turbo (base and fine-tuned)
File Formats: JSONL for training data
**Key Features:**
Robust script parsing and dialogue extraction
Flexible data splitting with customizable parameters
Step-by-step fine-tuning process using OpenAI's API
Comparative analysis of base and fine-tuned model responses
**Use Cases:**
Character-based chatbots or interactive experiences
Study of natural language processing and model fine-tuning
Exploration of context-aware language models in specific domains
**Important Notes:**
Requires an OpenAI API key (not included in the repository)
Fine-tuning costs may apply (refer to OpenAI's pricing)
The repository includes both data preparation and model fine-tuning scripts
This project serves as a comprehensive example of fine-tuning language models for character emulation, demonstrating the entire process from data preparation to model evaluation. 


OPEN AI PLAYGROUND LINK: 
https://platform.openai.com/playground/chat?models=gpt-3.5-turbo-1106 
