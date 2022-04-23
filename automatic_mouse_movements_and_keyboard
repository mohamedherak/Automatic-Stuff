import pyautogui
import numpy as np
import time

print(pyautogui.size())

print(pyautogui.position())

image = pyautogui.screenshot('my_screenshot.jpg')

pyautogui.moveTo(200, 200, duration = 1)

time.sleep(3)

w = np.random.randint(0, 1919)
h = np.random.randint(0, 1079)

pyautogui.moveTo(w, h, duration = 1)

time.sleep(3)

while True:
    w = np.random.randint(0, 1919)
    h = np.random.randint(0, 1079)
    pyautogui.moveTo(w, h, duration = 1)
    #pyautogui.click(x=w, y=h, clicks=2, interval= 1, button='right')
    pyautogui.click(x=w, y=h, clicks=2, interval= 1, button='left')
    pyautogui.write('Mohamed', interval=0.25) 
    time.sleep(10)  #time in seconds
