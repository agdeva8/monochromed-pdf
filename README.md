ABOUT IT:

This script converts any greyscaled/colored pdf to monochrome for better readliblity, Its user freindly script and anyone can easily use it. It can be more useful for college students where one wants to read the notes captured from camera or where one wants to make captured pdf look like scan copy. There are apps which does this work while capturing the pic but this script will save time while capturing.

HOW TO USE:
1. Download the script 
2. open terminal (ctrl+Alt+T) 
3. Now enter these commands in terminal; 
4. cd ~/Downloads 
5. unzip monochromed-pdf-master.zip 
6. cd monochromed-pdf-master/ 
7. chmod +x convert2monochrome.sh 
8. ./convert2monochrome.sh 
9. Now do as the script says :) 

TROUBLE SHOOT:
1. For error of the type: convert-im6.q16: not authorized `pdfFinal.pdf' @ error/constitute.c/WriteImage/1037.

edit the following file: /etc/ImageMagick-6/policy.xml
and set the permissions from none to read|write
Replace: rights="none" to rights="read|write"