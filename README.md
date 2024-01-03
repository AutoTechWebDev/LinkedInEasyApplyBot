# LinkedIn Easy Apply Bot (Updated 1/3/2024)

_Automate your LinkedIn job applications with ease!_

This Python and Selenium-based bot automates applying to jobs using the Easy Apply feature on LinkedIn.

## Key Features

- Apply to thousands of jobs effortlessly.
- Track application dates and times for performance analysis.

## Important

- Use at your own risk. LinkedIn may restrict or suspend accounts for bot usage.
- Consider this an educational project.

## Getting Started

**Setting Up From Scratch**
- Download and install Git tool [https://git-scm.com/downloads]
- Download and install PyCharm Community Edition (Free) [https://www.jetbrains.com/pycharm/download/?section=windows]
- Download the code from my repository to your local machine
- Configure [config.yaml] to your needs (these are the settings to be used while searching for Easy Apply jobs on LinkedIn) - Use edititing tool of choice mine is VSCode
- Launch PyCharm and Open 
- Select the folder for the EasyApplyBot that has all the repo files in it.
- Using the Requirements.txt file use this as a reference to install the missing packages
- Manage Packages 
  - Search for more packages and download the packages listed in requirements.txt
  - selenium
  - pyautogui
  - webdriver_manager
  - PyYAML
  - validate_email
Once all are installed open main.py and click Run
  - Note* If you have 2FA/Verifcation on your LinkedIn account have your phone/email ready to Verify.
 
While Main.py is running you will be able to see the status of the current task in the terminal provided in PyCharm. 
.csv's will auto populate as the program runs with failed and successful application attemtps. I would recommend reviewing the failed attempts and the unprepared questions which can be added to [config.yaml] as needed

## Additional Resources

- Optional BI dashboard setup:
- Download PowerBI through the Microsoft Store (Power Bi Desktop)
- Dashboard.pbix in the source folder can be configured using the .csv files to create a PowerBI visual to display your total applications, locations, job titles, etc
  - To configure the dashboard to your data
  - Expand the Data tab on the far right click on "successful" and select "Edit Query"
  - 3 Source Settings will need to be changed "Sample File", "Successful", and "Unprepared Questions" select each individually and under "Applied Steps" select "Source" and select the cogwheel to change the source to the EasyApplyBot Folder do this for all 3
  - After changing the Sources for all 3 select "Close and Apply" to see your personal data
 

- **Troubleshooting:** Encounter errors? Ensure dependencies are installed.
- **Need assistance?** Comment on GitHub
- **Genuine issues** Raise issues page at my GitHub.

## Support This Project

Buy me a coffee through [PayPal](https://paypal.me/eternalsessions6) if you find this tool helpful!

## Credits

- Original developer: [Nathan Duma](https://github.com/NathanDuma)
- Significant code updates: [Micheal Dingess](https://github.com/madingess/)
- Maintenance and improvements: [voidbydefault](https://github.com/voidbydefault)
- Current Development/Improvements/Maintenance [AutoTechWebDev](https://github.com/AutoTechWebDev)
