# VSploit-Framework
This Framework is for Educational Purposes only!

VSploit Framework (vsf) is a multi functional hacking framework with options like Port Scanner or Virus Creator

# How to use it
First create your project folder and make a python file (.py) 
then download the ZIP of the vsf
Open the zip and drag the folder named vsf into your project
In your Python file add following line: from vsf.main import *
Then you can code your tool and use following example commands in the code: vsf_port_scanner()
                                                                            vsf_virus_creator()

# Commands
vsf_port_scanner() - A simple and fast port scanner 
vsf_virus_creator() - Create a simple Virus (Not strong)


# Example:

from vsf.main import *

print("Welocme to my tool")
print("Options: Port Scanner 1")
print("         Virus creator 2")

option = input("Option: ")
if option == "1":
  vsf_port_scanner()
elif option == "3":
  vsf_virus_creator()

