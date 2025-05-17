# What's new in 1.1

## Hiller.qss
Change that whole UI for it
have new style such as winXP
Office 2003.

---

# Hiller.QSS
## What's this?
The Hiller.QSS is a kind of Qt StyleSheet .It offer 3 types style of it:
- Basic
- White
- Dark
## How to get it ?
If you have `git`,you can use command:
```Bash

git clone https://github.com/LinnerFeng/Hiller.QSS/
```
If not ,you can go to download page.

## How to use it?
For `Python` you can use code :
```Python
class QSSRead():
    def __init__(self):
        pass
    @staticmethod
    def LoadQSSFile(self,path):
        with open(path,"r") as f :
            return f.read()
```
If ` C++`,I don't know.
