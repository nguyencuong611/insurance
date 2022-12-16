# insurance
##practice on class

unique(movie$content_rating) #to look at unique values of certain variable

is.na(movie$budget)

## filter
movie2010 = filter(movie, title_year>=2010)
movie2010_R=filter(movie, title_year>=2010, content_rating=="R")
movie2010_R_PG13 = filter(movie, title_year>=2010, content_rating%in%c("R", "PG-13"))

