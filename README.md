# School_District_Analysis

*Overview of the school district analysis:* 
The purpose of this updated analysis is to show how omitting data can affect downstream data & final output. It's important to consider how to handle invalid data as datasets tend to refer to one another, which can lead to errors down the road. By removing the Thomas High School 9th grade results, we can see that the dataset changes. 

*Results*

**How is the district summary affected?**

***Original District Summary***
![Original_District_Summary](https://user-images.githubusercontent.com/99565016/158085925-6eea0662-bba8-4b1c-b110-2908922df9ca.PNG)


***Updated District Summary***
![Updated_District_Summary](https://user-images.githubusercontent.com/99565016/158085929-f4b06451-1daf-4ccf-b183-08ccf936d7b5.PNG)


We can see that removing Thomas 9th Grade data has changed the %Passing Math & Reading along with the % Overall Passing. We wouldn't expect too big of a change as the students from all the other high schools are weighed in the final results. 

**How is the school summary affected?**

***Original School Summary***
![Original School Summary1](https://user-images.githubusercontent.com/99565016/158086301-15613e5b-df25-4335-ada9-71270b49b121.PNG)


***Updated School Summary***
![Updated School Summary](https://user-images.githubusercontent.com/99565016/158086295-2e8589fc-00f9-40d4-9b51-38c221d58c0c.PNG)

We can see that removing Thomas 9th Grade data has changed the individual row (Thomas High School) to have a much higher success rate than the district summary counterpart. This is due to the fact that the results are unique only to Thomas High School, and therefore more volatile from changes. 

**How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?**

***Original Performance of Thomas High School***
![Original Performance](https://user-images.githubusercontent.com/99565016/158086590-f0f56565-647c-4a40-bb41-56a4c7728b5f.PNG)

***Updated Performance of Thomas High School***
![Updated Performance](https://user-images.githubusercontent.com/99565016/158086607-cb0b4268-1747-4501-bf10-f64181481e84.PNG)


The key difference between the updated and original dataframes is that the 9th graders' data from Thomas High School are missing in the updated form. This is expected as we omitted their data from the results.

**How does replacing the ninth-grade scores affect the following:**

**Math and reading scores by grade**


***Original Math Scores by Grade***
![Original Math Scores by Grade](https://user-images.githubusercontent.com/99565016/158093792-4af4eb8e-5b99-4619-82d3-ffa91d92eb6b.PNG)



***Original Reading Scores by Grade***
![Original Reading Scores by Grade](https://user-images.githubusercontent.com/99565016/158093787-3bab0a30-86e9-4e12-bc1a-25454078f535.PNG)


***Updated Math Scores by Grade***
![Upddated Math Scores by Grade](https://user-images.githubusercontent.com/99565016/158093481-ca13de0d-e0f2-429e-ab7d-9e15d453b436.PNG)



***Updated Reading Scores by Grade***
![Updated Reading Scores by Grade](https://user-images.githubusercontent.com/99565016/158093437-ad1dc89a-c42a-4bee-b49a-00b652b7ac12.PNG)



**Scores by school spending**

***Original Scores by School Spending***
![Original Scores by School Spending](https://user-images.githubusercontent.com/99565016/158092982-debc925b-1e2b-4fe7-b7ec-6484e7cc6ee3.PNG)


***Updated Scores by School Spending***
![Updated Scores by School Spending](https://user-images.githubusercontent.com/99565016/158093444-68c0c138-f244-451f-8bbf-f143c9b69cde.PNG)


Since Thomas High School results are in the $630-644 range, we can expect that only that row will be affected. We can see that the %Passing of math and reading & % Overall passing went up as a result of removing the 9th grader data from Thomas High.

**Scores by school size**

***Original Scores by school size***
![Original Scores by School Size](https://user-images.githubusercontent.com/99565016/158092992-c4ef7c28-c267-4fbc-a3c8-bc6213f7cf75.PNG)


***Updated Scores by school size***
![Updated Scores by School Size](https://user-images.githubusercontent.com/99565016/158093495-2bbaae8e-99e4-45a3-9db0-11d5d9711d45.PNG)

Since Thomas High School results are in the Medium (1000-2000) school size range, we can expect that the medium school size row will have changed results. We can see that the same case as school spending is applied here. The overall % passing has improved.

**Scores by school type**

***Original Scores by school type***
![Original Scores by School Type](https://user-images.githubusercontent.com/99565016/158093009-bcde7961-54b4-4321-9c61-e94ec9ddc9fd.PNG)


***Updated Scores by school type***
![Updated Scores by School Type](https://user-images.githubusercontent.com/99565016/158093502-6725f065-3bb1-4d45-93c2-6b3e92f0eb2b.PNG)

Since Thomas High School is classified as a Charter school type, the charter row should be the only one affected. Same trend applies to this case as well, % Passing of math and reading & % overall passing went up with the omission of 9th grader data from Thomas High.

*Summary*
Four apparent changes in the updated school district analysis is that the ranking of Thomas High School went from 8th place in the district to 2nd place using "% Overall passing" as the criteria. Another two changes is that the % passing of math and % passing of reading has went up by a considerable amount. The final change is that the overall % passing has gone up for Thomas high School students. These trends were discovered in the results portion of this page. 
