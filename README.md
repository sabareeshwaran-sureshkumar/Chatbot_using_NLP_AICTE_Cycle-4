# Chatbot using NLP (AICTE Cycle-4)

## 📌 Project Overview
This project is an AI-driven chatbot built using Natural Language Processing (NLP). It was developed as part of AICTE Cycle-4 to facilitate human-like interactions and automate responses to user queries. The chatbot is trained to understand context and generate meaningful replies based on user input.

## 🏗 Tech Stack
- **Programming Language:** Python
- **Machine Learning:** Natural Language Processing (NLP)
- **Libraries & Frameworks:**
  - TensorFlow/Keras
  - NLTK
  - SpaCy
  - Scikit-learn
  - Flask (for deployment)
- **Database:** ChromaDB
- **Model:** Llama.cpp with Biomistral 7B
- **Sentence Embeddings:** NeuML/pubmedbert-base-embeddings
- **Implementation Framework:** LangChain

## 🚀 Features
- Conversational AI with NLP-based responses
- Context-aware replies
- Integrated with a vector database (ChromaDB) for data storage
- Supports multiple domains and user queries
- Scalable and customizable

## 📂 Project Structure
```
Chatbot_using_NLP_AICTE_Cycle-4/
│-- data/                # Training data
│-- models/              # Pretrained & fine-tuned models
│-- scripts/             # Python scripts for preprocessing and training
│-- app.py               # Main Flask app for deployment
│-- requirements.txt     # Dependencies
│-- README.md            # Project documentation
```

## 🛠 Installation & Setup
1. **Clone the repository**
   ```bash
   git clone https://github.com/sabareeshwaran-sureshkumar/Chatbot_using_NLP_AICTE_Cycle-4.git
   cd Chatbot_using_NLP_AICTE_Cycle-4
   ```
2. **Create a virtual environment** (Optional but recommended)
   ```bash
   python -m venv venv
   source venv/bin/activate  # On macOS/Linux
   venv\Scripts\activate     # On Windows
   ```
3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```
4. **Run the chatbot**
   ```bash
   python app.py
   ```

## 📈 Model Training
- Data preprocessing using NLTK & SpaCy
- Fine-tuning with Biomistral 7B using Llama.cpp
- Sentence transformations with pubmedbert-base-embeddings

## 🌍 Deployment
- The chatbot can be deployed using Flask for a web-based interface.
- Can be integrated with cloud platforms like AWS/GCP for scalability.

## 📌 Future Enhancements
- Improve chatbot accuracy with Reinforcement Learning
- Deploy as a microservice with Docker and Kubernetes
- Expand knowledge base with real-time data retrieval

## 🤝 Contributing
Contributions are welcome! Feel free to fork the repository and submit a pull request.

## 📜 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📧 Contact
For any queries, reach out to:
- **Author:** Sabareeshwaran S
- **Email:** sabareeshjr12@gmail.com
- **GitHub:** https://github.com/sabareeshwaran-sureshkumar

---
Feel free to update your email and other details before using this `README.md`. 🚀
