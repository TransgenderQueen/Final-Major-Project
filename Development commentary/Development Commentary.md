## Project Outline


This project will be an upgrade of my original prototype. This is based on similar souls-like games, mixed with elements from styles of games like dungeon crawlers, while including elements of weapon crafting. There are many things I wish to include in this project that will have improved since the prototype:


- Weapon crafting system
- Multiple distinct weapon types
- Updated animations and art and design for the world
- More dungeons, with ranging difficulty due to more enemies or bosses.


There are a few things I know I will have an issue with. I am not the most confident in my level of design skills, so I know I will need to do a lot of research on how people feel about art and design.


I additionally have not dabbled with audio before, so setting it up will be a big challenge for me, though I am confident with enough practice and testing I can get it set up.


Ultimatly I am not too worried for this. With a lot of user testing and constant feedback I can fine tune this project.




## Research


### Methodology


So, what I ended up looking into was Agile methodology, specifically the idea of using sprints to break down progress into manageable chunks. The goal was to keep the development process iterative, so instead of trying to build everything all at once, I’d focus on small, incremental improvements and just keep looping back to the start after each sprint to refine things. It’s all about making consistent progress and being flexible with how things evolve, which seemed like a smart way to avoid getting stuck or overwhelmed.


On top of that, I also took some inspiration from a game called Star Citizen(Roberts Space Industries | Follow the development of Star Citizen and Squadron 42 - Roberts Space Industries | Follow the development of Star Citizen and Squadron 42, s.d.).
The way they approach development is by releasing small patches that gradually add more content over time, rather than trying to do everything at once. It’s a slower, more steady process, but it works for them. I thought this approach could work well for my project too—pushing out small updates regularly, instead of waiting until everything is “perfect.” This was the core of my methodology: a steady, ongoing push forward that builds up over time.


---

<br>


### Game Sources


The first game is Mount and Blade: Bannerlord II(Mount&Blade II Bannerlord - TaleWorlds Entertainment, s.d.). The crafting system in the weapons is quite in-depth. The higher the weapon you wish to craft, the rarer the recourses to craft it becomes.


 - I am looking at this game as I heard that people really enjoyed the crafting system, especially as it felt fun to use.


 - The game focuses on allowing you to craft parts of a weapon at a time before adding it all together. For example a dagger head and small hilt and handle would become a dagger, or a rake head and long pole would become a pike. It allows for fun combonations that get more and more intersting.


 - This is a unique way to have a weapon crafting system as it allows for a lot of flexibility and custom weapons. Players get greater satisfaction from having their own crafted weapons.
 - This is useful for my own game as I wish to have a crafting system like this. I want to replicate the part of the system that allows you to combine different weapon blades and handles. It will be fun for players to craft weapons and play around with different ranges and attack speeds.
 - I do not want to replicate all of it however. I do not wish to include weapon teirs or cosmetics, I will have similar things in the game that would work better for my specific system.


<br>


Additionally, I have also looked at Vault Hunters. This is a Minecraft modpack which focuses on dungeon running. Inside the Vaults, you can find weapons and items that can allow you to change current weapons.


- I like the design of the game that forces you to explore and keep trying untill you gain an item.
- It ensures the player has to try and try in order to and gain what they want in order to potentially uprade their weapons. This means that the player will constantly play to get better.
- I will not copy everything from this game, as that would be far too unoriginal. In my game, I wish to take ideas from this system. For example, items to reset the stats of weapons. When made in combination with the ideas from Mount and Blade: Bannerlord II(Mount&Blade II Bannerlord - TaleWorlds Entertainment, s.d.), it shall end up as an interesting system


### Academic Sources


### Documentation Sources
 CITE THIS A LOT

So, one of the best finds during development was this video on getting gamepads to work with menus. I had been scratching my head over how to implement gamepad support in a way that felt natural for navigating through menus, and it was an issue I couldn't figure out how to solve. But after searching, I came across this video, and it was an immediate help. It broke everything down step by step, covering all the little details I’d missed, and it instantly solved a massive problem I had.


Not only did it save me a ton of time, but it gave me a better understanding of how to handle user input more intuitively. I had been thinking about this feature for a while but wasn't sure how to approach it—this video just laid it out in such a simple, clear manner. It was like a lightbulb moment. I was able to implement the solution right away, and it felt satisfying to see it all come together. Sometimes the right resource at the right time can make all the difference, and that video was one of those moments for me.
Crafting System Video:


Then, I came across another video that was all about building crafting systems in games, which was pretty eye-opening. I was already thinking about how I wanted crafting to work in my game, but this video showed me some interesting techniques and design patterns that I hadn’t considered. Even though I didn’t end up using the exact system they were showing, it gave me tons of new ideas about how to approach it.


What was cool about it was that it got me thinking beyond the basic crafting mechanic. I started brainstorming ways to make the system feel more dynamic—things like adding more layers of customization, different materials, or ways to integrate crafting into the larger game world. The video gave me the tools to think about crafting not just as a standalone feature, but as something that could add depth to the overall experience.


Ultimately, I didn’t implement the system as shown in the video, but it helped shape how I designed my approach. Sometimes, it’s not about directly using the ideas you see but rather using them as inspiration to spark your own unique solutions. And that’s exactly what this video did for me—it expanded my thinking and helped me refine my own vision for the crafting system.


---


## Implementation


