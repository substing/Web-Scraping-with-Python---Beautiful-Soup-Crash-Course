# Web-Scraping-with-Python---Beautiful-Soup-Crash-Course
course by [Free Code Camp](https://www.youtube.com/watch?v=XVv6mJpFOb0)


## part1.py
Basic program that read from `home.html`.

## part2.py
More complex, reads through job listings for Python jobs. Asks the user for skills they are not comfortable with. Filters out jobs that require this skill, and filters out jobs that have been poster more than a few days prior. 

All such jobs are written into a file called posts as short `.txt` files. 

### Places for improvement
The input form that asks for unfamiliar skills only takes one skill. It could be expanded to two or more. 

The input form also does not account for capitalization, and this could be added on. Likely the most pythonic solution to this would be to use `.lower()` on all the skill listings, and then `.lower()` on the input itself. 

Because `part2.py` needs to write its data in a `posts` file, it may be a good idea to use the operating system to create a `posts` file in the same directory as the python scripts. If this is not done, the script can still be used by manually creating a `posts` file. 
