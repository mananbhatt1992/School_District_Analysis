# School_District_Analysis

Using Pandas library and Jupyter Notebook help Maria peform analysis on reading and math scores for students in different schools of a district.
The aim is to provide a summary of the district performance,school performance by type, size and spending

## Analysis

### District Analysis

Please refer below screenshot for District Analysis Summary:
![image](https://user-images.githubusercontent.com/99941484/161409115-8921d96b-939f-46ea-976d-2804bcda9f94.png)

The Overall Pass Percentage is 64.9%.
The pass percentage for mathematics and rading are 74.8% and 85.7% repectively.
We can determine the indivisual pass percentage for each subject is good while the overall percentage can be improved.

### School Analysis

Please refer below screenshot for School Analysis:
![image](https://user-images.githubusercontent.com/99941484/161409560-cad69786-c5be-4b4c-8714-169283600e45.png)

We can see from the table that the schools that have been allocated a high budget does not guarantee a higher overall pass percentage. This may also be due to the fact tha the number of students are more.
We can deduce from the results that the low performing schools are of type district while the charter schools are high perfroming. All the low perfroming have a per student budget greater than 600 and the number of students in the low perfroming schools is more than the high performing schools which is a contributing factor to the schools low overall passing percentage

Pleae refe screenshots below:

1.) High Performing Schools:

![image](https://user-images.githubusercontent.com/99941484/161409687-bb6b9486-ffb3-4625-9aca-428a75d6b67e.png)

2.) Low Performing Schools:

![image](https://user-images.githubusercontent.com/99941484/161409704-d7ed3a15-bfc7-4e1f-98e4-cec9d7a6de1d.png)


#### School Analysis by Size(No.of Students)

Please refer below screenshot:

![image](https://user-images.githubusercontent.com/99941484/161410145-253e3d9a-f08f-418c-a6c2-03053e7d16bf.png)

#### School Analysis by Spending(per student)

Please refer below screenshot:

![image](https://user-images.githubusercontent.com/99941484/161410182-8feefdf7-6171-408f-8b41-b1dd1948bbe3.png)

#### Analysis of Thomas High School

According to our analysis we can determine that Thomas high school is one of the high performing charter schools but we have only considered the scoring for 10th to 12th graders.

Please refer below screen shots:

1.) Replacing 9th Grade scores with NaN

![image](https://user-images.githubusercontent.com/99941484/161410329-a45bcc55-1eb7-406e-8bf0-5b9e6d90acfb.png)

We can see that overall passing percentage for Thomas High School is 65.7 percent when the math and reading scores values are replaced with NaN.

2.) Considering the reading and math score only for 10th to 12th grades in Thomas High School:

![image](https://user-images.githubusercontent.com/99941484/161410509-ecff97a1-0aa5-4523-9de2-6e0c7ca9ee07.png)

The overall percentage is 90 percent now.

Thoams high school was one of the low performing schools but if we only consider scores for 10th to 12 th grade the Thoams high schools becomes one high performing schools coming in at second position. 


## Summary

1.) Average Reading Scores by Grade - Math :

![image](https://user-images.githubusercontent.com/99941484/161410619-f6a70eee-dcda-4f74-a2da-21b2731cd996.png)

2.) Average Reading Scores by Grade - Reading :

![image](https://user-images.githubusercontent.com/99941484/161410639-26685d86-3081-4ed3-b543-3f5204b0b6fb.png)

From the above screen shots we can see that the average reading and math scroes for Thomas High School is NaN


3. Thomas High School Changes :

   a.) Overall Pass Percent for Thomas High School increases from 65.07 percent to 90.63 percent.
   
   b.) The pass percentage for math increases form 66.91% to 93.18%
   
   c.) The pass percentage for reading increases from 69.66 percent to 97.02% 
