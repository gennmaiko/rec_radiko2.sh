# rec_radiko2.sh
必要なもの↓
  ```
  $ sudo pacman -S swftools rtmpdump libxml2 wget ffmpeg lame
  ```
プログラムについて右も左も分からない私がradikoの仕様変更後に使えなくなったご本家rec_radiko.shを現仕様に対応させるため
https://gist.github.com/matchy2/3956266
様と
https://gist.github.com/saiten/875864
様のスクリプトを合わせて差分をとろうと「vimdiff　使い方」で必死にぐぐりました。
gitもcloneする使い方以外分からないのですべてWebから使ってます。
  ```
  $ crontab -l
  59 17 * * 6 /mnt/ubuntu/src/rec_radiko2.sh KISSFMKOBE 32 /mnt/ubuntu/home/gennmaiko/Music/radio/ weekly_garden
  ```
  
