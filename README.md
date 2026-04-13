# Class Replacement Tool # 

### Preface ### 
___Quick run down:___ you put your bot description source code into section 1, press "Run Replacements" and then copy your output in section 3 which should now contain the new description classes. Paste that back into your bot source code and enjoy not having to search-and-replace every individual class. 

I simply needed a tool that replaced one class ID with another. The site is constantly updating and changing and manually replacing classes just wasn't going to cut it anymore, so here we are. 

So despite it's name, actually, it's not JAI specific, you can use this with any CSS, but I made this for JAI-purposes. 


## How it works ## 
1. YOUR CSS/HTML 
> Drag & Drop your css file or manually enter it into the box. 

> This is the file you want to change the classes of. For example, your bot bio description source code. You can copy and paste that whole thing in there. 

2. CLASS MAPPING 
#### **I HAVE THIS PRE-LOADED WITH THE CURRENT CLASS EQUIVALENTS. IF YOU JUST WANT TO PLUG-AND-PLAY, DO NOT CHANGE ANYTHING IN THIS SECTION!** ####
> This is where you need to set the class equivalents. The input on the left will be replaced with the input on the right. 

> E.g. You have a class named "btn-primary" and now you need to update all instances to a class named "button-main". You put `btn-primary` --> `button-main` 
> To add more entries, press *+ Add row* and enter your old class on the left and the new class on the right

> You can import a `.ini` mappings file if you have an existing mapping you want to use, or export your current one with the buttons available.

3. OUTPUT 
> Your code with the newly updated class equivalents will appear here! You can now copy & paste this into where ever you need it or download it as a file. 

4. CHANGE LOG 
> Shows what classes were successfully replaced in your document.


### Disclaimers ### 
This tool is not officially associated with or officially endorsed by JanitorAI. It was created with the purpose of being a useful community tool to improve QOL with botmaking. I do *not* collect any data off of it and I do *not* receive any files you upload or information you put in the tool. I have *no* access to any of your personal information (nor do I want it). Please use the tool at your own discretion. 
*FULL DISCLOSURE: THE JAVASCRIPT WAS HEAVILY ASSISTED BY CLAUDE SONNET 4.6, I DO NOT TAKE CREDIT.*  

