# JS-understanding-Weird-Parts

### Conceptual Aside: 

#### 1. Syntax Parsers:
           A program that reads your code and determines what it does and if its grammer is valid.
           
           It's like a teacher who is trying to evaluate our test paper.
          
#### 2. Lexical Environment:
           Where the code sits.
           
           Like inside editor or functions.
           
#### 3. Execution Context: 
			A wrapper or box that help to manage the code that is running.
            There are lots of lexical environments which one is running is managed via execution context.
            For every function new exectuion context is created.
            



### Name/Value Pair:

#### Name:
      		A name is which maps to a uniqe value.
            
            Ex: 
                address = 'Hello'
                
#### Object: 
     		Collections of name value pairs.
            
            Ex: 
               laptop: 
               {
               		model: 123,
                    color: "silver",
                    configuration:
                    {
                    	RAM: 8 GB,
                        Processor: 2.7 GHz
                    }
               }
 
 ### Exection Context:
        At global level Global object window and this is created automatically.
        
        At Global level this = window .
  
               
            
            
            
