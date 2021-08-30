# Install NoiseTorch (RealTime Voice Noise Remover) In Linux

### 1 - Download NoiseTorch Release   
[https://github.com/lawl/NoiseTorch/releases](https://github.com/lawl/NoiseTorch/releases)

### 2 - Unpack The Downloaded `tgz` File To Your Home Directory
```bash 
tar -C $HOME -xzf NoiseTorch_x64.tgz
```

### If You Are Using Gnome... Refresh Icons Cache
```bash
gtk-update-icon-cache
```

### 3 - Set Required Permissions With `setcap`
```bash
sudo setcap 'CAP_SYS_RESOURCE=+ep' ~/.local/bin/noisetorch
```

## NoiseTorch Installed Successfullt ^^  
#### Run
```bash
~/.local/bin/noisetorch 
```

if you want, you can set `Run Command` in startup


#### Source 
[https://github.com/lawl/NoiseTorch](https://github.com/lawl/NoiseTorch)
