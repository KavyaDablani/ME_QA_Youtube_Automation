# Project Name - ME_QA_Youtube_Automation
```
## Project Description:
Automate the youtube and check the About Section,  Films, Music and News tab. 
```
## Installation Instructions:
Clear steps to set up and run the project locally.
> git clone https://github.com/KavyaDablani/ME_QA_Youtube_Automation.git
```
# java version 17
java --version
```

## Test Cases:
1. Go to YouTube.com and Assert you are on the correct URL. Click on “About” at the bottom of the sidebar, and print the message on the screen.

2. Go to the "Movies" tab and in the “Top Selling” section, scroll to the extreme right. Apply a Soft Assert on whether the movie is marked “A” for Mature or not. Apply a Soft assert on whether the movie is either “Comedy” or “Animation”.

3. Go to the “Music” tab and in the 1st section, scroll to the extreme right. Print the name of the playlist. Soft Assert on whether the number of tracks listed is less than or equal to 50.

4. Go to “News” tab and print the title and body of the 1st 3 “Latest News Posts” along with the sum of number of likes on all 3 of them. No likes given means 0.
```

# to run the project
./gradlew build
./gradlew test
```

