# ai_triage_tool
# AI Support Ticket Triage Assistant

A lightweight, zero-shot text classification tool built in Python that automatically categorizes customer support messages and determines their urgency level without needing any prior training data.

## Features
* **Zero-Shot Classification:** Leverages Hugging Face's `facebook/bart-large-mnli` model to classify text into custom business categories on the fly.
* **Dual Analysis:** Simultaneously predicts both the **support category** (e.g., Billing, Technical Bug, Feature Request, Account Access) and the **urgency level** (High, Medium, Low).
* **CLI Interface:** Built with Python's `argparse` for seamless command-line execution.

## Tech Stack
* **Python**
* **Hugging Face Transformers**
* **PyTorch**

## Installation & Setup

1. Clone the repository:
   ```bash
   git clone [https://github.com/JannatulYea/ai_triage_tool.git](https://github.com/JannatulYea/ai_triage_tool.git)
   cd ai_triage_tool
