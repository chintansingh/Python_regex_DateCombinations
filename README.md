# Python_regex_DateCombinations
Extracting, cleaning and sorting dates from messy data using Python Library Regex

Working with dates is tricky with dozens of possible date formats. This exercise uses messy annonyms medical data to extract, clean and standrdize medical data using Python libararies Regex and Pandas.


Sample raw input text:

24 yo right handed woman with history of large right frontal mass s/p resection 11/3/1985 who had recent urgent R cranial wound revision and placement of L EVD for declining vision and increased drainage from craniotomy incision site and possible infection. She has a hx of secondary mania related to psychosis and manipulation of her right frontal lobe.
7/04/82 CPT Code: 90801 - Psychiatric Diagnosis Interview
4-13-89 Communication with referring physician?: Not Done
Lithium 0.25 (7/11/77).  LFTS wnl.  Urine tox neg.  Serum tox + fluoxetine 500; otherwise neg.  TSH 3.28.  BUN/Cr: 16/0.83.  Lipids unremarkable.  B12 363, Folate >20.  CBC: 4.9/36/308 Pertinent Medical Review of Systems Constitutional:
4/12/74= 1Caffeine / Tobacco Use Caffeinated products: Yes
09/19/81 CPT Code: 90792: With medical services
9/6/79 Primary Care Doctor:
12/5/87 Total time of visit (in minutes):
01/05/1999 [report_end]
4/22/80 SOS-10 Total Score:
10/04/98 SOS-10 Total Score:
.Mr. Echeverria described having panic-like experiences on at least three occasions. The first of these episodes occurred when facial meshing was placed on him during radiation therapy. He recalled the experience vividly and described "freaking out", involving a sensation of crushing in his chest, difficulty breathing, a fear that he could die, and intense emotional disquiet. The second episode occurred during the last 10-15 minutes of an MRI scan. Mr. Echeverria noted feeling surprised and fearful when the feelings of panic started. Similar physiological and psychological symptoms were reported as above. The third episode occurred recently on 6/29/81. Mr.Echeverria was driving his car and felt similar symptoms as described above. He reported fearing that he would crash his vehicle and subsequently pulled over and abandoned his vehicle.
. Wile taking additional history, pt endorsed moderate depression and anxiety last 2 weeks, even though her period was on 8/04/78. Pt then acknowledged low to moderate mood and anxiety symptoms throughout the month, with premenstrual worsening. This mood pattern seems to have existed for many years, while premenstrual worsening increased in severity during last ~ 2 years, in context of likely peri menopause transition. Pt reported average of 3 hot flashes per day and 2 night sweats.



Sample extracted and cleaned dates:

69   1985-11-03
70   1982-07-04
71   1989-04-13
72   1977-07-11
73   1974-04-12
74   1981-09-19
75   1979-09-06
76   1987-12-05
77   1999-01-05
78   1980-04-22
79   1998-10-04
80   1981-06-29
81   1978-08-04
