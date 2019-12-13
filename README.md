TypeError: Login__System() takes no arguments
I am trying to use tkinter with python 3.7 but I am getting an error when run the code


CODE
from tkinter import*
class Login__System:
    def __int__(self,root):
        print('hello')



root=Tk()
obj=Login__System(root)
root.mainloop()


OUTPUT
"C:\Python 3.7\python.exe" C:/Users/kbasa/PycharmProjects/basanta/asu.py
Traceback (most recent call last):
  File "C:/Users/kbasa/PycharmProjects/basanta/asu.py", line 9, in <module>
    obj=Login__System(root)
TypeError: Login__System() takes no arguments

Process finished with exit code 1
