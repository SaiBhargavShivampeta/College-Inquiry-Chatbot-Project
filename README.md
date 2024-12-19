# College Inquiry Chatbot Project  

## Overview  
This project involves the development of a cloud-based chatbot designed to handle common student inquiries about a college. The chatbot provides information on topics like course offerings, location, fees, on-campus facilities, and more. It leverages Google Cloud Platform (GCP) components to ensure an interactive and scalable experience.  

**Live Application:** [College Inquiry Chatbot](https://chatbot-project-443402.ue.r.appspot.com)  

## Features  
1. **Interactive Cloud-Based Chatbot System**  
   - Prompts users for their First Name, Last Name, and Email Address.
   - Collects and displays the provided information.  

2. **Student Inquiry List**  
   - Supports four distinct questions that students might ask:
     - "Does the college have a football team?"  
     - "Does it offer a Computer Science major?"  
     - "What is the in-state tuition?"  
     - "Does it provide on-campus housing?"  

3. **Response to Student Queries**  
   - Provides detailed answers to all supported questions.  

4. **Chatbot Conclusion**  
   - Displays the user's input details (First Name, Last Name, and Email Address).  
   - Displays the chatbot creator's details, including the creator’s First Name, Last Name, and School Email Address.  

5. **Hosted on GCP**  
   - The chatbot is deployed on Google App Engine.  

## Tools and Technologies  
- **Google Cloud Platform (GCP)**  
  - **IaaS:** Google Compute Engine  
  - **PaaS:** Google App Engine  
  - **SaaS:** Google Dialogflow  

- **Programming Languages & Frameworks**  
  - Python  
  - Flask (for backend development)  

## Project Requirements and Scoring  
| **Requirement**                        | **Points** |  
|----------------------------------------|------------|  
| Interactive Chatbot System             | 3          |  
| Student Inquiry List                   | 1          |  
| Response to Student Queries            | 4          |  
| Chatbot Conclusion                     | 1          |  
| Submission URL                         | 1          |  

**Total Points:** 10  

## Deployment Steps  
1. Clone this repository:  
   ```bash
   git clone https://github.com/your-repo/college-inquiry-chatbot.git  
   cd college-inquiry-chatbot

2. Install dependencies:
pip install -r requirements.txt

3. Set up your GCP project and enable App Engine.

4. Deploy to Google App Engine:
   gcloud app deploy


## How to Use
1. Visit the live chatbot application: College Inquiry Chatbot.
2. Enter your First Name, Last Name, and Email Address.
3. Ask any of the four listed questions.
4. View detailed responses and the chatbot’s concluding information.
