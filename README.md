# cp2-fa19-final-project
For my final project I wanted to do something like a game and I burned through a few different ideas.

1. The first was a game with a punching bag where your punching speed is calculated by tracking your position on pose net. The issue I had here was that the way I was testing it was making it difficult for pose to understand where my fist was so I moved on to a different project.

2. The second project was a game where you have to keep your nose within the bounds of a circle that moves randomly across the screen. I did some basic code but did not want to continue with it as I wasn't into it.

3. After I found out about teachable machine by google I wanted to do a project with it and my idea was to make a game with motion controls. I trained the model to learn up, down, left, right, and then nothing for some background video. Then I trained it again to tweak the accuracy (eg, even pointing your head slightly to the left would count as left) Then I found a game where blocks are falling from the top and modified the number of bloacks, speed, player size, and canvas size to make it easier to use with motion controls. The issue I had with this project was making teachbale machine (TM) work with p5. The tutorials I looked at from code train used an older version of TM which worked with m5 and when I tried the same thing with my model it failed. I got my model to work with some code on glitch.io however glitch uses a different version of js that would require me to redo the code I had written earlier. Unfortunately by then I had run out of time.
