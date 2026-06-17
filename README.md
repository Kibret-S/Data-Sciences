

1. Create a Jupyter notebook where you create a list, iterate over the list and sort your results, generate random numbers, add to the list, and then print your results.

2. Create a line chart with Matplotlib and the following data file

Data file location
  https://view.officeapps.live.com/op/view.aspx?src=https%3A%2F%2Fcontent.bellevue.edu%2Fcst%2Fdsc%2F540%2Fid%2Fdata-files%2F12-week%2Fweeks-1-%26-2%2Fworld-population.xlsm&wdOrigin=BROWSELINK


4. Complete the following activities from the The Data Wrangling Workshop text. You can use the solution guides provided in the GitHub repo, but you must add your own original code comments, so that I can see you are learning what the logic means vs just copying from the book/answer guide. No code comments from the author should be included. You also need to consolidate all your code from each activity (including the ones above) into one notebook file. You do not have to follow the solution guides, and you are more than welcome to answer the problems in your own way using whatever method/function you deem appropriate - there are always more efficient or multiple ways to solve a problem. The goal is that you just answer the question in the activity, not copy the solution file.

  4. a. The Data Wrangling Workshop: Activity 1.01 page 23
   Activity 1.01: Handling Lists

1.Create a list of 100 random numbers. 
				
2.Create a new list from this random list, with numbers that are divisible by 3.
				
3.Calculate the length of these two lists and store the difference in a new variable.
				
4.Using a loop, perform steps 1, 2, and 3, and find the difference variable 10 times.
				
5.Find the arithmetic mean of these 10 difference values.


 4. b. The Data Wrangling Workshop: Activity 1.02 

     Activity 1.02: Analyzing a Multiline String and Generating the Unique Word Count

1 Create a mutliline_text variable by copying the text from the first chapter of Pride and Prejudice. 
Hint: Remember to add triple quotation marks to enter a multiline text. This is the only way to enter a chunk of text in Python.
https://raw.githubusercontent.com/PacktWorkshops/The-Data-Wrangling-Workshop/refs/heads/master/Chapter01/datasets/P%26P%20Ch01
2.Find the type and length of the multiline_text string using the type and len commands.
3.Remove all new lines and symbols using the replace method.
4.Find all of the words in multiline_text using the split method.
5.Create a list from this list that will contain only the unique words.
6.Count the number of times the unique word has appeared in the list using the key and value in dict.
7.Find the top 25 words from the unique words that you have found using the slice method.




  4. c. The Data Wrangling Workshop: Activity 2.01 

   Activity 2.01: Permutation, Iterator, Lambda, and List
In this activity, we will be using permutations to generate all possible three-digit numbers that can be generated using 0, 1, and 2. A permutation is a mathematical way to represent all possible outcomes. Then, we'll loop over this iterator and also use isinstance and assert to make sure that the return types are tuples. Use a single line of code involving dropwhile and lambda expressions to convert all the tuples to lists while dropping any leading zeros (for example, (0, 1, 2) becomes [1, 2]). Finally, we will write a function that takes a list like before and returns the actual number contained in it. 
These steps will guide you as to how to solve this activity:
			
1.Look up the definition of permutations and dropwhile from itertools.
2.Write an expression to generate all the possible three-digit numbers, using 0, 1, and 2.
3.Loop over the iterator expression you generated before. Print each element returned by the iterator. Use assert and isinstance to make sure that the elements are of the tuple type.
4.Write the loop again, using dropwhile, with a lambda expression to drop any leading zeros from the tuples. As an example, (0, 1, 2) will become [0, 2]. Also, cast the output of dropwhile to a list.
5.Check the actual type that dropwhile returns.
6.Combine the preceding code into one block; this time, write a separate function where you will pass the list generated from dropwhile and the function will return the whole number contained in the list. As an example, if you pass [1, 2] to the function, it will return 12. Make sure that the return type is indeed a number and not a string. Although this task can be achieved using other tricks, treat the incoming list as a stack in the function and generate the number by reading the individual digits from the stack.


     d. The Data Wrangling Workshop: Activity 2.02 
  
       Activity 2.02: Designing Your Own CSV Parser

A CSV file is something you will encounter a lot in your life as a data practitioner. A CSV file is a comma-separated file where data from a tabular format is generally stored and separated using commas, although other characters can also be used, such as tab or *. Here's an example CSV file:
We can convert the data in the preceding table into a Python dictionary, which would look as follows: {"Name": "Bob", "Age": "24", "Location": "California"}:
			
1 Import zip_longest from itertools. Create a function to zip header, line, and fillvalue=None.Open the accompanying sales_record.csv file from the GitHub link (https://raw.githubusercontent.com/PacktWorkshops/The-Data-Wrangling-Workshop/refs/heads/master/Chapter02/datasets/sales_record.csv) by using r mode inside a with block and check that it is opened.
2.Read the first line and use string methods to generate a list of all the column names.
3.Start reading the file. Read it line by line.
4.Read each line and pass that line to a function, along with the list of the headers. The work of the function is to construct a dictionary out of these two and fill up the key:values variables. Keep in mind that a missing value should result in None.

Don't forget to add original code comments to your work or you will lose points from the documentation section of the rubric.

You must submit one consolidated notebook file with the completed exercises. 
