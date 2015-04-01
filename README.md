# summarizeMD
SummarizeMD is a simple script that generate summary (TOC) for an existing MD document.  
Each item of summary is linked to the respective section.

#Usage
- download file
- open console
- chmod +x summarizeMD
- ./summarizeMD \<yourfile\>.md



#Output

In order to preserve original file, the output of the script produce another file prepending generated summary.

    $ls 
	.
	..
    summarizeMD
    readme.md 
    
<br>

	./summarizeMD readme.md
    $ls 
	.
	..
    summarizeMD
    readme.md
    summarized_readme.md
       
  
#Options

You can launch script with some options (work in progress).



- **-o, --output [filename]**  
You can specify output filename.  
- **-v, --[no-]verbose**  
Run script verbosely printing some informations.   
- **-h, --help**  
Display list of available options.   
- **--version**  
Display script version.  
