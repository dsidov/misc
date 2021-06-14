# ACDSee photo sorter

Script is searching for opened image file and copying it by pressing Enter. 


## Dependencies
* Python 3.8+
* win32gui (check python compability first!)
`pip install win32gui`

## Description
* Run script/program (you can easily create .exe file using pyinstaller).
* Enter file extension, which you want you sort. Default extension is Nikon .NEF
* (Program will check is here sorted files already and will show last of them)
* Open file in ACDSee. Use mouse scroll to navigate in photos and press Enter when you see matching file.
* (File will be copied to `_sorted` folder. You'll see your progress and total files sorted)

## P.S.
File name extension option should be on!
* `Windows Explorer -> View -> File name extension`