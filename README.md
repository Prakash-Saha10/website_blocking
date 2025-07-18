🚫 Website Blocker Using Python
🧠 1. Overview
This Python script helps you block distracting websites for a set period by editing your system’s host file. It’s a handy productivity tool for studying, working, or coding without distractions.

⚙️ 2. How It Works
🔁 The script continuously runs and:

🟢 Before the deadline (end_time):

Adds target websites to your system’s hosts file.

Redirects them to a dummy IP like 127.0.0.1 to block access.

🔴 After the deadline:

Automatically removes the websites from the hosts file, unblocking them.

✅ 3. Features
✨ Easy to customize
⏰ Blocks for a fixed time
🔒 Works in the background
💻 Lightweight (uses core Python only)

🧰 4. Tools & Libraries Used
🐍 Python 3.x

📦 datetime, time libraries

📁 System-level access to the hosts file

🛠️ 5. How to Use (Step-by-Step)
🔢 Step 1: Open the Python script
🔢 Step 2: Modify these variables:

🕒 end_time: set block expiry time

🌐 site_block: add websites you want to block (e.g., "www.youtube.com", "www.facebook.com")

🛣️ host_path: path to hosts file

Windows ➤ C:\\Windows\\System32\\drivers\\etc\\hosts

macOS/Linux ➤ /etc/hosts

🔁 redirect: set to 127.0.0.1

🎯 6. Real-World Use Cases
📚 Studying for exams? Block YouTube!
💼 Need deep focus at work? Block Facebook or Twitter.
📴 Want a break from social media? Run this script for a few hours.



