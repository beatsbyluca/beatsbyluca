  <img height="25" src="https://api.visitorbadge.io/api/VisitorHit?user=beatsbyluca&countColor=%234a12ba" alt="Profile Views"/>
  <img height="25" src="https://img.shields.io/github/followers/beatsbyluca?color=4a12ba&style=for-the-badge&logo=github&label=Follow" alt="Followers"/>
  <img height="25" src="https://img.shields.io/github/stars/beatsbyluca?color=4a12ba&style=for-the-badge&logo=github&label=Stars" alt="Stars"/>
</p>

<p align="center"> 
    <img src="https://github-readme-streak-stats-eta-three.vercel.app?user=beatsbyluca&theme=tokyonight&hide_border=true" alt="GitHub Streak" width="60%">
</p>

```python
from abc import ABCMeta, abstractmethod


class Beatsbyluca(metaclass=ABCMeta):
    
    @staticmethod
    @abstractmethod
    def contact():
        discord = "beatsbyluca"
        telegram = "@Beatsbyluca"
        return discord, telegram

class Attributes(Beatsbyluca):

    @staticmethod
    def life() -> tuple:
        langs = ("German", "English", "Russian")

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
