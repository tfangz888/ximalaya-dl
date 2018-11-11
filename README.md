# Download ximalaya podcast

**Usage:**  
python xima.py <album_no> <page_num>
example: python xima.py 16123812 3

For example:  
http://www.ximalaya.com/lishi/3703879/  
3703879 is the <album_no>

If downloading the album for the first time, it will create a folder with the album name and start downloading from 1st episode  

It will also track the downloaded episodes, so if you run it again it will only download new/undownloaded episodes.  


**Dependency:**  
Only external module used is requests, if you don't have one:  
pip install requests

**Note:**  
下载的MP3在windows下能播放，但在某些播放器里播放不了。这时需要用格式工厂全部转换成MP3一次就可以播放了。
