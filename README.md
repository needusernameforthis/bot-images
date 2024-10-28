use gallery-dl

gallery-dl <url> --write-metadata -o skip=true --sleep 1

Use the 3 different stuff, if it doesnt download everything the first time
https://www.twitter.com/<user>
https://www.twitter.com/<user>/media
https://twitter.com/search?q=from:<user>

The config is at C:\Users\Gelo\gallery-dl


https://www.reddit.com/r/DataHoarder/comments/yy8o9w/for_everyone_using_gallerydl_to_backup_twitter/

https://github.com/mikf/gallery-dl/blob/master/docs/options.md

-----------
## I now have multiple github accounts with ssh keys

https://youtu.be/jGwD3e1BZ5Y

# to clone:
Original (Uses default account): git clone git@github.com:MarkGelo/idontknow.git
Specific mlgameng account: git clone git@mlgameng.github.com:MarkGelo/idontknow.git
Specific geloprojects account: git clone git@geloprojects.github.com:MarkGelo/idontknow.git

# after cloning, change the config file in the repository
update the url in the remote origin to have the updated url -- git@geloprojects.github.com   etc..

# also add to config file in the repository
[user]
    name = needusernameforthis
    email = geloprojects@gmail.com