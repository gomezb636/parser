# parser

CPSC 323 Programming Project 2 - Parser in C

Teammates:
    
    1. Vibha Rajagopalan - vibha@csu.fullerton.edu

    2. Brenda Gomez - gomezb636@csu.fullerton.edu

    3. Anjali patel - anpatel8@csu.fullerton.edu

Description: 

    Our project has both a Lexical Analyzer and a Parser. Our Parser takes in the output from the Lexical Analyzer and generates a Parse tree. This is also known as the second phase of the compiler desing process.
    
*All output files have been provided, but if you wish to test on your own, below are the instructions to follow using Visual Studio*

How to Run:

    1. Open up two command prompts; one for lexical analyzer and one fo parser

    2. Before running, make sure to build the Lex.sln in the lexicalAnalyzer folder, and parser.sln in the parser folder to generate the executable files

    3. In first command prompt, once in parser directory:
        a. cd lexicalAnalyzer/Debug
        b. lexicalAnalyzer prog1.t lexOutput.txt
           (lexicalAnalyzer existingTestFile.t fileToBeCreated.txt)

    4. After the above line has ran, copy the lexOutput.txt file into the Debug folder in the parser folder

    5. In second command prompt, once in parser directory:
        a. cd parser/Debug
        b. parser lexOutput.txt > parserOutput.txt
           (parser existingFile.txt > fileToBeCreated.txt)

    6. Final output from parser can be found in "parserOutput.txt" file

Link to github repository: https://github.com/gomezb636/parser