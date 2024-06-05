# Wikipedia Summarizer GPT App 🦜️🔗🎥

In the rapidly evolving landscape of information technology, the ability to access and synthesize information quickly and effectively is paramount. To address this need, I developed a sophisticated Wikipedia Summary helper application. This project, built using Python and hosted via Streamlit, leverages advanced natural language processing (NLP) techniques and state-of-the-art machine learning models to provide users with concise and detailed summaries of Wikipedia articles.

### Project Overview

The Wikipedia Summary helper app is designed to offer users two distinct types of summaries: a short summary for quick information retrieval and a detailed summary for comprehensive analysis. This dual-summary feature caters to diverse user needs, from casual information seekers to researchers requiring in-depth content.

### Tools and Technologies

**Python** was chosen as the core programming language for this project and **Google Colab** was chosen to deploy the code since it offers free GPUs and TPUs boosting performance. The web application is hosted on **Streamlit**, a powerful framework that simplifies the deployment of machine learning models and interactive applications. Research was curated using **Wikipedia** API in Python. This library makes it easy to access and parse data from Wikipedia.

### Machine Learning Model

At the heart of the application is the **Google Flan-T5 XXL model** was the transformer model selected for this analysis. It was sourced from Hugging Face's model repository. Flan-T5 is renowned for its superior performance in generating coherent and contextually relevant text. The XXL variant, being one of the largest in the Flan-T5 series, was selected as it ensures high-quality summary generation due to its extensive training on diverse datasets.

![image](https://github.com/GanVib18/Wikipedia-Summarizer-GPT/assets/89754504/2325c6dc-d3f2-4e65-aeb2-f60902b55998)

Model Page: https://huggingface.co/google/flan-t5-xxl

**Summarization**: The Flan-T5 model is fine-tuned to generate both concise and detailed summaries. The model's architecture allows it to understand the context and produce summaries that retain the core information while varying in length and detail based on user requirements.

**API Integration**: The application integrates with multiple APIs to fetch real-time data and enhance the summarization process. For instance, Wikipedia's API is used to retrieve article content dynamically, ensuring that users always get the most up-to-date information.

### User Interface and Experience

The application's user interface, developed with Streamlit, is designed to be intuitive and user-friendly. Users can input the topic of interest, and the application fetches the corresponding Wikipedia article. With a simple click, they can generate both short and detailed summaries, displayed clearly on the interface. This streamlined process ensures that even users with minimal technical knowledge can benefit from the app's advanced capabilities.

### Future Enhancements

Future enhancements could include expanding the range of supported languages, incorporating user feedback mechanisms to continually improve summary quality, and integrating with other knowledge bases beyond Wikipedia to broaden the scope of information accessible through the app.

### Conclusion

The development of the Wikipedia Summary helper application underscores my capability to harness advanced technologies and methodologies to solve real-world problems. By leveraging Python, Streamlit, and the Google Flan-T5 XXL model, I created a tool that significantly enhances the way users interact with and consume information.
