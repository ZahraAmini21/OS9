# OS9
1-

chown
مالک تصمیم می‌گیره چه کسی به فایل اون بتونه «نگاه» کنه یا «دست بزنه».
chown -R
با بکارگیری فلگ R- تغییرت به همه زیرشاخه ها اعمال خواهد شد 
chown -v
تغییرات انجام شه را نمایش میدهد
 chown -f 
 این دستور برای کاهش خطا ها استفاده میشود
 gpasswd -a 
 کابر جدید رو به گروه ها اضافه میکند 
 gpasswd -d
 کاربر را از گروه حذف میکند
 gpasswd -r
 پسورد گروه را پاک میکند
2-id username 
بجای username حساب کاربری مورد نطر رو وارد میکنیم و اطلاعات اون رو چاپ میکند
3-sudo adduser oslab
  sudo password 25
  
4-sudo addgroup sadjad
  sudo addgroup Uni
  sudo usermod -G sadjad oslab
  sudo usermod -G Uni oslab
  sudo gpasswd -A oslab sadjad
  
5-sudo adduser os2
  sudo usermod -G sadjad os2
  sude userdel -r os2
