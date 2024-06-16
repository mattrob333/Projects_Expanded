# Custom Chat Bots
![image](https://github.com/mattrob333/txt-files/assets/31228129/5b69e4ff-8f73-4e27-8b20-c102c1210630)

## Appointment Booking Bot
## About the Bot

The Artistic Construction Support Bot is a powerful tool designed to streamline customer interactions and improve lead management for construction contractors. Embedded directly on the Artistic Construction website, this chatbot is here to assist you with booking appointments and answering any questions you may have about our services.

![image](https://github.com/mattrob333/Projects_Expanded/assets/31228129/7cbb2cbb-3e24-462d-bc32-bfedeff182e2)

### Key Features

- **Appointment Booking:** The chatbot allows users to easily book appointments. Simply click on the "Let's Book an Appointment" button and provide the necessary information.
- **Lead Capture:** As users interact with the bot, it collects essential information such as first name, last name, email address, phone number, and a description of the project. This data is then sent to an Airtable database where it is securely stored.

![image](https://github.com/mattrob333/Projects_Expanded/assets/31228129/ccd3071f-14d2-4997-9574-05d031b25a5b)

- **Comprehensive Answers:** Powered by OpenAI's assistance API, the bot is loaded with files and data about Artistic Construction. This enables it to answer questions about the company, its services, and any other relevant information accurately and efficiently.
- **Integration with Flowise:** Built using the Flowise no-code app builder, the bot's functionality is seamlessly integrated with the backend systems, ensuring smooth operations and data management.

![image](https://github.com/mattrob333/Projects_Expanded/assets/31228129/f62ff358-fe0b-4573-b41c-7f252f1bb5eb)

- **Automated Lead Management:** Utilizing Make.com, the bot connects OpenAI with Airtable, automating the process of capturing and storing lead information.

### How It Works

1. **User Interaction:** When a user visits the Artistic Construction website, they can interact with the chatbot by clicking on the available buttons or typing their queries.

![image](https://github.com/mattrob333/Projects_Expanded/assets/31228129/0a0e670a-28de-4097-a20d-7ee1a0747e30)

2. **Data Collection:** For booking an appointment, the bot will prompt the user to provide:
   - First Name
   - Last Name
   - Email Address
   - Phone Number
   - Description of the Service Needed or Project Description

3. **Lead Storage:** The collected information is automatically sent to an Airtable database. This ensures that all leads are captured in an organized and accessible manner.

![image](https://github.com/mattrob333/Projects_Expanded/assets/31228129/c63393fb-eda7-409e-af74-b0b0b3f4becb)

4. **Question and Answer:** The bot, powered by OpenAI, uses the pre-loaded files and data sources to provide accurate answers to user queries regarding Artistic Construction.

Prompt inside the Assistant:
```
You are a helpful assistant that works for a company called Artistic Construction.  Your name is Arty.
Your tone should be friendly and helpful.  Keep your answers short

Use the information contained in the provided files to answer questions about Artistic Construction, such as the products and services offered by the company.  After answering a question, ask the user if they would like to book an appointment or consultation.

If the user asks to set up an appointment or book a consultation, then collect the following information from the user and then send this information to function add_lead. 
- Their first name
- Their lastname
- Their email address
- Their phone number
- Description of the service needed or project description.
Once you have all this information, respond with a message like "Thank you, someone from sales will get back to you soon".
```

### Behind the Scenes

- **Flowise No-Code App Builder:** The chatbot's structure and flow are built using Flowise, a no-code app builder that allows for quick and efficient setup and customization.
- **OpenAI Assistance API:** The core intelligence of the chatbot is driven by OpenAI, which enables it to understand and respond to user queries effectively.
- **Make.com:** Connects Flowise and the OpenAI Assistant to Airtable

![image](https://github.com/mattrob333/Projects_Expanded/assets/31228129/b656a86f-4883-41d1-aedc-d52cc5296181)

- **Integration with Airtable:** Make.com is used to connect OpenAI with Airtable, automating the process of lead data capture and storage.

### Benefits

- **Efficiency:** Automates the process of booking appointments and capturing leads, saving time for both customers and the business.
- **Accuracy:** Provides precise information based on the data and files loaded into the system, ensuring users get reliable answers.
- **User-Friendly:** Easy to interact with, providing a seamless experience for website visitors.

We invite you to try the Artistic Construction Support Bot and experience the convenience and efficiency it brings to managing your construction projects and inquiries. For any further assistance, feel free to interact with our bot or contact us directly.

---

*Powered by Flowise, OpenAI, Airtable, and Make.com.*
