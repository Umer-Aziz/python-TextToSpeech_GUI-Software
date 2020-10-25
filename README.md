# python-TextToSpeech_GUI-Software
python PyQt5, Text to Speech Converter  frontend design with Qt designer and backend in python PyQt5. 
1.bground.png is my background pic.
2.SourceQt.qrc is a Qtdesigner file. The Qt Resource Collection File is stored in the QRC format and is affixed with the QRC extension, and is used by the Qt application and toolkit. QRC files are generally classified as settings file that contain a list of application resources like image files or icons in XML format.
3.you need to convert .qrc file into .py when you write backend in python using this Command.(pyrcc4 resources.qrc -o resources.py).
4.SourceQt.py is Converted File and the Text2Speech.py is the main file.

SCREENSHOT.

![image](https://user-images.githubusercontent.com/62507205/97101814-a3c07200-165d-11eb-9412-a5a842683827.png)

5.The output file in the form of .mp3 in the same folder.
6. you can also convert Text2Speech.py into .exe format by pyinstaller(pyinstaller --onefile -w Text2Speech.py) and use permanently on window.
