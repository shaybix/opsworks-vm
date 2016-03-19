Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu1404-opsworks"
  config.vm.provision :opsworks, type: 'shell', args: 'path/to/dna.json'
end
