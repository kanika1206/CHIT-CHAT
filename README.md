# 💬 Azure FAQ Chatbot

CHIT-CHAT is an AI-powered FAQ chatbot for IIT Jammu, built using Microsoft Azure Bot Services without writing any backend code. It provides users with instant answers and is deployed as a live Azure Web App.


## 🚀 Live Demo
👉 [Click here to talk to the bot](https://chitchitchat.azurewebsites.net)

## 🛠️ Technologies Used
- Azure Bot Service
- Azure Web App
- Azure QnA Maker / Language Studio
- Bot Framework Web Chat

## 📸 Screenshots

### 🔹 Chatbot Interface
![Chatbot UI](screenshots/bot-ui.png)

### 🔹 Sample Response
![Chatbot Response](screenshots/bot-response.png)

### 🔹 Chat History Support
![Chatbot History](screenshots/chat-history.png)

## 🧠 Features
- Answers FAQs about IIT Jammu
- Built without writing manual code
- Uses Azure-hosted AI capabilities
- Deploys directly to a web app
### ⚙️ How It Works

1. **Data Upload**  
   FAQs about IIT Jammu are added to Azure QnA Maker or Language Studio.

2. **Bot Setup**  
   The Azure Bot Service is configured and connected to the knowledge base.

3. **Web App Deployment**  
   The chatbot is deployed to an Azure Web App, making it accessible via a live link.

4. **User Interaction**  
   Users type questions into the chat interface; the bot fetches relevant answers using the AI-powered backend.

5. **Chat History**  
   The interface displays recent conversations for better context and continuity.

   
### ⚙️ Working Flow

#### 🔹 Step 1: Prepare FAQs
- Gather frequently asked questions related to IIT Jammu.
- Organize them into Question-Answer pairs for easy upload.

#### 🔹 Step 2: Create a QnA Knowledge Base
- Use [Azure Language Studio](https://language.azure.com/) or [QnA Maker](https://www.qnamaker.ai/) to create a knowledge base (KB).
- Add the QnA pairs manually or upload from a document.

#### 🔹 Step 3: Set Up Azure Bot Service
- Go to [Azure Portal](https://portal.azure.com) and create a **Web App Bot**.
- Link it with the QnA KB using the **Bot Channels Registration**.
- Azure automatically handles the bot logic using its Bot Framework.

#### 🔹 Step 4: Enable Web Chat Channel
- In the Azure Bot configuration, enable the **Web Chat** channel.
- Get the direct link or embed code to deploy it on a website.

#### 🔹 Step 5: Deploy and Go Live
- Azure automatically hosts the bot via **Azure Web App**.
- The chatbot becomes accessible at a live public URL.
- Users can chat in real-time, and the bot responds based on the KB.

#### 🔹 Step 6: Chat Interface + History
- Users interact via a clean web UI.
- The bot maintains a visible **chat history** to help with context.

---

### 📈 Future Flow and Improvements

#### 🧠 Sentiment Analysis
- Detect user emotions (happy, confused, angry) using NLP.
- Adapt bot responses or escalate to a human if negative sentiment is detected.

#### 🌐 Web Scraping
- Automatically extract FAQs from the official IIT Jammu website.
- Keep the knowledge base **fresh and updated** without manual input.

#### 💾 Chat Logging
- Store user queries and responses in **Azure Cosmos DB**.
- Useful for analytics, personalization, or feedback loops.

#### 🔐 User-Based Access (Future)
- Add login system for IIT students and staff.
- Serve personalized answers based on user role


### 📱 Progressive Web App (PWA)**  
  Convert the chatbot into an installable PWA for mobile users with offline fallback.


## License
This project is released under the MIT License.
  
### Contributing
Feel free to fork this repository and open a pull request with your improvements or suggestions. All contributions are appreciated!
1. Fork or clone this repository
2. Navigate to Azure Bot Service portal  
3. Import the bot and connect to Language Studio  
4. Deploy to Azure Web App using one-click publish


### Contact
For any issues or questions, feel free to reach out at kanikakapoor2308@gmail.com or you can reach at my Linkedin profile : https://www.linkedin.com/in/kanika-369bab286/ . 
