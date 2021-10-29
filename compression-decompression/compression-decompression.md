## Zip

Create zip file 
```bash
zip {output_filename}.zip {input_filename}
```
Decommpress zip file
```bash 
unzip {filename}.zip
```
Create zip file from foldder
```bash
zip -r {output_filename}.zip {foldername}
```

## Rar

Create rar file 
```bash
rar a {output_filename}.rar {input_filename}
```
Decommpress zip file
```bash 
unrar x {filename}.rar
```
Create zip file from foldder
```bash
rar a {output_filename}.rar {foldername}
```

## Tar

1. For .tar

Create rar file 
```bash
tar -cvf {output_filename}.tar {input_filename}
```
Decommpress zip file
```bash 
tar -xzvf {filename}.tar
```
Create zip file from foldder
```bash
tar -cvf {output_filename}.tar {foldername}
```

2. For .tar.gz

Create rar file 
```bash
tar -czvf {output_filename}.tar.gz {input_filename}
```
Decommpress zip file
```bash 
tar -xvf {filename}.tar.gz
```
Create zip file from foldder
```bash
tar -czvf {output_filename}.tar.gz {foldername}
```

3. For .tar.bz2

Create rar file 
```bash
tar -cjvf {output_filename}.tar.bz2 {input_filename}
```
Decommpress zip file
```bash 
tar -xjvf {filename}.tar.bz2
```
Create zip file from foldder
```bash
tar -czvf {output_filename}.tar.bz2 {foldername}
```

## Deb
 
Decommpress deb file
```bash
dpkg-deb -x {input_filename}.deb {output_foldername}
# it will not extract 'DEBIAN' directory from deb file

# extract 'control' file 
dpkg-deb -e {input_filename}.deb

# or
dpkg-deb -e {input_filename}.deb {output_foldername} 
```
Create deb file
```bash 
dpkg-deb -b {foldername}
# that folder with 'DEBIAN' directory and 'control' file in 'DEBIAN' directory

# to specify output filename
dpkg-deb -b {foldername} {output_filername}.deb
```