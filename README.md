INFORMATION GATHERING TOOL!! 

DummyScanner 

DummyScanner is a simple Python tool that scans websites for all publicly accessible URLs and email addresses. It helps identify potential security risks by uncovering both frontend and backend links, useful for security audits and penetration testing. 

Features: 

URL Scanning: Extracts all frontend and backend URLs. 

Email Extraction: Collects email addresses from the website. 

Error Handling: Gracefully handles connection errors and broken links. 

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
   git clone https://github.com/gufi99/DummyScanner.git
   cd DummyScanner
Install dependencies:

Copy
pip install -r requirements.txt
Usage:
Run the tool:

Copy
python scanner.py
Enter the target URL when prompted:

Copy
[+] Enter Target URL to scan: http://example.com

Example Output:
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

 

 

 
