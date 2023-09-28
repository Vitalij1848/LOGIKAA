mport sys
from PyQt5.QtWidgets import QApplication, QWidget

# Создаем приложение
app = QApplication(sys.argv)

# Создаем главное окно
window = QWidget()
window.setWindowTitle('Пример PyQt5 окна')
window.setGeometry(100, 100, 400, 200)  # Устанавливаем размеры и позицию окна

# Отображаем окно
window.show()

# Запускаем главный цикл приложения
sys.exit(app.exec_())
