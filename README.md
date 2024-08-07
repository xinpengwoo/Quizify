<h1 align="center">Quizify - AI-Generated Assessment Tool</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white" alt="Streamlit"/>
  <img src="https://img.shields.io/badge/LangChain-000000?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAxMjggMTI4Ij4KPHBhdGggZD0iTTAgNjRjMC00LjA0NiAyLjAzMS03Ljk2IDUuMzQzLTEwLjAzOEw1Mi4zNDMgMy4xNTNDNTQuMzc0IDIuMDQ2IDU2LjY5NyAxLjQ0MSA1OSAxLjQ0MXYzMkwzNiA2NGgyNlY0NGg0MHYyMEg3Mi4zNDNMMTAyLjY1NyA5NC42MzhDOTkuMzQ2IDk2LjY0IDk3IDk5LjU1NCA5NyAxMjNINDYuNjU3TDMuNjU3IDg5LjYzOEMxLjM0NiA4Ny42NCAwIDgxLjgzOCAwIDc2di0xMnoiIGZpbGw9IiNGRkYiLz4KPC9zdmc+Cg==" alt="LangChain"/>
  <img src="https://img.shields.io/badge/Chroma%20DB-00AA00?style=for-the-badge&logo=chroma&logoColor=white" alt="Chroma DB"/>
  <img src="https://img.shields.io/badge/Vertex%20AI-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white" alt="Vertex AI"/>
</p>


# About 🧩
Students and learners often struggle to reinforce their understanding of various topics and obtain timely feedback. To address this, an AI-generated assessment and quiz tool is developed to provide instant feedback and comprehensive explanations, dynamically generating quizzes based on user-provided documents to offer a tailored and user-friendly learning experience.

# Features 🚀
- Comprehensive quiz generation UI using Streamlit
- PDF document processing with Streamlit and LangChain
- Scalable document processing framework with Chroma DB
- Optimized backend architecture with Vertex AI embeddings and LangChain


# Installation 🛠️
1. Clone the repository to your local machine
2. Create a conda virtual environment with `python==3.8.19` and install the required dependencies by running `pip install -r requirements.txt`
3. Setup your Google Cloud Project, enable the necessary APIs and a service account, and install GCP SDK following the [official tutorial](https://cloud.google.com/sdk/docs/install-sdk).
4. Export the GCP credentials to an environment varibale by running `export GOOGLE_APPLICATION_CREDENTIALS="YOUR-GOOGLE-CREDENTIAL-JSON-PATH"`. More information on [Application Default Credentials (ADC)](https://cloud.google.com/docs/authentication/application-default-credentials#personal)
5. Fill `embed_config[project]` with your GCP project_id in  `main.py`.
6. Start the application by running `streamlit run main.py`.
7. Navigate to `http://localhost:8501` in your web browser.

# Demo 📷

A short introduction video hosted on Loom:

[![Watch the video](assets/video_thumbnail.png)](https://www.loom.com/share/e3587cd1fec14d70bc0fd6e39a1585f2)

# Acknowledgement
This project is based on [mission-quizify](https://github.com/radicalxdev/mission-quizify).

# Contact
If you have any question, please email xinpengwoo@gmail.com.