# yet-another-qb-reader
This program of mine will join the ever-growing list of quizbowl question readers out there. I decided to try and combine tossup readers like Protobowl and QuizBug and bonus readers like pkbot to create an all-in-one solo studying program for reading questions. 

More specifically, I plan to use the QuizDB database in order to access questions, then use simple Python GUI functions in order to have the program display the words one at a time. I plan on giving the tossups the same functionality as in protobowl and likewise with bonuses and pkbot, except for the fact that pkbot has a helpful function where even if the program may not initially detect your answer as being correct you can still say that you did in fact get it right, so I plan on giving the tossups this functionality alongside typo correction/spellcheck. 
## Keybinds
### Select Questions Window
`Enter` → [Go]

`Esc` → [Quit]

### Question Window
`]` → [Next/Skip]

`Space` → [Buzz]

`Enter` → [Enter]

`Esc` → [Quit]

## How to use
When the program is run, you will be prompted with a screen asking for inputs on what categories you want, difficulties, etc. Use the dropdown menus to select your options. There are also options for changing the time interval between words and whether you want tossups only, bonuses only, or tossups and bonuses. 

### Tossups
When you start the reading, the program will read the tossup one word at a time. The [Next/Skip] button stays enabled in case you want to skip tossups. The [Buzz] button will be enabled so that you can buzz in, and when you do, it disables itself and the [Next/Skip] button, and enables the text entry box, and a timer for 8 seconds. When you have finished typing, hit the [Enter] button and the program should either display the tossup and the correct answer or prompt you with a message asking whether your provided answer was correct. Once this happens, you should see that your number of tossups you've heard, number of tossup points, points per 20 tossups heard, and your powers/10s/negs ratio will have updated. When you have run out of tossups, everything will be disabled, but you will see your stats. 
### Bonuses
When you start the reading, the program will read the bonus one word at a time. The [Next/Skip] button stays enabled in case you want to skip entire bonuses. The [Buzz] button will be disabled so that you cannot buzz in, but the text entry and [Enter] have been enabled so you can simply type in as the question is being read and submit any time the bonus is being read. There will be a 10 second timer at the end when it reads each part of the bonus, in case you choose to answer after the question has finished. When you have finished typing, hit the [Enter] button and the program should either display the part of the bonus and the correct answer or prompt you with a message asking whether your provided answer was correct. Each time you complete a part of the bonus it will display all the previous parts of that bonus above the current bonus. After you have completed all 3 parts of the bonus, you should see that your number of bonus you've heard, number of bonus points, points per bonus, and your 30s/20s/10s/0s ratio will have updated. When you have run out of bonuses, everything will be disabled, but you will see your stats. 
### Tossups and Bonuses
This option basically has the same functionality as tossups and bonuses, just combined. I've made it such that even if you may have gotten a tossup wrong you will still be read a bonus after it, because I have the program simply alternate between tossups and bonuses. 
