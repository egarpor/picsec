picsec beamer theme
===================

picsec (**pic**ture **sec**tion) is a custom beamer theme for LaTeX. It is based on the progressbar beamer theme from Sylvain Bouveret (http://recherche.noiraudes.net/fr/LaTeX.php).

New feature in version 0.4: You can use different kinds of styles for headlines, frame titles and title page. You can switch from one style to another one by using \progressbaroptions{x=...} in your .tex file, where the different values for x are the following:

*headline* - two possible values : headline=none (default), displaying an empty headline (screenshot 1), or headline=sections, displaying the section list in the headline, as in earlier versions (screenshot 3).

*frametitle* - FOUR possible values : frametitle=picture-section (default), displaying the section, a picture, and the frametitle (screenshot 1), frametitle=picture-subsection (default), displaying the section, the subsection, a picture, and the frametitle, or frametitle=normal, displaying only the centered frametitle, as in earlier versions (screenshot 3), frametitle=picture-edu, displaying only the frametitle and the figure, with an horizontal line. 

*titlepage* - two possible values : titlepage=picture (default), displaying a picture in the title page (screenshot 2), or titlepage=normal, displaying no picture, as in the earlier versions (screenshot 4).

*imagename* : you can specify the picture to be displayed in the FRAME titles (default: images/tree04).
You can specify several options at the same time. You can change the options whenever you want in the .tex file.

*titleimagename* : you can specify the picture to be displayed in the TITLE page (default: images/tree04).
You can specify several options at the same time. You can change the options whenever you want in the .tex file.
