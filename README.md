# contact-center-mockapi-prompts (ccprompts)
<a href="https://ccprompts.wbx.ninja/"><strong>View Demo</strong></a>
·
<a href="https://github.com/WXSD-Sales/ccprompts/issues"><strong>Report Bug</strong></a>
·
<a href="https://github.com/WXSD-Sales/ccprompts/issues"><strong>Request Feature</strong></a>

Welcome to our WXSD DEMO Repo! <!-- Keep this here --> 

This is a Web App which can change the data of a mockapi end point.

<!-- Keep the following here -->  
 *_Everything included is for demo and Proof of Concept purposes only. Your use of the site is solely at your own risk. This site may contain links to third party content, which we do not warrant, endorse, or assume liability for. These demos are for Cisco Webex usecases, but are not Official Cisco Webex Branded demos._
 
 
## Overview
TBA

Server Requirements:
1. python version >= 3.8
2. pip install modules.


## Setup

### Server Side Setup
1. Clone this repository
2. Rename ```sample.env``` to ```.env```, and edit the values in .env
3. Navigate to the cloned directory in your terminal, then run:
```
pip install python-dotenv
pip install tornado==4.5.2
```
4. Run the following in the terminal:
```
python server.py --debug
```
5. Navigate to http://localhost:MY_APP_PORT in your browser, where MY_APP_PORT is set in the file .env


## Support

Please reach out to the WXSD team at [wxsd@external.cisco.com](mailto:wxsd@external.cisco.com?cc=<your_cec>@cisco.com&subject=RepoName).
