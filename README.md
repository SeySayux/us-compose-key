U.S. QWERTY with Compose Key keyboard layout for macOS
======================================================

This is a keyboard layout for macOS adapted from the normal US QWERTY layout to
add a "compose key" (symbol ⎄). The compose key allows you to type various
foreign symbols without the introduction of dead keys (such as for `"` or `'`)
or the need to remember specific code point numbers.

For example, pressing ⎄`'a` (first press Compose, then `'`, then `a`) would
yield á.

By default, the compose key is mapped to the key between the left shift and the
W key on ISO keyboards (ANSI keyboards lack this key). This means with the
default settings, you cannot use this layout on Apple's American English
keyboards, but you can use it on their British or International English
keyboards. Alternatively, you may use a tool such as 
[PCKeyboardHack](https://pqrs.org/macosx/keyremap4macbook/pckeyboardhack.html.en)
to remap another key (such as Caps Lock) to be the compose key. The key code
used for the compose key is `50`.

To edit the keyboard layout, you need to use the 
[Ukulele](http://scripts.sil.org/cms/scripts/page.php?site_id=nrsi&id=ukelele)
app.
To install the keyboard layout, drag the `U.S. with Compose Key.bundle` file to
the `/Library/Keyboard Layouts/` folder and enable it from the *Input Sources*
tab in the *Language & Text* panel in System Settings.

Below is a table of the various combinations. All symbols are produced by first
pressing Compose, followed by two or three keys, as shown in the table.

Key combinations
----------------


| Symbol |  Key 1  |  Key 2  |  Key 3  |      Unicode Name / *Description*     |
|:------:|:-------:|:-------:|:-------:|:--------------------------------------|
|        | (space) | (space) |         | NO-BREAK SPACE                        |
| ¸      | (space) | ,       |         | CEDILLA                               |
| ␣      | (space) | _       |         | OPEN BOX                              |
| ¡      | !       | !       |         | INVERTED EXCLAMATION MARK             |
| ‽      | !       | ?       |         | INTERROBANG                           |
| ¦      | !       | ^       |         | BROKEN BAR                            |
| Ä      | &quot;  | A       |         | LATIN CAPITAL LETTER A WITH DIAERESIS |
| Ë      | &quot;  | E       |         | LATIN CAPITAL LETTER E WITH DIAERESIS |
| Ḧ      | &quot;  | H       |         | LATIN CAPITAL LETTER H WITH DIAERESIS |
| Ï      | &quot;  | I       |         | LATIN CAPITAL LETTER I WITH DIAERESIS |
| N̈     | &quot;  | N       |         | *LATIN CAPITAL LETTER N WITH DIAERESIS* |
| Ö      | &quot;  | O       |         | LATIN CAPITAL LETTER O WITH DIAERESIS |
| T̈     | &quot;  | T       |         | *LATIN CAPITAL LETTER T WITH DIAERESIS* |
| Ü      | &quot;  | U       |         | LATIN CAPITAL LETTER U WITH DIAERESIS |
| Ẅ      | &quot;  | W       |         | LATIN CAPITAL LETTER W WITH DIAERESIS |
| Ẍ      | &quot;  | X       |         | LATIN CAPITAL LETTER X WITH DIAERESIS |
| Ÿ      | &quot;  | Y       |         | LATIN CAPITAL LETTER Y WITH DIAERESIS |
| ä      | &quot;  | a       |         | LATIN SMALL LETTER A WITH DIAERESIS   |
| ë      | &quot;  | e       |         | LATIN SMALL LETTER E WITH DIAERESIS   |
| ḧ      | &quot;  | h       |         | LATIN SMALL LETTER H WITH DIAERESIS   |
| ï      | &quot;  | i       |         | LATIN SMALL LETTER I WITH DIAERESIS   |
| n̈     | &quot;  | n       |         | *LATIN SMALL LETTER N WITH DIAERESIS* |
| ö      | &quot;  | o       |         | LATIN SMALL LETTER O WITH DIAERESIS   |
| ẗ      | &quot;  | t       |         | LATIN SMALL LETTER T WITH DIAERESIS   |
| ü      | &quot;  | u       |         | LATIN SMALL LETTER U WITH DIAERESIS   |
| ẅ      | &quot;  | w       |         | LATIN SMALL LETTER W WITH DIAERESIS   |
| ẍ      | &quot;  | x       |         | LATIN SMALL LETTER X WITH DIAERESIS   |
| ÿ      | &quot;  | y       |         | LATIN SMALL LETTER Y WITH DIAERESIS   |
| ‱      | %       | O       |         | PER TEN THOUSAND SIGN                 |
| ‰      | %       | o       |         | PER MILLE SIGN                        |
| ∧      | &       | &       |         | LOGICAL AND                           |
| Á      | '       | A       |         | LATIN CAPITAL LETTER A WITH ACUTE     |
| Ć      | '       | C       |         | LATIN CAPITAL LETTER C WITH ACUTE     |
| É      | '       | E       |         | LATIN CAPITAL LETTER E WITH ACUTE     |
| Í      | '       | I       |         | LATIN CAPITAL LETTER I WITH ACUTE     |
| Ḱ      | '       | K       |         | LATIN CAPITAL LETTER K WITH ACUTE     |
| Ĺ      | '       | L       |         | LATIN CAPITAL LETTER L WITH ACUTE     |
| Ḿ      | '       | M       |         | LATIN CAPITAL LETTER M WITH ACUTE     |
| Ń      | '       | N       |         | LATIN CAPITAL LETTER N WITH ACUTE     |
| Ó      | '       | O       |         | LATIN CAPITAL LETTER O WITH ACUTE     |
| Ṕ      | '       | P       |         | LATIN CAPITAL LETTER P WITH ACUTE     |
| Ŕ      | '       | R       |         | LATIN CAPITAL LETTER R WITH ACUTE     |
| Ś      | '       | S       |         | LATIN CAPITAL LETTER S WITH ACUTE     |
| Ú      | '       | U       |         | LATIN CAPITAL LETTER U WITH ACUTE     |
| Ẃ      | '       | W       |         | LATIN CAPITAL LETTER W WITH ACUTE     |
| Ý      | '       | Y       |         | LATIN CAPITAL LETTER Y WITH ACUTE     |
| á      | '       | a       |         | LATIN SMALL LETTER A WITH ACUTE       |
| ć      | '       | c       |         | LATIN SMALL LETTER C WITH ACUTE       |
| é      | '       | e       |         | LATIN SMALL LETTER E WITH ACUTE       |
| í      | '       | i       |         | LATIN SMALL LETTER I WITH ACUTE       |
| ḱ      | '       | k       |         | LATIN SMALL LETTER K WITH ACUTE       |
| ĺ      | '       | l       |         | LATIN SMALL LETTER L WITH ACUTE       |
| ḿ      | '       | m       |         | LATIN SMALL LETTER M WITH ACUTE       |
| ń      | '       | n       |         | LATIN SMALL LETTER N WITH ACUTE       |
| ó      | '       | o       |         | LATIN SMALL LETTER O WITH ACUTE       |
| ṕ      | '       | p       |         | LATIN SMALL LETTER P WITH ACUTE       |
| ŕ      | '       | r       |         | LATIN SMALL LETTER R WITH ACUTE       |
| ś      | '       | s       |         | LATIN SMALL LETTER S WITH ACUTE       |
| ú      | '       | u       |         | LATIN SMALL LETTER U WITH ACUTE       |
| ẃ      | '       | w       |         | LATIN SMALL LETTER W WITH ACUTE       |
| ý      | '       | y       |         | LATIN SMALL LETTER Y WITH ACUTE       |
| ±      | +       | -       |         | PLUS-MINUS SIGN                       |
| ⊕      | +       | O       |         | CIRCLED PLUS                          |
| ⊕      | +       | o       |         | CIRCLED PLUS                          |
| ¸      | ,       | (space) |         | CEDILLA                               |
| ¬      | ,       | -       |         | NOT SIGN                              |
| Ç      | ,       | C       |         | LATIN CAPITAL LETTER C WITH CEDILLA   |
| Ḑ      | ,       | D       |         | LATIN CAPITAL LETTER D WITH CEDILLA   |
| Ȩ      | ,       | E       |         | LATIN CAPITAL LETTER E WITH CEDILLA   |
| Ģ      | ,       | G       |         | LATIN CAPITAL LETTER G WITH CEDILLA   |
| Ḩ      | ,       | H       |         | LATIN CAPITAL LETTER H WITH CEDILLA   |
| Ķ      | ,       | K       |         | LATIN CAPITAL LETTER K WITH CEDILLA   |
| Ļ      | ,       | L       |         | LATIN CAPITAL LETTER L WITH CEDILLA   |
| Ņ      | ,       | N       |         | LATIN CAPITAL LETTER N WITH CEDILLA   |
| Ŗ      | ,       | R       |         | LATIN CAPITAL LETTER R WITH CEDILLA   |
| Ş      | ,       | S       |         | LATIN CAPITAL LETTER S WITH CEDILLA   |
| Ţ      | ,       | T       |         | LATIN CAPITAL LETTER T WITH CEDILLA   |
| ç      | ,       | c       |         | LATIN SMALL LETTER C WITH CEDILLA     |
| ḑ      | ,       | d       |         | LATIN SMALL LETTER D WITH CEDILLA     |
| ȩ      | ,       | e       |         | LATIN SMALL LETTER E WITH CEDILLA     |
| ģ      | ,       | g       |         | LATIN SMALL LETTER G WITH CEDILLA     |
| ḩ      | ,       | h       |         | LATIN SMALL LETTER H WITH CEDILLA     |
| ķ      | ,       | k       |         | LATIN SMALL LETTER K WITH CEDILLA     |
| ļ      | ,       | l       |         | LATIN SMALL LETTER L WITH CEDILLA     |
| ņ      | ,       | n       |         | LATIN SMALL LETTER N WITH CEDILLA     |
| ŗ      | ,       | r       |         | LATIN SMALL LETTER R WITH CEDILLA     |
| ş      | ,       | s       |         | LATIN SMALL LETTER S WITH CEDILLA     |
| ţ      | ,       | t       |         | LATIN SMALL LETTER T WITH CEDILLA     |
| ∓      | -       | +       |         | MINUS-OR-PLUS SIGN                    |
| ¬      | -       | ,       |         | NOT SIGN                              |
| —      | -       | -       | -       | EM DASH                               |
| –      | -       | -       | .       | EN DASH                               |
| ÷      | -       | :       |         | DIVISION SIGN                         |
| ←      | -       | <       |         | LEFTWARDS ARROW                       |
| →      | -       | >       |         | RIGHTWARDS ARROW                      |
| Đ      | -       | D       |         | LATIN CAPITAL LETTER D WITH STROKE    |
| Ħ      | -       | H       |         | LATIN CAPITAL LETTER H WITH STROKE    |
| Ɨ      | -       | I       |         | LATIN CAPITAL LETTER I WITH STROKE    |
| £      | -       | L       |         | POUND SIGN                            |
| ⊖      | -       | O       |         | CIRCLED MINUS                         |
| Ŧ      | -       | T       |         | LATIN CAPITAL LETTER T WITH STROKE    |
| Ƶ      | -       | Z       |         | LATIN CAPITAL LETTER Z WITH STROKE    |
| ⊖      | -       | o       |         | CIRCLED MINUS                         |
| ·      | .       | .       |         | MIDDLE DOT                            |
| •      | .       | o       |         | BULLET                                |
| ⁄      | /       | /       |         | FRACTION SLASH                        |
| ≠      | /       | =       |         | NOT EQUAL TO                          |
| ₡      | /       | C       |         | COLON SIGN                            |
| Ø      | /       | O       |         | LATIN CAPITAL LETTER O WITH STROKE    |
| ∧      | /       | \\      |         | LOGICAL AND                           |
| ¢      | /       | c       |         | CENT SIGN                             |
| ø      | /       | o       |         | LATIN SMALL LETTER O WITH STROKE      |
| ½      | 1       | 2       |         | VULGAR FRACTION ONE HALF              |
| ⅓      | 1       | 3       |         | VULGAR FRACTION ONE THIRD             |
| ¼      | 1       | 4       |         | VULGAR FRACTION ONE QUARTER           |
| ⅕      | 1       | 5       |         | VULGAR FRACTION ONE FIFTH             |
| ⅙      | 1       | 6       |         | VULGAR FRACTION ONE SIXTH             |
| ⅛      | 1       | 8       |         | VULGAR FRACTION ONE EIGHTH            |
| ⅔      | 2       | 3       |         | VULGAR FRACTION TWO THIRDS            |
| ⅖      | 2       | 5       |         | VULGAR FRACTION TWO FIFTHS            |
| ∬      | 2       | m       | i       | DOUBLE INTEGRAL                       |
| ¾      | 3       | 4       |         | VULGAR FRACTION THREE QUARTERS        |
| ⅗      | 3       | 5       |         | VULGAR FRACTION THREE FIFTHS          |
| ⅜      | 3       | 8       |         | VULGAR FRACTION THREE EIGHTHS         |
| ∭      | 3       | m       | i       | TRIPLE INTEGRAL                       |
| ∛      | 3       | m       | v       | CUBE ROOT                             |
| ⅘      | 4       | 5       |         | VULGAR FRACTION FOUR FIFTHS           |
| ⨌      | 4       | m       | i       | QUADRUPLE INTEGRAL OPERATOR           |
| ∜      | 4       | m       | v       | FOURTH ROOT                           |
| ⅚      | 5       | 6       |         | VULGAR FRACTION FIVE SIXTHS           |
| ⅝      | 5       | 8       |         | VULGAR FRACTION FIVE EIGHTHS          |
| ⅞      | 7       | 8       |         | VULGAR FRACTION SEVEN EIGHTHS         |
| ∞      | 8       | 8       |         | INFINITY                              |
| ∝      | 8       | c       |         | PROPORTIONAL TO                       |
| ☹      | :       | (       |         | WHITE FROWNING FACE                   |
| ☺      | :       | )       |         | WHITE SMILING FACE                    |
| ÷      | :       | -       |         | DIVISION SIGN                         |
| ∷      | :       | :       |         | PROPORTION                            |
| ⟨      | <       | (       |         | MATHEMATICAL LEFT ANGLE BRACKET       |
| «      | <       | <       |         | LEFT-POINTING DOUBLE ANGLE QUOTATION MARK |
| ≤      | <       | =       |         | LESS-THAN OR EQUAL TO                 |
| ≲      | <       | ~       |         | LESS-THAN OR EQUIVALENT TO            |
| ≠      | =       | /       |         | NOT EQUAL TO                          |
| ⇐      | =       | <       |         | LEFTWARDS DOUBLE ARROW                |
| ⇒      | =       | >       |         | RIGHTWARDS DOUBLE ARROW               |
| €      | =       | C       |         | EURO SIGN                             |
| €      | =       | E       |         | EURO SIGN                             |
| ₤      | =       | L       |         | LIRA SIGN                             |
| ₦      | =       | N       |         | NAIRA SIGN                            |
| ₩      | =       | W       |         | WON SIGN                              |
| ¥      | =       | Y       |         | YEN SIGN                              |
| €      | =       | c       |         | EURO SIGN                             |
| ₩      | =       | w       |         | WON SIGN                              |
| ¥      | =       | y       |         | YEN SIGN                              |
| ⟩      | >       | )       |         | MATHEMATICAL RIGHT ANGLE BRACKET      |
| ≥      | >       | =       |         | GREATER-THAN OR EQUAL TO              |
| »      | >       | >       |         | RIGHT-POINTING DOUBLE ANGLE QUOTATION MARK |
| ≳      | >       | ~       |         | GREATER-THAN OR EQUIVALENT TO         |
| ‽      | ?       | !       |         | INTERROBANG                           |
| ¿      | ?       | ?       |         | INVERTED QUESTION MARK                |
| Æ      | A       | E       |         | LATIN CAPITAL LETTER AE               |
| €      | C       | +       |         | EURO SIGN                             |
| ∈      | C       | -       | (space) | ELEMENT OF                            |
| ∉      | C       | -       | /       | NOT AN ELEMENT OF                     |
| ₡      | C       | /       |         | COLON SIGN                            |
| ₠      | C       | E       |         | EURO-CURRENCY SIGN                    |
| ₢      | C       | r       |         | CRUZEIRO SIGN                         |
| Ð      | D       | H       |         | LATIN CAPITAL LETTER ETH              |
| €      | E       | +       |         | EURO SIGN                             |
| ₣      | F       | r       |         | FRENCH FRANC SIGN                     |
| Ĳ      | I       | J       |         | LATIN CAPITAL LIGATURE IJ             |
| £      | L       | -       |         | POUND SIGN                            |
| ₤      | L       | =       |         | LIRA SIGN                             |
| ☽      | M       | L       |         | FIRST QUARTER MOON                    |
| ☉      | M       | S       |         | SUN                                   |
| ⊕      | M       | T       |         | CIRCLED PLUS                          |
| ∩      | M       | n       |         | INTERSECTION                          |
| ∪      | M       | u       |         | UNION                                 |
| ₦      | N       | -       |         | NAIRA SIGN                            |
| ₦      | N       | =       |         | NAIRA SIGN                            |
| Ŋ      | N       | G       |         | LATIN CAPITAL LETTER ENG              |
| №      | N       | O       |         | NUMERO SIGN                           |
| №      | N       | o       |         | NUMERO SIGN                           |
| ⊕      | O       | +       |         | CIRCLED PLUS                          |
| ❿      | O       | -       |         | DINGBAT NEGATIVE CIRCLED NUMBER TEN   |
| ⊙      | O       | .       |         | CIRCLED DOT OPERATOR                  |
| ⊘      | O       | /       |         | CIRCLED DIVISION SLASH                |
| ❶      | O       | 1       |         | DINGBAT NEGATIVE CIRCLED DIGIT ONE    |
| ❷      | O       | 2       |         | DINGBAT NEGATIVE CIRCLED DIGIT TWO    |
| ❸      | O       | 3       |         | DINGBAT NEGATIVE CIRCLED DIGIT THREE  |
| ❹      | O       | 4       |         | DINGBAT NEGATIVE CIRCLED DIGIT FOUR   |
| ❺      | O       | 5       |         | DINGBAT NEGATIVE CIRCLED DIGIT FIVE   |
| ❻      | O       | 6       |         | DINGBAT NEGATIVE CIRCLED DIGIT SIX    |
| ❼      | O       | 7       |         | DINGBAT NEGATIVE CIRCLED DIGIT SEVEN  |
| ❽      | O       | 8       |         | DINGBAT NEGATIVE CIRCLED DIGIT EIGHT  |
| ❾      | O       | 9       |         | DINGBAT NEGATIVE CIRCLED DIGIT NINE   |
| ©      | O       | C       |         | COPYRIGHT SIGN                        |
| Œ      | O       | E       |         | LATIN CAPITAL LIGATURE OE             |
| ℗      | O       | P       |         | SOUND RECORDING COPYRIGHT             |
| ®      | O       | R       |         | REGISTERED SIGN                       |
| ⊗      | O       | X       |         | CIRCLED TIMES                         |
| ©      | O       | c       |         | COPYRIGHT SIGN                        |
| ℗      | O       | p       |         | SOUND RECORDING COPYRIGHT             |
| ®      | O       | r       |         | REGISTERED SIGN                       |
| ⊗      | O       | x       |         | CIRCLED TIMES                         |
| ¶      | P       | !       |         | PILCROW SIGN                          |
| ℗      | P       | O       |         | SOUND RECORDING COPYRIGHT             |
| ¶      | P       | P       |         | PILCROW SIGN                          |
| ℗      | P       | o       |         | SOUND RECORDING COPYRIGHT             |
| ₧      | P       | t       |         | PESETA SIGN                           |
| ₨      | R       | s       |         | RUPEE SIGN                            |
| ẞ      | S       | S       |         | LATIN CAPITAL LETTER SHARP S          |
| ™      | T       | M       |         | TRADE MARK SIGN                       |
| ↓      | V       | \|      |         | DOWNWARDS ARROW                       |
| ₩      | W       | +       |         | WON SIGN                              |
| ¥      | Y       | =       |         | YEN SIGN                              |
| ∨      | \\      | /       |         | LOGICAL OR                            |
| ∖      | \\      | \\      |         | SET MINUS                             |
| ⁽      | ^       | (       |         | SUPERSCRIPT LEFT PARENTHESIS          |
| ⁾      | ^       | )       |         | SUPERSCRIPT RIGHT PARENTHESIS         |
| ⁺      | ^       | +       |         | SUPERSCRIPT PLUS SIGN                 |
| ⁰      | ^       | 0       |         | SUPERSCRIPT ZERO                      |
| ¹      | ^       | 1       |         | SUPERSCRIPT ONE                       |
| ²      | ^       | 2       |         | SUPERSCRIPT TWO                       |
| ³      | ^       | 3       |         | SUPERSCRIPT THREE                     |
| ⁴      | ^       | 4       |         | SUPERSCRIPT FOUR                      |
| ⁵      | ^       | 5       |         | SUPERSCRIPT FIVE                      |
| ⁶      | ^       | 6       |         | SUPERSCRIPT SIX                       |
| ⁷      | ^       | 7       |         | SUPERSCRIPT SEVEN                     |
| ⁸      | ^       | 8       |         | SUPERSCRIPT EIGHT                     |
| ⁹      | ^       | 9       |         | SUPERSCRIPT NINE                      |
| ⁼      | ^       | =       |         | SUPERSCRIPT EQUALS SIGN               |
| Â      | ^       | A       |         | LATIN CAPITAL LETTER A WITH CIRCUMFLEX |
| Ĉ      | ^       | C       |         | LATIN CAPITAL LETTER C WITH CIRCUMFLEX |
| Ê      | ^       | E       |         | LATIN CAPITAL LETTER E WITH CIRCUMFLEX |
| Ĥ      | ^       | H       |         | LATIN CAPITAL LETTER H WITH CIRCUMFLEX |
| Î      | ^       | I       |         | LATIN CAPITAL LETTER I WITH CIRCUMFLEX |
| Ĵ      | ^       | J       |         | LATIN CAPITAL LETTER J WITH CIRCUMFLEX |
| ℠      | ^       | M       |         | SERVICE MARK                          |
| Ô      | ^       | O       |         | LATIN CAPITAL LETTER O WITH CIRCUMFLEX |
| Ŝ      | ^       | S       |         | LATIN CAPITAL LETTER S WITH CIRCUMFLEX |
| ™      | ^       | T       |         | TRADE MARK SIGN                       |
| Û      | ^       | U       |         | LATIN CAPITAL LETTER U WITH CIRCUMFLEX |
| Ŵ      | ^       | W       |         | LATIN CAPITAL LETTER W WITH CIRCUMFLEX |
| Ŷ      | ^       | Y       |         | LATIN CAPITAL LETTER Y WITH CIRCUMFLEX |
| ␠      | ^       | ^       | (space) | SYMBOL FOR SPACE                      |
| ␟      | ^       | ^       | -       | SYMBOL FOR UNIT SEPARATOR             |
| ␡      | ^       | ^       | /       | SYMBOL FOR DELETE                     |
| ␀      | ^       | ^       | 0       | SYMBOL FOR NULL                       |
| ␡      | ^       | ^       | ?       | SYMBOL FOR DELETE                     |
| ␀      | ^       | ^       | @       | SYMBOL FOR NULL                       |
| ␛      | ^       | ^       | \[      | SYMBOL FOR ESCAPE                     |
| ␜      | ^       | ^       | \\      | SYMBOL FOR FILE SEPARATOR             |
| ␝      | ^       | ^       | \]      | SYMBOL FOR GROUP SEPARATOR            |
| ␞      | ^       | ^       | ^       | SYMBOL FOR RECORD SEPARATOR           |
| ␟      | ^       | ^       | _       | SYMBOL FOR UNIT SEPARATOR             |
| ␁      | ^       | ^       | a       | SYMBOL FOR START OF HEADING           |
| ␂      | ^       | ^       | b       | SYMBOL FOR START OF TEXT              |
| ␃      | ^       | ^       | c       | SYMBOL FOR END OF TEXT                |
| ␄      | ^       | ^       | d       | SYMBOL FOR END OF TRANSMISSION        |
| ␅      | ^       | ^       | e       | SYMBOL FOR ENQUIRY                    |
| ␆      | ^       | ^       | f       | SYMBOL FOR ACKNOWLEDGE                |
| ␇      | ^       | ^       | g       | SYMBOL FOR BELL                       |
| ␈      | ^       | ^       | h       | SYMBOL FOR BACKSPACE                  |
| ␉      | ^       | ^       | i       | SYMBOL FOR HORIZONTAL TABULATION      |
| ␊      | ^       | ^       | j       | SYMBOL FOR LINE FEED                  |
| ␋      | ^       | ^       | k       | SYMBOL FOR VERTICAL TABULATION        |
| ␌      | ^       | ^       | l       | SYMBOL FOR FORM FEED                  |
| ␍      | ^       | ^       | m       | SYMBOL FOR CARRIAGE RETURN            |
| ␎      | ^       | ^       | n       | SYMBOL FOR SHIFT OUT                  |
| ␏      | ^       | ^       | o       | SYMBOL FOR SHIFT IN                   |
| ␐      | ^       | ^       | p       | SYMBOL FOR DATA LINK ESCAPE           |
| ␑      | ^       | ^       | q       | SYMBOL FOR DEVICE CONTROL ONE         |
| ␒      | ^       | ^       | r       | SYMBOL FOR DEVICE CONTROL TWO         |
| ␓      | ^       | ^       | s       | SYMBOL FOR DEVICE CONTROL THREE       |
| ␔      | ^       | ^       | t       | SYMBOL FOR DEVICE CONTROL FOUR        |
| ␕      | ^       | ^       | u       | SYMBOL FOR NEGATIVE ACKNOWLEDGE       |
| ␖      | ^       | ^       | v       | SYMBOL FOR SYNCHRONOUS IDLE           |
| ␗      | ^       | ^       | w       | SYMBOL FOR END OF TRANSMISSION BLOCK  |
| ␘      | ^       | ^       | x       | SYMBOL FOR CANCEL                     |
| ␙      | ^       | ^       | y       | SYMBOL FOR END OF MEDIUM              |
| ␚      | ^       | ^       | z       | SYMBOL FOR SUBSTITUTE                 |
| ª      | ^       | _       | A       | FEMININE ORDINAL INDICATOR            |
| ⁱ      | ^       | _       | I       | SUPERSCRIPT LATIN SMALL LETTER I      |
| ⁿ      | ^       | _       | N       | SUPERSCRIPT LATIN SMALL LETTER N      |
| º      | ^       | _       | O       | MASCULINE ORDINAL INDICATOR           |
| â      | ^       | a       |         | LATIN SMALL LETTER A WITH CIRCUMFLEX  |
| ĉ      | ^       | c       |         | LATIN SMALL LETTER C WITH CIRCUMFLEX  |
| ê      | ^       | e       |         | LATIN SMALL LETTER E WITH CIRCUMFLEX  |
| ĥ      | ^       | h       |         | LATIN SMALL LETTER H WITH CIRCUMFLEX  |
| î      | ^       | i       |         | LATIN SMALL LETTER I WITH CIRCUMFLEX  |
| ĵ      | ^       | j       |         | LATIN SMALL LETTER J WITH CIRCUMFLEX  |
| ô      | ^       | o       |         | LATIN SMALL LETTER O WITH CIRCUMFLEX  |
| ŝ      | ^       | s       |         | LATIN SMALL LETTER S WITH CIRCUMFLEX  |
| û      | ^       | u       |         | LATIN SMALL LETTER U WITH CIRCUMFLEX  |
| ŵ      | ^       | w       |         | LATIN SMALL LETTER W WITH CIRCUMFLEX  |
| ŷ      | ^       | y       |         | LATIN SMALL LETTER Y WITH CIRCUMFLEX  |
| ↑      | ^       | \|      |         | UPWARDS ARROW                         |
| ₍      | _       | (       |         | SUBSCRIPT LEFT PARENTHESIS            |
| ₎      | _       | )       |         | SUBSCRIPT RIGHT PARENTHESIS           |
| ₊      | _       | +       |         | SUBSCRIPT PLUS SIGN                   |
| ₀      | _       | 0       |         | SUBSCRIPT ZERO                        |
| ₁      | _       | 1       |         | SUBSCRIPT ONE                         |
| ₂      | _       | 2       |         | SUBSCRIPT TWO                         |
| ₃      | _       | 3       |         | SUBSCRIPT THREE                       |
| ₄      | _       | 4       |         | SUBSCRIPT FOUR                        |
| ₅      | _       | 5       |         | SUBSCRIPT FIVE                        |
| ₆      | _       | 6       |         | SUBSCRIPT SIX                         |
| ₇      | _       | 7       |         | SUBSCRIPT SEVEN                       |
| ₈      | _       | 8       |         | SUBSCRIPT EIGHT                       |
| ₉      | _       | 9       |         | SUBSCRIPT NINE                        |
| ₌      | _       | =       |         | SUBSCRIPT EQUALS SIGN                 |
| Ā      | _       | A       |         | LATIN CAPITAL LETTER A WITH MACRON    |
| Ē      | _       | E       |         | LATIN CAPITAL LETTER E WITH MACRON    |
| Ḡ      | _       | G       |         | LATIN CAPITAL LETTER G WITH MACRON    |
| Ī      | _       | I       |         | LATIN CAPITAL LETTER I WITH MACRON    |
| Ō      | _       | O       |         | LATIN CAPITAL LETTER O WITH MACRON    |
| Ū      | _       | U       |         | LATIN CAPITAL LETTER U WITH MACRON    |
| ā      | _       | a       |         | LATIN SMALL LETTER A WITH MACRON      |
| ē      | _       | e       |         | LATIN SMALL LETTER E WITH MACRON      |
| ḡ      | _       | g       |         | LATIN SMALL LETTER G WITH MACRON      |
| ī      | _       | i       |         | LATIN SMALL LETTER I WITH MACRON      |
| ō      | _       | o       |         | LATIN SMALL LETTER O WITH MACRON      |
| ū      | _       | u       |         | LATIN SMALL LETTER U WITH MACRON      |
| À      | \`      | A       |         | LATIN CAPITAL LETTER A WITH GRAVE     |
| È      | \`      | E       |         | LATIN CAPITAL LETTER E WITH GRAVE     |
| Ì      | \`      | I       |         | LATIN CAPITAL LETTER I WITH GRAVE     |
| Ò      | \`      | O       |         | LATIN CAPITAL LETTER O WITH GRAVE     |
| Ù      | \`      | U       |         | LATIN CAPITAL LETTER U WITH GRAVE     |
| à      | \`      | a       |         | LATIN SMALL LETTER A WITH GRAVE       |
| è      | \`      | e       |         | LATIN SMALL LETTER E WITH GRAVE       |
| ì      | \`      | i       |         | LATIN SMALL LETTER I WITH GRAVE       |
| ò      | \`      | o       |         | LATIN SMALL LETTER O WITH GRAVE       |
| ù      | \`      | u       |         | LATIN SMALL LETTER U WITH GRAVE       |
| æ      | a       | e       |         | LATIN SMALL LETTER AE                 |
| ∈      | c       | -       | (space) | ELEMENT OF                            |
| ∉      | c       | -       | /       | NOT AN ELEMENT OF                     |
| ¢      | c       | /       |         | CENT SIGN                             |
| €      | c       | =       |         | EURO SIGN                             |
| Ǎ      | c       | A       |         | LATIN CAPITAL LETTER A WITH CARON     |
| Č      | c       | C       |         | LATIN CAPITAL LETTER C WITH CARON     |
| Ď      | c       | D       |         | LATIN CAPITAL LETTER D WITH CARON     |
| Ě      | c       | E       |         | LATIN CAPITAL LETTER E WITH CARON     |
| Ǧ      | c       | G       |         | LATIN CAPITAL LETTER G WITH CARON     |
| Ȟ      | c       | H       |         | LATIN CAPITAL LETTER H WITH CARON     |
| Ǐ      | c       | I       |         | LATIN CAPITAL LETTER I WITH CARON     |
| Ǩ      | c       | K       |         | LATIN CAPITAL LETTER K WITH CARON     |
| Ǒ      | c       | O       |         | LATIN CAPITAL LETTER O WITH CARON     |
| Š      | c       | S       |         | LATIN CAPITAL LETTER S WITH CARON     |
| Ť      | c       | T       |         | LATIN CAPITAL LETTER T WITH CARON     |
| Ǔ      | c       | U       |         | LATIN CAPITAL LETTER U WITH CARON     |
| Ž      | c       | Z       |         | LATIN CAPITAL LETTER Z WITH CARON     |
| ǎ      | c       | a       |         | LATIN SMALL LETTER A WITH CARON       |
| č      | c       | c       |         | LATIN SMALL LETTER C WITH CARON       |
| ď      | c       | d       |         | LATIN SMALL LETTER D WITH CARON       |
| ě      | c       | e       |         | LATIN SMALL LETTER E WITH CARON       |
| ǧ      | c       | g       |         | LATIN SMALL LETTER G WITH CARON       |
| ȟ      | c       | h       |         | LATIN SMALL LETTER H WITH CARON       |
| ǐ      | c       | i       |         | LATIN SMALL LETTER I WITH CARON       |
| ǰ      | c       | j       |         | LATIN SMALL LETTER J WITH CARON       |
| ǩ      | c       | k       |         | LATIN SMALL LETTER K WITH CARON       |
| ǒ      | c       | o       |         | LATIN SMALL LETTER O WITH CARON       |
| š      | c       | s       |         | LATIN SMALL LETTER S WITH CARON       |
| ť      | c       | t       |         | LATIN SMALL LETTER T WITH CARON       |
| ǔ      | c       | u       |         | LATIN SMALL LETTER U WITH CARON       |
| ž      | c       | z       |         | LATIN SMALL LETTER Z WITH CARON       |
| ¢      | c       | \|      |         | CENT SIGN                             |
| !      | f       | !       |         | EXCLAMATION MARK                      |
| ʺ      | f       | &quot;  |         | MODIFIER LETTER DOUBLE PRIME          |
| Ɛ      | f       | #       |         | LATIN CAPITAL LETTER OPEN E           |
| 4      | f       | \$      |         | DIGIT FOUR                            |
| Ƽ      | f       | %       |         | LATIN CAPITAL LETTER TONE FIVE        |
| &      | f       | &       |         | AMPERSAND                             |
| ʹ      | f       | '       |         | MODIFIER LETTER PRIME                 |
| (      | f       | (       |         | LEFT PARENTHESIS                      |
| )      | f       | )       |         | RIGHT PARENTHESIS                     |
| Ȣ      | f       | *       |         | LATIN CAPITAL LETTER OU               |
| =      | f       | +       |         | EQUALS SIGN                           |
| ,      | f       | ,       |         | COMMA                                 |
| -      | f       | -       |         | HYPHEN-MINUS                          |
| .      | f       | .       |         | FULL STOP                             |
| /      | f       | /       |         | SOLIDUS                               |
| 0      | f       | 0       |         | DIGIT ZERO                            |
| 1      | f       | 1       |         | DIGIT ONE                             |
| ƨ      | f       | 2       |         | LATIN SMALL LETTER TONE TWO           |
| ɛ      | f       | 3       |         | LATIN SMALL LETTER OPEN E             |
| 4      | f       | 4       |         | DIGIT FOUR                            |
| ƽ      | f       | 5       |         | LATIN SMALL LETTER TONE FIVE          |
| ƅ      | f       | 6       |         | LATIN SMALL LETTER TONE SIX           |
| ⁊      | f       | 7       |         | TIRONIAN SIGN ET                      |
| ȣ      | f       | 8       |         | LATIN SMALL LETTER OU                 |
| 9      | f       | 9       |         | DIGIT NINE                            |
| :      | f       | :       |         | COLON                                 |
| ;      | f       | ;       |         | SEMICOLON                             |
| ,      | f       | <       |         | COMMA                                 |
| =      | f       | =       |         | EQUALS SIGN                           |
| .      | f       | >       |         | FULL STOP                             |
| /      | f       | ?       |         | SOLIDUS                               |
| Ƨ      | f       | @       |         | LATIN CAPITAL LETTER TONE TWO         |
| Ə      | f       | A       |         | LATIN CAPITAL LETTER SCHWA            |
| B      | f       | B       |         | LATIN CAPITAL LETTER B                |
| Ɔ      | f       | C       |         | LATIN CAPITAL LETTER OPEN O           |
| D      | f       | D       |         | LATIN CAPITAL LETTER D                |
| Ǝ      | f       | E       |         | LATIN CAPITAL LETTER REVERSED E       |
| F      | f       | F       |         | LATIN CAPITAL LETTER F                |
| Ɣ      | f       | G       |         | LATIN CAPITAL LETTER GAMMA            |
| Ƕ      | f       | H       |         | LATIN CAPITAL LETTER HWAIR            |
| I      | f       | I       |         | LATIN CAPITAL LETTER I                |
| Ƞ      | f       | J       |         | LATIN CAPITAL LETTER N WITH LONG RIGHT LEG |
| K’     | f       | K       |         |                                       |
| L      | f       | L       |         | LATIN CAPITAL LETTER L                |
| Ɯ      | f       | M       |         | LATIN CAPITAL LETTER TURNED M         |
| Ŋ      | f       | N       |         | LATIN CAPITAL LETTER ENG              |
| O      | f       | O       |         | LATIN CAPITAL LETTER O                |
| P      | f       | P       |         | LATIN CAPITAL LETTER P                |
| Ƣ      | f       | Q       |         | LATIN CAPITAL LETTER OI               |
| Ʀ      | f       | R       |         | LATIN LETTER YR                       |
| S      | f       | S       |         | LATIN CAPITAL LETTER S                |
| T      | f       | T       |         | LATIN CAPITAL LETTER T                |
| Ʊ      | f       | U       |         | LATIN CAPITAL LETTER UPSILON          |
| V      | f       | V       |         | LATIN CAPITAL LETTER V                |
| Ƿ      | f       | W       |         | LATIN CAPITAL LETTER WYNN             |
| X      | f       | X       |         | LATIN CAPITAL LETTER X                |
| Ȝ      | f       | Y       |         | LATIN CAPITAL LETTER YOGH             |
| Ʒ      | f       | Z       |         | LATIN CAPITAL LETTER EZH              |
| \[     | f       | \[      |         | LEFT SQUARE BRACKET                   |
| \\     | f       | \\      |         | REVERSE SOLIDUS                       |
| \]     | f       | \]      |         | RIGHT SQUARE BRACKET                  |
| Ƅ      | f       | ^       |         | LATIN CAPITAL LETTER TONE SIX         |
| -      | f       | _       |         | HYPHEN-MINUS                          |
| §      | f       | \`      |         | SECTION SIGN                          |
| ±      | f       | \`      |         | PLUS-MINUS SIGN                       |
| ə      | f       | a       |         | LATIN SMALL LETTER SCHWA              |
| b      | f       | b       |         | LATIN SMALL LETTER B                  |
| ɔ      | f       | c       |         | LATIN SMALL LETTER OPEN O             |
| d      | f       | d       |         | LATIN SMALL LETTER D                  |
| ǝ      | f       | e       |         | LATIN SMALL LETTER TURNED E           |
| f      | f       | f       |         | LATIN SMALL LETTER F                  |
| ɣ      | f       | g       |         | LATIN SMALL LETTER GAMMA              |
| ƕ      | f       | h       |         | LATIN SMALL LETTER HV                 |
| i      | f       | i       |         | LATIN SMALL LETTER I                  |
| ƞ      | f       | j       |         | LATIN SMALL LETTER N WITH LONG RIGHT LEG |
| ĸ      | f       | k       |         | LATIN SMALL LETTER KRA                |
| l      | f       | l       |         | LATIN SMALL LETTER L                  |
| ɯ      | f       | m       |         | LATIN SMALL LETTER TURNED M           |
| ŋ      | f       | n       |         | LATIN SMALL LETTER ENG                |
| o      | f       | o       |         | LATIN SMALL LETTER O                  |
| p      | f       | p       |         | LATIN SMALL LETTER P                  |
| ƣ      | f       | q       |         | LATIN SMALL LETTER OI                 |
| ʀ      | f       | r       |         | LATIN LETTER SMALL CAPITAL R          |
| ſ      | f       | s       |         | LATIN SMALL LETTER LONG S             |
| t      | f       | t       |         | LATIN SMALL LETTER T                  |
| ʊ      | f       | u       |         | LATIN SMALL LETTER UPSILON            |
| ʌ      | f       | v       |         | LATIN SMALL LETTER TURNED V           |
| ƿ      | f       | w       |         | LATIN LETTER WYNN                     |
| x      | f       | x       |         | LATIN SMALL LETTER X                  |
| ȝ      | f       | y       |         | LATIN SMALL LETTER YOGH               |
| ʒ      | f       | z       |         | LATIN SMALL LETTER EZH                |
| \[     | f       | {       |         | LEFT SQUARE BRACKET                   |
| \|     | f       | \|      |         | VERTICAL LINE                         |
| \]     | f       | }       |         | RIGHT SQUARE BRACKET                  |
| ±      | f       | ~       |         | PLUS-MINUS SIGN                       |
| Α      | g       | A       |         | GREEK CAPITAL LETTER ALPHA            |
| Β      | g       | B       |         | GREEK CAPITAL LETTER BETA             |
| Ψ      | g       | C       |         | GREEK CAPITAL LETTER PSI              |
| Δ      | g       | D       |         | GREEK CAPITAL LETTER DELTA            |
| Ε      | g       | E       |         | GREEK CAPITAL LETTER EPSILON          |
| Φ      | g       | F       |         | GREEK CAPITAL LETTER PHI              |
| Γ      | g       | G       |         | GREEK CAPITAL LETTER GAMMA            |
| Η      | g       | H       |         | GREEK CAPITAL LETTER ETA              |
| Ι      | g       | I       |         | GREEK CAPITAL LETTER IOTA             |
| Ξ      | g       | J       |         | GREEK CAPITAL LETTER XI               |
| Κ      | g       | K       |         | GREEK CAPITAL LETTER KAPPA            |
| Λ      | g       | L       |         | GREEK CAPITAL LETTER LAMDA            |
| Μ      | g       | M       |         | GREEK CAPITAL LETTER MU               |
| Ν      | g       | N       |         | GREEK CAPITAL LETTER NU               |
| Ο      | g       | O       |         | GREEK CAPITAL LETTER OMICRON          |
| Π      | g       | P       |         | GREEK CAPITAL LETTER PI               |
| :      | g       | Q       |         | COLON                                 |
| Ρ      | g       | R       |         | GREEK CAPITAL LETTER RHO              |
| Σ      | g       | S       |         | GREEK CAPITAL LETTER SIGMA            |
| Τ      | g       | T       |         | GREEK CAPITAL LETTER TAU              |
| Θ      | g       | U       |         | GREEK CAPITAL LETTER THETA            |
| Ω      | g       | V       |         | GREEK CAPITAL LETTER OMEGA            |
| Χ      | g       | X       |         | GREEK CAPITAL LETTER CHI              |
| Υ      | g       | Y       |         | GREEK CAPITAL LETTER UPSILON          |
| Ζ      | g       | Z       |         | GREEK CAPITAL LETTER ZETA             |
| α      | g       | a       |         | GREEK SMALL LETTER ALPHA              |
| β      | g       | b       |         | GREEK SMALL LETTER BETA               |
| ψ      | g       | c       |         | GREEK SMALL LETTER PSI                |
| δ      | g       | d       |         | GREEK SMALL LETTER DELTA              |
| ε      | g       | e       |         | GREEK SMALL LETTER EPSILON            |
| φ      | g       | f       |         | GREEK SMALL LETTER PHI                |
| γ      | g       | g       |         | GREEK SMALL LETTER GAMMA              |
| η      | g       | h       |         | GREEK SMALL LETTER ETA                |
| ι      | g       | i       |         | GREEK SMALL LETTER IOTA               |
| ξ      | g       | j       |         | GREEK SMALL LETTER XI                 |
| κ      | g       | k       |         | GREEK SMALL LETTER KAPPA              |
| λ      | g       | l       |         | GREEK SMALL LETTER LAMDA              |
| μ      | g       | m       |         | GREEK SMALL LETTER MU                 |
| ν      | g       | n       |         | GREEK SMALL LETTER NU                 |
| ο      | g       | o       |         | GREEK SMALL LETTER OMICRON            |
| π      | g       | p       |         | GREEK SMALL LETTER PI                 |
| ;      | g       | q       |         | SEMICOLON                             |
| ρ      | g       | r       |         | GREEK SMALL LETTER RHO                |
| σ      | g       | s       |         | GREEK SMALL LETTER SIGMA              |
| τ      | g       | t       |         | GREEK SMALL LETTER TAU                |
| θ      | g       | u       |         | GREEK SMALL LETTER THETA              |
| ω      | g       | v       |         | GREEK SMALL LETTER OMEGA              |
| ς      | g       | w       |         | GREEK SMALL LETTER FINAL SIGMA        |
| χ      | g       | x       |         | GREEK SMALL LETTER CHI                |
| υ      | g       | y       |         | GREEK SMALL LETTER UPSILON            |
| ζ      | g       | z       |         | GREEK SMALL LETTER ZETA               |
| ĳ      | i       | j       |         | LATIN SMALL LIGATURE IJ               |
|       | k       | a       |         | *APPLE LOGO*                          |
| ←      | k       | b       | s       | LEFTWARDS ARROW                       |
| ⇪      | k       | c       | l       | UPWARDS WHITE ARROW FROM BAR          |
| ⌘      | k       | c       | m       | PLACE OF INTEREST SIGN                |
| ⎄      | k       | c       | o       | COMPOSITION SYMBOL                    |
| ⌃      | k       | c       | t       | UP ARROWHEAD                          |
| ⏏      | k       | e       | j       | EJECT SYMBOL                          |
| ⏎      | k       | e       | n       | RETURN SYMBOL                         |
| ⎋      | k       | e       | s       | BROKEN CIRCLE WITH NORTHWEST ARROW    |
| ⌥      | k       | o       | p       | OPTION KEY                            |
| ⇧      | k       | s       | h       | UPWARDS WHITE ARROW                   |
| ⬖      | k       | s       | y       | DIAMOND WITH LEFT HALF BLACK          |
| ⇥      | k       | t       | a       | RIGHTWARDS ARROW TO BAR               |
| ✓      | k       | v       |         | CHECK MARK                            |
| ✗      | k       | x       |         | BALLOT X                              |
| ∀      | m       | A       |         | FOR ALL                               |
| ∃      | m       | E       |         | THERE EXISTS                          |
| ℏ      | m       | H       |         | PLANCK CONSTANT OVER TWO PI           |
| ∏      | m       | P       |         | N-ARY PRODUCT                         |
| ∑      | m       | S       |         | N-ARY SUMMATION                       |
| ℵ      | m       | a       |         | ALEF SYMBOL                           |
| ∂      | m       | d       |         | PARTIAL DIFFERENTIAL                  |
| ℎ      | m       | h       |         | PLANCK CONSTANT                       |
| ∫      | m       | i       |         | INTEGRAL                              |
| µ      | m       | u       |         | MICRO SIGN                            |
| √      | m       | v       |         | SQUARE ROOT                           |
| ŋ      | n       | g       |         | LATIN SMALL LETTER ENG                |
| №      | n       | o       |         | NUMERO SIGN                           |
| ⊕      | o       | +       |         | CIRCLED PLUS                          |
| ⑩      | o       | -       |         | CIRCLED NUMBER TEN                    |
| •      | o       | .       |         | BULLET                                |
| ⓪      | o       | 0       |         | CIRCLED DIGIT ZERO                    |
| ①      | o       | 1       |         | CIRCLED DIGIT ONE                     |
| ②      | o       | 2       |         | CIRCLED DIGIT TWO                     |
| ③      | o       | 3       |         | CIRCLED DIGIT THREE                   |
| ④      | o       | 4       |         | CIRCLED DIGIT FOUR                    |
| ⑤      | o       | 5       |         | CIRCLED DIGIT FIVE                    |
| ⑥      | o       | 6       |         | CIRCLED DIGIT SIX                     |
| ⑦      | o       | 7       |         | CIRCLED DIGIT SEVEN                   |
| ⑧      | o       | 8       |         | CIRCLED DIGIT EIGHT                   |
| ⑨      | o       | 9       |         | CIRCLED DIGIT NINE                    |
| Å      | o       | A       |         | LATIN CAPITAL LETTER A WITH RING ABOVE |
| ©      | o       | C       |         | COPYRIGHT SIGN                        |
| ℗      | o       | P       |         | SOUND RECORDING COPYRIGHT             |
| ®      | o       | R       |         | REGISTERED SIGN                       |
| Ů      | o       | U       |         | LATIN CAPITAL LETTER U WITH RING ABOVE |
| å      | o       | a       |         | LATIN SMALL LETTER A WITH RING ABOVE  |
| ©      | o       | c       |         | COPYRIGHT SIGN                        |
| œ      | o       | e       |         | LATIN SMALL LIGATURE OE               |
| °      | o       | o       |         | DEGREE SIGN                           |
| ℗      | o       | p       |         | SOUND RECORDING COPYRIGHT             |
| ®      | o       | r       |         | REGISTERED SIGN                       |
| §      | o       | s       |         | SECTION SIGN                          |
| ů      | o       | u       |         | LATIN SMALL LETTER U WITH RING ABOVE  |
| ¤      | o       | x       |         | CURRENCY SIGN                         |
| ¶      | p       | !       |         | PILCROW SIGN                          |
| ℗      | p       | O       |         | SOUND RECORDING COPYRIGHT             |
| ℗      | p       | o       |         | SOUND RECORDING COPYRIGHT             |
| §      | s       | o       |         | SECTION SIGN                          |
| ß      | s       | s       |         | LATIN SMALL LETTER SHARP S            |
| ™      | t       | m       |         | TRADE MARK SIGN                       |
| ↓      | v       | \|      |         | DOWNWARDS ARROW                       |
| ⊗      | x       | O       |         | CIRCLED TIMES                         |
| ¤      | x       | o       |         | CURRENCY SIGN                         |
| ×      | x       | x       |         | MULTIPLICATION SIGN                   |
| ¥      | y       | =       |         | YEN SIGN                              |
| ℂ      | \|      | C       |         | DOUBLE-STRUCK CAPITAL C               |
| ℍ      | \|      | H       |         | DOUBLE-STRUCK CAPITAL H               |
| ℕ      | \|      | N       |         | DOUBLE-STRUCK CAPITAL N               |
| ℙ      | \|      | P       |         | DOUBLE-STRUCK CAPITAL P               |
| ℚ      | \|      | Q       |         | DOUBLE-STRUCK CAPITAL Q               |
| ℝ      | \|      | R       |         | DOUBLE-STRUCK CAPITAL R               |
| ↓      | \|      | V       |         | DOWNWARDS ARROW                       |
| ℤ      | \|      | Z       |         | DOUBLE-STRUCK CAPITAL Z               |
| ↑      | \|      | ^       |         | UPWARDS ARROW                         |
| ¢      | \|      | c       |         | CENT SIGN                             |
| ↓      | \|      | v       |         | DOWNWARDS ARROW                       |
| ∨      | \|      | \|      |         | LOGICAL OR                            |
| Ã      | ~       | A       |         | LATIN CAPITAL LETTER A WITH TILDE     |
| Ẽ      | ~       | E       |         | LATIN CAPITAL LETTER E WITH TILDE     |
| Ĩ      | ~       | I       |         | LATIN CAPITAL LETTER I WITH TILDE     |
| Ñ      | ~       | N       |         | LATIN CAPITAL LETTER N WITH TILDE     |
| Õ      | ~       | O       |         | LATIN CAPITAL LETTER O WITH TILDE     |
| Ũ      | ~       | U       |         | LATIN CAPITAL LETTER U WITH TILDE     |
| Ỹ      | ~       | Y       |         | LATIN CAPITAL LETTER Y WITH TILDE     |
| ã      | ~       | a       |         | LATIN SMALL LETTER A WITH TILDE       |
| ẽ      | ~       | e       |         | LATIN SMALL LETTER E WITH TILDE       |
| ĩ      | ~       | i       |         | LATIN SMALL LETTER I WITH TILDE       |
| ñ      | ~       | n       |         | LATIN SMALL LETTER N WITH TILDE       |
| õ      | ~       | o       |         | LATIN SMALL LETTER O WITH TILDE       |
| ũ      | ~       | u       |         | LATIN SMALL LETTER U WITH TILDE       |
| ỹ      | ~       | y       |         | LATIN SMALL LETTER Y WITH TILDE       |
| ≈      | ~       | ~       |         | ALMOST EQUAL TO                       |
| Ő      | ⌥&quot; | O       |         | LATIN CAPITAL LETTER O WITH DOUBLE ACUTE |
| Ű      | ⌥&quot; | U       |         | LATIN CAPITAL LETTER U WITH DOUBLE ACUTE |
| ő      | ⌥&quot; | o       |         | LATIN SMALL LETTER O WITH DOUBLE ACUTE |
| ű      | ⌥&quot; | u       |         | LATIN SMALL LETTER U WITH DOUBLE ACUTE |
