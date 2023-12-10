# 🚀 AI Document Navigator and Insight Extractor

Welcome to the AI Document Navigator and Insight Extractor! A cutting-edge tool harnessing the power of AI to revolutionize document analysis, navigation, and insight extraction.

# 🌟 Features

Advanced NLP Techniques: Leverage state-of-the-art natural language processing to dissect and interpret document content.

Effortless Navigation: Quickly search for specific information within documents, enhancing productivity and efficiency.

Insight Extraction: Extract valuable insights from documents to uncover hidden patterns and knowledge.

# 🔧 Tech Stack
The AI-powered Document Navigator and Insight Extractor is built using the following technologies:

Frontend: React.js, HTML, CSS
Backend: Node.js(18+), Express.js, Typescript
Database: MongoDB
AI and NLP: Python(3.10), TensorFlow, Natural Language Toolkit (NLTK), OPENAI API
OCR: Optical Character Recognition API (e.g., Tesseract)

🛠️ Installation
To install and run the AI-powered Document Navigator and Insight Extractor locally, follow these steps:

* Clone the repository from GitHub: git clone https://github.com/C4IR-Practicum/c4ir_backend.git
* Install the dependencies: npm install
* Start the development server: npm run dev

# Note:
open the .env and add the needed environmnent variables the application needs to run

# 📚 Dependencies

Below are the dependencies and the version used in the backend system:

* bcrypt: 5.1.1,
* compromise: 14.10.1
* cookie-session: 2.0.0
* cors: 2.8.5,
* dotenv: 16.3.1,
* express: 4.18.2,
* express-session: 1.17.3,
* gridfs-stream: 1.1.1,
* helmet: 7.0.0,
* jsonwebtoken: 9.0.2,
* mammoth: 1.6.0,
* mongoose: 7.5.2,
* morgan: 1.10.0,
* multer: 1.4.5-lts.1,
* natural: 6.8.1,
* node-fs: 0.1.7,
* nodemon: 3.0.1,
* openai: 4.19.1,
* passport: 0.7.0,
* passport-google-oauth20: 2.0.0,
* pdf-parse: 1.1.1,
* ts-node: 10.9.1,
* typescript: 5.3.2

# 🔄 schema relationships and endpoints

1. Admin Endpoints (Admin Routes):

Admin Schema:
The admin schema defines the structure for storing administrator-related information, such as usernames, passwords, and administrative privileges.

Endpoints:
Admin routes handle requests related to administrator functionalities, including user management, access control, and system configuration.

2. User Endpoints (User Routes):

User Schema:
The user schema outlines the data structure for user-related details, encompassing user profiles, authentication credentials, and other user-specific information.

Endpoints:
User routes manage operations related to user interactions, authentication, and profile management. These endpoints handle requests from regular users accessing the system.

3. Conversation Endpoints:

Conversation Schema:
The conversation schema captures the interactions between users and the AI, storing details like user queries, AI responses, timestamps, and any relevant metadata.

Endpoints:
These endpoints facilitate the retrieval and storage of conversation histories, allowing users to review past interactions with the AI.

4. Regulatory Document Endpoints:

Regulatory Document Schema:
The regulatory document schema defines the structure for storing documents related to regulatory compliance. It may include fields for document content, metadata, and timestamps.

Endpoints:
Regulatory document endpoints handle operations related to the management and retrieval of documents that need to adhere to regulatory standards.

5. Reviews Endpoints:
   
Reviews Schema:
The reviews schema outlines the data structure for storing feedback and reviews submitted by users. It includes fields for user identifiers, ratings, comments, and timestamps.

Endpoints:
These endpoints manage the submission, retrieval, and analysis of user reviews, contributing to the feedback loop within the system.

# Schema Relationships:


The reviews schema  includes a relationship with the user schema to associate reviews with specific users, providing context for feedback.
User-Conversation Relationship:

The conversation schema  have a relationship with the user schema to link user interactions with the AI to specific user profiles.
User-Regulatory Document Relationship:

These relationships help establish a structured and interconnected data model, ensuring that the application can efficiently manage and retrieve information across different aspects of user interactions, administrative tasks, reviews, and regulatory document handling.

# 🎉 Conclusion


In conclusion, the AI-powered Document Navigator and Insight Extractor represent a groundbreaking fusion of advanced technologies to transform the way we interact with and glean insights from documents. This innovative tool harnesses the prowess of Natural Language Processing (NLP) and Artificial Intelligence (AI) to enable users to effortlessly navigate through document content and extract valuable insights.

With a robust tech stack encompassing React.js, Node.js, MongoDB, and a suite of AI and NLP tools such as TensorFlow, NLTK, and the OPENAI API, this project is not just a tool; it's a technological marvel. The seamless integration of Optical Character Recognition (OCR) further enhances its capabilities, making it a comprehensive solution for document analysis.
