---
  title:
    LATEX FORMAT CAPSTONE 2019 BTECH VIT
  author:
    TUNEER BHATTACHERJEE 15BEE0134
  email:
    tuneerbhattacharya@gmail.com
---
## Important Note
IF YOU DONOT KNOW HOW TO USE LATEX AND THIS IS YOUR FIRST TIME USING IT. THIS WILL TAKE SOME TIME (PROBABLY A MONTH). DONOT TRY TO PULL THIS OFF A DAY OR TWO BEFORE. IF YOU HAVE ONLY A COUPLE OF DAYS LEFT FOR FINAL THESIS SUBMISSION STICK TO WORD LIKE THE OTHER NOOBS :P
## How to use this file?
1. If you have git installed on your machine then use :
 >git clone https://github.com/mr-solenya/capstone-project-latex-format.git
2. Else download the zip file from github and unpack it
3. Replace all the data which is given within '<'and '>' (donot change any commands)
4. Insert your own table under Symbols and Notations. Since making tables from scratch is very tedious in latex therefore, you can use the website https://www.tablesgenerator.com/
5. Change the bib file contents according to your needs
6. Sample fig attachement code is given under the section 'Background'
7. Sample code attachement code is given under the section 'Schedule, Tasks and Milestones' and is as follows:-
>\lstinputlisting[language=Python]{./codes/samplecode.py}

## MISC INFO REGARDING THE latex
1. Use pDFLatex to compile the codes
2. For build options see command1.png and command2.png in instruction_images
3. Add the following user commands:-
- user0:Make Nomenclature  ->  makeindex -s nomencl.ist -t %.nlg -o %.nls %.nlo
- user1:Make Glossaries    ->   makeindex thesis.glo -s thesis.ist -t thesis.glg -o thesis.gls
4. Run makeindex once before running the texfile (which is done by clicking on 'index' in the 'Tools' menu in TexStudio)
