# My Digital Clone
This project aims to develop an AI model that automatically responds to WhatsApp messages with personalized responses. The AI model will be trained using Python and the goal is to mimic my personality as much as possible.


## Table of Contents
1. [Prerequisites](#prerequisites)
2. [Installation](#installation)
3. [Training the Model](#training-the-model)
4. [Deploying the Model](#deploying-the-model)
5. [Usage](#usage)


## Prerequisites

1. Python 3.10
2. [WhatsApp Web](https://web.whatsapp.com/)

## Installation

1. **Clone the repository**
    ```bash
    git clone https://github.com/MSH4R1F/my-digital-clone.git
    ```

2. **Navigate to the project directory**
    ```bash
    cd my-digital-clone
    ```

3. **Install required packages**
    ```bash
    pip install -r requirements.txt
    ```

4. **Configure environment variables**
    Create a `.env` file in the root directory and add the necessary variables such as API keys or tokens if needed.


## Training the Model

1. **Data Collection**

    You will have to provide your own past messages. You can do this by using the export button on your WhatsApp and export it in the format you want it to.

2. **Data Preprocessing**

    Run the `data_preprocessing.py` script to clean and prepare the data for training.
    
    ```bash
    python data_preprocessing.py
    ```

3. **Training**

    Run the `train_model.py` script to train your model.
    
    ```bash
    python train_model.py
    ```

## Deploying the Model

Run the `deploy.py` script to deploy your trained model.

```bash
python deploy.py
```
## Usage

After deploying, the model will start listening for incoming WhatsApp messages. Once it detects a message from an allowed contact list or group, it will generate a response based on the trained model and send it automatically.
