# fontconfig-zh-cn

## 📖[使用说明](https://github.com/rabbee/fontconfig-zh-cn)

- For Archlinux

```bash
cd fontconfig-zh-cn
sudo cp fonts.conf /etc/fonts/conf.avail/99-"yourname".conf
sudo ln -sf /etc/fonts/conf.avail/99-yourname.conf /etc/fonts/conf.d/
fc-cache --force -v
 ```