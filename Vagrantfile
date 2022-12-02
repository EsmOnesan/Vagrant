Vagrant.configure(2) do |config|
    # образ системы Ubuntu 20.04 LTS
    config.vm.box = "ubuntu/trusty64"
    # не проверять репозиторий на наличие обновлений
    config.vm.box_check_update = false
  
    config.vm.provider "virtualbox" do |vb|
      # имя виртуальной машины
      vb.name = "vm1"
      # объем оперативной памяти
      vb.memory = 2048
      # количество ядер процессора
      vb.cpus = 2
    end
    
    # hostname виртуальной машины
    config.vm.hostname = "vm1"
    config.vm.network "public_network", type: "dhcp", bridge: "Intel(R) Wireless-AC 9462"
end