# Нужен Docker.

Запускать в режиме Linux контейнеров.

Конвертация PSD в PNG

docker run --entrypoint=mogrify -v [full-path-to-repo]\Sprites\Map\WallsCommon:/imgs dpokidov/imagemagick -format png /imgs/*.psd[0]

В клиент отправлять только PNG, потому что PSD импортируется без прозрачности.