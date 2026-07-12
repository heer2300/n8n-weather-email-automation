# n8n-weather-email-automation
An n8n automation that retrieves daily weather data from the OpenWeatherMap API and sends an AI-generated weather summary to your email automatically.


# Daily Weather Email Automation using n8n

## Overview

This project is my first automation built using **n8n**. It automatically retrieves the current weather information for a specified location using the **OpenWeatherMap API** and sends the weather report directly to an email address.

The workflow can be scheduled to run every day, providing a daily weather update without any manual intervention.

---

## Features

- Fetches real-time weather data using the OpenWeatherMap API
- Sends the weather report to an email address
- Fully automated workflow using n8n
- Supports scheduled execution for daily weather updates
- Demonstrates API integration and email automation

---

## Technologies Used

- n8n (Self-Hosted)
- OpenWeatherMap API
- Gmail / SMTP

---

## Workflow

1. Trigger the workflow (Manual or Schedule Trigger)
2. Retrieve weather data from the OpenWeatherMap API
3. Process the response
4. Format the weather information
5. Send the weather report via email

---

## Screenshots

### Workflow

![Workflow](screenshots/workflow.png)

### Successful Execution

![Execution](screenshots/execution.png)

### Email Output

![Email Output](screenshots/email-output.png)

---

## Email Output

The workflow sends an email containing the latest weather information, including:

- Location
- Temperature
- Weather Condition
- Humidity
- Wind Speed
- Date and Time

---

## Learning Outcomes

Through this project, I learned:

- Building automation workflows with n8n
- Connecting to third-party APIs
- Managing API credentials
- Processing JSON responses
- Automating email notifications
- Debugging and testing workflows

---

## Future Improvements

- Add AI-generated weather summaries
- Support multiple locations
- Send weather alerts based on conditions
- Add Telegram or WhatsApp notifications
- Store weather history in a database
- Design a responsive HTML email template

---

## Project Structure

```
n8n-weather-email-automation/
│
├── README.md
├── workflow.json
└── screenshots/
    ├── workflow.png
    ├── execution.png
    └── email-output.png
```





WELLLLLLLL SCREENSHOTS NAMES ARE NOT AS IT ISSS, I WAS BORED SOOOOOOOOOOOO YK
---

lol ykwim

## Author

**Heer Patel**

This project is part of my journey in learning automation, APIs, and AI workflows using n8n.
