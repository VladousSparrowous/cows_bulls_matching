# cows_bulls_matching

Cow-Bull Pairing Algorithm for Cattle Breeding

I've developed a Python algorithm that optimally pairs bulls with cows while considering:

  1. Maximizing expected breeding value (EBV) of offspring

  2. Maintaining genetic diversity

  3. Respecting inbreeding constraints

  4. Following bull usage limitations

Parts of solution:

  1. Data analysis
    
  2. Population Segmentation
     
  the population was systematically divided into family groups based on pedigree relationships
   
<img width="943" height="842" alt="загруженное" src="https://github.com/user-attachments/assets/d6f7fd64-eebb-4c9c-9034-3f90e2945a51" />

  3. Handling missing values of ebv
     
  values are processed based on pedigree or taken as zero

  4. Pairing Algorithm Implementation
     
  to maximize the average for cows with a lower ebv, bulls with a higher ebv are selected in accordance with the restrictions.
