    1  cd ocr-test
    2  sudo apt-get install tesseract-ocr
    3  sudo apt-get install imagemagick
    4  convert -density 300 ~/war-diary/e001518087.jpg -depth 8 -strip -background white -alpha off e001518087.tiff
    5  ls
    6  tesseract e001518087.tiff output.txt
    7  ls
    8  sudo apt-get install libcurl4-gnutls-dev
    9  sudo apt-get install libmagick++-dev
   10  sudo apt-get install libtesseract-dev
   11  sudo apt-get install libleptonica-dev
   12  sudo apt-get install tesseract-ocr-eng
   13  sudo apt-get install libpoppler-cpp-dev
   14  tesseract output_1.png output_1.txt
   15  ls
   16  cd ..
   17  mkdir war-diary-txt
   18  cd war-diary-txt
   19  ls
   20  history > module2exercise6_commands.md
