Проект по переводу BMP-картинки в монохромный BMP. При запуске без параметров выодит краткое описание, как его использовать: первым параметром можно передать путь до входного файла, а вторым - префикс выходных файлов (для черно-белого монохрома, 16-цветного и 256-цветного изображений в оттенках серого).
Рекомендуется использовать MinGW GCC компилятор ("gcc BMP_to_monochrome.c bmp.c -o bmtToMonochrome.exe"), при установленном cmake можно запустить "build.bat".