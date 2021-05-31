# vscode-pytest-icons

With python 3.8.9 on macOS 11.2.3

```
python -m venv venv
source venv/bin/activate
pip install -upgrade setuptools pip
pip install -r requirements.txt
```

Open vscode, discover tests, then run and observe icons not updating. Remove the `python.testing.pytestArgs` directive from `.vscode/settings.json` and run and observe icons updating ok.