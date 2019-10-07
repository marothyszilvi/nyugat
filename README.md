# Nyugat
Research on the Hungarian literary journal "Nyugat" (1908-1941) with a special focus on network theory and digital humanities.

All files under CC-BY-NC-SA 4.0 international licence, feel free to use and pls tell us about it! :)
https://creativecommons.org/licenses/by-nc-sa/4.0/


Description of the files in this repository:
- MarothyMinkoParadi_slides.pdf Our (Maróthy Szilvia, Minkó Mihály, Parádi Andrea) presentation about the project.
- Original source files we worked with:
  1. nyugat.htm downloaded from: http://epa.oszk.hu/00000/00022/b1.htm
  2. napkelet.zip from the database of Arcanum Adatbázis Kft., thx for that! See online: https://adtplus.arcanum.hu/hu/collection/Napkelet/
- Cleaned data:
  1. nyugat_raw.txt Almost clean data, article titles also included.
  2. napkelet_raw.txt Almost clean data, article titles and beginning page numbers also included.
  3. nyugat_issue-author.csv Contains issue-author connections of Nyugat.
  4. napkelet_issue-author.csv Contains issue-author connections of Napkelet.
- Network visualizations (Gephi):
  - nyugat_full.png Author-journal issue connections of Nyugat.
  - nyugat_withoutonedegree Author-journal issue connections of Nyugat without one-degree nodes (=authors publishing only once).
  - nyugat_auth.png Author-author connections of Nyugat.
  - nyugat_top20btw.png Connections of TOP20 authors of Napkelet by betweenness centrality. (for more details pls chech the slides)
  - napkelet_full.png Author-journal issue connections of Napkelet.
  - napkelet_withoutonedegree Author-journal issue connections of Napkelet without one-degree nodes (=authors publishing only once).
  - napkelet_auth.png Author-author connections of Napkelet.
  - napkelet_top20btw.png Connections of TOP20 authors of Napkelet by betweenness centrality. (for more details pls check the slides)
  - nyugat-napkelet_full.png Author-journal issue connections of Nyugat and Napkelet.
  - nyugat-napkelet_auth.png Author-author connections of Nyugat and Napkelet.
  - nyugat-napkelet_top20btw.png Connections of TOP20 authors of Nyugat and Napkelet by betweenness centrality. (for more details pls chech the slides)
