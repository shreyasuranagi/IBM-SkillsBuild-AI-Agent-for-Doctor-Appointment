---

# Doctor Appointment AI Agent

**IBM SkillsBuild – Applied Artificial Intelligence**

## Project Overview

This project implements a Doctor Appointment AI Agent using Python and a Large Language Model (FLAN-T5). The agent assists users in checking doctor availability, booking appointments, and answering clinic-related queries through an interactive chat interface. The system demonstrates AI-driven intent classification combined with rule-based automation for reliable and accurate responses.
This project was developed as part of the **IBM SkillsBuild Winter Certification Program – Applied Artificial Intelligence**. It represents a hands-on internship-style assignment focused on building practical AI agents using real-world use cases and industry-relevant tools.

---

## Problem Statement

In many clinics and hospitals, receptionists are overloaded with administrative tasks, leading to missed calls, booking errors, and delayed responses to patient queries. There is a need for an automated, intelligent system that can handle appointment scheduling and provide accurate clinic information efficiently.

---

## Solution

The Doctor Appointment AI Agent uses a hybrid approach:

* A Large Language Model (FLAN-T5) to understand and classify user intent.
* Python-based tools to execute actions such as checking availability, booking appointments, and responding to general queries.
* Rule-based logic to ensure deterministic and error-free responses for critical information.

---

## Key Features

* Interactive chat-based interface
* AI-based intent classification
* Automated appointment booking
* Real-time availability checking
* Accurate clinic information delivery
* Prevention of double booking

---

## Technologies Used

* Python 3 (Google Colab)
* Hugging Face Transformers
* FLAN-T5 Large Language Model
* Regular Expressions (re)
* Dictionary-based in-memory data storage

---

## How the Agent Works

1. The user enters a query in the chat interface.
2. The LLM classifies the user’s intent.
3. Decision logic selects the appropriate tool.
4. The selected Python function executes the required action.
5. The agent returns a clear and accurate response to the user.

---

## Project Structure

* `decide_and_act()` – Determines user intent and routes requests
* `availability_tool()` – Displays available appointment slots
* `booking_tool()` – Books appointments and updates schedule
* `chat_tool()` – Handles general clinic-related queries
* `doctor_schedule` – Stores appointment availability

---

## Learning Outcomes

* Understanding of AI agent architecture
* Practical use of LLMs for intent classification
* Experience with hybrid AI systems (AI + rules)
* Improved skills in Python automation and NLP
* Real-world application of applied artificial intelligence

---

## How to Run

1. Open the project in Google Colab.
2. Install required libraries if not already available.
3. Run the notebook cells sequentially.
4. Interact with the agent through the console.
5. Type `exit` to end the session.

---



If you want, I can also help you **shorten this README** to a one-page version or **convert it into a PDF-friendly format**.
