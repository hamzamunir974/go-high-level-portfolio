# Quick Start Guide

Welcome! This guide will help you quickly add your first n8n workflow or chatbot to this portfolio.

## 📁 Repository Overview

```
n8n-portfolio/
├── workflows/          # Your workflow projects go here
│   ├── .template/     # Template to copy for new workflows
│   └── README.md
├── chatbots/          # Your chatbot projects go here
│   ├── .template/     # Template to copy for new chatbots
│   └── README.md
├── README.md          # Main portfolio page
└── CONTRIBUTING.md    # Detailed guidelines
```

## 🚀 Adding Your First Workflow

### Step 1: Create Your Project Folder
```bash
cd workflows
mkdir my-awesome-workflow
cd my-awesome-workflow
```

### Step 2: Add Your Files
1. **Export from n8n**: In n8n, go to your workflow → Click "..." → "Export" → Save as `workflow.json`
2. **Take screenshots**: Capture your workflow overview and important configurations
3. **Record a video**: Show your workflow in action (optional but recommended)

### Step 3: Organize Your Files
```
my-awesome-workflow/
├── workflow.json              # Your exported n8n workflow
├── screenshots/
│   ├── workflow-overview.png # Full view of your workflow
│   └── node-config.png        # Important configurations
├── videos/
│   └── demo.mp4              # Demo video (or video-link.txt with URL)
└── README.md                  # Project documentation
```

### Step 4: Create Documentation
Copy the template README and customize it:
```bash
cp ../.template/README.md ./README.md
# Now edit README.md with your project details
```

### Step 5: Update Main README
Open the main `README.md` and add your project to the Workflows section:
```markdown
### Workflows
- **[My Awesome Workflow](./workflows/my-awesome-workflow/)** - Automates data processing from API to database
```

## 🤖 Adding Your First Chatbot

Follow the same steps as above, but use the `chatbots/` directory instead!

```bash
cd chatbots
mkdir my-first-chatbot
cd my-first-chatbot
# Add your chatbot.json, screenshots, videos, and README.md
```

## 💡 Quick Tips

### Taking Great Screenshots
- Use full workflow view to show the complete flow
- Capture individual node configurations for complex setups
- Show sample data flowing through nodes
- Use annotations if needed to highlight important parts

### Recording Videos
- Keep videos short and focused (2-5 minutes ideal)
- Show the workflow triggering and completing
- Demonstrate key features
- Consider using Loom, YouTube, or similar for hosting

### Writing Documentation
- Start with what the workflow/chatbot does
- List prerequisites (credentials, API keys needed)
- Include installation steps
- Add troubleshooting tips
- Document any custom configurations

## 📋 Checklist Before Publishing

- [ ] JSON file exports and imports correctly
- [ ] Screenshots are clear and informative
- [ ] Video demonstrates key functionality
- [ ] README is complete and accurate
- [ ] No sensitive data (passwords, keys) included
- [ ] Main README updated with project link
- [ ] Files committed and pushed to repository

## 🎯 Example Project Structure

Here's what a complete project looks like:

```
workflows/email-automation/
├── workflow.json
├── screenshots/
│   ├── 01-workflow-overview.png
│   ├── 02-trigger-setup.png
│   ├── 03-email-template.png
│   └── 04-results.png
├── videos/
│   └── full-demo.mp4
└── README.md
```

## 🆘 Need Help?

Check out:
- [CONTRIBUTING.md](./CONTRIBUTING.md) - Detailed contribution guidelines
- [workflows/README.md](./workflows/README.md) - Workflows-specific info
- [chatbots/README.md](./chatbots/README.md) - Chatbots-specific info
- [.template folders](./) - Example templates to copy

## 🎉 Ready to Start?

1. Choose whether to add a workflow or chatbot
2. Create your project folder
3. Add your files (JSON, screenshots, video)
4. Document your project
5. Update the main README
6. Commit and push!

Happy automating! 🚀
