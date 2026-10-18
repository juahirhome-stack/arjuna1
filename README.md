# Evergrow — Level 3: Our Space Celebration

[Download Evergrow Level 3](https://raw.githubusercontent.com/juahirhome-stack/arjuna1/evergrow-download/Evergrow-Level-3.zip)

**The same game, from your bedroom to 100 km.** Level 3 continues the existing adventure at 50 km. Your floating world-city, miners, garden, train, night-light, friends, and every previous rescue come with you. Automatic milestone stops remain; choose **Keep growing** to continue. Numbered chapter gates stay removed.

## New space-party activities

At **50 km**, your friends start a space celebration and assemble **Friendship Spaceport** in six seconds, including while height is paused. A large docking hoop, station windows, protected terraces and suited crew appear beside you.

- **Visit the spaceport** in first person and look at its Moon panorama.
- **Launch a party rocket.** It rises for seven seconds from a separate pad and becomes a celebration beacon. Construction and launch animation continue at the height cap.
- **Activate the celebration shield** and take an **eight-second floating ride**. The real first-person camera follows a loop with a gentle vertical offset. Growth and walking pause; drag to look around. The phone/help pauses the trip. Repeat rides work at 100 km.
- **Catch three floating presents.** Aim with **Look at my next present**, then catch when lined up. Each gives **200 celebration points**, once. The third reveals a hovering **robot buddy** near your helmet.
- **Build a docking ring** using **12 crystals and 20 sky iron**, deducted once. Your miners continue gathering afterward.
- **Take a space celebration photo.** Your phone shows the local news picture with the city, Moon and party decorations, and City buzz saves a pretend post.
- At **90 km**, **start the lantern parade**. Three friendly ships circle the spaceport with steady colored lantern trails. Welcoming the parade awards **300 celebration points**, once.
- At **100 km**, **seal a time capsule** with your photo, three collected presents, a built docking ring and one of three wishes. It adds a visible capsule and **1,000 celebration points**, once. The complete celebration earns **1,900 points**.

Our dream-space party starts at 50 km. At **100 km**, the story celebrates the **Kármán line**, a commonly used boundary of space. Fictional shields and levitation make the activities possible; height alone does not remove gravity. The world’s curvature remains deliberately exaggerated storybook geography.

## Five more rescues

| Rescue | Height | Lives | Popularity | Social points |
| --- | ---: | ---: | ---: | ---: |
| Space research rocket | 55 km | 6 | 14,000 | 32,000 |
| Satellite service cabin | 65 km | 3 | 15,500 | 35,000 |
| Lunar visitor bus | 75 km | 24 | 17,000 | 40,000 |
| Space greenhouse shuttle | 85 km | 8 | 19,000 | 45,000 |
| Starliner | 100 km | 500 | 25,000 | 60,000 |

New calls require a ready spaceport, the celebration shield, F1 boots, NASA shields and SRMAS. They approach within 300 m of your eyes. Look, catch within reach, then **Lower gently** onto a clear spaceport terrace. Loads begin above their landing areas; arms keep normal proportions while levitation moves the load. There is no crash countdown.

Growth and walking pause during active rescues. Rewards arrive once after landing, with an independent replay and pretend social post. All **29 rescues** together save **1,467 lives**, award **174,250 popularity** and **406,700 social points**. There are **76 optional tasks** and **28 Lab readings**.

## Your earlier adventures remain

Explore your house; meet ten neighboring homes at 25 m; see New York, news and skydivers at 100 m; use the X-ray helmet through clouds at 200–350 m; invite NASA visitors; visit the rising offices at 400 m; answer the Morse call and receive the Burj’s suit pods and growing SRMAS at 600 m; explore six alien mountains at 1 km; hire six miners at 2 km; and watch the whole community put on astronaut suits at 5 km.

At 10 km, buildings fly up from the round world and unite into a giant floating city that follows you all the way to **100 km**. Tour six districts, collect passport stamps, connect skybridges, ride the sky train, plant a garden, and start the city light festival. Sunlight collectors power the giant night-light and shared warmth. At 45 km, the sky turns black and nine friendly aircraft become fictional shielded SR-71 Blackbirds. Map three stars for the Friendship constellation and 300 discovery points.

Miners deliver **3 crystals and 5 sky iron every six seconds**, including while growth is paused or capped. The older rescue beacon costs 6 crystals and 10 iron; the garden costs 9 crystals and 15 iron. All recipes spend once. Storage caps at 9,999 each.

Automatic stops occur once at **2.9, 25, 100, 200, 350, 400, 450, 500, 600, 800, 1,000, 2,000, 3,000, 5,000, 7,500, 10,000, 12,000, 15,000, 20,000, 25,000, 30,000, 35,000, 40,000, 45,000, 50,000, 55,000, 60,000, 65,000, 70,000, 75,000, 85,000, 90,000 and 100,000 m**. At 100 km, growth stops for this update. Mining, construction, rides, celebration activities, the phone and unfinished rescues keep working.

## Play and develop

Extract **Evergrow-Level-3.zip**, then open **Play-Evergrow.html** in Chrome or another modern browser. The ZIP contains that HTML file and READ-ME.txt. No installer, account, server or Internet is needed. Drag to look; W A S D, arrows and on-screen controls move and turn. Progress lasts for the current session and resets when you start over. All news, posts, resources and inventions stay inside the pretend game.

Node.js 22.12 or later is required; the cloud uses Node 24.

```sh
npm ci
npm run dev
npm test
npm run test:browser
```

The build exports Vite assets, a self-contained classic-script HTML game and reproducible ZIPs. Older local filenames alias the current build; earlier published downloads remain preserved. Static skyline, district and spaceport meshes are cached rather than rebuilt at every new height.

Validation covers the existing story and new 100 km cap, automatic stops, party construction and animation at the cap, actual float-ride motion and pause, aimed present collection, single-spend crafting, reward limits and time-capsule prerequisites, finite cached geometry, five new rescue paths and separate replays, normal arms, mining, reset, strict offline touch sandboxes and startup regressions. Browser checks use Linux Chromium; Windows Chrome and the chat Web preview wrapper are not directly tested.

Startup Check W2 draws a readable fallback before the game script. The first picture draws immediately, with a timer backup for stalled animation callbacks. No backend or credentials are required.

Validation complete: **95 unit checks and 22 browser scenarios passed**, plus an offline smoke check of the extracted ZIP. Earlier published downloads remain preserved.
