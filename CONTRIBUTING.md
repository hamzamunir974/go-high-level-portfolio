# Contributing to n8n Portfolio

Thank you for your interest! This is a personal portfolio repository, but here's how it's organized:

## Adding a New Workflow

1. **Create a project folder**
   ```bash
   mkdir workflows/your-project-name
   cd workflows/your-project-name
   ```

2. **Copy the template structure**
   ```bash
   cp -r ../workflows/.template/* .
   ```

3. **Add your files**
   - Export your workflow from n8n as JSON and save as `workflow.json`
   - Add screenshots to the `screenshots/` folder
   - Add videos to the `videos/` folder (or add links in the README)
   - Edit the `README.md` with your project details

4. **Update the main README**
   - Add a link to your project in the "Workflows" section of the main README.md
   - Include a brief description

## Adding a New Chatbot

1. **Create a project folder**
   ```bash
   mkdir chatbots/your-chatbot-name
   cd chatbots/your-chatbot-name
   ```

2. **Copy the template structure**
   ```bash
   cp -r ../chatbots/.template/* .
   ```

3. **Add your files**
   - Export your chatbot workflow from n8n as JSON and save as `chatbot.json`
   - Add screenshots to the `screenshots/` folder
   - Add videos to the `videos/` folder (or add links in the README)
   - Edit the `README.md` with your chatbot details

4. **Update the main README**
   - Add a link to your chatbot in the "Chatbots" section of the main README.md
   - Include a brief description

## File Naming Best Practices

- Use lowercase with hyphens: `my-awesome-workflow`
- Be descriptive but concise
- Use meaningful screenshot names: `workflow-overview.png`, `node-configuration.png`
- For videos, indicate what they show: `demo-full-run.mp4`, `setup-guide.mp4`

## Documentation Tips

- Write clear, concise descriptions
- Include prerequisites and requirements
- Document any credentials or API keys needed (without exposing actual secrets!)
- Add troubleshooting tips if applicable
- Include sample inputs/outputs when helpful

## Quality Checklist

Before adding a project, ensure:
- [ ] JSON file is valid and imports successfully into n8n
- [ ] Screenshots are clear and properly cropped
- [ ] Video demonstrates the key features
- [ ] README is complete with all sections filled
- [ ] No sensitive data (passwords, API keys, personal info) is included
- [ ] Main README is updated with a link to your project

## Questions?

Feel free to open an issue for any questions or suggestions!
