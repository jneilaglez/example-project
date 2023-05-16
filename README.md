# Example Project

This project is an example of how to Ansible works, it only creates 2 files within **tmp** folder inside **ansible**
folder.

## Requirements

* python3

## Installation

Execute the following commands within the project root path:

* Create python virtualenv (this will create a venv folder within root directory project)

```shell
python3 -m venv venv
```

* Activate python virtualenv

```shell
source venv/bin/activate
```

* Install requirements within virtualenv

```shell
pip install -r requirements.txt
```

* Execute ansible

```shell
ansible-playbook -i ansible/inventory/ ansible/example-playbook.yaml
```

## Uninstallation

Delete the example-project folder.

## UML Diagrams

Use cases diagram

![alt Use cases diagram](/diagrams/example-project-use-case-diagram.drawio.png)

Classes diagram

![alt Classes diagram](/diagrams/example-project-class-diagram.drawio.png)
