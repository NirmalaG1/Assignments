# Assignments
Assignment 01 Python Data Structures 
created data set with given data
1) Using a for loop, print each job posting in a readable format.

   used for loop with the range as length of jobid
   extracted key and value with .iems function and printed with | 

 2)  Add New Job Postings (interactive)
     got inputs from user. based on inputs, inside for loop,
     autoincremented jobid using nagative index. and appened values to corressponding keys

3 )  Clean & Normalize Skills (text processing) 
  created a function to clean input. inside clean_skill function,processed data.
  using list comprehension, updated skills to respective key and value in dictionary and printed same.
 
4)  Skill Extraction & Frequency
      splited every skill in to indivually based on space.stored all skills in a list. for counting the values in list ,based pn for loop
    checked how many time skills are existed and updated count.
    prined the skill and count to list
    sorted it in reversed order. after unpacked the sorted list as tuple, printed skill and its count 
   
   
5) Basic Statistics & Insights
    Total number of job postings is calculated based on the length
   splitted the skills list .stored all the indivudual sets in another list.and passed this in to
   set() to find unique skills.and  length(unique silks ) is printed
   using list comprehension method found the company lists which need specfic skill

6) Skill Search Function (functions & conditional logic)

      created a string function which accepts sring as arguments. the processed string.
      based on for loop i extracted skill and processed. and compared input string with extracted.
      if found similar, printed corressponding job details in the list
7)  Lambda Filtering & List Comprehension
      used filter function. inside passed lamba fuction as argument and list as iterable

 8)Unique Skill Set
 
after findling consolidated skills, passed this as a variable inside set() function
and printed unique 

9)  Save Cleaned Data to File (file handling & exceptions)
   after processing all the above,  written the data in .csv and .txt file
used try and except methods to handle error






 
      

     













