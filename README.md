# Last Letter Country Solver
We've all played the places game where someone names a place (like a country or a city) and the someone else must then name another place that starts with the last letter of the previous word. The game also known as [word chain](https://en.wikipedia.org/wiki/Word_chain), grab on behind, last and first, alpha and omega, and the name game.
 

Requirements:
import: pandas, numpy
text file with header with places separated by newlines: countries.txt


Given a list of countries and/cities and a starting value, the algorithm brute force generates a tree of every possible combination of places.

Results are then shown of the longest chain, and length of chain. 


Issues:

-when using a dataset of 196 locations(all countries) generation>4 take minutes-hours without optimizations


TODO:

-function to remove input place from data list 

-function to remove locations that start and end with the same letter, than add them to the last/longest chains


https://colab.research.google.com/drive/1_jSwWHmne74TtBIUN4sQu8jg5d1UoKx3
made in tensorflow
