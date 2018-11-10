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
