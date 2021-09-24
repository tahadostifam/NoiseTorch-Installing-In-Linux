# ติดตั้ง NoiseTorch (RealTime Voice Noise Remover) ใน Linux

### 1 - ดาวน์โหลด NoiseTorch Release   

[https://github.com/lawl/NoiseTorch/releases](https://github.com/lawl/NoiseTorch/releases)

### 2 - แกะไฟล์ `tgz' ที่ดาวน์โหลดมาไว้ในโฮมไดเร็กทอรีของคุณ

``` ทุบตี 

tar -C $HOME -xzf NoiseTorch_x64.tgz

```

### หากคุณกำลังใช้ Gnome... รีเฟรชไอคอน แคช

``` ทุบตี

gtk-update-icon-cache

```

### 3 - ตั้งค่าการอนุญาตที่จำเป็นด้วย `setcap`

``` ทุบตี

sudo setcap 'CAP_SYS_RESOURCE=+ep' ~/.local/bin/noisetorch

```

## ติดตั้ง NoiseTorch สำเร็จแล้ว ^^  

#### วิ่ง

``` ทุบตี

~/.local/bin/noisetorch 

```

หากต้องการ คุณสามารถตั้งค่า `Run Command` ในการเริ่มต้น

#### แหล่งที่มา 

[https://github.com/lawl/NoiseTorch](https://github.com/lawl/NoiseTorch)

