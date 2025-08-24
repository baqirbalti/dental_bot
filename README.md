🦷 Dental_Bot – AI-powered WhatsApp Chatbot for Dental Clinics
📌 Overview

Dental_Bot is an AI-powered WhatsApp chatbot built with n8n that helps dental clinics automate patient interaction.
The bot can:

Answer patient queries about dental problems, treatments, and charges 💬

Collect patient details and guide them through booking 🗓️

Store appointment data securely in an SQL database 📂

Provide intelligent responses using Google Gemini AI 🤖

This system reduces manual workload for clinic staff and improves patient engagement by offering a seamless, automated booking flow.

⚙️ Features

✅ WhatsApp Integration – Patients can chat directly with the clinic via WhatsApp.
✅ AI-Powered Queries – Uses Google Gemini to answer common dental questions (treatments, charges, timings).
✅ Booking Flow – Patients can finalize an appointment directly in chat.
✅ Database Storage – Appointment & patient details are stored in an SQL database for record-keeping.
✅ AI Agent Node – Handles natural conversation flow and ensures smooth query → booking transition.

🛠️ Tech Stack

n8n (automation + workflow engine)

WhatsApp Business API (patient communication)

Google Gemini AI (smart query handling)

SQL Database (patient records & bookings)

🚀 Workflow

Patient sends a WhatsApp message to the clinic.

WhatsApp Trigger receives the message in n8n.

AI Agent + Google Gemini interprets the query and responds.

If the patient wants to book:

Bot collects details (Name, Problem, Date, Time).

Stores booking in SQL database.

WhatsApp Send Message confirms the booking to the patient.

📈 Future Enhancements

🗓️ Google Calendar Integration – To sync bookings with the dentist’s schedule.

📊 Google Sheets – For maintaining appointment logs.

📞 AI Voice Caller – Automated call confirmations.
