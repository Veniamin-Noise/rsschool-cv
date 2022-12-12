# Veniamin Ilkov
## My contacts:

__Mobile-Phone:__ +7 771 535 3963

__e-mail:__ [studying.is.the.key.to.a.dream@gmail.com](mailto:studying.is.the.key.to.a.dream@gmail.com)

## About Me
I have been programming for several years, I have a little experience of teamwork on a common project and also twice won a prize in a programming hackathon from the Step Academy.
I'm learning fast.

## Skills:
* HTML/CSS
* C/C++ for microcontrollers
* С#
* Python
* Unity

## Code examples:
Little code for simultaneously changing the characteristics of slides that are displayed on the projector through a special program (significantly speeds up the process):
```python
import os
from PIL import ImageColor
import PyQt5
from PyQt5 import QtCore, QtGui, QtWidgets
class Ui_MainWindow(object):
    def setupUi(self, MainWindow):
        MainWindow.setObjectName("MainWindow")
        MainWindow.resize(299, 393)
        MainWindow.setStyleSheet("background-color: qlineargradient(spread:pad, x1:0, y1:0, x2:1, y2:1, stop:0 rgba(255, 0, 225, 255), stop:1 rgba(0, 239, 255, 255));\n"
"color: qlineargradient(spread:pad, x1:0, y1:0, x2:1, y2:1, stop:0 rgba(255, 0, 225, 255), stop:1 rgba(0, 239, 255, 255));")
        self.centralwidget = QtWidgets.QWidget(MainWindow)
        self.centralwidget.setObjectName("centralwidget")
        self.horizontalLayoutWidget = QtWidgets.QWidget(self.centralwidget)
        self.horizontalLayoutWidget.setGeometry(QtCore.QRect(-550, -130, 160, 80))
        self.horizontalLayoutWidget.setObjectName("horizontalLayoutWidget")
        self.horizontalLayout = QtWidgets.QHBoxLayout(self.horizontalLayoutWidget)
        self.horizontalLayout.setContentsMargins(0, 0, 0, 0)
        self.horizontalLayout.setObjectName("horizontalLayout")
        self.checkBoxHeight = QtWidgets.QCheckBox(self.centralwidget)
        self.checkBoxHeight.setGeometry(QtCore.QRect(4, 252, 72, 26))
        sizePolicy = QtWidgets.QSizePolicy(QtWidgets.QSizePolicy.Minimum, QtWidgets.QSizePolicy.Fixed)
        sizePolicy.setHorizontalStretch(0)
        sizePolicy.setVerticalStretch(0)
        sizePolicy.setHeightForWidth(self.checkBoxHeight.sizePolicy().hasHeightForWidth())
        self.checkBoxHeight.setSizePolicy(sizePolicy)
        self.checkBoxHeight.setSizeIncrement(QtCore.QSize(200, 200))
        self.checkBoxHeight.setBaseSize(QtCore.QSize(200, 200))
        font = QtGui.QFont()
        font.setFamily("Trebuchet MS")
        font.setPointSize(12)
        font.setBold(True)
        font.setWeight(75)
        font.setStyleStrategy(QtGui.QFont.PreferDefault)
        self.checkBoxHeight.setFont(font)
        self.checkBoxHeight.setMouseTracking(True)
        self.checkBoxHeight.setContextMenuPolicy(QtCore.Qt.ActionsContextMenu)
        self.checkBoxHeight.setStyleSheet("background-color: rgba(0, 0, 0, 70);\n"
"selection-color: rgb(20, 20, 20);\n"
"color: rgb(255, 255, 255);")
        self.checkBoxHeight.setIconSize(QtCore.QSize(16, 16))
        self.checkBoxHeight.setShortcut("")
        self.checkBoxHeight.setCheckable(True)
        self.checkBoxHeight.setChecked(False)
        self.checkBoxHeight.setAutoRepeat(False)
        self.checkBoxHeight.setAutoExclusive(False)
        self.checkBoxHeight.setTristate(False)
        self.checkBoxHeight.setObjectName("checkBox_3")
        self.checkBoxColor = QtWidgets.QCheckBox(self.centralwidget)
        self.checkBoxColor.setGeometry(QtCore.QRect(4, 211, 64, 26))
        sizePolicy = QtWidgets.QSizePolicy(QtWidgets.QSizePolicy.Minimum, QtWidgets.QSizePolicy.Fixed)
        sizePolicy.setHorizontalStretch(0)
        sizePolicy.setVerticalStretch(0)
        sizePolicy.setHeightForWidth(self.checkBoxColor.sizePolicy().hasHeightForWidth())
        self.checkBoxColor.setSizePolicy(sizePolicy)
        self.checkBoxColor.setSizeIncrement(QtCore.QSize(200, 200))
        self.checkBoxColor.setBaseSize(QtCore.QSize(200, 200))
        font = QtGui.QFont()
        font.setFamily("Trebuchet MS")
        font.setPointSize(12)
        font.setBold(True)
        font.setWeight(75)
        font.setStyleStrategy(QtGui.QFont.PreferDefault)
        self.checkBoxColor.setFont(font)
        self.checkBoxColor.setMouseTracking(True)
        self.checkBoxColor.setContextMenuPolicy(QtCore.Qt.ActionsContextMenu)
        self.checkBoxColor.setStyleSheet("background-color: rgba(0, 0, 0, 70);\n"
"selection-color: rgb(20, 20, 20);\n"
"color: rgb(255, 255, 255);")
        self.checkBoxColor.setIconSize(QtCore.QSize(16, 16))
        self.checkBoxColor.setShortcut("")
        self.checkBoxColor.setCheckable(True)
        self.checkBoxColor.setChecked(False)
        self.checkBoxColor.setAutoRepeat(False)
        self.checkBoxColor.setAutoExclusive(False)
        self.checkBoxColor.setTristate(False)
        self.checkBoxColor.setObjectName("checkBox_4")
        self.checkBoxFontSize = QtWidgets.QCheckBox(self.centralwidget)
        self.checkBoxFontSize.setGeometry(QtCore.QRect(4, 170, 91, 26))
        sizePolicy = QtWidgets.QSizePolicy(QtWidgets.QSizePolicy.Minimum, QtWidgets.QSizePolicy.Fixed)
        sizePolicy.setHorizontalStretch(0)
        sizePolicy.setVerticalStretch(0)
        sizePolicy.setHeightForWidth(self.checkBoxFontSize.sizePolicy().hasHeightForWidth())
        self.checkBoxFontSize.setSizePolicy(sizePolicy)
        self.checkBoxFontSize.setSizeIncrement(QtCore.QSize(200, 200))
        self.checkBoxFontSize.setBaseSize(QtCore.QSize(200, 200))
        font = QtGui.QFont()
        font.setFamily("Trebuchet MS")
        font.setPointSize(12)
        font.setBold(True)
        font.setWeight(75)
        font.setStyleStrategy(QtGui.QFont.PreferDefault)
        self.checkBoxFontSize.setFont(font)
        self.checkBoxFontSize.setMouseTracking(True)
        self.checkBoxFontSize.setContextMenuPolicy(QtCore.Qt.ActionsContextMenu)
        self.checkBoxFontSize.setStyleSheet("background-color: rgba(0, 0, 0, 70);\n"
"selection-color: rgb(20, 20, 20);\n"
"color: rgb(255, 255, 255);")
        self.checkBoxFontSize.setIconSize(QtCore.QSize(16, 16))
        self.checkBoxFontSize.setShortcut("")
        self.checkBoxFontSize.setCheckable(True)
        self.checkBoxFontSize.setChecked(False)
        self.checkBoxFontSize.setAutoRepeat(False)
        self.checkBoxFontSize.setAutoExclusive(False)
        self.checkBoxFontSize.setTristate(False)
        self.checkBoxFontSize.setObjectName("checkBox_2")
        self.checkBoxPhoto = QtWidgets.QCheckBox(self.centralwidget)
        self.checkBoxPhoto.setGeometry(QtCore.QRect(4, 129, 67, 26))
        sizePolicy = QtWidgets.QSizePolicy(QtWidgets.QSizePolicy.Minimum, QtWidgets.QSizePolicy.Fixed)
        sizePolicy.setHorizontalStretch(0)
        sizePolicy.setVerticalStretch(0)
        sizePolicy.setHeightForWidth(self.checkBoxPhoto.sizePolicy().hasHeightForWidth())
        self.checkBoxPhoto.setSizePolicy(sizePolicy)
        self.checkBoxPhoto.setSizeIncrement(QtCore.QSize(200, 200))
        self.checkBoxPhoto.setBaseSize(QtCore.QSize(200, 200))
        font = QtGui.QFont()
        font.setFamily("Trebuchet MS")
        font.setPointSize(12)
        font.setBold(True)
        font.setWeight(75)
        font.setStyleStrategy(QtGui.QFont.PreferDefault)
        self.checkBoxPhoto.setFont(font)
        self.checkBoxPhoto.setMouseTracking(True)
        self.checkBoxPhoto.setContextMenuPolicy(QtCore.Qt.ActionsContextMenu)
        self.checkBoxPhoto.setStyleSheet("background-color: rgba(0, 0, 0, 70);\n"
"selection-color: rgb(20, 20, 20);\n"
"color: rgb(255, 255, 255);")
        self.checkBoxPhoto.setIconSize(QtCore.QSize(16, 16))
        self.checkBoxPhoto.setShortcut("")
        self.checkBoxPhoto.setCheckable(True)
        self.checkBoxPhoto.setChecked(False)
        self.checkBoxPhoto.setAutoRepeat(False)
        self.checkBoxPhoto.setAutoExclusive(False)
        self.checkBoxPhoto.setTristate(False)
        self.checkBoxPhoto.setObjectName("checkBox")
        self.lineEditFontSize = QtWidgets.QLineEdit(self.centralwidget)
        self.lineEditFontSize.setGeometry(QtCore.QRect(145, 175, 150, 25))
        self.lineEditFontSize.setMinimumSize(QtCore.QSize(150, 25))
        self.lineEditFontSize.setMaximumSize(QtCore.QSize(150, 25))
        font = QtGui.QFont()
        font.setFamily("Trebuchet MS")
        font.setPointSize(12)
        font.setBold(True)
        font.setWeight(75)
        self.lineEditFontSize.setFont(font)
        self.lineEditFontSize.setStyleSheet("background-color: rgba(0, 0, 0, 70);\n"
"selection-color: rgb(20, 20, 20);\n"
"color: rgb(255, 255, 255);")
        self.lineEditFontSize.setPlaceholderText("")
        self.lineEditFontSize.setObjectName("lineEdit")
        self.lineEditColor = QtWidgets.QLineEdit(self.centralwidget)
        self.lineEditColor.setGeometry(QtCore.QRect(145, 215, 150, 25))
        self.lineEditColor.setMinimumSize(QtCore.QSize(150, 25))
        self.lineEditColor.setMaximumSize(QtCore.QSize(150, 25))
        font = QtGui.QFont()
        font.setFamily("Trebuchet MS")
        font.setPointSize(12)
        font.setBold(True)
        font.setWeight(75)
        self.lineEditColor.setFont(font)
        self.lineEditColor.setStyleSheet("background-color: rgba(0, 0, 0, 70);\n"
"border-color: rgba(255, 255, 255, 50);\n"
"selection-color: rgb(20, 20, 20);\n"
"color: rgb(255, 255, 255);")
        self.lineEditColor.setPlaceholderText("")
        self.lineEditColor.setObjectName("lineEdit_2")
        self.pushButtonPhoto = QtWidgets.QPushButton(self.centralwidget)
        self.pushButtonPhoto.setEnabled(True)
        self.pushButtonPhoto.setGeometry(QtCore.QRect(145, 130, 150, 30))
        sizePolicy = QtWidgets.QSizePolicy(QtWidgets.QSizePolicy.Maximum, QtWidgets.QSizePolicy.Maximum)
        sizePolicy.setHorizontalStretch(0)
        sizePolicy.setVerticalStretch(0)
        sizePolicy.setHeightForWidth(self.pushButtonPhoto.sizePolicy().hasHeightForWidth())
        self.pushButtonPhoto.setSizePolicy(sizePolicy)
        self.pushButtonPhoto.setMinimumSize(QtCore.QSize(150, 30))
        self.pushButtonPhoto.setMaximumSize(QtCore.QSize(150, 30))
        self.pushButtonPhoto.setSizeIncrement(QtCore.QSize(0, 0))
        self.pushButtonPhoto.setBaseSize(QtCore.QSize(0, 0))
        font = QtGui.QFont()
        font.setFamily("Trebuchet MS")
        font.setPointSize(12)
        font.setBold(True)
        font.setItalic(False)
        font.setUnderline(False)
        font.setWeight(75)
        font.setStrikeOut(False)
        font.setKerning(True)
        font.setStyleStrategy(QtGui.QFont.PreferDefault)
        self.pushButtonPhoto.setFont(font)
        self.pushButtonPhoto.setCursor(QtGui.QCursor(QtCore.Qt.ArrowCursor))
        self.pushButtonPhoto.setMouseTracking(True)
        self.pushButtonPhoto.setTabletTracking(False)
        self.pushButtonPhoto.setAcceptDrops(False)
        self.pushButtonPhoto.setToolTipDuration(-1)
        self.pushButtonPhoto.setStatusTip("")
        self.pushButtonPhoto.setStyleSheet("background-color: rgba(0, 0, 0, 70);\n"
"selection-color: rgb(20, 20, 20);\n"
"color: rgb(255, 255, 255);")
        self.pushButtonPhoto.setCheckable(False)
        self.pushButtonPhoto.setAutoRepeat(False)
        self.pushButtonPhoto.setAutoExclusive(False)
        self.pushButtonPhoto.setAutoRepeatDelay(300)
        self.pushButtonPhoto.setAutoRepeatInterval(100)
        self.pushButtonPhoto.setAutoDefault(False)
        self.pushButtonPhoto.setDefault(False)
        self.pushButtonPhoto.setFlat(False)
        self.pushButtonPhoto.setObjectName("pushButton_2")
        self.pushButtonFolder = QtWidgets.QPushButton(self.centralwidget)
        self.pushButtonFolder.setEnabled(True)
        self.pushButtonFolder.setGeometry(QtCore.QRect(30, 30, 250, 50))
        sizePolicy = QtWidgets.QSizePolicy(QtWidgets.QSizePolicy.Maximum, QtWidgets.QSizePolicy.Maximum)
        sizePolicy.setHorizontalStretch(0)
        sizePolicy.setVerticalStretch(0)
        sizePolicy.setHeightForWidth(self.pushButtonFolder.sizePolicy().hasHeightForWidth())
        self.pushButtonFolder.setSizePolicy(sizePolicy)
        self.pushButtonFolder.setMinimumSize(QtCore.QSize(250, 50))
        self.pushButtonFolder.setMaximumSize(QtCore.QSize(250, 50))
        self.pushButtonFolder.setSizeIncrement(QtCore.QSize(0, 0))
        font = QtGui.QFont()
        font.setFamily("Trebuchet MS")
        font.setPointSize(20)
        font.setBold(True)
        font.setWeight(75)
        font.setStrikeOut(False)
        self.pushButtonFolder.setFont(font)
        self.pushButtonFolder.setMouseTracking(False)
        self.pushButtonFolder.setAcceptDrops(False)
        self.pushButtonFolder.setToolTip("")
        self.pushButtonFolder.setAutoFillBackground(False)
        self.pushButtonFolder.setStyleSheet("background-color: rgba(0, 0, 0, 70);\n"
"selection-color: rgb(20, 20, 20);\n"
"color: rgb(255, 255, 255);")
        self.pushButtonFolder.setAutoDefault(True)
        self.pushButtonFolder.setObjectName("pushButton")
        self.pushButtonRun = QtWidgets.QPushButton(self.centralwidget)
        self.pushButtonRun.setGeometry(QtCore.QRect(50, 310, 201, 51))
        sizePolicy = QtWidgets.QSizePolicy(QtWidgets.QSizePolicy.Minimum, QtWidgets.QSizePolicy.Minimum)
        sizePolicy.setHorizontalStretch(0)
        sizePolicy.setVerticalStretch(0)
        sizePolicy.setHeightForWidth(self.pushButtonRun.sizePolicy().hasHeightForWidth())
        self.pushButtonRun.setSizePolicy(sizePolicy)
        font = QtGui.QFont()
        font.setFamily("Trebuchet MS")
        font.setPointSize(20)
        font.setBold(True)
        font.setWeight(75)
        self.pushButtonRun.setFont(font)
        self.pushButtonRun.setStyleSheet("background-color: rgba(0, 0, 0, 70);\n"
"selection-color: rgb(20, 20, 20);\n"
"color: rgb(255, 255, 255);")
        self.pushButtonRun.setObjectName("pushButton_3")
        MainWindow.setCentralWidget(self.centralwidget)
        self.retranslateUi(MainWindow)
        QtCore.QMetaObject.connectSlotsByName(MainWindow)
        self.wayImage = ""
        self.WayFolder = ""
        self.ChangeFontSize = False
        self.ChangePhoto = False
        self.ChangeColor = False
        self.ChangeHeight = False
        self.TextColor = False
        self.TextFontSize = False
        self.add_functions()
    def retranslateUi(self, MainWindow):
        _translate = QtCore.QCoreApplication.translate
        MainWindow.setWindowTitle(_translate("MainWindow", "MainWindow"))
        self.checkBoxHeight.setText(_translate("MainWindow", "Height"))
        self.checkBoxColor.setText(_translate("MainWindow", "Color"))
        self.checkBoxFontSize.setText(_translate("MainWindow", "Font size"))
        self.checkBoxPhoto.setText(_translate("MainWindow", "Photo"))
        self.lineEditFontSize.setText(_translate("MainWindow", ""))
        self.lineEditColor.setText(_translate("MainWindow", ""))
        self.pushButtonPhoto.setText(_translate("MainWindow", "Photo"))
        self.pushButtonFolder.setText(_translate("MainWindow", "Folder"))
        self.pushButtonRun.setText(_translate("MainWindow", "Run"))
    def add_functions(self):  # функция
            self.pushButtonPhoto.clicked.connect(lambda: self.selectFile(self.pushButtonPhoto))  # включение функции selectFile() в случае если была нажата кнопка
            self.pushButtonFolder.clicked.connect(lambda: self.selectFile(self.pushButtonFolder))  # включение функции selectFile() в случае если была нажата кнопка
            self.pushButtonRun.clicked.connect(lambda: self.write_conversion())  # включение функции write_conversion() в случае если была нажата кнопка
            self.checkBoxColor.stateChanged.connect(lambda: self.CheckChange())
            self.checkBoxPhoto.stateChanged.connect(lambda: self.CheckChange())
            self.checkBoxFontSize.stateChanged.connect(lambda: self.CheckChange())
            self.checkBoxHeight.stateChanged.connect(lambda: self.CheckChange())
    def CheckChange(self):
            if self.checkBoxColor.isChecked():
                    self.ChangeColor = True
                    print(self.ChangeColor)
            else:
                    self.ChangeColor = False
                    print(self.ChangeColor)
            if self.checkBoxPhoto.isChecked():
                    self.ChangePhoto = True
                    print(self.ChangePhoto)
            else:
                    self.ChangePhoto = False
                    print(self.ChangePhoto)
            if self.checkBoxFontSize.isChecked():
                    self.ChangeFontSize = True
                    print(self.ChangeFontSize)
            else:
                    self.ChangeFontSize = False
                    print(self.ChangeFontSize)
            if self.checkBoxHeight.isChecked():
                    self.ChangeHeight = True
                    print(self.ChangeHeight)
            else:
                    self.ChangeHeight = False
                    print(self.ChangeHeight)
    def selectFile(self, object):  # функция которая отображает окно для выбора файла
            self.fileDialog = QtWidgets.QFileDialog()  # создание диалогового окна
            if object == self.pushButtonPhoto:  # если функция была нажата кнопкой "Фото"
                    self.wayImage = self.fileDialog.getOpenFileName()[0]  # выводим диалоговое окно и присваиваем переменной значение путя к этому изображению
                    object.setText(self.wayImage)  # присваиваем кнопке текст пути к фотке
            else:  # иначе, если функция была нажата кнопкой "Папка"
                    self.wayFolder = self.fileDialog.getExistingDirectory()  # выводим диалоговое окно и присваиваем переменной значение путя к этой папке
                    object.setText(self.wayFolder)  # присваиваем кнопке текст пути к папке
    def write_conversion(self):  # создаем функцию конвертации файлов
            if (str(self.wayImage) != "" and str(self.wayFolder) != ""):
                    for elem in os.listdir(str(self.wayFolder)):  # цикл который перебирает файлы из папки с помощью плагина os
                            file1 = open(str(self.wayFolder) + "\\" + elem, 'r', encoding='Windows-1251')  # открываем каждый файл по очереди
                            lines = file1.readlines()  # присваиваем переменной текст линии файла
                            frame = 1  # создаем переменную которая будет хранить значение frame (номер слайда)
                            for i in range(0, len(lines), 1):  # цикл который от 0 до длины линии текста
                                    if (str("[frame_" + str(frame) + "]") in lines[i]):  # если в линии содержится текст [frame_" + str(frame) + "] то:
                                            lenght = 0  # создание переменной харнящей в себе количество \n (переходов строки)
                                            for i2 in range(i, len(lines), 1):  # цикл перебирающий строки внутри одного фрейма (рабоатет пока не достигнет следующего фрейма)
                                                    if ("TXT_text=" in lines[i2]):  # если в линии содержится надпись TXT_text= то:
                                                            for line2 in bytes.fromhex(lines[i2].replace('TXT_text=', '')).decode('Windows-1251'):  # цикл проверяет есть ли переход строки (\n) в декодированном из 16 ричной системы счисления в текстовый тексте
                                                                    #print(line2)
                                                                    if "\n" in line2:  # если в \n содержится в линии то:
                                                                            lenght += 1  # увеличить lenght на 1
                                                    if ("TXT_fontSize=" in lines[i2] and self.ChangeFontSize):  # если в линии содержится надпись TXT_fontSize= то:
                                                            if lenght >= 4:  # если количество \n больше 4 то:
                                                                    lines[i2] = 'TXT_fontSize=' + str(int(self.lineEditFontSize.text()) - 2) + '\n'  # изменяем размер текста , заемняем значение линии
                                                            elif lenght <= 4:  # иначе, если количество \n меньше 4 то:
                                                                    lines[i2] = 'TXT_fontSize=' + str(self.lineEditFontSize.text()) + '\n'  # размер текста равен заданному размеру, заемняем значение линии
                                                            elif lenght <= 2:  # иначе, если количество \n меньше 4 то:
                                                                    lines[i2] = 'TXT_fontSize=' + str(int(self.lineEditFontSize.text()) + 2) + '\n'  # размер текста равен заданному размеру + 2, заемняем значение линии
                                                    if ("TXT_TopMargin=" in lines[i2]):  # если в линии содержится надпись TXT_TopMargin= то:
                                                            lines[i2] = 'TXT_TopMargin=' + str(290 - lenght * 20) + '\n'  # изменяем отступ от текста с верху текста на 290 - lenght * 20, заемняем значение линии
                                                    # if ("[frame_" + str(frame + 1) + "]" in lines[i2]):  # если в линии содержится надпись [frame_" + str(frame + 1) + "] то:
                                                    #         break  # кончаем цикл, работаем в пределах одного фрейма, дальшне уходим
                                            frame += 1  # увеличиваем значение фрейма на 1
                                    # if ("TXT_fontName=" in lines[i]):  # если в линии содержится надпись TXT_fontName= то:
                                    #         lines[i] = 'TXT_fontName=trebuchet MS' + '\n'  # меняем шрифт на trebuchet MS, заемняем значение линии
                                    if ("TXT_fontColor=" in lines[i] and self.ChangeColor):  # если в линии содержится надпись TXT_fontColor= то:
                                            self.color = ImageColor.getcolor(str(self.lineEditColor.text()), "RGB")
                                            self.colorInt = int(self.color[0]) + 256 * int(self.color[1]) + 256 * 256 * int(self.color[2])
                                            lines[i] = 'TXT_fontColor=' + str(self.colorInt) + '\n'  # меняем цвет текста на другой (Белый - 16777215(#ffffff)), заемняем значение линии
                                    # if ("TXT_bold=" in lines[i]):  # если в линии содержится надпись TXT_bold= то:
                                    #         lines[] = 'TXT_bold=1' + '\n'  # делаем текст жирным, заемняем значение линии
                                    if ("BG_filename=" in lines[i] and self.ChangePhoto):  # если в линии содержится надпись BG_filename= то:
                                            lines[i] = "BG_filename=" + str(self.wayImage) + '\n'  # указываем путь к фотке которую мы указали, заемняем значение линии
                                    if ("BG_nochange=1" in lines[i]):  # если в линии содержится надпись BG_nochange=1 то:
                                            lines[i] = 'BG_nochange=0' + '\n' # изменяем значение на 0 для того чтобы фото песни можно было менять
                                    if ("BG_colorInstead=" in lines[i]):  # если в линии содержится надпись BG_colorInstead= то:
                                            lines[i] = 'BG_colorInstead=0' + '\n'
                            save_changes = open(str(self.wayFolder) + "\\" + elem, 'w')  # Открываем файл для записи
                            save_changes.writelines(lines)  # Сохраняем список строк
                            save_changes.close()  # Закрываем файл
                            self.pushButtonPhoto.setText("Photo")  # ставим текст кнопок по умолчанию, (возвращаем)
                            self.pushButtonFolder.setText("Folder")  # ставим текст кнопок по умолчанию, (возвращаем)
                            self.pushButtonRun.setText("Run")
if __name__ == "__main__":
    import sys
    app = QtWidgets.QApplication(sys.argv)
    MainWindow = QtWidgets.QMainWindow()
    ui = Ui_MainWindow()
    ui.setupUi(MainWindow)
    MainWindow.show()
    sys.exit(app.exec_())
```

## Experience:
* telegram bot for playing the game "words", and communicating with him.
* Arduino projects:
  * remote control of the computer via the remote control (mouse, keyboard, media) via a microcontroller connected via Usb
  * modification of lighting in the apartment for remote control
* A program that changes slides for another program

## English
I am studying English at Karaganda Technical University. My current level is A2 (Pre-Intermediate).
