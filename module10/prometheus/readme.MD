### sync VM time with host
```
shutdown vm
cd VirtualBox\ VMs
VBoxManage list vms
"localkube" {014a8874-1cbe-43ec-a47c-ce7248bce13e}
vboxmanage setextradata "localkube" "VBoxInternal/Devices/VMMDev/0/Config/GetHostTimeDisabled" "1"
```
### start VM and then you can get prometheus data

### grafana dashboard
```
cluster health
6417
pod dashboard
9729
Istio Mesh
7639
```