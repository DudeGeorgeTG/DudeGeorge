<p align="center">
  <img height="25" src="https://api.visitorbadge.io/api/VisitorHit?user=DudeGeorgeTG&countColor=%234a12ba" alt="Profile Views"/>
  <img height="25" src="https://img.shields.io/github/followers/DudeGeorgeTG?color=4a12ba&style=for-the-badge&logo=github&label=Follow" alt="Followers"/>
  <img height="25" src="https://img.shields.io/github/stars/DudeGeorgeTG?color=4a12ba&style=for-the-badge&logo=github&label=Stars" alt="Stars"/>
</p>

<p align="center"> 
    <img src="https://github-readme-streak-stats-eta-three.vercel.app?user=DudeGeorgeTG&theme=tokyonight&hide_border=true" alt="GitHub Streak" width="60%">
</p>

```python
from abc import ABCMeta, abstractmethod


class xKian(metaclass=ABCMeta):
    
    @staticmethod
    @abstractmethod
    def contact():
        discord = "dudegeorgei"
        telegram = "@DudeGeorges"
        return discord, telegram

class Attributes(xKian):

    @staticmethod
    def life() -> tuple:
        langs = ("Georgian", "English", "German")

        return langs

    @staticmethod
    def coding() -> tuple:
        text_editor = ["vscode", "Pycharm"]
        specialities = ["automation"]
        langs = {
            "pro": "python", 
            "learning": "golang"
        }
        
        return langs, specialities, text_editor
```

