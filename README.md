# Hello there 👋

![](https://komarev.com/ghpvc/?username=MK-444)


```python
class Software Engineer:
    """
    👩‍💻 Just like the Singleton pattern ensures a single, unique instance, 
    each of us is a singular, irreplaceable individual in this world.
    """
    _instance = None

    def __new__(cls, *args, **kwargs):
        """ 👶 We create ourselves, and everything depends solely on us. """
        if cls._instance is None:
            cls._instance = super().__new__(cls)
        return cls._instance

    def __init__(self):
        self.name: str = "👩 Marie Kostenkova"
        self.role: str = "🚀🐍 DevOps Engineer/Python developer"
        self.language_spoken: set[str] = {"🇨🇿 cs_CZ", "🇺🇸 en_US", "🇺🇦 uk", "🇷🇺 ru-RU"}

    def say_hi(self) -> str:
        """ Return my greeting message."""
        return "😀 Thanks for dropping by, hope you find some of my work interesting."


me = PythonDeveloper()
greeting = me.say_hi()
print(greeting)
```


## My stack

![Python](https://img.shields.io/badge/-Python-black?style=flat-square&logo=Python)
![Django](https://img.shields.io/badge/-Django-0aad48?style=flat-square&logo=Django)
![Django Rest Framework](https://img.shields.io/badge/DRF-red?style=flat-square&logo=Django)
![Django Ninja](https://img.shields.io/badge/-Django_Ninja-%234B32C3?style=flat-square&logo=Django)
![FastAPI](https://img.shields.io/badge/-FastAPI-%2300C7B7?style=flat-square&logo=FastAPI)
![Flask](https://img.shields.io/badge/-Flask-%232c3e50?style=flat-square&logo=Flask)
![Celery](https://img.shields.io/badge/-Celery-%2300C7B7?style=flat-square&logo=Celery)
![Postgresql](https://img.shields.io/badge/-Postgresql-%232c3e50?style=flat-square&logo=Postgresql)
![Redis](https://img.shields.io/badge/-Redis-FCA121?style=flat-square&logo=Redis)
![React](https://img.shields.io/badge/-React-%232c3e50?style=flat-square&logo=react)
![HTML5](https://img.shields.io/badge/-HTML5-%23E44D27?style=flat-square&logo=html5&logoColor=ffffff)
![CSS3](https://img.shields.io/badge/-CSS3-%231572B6?style=flat-square&logo=css3)
![Docker](https://img.shields.io/badge/-Docker-46a2f1?style=flat-square&logo=docker&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FCA121?style=flat-square&logo=postman)
![Linux](https://img.shields.io/badge/Linux-black?style=flat-square&logo=linux)
![Git](https://img.shields.io/badge/-Git-black?style=flat-square&logo=git)

<!--
**MK-444/MK-444** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
