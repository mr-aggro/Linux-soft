# Linux-soft
EСТАНОВКА ПОДДЕРЖКИ Serial EPS32/Arduino

    arduino-linux-setup.sh

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
Указатель мыши:

    La Capitaine: https://github.com/keeferrourke/capitaine-cursors

Шрифты:

        sudo apt-get install fonts-cantarell

        Window Title: Cantarell Bold

        GUI: Cantarell Regular

        Doc: Sans Regular

        Monospace: Monospace Regular
        
Настройка метрики сетевых интерфейсов:
        sudo nano /etc/dhcpcd.conf
            
        For DHCP:
        
            interface eth0
        
            metric <num>
        
            interface wlan0
        
            metric <num>
            
       For Static:
       
            interface eth0
            
            static ip_address=192.168.1.16/24
            
            static routers=192.168.1.1
            
            static domain_name_servers=127.0.0.1
            
            metric <num>
