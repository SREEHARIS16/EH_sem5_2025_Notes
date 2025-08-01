✅ Assignment Task Breakdown

bash
Copy
Edit
python3 -m http.server 8080
Accessed the server via browser at http://localhost:8080

Captured terminal and browser screenshots

Observed how files are listed and served publicly

🖼️ Screenshots
screeshot.png


Terminal running the server

Browser view of served page

🔐 Findings on Web Security
Risk	Description
No authentication	Anyone on the same network can access files
Directory listing	All files in folder are visible
No HTTPS	Data sent over the network is unencrypted
Port exposure	If firewall allows, outsiders can access it

🧠 Conclusion
This assignment demonstrates how a simple Python command can turn any directory into a server. It also reveals the importance of secure configurations and protections when working with web technologies.

📤 Final GitHub Structure (Example)
markdown
Copy
Edit
EH_sem3_2025_Notes/
└── Assignment_01_Serve_Directory/
    ├── index.html
    ├── report.pdf
    ├── server_screenshot.png
    ├── browser_screenshot.png
    └── README.md
Optional README.md content:
markdown
Copy
Edit
# Assignment 01 - Serve a Directory using Python

This folder contains:
- A sample web page (`index.html`)
- Terminal and browser screenshots
- A 1-page report discussing method and findings

## Command Used:
```bash
python3 -m http.server 8080
yaml
Copy
Edit

---

