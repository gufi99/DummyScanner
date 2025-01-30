INFORMATION GATHERING TOOL!! 

DummyScanner 

DummyScanner is a simple Python tool that scans websites for all publicly accessible URLs and email addresses. It helps identify potential security risks by uncovering both frontend and backend links, useful for security audits and penetration testing. 

Features: 

URL Scanning: Extracts all frontend and backend URLs. 

Email Extraction: Collects email addresses from the website. 

Error Handling: Gracefully handles connection errors and broken links. 

Requirements: 

Python 3.x 

Dependencies: 

beautifulsoup4 

requests 

lxml 

Installation: 

Clone the repository: `` git clone https://github.com/gufi99/DummyScanner  

cd dummy-scanner 

 

Run the tool: 

bash 

Copy 

python scanner.py 
 

Enter the target URL when prompted: 

bash 

Copy 

[+] Enter Target URL to scan: http://example.com 

 
Got it! Here's the shortened version of the README.md with the updated tool name DummyScanner:

README.md:
markdown
Copy
# DummyScanner

**DummyScanner** is a simple Python tool that scans websites for all publicly accessible URLs and email addresses. It helps identify potential security risks by uncovering both frontend and backend links, useful for security audits and penetration testing.

## Features:
- **URL Scanning:** Extracts all frontend and backend URLs.
- **Email Extraction:** Collects email addresses from the website.
- **Error Handling:** Gracefully handles connection errors and broken links.

## Requirements:
- Python 3.x
- Dependencies:
  - `beautifulsoup4`
  - `requests`
  - `lxml`

## Installation:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/dummy-scanner.git
   cd dummy-scanner
Install dependencies:
bash
Copy
pip install -r requirements.txt
Usage:
Run the tool:

bash
Copy
python scanner.py
Enter the target URL when prompted:

bash
Copy
[+] Enter Target URL to scan: http://example.com

Example Output:
bash
Copy
[1] Processing http://example.com
[2] Processing http://example.com/page1
[3] Processing http://example.com/contact

[+] Emails found:
contact@example.com
admin@example.com

[+] URLs found:
http://example.com
http://example.com/page1
http://example.com/contact

 

 

 
