
### Install di Termux
````
pkg install nodejs-lts git tesseract libwebp wget imagemagick ffmpeg
git clone https://github.com/TypeRegency/Type0
wget https://raw.githubusercontent.com/tesseract-ocr/tessdata_best/master/ind.traineddata
mv ind.traineddata /data/data/com.termux/files/usr/share/tessdata 
cd whatsapp-bot
npm install
node index.js
````

### Install di Linux (ubuntu & debian)
```
sudo apt install npm git webp imagemagick ffmpeg
sudo apt install tesseract-ocr tesseract-ocr-ind
sudo npm install -g n
sudo n stable
git clone https://github.com/TypeRegency/Type0
cd whatsapp-bot
npm install
node index.js
```

### fitur
```
- convert gambar ke sticker
- convert text ke sticker
- convert text ke gif sticker
- convert sticker ke gambar
- convert sticker ke gif
- convert gambar ke pdf
- nulis
- brainly
- ocr
- random quotes
- random pengetahuan
- text to sound
- wikipedia
- soal matematika
- bahasa planet
```
