# DeepSeek-R1-demo

## Overview
This repository provides a **Streamlit web application** that runs the **DeepSeek-R1** model locally. The app allows users to input text prompts and receive AI-generated responses from the DeepSeek R1 model in an interactive and user-friendly interface.

## Features
- **Local Execution**: Runs the DeepSeek R1 model on your machine.
- **Streamlit UI**: A lightweight and interactive web-based interface.
- **Real-time Inference**: Get responses from the DeepSeek R1 model instantly.
- **Easy Setup**: Simple installation and execution steps.

## Prerequisites
Ensure you have the following installed:
- **Python 3.8+**
- **pip**
- **DeepSeek R1 Model** (local installation)
- **Virtual environment** (optional but recommended)

## Installation
### 1. Clone the Repository
```sh
git clone https://github.com/yashksaini-coder/streamlit-deepseek-r1.git
cd streamlit-deepseek-r1
```

### 2. Set Up a Virtual Environment (Recommended)
```sh
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```

### 3. Install Dependencies
```sh
pip install -r requirements.txt
```

### 4. Download the DeepSeek R1 Model
Ensure that you have downloaded and installed the DeepSeek R1 model locally. Follow the official DeepSeek R1 installation guide: [DeepSeek AI](https://deepseek.ai/).

## Running the Web App
Once everything is set up, start the Streamlit app:
```sh
streamlit run app.py
```
This will launch the app in your default web browser.

## Usage
1. Open the app in your browser.
2. Enter a text prompt in the input box.
3. Click the **Submit** button to generate a response.
4. View the AI-generated response on the screen.

## Project Structure
```
DeepSeek-R1-demo/
├── .python-version
├── .venv/
│   ├── .gitignore
│   ├─] CACHEDIR.TAG (ignored)
│   ├─] etc/ (ignored)
│   ├─] include/ (ignored)
│   ├─] Lib/ (ignored)
│   ├─] pyvenv.cfg (ignored)
│   ├─] Scripts/ (ignored)
│   └─] share/ (ignored)
├── LICENSE
├── main.py
├── pyproject.toml
├── README.md
├── requirements.txt
└── uv.lock
```

## Dependencies
Ensure the `requirements.txt` contains:

```
streamlit
langchain_core
langchain_community
langchain_ollama
```

## Contributing
Feel free to submit issues, feature requests, or contribute via pull requests!

## License
This project is licensed under the **GNU GENERAL PUBLIC LICENSE**.

## Contact
For any queries, reach out via [Twitter](https://x.com/yash_k_saini) or visit [Linkedin](https://www.linkedin.com/in/yashksaini/).

