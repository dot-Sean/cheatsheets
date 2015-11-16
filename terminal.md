# Useful OSX terminal commands

### Find and delete files

```bash
find . -name my_folder -exec rm -rf {} \;
```

### Compress folder

```bash
tar cfz myfile.tar.gz myfolder/
```

### Uncompress folder

```bash
tar xfz myfile.tar.gz
```

### Upload files

```bash
scp -P 1234 myfile.txt user@111.222.333.444:/some/folder
```

### Check free disk space

```bash
df -h
```

### Check size of directory contents

```bash
du -sh *
```