### Process
For my project, I needed to create a system that allowed me to reroll for weapons stats. This meant that I needed to call only a certain part of the system that created the stats while ignoring the system that allowed the rarity of the weapons and weapon type.


(Insert image here)
<br>
However, as I went to create the system that did it, I noticed a lot of issues with the original system. When making a weapon, it would start the stat system before then deciding what weapon type and rarity it was. This was increadibly inefficent and after plenty of testing, it would often not work correctly, having different outcomes roughly about 70% of the time.


Eventually I came up with a final outcome. I had to reorginize the system. I needed to put the weapon rarity and type before any other systems began to work.




### New Approaches  


### Testing

This was my favorite part of making my game. I always enjoy seeing people try out my game. For three of the tests I sat in the rooom with them as they tested what I had. This was during spint weeks 5-6

- Each of the testers instantly began to ask me what to do as soon as they loaded into the game. I told them to read the text.
- They all began by instantly testing the weapons, using the attacks and abilities. First peice of feedback was that the weapon animations were fun.
- The next peice of information they all had for me was that they all enjoyed the goofieness of the enemies sliding across the floor. Though one mentioned that it was annoying they didnt have walking animations.


### Later testing

<br>



![alt text](https://raw.githubusercontent.com/TransgenderQueen/Final-Major-Project/refs/heads/main/Development%20commentary/Testing%20Image%201-1.png)

<br>

### Technical Difficulties

During this project, I had come up with plenty of new ideas, begining to build them up as blueprints.
However, as I continued to work on the project, I found myself hating the project more and more, being unable to work on it. As I looked at what I had made, i found myself hating it. But I eventually couldnt deal with what I worked on and deleted it all in anger. This was not a good idea, as it meant I had lost a considerable amount of work.
However, this meant I could go back and work on everything from a fresh start, learning from my mistakes.




## Outcomes


### Source Code/Project Files


### Build Link


### Video Demonstration






## Reflection


### Research Effectiveness  


### Positive Analysis


I think the random weapon system, even though it’s pretty basic, actually worked well. It added just enough variety to keep things interesting without overcomplicating anything. I'm honestly pretty proud of how it turned out—it did what it needed to do, and it felt good in the game.


I also really like how the weapon crafting system came together. It gave players some control over their loadout, which balanced nicely with the randomness. It was fun to build and even more fun to see players experiment with it.


Additionally, my favourite aspect of the project, in general, was finishing up the UI. I am not the best at designing nice UI, but I am proud of mine, keeping it all neat and tidy so everything is out of the way of one another. It is not too clumped and not too small, making sure it is perfect.




### Negative Analysis  


The main issue here, honestly, was a mix of creative burnout and time pressure. I hit a point where I just ran out of ideas and couldn’t find the motivation to push things forward. Inspiration dried up, and I didn’t have a clear direction anymore. On top of that, I made a few bad calls that didn’t help and ended up dragging the whole thing down. Looking back, I can see where it started to fall apart, and a lot of that comes down to me just not being in the right headspace to keep it going.


Alongside this, there was also a small issue of me not having internet commection for two weeks, causing me to be unable to work on a lot of my necessary work as I was unable to check online.


### Next Time


Next time, I’ll make a proper plan so I don’t just dive in headfirst without thinking things through. The big issue I ran into was getting overwhelmed. I didn’t pace myself, and it ended up burning me out pretty quickly.

Additionally, I had a Trello board for the first few weeks. While it started out rather well, it quickly fell apart into peices, becoming a bit of a mess. Originally I used a 

Looking ahead, I’ll be way more thoughtful about choosing projects that I’m excited about, rather than just going for something that sounds cool at first. The real problem here was that I ended up falling out of love with the project midway, and once that happened, it was tough to keep pushing forward. It led to me not finishing as strong as I should have.


## Bibliography


- Mount&Blade II Bannerlord - TaleWorlds Entertainment (s.d.) At: https://www.taleworlds.com/en/games/bannerlord# (Accessed  03/03/2025).


- Iskallia (s.d.) Vault Hunters. At: https://www.vaulthunters.gg (Accessed  03/03/2025).


- How To Make Gamepad Navigation For Menu/UI Widgets In Unreal Engine 5 (2024) At: https://www.youtube.com/watch?v=RdaAVTMIg08 (Accessed  03/03/2025).


- Unreal Engine 4 Tutorial - Survival Game Part 10: Crafting Setup (2022) At: https://www.youtube.com/watch?v=Clfqu46vGfM (Accessed  03/03/2025).


- Roberts Space Industries | Follow the development of Star Citizen and Squadron 42 - Roberts Space Industries | Follow the development of Star Citizen and Squadron 42 (s.d.) At: https://robertsspaceindustries.com/en/ (Accessed  15/05/2025).

https://bannerlord-online.com/forum/index.php?threads/crafting-system-and-items-quality.1891/

https://mountandblade.fandom.com/wiki/Weapon_crafting

https://www.proquest.com/docview/2555194299?pq-origsite=gscholar&fromopenview=true&sourcetype=Scholarly%20Journals

https://kingdomcomedeliverance2.wiki.fextralife.com/Blacksmithing

https://dev.epicgames.com/documentation/en-us/unreal-engine/saving-and-loading-your-game-in-unreal-engine 

https://dev.epicgames.com/documentation/en-us/unreal-engine/using-retargeted-animations-in-unreal-engine?application_version=5.5

