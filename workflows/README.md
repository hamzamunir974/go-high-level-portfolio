# Workflows

This directory contains all n8n workflow projects.

## Structure

Each workflow project should be organized in its own folder with:
- Screenshots (PNG/JPG)
- Video recordings (MP4 or links to videos)
- JSON workflow file
- Optional: Description document

Example:
```
workflows/
├── project-name/
│   ├── screenshots/
│   │   ├── workflow-overview.png
│   │   └── node-configuration.png
│   ├── videos/
│   │   └── demo.mp4 (or video-link.txt)
│   ├── workflow.json
│   └── README.md
```

## Adding a New Workflow

1. Create a new folder with your project name
2. Add your workflow JSON file exported from n8n
3. Add screenshots showing the workflow in action
4. Add video recording or link to demonstrate the workflow
5. Update the main README.md with a link to your project
