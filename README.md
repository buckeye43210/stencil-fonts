# stencil-fonts

Handcrafted postscript font shapes.

~~~postscript
!%ps

/block_u {
    newpath
    0	98	moveto
    23	98	lineto %% horizontal right
    23	22	lineto %% virtical down
    50	22	lineto %% horizontal right
    50	98	lineto %% virtical up
    70	98	lineto %% horizontal right
    70	11	lineto %% virtical down
    61	0	lineto %% diagonal
    11	0	lineto %% horizontal left
    0	11	lineto %% diagonal
    closepath
    gsave
    setrgbcolor
    fill
    grestore
    1 setlinewidth
    0 setgray
    stroke
} def

/block_s {
    newpath
    0	87	moveto
    11	98	lineto %% diagonal
    56	98	lineto %% horizontal right
    68	87	lineto %% diagonal
    68	68	lineto %% virtical down
    45	68	lineto %% horizontal left
    45	80	lineto %% virtical up
    23	80	lineto %% horizontal left
    23	57	lineto %% virtical down
    56	57	lineto %% horizontal right
    68	45	lineto %% diagonal
    68	11	lineto %% virtical down
    56	0	lineto %% diagonal
    11	0	lineto %% horizontal left
    0	11	lineto %% diagonal
    0	31	lineto %% virtical up
    23	31	lineto %% horizontal right
    23	18	lineto %% virtical down
    45	18	lineto %% horizontal right
    45	41	lineto %% virtical up
    11	41	lineto %% horizontal left
    0	52	lineto %% diagonal
    closepath
    gsave
    setrgbcolor
    fill
    grestore
    1 setlinewidth
    0 setgray
    stroke
} def

/block_a {
    newpath
    0	0	moveto
    36	98	lineto  %% diagonal up
    56	98	lineto  %% horizontal right
    20  0   lineto  %% diagonal down
    closepath

    59  96  moveto
    90	0	lineto  %% diagonal down
    71	0	lineto  %% horizontal left
    60	35	lineto  %% diagonal up
    37	35	lineto  %% horizontal left
    44  55  lineto  %% diagonal up
    55  55  lineto  %% horizontal right
    50  70  lineto  %% diagonal up
    closepath
    gsave
    setrgbcolor
    fill
    grestore
    1 setlinewidth
    0 setgray
    stroke
} def

/block_f {
    0	0	moveto
    0	98	lineto  %% virtical up
    61	98	lineto  %% horizontal right
    61	76	lineto  %% virtical down
    23	76	lineto  %% horizontal left
    23	60	lineto  %% virtical down
    45	60	lineto  %% horizontal right
    45	42	lineto  %% virtical down
    23	42	lineto  %% horizontal left
    23	0	lineto  %% virtical down
    closepath
    gsave
    setrgbcolor
    fill
    grestore
    1 setlinewidth
    0 setgray
    stroke
} def

/line_h {
    newpath
    0    48    moveto
    450	 48    lineto  %% horizontal reference line
    0.5        setlinewidth
    setrgbcolor
    0.5 setlinewidth
    stroke
} def


99 600 translate
255 255 255 block_u

85 0 translate
255 255 255 block_s

75 0 translate
255 255 255 block_a

100 0 translate
255 255 255 block_f

45 0 translate
255 255 255 block_a

%% -350 0 translate
%% 255 255 255 line_h

~~~
