## Introduction to Galaxy.  
Galaxy is a web interface that allows for user frienndly manipulation of data as compared to other progarmming heavy manipulation tools. Galaxy provides a platform for scientific workflows and data intergration. It also enables reproduciblity and collaboration as well as accessibility. This is because everything done in galaxy can be shared.
To begin working with galaxy, one needs to login to any of the three galaxy servers in the world; usegalaxy, galaxy EU and galaxy AU. 

## Working with galaxy.  
The three main steps in analysis on galaxy are:
   * Upload data
   * Find and run tool
   * View the results
 
 1. Upload data  
     Data can be uploaded on to galaxy using the upload data function on the galaxy platform. Data can be uploaded from a local computer, a data store        such as NCBI , or from a URL. Once the data is uploaded, it will be visible on the history column. Anything done on galaxy can be viewed from the        history section. Different histories can be created for different analysis and it is advisable to name the history to be able to remember what was        being done.
     
 2. Find the tools  
      The tools are located on the left side of the platform. If the user knows the tools they will use, they can search for the tool in this section. If       they do not know the tool, the tools are grouped according to the task they perform. Once the tool has been selected, the parameters for the run         are set and the task is executed.  
 
 3. View the results  
     The process of the task can be viewed in the history section. Once it completes successfully, the results can be downloaded from history. Galaxy          also provides varius options to visualize the output. The output of the first process can be used as the output for the next process. As a result,        galaxy enables creation of workflows.  
     
 ## Workflows  
   Workflows in galaxy can be created in three ways:   
       1. The workflow can be extracted from history  
       2. One can manually create a workflow  
       3. The workflow can be imported  
       
   
   * Extracting from history.  
     Once all the processes have been completed, the failed jobs are removed. Once this is done, a workflow can be created from the history. Anew history can be created and the same workflow can be executed in this history as long as it has the right data set for analysis.  
     
   * Importing workflows. 
     Workflows can be imported from the shared data in the galaxy platform . They can also be imported from the web by pasting the URL in the import          section.  
     
   * Manual creation of workflows.  
     Galaxy provides the option of manually creating a workflow. It even provides a graphical representation of the workflows. These workflows can then be exported or published . Here is a workflow I have created for the identification of AMR genes in waste water collected from Kenya by Rene S.Hendriksen *et al* for their paper on [**Global monitoring of antimicrobial resistance based on metagenomics analyses of urban sewage**](https://www.nature.com/articles/s41467-019-08853-3).  
* [The pictorial representation](https://usegalaxy.org/workflow/gen_image?id=4bbeefad1fa741ed)    
* [The workflow](https://usegalaxy.org/u/ann_cheptoo/w/first-workflow/json-download)  
