# SDLC-
Water reminder 
import time
import tkinter as tk
from tkinter import messagebox

def remind_water():
    # Show the popup message
    root = tk.Tk()
    root.withdraw()           # Hide the empty window
    messagebox.showinfo("Water Time!", "Drink some water! 💧")
    root.destroy()

print("Water reminder started... Press Ctrl+C to stop")

while True:
    remind_water()          # Show message
    time.sleep(3600)        # Wait 1 hour (3600 seconds)
