# adb install

> Android Debug Bridge Install: Установка пакетов на эмулятор Android или подключенное устройство Android.
> Больше информации: <https://developer.android.com/studio/command-line/adb>.

- Установить приложение Android на эмулятор/устройство:

`adb install {{путь/до/файла.apk}}`

- Переустановить существующее приложение, оставив его данные:

`adb install -r {{путь/до/файла.apk}}`

- Дать все разрешения, перечисленные в манифесте приложения:

`adb install -g {{путь/до/файла.apk}}`

- Быстрое обновление установленного пакета путём обновления только тех частей APK, которые изменились:

`adb install --fastdeploy {{путь/до/файла.apk}}`
