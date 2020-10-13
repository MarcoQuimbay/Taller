# Taller

import tkinter as tk
from tkinter import ttk


def init_window(): 
    window=tk.Tk()
    window.title=("Mi primera aplicación")
    window.geometry=('400x250')
    
    label= tk.Label(window, text="calculadora", font=("Arial bold", 15))
    label.grid(column = 0, row = 0)
    
    entrada1 = tk.Entry(window, width=10)
    entrada2 = tk.Entry(window, width=10)
    
    entrada1.grid(column = 1, row = 1)
    entrada2.grid(column = 1, row = 2)
    
    label_entrada1= tk.Label(window, text="Ingrese primer numero:", font=("Arial bold", 10))
    label_entrada1.grid(column = 0, row = 1)
    
    label_entrada2= tk.Label(window, text="Ingrese primer numero:", font=("Arial bold", 10))
    label_entrada2.grid(column = 0, row = 2)
    
    window.mainloop()
