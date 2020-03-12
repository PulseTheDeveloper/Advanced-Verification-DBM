# Advanced-Verification-DBM

These are the raw data files for a verification system inside Discord Bot Maker
simply copy the rad data from each of the four files and create a new command
in Discord Bot Maker. Right click the enw command and select edit raw data and
paste the raw data i provided. Do this three more times for each command.

Step One: Making !verify Command Work
1) Change Action #8 (Find Role) - Add the Role ID for the role you want them to receive.

Step Two: Making !verifymember Command Work
1) Change Action #1 (Find Role) - Add the Role ID for the role you want them to receive. (Same from Step One)

Step Three: Making the Category
1) Do !setupcategory and it will make the category!

Step Four: Making the !setupchannel work!
1) Change Action #4 (Create Text Channel) - Copy the ID of the category
that was just created and paste it into "Category ID".
2) Change Action #5 (Find Role) - Replace the ID in "Search Value" to the role ID for @everyone in your discord.
3) Change Action #5 (Find Role) - Replace the ID in "Search Value" to the role ID for the verified role in your discord.
4) Do setupchannel and it will make the channel with the permission setup!

Channel Permission: (This will work even better with an anti invite event)
(Everyone): Can read/send. Cannot read message history.
(Verified) Cannot read/send
