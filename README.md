# Linux-soft
УСТАНОВКА KRITA ПРОФИССИОНАЛЬНОГО ГРАФИЧЕСКОГО РЕДАКТОРА

    from PPA
    
    sudo add-apt-repository -y ppa:kritalime/ppa
    sudo apt update
    sudo apt install krita-testing krita-nautilus-thumbnailer
    
    from APT
    sudo apt-get install krita
    
ОБНОВЛЕНИЕ ДРАЙВЕРОВ
    NVIDIA NATIVE DRIVER
    для ПК:

    sudo add-apt-repository -y ppa:graphics-drivers/ppa
    sudo apt update

ДЛЯ НОУТБУКОВ NVIDIA

    sudo apt install -y nvidia-361 nvidia-settings nvidia-prime

ДЛЯ НОУТОВ\ПК INTEL\AMD

    sudo add-apt-repository -y ppa:paulo-miguel-dias/pkppa
    sudo apt update
    
ДЛЯ ИНФОРМАЦИИ О СИСТЕМЕ

    sudo apt-get install screenfetch inxi
    Для подробной информации о железе устройства нужно ввеси в терминале: inxi -F
