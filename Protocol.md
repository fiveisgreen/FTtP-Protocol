Protocol version 0.1

# Protocol Checklist
- [ ] Open a spreadsheet program
- [ ] Set up whatever condensing particle counter you're using with a new alcohol cartridge.
- [ ] Install the probe in the mask (see @toba‘s vid)
- [ ] Turn the CPC machine on 
- [ ] If your mask has a nosewire, preform the nosewire with your thumbs.
- [ ] Put the mask on. 
- [ ] If the mask uses a nosewire, pinch it again to tighten it
- [ ] Don’t wait for the mask to purge - start collecting data now!
- [ ] No touching the mask after the exercises start.

## Exercise 1
- [ ] Start with talking or singing! 

Yes, this is the opposite of OSHA. 
If you can’t think of a song, use this long paragraph of instructions or The Rainbow Passage (see Resources section). 
The computer vision display will let you know if you moved your jaw enough. (If no computer vision setup is available, see the master branch.)
**Don’t mumble. TRY to crash the score.** (If you *fail* to crash it, the mask is good. )
Some good masks will fail, but this ensures that only good masks will pass. 
The priority is the user’s safety, not protecting the ego of the mask company.

- [ ] When you hear the beep mid-song/passage, type the number you see into the spreadsheet 
- [ ] continue vocalizing

## Exercise 2
- [ ] Continue with talking or singing right through.
- [ ] When you hear the beep, stop vocalizing
- [ ] type the number you see into the spreadsheet.

## Exercise 3
- [ ] Relax and check your phone for notifications. This is to give the mask time to reseal. 
You can choose to move your head however you want or not. (The previous exercise is already a big enough challenge). 
- [ ] Type in the result

## Exercise 4
- [ ] Repeat of exercise 3

## Exercise 5
- [ ] Same as last two except you’re trying to touch your chin to your chest
* Beep. That’s it
- [ ] Type in the last number. 

## Data Processing
Go to a blank cell and type 
= HARMEAN(
Select all the numbers
Close parentheses )
Enter

That number should be within an order of magnitude of you actual exposure reduction.

Double digits is great. Triple digits is better. Four digits is overkill.

## Computer Vision component
The computer vision part checks that jaw motion during speech is between a certain threshold, probably at least 2cm of amplitude. Challenging enough to dislodge bad seals while also being a realistic upper bound for normal speech.
![Screenshot of the Dotdiff computer vision tool in use](/cv_screenshot_4md.jpg)

# Notes
Speech increases particle count compared to just jaw motion. 
That’s fine. It always biases the score down, away from overpromising. 
If the speech generated particle count is meaningfully affecting your score, you’re already getting good protection and should focus on other things.
If none of your masks do well, pick the highest and keep an eye out for a better one.

# Resources
* The [Dotdiff](https://github.com/fiveisgreen/Dotdiff/blob/main/helloworld.py) computer vision tool.
* This version is taken from FTtP's thread [here](https://twitter.com/FitTestMyPlanet/status/1660484149344337920?s=20)
* [@toba's port installation video ](https://twitter.com/toba/status/1656825931971850240?s=20)
  - Note that the ring must be installed in the magnetic holder with the concave side up (convex side touching touching the magnet.)
  - Note that the spike must be inserted from the inside center of the mask. 
* [The Rainbow Passage](https://www.york.ac.uk/media/languageandlinguistics/documents/currentstudents/linguisticsresources/Standardised-reading.pdf)
