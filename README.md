# Medical Chatbot using Llama2

## Features

The Medical Chatbot offers the following features:

1. **Chatbot:**

2. **User-friendly Interface:**

3. **Answer questions using user's data**

## Application interface

![image](https://github.com/Msparihar/Medical-Chatbot-using-Llama2/assets/75237981/e81d0b04-3718-45ee-a85d-78abebbbf9fb)

## Techstack Used:

- Python
- LangChain
- Flask
- Meta Llama2
- Pinecone

## How to run?
### STEPS:

Clone the repository

```bash
git clone https://github.com/Msparihar/Medical-Chatbot-using-Llama2.git
```

### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n mchatbot python=3.8 -y
```

```bash
conda activate mchatbot
```

### STEP 02- install the requirements
```bash
pip install -r requirements.txt
```


### Create a `.env` file in the root directory and add your Pinecone credentials as follows:

```ini
PINECONE_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
PINECONE_API_ENV = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
```


### Download the quantized model from the link provided in the model folder & keep the model in the model directory:

```ini
## Download the Llama 2 Model:

llama-2-7b-chat.ggmlv3.q4_0.bin


## From the following link:
https://huggingface.co/TheBloke/Llama-2-7B-Chat-GGML/tree/main
```

```bash
# run the following command
python store_index.py
```

```bash
# Finally run the following command
python app.py
```

Now,
```bash
open up localhost:
```

## Contribution

Contributions to the Fire Detection project are welcome! If you'd like to contribute, please follow these steps:

1. Fork the repository on GitHub.

2. Create a new branch from the `main` branch.

3. Make your modifications and enhancements.

4. Test your changes thoroughly.

5. Commit and push your changes to your forked repository.

6. Submit a pull request to the main repository, describing your changes in detail.

Please ensure your contributions adhere to the project's coding standards and guidelines.

## ## License

This project is licensed under the [MIT License](LICENSE). Feel free to modify and distribute it according to the terms of the license.

## Contact

If you have any questions, suggestions, or feedback regarding this project, please contact the project maintainer at manishsparihar2020@gmail.com

<hr>

I really appreciate your interest in this project and hope you found this project helpful! Keep Exploring!


