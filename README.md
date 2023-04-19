Для начало добовляем несколько библеотек для данной пограммы
Скопируйте если вам надо.

       from PyQt5.QtCore import Qt, QTimer, QTime, QLocale#для работы параметра alignment
       from PyQt5.QtGui import QDoubleValidator, QIntValidator, QIntValidator, QFont
       from PyQt5.QtWidgets import (
          QApplication, QWidget,
          QHBoxLayout, QVBoxLayout,
          QPushButton, QLabel, QLineEdit)      
 
 
      from instr import *
      from second_win import *
      
Далее созаем первое окно для приложения 
![image](https://user-images.githubusercontent.com/128893943/233141025-88ff208b-900a-4d47-8edc-f39e1cbd559a.png)
Даная часть кода нужна для работы
        
        app = QApplication([])
        mw = MainWin()
        app.exec_()

![image](https://user-images.githubusercontent.com/128893943/233142722-92b7b418-e0b7-4968-8588-1fe798b971d0.png)
Данная часть окна нужна для надписей в разных окнах

Данная часть нужна для библеотеки второго окна
      
      from PyQt5.QtCore import Qt, QTimer, QLocale
      from PyQt5.QtGui import QDoubleValidator, QIntValidator, QFont
      from PyQt5.QtWidgets import(
            QApplication, QWidget,
            QHBoxLayout, QGridLayout, QVBoxLayout,
            QGroupBox, QRadioButton,
            QPushButton, QLabel, QListWidget, QLineEdit)

    from instr import*
    from final_win import*
    
Данная часть для работы втрого окна и работы кнопок
![image](https://user-images.githubusercontent.com/128893943/233146745-cf9f3715-8899-4de0-ab6d-5dea782790e4.png)
![image](https://user-images.githubusercontent.com/128893943/233147381-9eb065a7-0634-4be5-9cde-a94d33c34ac7.png)
![image](https://user-images.githubusercontent.com/128893943/233147452-2991946e-0a10-49b9-ae95-1ac22f76dd98.png)

Для третьего окна нужны данные библеотеки
  
    from PyQt5.QtCore import Qt,QTimer,QTime,QLocale
    from PyQt5.QtGui import QDoubleValidator,QIntValidator,QFont
    from PyQt5.QtWidgets import QApplication,QWidget,QHBoxLayout,QVBoxLayout,QGridLayout,QPushButton,QLabel,QLineEdit
    from instr import*

Данное окно финальное, и тут пишем результаты 
![image](https://user-images.githubusercontent.com/128893943/233149897-64358ff2-e91e-41ed-a30d-53875eea0839.png)


все конец
![image](https://user-images.githubusercontent.com/128893943/233150822-fb27f8d1-deee-41c2-bb94-14f12bd6c190.png)
![image](https://user-images.githubusercontent.com/128893943/233150904-b22a7ab7-1af9-4a18-8bc7-146076083148.png
