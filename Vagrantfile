Vagrant.configure("2") do |config|
    config.vim.box = "bento/ubuntu-20.04"

    config.vim.provider "virutalbox" do |v|
        v.memory = 10240
        v.cpus = 3
    end
    config.vm.network "private_network", ip: "192.168.44.44"
end