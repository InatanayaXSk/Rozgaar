# A really cool project!

# Rozgaar Portal

Rozgaar is a multilingual, AI-powered platform designed to streamline resume generation and job matching for workers in various industries. With features like voice input, manual entry, and real-time filtering, Rozgaar bridges the gap between job seekers and employers by leveraging technology to provide accessible and efficient solutions.

---

## Key Features

- **Multilingual Support:** Seamless language toggling between English and Hindi.
- **AI-Powered Resume Generation:** Uses advanced models (Llama 3.1) to generate professional resumes tailored to job categories.
- **Voice and Manual Input Modes:** Flexible options for users to input their experience and details.
- **Real-Time Resume Filtering:** Employers can filter resumes based on age, gender, locality, and experience.
- **Industry-Specific Modules:** Dedicated support for various job sectors, including Construction Work, Domestic Work, and Handicrafts.
- **Photo and Audio Integration:** Users can upload photos and provide additional details via voice.

---

## Technologies Used

- **Frontend Framework:** [Streamlit](https://streamlit.io/) for a dynamic user interface.
- **Backend Processing:** Python for data handling and integration.
- **AI Model:** Llama 3.1 via the [Ollama API](https://ollama.ai/).
- **Speech Processing:** [SpeechRecognition](https://pypi.org/project/SpeechRecognition/) and [PyDub](https://pypi.org/project/pydub/) for audio input.
- **Data Storage:** JSON-based resume storage and filtering.
- **Libraries:** PIL for image handling, Pandas for data processing, and Flask for server-side integration.

---

## Installation Guide

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-repo-url/rozgaar-portal.git
   cd rozgaar-portal
   ```

2. **Set Up a Virtual Environment:**
   ```bash
   python3 -m venv env
   source env/bin/activate   # On Windows: env\Scripts\activate
   ```

3. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Application:**
   ```bash
   streamlit run app.py
   ```

---

## Usage Instructions

1. Open the application in your browser using the displayed Streamlit URL.
2. Toggle between English and Hindi for the interface language.
3. Enter personal details and select a job category.
4. Choose between voice input or manual input for providing additional experience details.
5. Click "Generate Resume" to create a professional resume in markdown format.
6. Employers can filter resumes and view them based on specific criteria.

---



## Future Scope

- Expand language support to other regional languages.
- Add more job categories based on user demand.
- Implement a mobile-friendly UI.
- Integrate real-time notifications for job matches.

---

