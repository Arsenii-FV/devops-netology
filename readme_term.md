5.
Default
Base memory : 1024mb
Processor : 1 Cpu
Virtual size : 64 Gb
Actual size : 1.7 Gb

6.
config.vm.provider "virtualbox" do |vb|
  #   # Display the VirtualBox GUI when booting the machine
  #   vb.gui = true
  #
  #   # Customize the amount of memory on the VM:
     vb.name = "ubuntu-20.04-netology"
	 vb.memory = "4096"
	 vb.cpus = 2
end

8.
history xx , где хх- число вывода последних строк журнала ,  2396 строка
ignoreboth — использовать обе опции ‘ignorespace’ и ‘ignoredups’
ignorespace — не сохранять строки начинающиеся с символа <пробел>
ignoredups — не сохранять строки, совпадающие с последней выполненной командой
настройки в файле /home/vagrant/.bashrc

9.
Список команд находящийся в {} скобках выполняется в текущей среде оболочки. Строка 213

10.
10.1 OK
10.2 touch test{1..300000}
-bash: /usr/bin/touch: Argument list too long

11.
Проверяет существует ли каталог /tmp

12.
mkdir /tmp/new_path_directory
export PATH=$PATH:/tmp/new_path_directory
source ~/.bashrc
sudo ln /usr/bin/bash /tmp/new_path_directory/bash

13.
Команда batch выполняет задание в порядке очереди пакетов (когда загрузка системы ниже 1,5%)
Команда at выполняет задание разово в запланированное время
