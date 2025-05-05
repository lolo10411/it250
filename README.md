# it250
# Burp Suite Demo – IT 250 Spring 2025

**Role:** Junior Pen Tester | **Tool:** Burp Suite Community | **Target:** OWASP Juice Shop  
**Video:** <https://youtu.be/REPLACE_WITH_VIDEO_URL>

---

## What this shows 
- Capture browser traffic with **Burp Proxy**  
- Replay & tweak a request in **Repeater**  
- Inject `' OR 1=1--` to bypass login (SQLi)  
- Prove admin access without a password  

---

## Run it yourself
```bash
# 1. pull repo
git clone https://github.com/your‑user/it250-burp-demo.git
cd it250-burp-demo

# 2. start vulnerable site (port 3000)
docker run -d --name juice -p 3000:3000 bkimminich/juice-shop

# 3. open Burp → Open Browser
# 4. follow steps shown in the video
