### Hi, I'm Suphawish Somkliang!

A Business Analyst with a solid foundation in Data Science and Business Analytics from King Mongkut's Institute of Technology Ladkrabang. 

I leverage my skills in SQL, Python, and Excel to interpret complex data sets for strategic decision-making. 
Committed to using my analytical prowess to fuel business growth and innovation.

```python
from datetime import datetime, timedelta

class About_me:
    def __init__(self):
        self.name = "Suphawish Somkliang"
        self.role = "Business Analyst"
        self.education = "BSc in Data Science & Business Analytics"
        self.university = "King Mongkut's Institute of Technology Ladkrabang"
        self.skills = ["SQL", "Python", "Excel", "Power BI"]
        self.interests = ["Data Analysis", "Machine Learning", "Event Coordination"]
        self.languages = {"Thai": "Native", "English": "Fair"}

    def current_project(self):
        return "Developing an online test analysis system on the Moodle platform."

    def improve_skills(self):
        print("Actively learning new data analysis tools and techniques.")

    def update_status(self):
        if datetime.now() > datetime.now() - timedelta(days=1):
            self.improve_skills()
        else:
            print("Reviewing past projects and refining methodologies.")

my_profile = About_me()
my_profile.update_status()
