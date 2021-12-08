# Suckless

My suckless utilities with custom configs and tweaks to make it more clean 

If you're feeling spicy and wanna use my setup, you can drop one of these and try your luck

```bash
git clone https://github.com/dandeeccastro/suckless
cd suckless
for Dir in $(ls -d /*); do
	cd $Dir
	sudo make clean install
	cd ..
done
```
