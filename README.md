# barcode_php
A php scripts to generate barcode

This is a modified version of the code provided by:

https://ashberg.de/php-barcode/

Notes:

1 PHP GD Library must have FreeType enabled

2 Must have a TTF font file in the php file directory:
  $font = __DIR__."/DejaVuSans.ttf";

3 The command to generate the digits:
  imagettftext($im, 24, 0, 75, 240, $col_text, $font, $text);
  //numbers are set for the positioning of the text
  
  Hope this helps.
  
  
