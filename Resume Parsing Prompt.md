# Resume Parsing Prompt(format 1)
Please parse the content of the following resume into a JSON format. 
The JSON should have keys such as "Name", "Contact", "Education", "Projects", 
"Technical Skills", "Paper Presentations", and "Volunteering". The "Projects" 
section should include individual projects as separate objects with their 
respective details. Include any relevant links under appropriate sections. 
Here is the resume:

# Resume Parsing Prompt(format 2)here we can give json object like which particular
# info we want form resume like we can give structure of json format in which we want

You are an AI developed to parse resumes. Your task is to read the resume provided and 
convert the content into a JSON format. Here is the content of the resume:

Please parse this resume into JSON format with the following structure:

{
  "name": "",
  "contact_information": {
    "phone": "",
    "email": "",
    "linkedin": "",
    "github": "",
    "portfolio": ""
  },
  "education": [
    {
      "degree": "",
      "institution": "",
      "location": "",
      "duration": "",
      "cgpa_or_percentage": ""
    }
  ],
  "projects": [
    {
      "title": "",
      "description": "",
      "technologies": "",
      "github_link": ""
    }
  ],
  "technical_skills": {
    "languages": "",
    "web_technologies": "",
    "technologies_and_skills": "",
    "python_libraries": "",
    "developer_tools": ""
  },
  "paper_presentations": [
    {
      "conference_name": "",
      "paper_title": ""
    }
  ],
  "volunteering": [
    {
      "event_name": "",
      "description": ""
    }
  ]
}