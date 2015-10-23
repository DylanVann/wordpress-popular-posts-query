# Wordpress Popular Posts Query

Allows you to use WP_Query with orderby set to popular.

The problem with most Wordpress popular posts plugins is that they're widgets, they provide their own query methods, and their own templating methods. They're not flexible and getting them to look and work the way you want is a bigger hassle than it needs to be.

WPPQ let's you pass in normal WP_Query args, with orderby set to one of the following:

- popular
- popular-daily
- popular-weekly
- popular-monthly
- popular-yearly
- popular-custom
    - start
    - end

Then you've got your list of popular posts and you can do whatever you want with them. You could make your own popular posts widget using standard functions to display the information you want from the posts, or you could create archive pages sorted by popularity.
