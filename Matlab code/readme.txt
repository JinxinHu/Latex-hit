It's a sty file of mcode.
Just put this file into your file path and it worked. 
you will also need to invoke some packages,for example:

\usepackage{listings}
\lstset{language=Matlab}
\usepackage[framed,numbered,autolinebreaks,useliterate]{mcode} 
\lstset{breaklines}%自动将长的代码行换行排版
\lstset{extendedchars=false}%解决代码跨页时，章节标题，页眉等汉字不显示的问题
