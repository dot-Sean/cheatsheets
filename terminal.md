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

### DNS Lookup

```bash
dig winterbe.com +nostats +nocomments +nocmd
```

### Flush DNS Cache

```bash
dscacheutil -flushcache
```

### Convert MOV to MP4

```bash
ffmpeg -i myfile.mov -vcodec h264 myfile.mp4
```

### Grep Java type usage

```bash
grep -or "com\.company\.project.\+" * | grep -o ":[a-zA-Z0-9\.]\+" | sort | uniq
```

### Text to speech

```bash
echo woot | say -v Albert
```

### Pipe stdout and sterr to file

```bash
some_command > everything.txt 2>&1
```

### Java Thread Dumps

```bash
sudo jstack -F $PID > threads.log
```
