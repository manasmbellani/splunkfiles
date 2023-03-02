# splunkfiles
Files that pertain to Splunk Lab Deployment

## Usage

To backup the file, ensure that first the file type is tracked for `lfs`:
```
git lfs track "*.msi"
```

Then copy the files and backup as usual e.g. `~/test.msi`:
```
cp ~/test.msi .
git add . 
git commit -m "test.msi: adding new file"
git push
```
