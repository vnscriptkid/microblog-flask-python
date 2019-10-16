### Handle env
- sudo apt-get install python3 python3-venv
- python3 -m venv venv
- set FLASK_APP=blog.py
- set FLASK_DEBUG=1
- flask run

### Deps
- pip install flask

### Tips
- Open termial, then python shell, import libs, do testing ...

### Questions
- Special file: __init__.py
- Special vars: __name__ ('__main__' or ...)
- How import works? What can be imported ? class, method, what else ?
- How package resolution works? Where to find ? What is the order?
> from x import y
> from x.y import z
> from .x import y
> from . import x
- Syntax
> Init a class: Flask(__name__) -> no `new` key word !?!
> No `;` at the end of statement
- Flask(__name__) 
> What values of `__name__` can be?
> How does that influence flask?
> https://teamtreehouse.com/community/can-someone-help-me-understand-flaskname-a-little-better
- package vs modules
> package: folder/ with __init__.py
> module: file.py
- Flask
    - Circular dependencies
        > How to solve? Put `import` at tail
        > When it happens?
    - Decorator
        > enhance functions

