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

need to use windows powershell with run on adminstrator
https://youtu.be/jGwD3e1BZ5Y

# to clone:
Original (Uses default account): git clone git@github.com:USERNAME/idontknow.git
Specific USER1 account: git clone git@USER1.github.com:USERNAME/idontknow.git
Specific USER2 account: git clone git@USER2.github.com:USERNAME/idontknow.git

# after cloning, change the config file in the repository
update the url in the remote origin to have the updated url -- git@USER2.github.com   etc..

# also add to config file in the repository
[user]
    name = GITHUB_USERNAME
    email = EMAIL@gmail.com