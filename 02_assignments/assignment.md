## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `11:59 PM - 27/04/2024`
* The branch name for your repo should be: `assignment`
* What to submit for this assignment:
    * This markdown file (assignment.md) should be populated and should be the only change in your pull request.
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/shell/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

# Assignment: The Secret Password

You are stuck in a virtual room and can only leave if you figure out the password! Fortunately, somebody left behind 6 clues for you to find the secret password, but the messaging is not that clear. It is your job to discover what the secret password is!

1. The very odd and inedible ingredient in a cake recipe
2. The season number that contains only 18 episodes (Hint: How do you list them?)
3. Fifth word of Season 6, Episode 21 of Friends
4. Fifth word of the fifth fictional Space Wars series
5. Second word of this song that's exactly 4 minutes long in this "colour" album
6. The fourth word to the fourth Hunger Games movie

## Instructions
1. Fork this Shell learning module repository following these [instructions](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#setting-up)
2. Use your bash skills (such as `cd`, `cat`, etc.) to figure out what the secret password is! You will be exploring the `clues` directory in your bash terminal.
3. Write the secret password in your own version of this markdown file in your forked repo.

**What is the secret password?**
```
Your answer here...
My answers: 
@dtxe
@michaeladrouillard
1. The very odd and inedible ingredient is 'Paper Rings'
here is the flow from my bash terminal:
skiev@Serhiy_Laptop MINGW64 ~/shell (assignment)
$ cd 02_assignments
(base) 
skiev@Serhiy_Laptop MINGW64 ~/shell/02_assignments (assignment)
$ ls
assignment.md  clues/
(base) 
skiev@Serhiy_Laptop MINGW64 ~/shell/02_assignments (assignment)
$ cd clues
(base) 
skiev@Serhiy_Laptop MINGW64 ~/shell/02_assignments/clues (assignment)
$ ls
albums/  food/  movies/  shows/
(base) 
skiev@Serhiy_Laptop MINGW64 ~/shell/02_assignments/clues (assignment)
$ cd food
(base) 
skiev@Serhiy_Laptop MINGW64 ~/shell/02_assignments/clues/food (assignment)
$ ls
cake/
(base) 
skiev@Serhiy_Laptop MINGW64 ~/shell/02_assignments/clues/food (assignment)
$ cd cake
(base) 
skiev@Serhiy_Laptop MINGW64 ~/shell/02_assignments/clues/food/cake (assignment)
$ ls
chocolate_cake.txt  red_velvet_cake.txt  vanilla_cake.txt
(base) 
skiev@Serhiy_Laptop MINGW64 ~/shell/02_assignments/clues/food/cake (assignment)
$ cat chocolate_cake.txt  red_velvet_cake.txt  vanilla_cake.txt
Milk
Cake Flour
Eggs
Cocoa Powder
Dark Chocolate
Baking Powder
Sugar
Vanilla Extract
Butter
Baking Powder
Milk
Vanilla Extract
Red Food Colouring
Eggs
Cocoa Powder
Sugar
Butter
Cake Flour
Milk
Sugar
Baking Powder
Cake Flour
Eggs
Butter
Vanilla Extract
Paper Rings
(base) 
skiev@Serhiy_Laptop MINGW64 ~/shell/02_assignments/clues/food/cake (assignment)
$
-------------------------------------------------------------------------------------------------------------------------------
2. The season number is season_10 that contains only 18 episodes.
Here is the copy of my bash terminal requests:
skiev@Serhiy_Laptop MINGW64 ~/shell/02_assignments/clues (assignment)
$ ls
albums/  food/  movies/  shows/
(base)
skiev@Serhiy_Laptop MINGW64 ~/shell/02_assignments/clues (assignment)
$ cd shows
(base)
skiev@Serhiy_Laptop MINGW64 ~/shell/02_assignments/clues/shows (assignment)
$ ls
friends/
(base)
skiev@Serhiy_Laptop MINGW64 ~/shell/02_assignments/clues/shows (assignment)
$ cd friends
(base)
skiev@Serhiy_Laptop MINGW64 ~/shell/02_assignments/clues/shows/friends (assignment)
$ ls
season_1/  season_10/  season_2/  season_3/  season_4/  season_5/  season_6/  season_7/  season_8/  season_9/
(base)
skiev@Serhiy_Laptop MINGW64 ~/shell/02_assignments/clues/shows/friends (assignment)
$ ls -1q season_1 season_2 season_3 season_4 season_5 season_6 season_7 season_8 season_9 season_10
season_1:
ep_1.txt 
ep_10.txt
ep_11.txt
ep_12.txt
ep_13.txt
ep_14.txt
ep_15.txt
ep_16.txt
ep_17.txt
ep_18.txt
ep_19.txt
ep_2.txt
ep_20.txt
ep_21.txt
ep_22.txt
ep_23.txt
ep_24.txt
ep_3.txt
ep_4.txt
ep_5.txt
ep_6.txt
ep_7.txt
ep_8.txt
ep_9.txt

season_10:
ep_1.txt
ep_10.txt
ep_11.txt
ep_12.txt
ep_13.txt
ep_14.txt
ep_15.txt
ep_16.txt
ep_17.txt
ep_18.txt
ep_2.txt
ep_3.txt
ep_4.txt
ep_5.txt
ep_6.txt
ep_7.txt
ep_8.txt
ep_9.txt

season_2:
ep_1.txt
ep_10.txt
ep_11.txt
ep_12.txt
ep_13.txt
ep_14.txt
ep_15.txt
ep_16.txt
ep_17.txt
ep_18.txt
ep_19.txt
ep_2.txt
ep_20.txt
ep_21.txt
ep_22.txt
ep_23.txt
ep_24.txt
ep_3.txt
ep_4.txt
ep_5.txt
ep_6.txt
ep_7.txt
ep_8.txt
ep_9.txt

season_3:
ep_1.txt
ep_10.txt
ep_11.txt
ep_12.txt
ep_13.txt
ep_14.txt
ep_15.txt
ep_16.txt
ep_17.txt
ep_18.txt
ep_19.txt
ep_2.txt
ep_20.txt
ep_21.txt
ep_22.txt
ep_23.txt
ep_24.txt
ep_25.txt
ep_3.txt
ep_4.txt
ep_5.txt
ep_6.txt
ep_7.txt
ep_8.txt
ep_9.txt

season_4:
ep_1.txt
ep_10.txt
ep_11.txt
ep_12.txt
ep_13.txt
ep_14.txt
ep_15.txt
ep_16.txt
ep_17.txt
ep_18.txt
ep_19.txt
ep_2.txt
ep_20.txt
ep_21.txt
ep_22.txt
ep_23.txt
ep_24.txt
ep_3.txt
ep_4.txt
ep_5.txt
ep_6.txt
ep_7.txt
ep_8.txt
ep_9.txt

season_5:
ep_1.txt
ep_10.txt
ep_11.txt
ep_12.txt
ep_13.txt
ep_14.txt
ep_15.txt
ep_16.txt
ep_17.txt
ep_18.txt
ep_19.txt
ep_2.txt
ep_20.txt
ep_21.txt
ep_22.txt
ep_23.txt
ep_24.txt
ep_3.txt
ep_4.txt
ep_5.txt
ep_6.txt
ep_7.txt
ep_8.txt
ep_9.txt

season_6:
ep_1.txt
ep_10.txt
ep_11.txt
ep_12.txt
ep_13.txt
ep_14.txt
ep_15.txt
ep_16.txt
ep_17.txt
ep_18.txt
ep_19.txt
ep_2.txt
ep_20.txt
ep_21.txt
ep_22.txt
ep_23.txt
ep_24.txt
ep_25.txt
ep_3.txt
ep_4.txt
ep_5.txt
ep_6.txt
ep_7.txt
ep_8.txt
ep_9.txt

season_7:
ep_1.txt
ep_10.txt
ep_11.txt
ep_12.txt
ep_13.txt
ep_14.txt
ep_15.txt
ep_16.txt
ep_17.txt
ep_18.txt
ep_19.txt
ep_2.txt
ep_20.txt
ep_21.txt
ep_22.txt
ep_23.txt
ep_24.txt
ep_3.txt
ep_4.txt
ep_5.txt
ep_6.txt
ep_7.txt
ep_8.txt
ep_9.txt

season_8:
ep_1.txt
ep_10.txt
ep_11.txt
ep_12.txt
ep_13.txt
ep_14.txt
ep_15.txt
ep_16.txt
ep_17.txt
ep_18.txt
ep_19.txt
ep_2.txt
ep_20.txt
ep_21.txt
ep_22.txt
ep_23.txt
ep_24.txt
ep_3.txt
ep_4.txt
ep_5.txt
ep_6.txt
ep_7.txt
ep_8.txt
ep_9.txt

season_9:
ep_1.txt
ep_10.txt
ep_11.txt
ep_12.txt
ep_13.txt
ep_14.txt
ep_15.txt
ep_16.txt
ep_17.txt
ep_18.txt
ep_19.txt
ep_2.txt
ep_20.txt
ep_21.txt
ep_22.txt
ep_23.txt
ep_24.txt
ep_3.txt
ep_4.txt
ep_5.txt
ep_6.txt
ep_7.txt
ep_8.txt
ep_9.txt
(base) 
skiev@Serhiy_Laptop MINGW64 ~/shell/02_assignments/clues/shows/friends (assignment)
$
-------------------------------------------------------------------------------------------------------------------
3. Fifth word of Season 6, Episode 21 is 'Meets'
Here is bash terminal requests:
skiev@Serhiy_Laptop MINGW64 ~/shell/02_assignments/clues/shows (assignment)
$ cd friends
(base) 
skiev@Serhiy_Laptop MINGW64 ~/shell/02_assignments/clues/shows/friends (assignment)
$ ls
season_1/  season_10/  season_2/  season_3/  season_4/  season_5/  season_6/  season_7/  season_8/  season_9/
(base) 
skiev@Serhiy_Laptop MINGW64 ~/shell/02_assignments/clues/shows/friends (assignment)
$ cd season_6
(base) 
skiev@Serhiy_Laptop MINGW64 ~/shell/02_assignments/clues/shows/friends/season_6 (assignment)
$ ls
ep_1.txt   ep_11.txt  ep_13.txt  ep_15.txt  ep_17.txt  ep_19.txt  ep_20.txt  ep_22.txt  ep_24.txt  ep_3.txt  ep_5.txt  ep_7.txt  ep_9.txt
ep_10.txt  ep_12.txt  ep_14.txt  ep_16.txt  ep_18.txt  ep_2.txt   ep_21.txt  ep_23.txt  ep_25.txt  ep_4.txt  ep_6.txt  ep_8.txt
(base) 
skiev@Serhiy_Laptop MINGW64 ~/shell/02_assignments/clues/shows/friends/season_6 (assignment)
$ cat ep_21
cat: ep_21: No such file or directory
(base) 
skiev@Serhiy_Laptop MINGW64 ~/shell/02_assignments/clues/shows/friends/season_6 (assignment)
$ cat ep_21.txt
The One Where Ross Meets Elizabeth's Dad
(base) 
----------------------------------------------------------------------------------------------------------------------
4. Fifth word of the fifth fictional Space Wars series is 'and'
Here is the bash terminal requests:
skiev@Serhiy_Laptop MINGW64 ~/shell/02_assignments/clues (assignment)
$ ls
albums/  food/  movies/  shows/
(base) 
skiev@Serhiy_Laptop MINGW64 ~/shell/02_assignments/clues (assignment)
$ cd movies
(base) 
skiev@Serhiy_Laptop MINGW64 ~/shell/02_assignments/clues/movies (assignment)
$ ls
hanger_games/  space_wars/
(base) 
skiev@Serhiy_Laptop MINGW64 ~/shell/02_assignments/clues/movies (assignment)
$ cd space_wars
(base) 
skiev@Serhiy_Laptop MINGW64 ~/shell/02_assignments/clues/movies/space_wars (assignment)
$ ls
fifth_movie.txt  first_movie.txt  fourth_movie.txt  second_movie.txt  third_movie.txt
(base) 
skiev@Serhiy_Laptop MINGW64 ~/shell/02_assignments/clues/movies/space_wars (assignment)
$ cat fifth_movie.txt 
Space Wars: Future Legends and Past Legacies
(base) 
skiev@Serhiy_Laptop MINGW64 ~/shell/02_assignments/clues/movies/space_wars (assignment)
$
-----------------------------------------------------------------------------------------------------------
5. Second word of the song in the 'red' album that is exactly 4 minutes long is 'Lucky'.
Here is the bash terminal requests:
skiev@Serhiy_Laptop MINGW64 ~/shell/02_assignments/clues (assignment)
$ ls
albums/  food/  movies/  shows/
(base) 
skiev@Serhiy_Laptop MINGW64 ~/shell/02_assignments/clues (assignment)
$ cd albums
(base) 
skiev@Serhiy_Laptop MINGW64 ~/shell/02_assignments/clues/albums (assignment)
$ ls
fearless/  lover/  red/
(base) 
skiev@Serhiy_Laptop MINGW64 ~/shell/02_assignments/clues/albums (assignment)
$ cd red
(base) 
skiev@Serhiy_Laptop MINGW64 ~/shell/02_assignments/clues/albums/red (assignment)
$ ls
song_1.txt  song_2.txt  song_3.txt  song_4.txt  song_5.txt
(base) 
skiev@Serhiy_Laptop MINGW64 ~/shell/02_assignments/clues/albums/red (assignment)
$ cat song_1.txt  song_2.txt  song_3.txt  song_4.txt  song_5.txt
Title: Red
Duration: 3:43
Title: I Knew You Were Trouble
Duration: 3:39
Title: Everything Has Changed
Duration: 4:05
Title: Holy Ground
Duration: 3:22
Title: The Lucky One
Duration: 4:00
(base) 
skiev@Serhiy_Laptop MINGW64 ~/shell/02_assignments/clues/albums/red (assignment)
$ cat song_5.txt
Title: The Lucky One
Duration: 4:00
(base) 
skiev@Serhiy_Laptop MINGW64 ~/shell/02_assignments/clues/albums/red (assignment)
$
-------------------------------------------------------------------------------------------------
6. The fourth word to the fourth Hunger Games movies is 'Stars'.
Here is the the bash terminal requests:
skiev@Serhiy_Laptop MINGW64 ~/shell/02_assignments/clues (assignment)
$ ls
albums/  food/  movies/  shows/
(base) 
skiev@Serhiy_Laptop MINGW64 ~/shell/02_assignments/clues (assignment)
$ cd movies
(base) 
skiev@Serhiy_Laptop MINGW64 ~/shell/02_assignments/clues/movies (assignment)
$ ls
hanger_games/  space_wars/
(base) 
skiev@Serhiy_Laptop MINGW64 ~/shell/02_assignments/clues/movies (assignment)
$ cd hanger_games
(base) 
skiev@Serhiy_Laptop MINGW64 ~/shell/02_assignments/clues/movies/hanger_games (assignment)
$ ls
movie_1.txt  movie_2.txt  movie_3.txt  movie_4.txt
(base) 
skiev@Serhiy_Laptop MINGW64 ~/shell/02_assignments/clues/movies/hanger_games (assignment)
$ cat movie_4.txt
Hanger Games & the Stars of Darkness
(base) 
skiev@Serhiy_Laptop MINGW64 ~/shell/02_assignments/clues/movies/hanger_games (assignment)
$

```

|Criteria|Complete|Incomplete|
|---|---|---|
|Secret Password|The user properly used the proper bash commands to find the secret password.|The user did not properly used the proper bash commands to find the secret password.|



If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack at `#cohort-3-help`. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
