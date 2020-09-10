Hi i´m peter this is a robot for pianotiles!

use it whith this webside

pip recviraments
from pyautogui import *
import pyautogui
import keyboard
import win32api, win32con
import pynput
from pynput.mouse import Button, Controller
 
licence:
for personal use no youtube videos about it!

Code:
from pyautogui import *
import pyautogui
import keyboard
import win32api, win32con
import pynput
from pynput.mouse import Button, Controller
pyautogui.FAILSAFE = False
def on_click(x,y):
    win32api.SetCursor ((x,y))
    win32api.mouse_event(win32con.mouse_eventf_leftdown,0,0)
    time.sleep(0.01)
    win32api.mouse_event(win32con.mouse_eventf_left_up,0,0)
while keyboard.is_pressed('q') == False:
        if pyautogui.pixel(703, 546) [0] == 0:
            click(703, 546)
        if pyautogui.pixel(775, 546) [0] == 0:
            click(775, 546)
        if pyautogui.pixel(888, 546) [0] == 0:
            click(888, 546)
        if pyautogui.pixel(1019, 546) [0] == 0:
            click(1019, 546)
