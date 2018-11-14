# Graduate Course Selector

This is a project designed for Undergraduate students at NC State University. In this project, the undergraduate students can select the current subjects and their interest in the domain and we will suggest them the subjects that they can take during the graduate studies.

## Problem Description
When we joined NC State University for Master of Computer Science, we were not aware of many of the courses which were available here. While enrolling for the courses on the MyPack Portal, there were hundreds of course and we were not sure how to plan our journey for the masters. So one day, we came up with this idea to design a system which can propose the subjects based on our undergraduate courses, interests and past records of the master students with similar interests. 

## Implementation
While designing this courses, we scraped the CSC Department subject list of the Undergraduate studies at NC State University and categorized them into different sections and domains. After that, we created a dummy dataset of 70 graduate students and the courses which they have taken during their undergraduate and graduate. We also scraped the data of the CSC Department subjects list of the Graduate studies at NC State University. 

The real challenge was how to integrate this system as a whole to work as desired and which algorithms to go for. For this, we started by identifying the different interest domains of the student and rated each subject according to these domains. The domains are:

- Database     
- Operating Systems
- Artificial Intelligence    
- Data Science    
- Graphics    
- Networking    
- Software Developer    
- Security

We rated all the courses of the graduate and undergraduate on the basis of these domains. For training our model, we made a data of students which comprises of their undergraduate and graduate courses. This dataset trains our model. We have used two approaches to decide which 10 courses should be taken by the Undergraduate students based on their current choices:
### Approach 1
### Approach 2

## Results

Since the front end of the project is under development, we manually entered the subjects which the student has taken during undergraduate as an array. This array can have 3 values:
- 0: If that subject was not taken
- 1: If that subject was taken
- 2: If the subject was taken and the student got good marks or if he/she likes the subject/domain

As an example, we have selected that the student gave 1/2 ratings to the following subjects. Consider 0 for the rest of the subjects.
- Subjects with Rating 1: 
- Subjects with Rating 2:

On the basis of this input and the trained model, our system was able to generate a list of 10 subjects which can be taken during the Graduate Studies. The subjects are:
- CSC505: Design and Analysis of Algorithms
- CSC520: Artificial Intelligence
- CSC554: Human-Computer Interaction
- CSC570: Computer Networks
- CSC573: Internet Protocols
- CSC574: Computer and Network Security
- CSC705: Operating Systems Security
- CSC773: Advanced Topics in Internet Protocols

<p align="center">
<img alt="Results" src="https://github.com/rayandasoriya/CourseSelector/images/result.png">
</p>

## Contributors

  - [Javan Rajpopat](https://www.linkedin.com/in/javanrajpopat/)
  - [Rayan Dasoriya](https://www.linkedin.com/in/rayan-dasoriya/)
  
  For any improvements and suggestions, reach us at jkrajpop@ncsu.edu or dasoriyarayan@gmail.com
