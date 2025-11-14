import tkinter as tk
from tkinter import messagebox

def on_button_click():
    messagebox.showinfo("", "")

root = tk.Tk()
root.title("")
root.geometry("300x400")

button = tk.Button(root, text="", command=on_button_click)

button.pack(pady=50)

def on_button_click():
    messagebox.showinfo("", "")

button = tk.Button(root, text="", command=on_button_click)

button.pack(pady=60)

root.mainloop()

print("")
