# chatbot
Introduction to GenAI and Simple LLM Inference on CPU and fine-tuning of LLM Model to create a Custom Chatbot

Open Terminal
Run the following commands

conda create -n itrex python=3.10 -y conda activate itrex

pip install intel-extension-for-transformers

git clone https://github.com/intel/intel-extension-for-transformers.git

cd ./intel-extension-for-transformers/intel_extension_for_transformers/neural_chat/

pip install -r requirements_cpu.txt

pip install -r requirements.txt

huggingface-cli login (enter your hugging face login details)

##install jupyter and ipykernel python3 -m pip install jupyter ipykernel

##Add kernel for its environment python3 -m ipykernel install --name Neural-Chat --user

In the notebook set kernel to Neural-Chat

then open final.ipynb
