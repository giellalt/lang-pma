# The Paamese morphophonological/twolc rules file 

## The Paamese letters, symbols and letter sets

### Alphabet and symbols

* a b c d e f g h i j k l m n o p q r s t u v w x y z æ ø å 
 á é ó ú í à è ò ù ì ä ë ö ü ï â ê ô û î ã ý þ ñ ð ß ç 
* ā ē ī ō ū. 

* A B C D E F G H I J K L M N O P Q R S T U V W X Y Z Æ Ø Å 
 Á É Ó Ú Í À È Ò Ù Ì Ä Ë Ö Ü Ï Â Ê Ô Û Î Ã Ý þ Ñ Ð 

* %> %< ; 

### Sets

* Vow = a e i o u y æ ø å ā ē ī ō ū. 
 á é ó ú í à è ò ù ì ä ë ö ü ï â ê ô û î ã ý ; 
* Cns = b c d f g h j k l m n p q r s t v w x z ; 

## Rule section

**RULE: Delete affix initial -i-** =  for e- and o- stems in the Px declension.

**RULE:  i is backed to u before u over a morpheme boundary** 

* example: ni+uasi+e = nuuasie (1SG.dist.hit.3SG; I will hit him)
* example: i+umo = ūmo (3PL.dist.work; they will work)
* *ni>uasi>e*
* *nu>0asi>e*
* *i>umo*
* *u>umo*

**RULE:  e is backed to o where there is a following u** = This rule applies only when the front vowel precedes the back vowel, and not when it follows the back vowel. This rule is stated without reference to any morpheme boundaries.
We should consider %< instead of %> (for prefixes)

* example: he+uasi+e --> houasie 3SG.dist.hit.3SG; he will hit him)
* example: he+usili+e --> housilie (3SG.dist.follow.3SG; he will follow him)
* *he>uasi>e*
* *ho>uasi>e*

**RULE:  Vowel deletion in stem medial position** = works in stem medial position, a vowel is deleted between an identical vowel and any other vowel, either preceding or following it

* *ni>uasi>e*
* *nu>0asi>e*
* example: ni+uasi+e --> nūasie --> nuasi (1SG.dist.hit.3SG; I will hit him)

**RULE:  e raising** = e raises to i between the vowels o and a on the one hand, and the vowels a and a on the other.

* *lenga>ealo*
* *lenga>ialo*
* *lango>ealo*
* *lango>ialo*

**RULE:  e deletion** = e is deleted whenever it occurs in the sequence iea

* *vati>ealo*
* *vati>0alo*

* * *

<small>This (part of) documentation was generated from [src/fst/phonology.twolc](https://github.com/giellalt/lang-pma/blob/main/src/fst/phonology.twolc)</small>

---

