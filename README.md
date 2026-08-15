```python
from pprint import pprint

my_info = {
    "name": "Lucas",
    "location": "Cork, Ireland",
    "role": "Software Developer",
    "spoken_languages": ["Portuguese (native)", "English (professional)"],
}

class DeveloperProfile:
    def __init__(self, name: str, location: str, role: str, languages: list[str]) -> None:
        self.name = name
        self.location = location
        self.role = role
        self.languages = languages

    def present(self) -> dict:
        return {
            'Name': self.name,
            'Location': self.location,
            'Role': self.role,
            'Languages': self.languages,
            }

def main() -> None:
    profile = DeveloperProfile(
    name=my_info["name"],
    location=my_info["location"],
    role=my_info["role"],
    languages=my_info["spoken_languages"]
    )
    pprint(profile.present())

if __name__ == "__main__":
    main()
```
# Lucas Batista

Software Developer based in Cork, Ireland, building Python automation,
API integrations, and data workflows that reduce manual operational work.

**Core focus:** Python · REST APIs · Selenium · FastAPI · SQL · Workflow automation  
**Currently:** Building automation and integration projects; open to Software Developer,
Automation Engineer, and Integration Engineer opportunities.

## Featured projects

- **[Automation project](https://github.com/BLUCASS/NC6_Auto-Submitter)** — Automates the submission of ESB Networks' NC6 Micro-generation Connection Application by pulling customer and system data straight from OpenSolar and driving the ESB Networks portal end-to-end with Selenium.
- **[FastAPI with Pytest project](https://github.com/BLUCASS/Weekly-timesheet-FastAPI)** - A FastAPI web app for logging weekly work hours. Pick the Monday that starts a week, enter hours and minutes worked per day, and get back a formatted summary with the total time worked for the week.
- **[Weather API with Tkinter project](https://github.com/BLUCASS/WeatherAPI-with-Python-and-Tkinter)** — A simple Python weather application that retrieves current weather information for a city using the WeatherAPI service. The project includes both a command-line interface and a desktop graphical user interface built with Tkinter.

## SKILLS

<p align="left">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/python/python-original-wordmark.svg" alt="Python" width="48" height="48"/>
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/flask/flask-original.svg" alt="Flask" width="48" height="48"/>
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/selenium/selenium-original.svg" alt="Selenium" width="48" height="48"/>
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/mysql/mysql-original.svg" alt="MySQL" width="48" height="48"/>
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/sqlite/sqlite-original.svg" alt="SQLite" width="48" height="48"/>
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/css3/css3-original.svg" alt="CSS3" width="48" height="48"/>
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/html5/html5-original.svg" alt="HTML5" width="48" height="48"/>
</p>

## STUDYING

<p align="left">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/docker/docker-plain-wordmark.svg" alt="Docker" width="48" height="48"/>
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/amazonwebservices/amazonwebservices-plain-wordmark.svg" alt="AWS" width="48" height="48"/>
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" alt="Git" width="48" height="48"/>
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/fastapi/fastapi-original.svg" alt="FastAPI" width="48" height="48"/>
</p>

## SOCIAL MEDIA

[<img src='https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white' target="blank" alt='LinkedIn' height='30'>](https://www.linkedin.com/in/lucas-batista-pilantil/)
---
