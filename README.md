
Config files for my programs
----------------------------


YASB, to find screens for bar run:
 
	from PyQt6.QtWidgets import QApplication
	from PyQt6.QtGui import QScreen
	import sys

	app = QApplication(sys.argv)

	for screen in QApplication.screens():
    	print(screen.name())

	app.quit()

