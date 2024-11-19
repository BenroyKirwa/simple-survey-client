# SurveyMaster - The simple-survey-app

This repository contains the Static and template files for the simple survey application. This repository contains the client side of the application, the interface. Below is shown how to set up with the simple-survey-api repository to create the survey app on your own machine.

---

### Repository Contents by Project Task

| Tasks | Files | Description |
| ----- | ----- | ------ |
| 0. README  | [/survey/README.md](https://github.com/BenroyKirwa/simple-survey-client/blob/main/README.md) | Project details and instructions |
| 1. Home | [/survey/home.html](https://github.com/BenroyKirwa/simple-survey-client/blob/main/templates/survey/home.html) | Home page code for the survey app|
| 2. Log in | [/survey/login.html](https://github.com/BenroyKirwa/simple-survey-client/blob/main/templates/survey/login.html) | Page for log in of users for the app |
| 3. Sign up | [/survey/signup.html](https://github.com/BenroyKirwa/simple-survey-client/blob/main/templates/survey/signup.html) | Page for new users to sign up to the app |
| 4. Base template | [/survey/base.html](https://github.com/BenroyKirwa/simple-survey-client/blob/main/templates/survey/base.html) | A template for the main site. Contains all common code for the template |
| 5. Show surveys | [/survey/survey_list.html](https://github.com/BenroyKirwa/simple-survey-client/blob/main/templates/survey/survey_list.html)| Displays a list of surveys the are available to be answered |
| 6. Answer Survey | [/survey/survey_detail.html](https://github.com/BenroyKirwa/simple-survey-client/blob/main/templates/survey/survey_detail.html) | Displays the survey and survey questions, paginated |
| 7. Survey Summary | [/survey/survey_summary.html](https://github.com/BenroyKirwa/simple-survey-client/blob/main/templates/survey/survey_summary.html) | Displays a detailed summary of the answered survey |
| 8. Survey Responses | [/survey/survey_responses.html](https://github.com/BenroyKirwa/simple-survey-client/blob/main/templates/survey/survey_responses.html) | Displays all survey responses answered by a user filtered by page for each survey |


## General Use

1. Clone the repository.

2. Save the static and template to fit the structure below :
```
simple-survey-api/
├── sky_survey/                 
│   ├── settings.py             
│   ├── urls.py                 
│   └── ...
├── survey/                     
│   ├── templates/              
│   ├── static/                 
│   └── ...
├── venv/                       
├── requirements.txt            
├── README.md                   
└── db.sqlite3                  
```
3. Follow the instructions in the [simple-survey-api](https://github.com/BenroyKirwa/simple-survey-api) to create the app.
