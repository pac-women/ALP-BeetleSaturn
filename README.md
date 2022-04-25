# ALP-Beetle Saturn

How To Build Beetle Saturn for ALP

- Source: https://github.com/libretro/beetle-saturn-libretro
- Build steps
```
# prepare
git clone https://github.com/libretro/beetle-saturn-libretro
cd beetle-saturn-libretro

# build
source /opt/rk3399env.sh
make platform=unix_gles IS_X86=0
```
- executable output:
	**mednafen_saturn_libretro.so**

