File: Pandas/obesity.py
Error:
print  data.sheet_names
              ^
SyntaxError: Missing parentheses in call to 'print’

# Adding parentheses resolved this issue.

File: Pandas/pandas_movie.py
Error: (found on line 19)
print "Top rated movies (overall): \n" , movie_data.groupby('title').size().order(ascending=False)[:20]
                                         ^
SyntaxError: invalid syntax
