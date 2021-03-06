# parser

CPSC 323 Programming Project 2 - Parser in C

Teammates:
    
    1. Vibha Rajagopalan - vibha@csu.fullerton.edu

    2. Brenda Gomez - gomezb636@csu.fullerton.edu

    3. Anjali patel - anpatel8@csu.fullerton.edu

Description: 

    Our project has a Lexical Analyzer, a Parser, and a Semantic Analyzer. Our Parser takes in the output from
    the Lexical Analyzer and generates a Parse tree. Our Semantic Analyzer takes the output from the Parser and 
    makes sure that it is semantically consistent. This is also known as the third phase of
    the compiler desing process.
    
*All output files have been provided, but if you wish to test on your own, below are the 
instructions to follow using Visual Studio*

How to Run:

    1. Open up three command prompts; one for lexical analyzer, one for parser, and one for the semantic analyzer

    2. Before running, make sure to build the Lex.sln in the lexicalAnalyzer folder, and parser.sln 
    in the parser folder to generate the executable files

    3. In first command prompt, once in parser directory:
        a. cd lexicalAnalyzer/Debug
        b. lexicalAnalyzer prog1.t lexOutput.txt
           (lexicalAnalyzer existingTestFile.t fileToBeCreated.txt)

    4. After the above line has ran, copy the lexOutput.txt file into the parser/x64/Debug folder in the parser 
    folder

    5. In second command prompt, once in parser directory:
        a. cd parser/x64/Debug
        b. parser lexOutput.txt > parserOutput.txt
           (parser existingFile.txt > fileToBeCreated.txt)

    6. Final output from parser can be found in "parserOutput.txt" file in the current directory

    7. After that, copy the parserOutput.txt file into the SemanticAnalyzer/SemanticAnalyzer/Debug folder in the SemanticAnalyzer 
    folder
    
    8. In third command prompt, once in SemanticAnalyzer directory:
        a. cd SemanticAnalyzer/SemanticAnalyzer/Debug
        b. SemanticAnalyzer parserOutput.txt > semanticOutput.txt
           (SemanticAnalyzer existingFile.txt > fileToBeCreated.txt)

Link to github repository: https://github.com/gomezb636/parser