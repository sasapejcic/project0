# Project 0

Web Programming with Python and JavaScript

This is small website about youth basketball team and its star player.

There are four html files corresponding to four pages listed in main menu:
index.html, u12.html, u13.html and starplayer.html.

Each of this files has three main sections: header, content and footer.
Header and footer are the same across all html files. All three sections have
'container' class to add a little space on both sides.

There is a logo in header that uses image stored in subfolder 'images' and a
navigation based on a unordered list and (hopefully) nice styling.

Navigation has responsive design with breakpoint set to 992px.

All styles with the exception of bootstrap cards and grid are placed in
css/styles.scss file.

Content of index.html uses some basic styling.

Table tag is used to display scoreboard in u13.html content. Styling is very
simple again.

The most complex content has page starplayer.html.

Player stats on this page are displayed using Bootstrap 'Card' component inside
Bootstrap 'Grid'.

Card class has custom styling with nested styling for paragraph inside of it.

'Steals' category has id attribute set to 'highlight' used to apply specific
style which is green text color in this case.

SASS inheritance is used to style head tags on this page. As a consequence
'Season Stats' and 'Day 1 stats' are displayed with slightly different shades
of blue color.

There is not much to say about footer section and u12.html.

I used atom as editor and standalone SASS compiler in a css folder to compile
SASS file to CSS.

Consquently there are styles.scss, syles.css and styles.css.map files in a css
folder.

Couple of variables has been used in style.scss file.

SASS compiler is excluded from repository using .gitignore.
