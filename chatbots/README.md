# Chatbots

This directory contains all n8n chatbot projects.

## Structure

Each chatbot project should be organized in its own folder with:
- Screenshots (PNG/JPG)
- Video recordings (MP4 or links to videos)
- JSON workflow file
- Optional: Description document

Example:
```
chatbots/
├── project-name/
│   ├── screenshots/
│   │   ├── chatbot-flow.png
│   │   └── conversation-example.png
│   ├── videos/
│   │   └── demo.mp4 (or video-link.txt)
│   ├── chatbot.json
│   └── README.md
```

## Adding a New Chatbot

1. Create a new folder with your project name
2. Add your chatbot workflow JSON file exported from n8n
3. Add screenshots showing the chatbot flow and interactions
4. Add video recording or link to demonstrate the chatbot
5. Update the main README.md with a link to your project
