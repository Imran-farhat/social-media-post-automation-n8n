# Social Media Automation with n8n

A multi-platform social media posting automation built using **n8n**.  
This project demonstrates how to publish images and videos automatically to different social platforms using API-based workflows.

---

## Supported Platforms

### X (Twitter)
<img width="1684" height="622" alt="image" src="https://github.com/user-attachments/assets/a598006a-6f9b-42c8-8b47-475290eb0d85" />

API Access:  
https://developer.x.com

---

### Threads
<img width="1269" height="372" alt="image" src="https://github.com/user-attachments/assets/8624a737-1d31-4cdb-abb8-e210b22455ca" />

API Access (via Meta Developers):  
https://developers.facebook.com

---

### Facebook Pages
<img width="1420" height="548" alt="image" src="https://github.com/user-attachments/assets/9aeea03f-4e5e-466c-93da-a914cd64bec9" />

API Access (Meta Graph API):  
https://developers.facebook.com

---

### Pinterest
<img width="1714" height="435" alt="image" src="https://github.com/user-attachments/assets/ade17175-6aee-4769-a1c0-360b8258dd39" />

API Access:  
https://developers.pinterest.com

---

## Key Features
- Form-based trigger for content input
- Automatic image / video detection
- Platform-specific API handling
- Supports both image and video posts
- Credentials managed securely inside n8n
- Safe for public GitHub repositories

---

## How It Works
1. User submits content through an n8n Form Trigger
2. Workflow detects media type (image or video)
3. Data is routed to the correct platform logic
4. Platform API publishes the post automatically

---

## Setup Instructions
1. Install or open your n8n instance (cloud or self-hosted)
2. Import the required workflow JSON from the `workflows/` folder
3. Configure API credentials inside **n8n Credentials**
4. Replace placeholder IDs (Board ID, Page ID, etc.)
5. Activate the workflow
6. Use the Form Trigger URL to post content

---

## Security Notes
- No API keys, secrets, or tokens are stored in this repository
- No `.env` files are used
- All credentials must be added manually inside n8n
- Workflow files are safe to publish after removing credential references

---

## Intended Use
- Automation demos
- Portfolio projects
- Interview showcases
- Learning API-based workflow automation

---

## Author
Imran

---

## License
MIT License
