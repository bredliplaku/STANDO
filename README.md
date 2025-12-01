<div align="center">
<img src="https://raw.githubusercontent.com/bredliplaku/STANDO/refs/heads/main/favicon.png" alt="STANDO Logo" width="120" height="120" />

STANDO Smart Attendance

Efficient. Reliable. Smart.

<p>
<a href="#about">About</a> •
<a href="#features">Features</a> •
<a href="#technology">Technology</a> •
<a href="#getting-started">Getting Started</a> •
<a href="#team">The Team</a>
</p>
</div>

📖 About STANDO

STANDO is a digital transformation initiative designed to modernise university attendance tracking. By leveraging existing infrastructure—specifically Student ID cards with NFC technology—STANDO eliminates the inefficiencies of paper-based roll calls.

Originally conceptualised by Bredli Plaku to address environmental concerns (saving thousands of sheets of paper annually) and academic integrity issues (preventing signature forgery), the system has evolved into a comprehensive tool. It automates the flow of data from the classroom directly to the university's management systems (EIS), aligning with the vision of a sustainable, smart campus.

✨ Key Features

🎓 For Lecturers

NFC Smart Scanning: Instantly register attendance by tapping student ID cards using any NFC-enabled Android device.

Audio Feedback: Distinct sound effects confirm successful scans without needing to look at the screen.

EIS Integration: Automated scripting populates the Epoka Interactive System (EIS) with course data, including auto-filled week numbers and topics.

Offline Capability: "Import/Export" functionality ensures attendance can be tracked and saved even without an active internet connection.

Automated Reporting: Generates digital PDFs that match university templates for electronic submission to Department Coordinators.

🧑‍🎓 For Students

Transparency: Students can sign in with their university Google Account to view their personal attendance records.

Permission Requests: A built-in form allows students to digitally request leave (documenting reasons like health or emergencies) without needing physical paperwork.

ID Registration: Students can register their own ID cards directly via the mobile interface for approval.

🌍 Global Standards

ISO 8601 Compliance: All dates are strictly formatted as YYYY-MM-DD to ensure consistency across databases and reports.

🛠️ Technology Architecture

STANDO is built as a lightweight, web-based solution to ensure broad accessibility and ease of deployment.

Core Stack: HTML5, JavaScript (ES6+), CSS3.

Hardware Interface: Chrome NFC API (WebNFC) allows direct communication between the web application and NFC tags.

Authentication: Integrated with Google OAuth (University Workspace accounts).

Data Management: Automated scripts bridge the gap between raw scan data (Spreadsheets) and the official EIS platform.

Compatibility: Optimised for Android devices running Google Chrome (due to WebNFC API support).

🚀 Getting Started

Prerequisites

To use the scanning features of STANDO, you require:

An Android device with NFC functionality.

Google Chrome browser (support for WebNFC).

A valid University Google Account.

Installation & Local Development

Clone the repository

git clone [https://github.com/swimmingbrain/stando.git](https://github.com/swimmingbrain/stando.git)
cd stando


Serve the application
Because WebNFC requires a secure context (HTTPS) or localhost, use a local server to test.

# Using Python 3
python3 -m http.server 8000

# Or using Node.js http-server
npx http-server .


Access the App
Open localhost:8000 in your browser. (Note: NFC scanning functionality requires testing on an actual Android device via HTTPS or port forwarding).

🔮 Future Roadmap

We are actively exploring expansion opportunities to further digitise the academic experience:

Automated Theoretical Exams: Multiple-choice questions with automatic grading and device fingerprinting.

Centralised Course Materials: Direct upload capabilities to EIS.

🤝 Contributing

Contributions are welcome from the community. Whether you are looking to fix a bug, enhance the EIS integration script, or improve the UI, please feel free to fork the repository and submit a Pull Request.

Please ensure all date formats in your contributions adhere to ISO 8601 (YYYY-MM-DD).

👥 The Team

STANDO is proudly maintained and developed by the swimmingbrain team.

Creator & Lead Developer: Bredli Plaku

Maintainers: swimmingbrain team

📄 License

This project is open-source and available under the MIT License. See the LICENSE file for more details.

<div align="center">
<small>© 2025 swimmingbrain team. All Rights Reserved.</small>
</div>