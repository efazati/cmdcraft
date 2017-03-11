# spliter
split --bytes 30M --numeric-suffixes --suffix-length=3 input.txt output

find . -name "*.pyc" -exec rm -rf {} \;

ps auxww | grep 'bfl.sock' | awk '{print $2}' | xargs kill -9;

dd if=/home/user/Downloads/debian.iso of=/dev/sdb1 bs=512M; sync

lsblk

TAR:
c – Creates a new .tar archive file.
v – Verbosely show the .tar file progress.
f – File name type of the archive file.
tar -cvf archieve.tar.gz(.bz2) /path/to/folder/abc
tar cvzf MyImages-14-09-12.tar.gz /home/MyImages
tar cvfj Phpfiles-org.tar.bz2 /home/php

Extract
tar -xvf public_html-14-09-12.tar
tar -zxvf abc.tar.gz (Remember 'z' for .tar.gz)
tar -jxvf abc.tar.bz2 (Remember 'j' for .tar.bz2)

for file in *.JPG; do convert $file -interlace Plane -resize 85% -quality 85%  -gaussian-blur 0.05 $file; done

mogrify -format jpg *.png


mysqldump -u root -p --databases khp > khpc_fixed_page.sql

nc -zv  85.185.83.35 22

cloc

pybabel update -i messages.pot -d translations
pybabel compile -d translations


scp ./* argus@162.223.95.148:/opt/argus/www/r2tg1/project/media/statics/blue/img


xargs -i wget --limit-rate=400k -c '{}'  < dl


for i in */; do zip -r "${i%/}.zip" "$i"; done


for D in */; do subliminal download ./"${D}"*.mp4 -l eng ; done;

for file in *.JPG; do convert $file -resize 25% minify-$file; done

for file in *.JPG; do convert $file -strip -interlace Plane -gaussian-blur 0.05 -quality 85% minify-$file; done

for file in *.JPG; do convert $file -strip -interlace Plane -gaussian-blur 0.05 -quality 85%  -black-threshold 50% minify-$file; done

for file in *.JPG; do convert  $file -profile sRGB.icc -strip  base.png; convert base.png  -auto-level -auto-gamma  -blur 0x10 -fill White -fuzz 10%% -draw "color 0,0 floodfill"  -fill Black +opaque White  mask.png;   convert base.png -morphology dilate disk:2 b-base.png;  convert $file base.png b-base.png mask.png  -compose Over -composite final-$file ; done


for file in *.JPG; do convert  $file -profile sRGB.icc -strip  base.png; convert base.png  -auto-level -auto-gamma  -blur 0x10 -fill White -fuzz 10%% -draw "color 0,0 floodfill"  -fill Black +opaque White  mask.png;   convert base.png -morphology dilate disk:2 final-$file ; done

$ cat fixed-positions.json | jq 'sort_by(.page)' > sorted

for file in *.JPG; do convert $file -gaussian-blur 0.05 -quality 90% -resize 400 ../$file; done
for file in *.jpg; do convert $file  -resize 400 ../$file; done

ffmpeg -i output.avi -c:v libx264 -preset slow -crf 15 output-final.mkv



ffmpeg -r 25 -pattern_type glob -i '*.jpg' -c:v copy output.avi

mogrify -path resized -resize 1920x1080! *.JPG
ffmpeg -i output.avi -filter:v scale=720:-1 -c:a copy output.mkv