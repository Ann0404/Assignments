## What is Snakemake 
Snakemake is a workflow engine that utilises Python based language to define the processes. It offers a powerful working environment that ranges from  from single-core workstations to compute clusters without changing the process.  
It allows the scripts to be more transferrable and neat.  

## Basics of Snakemake  
A snakemake workflow has four main components:
* Rule  
     * Rules contain the name of the name of the process, input and output files and the command to be executed. For instance;
          ```  
          rule fastqc:
               input:
                  "path/to/inputfile"
               output:
                  "path/to/outputfile"
               shell:
                   "command to be executed {input} {output}"
          ```  
     * Naming the rule is important as it enables anyone using the script to understand what each step entails. The rule in this step is fastqc.   
  
 * Input  
      * Define the input files for this process;  
            ```  
               input:
                  "examples/primates.fa"
            ```  
     * More than one input file can be provided for analysis  

 * Output 
