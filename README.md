  <div>
    <h2>Shark Attacks - Week 2 Quest</h2>
    <p>by Carmen Matos & Ivet Petkowa</p>
    <img src="https://github.com/calumatos/Shark-Attack-Quest/blob/main/shark.png" alt="shark" width="200">         
  </div>

            Content:    
            
            shark_attacks.ipynb,  
            function.py,  
            shark_attacks_quest_CI (Google Slides),
            Shark_Attacks_Quest.pdf,
            README.md
            
To start the project we needed to read the file and load the given dataset. The dataset sharks_csv contains information about shark attacks from different locations around the world.

After checking the content of the columns, we dropped the columns that didn't contain the information we needed or that had no values at all. We checked the number of missing values with isna().sum(), we start checking each column independently with .value_counts() and we fill the missing values in the columns with 'N' to make the analysis easier.

We also created lambda functions to replace the names of the variables of interest in our analysis. Once the columns of interest were clear, we carried out some methods to validate our hypothesis. We also created some plots to confirm our findings and conclusions. 

[View Final Presentation](https://github.com/calumatos/Shark-Attack-Quest/blob/main/Shark_Attacks_Quest.pdf)

#### Here's a summary of the columns:

1. **Date:** The date when the attack has happened.
2. **Year:** The year in which the attack has happened.
3. **Type:** The type of the attack.
4. **Country:** The country of the attack's location.
5. **State:** The state where the attack was reported.
6. **Location:** The location where the attack was reported.
7. **Activity:** The activity that the attacked person was practicing in water.
8. **Name:** The name of the attacked person.
9. **Sex:** The gender of the attacked person.
10. **Age:** The age of the attacked person.
11. **Injury:** The injury the attacked person has suffered.
12. **Unnamed: 11:** Column with NaN
13. **Time:** The time in which the attack has happened.
14. **Species:** The specie of the shark related to the reported attack.
15. **Source:** Where the information is coming from.
16. **pdf:** Links to pdf documents related to the incident.
17. **href formula:** Function returns a hyperlink from a given destination and link text.
18. **href:** The href attribute specifies the URL of the page the link goes to.
19. **Case Number:** Case number of the incident
20. **Case Number.1:** Column with NaN
21. **original order:** Column with NaN
22. **Unnamed: 21:** Column with NaN
23. **Unnamed: 22:** Column with NaN

