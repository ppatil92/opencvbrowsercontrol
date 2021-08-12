# opencvbrowsercontrol
create keyboard events using open cv hand gesture

you will need open cv4 and python3 to run this project

original credits goes to project link for hand gesture recognition
https://github.com/lzane/Fingers-Detection-using-OpenCV-and-Python


    run it in python - python handgesturekeyboard.py
    press 'b' to capture the background model (Remember to move your hand out of the blue rectangle)
    press 'r' to reset the backgroud model
    press 'ESC' to exit


## Below code in the handgesturekeyboard.py script is to handle keyboard events
```
from pynput.keyboard import Key, Controller
from pynput import keyboard

keyboardController = Controller()
 if triggerSwitch is True:
                if isFinishCal is True and cnt == 1:
                    print (cnt)
		    keyboardController.press(Key.up)
                    keyboardController.release(Key.up)
		elif isFinishCal is True and cnt == 2:
                      print (cnt)
		      keyboardController.press(Key.down)
                      keyboardController.release(Key.down)
		elif isFinishCal is True and cnt == 3:
                      print (cnt)
		      keyboardController.press(Key.left)
                      keyboardController.release(Key.left)
		elif isFinishCal is True and cnt == 4:
                      print (cnt)
		      keyboardController.press(Key.right)
                      keyboardController.release(Key.right)
		    
```

##Youtube link - 
https://www.youtube.com/watch?v=Uc11ZJv29iA
