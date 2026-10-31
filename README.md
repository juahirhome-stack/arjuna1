# Evergrow — Level 3.4: The Navigation Frontier

[Download Level 3.4](https://raw.githubusercontent.com/juahirhome-stack/arjuna1/evergrow-download/Evergrow-Level-3.4.zip)

The same first-person story now reaches **35,000 km**, with a game menu, saved stories, four navigation-satellite repairs, five crew rescues and new MEO activities. The previous 2,000 km stop is resumable. All earlier adventures and the annual Halloween event remain.

## Game menu and saved stories

**New Game** starts at home. **Menu** pauses all simulation clocks, mining, construction and active rescues. **Quit Game** saves your current story and leaves you at the menu; you can then close the browser tab. Reopen the same HTML file in the same browser and choose **Resume**. Growing remains paused until you choose **Keep growing**, while an unfinished rescue can continue from its saved stage. New Game asks before replacing an existing story.

The game saves after story actions, every five active seconds, when opening the menu and when leaving the page. Continuous tuning sliders are picked up by the next periodic or exit save. **Download save** creates a portable `Evergrow-save.json`; **Load save** imports it after validation. Use a backup when moving to a new game file or clearing browser data. If browser storage is unavailable, the menu explains that the current session can resume, but you need a downloaded save before closing. There is no account or cloud save. A bad import leaves the current story intact; text from imported rescue records is rebuilt from the game's trusted data.

## A new MEO journey

MEO approaches geostationary altitude, about 35,786 km. This game's simpler upper limit is **35,000 km**. Between 2,000 and 5,000 km the helmet gradually changes its exaggerated close-up storybook globe into the wide Earth view, using Earth's approximate **6,371 km radius**. Above 5,000 km this globe gets smaller as you grow. The floating world-city, normal arms, shields and self-replicating suit keep following you. Fixed ISS and Hubble visits still work at 400 and 520 km, including from the new cap.

| Height | New activity or mission |
| --- | --- |
| 3,000 km | Rescue the waystation workshop's 6 engineers. |
| 5,000 km | Build a free navigation beacon in four active seconds. |
| 8,000 km | Rescue the solar-sail courier's 8 helpers. |
| 12,000 km | Rescue the navigation school cabin's 18 students and helpers. |
| 16,000 km | Tune the pretend navigation clock to **42**, within 2, and lock it. |
| 19,100 km | Repair an uncrewed **GLONASS** navigation satellite. |
| 20,200 km | Repair an uncrewed **GPS** satellite. |
| 21,528 km | Repair an uncrewed **BeiDou MEO** satellite. |
| 23,222 km | Repair an uncrewed **Galileo** satellite. |
| 27,000 km | Rescue 20 outer-orbit observatory researchers. |
| 31,000 km | Look at and scan three marked safe flight lanes. |
| 35,000 km | Rescue a 120-person MEO liner and earn the **MEO Pathfinder** badge. |

The four satellite heights are approximate representative MEO altitudes. In the dream, protected service lanes put these crafts beside your hands. Look, catch and lower each onto a service terrace to restore its signal. The navigation satellites have **no people aboard**, so repairs earn popularity and social points without adding fictional people to the lives-saved counter. The five crew rescues save **172 people**. All nine missions award once and each saves a distinct replay and pretend social post, for **844,000 popularity** and **2,320,000 social points** in total.

After each satellite repair, select the requested system and choose **Look at this system**, then route its message: mountain rescuers → GLONASS; ocean pilots → GPS; ship captains → BeiDou; balloon scientists → Galileo. Beacon and clock must be ready. Wrong routes cost nothing. Once all four messages, nine missions, three lanes, beacon and clock are complete, claim the Pathfinder badge at the cap. MEO activities give **5,150 separate points**: beacon 300, clock 400, four messages 1,200, three scans 750 and badge 2,500.

There are **153 optional story tasks**, **69 Lab observations** and **74 automatic growth stops**. Unfinished activities, mining, rescue calls and station visits remain available at 35,000 km. All models remain bounded, and the 24 fps drawing limit, offscreen sleep, polygon culling and sharp display-density canvases remain enabled.

## Earlier updates


The same first-person adventure now has an automatically recurring Halloween event. **October 1–31 each year, Singapore time (UTC+8)**: themed home and world, pumpkin lanterns, bat bunting, warm city windows, a growing costume, and pumpkins on the phone and weather camera. It closes **November 1 at 00:00** and returns the next October without downloading another seasonal update. The offline game follows the computer’s clock.

Choose Pumpkin explorer, Friendly bat or Moon ghost. Deliver five lantern-and-treat parcels at home, 25 m, 100 m, 10 km and 100 km for **100 Halloween points each**. Complete three seasonal rescues to unlock the harvest lantern parade for **1,000 bonus points**. The seasonal checklist is separate from the regular story tasks; it adds no growth stops and no resource costs.

| Halloween rescue | Height | People | Popularity | Social points |
| --- | ---: | ---: | ---: | ---: |
| Runaway pumpkin balloon | 100 m | 12 | 1,000 | 3,000 |
| Stranded bat-wing bus | 10 km | 24 | 12,000 | 28,000 |
| Moon masquerade shuttle | 1,000 km | 60 | 70,000 | 160,000 |

Magic boots protect each catch. The bus needs SRMAS and NASA shields; the Moon shuttle also needs the celebration shield. They use the same first-person look/catch/lower controls, normal arm proportions, downward shielded landings, separate replays and pretend social posts. Each rescue rewards once per season: **96 lives, 83,000 popularity and 191,000 social points** in total. Halloween activities give a separate **1,500 points**.

The date is checked during play, including while dialogs pause the story, and before actions. After closing, decorations and new seasonal calls disappear; an underway rescue may finish safely. Earned rescue rewards and saved replays remain in the current session. The next year resets the seasonal checklist and makes its calls available again without resetting the regular adventure. Reloading or Start over still resets the play session, as before. No account, online clock, purchases, particles or flashing lights are required.

## Clean graphics remain

The graphics selector has been removed. The game now uses **sharp graphics automatically**, matching the display’s pixel density up to 2×. Old graphics preferences are ignored, and no graphics setting or browser storage is required.

The first-person view, live weather camera, phone, research charts, rescue replays and Hubble photo album all draw at the display’s resolution instead of stretching a small bitmap. The weather globe’s day/night shadow is smooth and cached; the clear-night weather camera shows a crescent Moon.

The performance improvements remain: camera culling skips invisible objects and polygons, repeated lighting colors are shared, the game caps drawing at **24 pictures per second**, and offscreen views slow to one refresh per second. Weather updates at most ten times per second when visible. Covered scenes rest while dialogs are open, and the simulation keeps its normal speed. There are no graphics buttons or automatic switches to a blurry mode.

The same first-person growing story starts in your bedroom and now reaches **2,000 km**. All earlier adventures, rescues, the floating world-city, miners, satellite fleet, Hubble and ISS remain. **Automatic growth stops remain**; choose **Keep growing** to continue. The former 1,000 km cap is now resumable.

## Day + night in 9–12 minutes

Choose **9 minutes**, **10½ minutes** (default), or **12 minutes** for one complete day-and-night cycle of active simulation time. Growth pace does not accelerate this clock. Pausing growth lets time, weather and miners continue. Phone, help, observatory album and hidden tabs pause the simulation.

Sunlight moves across the same round Earth; buildings darken gently at night while remaining visible. The Sun moves in the sky and disappears during the local night. Space remains black with stars. **Watch day now** and **Watch night now** jump to a view without changing progress, after which the selected cycle continues normally. These jumps do not count as completed natural orbits. Changing cycle length preserves the current phase.

## Weather you can see

The **Live Earth Weather** panel appears as soon as your story begins. It shows an illustrated globe with drifting cloud sheets, moving sunlight, night-side lights and a close-up camera. Choose four camera regions to see **clear skies, falling rain, fluttering snow and a slowly swirling ocean storm**. Camera conditions rotate every **90 active seconds**. The first-person round Earth also has moving cloud sheets.

Weather happens in Earth's atmosphere, below the space view. These are fictional illustrated conditions generated inside the offline game. No real weather service, location data or internet is used.

At **1,000 km**, scan each of the four weather kinds for **150 weather points** each, then save a picture of that kind for **200 points** each. Each awards once. The **Weather album** stores a snapshot of its camera region, cloud time and sunlight phase; pictures remain still while live weather continues. Select any saved picture to view it.

## Activities between 1,000–2,000 km

| Height | Activity |
| --- | --- |
| 1,100 km | Build a **sunlight battery** for **4 crystals + 6 sky iron** after hiring miners. It charges for **eight active daylight seconds**; night pauses charging. Once full, switch to night and **send stored light to night-side homes** for **600 points**, once. The weather globe shows the powered lights. |
| 1,200 km | After all four scans, **share the four-region forecast** for **500 points**, once. |
| 1,300 km | Watch mountain snow and answer the snow-laboratory rescue. |
| 1,400 km | Follow the ocean spiral storm and rescue its weather pilots. |
| 1,500 km | Tune the **aurora beacon slider to 72**, within 3, and switch it on for **700 points**, once. Look at its steady mint-and-violet ribbon beside your satellites. This is a pretend beacon at helmet height; real auroras remain much lower. |
| 1,650 km | Rescue the garden seed ship, including twelve gardeners and their seedlings. |
| 1,800 km | Help the night-side school trip. |
| 1,900 km | The city prepares its horizon festival; finish any remaining activities. |
| 2,000 km | Rescue the 800-person horizon liner. Complete four weather photos, the forecast, battery delivery, aurora beacon and all eight new rescues to start the **horizon festival** for **2,000 points**, once. |

Completing all new non-rescue activities gives **5,200 weather points**, separate from satellite, orbital, celebration, discovery and rescue scores. The sunlight battery spends resources only once. It can finish charging at the height cap. All unfinished activities and earlier station visits remain available at 2,000 km.

## Eight new rescues

| Rescue | Height | People | Popularity | Social points |
| --- | ---: | ---: | ---: | ---: |
| Dawn observatory crew | 1,100 km | 6 | 52,000 | 125,000 |
| Coastal rain ferry | 1,200 km | 48 | 54,000 | 130,000 |
| Snow laboratory | 1,300 km | 8 | 56,000 | 135,000 |
| Storm-watch pilots | 1,400 km | 4 | 58,000 | 140,000 |
| Aurora researchers | 1,500 km | 7 | 60,000 | 145,000 |
| Garden seed ship | 1,650 km | 12 | 62,000 | 150,000 |
| Night-side school bus | 1,800 km | 50 | 64,000 | 155,000 |
| Horizon liner | 2,000 km | 800 | 80,000 | 200,000 |

These eight save **935 people**, with **486,000 popularity** and **1,180,000 social points**. Across all **53 rescues**, save **3,164 people**, with **1,201,250 popularity** and **2,863,700 social points**.

Wear F1 boots, SRMAS, NASA shields and the celebration shield, and let Friendship Spaceport finish building. Answer a rescue call, **Look at rescue**, **Catch** when lined up and close, then **Lower gently**. Each lands on a clear terrace below your eyes. Protective levitation moves the load while arms keep normal proportions. Growth and walking pause; there is no crash countdown. Each rescue awards once after landing and saves its own pretend social post and replay. Climate controls are locked during active rescues, rides and station visits.

Level 3.3 added the weather chapter; Level 3.4 expands the totals to **153 optional tasks**, **69 Lab observations** and **74 automatic stops**. New stops are **1,100, 1,200, 1,300, 1,400, 1,500, 1,650, 1,800, 1,900 and 2,000 km**. Start over clears the current session's progress, including weather, pictures, time and inventions.

## Earlier adventures remain

Explore home in first person. At 25 m, ten more houses and filming neighbors appear. At 100 m, see New York, the news helicopter and skydivers; wear magic F1 boots and rescue an airliner. At 200–350 m, equip the growing X-ray helmet to see through clouds and invite shielded NASA visitors. At 400 m, watch buildings rise, visit office researchers and read their growth observations. At 600 m, a Morse call brings a friendly alien, the Burj Khalifa and suit pods. Receive and wear SRMAS.

At 1 km, see six alien mountains and nine planes. Hire six miners at 2 km: they bring **3 crystals + 5 sky iron every six seconds**, even while height is paused or capped. At 5 km, everyone suits up. At 10 km, the map becomes a curved globe and cities unite into a floating world-city that keeps pace with you. Visit six districts, build skybridges, take the first-person sky train, plant a garden and start a festival. Sunlight collectors at 15 km power the giant night-light and shared warmth. At 45 km, see stars and nine shielded SR-71 Blackbirds.

From 50–100 km, enjoy Friendship Spaceport, a party rocket, presents, robot buddy, docking ring, floating ride, Moon, photo, lantern parade and time capsule. Between 100–400 km, answer the ISS radio, send supplies, take an Earth postcard, recycle fragments, build a relay and play the light harp. Visit a shielded service pod beside the **fixed ISS at 400 km**, collect tools, align its solar wing to **35°**, repair cooling (**inlet open, bypass closed, return open**), help three station rescues and earn the Orbital Helper badge.

From 500–1,000 km, the dream helper fleet grows from 24 to **120 satellites**, plus **three craftable CubeSats**. Scan six designs. Visit the **fixed Hubble telescope at our chosen 520 km game altitude**, open its pretend cover, tune the stabilizer to **65** and expose three locally illustrated space pictures. Hubble is uncrewed; its rescue is a separate fictional service pod. Route hospital/forecast/classroom messages through Rescue beacon/Weather/Communications helpers, ride the satellite skyway, sweep fragments, start the constellation parade and name a sky crown. The fictional helper viewing lanes follow your growing body; Hubble and ISS stay in their own game orbits and can be revisited from 2,000 km.

All earlier resource recipes remain: beacon **6/10**, relay **6/10**, garden **9/15**, docking ring **12/20**, each CubeSat **2/3** (crystals/iron). The round Earth exaggerates curvature for storybook geography. Shields, levitation, suits and air packs are dream inventions. Posts, news, weather and pictures stay inside the game.

## Play and develop

Download **Evergrow-Level-3.4.zip**. On Windows: right-click → **Extract All** → open **Play-Evergrow.html** in Chrome. The ZIP contains exactly that HTML file and **READ-ME.txt**. No installer, account, backend, server or internet is required. Drag to look; W A S D, arrows and on-screen controls move and turn.

Node.js 22.12 or newer is required; the cloud uses Node 24.

```sh
npm ci
npm run dev
npm test
npm run test:browser
```

The build exports Vite assets, a self-contained classic-script HTML game and reproducible ZIPs. Older local filenames alias the current build. Older published downloads remain preserved. Startup Check W2 draws the first picture immediately and supplies a timer backup for stalled animation callbacks.

Validation covers exact cycle lengths and lighting, time independent of growth pace, live weather and saved snapshots, daylight-only charging and single resource spending, tuning and festival gates, all eight new rescues and independent replays, normal arms, 62 stops, the expanded cap, fixed Hubble/ISS return visits, timers at the cap, reset and offline touch sandboxes. Browser checks use Linux Chromium; Windows Chrome and the chat Web preview wrapper are not directly tested.

Level 3.4 validation: **160 unit checks and 8 browser checks passed**, including persisted Resume, active rescue reload, safe New Game, portable save backups, all nine MEO missions, activities, replays, 35,000 km and fixed station visits. The extracted ZIP also passed its offline menu and Halloween date checks. Older published downloads remain preserved.
