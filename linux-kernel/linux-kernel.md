## For checking list of kernels in your system
```bash
dpkg --list | grep linux-image
```

## Remove old linux image
```
sudo apt remove --purge linux-image-5.7.0-2parrot2-amd64
```