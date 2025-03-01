# python_graphics
Having fun with graphics using Python

https://build-system.fman.io/pyqt5-tutorial

https://pypi.org/project/PyQt5/


# Steps to run

0. Create a Python virtul environment

```
python -m venv venv
```

1. Install dependencies 

```
pip install -r requirements.txt
```

2. Run main.py
```
python main.py
```

2.5 Alternativly, build an exe
```
pyinstaller .\src\main.py --noconsole --distpath .\application\ --specpath .\application\ --workpath .\application\ --onefile
```