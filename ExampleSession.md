# A sample output from the Arduino serial terminal during a programming session

# Example #

Detected:      PIC32MX210F016B<br>
DeviceID:      0x4A01053<br>
Row size:      128B<br>
Page size:     1024B<br>
Boot Flash:    0x1FC00000 - 0x1FC00BFF<br>
Program Flash: 0x1D000000 - 0x1D003FFF<br>

Press "H" to start!<br>
Commands<br>
<blockquote>h    - help<br>
p    - .hex program+verify mode<br>
P    - .hex programming only<br>
v    - .hex verify mode<br>
e    - erase device<br>
d    - dump memory<br>
x    - exit<br></blockquote>

<blockquote>><b>d</b><br>
DevID:<br>
BF80F220: 4A01053<br>
Boot Flash Start:<br>
1FC00000: 3C1ABFC0<br>
1FC00004: 275A0010<br>
1FC00008: 3400008<br>
1FC0000C: 0<br>
Config bits:<br>
1FC00BF0: FFFFFFFF<br>
1FC00BF4: FFFFFFFF<br>
1FC00BF8: FF7FFFF8<br>
1FC00BFC: 7FFFFFFF<br>
Program Flash Start:<br>
1D000000: FFFFFFFF<br>
1D000004: FFFFFFFF<br>
1D000008: FFFFFFFF<br>
1D00000C: FFFFFFFF<br></blockquote>

<blockquote>><b>e</b><br>
Erase<br>
Erasing: 1FC00000<br>
Erasing: 1FC00400<br>
Erasing: 1FC00800<br>
Erasing: 1D000000<br>
- Done!<br></blockquote>

<blockquote>><b>d</b><br>
DevID:<br>
BF80F220: 4A01053<br>
Boot Flash Start:<br>
1FC00000: FFFFFFFF<br>
1FC00004: FFFFFFFF<br>
1FC00008: FFFFFFFF<br>
1FC0000C: FFFFFFFF<br>
Config bits:<br>
1FC00BF0: FFFFFFFF<br>
1FC00BF4: FFFFFFFF<br>
1FC00BF8: FFFFFFFF<br>
1FC00BFC: 7FFFFFFF<br>
Program Flash Start:<br>
1D000000: FFFFFFFF<br>
1D000004: FFFFFFFF<br>
1D000008: FFFFFFFF<br>
1D00000C: FFFFFFFF<br></blockquote>

<blockquote>><b>h</b><br>
Commands<br>
<blockquote>h    - help<br>
p    - .hex program+verify mode<br>
P    - .hex programming only<br>
v    - .hex verify mode<br>
e    - erase device<br>
d    - dump memory<br>
x    - exit<br></blockquote></blockquote>

<blockquote>><b>p</b><br>
Program+verify mode<br>
Send your .hex -file now.<br></blockquote>

\<br>
Done!<br>
.<br>
<blockquote>><b>d</b><br>
DevID:<br>
BF80F220: 4A01053<br>
Boot Flash Start:<br>
1FC00000: 3C1ABFC0<br>
1FC00004: 275A0010<br>
1FC00008: 3400008<br>
1FC0000C: 0<br>
Config bits:<br>
1FC00BF0: FFFFFFFF<br>
1FC00BF4: FFFFFFFF<br>
1FC00BF8: FF7FFFF8<br>
1FC00BFC: 7FFFFFFF<br>
Program Flash Start:<br>
1D000000: FFFFFFFF<br>
1D000004: FFFFFFFF<br>
1D000008: FFFFFFFF<br>
1D00000C: FFFFFFFF<br></blockquote>

<blockquote>><b>x</b><br>
THE END!<br>