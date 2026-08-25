# Zaheermatn Font خط ظهير متن

Zaheermatn is an Arabic font project forked from Vazirmatn.
Here are the main intended differences:

#### Hamza

* Make standalone hamza ء size smaller to match seated (combined) hamza ؤ أ ئ
* Add support for inline hamza, 
  * Implementation should match Amiri's so that typing ء between two joining letters will not break the joining.
  * Also allow for Hamza combined with tatweel implementation.
  * Pay special attention to hamza between lam-alef ligature.
 
#### Lam-alef ligature

Use classic لا ligature everywhere.

#### heh

The character ه should follow a basic form in all 4 positions: ه ههه

#### kaf

Use ک for Arabic kaf instead of ك

#### seen

The teeth of seen س should be shorter and closer together to distinguish from ب.
Also, don't raise first tooth to make it higher than the following ones in initial position.

#### Add honorifics

Copy over from Kitab font.
