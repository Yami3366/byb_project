# byb_project
# Task 21 - Build your Brand 05 - Technical Portfolio
The most complex Hello World I have ever written.
Directory Structure :
+ byb_project
  +src
    +hello
      __init__.py
      HelloWorld.py
   __init__.py
   __main__.py


__init__.py file in src
print("In /src/__init__.py")

__init__.py file in src/hello
print("In /src/hello/__init__.py")

__main__.py file in src
import sys
from src.hello.HelloWorld import HelloWorld
print("In /src/__main__.py")
HelloWorld.main(sys.argv)


# Run Application
/usr/bin/python3 -m src
In /src/__init__.py
In /src/hello/__init__.py
In /src/__main__.py
Hello World
  
