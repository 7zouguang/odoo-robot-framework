This allows to play back the testcases recorded with https://github.com/brain-tec/se-builder

## Installation

```bash
pip install robotframework
pip install robotframework-selenium2library
pip install robotframework-ExtendedSelenium2Library
git clone https://github.com/brain-tec/odoo-robot-framework.git
```

## Run tests

Save the testfile (from SE Builder) in the same directory as the odoo-robot-framework and execute
```bash
pybot -v CONFIG:config.py testfile.robot
```
