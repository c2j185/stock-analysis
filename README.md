# VBA of Wall Street
## Project Overview
The purpose of the project is to refactor, or rework, VBA code in excel. The client wants to use the code to research possibly thousands of stocks over a larger time period. The original code would have been to slow. Refactoring the code allowed the code to perform the same tasks more efficiently.

## Results
Utilizing the code and looking at the data, one can conclude that the stocks performed better in 2017 versus 2018, except for TERP. Terp was in the red for both years but did increase from -7.2% to -5.0%. In 2018 ENPH went down, but was still in the green; while RUN jumped 78.5%.


![2017_tickers](https://user-images.githubusercontent.com/86030200/125223546-f5fffc80-e299-11eb-999e-097bdde97ba4.png)                ![2018_tickers](https://user-images.githubusercontent.com/86030200/125223834-6c9cfa00-e29a-11eb-8022-befbf0198236.png)


## Summary
### Advantages of refactoring code:
  - Allows the ability to make code more efficient
  - Uses less memory
  - Makes code easier to read

### Disadvantages of refactoring code:
  - Can introduce more errors if not understood properly
  - Can take more time to refactor the code than is actually worth

### Specific Pros and Cons that apply to refoctoring the project's original VBA Code
  -The main advantage was the increase in speed. Approximately an 80% increase in speed.
    -Running the 2017 data went from 1.02 seconds to .187 seconds
    -Running the 2018 data went from 1 second to .18 seconds
    
  -The main disadvantage would be the time it took to refactor the code. If the code was only going to be used on the original 12 stocks, it would not have been worth the cost to      refactor the code. 
  
  I believe since the object is to use the program on thousands of stocks, it was beneficial to refactor the code.
