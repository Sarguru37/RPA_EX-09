# RPA-EXPERIMENT-9
### Name : SARGURU K
### Reg No : 212222230134
## AIM:
  To create a UiPath workflow that opens Notepad and simulates keyboard typing and shortcuts like saving a file using simulated keystrokes.

## ALGORITHM:
Step 1: Create a New Process Open UiPath Studio and create a new process named KeyboardAutomation.

Step 2: Open Notepad Drag and drop Start Process activity.
* Set the properties:
* FileName: "notepad.exe"

Step 3: Add Delay (Optional but Recommended) Add a Delay activity to wait for Notepad to open.
* Duration: 00:00:02 (2 seconds)

Step 4: Use Type Into Activity Drag and drop a Type Into activity.
* Click Indicate on Screen and select the Notepad window.
* Text to type:
* Hello! This text is typed by UiPath using keyboard automation.
* Enable ClickBeforeTyping and Activate options in the Properties panel for accuracy.
  
Step 5: Use Keyboard Shortcuts (e.g., Save) Drag and drop a Send Hotkey activity. Indicate the same Notepad window. Set the key to Ctrl + S (hold Ctrl, then choose S).

Step 6: Type File Name and Press Enter Add a Type Into activity to type file name (e.g., MyFile.txt). Add another Send Hotkey for pressing Enter.

## PROGRAM:

![image](https://github.com/user-attachments/assets/4c3e0b2d-8835-480b-a540-563c903add2a)
![image](https://github.com/user-attachments/assets/60dac8c2-4e93-4dad-a647-e1e4f577219e)
![image](https://github.com/user-attachments/assets/89ff4dc8-a794-4706-9114-fa2e414cf569)

## OUTPUT:

![image](https://github.com/user-attachments/assets/7d373f0f-363b-4229-9c18-5f2e7d79e94c)

## RESULT:
   The workflow successfully simulates human-like typing in Notepad and saves the file using keyboard shortcuts through UiPath's keyboard automation capabilities.
