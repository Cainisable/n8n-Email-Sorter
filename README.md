# n8n-Email-Sorter
An email sorter that I built to keep my professional email organized: [Email_Sorter.json](https://github.com/user-attachments/files/19745537/Email_Sorter.json)
![Email Sorter](https://github.com/user-attachments/assets/17762505-d601-42eb-a5c2-6035cecc6065)

This pipeline is fairly basic in theory. It utilizes ChatGPT to read the email content and sort each email into one of several predetermined categories. Based on the category, several different steps will happen based on how I may want to action emails of that type.

The top path is a bit more complex. It scrapes job alert emails from major job banks and prepares any jobs featured on the alert for further analysis. (the job analysis flow can be viewed here: https://github.com/Cainisable/n8n-Job-Posting-Analyzer/tree/main)

It utilizes filters primarily to check job posting validity due to the vast quantity of job postings analyzed, as the formatting is consistent enough, and utilizing an AI like ChatGPT would utilize too many operations to be feasible. 
