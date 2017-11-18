# A cognitive walkthrough for the recruiters!

This is a redesign version of lab session 6, where we developed an interactive visualization to provide recruiters an essence of MSIS program at Santa Clara University. Here is the link: <br />
https://github.com/Tanushreechaudhary/Lab_Session6 <br />

## Lab 6 Visualization:
![image1](https://user-images.githubusercontent.com/32077698/32917704-eb66ed46-cad4-11e7-8f9d-ab7443609123.png)

## Critique for the Visualization:
The Visualization covers three metrics the four-year graduation rate, SCU graduates average salary, and percentage of students with GPA 3.75 or higher. In this lab session, we were supposed to develop an interactive visualization to help recruiters know why should they hire SCU students. But the visualization above is neither interactive nor it provides any valuable information that would be helpful from a recruiter's standpoint. Also, it only compares data about three universities and leaves out the other significant competitors.

## Roadmap for Improvement:
In the redesign version, I will be developing interactive visualization using three datasets - the MSIS skillset, MSIS students mid career salary and the university rankings in CA. The skills acquired by the MSIS students and the number of people having them will help recruiters to know that students at SCU have a erfect blend of techical and business skills required to excel in the market. Mid career salary would tell them how quickly the students graduated from SCU MSIS progress in thrie career. And lastly, university rankings data helps them to analyze the quality of education students had. These three important metrics would answer the audience's questions as to Why they should hire SCU graduates? I will also ensure to maximize the Data-Viz ratio, decrease the use of extra pixels if there is no relevant data. I will try to limit the use of colors to get it right in black and white and in printable form.

## Audience:
The audience here are the "Recruiters" looking to hire potential candidates. The first thing a recruiter would do is to map his requirements as per the skill set of the candidate. So, MSIS skill set is an important metric that would show what are the technical and business skills possessed by MSIS students at SCU. Secondly, how good SCU graduates are performing in their careers by seeing the mid-career salaries. And thirdly, the ranking of the university the student belongs to helps them evaluate the reputation of the university a candidate has studied in.

### Audience Need:
The need is to hire a highly skilled person from both technical and business aspects that can match the company requirements. Also, if a person is already high skilled, the company can save on training costs. If an alumni from a top ranked university is earning good in their mid-career, that is also a green flag for a recruiter.

### Audience Want:
A recruiter would want a candidate who is comfortable with new technology, familiar with new age tools like MySql, Tableau and have skills like Business Intelligence or HTML or Java. Recruiters would want university rankings that focus on academic prestige and scholarly excellence rather than attractiveness of the campus. So, in this way rankings based on MSIS programs in CA would be one of the metrics the audience would want to know. 

### Audience Fears:
* Not able to provide company with an ideal candidate with required skillset
* They might hire a wrong candidate

### Data Sources:
Data about Mid career Salary - https://www.payscale.com/ <br />
Data about University Rankings - https://patch.com  <br />
Data about MSIS skill set is taken from data shared by fellow classmates. <br />

### Link to Jupyter notebook:
https://github.com/Tanushreechaudhary/Lab_Session9/blob/master/LabSession_9_JupyterNotebook.ipynb

## Redesign: The key metrics are:
### 1. SCU MSIS graduates possess the perfect blend of technical and business skills!
#### Selected Technical skills
![image2](https://user-images.githubusercontent.com/32077698/32917705-eb8228fe-cad4-11e7-833c-6a0c321dea9f.png) 

#### Selected Business skills
![image3](https://user-images.githubusercontent.com/32077698/32917706-eba30cb8-cad4-11e7-8b67-5be83006d0c4.png)

The visualization above shows a pie chart on the left with two categories Technical and Business, upon selection of any one category, the graph on the right side changes, making it interactive. When selected Technical, it displays all the technical skills acquired by MSIS SCU students and the number of people in it. Similarly, for business category, it displays skills that fall in business category. 

### 2. How well SCU MSIS graduates are doing in their careers!
![image4](https://user-images.githubusercontent.com/32077698/32917707-ebbf2f60-cad4-11e7-8b17-281084a235a7.png)

The visualization shows that SCU MSIS graduates are earning better salaries in their mid-career as compared to other universities in the same area. This clearly gives audience an idea how SCU students are progressing quickly in their careers. One important reason behind this could be the curriculum designed for the students. At SCU, coursework is project-based, connecting learning to actual challenges in the field and the company will not have to spend extra money providing them training because they already are good with technology and have the required skillset.

### 3. SCU, the second best university in CA!
![image5](https://user-images.githubusercontent.com/32077698/32917708-ebe4ba28-cad4-11e7-8a71-450a378291a7.png)

I have used university rankings metrics which shows after Stanford University, SCU is the second best university offering MSIS in CA. I have used text tables because that is the best way to show the rankings instead of using bar charts or pie charts. The reason behind this ranking is greatly designed curriculum that offers the best to the students looking for undergraduate or graduate programs. Also, the acceptance rate is low at SCU and they require a high GRE score to admit students, which shows the university is very selective.

### Integrated Metrics
![image6](https://user-images.githubusercontent.com/32077698/32983744-82c306dc-cc4e-11e7-82e0-5ddaad5404b8.png)

As we all know, Stanford is the best university in CA, but Santa Clar University being so close to it in terms of Ranking and mid career salary is an excellent achievement. Stanford Graduates are earning $144,000 and SCU graduates are earning $140,000, which is so close. Also, if we compare the rankings, Stanford is the first one and SCU is the second best! <br />
I have used a scattered plot to show the integrated metrics for Rankings and Mid career salary, also I have put a trend line that clearly shows that Santa Clara is among the top universities.

## Link to cognitive walkthrough for Recruiters(Story): <br />
https://public.tableau.com/profile/tanushree3514#!/vizhome/AcognitivewalkthroughaboutMSISSCUforRecruiters/MSISDashboard

### Reason: Why I chose Story?
I wanted to present a sequence of visualizations that convey the message to the audience why they should hire students from SCU? I found it to be a better way to make an interactive dashboard and through story points we can highlight the main features of the worksheet in a narrative way. Also, If I had used a dashboard, it would have been too crowded to display all information on one screen.

## Conclusion:
Students at SCU have a perfect blend of technical and business skills like Tableau, Java, C, Project Management, Business Intelligence which are all the new age technology and are in high demand. Being ranked 2nd among the top universities in CA as per the academic excellence, it has a cutting edge curriculum that helps students to stand out in the crowd and progress more in their career. 

## RoadMap for future enhancements:
For the first story point about technical and business skills, can use a bar chart that displays the two categories, since the skills listed on x-axis like Java, SQL etc do not really represent a scale. Also after this, I can squeeze in the ranking and mid career salary worksheet (the second story point) in the same dashboard to satisfy the "Eye beats memory" rule.

### References:
https://insights.dice.com/2017/10/18/recruiters-managers-fear-hiring/ <br />
http://college.usatoday.com/2015/07/22/hiring-recent-college-graduates/ <br />
https://thebestschools.org/features/100-best-universities-in-world-today/ <br />
https://community.tableau.com/thread/148160


