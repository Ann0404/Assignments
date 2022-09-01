## What is Snakemake 
Snakemake is a workflow engine that utilises Python based language to define the processes. It offers a powerful working environment that ranges from  from single-core workstations to compute clusters without changing the process.  
It allows the scripts to be more transferrable and neat.  

## Basics of Snakemake  
A snakemake workflow has four main components:
* Rule  
     * This is the name of the process for instance;
          ```  
          rule fastqc:
          ```  
     * The process in this step is fastqc. It enables anyone using the script to understand what each step entails.  
  
* Input  
     * Define the input files for this process;
        ```  
         input:
           "examples/primates.fa"
        ```  
     * More than one input file can be provided for analysis  

* Output 
