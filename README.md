# Loader
В этом каталоге лежат прошивка для `ESP 8266`.
* `at_commands.bin` используется для программирования `ESP 8266` на `C++` 
* используется для программирования `ESP 8266` на `Java Script`

# Soft
В этом каталоге лежит программа для перепрошивки контроллеров `ESP 8266`

# Examples
Скетч для работы с `AT-командами` `wifi troyka-модуля` через `Arduino`

# Перепрошивка ESP 8266
1) Запустите файл `ESPFlashDownloadTool`
2) В появившемся окне выберите `ESP8266 DownloadTool`.
3) Укажите путь к файлу прошивки, отметьте выбранный файл галочкой в чекбоксе напротив и укажите адрес `0х00`, по которому будет записан файл в память модуля.
5) Выберите `СОМ-порт` к которому подключен модуль и установите скорость `115200 бод`.
6) Зажмите кнопку `PROG` модуле и удерживая её нажмите и отпустите кнопку `RESET`. После этого отпустите кнопку `PROG`. Модуль перейдет в режим ожидания прошивки.
7) Жмите кнопку `Start` в окне программы.
