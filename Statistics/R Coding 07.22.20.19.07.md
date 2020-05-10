R Coding 07.22.20.19.07
========
@R


# The verbs of data manipulation

    Pick observations by their values (filter()).
    Reorder the rows (arrange()).
    Pick variables by their names (select()).
    Create new variables with functions of existing variables (mutate()).
    Collapse many values down to a single summary (summarise()).

These can all be used in conjunction with group_by() which changes the scope of each function from operating on the entire dataset to operating on it group-by-group. These six functions provide the verbs for a language of data manipulation.

All verbs work similarly:

    The first argument is a data frame.

    The subsequent arguments describe what to do with the data frame, using the variable names (without quotes).

    The result is a new data frame.

Together these properties make it easy to chain together multiple simple steps to achieve a complex result. Let’s dive in and see how these verbs work.

View ()

Filter uses boolean operators

! = not
& = "and"
| = "or"

Sometimes you can simplify complicated subsetting by remembering De Morgan’s law: !(x & y) is the same as !x | !y, and !(x | y) is the same as !x & !y. For example, if you wanted to find flights that weren’t delayed (on arrival or departure) by more than two hours, you could use either of the following two filters:

Missing values: is.na()

There are a number of helper functions you can use within select():

    starts_with("abc"): matches names that begin with “abc”.

    ends_with("xyz"): matches names that end with “xyz”.

    contains("ijk"): matches names that contain “ijk”.

    matches("(.)\\1"): selects variables that match a regular expression. This one matches any variables that contain repeated characters. You’ll learn more about regular expressions in strings.

    num_range("x", 1:3): matches x1, x2 and x3.

