# -*- coding: utf-8 -*-

"""
Created on Thu Mar  3 00:37:52 2022

@author: vered
"""

from tkinter import *

from tkinter.ttk import *
from time import strftime



root = Tk()
root.title("Clock")

def time():
    string = strftime("%I:%M:%S %p")

    label.config(text=string)
    label.after(1000,time)

label = Label(root, font = "ds-digital 100", background = "black", foreground = "cyan")
label.pack(anchor='center')
time()

mainloop()
