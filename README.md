Template for installing rancheros' cloud-init.yaml file

**Note**: Use spaces instead of tabs

```shell
# Just validate syntax
sudo ros config validate -i <cloud-init.yaml>
```

```shell
# To ensure it can be loaded correctly
sudo ros config merge -i <cloud-init.yaml>
```

```shell
sudo ros install -c <cloud-init.yaml> -d <device>
```

> If using a virtual machine to install rancheros, remember to remove the image when the installer asks whether to reboot.
