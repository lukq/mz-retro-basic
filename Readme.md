Try it [online.](https://lukq.github.io/mz-retro-basic/mzbasic.htm)

A reimplementation of a BASIC language for the browser. It is an old-style BASIC
with line numbers and command-line input interface. The syntax is based on the
version of BASIC shipped with Sharp MZ-800 computers.

Supported commands:
- AUTO AND CONT CLS CLR DELETE DATA DEF DIM EDIT ELSE END FOR FN GOTO GOSUB INPUT
 IF LIST LET LOAD MOD NEXT NEW NOT ON OR POKE PRINT RUN RETURN READ REM RENUM
 RESTORE STOP STEP TAB THEN TO TRON TROFF USING XOR

Functions:
- ABS ASC ATN CHR$ COS EXP FRAC HEX$ INT LEFT$ LEN LN LOG MID$ PAI PEEK RAD
 RIGHT$ RND SGN SIN SPC SPACE$ SQR STR$ TAN VAL

Data types:
- numbers are stored in double-precision floating point format
- boolean operations process 16-bit integers
- strings have a maximum length of 255 characters

Special input:
- \bar -Graph+Q character, \div -Graph+x character, \pi -Shift+0 character
- Pause key breaks out of INPUT
