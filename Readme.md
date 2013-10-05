# Зангилааг Эзэмших нь

 "Зангилааг эзэмших нь" бол зангилаан хакеруудаас зангилаан хакеруудад зориулан гаргаж буй нээлттэй эхийн эНом юм. ВышнМедиагийн/VisionMedia/ хөгжүүлэгч ТиЖэй Головэйчакийн/TJ Holowaychuk/ санаачилсан "http://visionmedia.github.io/masteringnode/" цахим номыг Монгол хэлнээ буулгахыг зорив...

## Зохиогч

 - ТиЖэй Головэйчак /TJ Holowaychuk/ ([visionmedia](http://github.com/visionmedia))

## Формат

 Зангилааг эзэмших нь номыг `./chapters` хавтас дотор бүлэг, бүлгээр хэсэгчилэн бичсэн байгаа. Ингэснээр номыг _pdf_, _mobi_, _epub_ болон _html_ гэх мэт олон төрлийн бичиг баримтын өргөтгөлөөр боловсруулж гаргах боломжтой.

## Нийт формат

Тушаалын мөрөнд дараах тушаалыг өгснөөр бүх форматаар боловруулна.

    $ make

## PDF

PDF баримт болгоход _brew_ хэрэгтэй ба дараах хоёр тушаалыг өгөхөд хангалттай:

    $ brew install htmldoc
    $ make book.pdf

## HTML

HTML хуудас болгоход _ronn_ хэрэгтэй ба дараах хоёр тушаалыг өгөхөд хангалттай:

    $ gem install ronn
    $ make book.html

## EPUB && MOBI

_Epub_, _Mobi_ өргөтгөл бүхий цахим ном болгоход [Calibre](http://calibre-ebook.com/) цахим ном програм шаардлагатай ба суулгасны дараа доорх тушаалаар боловсруулна.

    $ make book.epub
    
    $ make book.mobi

## Эх сурвалж

Энэхүү номд ашиглагдсан програмын хувилбар:

  - node 0.2.0

## Эх

Нийт жишээ файлуудыг зангилаа ашиглан шууд ажиллуулж болно.
Жишээлбэл:

      $ node src/events/basic.js

## Лиценз

Node.js бол "Joyent"-ийн албан ёсны худалдааны тэмдэг юм. Гэвч энэхүү ажил нь "Joyent Node.js"-ийн худалдааны эсэхүл нээлттэй эхийн төсөлд хамаарахгүй.

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/3.0/"><img alt="Creative Commons License" style="border-width:0" src="http://creativecommons.org/images/public/somerights20.png" /></a><br /><span xmlns:cc="http://creativecommons.org/ns#" property="cc:attributionName">ТиЖэй Голловэйчак</span>-ийн <span xmlns:dc="http://purl.org/dc/elements/1.1/" href="http://purl.org/dc/dcmitype/Text" property="dc:title" rel="dc:type">Node-ийг Эзэмших нь</span> бүтээлийн лиценз <br/> <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/3.0/">Creative Commons Attribution-NonCommercial-ShareAlike 3.0 Unported License</a>.
