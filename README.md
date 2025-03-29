# Smart India Hackathon Workshop
# Date:29/03/2025
## Register Number:212224240022
## Name:BARATH S
## Problem Title
SIH 1653: Web based Selector-Applicant Simulation Software
## Problem Description
Background: Recruitment and Assessment Centre (RAC) under DRDO, Ministry of Defence carries out interviews for applications received against advertised vacancies and for promotion to next higher grade for scientific manpower inducted within DRDO. Description: The process of interviewing is a challenging task. An unbiased objective interviewing process helps identify the right talent. The basic process of an interview involves posing a set of questions by an interviewer and thereafter evaluating responses from candidates. Thus, the questions asked should be relevant and match the area/ expertise of the applicant and the responses should also be of relevance w.r.t. the question asked. Expected Solution: The proposed solution should provide experts as well as candidates a real life Board Room experience, starting with initial ice-breaking questions leading to in-depth techno-managerial (depending on the level of candidate) questions. It shall also be able to provide a quantifiable score for experts as well as the candidate for the relevancy of questions w.r.t. the area/ expertise of the applicant. Similarly, candidate responses should also be graded for relevancy w.r.t. the question asked, finally assisting in arriving at an overall score for the subject knowledge of the candidate and thus his/ her suitability against the advertised post.

## Problem Creater's Organization
Ministry of Defence

## Idea
To enhance the interview process at the Recruitment and Assessment Centre (RAC) under DRDO, integrating Artificial Intelligence (AI) can significantly improve efficiency, reduce biases, and provide a more objective evaluation of candidates. AI-driven tools can analyze candidate responses, both verbal and non-verbal, assessing technical knowledge and behavioral traits. For instance, platforms like HireVue utilize AI to evaluate video interviews, analyzing verbal and facial cues to predict job performance and cultural fit. Implementing such technologies can assist experts in formulating relevant questions tailored to each candidate's expertise, ensuring a more personalized and effective interview experience.

Incorporating AI into the interview process also aids in standardizing evaluations, which is crucial for maintaining fairness and objectivity. Structured interviews, where each candidate is asked the same set of questions, have been shown to have higher interrater reliability and are less prone to biases. AI can facilitate this by generating consistent, job-relevant questions and providing real-time analysis of responses, helping interviewers focus on assessing candidates' suitability for the role based on their expertise and knowledge. This approach aligns with best practices for conducting unbiased interviews, as it minimizes the influence of unconscious biases and ensures that evaluations are based on objective criteria.

Furthermore, AI can assist in mitigating biases that may arise from traditional interview methods. Studies have shown that AI can effectively minimize sentiment-driven biases by analyzing interview dynamics and emphasizing skills and knowledge over emotional sentiments. By implementing AI-driven assessments, RAC can enhance the objectivity of the interview process, ensuring that candidates are evaluated based on their qualifications and fit for the role, rather than subjective perceptions. This technology also supports the creation of a diverse and inclusive hiring process, as AI can be programmed to recognize and counteract potential biases, leading to more equitable outcomes.

## Proposed Solution / Architecture Diagram

