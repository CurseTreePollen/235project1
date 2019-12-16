# Documentation

## Process (Project 1)
If you couldn't tell, my idea is fairly derivative of League of Legend's [Miss Fortune]("https://leagueoflegends.fandom.com/wiki/Miss_Fortune").  Back when I played League *a lot*, I liked her character, or at least the idea of a character like her, but I was less than satisfied with how she was in-game.  As such, my younger self went and thought about how I would design MF. That idea stayed around in my head, and when this project came around, I built off of it (specifically, my reimagined Double-Up, her primary ability) and came up with what I described in the proposal.  That said, this game is definitely going to focus only on that ricochet shot and the idea of hiding in plain sight.  No firing waves/hails of bullets.

On the note of Miss Fortune, the name of this may eventually be changed to "Miss Direction".

I am a little worried that I may have overscoped, but worst case scenario, I can change it into a pure puzzle game based on figuring out how to hit your target(s) with bouncing bullets.

As for the site, I used coolors.co to create a palette based on some colors I got from a color palette generator (returns the palettes of images it is given).  That palette ended up having some problems though, and had to get changed.  I think I found something that works now.

## Process (Project 3)
Well, in case you couldn't tell, what I have made is a LOT different from what I initially thought up.  I really wanted to make sure I did not overscope, especially after struggling with the last project, so I opted to go for a relatively simple SHMUP instead.

While I initially considered putting Miss Dir in the middle of the screen, and have the player strafe around enemies while hitting them with ricochets and blowing them up, I eventually came to the conclusion that this perspective seemed a bit too far away from my initial intention.

Instead of that, I decided to go with my other early idea, which involved Miss Dir (behind cover) fighting waves of approaching enemies.  I kind of thought of it as what would happen if her identity/mission was discovered.

One of the first things I did was to change the circle into enemies of my own creation (the blue mooks).  I had a different, worse sprite for them at the time, but their behavior was locked down fairly quickly.

After that, my focus was on getting the player moving.  I initially locked them to just moving on the x-axis, but I would later come up with the goal (maybe a better name would have been camp or shelter) and would instead let the player move freely within its bounds.

After that was the barrels, which was fairly easy.  At the time, I was still using the explosions from circle-blaster, so I scaled them up, removed them from enemies, and added a collision event between explosions and enemies.  I also created the skulls array, though it would be a while before I revisited it.  It was also called corpses at the time.

The next thing was getting the bullet to fire at the mouse.  To be honest, I had to ask the IGM tutors for help with this.  They have been a bloody godsend the past week (for anyone looking at this in the future, finals week), and they were able to help me fix the issues I was having (I could get it going the right direction OR have it travel past where I clicked).

From there, covers, the goal, and ricochet/reflectX() were all added with no real problems.  The only thing of note is that I let it ricochet twice instead of the initially planned once.  Thought it would help with later levels and make tricky shots easier.

The next thing I did was add more enemy types, starting with the green and red enemies.  All of the enemies pretty much have the same behavior as when I started, though I did initially have an issue where multi-health enemies would be instakilled if hit from below.  By adding straight(e) to the ally bullets I was able to just despawn the bullets if they hit from below, avoiding this issue. On the note of bullets, when I added the enemyBullets, I initially made a mistake that resulted in missDir firing them and killing herself.

The next thing I did was replacing and resizing the assets. Not much to say here other than I only remembered to replace the cursor reticle about 3 hours before this was due.

After this, all that was left was comment everything, improve some the ui (the text is much prettier now) and code, and center the game in my Project1 body.  I also decided to re-add the score to help encourage smartly ricocheting bullets over firing wildly.  That said, I hope I tuned it in a way that still encourages survival over optimization.

I hope you enjoy my game, and have a good day.

### Useful Sites
Project 1
* [HTML Validator](https://html5.validator.nu/)
* [CSS Validator](https://jigsaw.w3.org/css-validator/)
* [Color Palette Creator](https://coolors.co/)
* [Color Palette Generator](http://www.cssdrive.com/imagepalette/index.php)
* [w3schools.com (HTML Review)](https://www.w3schools.com/)
* [Context for what Mark of the Ninja is Like](https://www.klei.com/games/mark-ninja)
* [More context for Miss Fortune](https://na.leagueoflegends.com/en/site/bilgewater/#story-2-part-3). My idea has deviated from its inspiration (even if it doesn't totally show in this little game).

Project 3
* [freesounds.org (Where I got my sounds)](https://freesound.org/)
* [JS Validator](https://esprima.org/demo/validate.html)

### Image Sources
Project 1
* [Home Page Image](https://fire-force.fandom.com/wiki/Ricochet_Control)
* [Double-Up Image](https://www.youtube.com/watch?v=gZ4QiB-epAE)
* Placeholder Game Image: My personal creation. Beauty incarnate.

Project 3
All of the images are of my own creations.  Sounds on the other hand...
* [ricochet-woodAttrib.wav](https://freesound.org/people/CGEffex/sounds/96636/).  All 5 sound names are different from their originals.
* The above is by CGEffex and licensed under the Creative Commons attribution license.
* [fireExplo.wav](https://freesound.org/people/HighPixel/sounds/431174/)
* [gunshot.wav](https://freesound.org/people/Shades/sounds/37236/)
* [hitsound.mp3](https://freesound.org/people/Raclure/sounds/458867/)
* [manOuch.wav](https://freesound.org/people/Under7dude/sounds/163441/)

### Current Palette (Project 1)
![Picture of the 5 colors used on this site]("media/c6532f-dddddd-483526-514d5e-891b13.png" "Picture of the 5 colors used on this site")

### Links
[Home Page](index.html)

[Game Treatment/Proposal](proposal.html)

[Documentation](documentation.html)

[Project](project.html)
