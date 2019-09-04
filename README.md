# linux-image-5.2.11_X86_64_zstd_versia_7_griggorii_config
linux-image-5.2.11_X86_64_zstd_versia_7_griggorii_config

Скачать deb пакетами готовое ядро https://drive.google.com/open?id=1DstgvGVCTW-NnOcUCyBa79ynQFGMP95c

Ядра проверены все работает всё заводится не совсем zstd конфиг от ядра 4.18 с небольшими или почти без изменений моя система 
уже автоматом исправляет ошибки в конфиге если сами ядра не сырые сама система https://github.com/Griggorii/Cinnamon-Budgie-Linux-OS-11-based-19.04-Ubuntu-Pop

-----------------------------------------------------------------------------------------------------------------------------

Зависимости которые надо установить для компиляции 

&& sudo apt update && apt --reinstall install gcc make dpkg-dev cpp bc fakeroot libncurses5-dev qt5-default libncurses-dev libglade2-dev bison build-essential flex font-uralic g++ g++-8 git git-man libbison-dev libc6-dev libc-dev-bin linux-libc-dev liberror-perl libfl-dev libfl2 libstdc++-8-dev zlib1g-dev libelf-dev libssl-dev 

-----------------------------------------------------------------------------------------------------------------------------



Конфигурировать можно командами 

     "make config"      Plain text interface.

     "make menuconfig"  Text based color menus, radiolists & dialogs.

     "make nconfig"     Enhanced text based color menus.

     "make xconfig"     X windows (Qt) based configuration tool.

     "make gconfig"     X windows (Gtk) based configuration tool.
     
     Моё минимальное ядро на котором я нахожусь это https://github.com/Griggorii/linux-image-5.2.11_X86_64_zstd_versia_4_griggorii_config 
     все последующие ядра раздаю если вдруг у вас есть какие то 
     специфичные устройства для которых нужны модули я же пока не нуждаюсь в модулях и моё оборудование
     работает и вроде все устройства поддерживает которые у меня под рукой , так что в случае чего в других 
     ядрах у меня на гит гораздо больше модулей.
