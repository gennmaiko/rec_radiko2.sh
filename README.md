# rec_radiko2.sh
必要なもの↓</br>
$ sudo pacman -S swftools rtmpdump libxml2 wget ffmpeg lame </br>
</br>
ご本家rec_radiko.shのように時間指定してcrontabに登録したかったのです</br>
$ crontab -l </br>
59 17 * * 6 /mnt/ubuntu/src/rec_radiko2.sh KISSFMKOBE 32 /mnt/ubuntu/home/gennmaiko/Music/radio/ weekly_garden </br>
</br>
プログラムについて右も左も分からない私が</br>
https://gist.github.com/matchy2/3956266 </br>
様と</br>
https://gist.github.com/saiten/875864 </br>
様のスクリプトを合わせて差分をとろうと「vimdiff　使い方」で必死にぐぐりました</br>
gitもcloneする使い方以外分からないのですべてWebから使ってます</br>
