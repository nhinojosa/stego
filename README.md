# stego

- git clone https://github.com/nhinojosa/stego.git
- sudo apt install steghide
- sudo apt install exiftool
- sudo apt install stegosuite

- exiftool [imagefile.jpg]

- steghide embed -cf image.jpg -ef secretmessage.txt

- steghide info image.jpg

- steghide extract -sf image.jpg