![WhatsApp Image 2025-03-29 at 10 40 23_41c2e0ef](https://github.com/user-attachments/assets/621bbd72-30c2-43de-a00e-22d7d49cc243)

## Use Cases

![WhatsApp Image 2025-03-29 at 10 42 31_6dcf50be](https://github.com/user-attachments/assets/674e440e-f191-4dcc-8e55-b0440a9d772a)

## Technology Stack
Technology Stack for AI-Driven Interview Process at RAC (DRDO)

To build an AI-powered recruitment system, a combination of machine learning, natural language processing (NLP), video analytics, cloud computing, and database management is required. Below is a structured technology stack for the system:

⸻

1. Frontend (User Interface & Candidate Interaction)

Technologies:
	•	React.js / Angular / Vue.js – For building an interactive and responsive UI.
	•	HTML5, CSS3, JavaScript (ES6+), Bootstrap / Tailwind CSS – For structuring and styling the web application.
	•	WebRTC – For real-time video interviews.

Purpose:
	•	Provides candidates and interviewers with a smooth, interactive, and intuitive user experience.

⸻

2. Backend (Application Logic & API Management)

Technologies:
	•	Node.js (Express.js) / Django (Python) / Spring Boot (Java) – For handling business logic and API requests.
	•	GraphQL / REST API – For communication between frontend and backend.
	•	FastAPI (Python) – For deploying AI models efficiently.

Purpose:
	•	Manages interview sessions, processes data, and interacts with AI modules.

⸻

3. Artificial Intelligence (AI & Machine Learning Models)

Technologies:
	•	NLP & Speech Processing:
	•	Google Speech-to-Text / IBM Watson Speech API – For transcribing and analyzing spoken responses.
	•	spaCy / NLTK / Transformers (BERT, GPT-based models) – For evaluating verbal responses.
	•	Facial & Behavioral Analysis:
	•	OpenCV / MediaPipe / DeepFace / Affectiva – For analyzing facial expressions, emotions, and body language.
	•	Machine Learning Models:
	•	TensorFlow / PyTorch / Scikit-Learn – For training and deploying AI models.
	•	Bias Mitigation Algorithms:
	•	AI Fairness 360 (IBM) / Fairlearn (Microsoft) – For ensuring unbiased AI evaluations.

Purpose:
	•	AI processes candidate responses, scores interviews, and ensures fairness.

⸻

4. Video Processing & Storage

Technologies:
	•	FFmpeg / OpenCV – For video recording, compression, and analysis.
	•	AWS S3 / Google Cloud Storage / Azure Blob Storage – For storing interview recordings securely.
	•	HLS / MPEG-DASH – For smooth video playback.

Purpose:
	•	Ensures efficient handling and storage of candidate interview recordings.

⸻

5. Data Storage & Management

Technologies:
	•	PostgreSQL / MySQL – For structured interview data.
	•	MongoDB / Firebase – For unstructured and real-time candidate interaction data.
	•	Elasticsearch – For efficient search and analytics.

Purpose:
	•	Stores candidate profiles, interview results, and AI-driven assessments securely.

⸻

6. Cloud & Infrastructure (Deployment & Scalability)

Technologies:
	•	AWS / Google Cloud / Azure – For hosting the application and AI models.
	•	Kubernetes / Docker – For containerization and microservices deployment.
	•	CI/CD (Jenkins / GitHub Actions / GitLab CI) – For automated deployment.

Purpose:
	•	Ensures high availability, security, and scalability of the system.

⸻

7. Security & Compliance

Technologies:
	•	OAuth 2.0 / JWT – For secure authentication.
	•	GDPR, HIPAA, ISO 27001 Compliance – For data privacy and security.
	•	WAF (Web Application Firewall) / Cloudflare – For DDoS protection.

Purpose:
	•	Protects candidate data and ensures compliance with security regulations.

⸻

8. HR & Recruitment System Integration

Technologies:
	•	SAP SuccessFactors / Workday / Greenhouse API – For integration with existing HR software.
	•	Zapier / Apache Kafka – For connecting various data pipelines and automation.

Purpose:
	•	Syncs AI-driven interview results with recruitment workflows

## Dependencies
Dependencies for AI-Driven Interview Process at RAC (DRDO)

Here’s a list of key dependencies for implementing an AI-driven interview system, categorized based on different system components.

⸻

1. Frontend (User Interface & Candidate Interaction)

📌 Dependencies:
	•	React.js / Angular / Vue.js → Frontend framework
	•	Bootstrap / Tailwind CSS → UI styling
	•	WebRTC → Real-time video streaming
	•	Axios / Fetch API → Handling API requests

Why?
	•	Ensures smooth candidate interaction and real-time video interviews.

⸻

2. Backend (API & Business Logic)

📌 Dependencies:
	•	Node.js (Express.js) / Django / FastAPI → Backend framework
	•	GraphQL / REST API (Flask-RESTful) → API communication
	•	JWT / OAuth2 → Secure authentication
	•	Celery / Redis → Background task processing

Why?
	•	Manages interview sessions, processes AI results, and secures API calls.

⸻

3. AI & Machine Learning (Candidate Evaluation)

📌 Dependencies:
	•	Natural Language Processing (NLP):
	•	spaCy / NLTK / Transformers (Hugging Face) → Text processing
	•	SpeechRecognition / Google Speech-to-Text → Verbal response analysis
	•	Facial & Behavioral Analysis:
	•	OpenCV / MediaPipe / DeepFace / Affectiva → Facial emotion recognition
	•	Machine Learning Models:
	•	TensorFlow / PyTorch / Scikit-Learn → Model training
	•	Fairlearn / AI Fairness 360 (IBM) → Bias mitigation

Why?
	•	Enables AI-powered assessment of verbal, non-verbal, and facial cues.

⸻

4. Video Processing & Storage

📌 Dependencies:
	•	FFmpeg / OpenCV → Video processing
	•	AWS S3 / Google Cloud Storage → Secure video storage
	•	HLS / MPEG-DASH → Adaptive video streaming

Why?
	•	Ensures efficient handling and storage of candidate video responses.

⸻

5. Database & Storage

📌 Dependencies:
	•	PostgreSQL / MySQL → Structured interview data
	•	MongoDB / Firebase → Unstructured candidate interaction data
	•	Elasticsearch → Fast search and analytics

Why?
	•	Stores candidate profiles, AI results, and reports securely.

⸻

6. Cloud & DevOps (Deployment & Scalability)

📌 Dependencies:
	•	Docker / Kubernetes → Microservices and containerization
	•	AWS Lambda / Google Cloud Functions → Serverless processing
	•	Jenkins / GitHub Actions → CI/CD pipeline for deployment

Why?
	•	Ensures high availability, auto-scaling, and secure deployment.

⸻

7. Security & Compliance

📌 Dependencies:
	•	bcrypt / Argon2 → Password hashing
	•	Helmet.js / CSRF-Protection → Security headers
	•	Cloudflare / WAF → DDoS protection

Why?
	•	Protects sensitive candidate data and interview results.

⸻

8. HR & Recruitment System Integration

📌 Dependencies:
	•	SAP SuccessFactors API / Workday API → HR software integration
	•	Apache Kafka / Zapier → Automating workflows

Why?
	•	Seamlessly integrates AI interview results with existing HR systems.

⸻

Conclusion

These dependencies form the backbone of the AI-driven interview process, ensuring real-time evaluation, security, fairness, and seamless integration with HR systems.

Would you like a detailed dependency installation guide for a specific tech stack
