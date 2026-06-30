# Vighnesh-Chorge

# 👋 Hi there, I'm Vighnesh Chorge

Welcome to my GitHub profile!

---

## 🧑‍💻 About Me

- 🎓 Computer Engineering graduate from MGM College of Engineering, University of Mumbai
- 🤖 Passionate about Artificial Intelligence, Machine Learning, Data Science, and Software Development
- 🧠 Skilled in building LLM-powered systems — Retrieval-Augmented Generation (RAG) pipelines, vector search (FAISS, sqlite-vec), embeddings, local inference via Ollama, and prompt/persona engineering
- 🐍 Python is my go-to language for building intelligent applications, automation tools, and backend systems
- 📊 Experienced in data analysis and machine learning using Pandas, NumPy, Matplotlib, Seaborn, and Scikit-learn
- 🌐 Building web applications, APIs, and automation solutions using Flask, MySQL, and Firebase
- 🚀 Developed projects in NLP, LLM/RAG systems, recommendation systems, predictive analytics, AI-powered news summarization, and intelligent automation
- ✨ Always curious to learn, build innovative products, and contribute to meaningful technology projects

---

## 📜 Certifications

- 🧠 Python Programming (Aptech Certified)  
- 🤖 Artificial Intelligence & Machine Learning (Aptech Certified)

---

## 🧪 Internships

- 🏢 **Prudent Infotech** – *AI Intern*  
  *April 2026 – Present*  
  Evaluating and benchmarking large language models (GPT-4.1 API vs. open-source alternatives like Llama 3.3 70B via Groq, and self-hosted A100 deployments) to guide production model selection. Designing and optimizing a real estate information chatbot for a live client, with a modular architecture covering SQLite-based vector retrieval, a Retrieval-Augmented Generation (RAG) pipeline, and a voice interaction module.

- 🏢 **Indian Oil Corporation Limited (IOCL)** – *AI/ML Intern*  
  *June 2025 – August 2025*  
  Developing an AI model to identify and flag negative news articles about IOCL using NLP techniques. The project involved collecting news data, performing sentiment analysis, and building a pipeline to detect reputation-sensitive content using Python and machine learning libraries.

