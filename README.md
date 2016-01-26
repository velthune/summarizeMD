# summarizeMD
SummarizeMD is a simple Ruby script that generate summary (TOC) for an existing MD document.  
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


#License

Copyright (c) 2015 velthune

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
