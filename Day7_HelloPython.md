# Introduction to Python Programming
## program
- is a specific set of ordered operations for a computer to perform
- is an algorithm
#### An algorithm 
- is a detailed sequence of actions to perform to accomplish some task.
- is a list set of instructions, used to solve problems or perform tasks, based on the understanding of available alternatives.
## Programming language
-  is a way for programmers (developers) to communicate with computers.
- Computers have this languages to like Assembly,C,C++,Java,Javascript,Pythonetc
## Generation of Computers
### 1.First Generation Computers (1940-1956) 
- The first computers used vacuum tubes for circuitry and magnetic drums for memory. 
- They were often enormous and taking up entire room. 
- First generation computers relied on machine language. 
- They were very expensive to operate and in addition to using a great deal of electricity, generated a lot of heat, which was often the cause of malfunctions. 
- The UNIVAC and ENIAC computers are examples of first-generation computing devices.

Advantages : 
- It was only electronic device 
- First device to hold memory 

Disadvantages : 
- Too bulky  i.e. large in size 
- Vacuum tubes burn frequently 
- They were producing heat
### 2.Second Generation Computers (1956-1963) 
- Transistors replaced vacuum tubes and ushered in the second generation of computers. 
- Second-generation computers moved from cryptic binary machine language to symbolic. 
- High-level programming languages were also being developed at this time, such as early versions of COBOL and FORTRAN. 
- These were also the first computers that stored their instructions in their memory. 

Advantages :                                                                                                                                          
- Size reduced considerably                               
- The very fast          
- Very much reliable

Disadvantages : 
- They over heated quickly 
- Maintenance problems
### 3.Third Generation Computers (1964-1971) 
- The development of the integrated circuit was the hallmark of the third generation of computers. 
- Transistors were miniaturized and placed on silicon chips, called semiconductors. 
- Instead of punched cards and printouts, users interacted with third generation computers through keyboards and monitors and interfaced with an operating system. 
- Allowed the device to run many different applications at one time. 

Advantages :  
- ICs are very small in size 
- Improved performance 
- Production cost cheap 

Disadvantages : 
- ICs are sophisticated
### 4.Fourth Generation Computers (1971-present) 
- The microprocessor brought the fourth generation of computers, as thousands of integrated circuits were built onto a single silicon chip. 
- The Intel 4004 chip, developed in 1971, located all the components of the computer. 
- From the central processing unit and memory to input/output controls—on a single chip. 
- Fourth generation computers also saw the development of GUIs, the mouse and handheld devices.

Advantages:
- They were developed for totally general purpose use (general-purpose computers).
- Smaller in size and much more reliable than other generations of computers.
- The heat generation was negligible.
- No cooling system is required in many cases of the fourth-generation computer.
- Portable and cheaper than the older versions.
- Fourth-generation computers were much faster than the older generations.

Disadvantages:
- Very advanced technology was required to fabricate the ICs (Integrated Circuits).
- A high-quality and reliable system or technology can only make the ICs.
- Cooler is required (Fan)
- The latest technology is required for the manufacturing of Microprocessors.
### 5.Fifth Generation Computers (present and beyond) 
- Fifth generation computing devices, based on artificial intelligence. 
- Are still in development, though there are some applications, such as voice recognition. 
- The use of parallel processing and superconductors is helping to make artificial intelligence a reality. 
- The goal of fifth-generation computing is to develop devices that respond to natural language input and are capable of learning and self-organization.

Advantages:
- The fifth-generation computers will use super large-scale integrated chips.
- They will have artificial intelligence.
- They will be able to recognize images and graphs.
- Fifth-generation computer aims to be able to solve highly complex problem including decision making, logical reasoning.
- They will be able to use more than one CPU for faster processing speed.
- Fifth-generation computers are intended to work with natural language.
- These computers are much faster than other generation computers.
- It is easier to repair these computers.
- These computers are much smaller in size than other generation computers
- They are portable and easy to handle.
- Development of true artificial intelligence.
- Advancement in Superconductor technology

Disadvantages:
- They tend to be sophisticated and complex tools.
- They can give more power to companies to watch what you are doing 
## Types of Programming Languages
A.LOW level programming language
-These languages are more like machines but with lots of effort people can understand them. They are close to the hardware of the computer.
- Ex: Assembly

B.High level Programming languages
- They are more close to human languages.
- Example: Python,C++,Java,JS…

C.Medium Level
- Languages Between Low level and High level, they combine both
- Ex: C-lang
## How do high level languages work?
1. Compilers: are tools which helps to convert the whole code to bytecode then computer will execute it
  - Example: C,C++,Java,..
2. Interpreter: can directly execute the code by reading the source code line by 
line
  -  Example: python
## Python Programming
- Python is a computer programming language often used to build websites and software, automate tasks, and conduct data analysis. 
- Python is a general-purpose language, meaning it can be used to create a variety of different programs and isn’t specialized for any specific problems.
- is a High level & interpreted programming language and also Very easy to learn
## Uses of Python
- Data visualization
- Data analysis
- Machine learning
- Artificial intelligence
- Back-end web development (with frameworks like Django and Flask)
- Game development
- Hacking Script writing
## IDE & Code editors
#### IDE ( Integrated Development Enviroment ):
- Is a Software that helps to write & run a Specific Programming language. Example: PythonIDE
#### Code Editors: 
- are softwares those can help to write any kind of programming languages. And also by adding some compiling/ interpreting feature they can run programs/scripts Example: Sublime,Vscode
## Outputs and Comments
- On python, to display output we use keyword ‘print’
- Syntax: print(object=’’, sep=’’, end=’’)
- This are a simple notes written on our codes those can help as to remember the function of the code or to make it simple for peoples to understand our code.
- Comments won’t be executed.
- Syntax: # This is a comment line
- Keywords are predefined, reserved words used in Python programming that have special meanings to the compiler.
## Variables
- Variables are a value holders /containers/ 
- They store data
- We give some value to some word.
- example : apple = 10 => from now on my python program knows the value of apple is 10.
- The process of giving value to word is called Variable Declaration
- The word that holds the data is called Identifier
- We can Print value of variables by giving the identifier
- You can print the variable with {variableName} on print keyword Syntax: print(f”yourtext {variable}”)
##### On naming the identifier:
  - Don't use space between words use _
  - Don't use numbers as identifier
## Data types
A) Numeric Data type
int(integer) - holds signed integers of non-limited length.
● float - holds floating decimal points and it's accurate up to 15 decimal places.
● complex - holds complex numbers.
★ You can Identify The type of a variable with the keyword ‘type()’

B. String Data
- String is a sequence of characters represented by either single or double quotes. For 
example, var = “ ” or var = ‘ ’

C. Sequence Data
  1. Lists
  a.List is an ordered collection of similar or different types of items separated by commas and enclosed within brackets [ ]. For example, languages = ["Swift", "Java", "Python"]

  b.To access items from a list, we use the index number (0, 1, 2 ...). For example, languages[0]

  c.We can add/modify objects to the list, languages.append(“Amharic”)

  2.Tuple
- Tuple is an ordered sequence of items same as a list. The only difference is that tuples are immutable. Tuples once created cannot be modified.
- we use the parentheses () to store items of a tuple. For example, product = ('Xbox', 499.99)
- Similar to lists, we use the index number to access tuple items in Python 

D.Dictionary data
- Python dictionary is an unordered collection of items. It stores elements in key/value pairs.
- user1 = {'name':’eleni,'Dep:'cs'}
- name and Dep = key
- eleni & cs = value
- We use keys to retrieve the respective value. But not the other way around.
