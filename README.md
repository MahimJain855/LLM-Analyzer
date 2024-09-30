nstallation
1.Clone this repository to your local machine using:

  git clone https://github.com/MahimJain855.git
2.Navigate to the project directory:
 cd LLM-Analyzer
3.Install the required dependencies using pip:
  pip install -r requirements.txt
4.Set up your OpenAI API key by creating a .env file in the project root and adding your API

  OPENAI_API_KEY=your_api_key_here
Usage/Examples
1. Run the Streamlit app by executing:
  streamlit run project_main.py
2.The web app will open in your browser.

On the sidebar, you can input URLs directly.

Initiate the data loading and processing by clicking "Process URLs."

Observe the system as it performs text splitting, generates embedding vectors, and efficiently indexes them using FAISS.

The embeddings will be stored and indexed using FAISS, enhancing retrieval speed.

The FAISS index will be saved in a local file path in pickle format for future use.

One can now ask a question and get the answer based on those urls.

