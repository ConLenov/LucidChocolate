## LucidChocolate GTK theme

How to install GTK theme like main Ubuntu UI 10.04 theme

### 1. Clone data for `/usr/share/themes`
```bash
cd /tmp;
git clone https://github.com/ConLenov/LucidChocolate.git;
rm LucidChocolate/doc LucidChocolate/README.md -rv; 
```
### 2. Copy data as superuser

Type after `sudo bash` or similar commands

```bash
chown 0:0 -Rv /tmp/LucidChocolate; 
mv LucidChocolate/ /usr/share/themes/ -v;
```
### 3. Run a theme manager.
For example
```
mate-appearance-properties
```
<img src="doc/Пример.png" alt="Theme example"/>
