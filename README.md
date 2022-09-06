# Simos' Revised Procedure
The intuitive way to express the importance of criteria through a deck of cards playing procedure.

<br>
How to cite?

Pavel Anselmo Alvarez, Cuitláhuac Valdez, Bapi Dutta (2022). Analysis of the innovation capacity of Mexican regions with the multiple criteria hierarchy process. Socio-Economic Planning Sciences. https://doi.org/10.1016/j.seps.2022.101418

<br>
How to run?
- ./Simos_revised_share <directory_with_input_files>
- ./Simos_revised_share example_project

<br><br>
## Description of the input and output data

> The input files shoul be saved in a directory in same path that binary file "Simos_revised_share"

<br><br>
### Input 


> criteria_order.txt  | importance order of the criteria

O_1	:posAlternative g_1

O_2	:posAlternative g_2

...	

0_m	:posAlternative g_m


<br>

> problem.txt

3	:number of criteria

6.5	:z value, how many times the last criterion is more important than the first one in the ranking

1	:[0,1,2] w value, is the precision of the output weight value (number of positions after decimal point)

<br>

> white_cards.txt | number of white cards (wc) between groups of criteria

a group can contains one or more cards

the total of withe card will be number of groups (G) less one; total_wc = G-1

wc_1	:number of wc between group1 and group2

wc_2	:number of wc between group2 and group3

...	...

wc_G-1	:number of wc between group_G-1 and group_G

<br><br>

### Output 
Importance weight of criteria

Weights <br>
2.370000 <br>
2.370000 <br>
2.370000 <br>
4.540000 <br>
8.880000 <br>
8.880000 <br>
8.880000 <br>
8.880000 <br>
11.050000 <br>
13.200000 <br>
13.200000 <br>
15.380000 <br>
Sum weights: 100

