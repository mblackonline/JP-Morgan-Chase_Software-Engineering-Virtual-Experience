# JPMorgan Chase & Co. Software Engineering Virtual Experience Program
This virtual work experience opportunity was provided by the [Forage](https://www.theforage.com/virtual-internships/prototype/R5iK7HMxJGBgaSbvk/Software%20Engineering%20Virtual%20Experience) and [JPMorgan Chase & Co](https://careers.jpmorgan.com/us/en/students/campaign/virtual-internship). I chose to participate in the program because I wanted to gain more experience working with technologies like Git, Python, TypeScript, Node.js, React, and JPMorgan's open-source Perspective web application. 
<br>
_All participants of this program were required to submit Git patches for each task to show proof of task completion. My Git patches for each task are saved in the Folder 'Git-Patch-Files'._

## The 3 main tasks required for this virtual work experience program were:
  1. Set up a development environment and make corrections to functions in the supplied Python code to allow it to interface with a stock-price data feed.
  2. Fix errors in the supplied typescript code to prepare the [Perspective](https://perspective.finos.org/) web application to visually display data in a graph.
  3. Edit a function in the supplied typescript code to ensure that the Perspective web app displayed the stock price data in accordance with the project's business requirements.
      - The business requirements required the final web application to:
        - display and track the ratio between two stock prices over time
        - display upper and lower bounds based on the ratios
        - trigger an alert if those thresholds were crossed to enable the stock traders to determine if a potential trading opportunity existed.

<br>

###  I produced a short video to share my approach to completing the final project and to show my final working version of the application. The video is available on YouTube at the below link: 

[![Video Link](https://i9.ytimg.com/vi/_Pt1WJpoaSo/mq3.jpg?sqp=CMDG65oG&rs=AOn4CLAuPW9NJl3yjbhCxnSur0c0fhzuLw)](https://www.youtube.com/watch?v=_Pt1WJpoaSo)

<br>

### My Certificate of Completion 

![](https://github.com/mblackonline/JP-Morgan-Chase_Software-Engineering-Virtual-Experience/blob/b80b40a23e566a24b64044cff36dfe2d4a2a3f66/JPMorganCertificateofCompletion.png)

#### Project tips:
- I recommend setting up the development environment for this project in a virtual environment. This will make it easy to create snapshots that can be used to revert to a previous state if needed.
- I initially started this project using Replit because I did not want to install all of the project dependencies on my main system. However, I encountered some difficulties getting the required npm modules installed in Replit, so I  used VirtualBox to set up a development environment for tasks 2 and 3. 
- The biggest challenge that I faced with this project was getting the development environment set up correctly. The project instructions give you the options of using Python 2 or Python 3 for your development environment, so I used Python 3. However, I later found that the npm modules provided in the project's starter code were dependent on Python 2.7. After reading through the project's troubleshooting documentation and doing some internet research, I found that the issue could be corrected by installing the correct build tools from an elevated PowerShell terminal using: `npm install -g windows-build-tools`. The solution was found at the following link, under Environment setup and configuration: -> Prerequisites: -> Option 1: https://github.com/Microsoft/nodejs-guidelines/blob/master/windows-environment.md#prerequisites.