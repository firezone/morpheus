Vagrant.configure("2") do |config|
    config.vm.box = "generic/alpine35"

    config.vm.define 'alpine'

    # Prevent SharedFoldersEnableSymlinksCreate errors
    config.vm.synced_folder ".", "/vagrant", disabled: true
end
