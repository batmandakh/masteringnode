# Нөүдийг Эзэмших нь

 "Нөүдийг эзэмших нь" бол "Нөүд.ЖС"-ийг суралцаж буй залууст зориулан нөүдийн хакеруудаас бэлтгэн гаргаж буй нээлттэй эхийн цНом юм. ВышнМедиагийн/VisionMedia/ хөгжүүлэгч ТиЖэй Головэйчакийн/TJ Holowaychuk/ санаачилсан "http://visionmedia.github.io/masteringnode/" цахим номыг Монгол хэлнээ буулгахыг зорив...

## Зохиогч

 - ТиЖэй Головэйчак /TJ Holowaychuk/ ([visionmedia](http://github.com/visionmedia))

## Формат

 Нөүдийг эзэмших нь номыг `./chapters` хавтас дотор бүлэг, бүлгээр нь хэсэгчлэн сийрүүлэн буулгасан. Ингэснээр номыг _pdf_, _mobi_, _epub_ болон _html_ гэх мэт олон төрлийн бичиг баримтын өргөтгөлөөр боловсруулж гаргах боломжтой.

## Нийт формат

Тушаалын мөр(Command line)-д дараах тушаалыг буулгаснаар бүх форматаар боловсруулна.

    $ make

## PDF

PDF баримт болгоход _brew_ хэрэгтэй ба дараах хоёр тушаалуудыг өгөн боловсруулна:

    $ brew install htmldoc
    $ make book.pdf

## HTML

HTML хуудас болгоход _ronn_ хэрэгтэй ба дараах хоёр тушаалуудыг өгөн боловсруулна:

    $ gem install ronn
    $ make book.html

## EPUB && MOBI

_Epub_, _Mobi_ өргөтгөл бүхий цахим ном болгоход [Calibre](http://calibre-ebook.com/) цахим номын програм шаардлагатай ба суулгасны дараа доорх тушаалаар боловсруулна.

    $ make book.epub
    
    $ make book.mobi

## Эх сурвалж

Энэхүү номд ашиглагдсан програмын хувилбар:

  - node 0.2.0

## Эх

Нийт жишээ файлуудыг нөүдийг ашиглан шууд ажиллуулж болно.
Жишээлбэл:

      $ node src/events/basic.js

## Зохиогчийн эрх

Node.js бол "Joyent"-ийн албан ёсны худалдааны тэмдэг юм. Гэхдээ энэхүү цахим ном нь "Joyent Node.js"-ийн ямар нэг худалдааны эсвэл нээлттэй эхийн төсөлд харъялагдахгүй.

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/3.0/"><img alt="Creative Commons License" style="border-width:0" src="http://creativecommons.org/images/public/somerights20.png" /></a><br /><span xmlns:cc="http://creativecommons.org/ns#" property="cc:attributionName">ТиЖэй Голловэйчак</span>-ийн <span xmlns:dc="http://purl.org/dc/elements/1.1/" href="http://purl.org/dc/dcmitype/Text" property="dc:title" rel="dc:type">Node-ийг Эзэмших нь</span> бүтээлийн лиценз <br/> <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/3.0/">Creative Commons Attribution-NonCommercial-ShareAlike 3.0 Unported License</a>.
