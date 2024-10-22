# Legal-Documentation-Assistant

## Table of Contents

- [Project](#legal-documentation-assistant)
  - [Table of Contents](#table-of-contents)
  - [About The Project](#about-the-project)
  - [Demo](#demo)
  - [Tech Stack](#tech-stack)
  - [File Structure](#file-structure)
  - [Screenshots of Website](#screenshots-of-the-website)
  - [Contributors](#contributors)
  - [License](#license)

## About The Project

Legal documentation can be a complicated and time-consuming process, especially for individuals and small businesses who may not have access to legal resources. In addition, the language and jargon used in legal documents can be difficult for non-lawyers to understand, which can lead to errors and misunderstandings. 

**Objective**: The objective of this project is to develop an AI-powered solution that can simplify legal documentation for individuals and small businesses in India, by automatically drafting legal documents in plain language and using easy-to-understand terms. 

**Features**: 

1. User-friendly interface to input relevant information such as parties involved, terms of the agreement, and other necessary details. 

2. AI-powered document generation that automatically recommends legal documents based on user query. 

3. Ability to customize legal documents based on the specific needs of the user. 

4. Integration with existing legal resources and databases to ensure accuracy and completeness of the legal documents. 

**Impact**: The proposed solution can greatly benefit individuals and small businesses in India, who often face challenges with legal documentation due to limited access to legal resources. By simplifying legal documentation, this solution can potentially save time, reduce errors, and increase access to justice. 

**Data**: We have made use of [LawRato](https://lawrato.com/legal-documents) for the dataset of legal documents.

## Demo

https://github.com/PritK99/Legal-Documentation-Assistant/assets/103848930/023f19a9-dea2-458b-ae53-6f6c7f36d74f

## Tech Stack

- ![react](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)

- ![tailwind](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)

- ![python](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue)

- ![flask](https://img.shields.io/badge/flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white)

- ![psql](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)

## File Structure
```
👨‍💻Legal-Documentation-Assistant
 ┣ 📂assets                            // Contains all the reference gifs, images
 ┣ 📂client                            // Frontend        
 ┃ ┣ 📂src                                      
 ┃ ┃ ┣ 📂components  
 ┃ ┃ ┃ ┣ 📄Chat.jsx
 ┃ ┃ ┣ 📄about.jsx
 ┃ ┃ ┣ 📄Faq.jsx
 ┃ ┃ ┣ 📄Home.jsx
 ┃ ┃ ┣ 📄InputForm.jsx
 ┃ ┃ ┣ 📄LoginPage.jsx
 ┃ ┣ 📂public 
 ┃ ┃ ┣ 📄index.html
 ┣ 📂model                             // Standalone model         
 ┃ ┣ 📄similarity.py                   // Based on Cosine Similarity
 ┃ ┣ 📄bot.py    
 ┃ ┣ 📄chat.py                         // To chat with the standalone model
 ┃ ┣ 📄model.py                        // Based on Bag of Words
 ┃ ┣ 📄train.py                        
 ┃ ┣ 📄dataset.py 
 ┃ ┣ 📄util.py   
 ┃ ┣ 📄trained_model.pth
 ┃ ┣ 📄intents.json                    // Dataset 
 ┣ 📂server                            // Backend 
 ┃ ┣ 📂docs  
 ┃ ┃ ┣ 📄localfile.docx
 ┃ ┃ ┣ 📄Output2.docx
 ┃ ┣ 📄app.py 
 ┃ ┣ 📄createdatabase.py  
 ┃ ┣ 📄requirements.txt      
 ┣ 📄README.md
``` 
