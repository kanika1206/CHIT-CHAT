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

   

### 📁 Project Structure

This project was built using Microsoft Azure's no-code and low-code services. Here's how each part contributes:

1. **Azure QnA Maker / Language Studio**  
   - A knowledge base of IIT Jammu FAQs was created.
   - Questions and answers were added manually or imported from a document.

2. **Azure Bot Service**  
   - A bot was created and connected to the QnA Maker resource.
   - Azure Bot Framework handles natural language understanding.

3. **Bot Deployment**  
   - The bot was deployed using **Azure Web App Bot** (via Azure Portal).
   - Web Chat channel enabled to interact with the bot using a public URL.

4. **Web App Hosting**  
   - The chatbot interface is hosted as a live website using Azure App Service.
   - Users can interact with it through a browser at:  
     [`https://chitchitchat.azurewebsites.net`](https://chitchitchat.azurewebsites.net)

## Future Improvements
### 🔮 Future Improvements

- **🧠 Sentiment Analysis**  
  Integrate sentiment analysis to detect the user's emotional tone (e.g., confusion, frustration, satisfaction).  
  This can help the bot respond more empathetically or escalate to a human if needed.

- **🌐 Web Scraping for Dynamic FAQs**  
  Automate the extraction of updated FAQs from the official IIT Jammu website using web scraping.  
  This would allow the knowledge base to stay current without manual updates.

- **💾 Chat Logging with Azure Cosmos DB**  
  Store conversation history in a database to allow personalized responses, analytics, and admin review.

- **🔐 Role-Based Access**  
  Add login for students/faculty to provide more specific answers to internal queries.

- **📱 Progressive Web App (PWA)**  
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