- 🏢 **Ganishka Technology** – *AI/ML Intern*  
  *July 2024 – December 2024*  
  Worked on NLP and machine learning-based solutions as part of the product team.Developed the [Resume Screening System](https://github.com/VighneshChorge/Resume-Screening-System) – a Flask-based application using `spaCy` to extract and evaluate key candidate information from resumes, streamlining the recruitment process.

---

## 📚 Publications

- Chorge, A. *Multi-Source News Synthesizer Using Deep Learning*.  
  **International Journal of Innovative Research in Technology (IJIRT)**, ISSN 2349-6002, Vol. 12, Issue 11, April 2026.  
  Impact Factor: 8.412.

---

## 🧾 Roles & Contributions

- 🎭 **Cultural Co-Head** *(July 2024 – June 2025)*  
  - Co-led the college cultural committee, planning and executing major cultural fests, inter-college competitions, and themed campus events.  
  - Managed student teams, coordinated with faculty and external partners, and handled budgeting and sponsorship activities. 
  - Boosted student participation and strengthened the college’s cultural presence through high-quality, well-organized events.

- 🧢 **Ex NSS Event Team Head** *(July 2024 – June 2025)*  
  - Led the NSS event management team, organizing awareness drives, social outreach events, and technical activities.  
  - Handled end-to-end planning, logistics, and team coordination for large-scale programs.  
  - Strengthened leadership, communication, and multitasking skills through on-ground execution.

- 🤝 **NSS Volunteer** *(July 2023 – June 2024)*  
  - Contributed over 120+ hours to community service activities such as cleanliness drives, blood donation camps, and awareness campaigns.  
  - Actively participated in team-based initiatives promoting social responsibility and civic engagement.  
  - Developed teamwork, empathy, and public engagement skills.

---

## 🚀 Skills

- **Languages & Tools:** Python, SQL, C/C++ (Basic), Power BI, Tableau  
- **Libraries:** Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib, Flask  
- **Database:** MySQL  
- **Soft Skills:** Problem-solving, Creativity, Adaptability, Eye for Detail, Communication, Leadership

---

## 🛠️ Projects

Here are some of the projects I've worked on:

- 🏠 [Real Estate Chatbot — RAG-Powered Property Assistant](https://github.com/VighneshChorge/realestate-chatbot)  
  A retrieval-augmented chatbot built during my AI internship at Prudent Infotech that answers questions about a real-estate listings catalogue using only grounded, verifiable data. Routes incoming questions into either a structured SQL "list mode" (for catalogue-style queries like "show me all 2BHK in Pune") or a semantic vector-search mode (for detail-level questions over brochures, inspection reports, and FAQs), then feeds the retrieved context into a locally-hosted Llama 3.1 model via Ollama. Built on SQLite extended with `sqlite-vec` for native vector search, with `bge-small-en-v1.5` embeddings — no separate vector database required, and answers always cite the source listing.
  
- 🤖 [Portfolio Chatbot — Local RAG Assistant](https://github.com/VighneshChorge/portfolio-chatbot)  
  A persona-driven RAG chatbot that sits on my portfolio site and speaks on my behalf to recruiters, answering questions about my projects, skills, and experience strictly from a curated Markdown knowledge base. Chunks the knowledge base by section, embeds chunks with `BAAI/bge-small-en-v1.5` via `fastembed`, and retrieves the most relevant context for each query before generating a grounded, third-person answer with a local Llama 3.2 / Llama-3.1-8B model through Ollama. Includes guardrails tested against adversarial prompts (salary questions, phone-number requests, prompt-injection attempts) so it deflects what it shouldn't answer while staying in character.
  
- 📘 [Notes-to-Answer Model](https://github.com/VighneshChorge/Notes-to-answer-model)  
  A lightweight RAG pipeline that turns a PDF of notes into exam-ready answers: extracts text with PyMuPDF, splits it into sentence-level chunks, embeds each chunk with Sentence-Transformers, retrieves the most relevant context for a given question using FAISS vector search, and generates a polished, detailed answer with Falcon-7B-Instruct. Supports multiple questions in a single run and was designed specifically for study, assignment, and exam-prep use cases.
  
- 📖 [DocTalk — Chat with Your Documents Locally](https://github.com/VighneshChorge/DocTalk-Chat-with-Your-Documents-Locally)  
  A local PDF Q&A tool that demonstrates the core idea behind RAG through pure context injection rather than embeddings: PyMuPDF extracts all text from an uploaded PDF, that text is injected directly into Llama 3.2's system prompt, and the model answers user questions strictly from the document — entirely offline, with no vector database, fine-tuning, or API key required.
  
- 📰 [AI-Powered News Synthesizer](https://github.com/VighneshChorge/News-Synthesizer)  
  A Colab-based app that summarizes the same story as covered across multiple news sources into a single coherent summary, using a BART-based abstractive summarization model. Paired with a responsive frontend hosted via Google Drive, and the underlying approach was later written up and published in IJIRT.
  
- 🐦 [Twitter Sentiment Analysis for Stock Forecasting](https://github.com/VighneshChorge/-Twitter-Sentiment-Analysis-for-Stock-Market-Forecasting)  
  Combines tweet-level sentiment scoring (VADER + TextBlob) with an LSTM time-series model to forecast short-term stock price movement, treating social sentiment as a leading signal alongside historical price data. Achieved ~85% prediction accuracy on the evaluated stock data.
  
- 🛒 [Product Recommendation for Walmart Products](https://github.com/VighneshChorge/Product-Recommendation-for-Walmart-Products)  
  A content-based recommender for e-commerce products that vectorizes product descriptions with TF-IDF and ranks similar items using cosine similarity, surfacing related products without needing any user purchase history.
  
- 🎬 [Movie Recommendation System](https://github.com/VighneshChorge/Movie-Recommendation-System)  
  A content-based movie recommender that compares movie metadata (genre, cast, plot keywords) using cosine similarity, wrapped in a simple Tkinter desktop GUI so users can search for a title and get similar recommendations instantly.
  
- 🏠 [Housing Price Prediction using AdaBoost](https://github.com/VighneshChorge/Housing-Price-Prediction-using-AdaBoost)  
  A regression pipeline that predicts housing prices from key structural and location features, with dedicated outlier handling and feature preprocessing, using an AdaBoost ensemble to boost weaker learners into a more accurate final model.
  
- 📬 [SVM-based Email Spam Classifier](https://github.com/VighneshChorge/SVM-based-Email-Spam-Classifier)  
  A text classification system that vectorizes SMS/email message content and uses a Support Vector Machine to separate spam from legitimate messages, evaluated on classification accuracy and precision/recall for the spam class.
  
- ✍️ [Autocorrect System using Naive Bayes](https://github.com/VighneshChorge/Autocorrect-System-using-Naive-Bayes)  
  An NLP-based spelling-correction tool that models word likelihoods with a Naive Bayes approach, generating and ranking candidate corrections for misspelled input words based on edit distance and probability.
  
- 📂 [Resume Screening System](https://github.com/VighneshChorge/Resume-Screening-System)  
  A Flask web application built during my Ganishka Technologies internship that uses `spaCy`'s Named Entity Recognition to automatically extract key candidate information (skills, education, experience) from uploaded resumes, helping recruiters screen applicants faster.
  
- 📊 [Academic Evaluation System](https://github.com/VighneshChorge/Academic-Evaluation-System)  
  A Flask-based web application for managing and evaluating student academic performance, providing a structured interface for recording assessments and tracking performance over time.
  
- 🌸 [Artificial Neural Network (Iris Dataset)](https://github.com/VighneshChorge/Artificial-Neural-Network-Implementation)  
  A custom feed-forward Artificial Neural Network built with Keras to classify the classic Iris flower dataset into its three species, used as a hands-on implementation of core ANN concepts like layers, activation functions, and backpropagation.
  
- 🍷 [Wine Quality Prediction](https://github.com/VighneshChorge/Wine-Quality-Prediction-Using-Logistic-Regression)  
  A Logistic Regression model that predicts white wine quality from measurable chemical attributes (acidity, sugar, sulphates, alcohol content, etc.), framed as a classification problem to distinguish higher- and lower-quality wines.
  
---

## 📫 Let's Connect!

- [LinkedIn](linkedin.com/in/vighnesh-chorge)  
- 📧 Email: [VighneshChorge2@gmail.com](mailto:VighneshChorge83@gmail.com)  

Thanks for stopping by! 😊
