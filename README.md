# Crop-Images-App

- cv2
- PIL
- numpy
- re
- os
- ThreadPoolExecutor

About the project:
Console application The application is designed to process any number of book scans.
1. Data is taken from folders in the "data" directory.
2. The program crops the photos, removing margins along the edges, leaving only a page the size of the entire photo (for jpg), or leaving a fixed minimum margin for pages (for tif)
3. Then all photos are scaled to a single size
4. Saving in jpg and tif formats

О проекте:
Консольное приложение приложение предназначено для обработки любого количества сканов книг.
1. Данные берутся из папок в дериктории "data".
2. Программа обрезает фотографии, убирая отступы по краям, оставляя только страницу на весь размер фотографии (для jpg), или же оставляя фиксированный минимальный отступ для страниц (для tif) 
3. Далее происходит масштабирование всех фото под единый размер
4. Сохранение в формате jpg и в формате tif
