# N8N-The-Intelligent-Customer-Feedback-Processor
✨ “AI-powered workflow for real-time feedback analysis and smart team notifications.”  

## ⚙️ Prerequisites

Before you start, make sure you have:  
🛠️ **n8n:** self-hosted or cloud version    
📦 **Postman:** to simulate new order webhook triggers    
💬 **Messaging app integration:** Slack/Discord/MS Teams  

## 📝 Sample Input

This workflow is triggered whenever a **new feedback** is submitted.  
The input JSON contains feedback details such as the user's name, email, and their feedback message.  
*💡 **Reminder:**   
1- Paste this code in your Postman → Body → Raw*  
*2- You can change feedback to track positive, negative, & neutral feedbacks*

### Example
```json
{
  "name": "alice",
  "email": "alice783@gmail.com",
  "feedback": "Best customer service I've ever had"
}
```

## Workflow
![image](https://github.com/user-attachments/assets/7e99c0e8-c416-49a7-9c03-0c19f40d45fb) 

