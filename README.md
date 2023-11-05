[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=12539233&assignment_repo_type=AssignmentRepo)
# Theory vs. Practice

- List 3 reasons why asymptotic analysis may be misleading with respect to
  actual performance in practice.
  They can take more or less time overall. This is because you can have different hardware, different data, and various inefficienies caused by humans.

- Suppose finding a particular element in a binary search tree with 1,000
  elements takes 5 seconds. Given what you know about the asymptotic complexity
  of search in a binary search tree, how long would you guess finding the same
  element in a search tree with 10,000 elements takes? Explain your reasoning.
  Since the time complexity is O(logn) (assuming balanced) the initial time complexity is log(1000). Therefore a list 
  with 10k elements would result in a time equal to 5*(log(10000)/log(1000)) or 6.6666 seconds.

- You measure the time with 10,000 elements and it takes 100 seconds! List 3
  reasons why this could be the case, given that reasoning with the asymptotic
  complexity suggests a different time.
  Most likely I would suggest that poor coding of a search algorithm would result in this, as human error has a very big impact on how efficient something
  can be. Other potential causes could be hardware not performing correctly, possibly an old computer is used, and calling back on the poor code, the data
  could be poorly managed resulting in the distribution within the tree preventing the algorithm from efficiently accessing the 

Add your answers to this markdown file.
