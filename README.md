
import tkinter as tk  
from tkinter import messagebox  

def show_hack_message():  
    messagebox.showerror("اختراق!", "تم اختراق هاتفك! جميع بياناتك في خطر.")  

root = tk.Tk()  
root.withdraw()  # إخفاء النافذة الرئيسية  
show_hack_message()  
