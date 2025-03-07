# VoiceGrade

# VoiceGrade: Speech-to-Text Accuracy Comparison Website

## Overview
VoiceGrade is an AI-powered academic tool that helps students and educators analyze speech accuracy compared to a given formal text. The system uses speech recognition and NLP-based text comparison to provide insights into missing points in the spoken answer and overall accuracy.

## Features
- **Speech-to-Text Conversion:** Converts spoken answers into text.
- **Accuracy Analysis:** Compares spoken text with formal text using NLP.
- **Highlight Missing Points:** Identifies words and phrases missing from the spoken response.
- **Performance Feedback:** Provides a similarity score and suggestions for improvement.
- **Interactive UI:** Users can record speech and view results in an intuitive interface.

## Use Cases in Academia
- **Assessment & Evaluation:** Educators can use it to gauge student comprehension and oral proficiency.
- **Self-Learning Tool:** Learners can practice and refine spoken responses to predefined academic prompts.
- 

### Backend Setup
```sh
# Clone the repository
git clone https://github.com/your-username/VoiceGrade.git
cd VoiceGrade/backend

# Create a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`

# Install dependencies
pip install -r requirements.txt

# Run the backend server
uvicorn main:app --reload
```

### Frontend Setup
```sh
cd ../frontend

# Install dependencies
npm install

# Start the React development server
npm start
```


## Future Enhancements
- **Multi-Language Support** for broader usability.
- **More Advanced NLP Models** for improved text understanding.
- **User Authentication** for personalized history tracking.
- **Mobile-Friendly UI** for accessibility.

## Contribution
Contributions are welcome! Feel free to fork the repo, create feature branches, and submit pull requests.

## License
This project is open-source and available under the MIT License.

