# ENG Homework 3 Group 2

## Homework Plan

### Member responsibility:

Jason: Algorithm \+ Coding   
James: Testing \+ Verification  
Chen-Yi: Review \+ Format \+ Submit

### Collaboration tools:

Communication: Discord  
Coding: VSCode

## Algorithm \+  Testing Plan Chart

![][image1]

## Testing Plan

Implement the z-score equation we wrote in the python script and hook it up with population 1\~3 and additional 2 cases. Have it print out the result and insert them into excel. In excel make an error row that checks and outputs a boolean value on whether the result of the python script and excel equation is the same. 

## Python script

## Test Results

## Report

[image1]: <data:image/png;base64,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7du37WNHDc25c+dsxX3mzJmSeadPn7aNquv1UGO7Z88e2xhOnTrVHD582L6/7t272/emELF161Zz9OjRaB167860adOi+z///LO97dOnjxk9erR9f3o99TLEGyo1sgo2eg1Hn1vL6LvTe9F7VM+EqFzLxoORqBfjww8/tMHIF/++tU4FMdG6jh07VvJ6opCh79KnsKGgpfekqaOGUP/fX375ZUmZQoPei15Pr6vHuj9s2DB763aNaXvYuHFjyXO/+eYbe6v5Woe+F70P/d+o18ZZuXKlmTNnTvQ9u3Xq/0Lz9P8a3y71fWp30ldffRWtozPc6azVglej6TXTfD2giAglOaAGX42H/joeOHCg/Stc9xU+1Cj88ssvtsxRmZ7z3nvv2b9gXcOh26dPn5pPP/00euzo+Qov8YbdUeOqZTXpffgUWDRPYUSN0pUrV2xjqQb1448/jp6ndeu+GtH4Lou+fftG99WILl682N5XT8nVq1ftc9VAjRw50gYtce993rx5UQM7YsQIW6YeCBcsNE+NtRpo9zrlPqP4vQqO/33ru507d67p1auXfY7K4q/nTJw4MbpfL61X61cAqGTWrFnRfRfs7t69az744IOS9xGnXUfi/r/03brdfe7zKAyqXMvs3LnTztN3ps+teW79+j9Wr5VbXyO0ejdKK18bKAJCSU7Mnj3bNjw6qFGNpGsgNf36668ljZfruejXr59tONSY6y97FyiOHDkShRX1DqjHQLtffvjhh2gdceod0Tz1mJTrnldw0IGdWp/+4h4zZoz9i1qTCyXqydA813jFGzH14DjqpXGhQWFHf9lrWb2u3qMaTnHhQK/lN4h6ntahEPLaa6/ZST0UTrxnphb+9y3+/fjriXoW1Hgnpc+p9ep26dKl/mzLhTDRsuql0nfuek7KWb16tXn06FE0X+/X9U6pTKHAhUzX+yVjx461oVXl2n7c/4lT6fXq0epAIh31XAHoHEJJjsSP59BxHnHxee74BDU+TrkwIfFyNU4KMRs2bHjpGIdq3n33XRt41DMSd/36dXsbb9zc67399tu2kdO8AQMGlIQGhSmFmXLc89UwvvPOO1G5dj0oFGj3jqPjcLSbQbT7R2Hku+++M7/99lu0TK3877vcsSTx11PPTD3foc8doyHaPaUzknz+8T3xZc6fPx+bU537TvX/6HpNtIuwR48e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>