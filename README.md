# WhatsApp Chatbot for Rohini Institute of Technology  

### Project Overview  
This WhatsApp chatbot project, developed using **Flask** and **MongoDB Compass**, facilitates efficient communication for campus drive activities at Rohini Institute of Technology. It offers automated responses to common queries and services such as:  
1. Courses  
2. Placements  
3. Trainings  
4. Admissions Information  
5. Professional Development Workshops  
6. Student Welfare  
7. Book Appointment  
8. Upcoming Appointment  
9. About  
10. Contact Us  
11. Upcoming Events  

### Features  
- **Automated Messaging:** Enables users to receive instant replies to queries.  
- **Custom Web Interface:** Includes web pages for signup and user interaction.  
- **Data Storage:** Utilizes MongoDB for efficient data management.  
- **Integration with WhatsApp API:** Supports seamless communication with users.  

### File Structure  
```plaintext  
WhatsappChatbot/  
├── whatsappbot.py        # Main Flask application  
├── ngrok.exe             # Ngrok for tunneling localhost to public URL  
├── requirements.txt      # Python dependencies  
├── templates/  
│   ├── signup.html       # Signup page  
│   └── index.html        # Landing page for interaction  
└── README.md             # Documentation  
```  

### Installation and Setup  

1. **Clone the Repository:**  
   ```bash  
   git clone https://github.com/Rohini371/Whatsappchatbot.git  
   cd Whatsappchatbot  
   ```  

2. **Set up a Virtual Environment:**  
   ```bash  
   python3 -m venv venv  
   source venv/bin/activate  # For Windows, use venv\Scripts\activate  
   ```  

3. **Install Dependencies:**  
   ```bash  
   pip install -r requirements.txt  
   ```  

4. **Configure MongoDB:**  
   - Ensure your MongoDB database is running and accessible.  

5. **Set Up Ngrok:**  
   - Install and run `ngrok.exe`:  
     ```bash  
     ./ngrok.exe http 5000  
     ```  
   - Copy the generated public URL for WhatsApp webhook setup.  

6. **Run the Application:**  
   ```bash  
   python whatsappbot.py  
   ```  

7. **Set Up WhatsApp Webhook:**  
   - Use the Ngrok public URL in your WhatsApp Business API settings.  

### Usage  
- Access the chatbot through WhatsApp.  
- Interact by sending the number corresponding to your desired service.  
- Navigate to `/signup` for user registration or `/` for the main interface.  

### Future Enhancements  
- Add authentication for user registration.  
- Include analytics for tracking user interactions.  
- Expand functionality with additional templates and services.  

### Contribution  
Contributions are welcome! Feel free to submit issues or pull requests for improvements.  

### License  
This project is licensed under the [MIT License](LICENSE).  
