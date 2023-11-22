# Operation-Analytics-and-Investigating-Metric-Spike    


   
  
### Project Overview    
---

Operational Analytics is a crucial process that involves analyzing a company's end-to-end operations. This analysis helps identify areas for improvement within the company. As a Data Analyst, I'll work closely with various teams, such as operations, support, and marketing, helping them derive valuable insights from the data they collect.  


One of the key aspects of Operational Analytics is investigating metric spikes. This involves understanding and explaining sudden changes in key metrics, such as a dip in daily user engagement or a drop in sales. As a Data Analyst, you'll need to answer these questions daily, making it crucial to understand how to investigate these metric spikes.  


In this project, I'll be dealing with various datasets and tables, and your task will be to derive insights from this data to answer questions posed by different departments within the company. The goal is to use  advanced SQL skills to analyze the data and provide valuable insights that can help improve the company's operations and understand sudden changes in key metrics.     

  

  

  </br>  
   </br>   
   
    
  
### Tools Used
- `SQL`
- `SQL Workbench`

   


    </br>  
      </br>  
      
### Operations Performed   

`Case Study 1:` Job Data Analysis  

You will be working with a table named job_data with the following columns:

`job_id:` Unique identifier of jobs </br>
`actor_id:` Unique identifier of actor</br>
`event:` The type of event (decision/skip/transfer).</br>
`language: `The Language of the content</br>
`time_spent: `Time spent to review the job in seconds.</br>
`org:` The Organization of the actor</br>
`ds: `The date in the format yyyy/mm/dd (stored as text).  </br>

  
 Tasks:


1.Jobs Reviewed Over Time:  </br>
 Calculate the number of jobs reviewed per hour for each day in November 2020.  
 
2.Throughput Analysis:</br>
 Calculate the 7-day rolling average of throughput. Additionally, explain whether you prefer using the daily metric or the 7-day 
 rolling average for throughput, and why.  
 
3.Language Share Analysis:</br>
 Calculate the percentage share of each language over the last 30 days.  
 
4.Duplicate Rows Detection:</br>
 Display duplicate rows from the job_data table.    

   

   </br>  
     </br>  
   
  
  `Case Study 2:` Investigating Metric Spike  

You will be working with three tables:

`users:` Contains one row per user, with descriptive information about that user’s account.</br>
`events: `Contains one row per event, where an event is an action that a user has taken (e.g., login, messaging, search).</br>
`email_events:` Contains events specific to the sending of emails.  </br>

Tasks:

1.Weekly User Engagement:</br>
 Calculate the weekly user engagement.  
 
2.User Growth Analysis:</br>
 Calculate the user growth for the product.  
 
3.Weekly Retention Analysis:</br>
 Weekly retention of users based on their sign-up cohort.  

4.Weekly Engagement Per Device:</br>
 Calculate the weekly engagement per device.  
 
5.Email Engagement Analysis:</br>
 Calculate the email engagement metrics.  
 

