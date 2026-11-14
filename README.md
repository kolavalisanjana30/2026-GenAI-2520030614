# EventGen AI – Campus Event Announcement Generator using Prompt Templates

## 1. Project Overview

EventGen AI is a Generative AI-based application designed to automate the creation of campus event announcements using predefined prompt templates and Large Language Models (LLMs).

The application allows users to enter basic event details such as event name, date, time, venue, organizer, and description. Using prompt engineering and the Google Gemini API, the system generates professional and well-structured announcements in different formats.

## 2. Problem Statement

Colleges regularly organize workshops, seminars, hackathons, cultural festivals, and other events. Creating announcements manually for different communication platforms can be repetitive and time-consuming.

EventGen AI addresses this problem by automating announcement generation and providing customized content based on user requirements.

## 3. Objectives

- Automate campus event announcement generation.
- Use predefined prompt templates for structured content.
- Generate announcements in multiple formats.
- Allow customization of announcement tone and style.
- Reduce manual effort and save time.
- Improve consistency and communication.

## 4. Key Features

- **Event Details Input:** Enter event name, date, time, venue, organizer, and description.
- **Prompt Templates:** Use predefined prompts to guide AI-generated content.
- **Multiple Formats:** Generate formal notices, emails, WhatsApp messages, and social media posts.
- **Tone Customization:** Choose formal, friendly, or professional tones.
- **AI Content Generation:** Generate announcements using Google Gemini API.
- **Output Display:** View, review, edit, and copy generated announcements.

## 5. Technologies Used

| Component | Technology |
|---|---|
| Programming Language | Python |
| AI Model | Google Gemini |
| API Integration | Gemini API |
| User Interface | Streamlit |
| Prompt Engineering | Prompt Templates |
| Version Control | Git and GitHub |
| Development Environment | Visual Studio Code |

## 6. System Workflow

1. User enters the campus event details.
2. User selects the announcement format.
3. User chooses the preferred tone.
4. The system selects the appropriate prompt template.
5. Event details are inserted into the prompt.
6. The completed prompt is sent to the Google Gemini API.
7. Gemini generates the announcement.
8. The generated announcement is displayed for review and editing.

## 7. Project Structure

```text
EventGen-AI/
│
├── app.py
├── prompts.py
├── requirements.txt
├── .env
├── .gitignore
└── README.md
```

*The file structure may be adjusted according to the final implementation.*

## 8. Software Requirements

- Windows 10/11 or Ubuntu
- Python 3.10 or above
- Visual Studio Code
- Google Gemini API Key
- Streamlit
- Internet Connection

## 9. Installation and Setup

**Step 1: Clone the repository**

```bash
git clone <your-github-repository-url>
```

**Step 2: Open the project folder**

```bash
cd EventGen-AI
```

**Step 3: Install the required libraries**

```bash
pip install -r requirements.txt
```

**Step 4: Configure the API key**

Create a `.env` file and add your Gemini API key:

```env
GEMINI_API_KEY=your_api_key_here
```

**Step 5: Run the application**

```bash
streamlit run app.py
```

The application will open in your default web browser.

## 10. Expected Output

The system generates customized campus event announcements based on the information provided by the user.

Supported output formats include:
- Formal College Notices
- Email Invitations
- WhatsApp Announcements
- Social Media Posts

## 11. Future Enhancements

- Support for multiple languages.
- Download announcements as PDF or text files.
- Add event poster generation.
- Provide more announcement templates.
- Integrate with college websites and event management platforms.

## 12. Conclusion

EventGen AI demonstrates how Generative AI and prompt engineering can simplify campus communication. By using predefined prompt templates and the Google Gemini API, the application helps users generate professional announcements quickly, reduces repetitive manual work, and improves the consistency of event-related communication.

---

**Project Name:** EventGen AI

**Project Title:** Campus Event Announcement Generator using Prompt Templates

**Domain:** Generative Artificial Intelligence

**Academic Year:** 2026–2027
