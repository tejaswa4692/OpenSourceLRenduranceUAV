# Efficient Long Range UAV — Development Journal

**Devlogs included:** 33
**Total Time :** 56h
**Build Time :** 47h

Note: Every devlog has an image with it, unfortunately stardance is bugged out and cant export my data so i couldnt get images here, but heres the link to sd project https://stardance.hackclub.com/projects/12767 it has some really cool flight footage

these were imported from stardance thats why there are slack emojis here

## Devlog 01 — 5 months ago

**Time recorded:** 17m 30s logged

Starting out as a flying wing UAV design, uses efficent flying wing type airfoils and will have max payload capacity of around 500g, this aircraft will be mostly responsible for delivering medicines to remote areas without stopping, it’ll use a bomb dropping type mechanism with a parachute strapped to the package.

Main aim of this project is to finish everything in as cheap as but as perfect as possible, in india expensive tech doesnt work out, so im making something that people can actually use

---

## Devlog 02 — 5 months ago

**Time recorded:** 1h 42m 46s logged

Changed the entire design from a flying wing to a conventional UAV type design 2m wingspan and 18cm chord length with a SD7037 airfoil payload capacity of around 500g, there’s a dedicated space for the payload, the entire aircraft will be built out of lightweight pharmocol carbon spars and my own special building techniques that uses trash to reinforce the aircraft.

Ive ran CFD sims on this aircraft aswell and im satisfied by the results for now

---

## Devlog 03 — 5 months ago

**Time recorded:** 1h 12m 16s logged

Made some realistic changes like adding 2 motors instead of one, estimate weight is around 1.7kgs and ill be using 12 inch fiber props in this build, the battery will be made up of either 3000 or 5000 cells if i manage to get my hands on them, the rear stab LOOKS small but its enough for this build providing 1 vbar ratio, this with differential thrust the aircraft will have insane yaw authority, which can be increased to even more by just moving the thrust motors a little outward on the wing, i have added the pixhawk ESC and my motor models to the document aswell

---

## Devlog 04 — 5 months ago

**Time recorded:** 1h 19m 26s logged

Currently dont have a pixhawk board, but thought learning to plan a mission wont be that hard, installed mission planner, and now am trying to get a hang of things in this, ill have a servo attached to the AUX port of the pixhawk and ill plan it so the plane reaches X m/s amount of gps speed before dropping the payload and then before X-C m ill drop the payload so that the landing of the payload is as precise as possible here C is the drag coefficient, ill also have to take into account the paracute ill be making out of old plastic bags and how much they will reduce the speed.

---

## Devlog 05 — 5 months ago

**Time recorded:** 33m 3s logged

What if life-saving supplies could reach places of distress without roads, traffic, or human pilots? This project presents a long-endurance autonomous UAV designed to deliver payloads upto 300g using an energy-efficient airframe, autonomous flight planning, and low-cost hardware and really low cost maintenance, most parts of this build are easy to find and the build processes that are used in this aircraft are personally developed worked and tested in real life by me personally.

Built from the ground up as a practical engineering platform, the aircraft demonstrates how modern autonomous systems can make aerial logistics more accessible, affordable, and adaptable for real-world challenges.

The build uses cheap/easily available parts, and every dime serves a purpose in this project, ive linked the github (currently unfinished) on my project page aswell, please check it out and if yall like it then drop a like aswell.

in the images attached, i have made out a flight plan for how it would go in real life, ive ran CFD sims on the aircraft and made a wing profile of 45cm out of thermocol of the SD7037 airfoil to test its stall characteristics to have a better idea about the cruise speed estimation, this testing was done by me sitting in a car with this airfoil outside the window and strapping a MPU gyro to read the angle readings and telling my dad to speed up or slow down.

---

## Devlog 06 — 5 months ago

**Time recorded:** 58m 6s logged

Made the templates for airofoil, servo horns, motor mount, and the rib template in cad aswell, the rib and airfoil templates have to be traced on cardboard, cut out and have their edges sanded to work properly, motor mounts should be printed twice and there are already way more servo horns than you might need.

Even printed these out on my Anycubic Kobra 2 neo to speed up the build process as soon as i get eligible for building

---

## Devlog 07 — 5 months ago

**Time recorded:** 1h 29m logged

Made a real life inspired Aleron servo link for this project.
I had printed the old servo links out, they worked fine but the problem was they relied on adhesive to work, and on my aircraft i had used transparent tape over paper as reinforcement so it had 0 hold to it, hence i decided to model a real life inspired servo link with ziptie like behavior, this one doesn’t rely on glue but on the strength of your control surface to hold on, so this ones a lot better and a lot cleaner, the only downside is that it requires a bit of support material to print but that’s okay as aesthetically it looks a lot better, i might make a version that doesn’t require support material if you don’t care about aesthetics so lmk abt that.
also this versions step and 3mf file is aslo available on the github

---

## Devlog 08 — 4 months ago

**Time recorded:** 52m 6s logged

Made the wiring diagram in figma and added where the electronics are going to be placed around the aircraft.

---

## Devlog 09 — 4 months ago

**Time recorded:** 23m 2s logged

This might be the best day of my life, i got the funding approved for my project got 180 in my HCB, now i can finally start building the project, I have ordered the pixhawk board i just need other electronics and materials.

Tomorrow ill be going out to buy 30mm EPS sheets from my local vendor, and then ill start posting time lapses of me building the wing

---

## Devlog 10 — 4 months ago

**Time recorded:** 2h 15m 9s logged

Ok so i measured and the 2m wing wont fit in my car, really sorry for that, But I will be making the wing 1.5m long, this will reduce the endurance a bit but i wont be sending it to intercity missions just yet so 1.5m will be fine. :jamegam-yay: :neocat-blahaj-dom:

Also im switching to Clark Y airfoil as its more famous and has a lot of reading material online, the build process has started, i have bought the electronics i need im js waiting for them to arrive now. :ultrafastparrot:

I cant wait to get my hands on the pixhawk and then take it to fly :yayayayayay:

---

## Devlog 11 — 4 months ago

**Time recorded:** 55m logged

OKAY SO MY DAD GOT ME EPS BLOCKS FINALLY :yayayayayay:

I cut out the airfoil profile twice (i had one 50cm section laying around already) now i finally have the wing structure ready, now after this ima be designing the modular part for the wing that lets it detach and attach to the 10mm carbon fiber tube that i ordered. :smirk1:

Cant estimate the RTF weight of the aircraft yet, but without battries im trying to hit around 550g, things are looking pretty decent now

EXCEPT THE FACT THAT I ALMOST BURNT MY CLOTHES. Bro i gotta make a better hot wire cutter instead of doing it by hand, i accidentally left the wire touching my pants and i made a lil hole in them. its cool tho :mona:

FOLLOW ME FOR MORE COOL DEVLOGS

---

## Devlog 12 — 4 months ago

**Time recorded:** 1h 7m 30s logged

Ok so i just designed and cut out the rear elevator :yayayayayay:

It looks queit decent, i used 6mm old circular dowels tgat were laying around the house to make it more sturdier, the elevator came out perfect im quiet satisfied by it. Also shout out to this foam, its holds its shape quiet well and its not soft like my old one.

Im js waiting for my electronics to arrive, its gonna be christmas soon when all the electroncis do arrive :smirk1:

Oh and i will be using the rounded wingtips for everything in aricraft to increase endurance as much as i can. At speeds this aircraft will be running on, i dont expect the vortex to touch the trailing edge of the wing so yeah thats good

---

## Devlog 13 — 4 months ago

**Time recorded:** 2h 45m 25s logged

MORE ELECTRONICS ARRIVED TODAY :yayayayayay:

I have made the rear assembly with a beautiful and modular connector that uses zipties to hold onto the carbon spar (i will also add ductape for more rigidity)

And i designed the mount of how the BLDC motors are going to hold on the wingspar. :ultrafastcatppuccinmauveparrot:

ALSO THE SERVOS ARRIVED YAYAYAYAYA, I can finally finish the rear assembly with electronics and all.

Unfortunately my gluegun exploded (literally) :fear:
So i have been set back by a bit but i think im good

Heres a graphic for more accurate depiction of how it looked when the gluegun exploded

---

## Devlog 14 — 4 months ago

**Time recorded:** 2h 10m 42s logged

Okay dang my back hurts :heavysob:
But REAR STABS ARE READY, They are made as perfect, modular and easy to transport as possible. :yayayayayay:

I centered the servos and installed them after lining the entire wing using my custom build process :smirk1:

The carbon fiber tube is slid on on site and then clamped to the rear assembly using zipties, this is a little wasteful, but you can also use screws and bolts if youre rich enough.

Im quiet proud of the lining job, this rear assembly is one of my best pieces of work ive ever manufactured,
I cant wait to see this baby fly :ultrafastcatppuccinmauveparrot:

Unfortunately no updates on into the cosmos today cuz i was way too excited to work on this project.

Oh and shoutout and a huge thanks to hackclub :pink_heart-magic_wand: this would NOT have been able to be possible if not for them.

---

## Devlog 15 — 4 months ago

**Time recorded:** 3h 27m 58s logged

May lord have mercy on my back damm :heavysob:
But the wing is 80% dont, along with the elevator, i have designed everything in most modular and easy t transport as possible.

I didnt use my construction method all the way on the wing as it was adding a ton on unnecessary weight on the wing, and the center part does not even need to be that structurally strong so i just let it be exposed, and honestly it looks way better. :ultrafastparrot:

ALSO MORE ELECTRONICS ARRIVED :yayayayayay: , today my battery, ESC, and the receiver arrived, i was finally able to see the pixhawk control the servos, for some reason ESCs do get warm when i try to use them but i hope itll be fine.

tomorrow the thing im most dreading about, the fuselage and wiring the servos through the wing i will be doing, its most tedious job ever :heavysob: but we gotta do what we gotta do.

Im quiet proud how sturdy the frame is tho, the way i made it its absolutely perfect, and it looks like a kit istg. i love working on this project.

OH and again HUGE shout out to stardance for getting me all this electronics :pink_heart-magic_wand: i will never forget this favor from y’all ever, this is genuinely a core memory of mine now

---

## Devlog 16 — 4 months ago

**Time recorded:** 2h 18m 19s logged

Istg my back is GONE atp :fear:

so i covered the entire wing in paper :yayayayayay:
turns out yesterday the weight was so high due to wet glue all over the wing, once it dried.

So i js covered the entire wing in paper, and its quiet sturdy, Also i fixed the servos inside the wing aswell, it looks very flush, but im sure all that is going to go down the drain once i start installing the esc.

This is an insanely tedious job, im just dreading the fuselage part idk how im gonna mke that :heavysob:

The support ive been receiving is INSANE it really motivates me to work on it more so thnx yall :ultrafastcatppuccinmauveparrot:

LOOK AT MY BACK THO GOD DAMM IM FKIN CROOKED

---

## Devlog 17 — 4 months ago

**Time recorded:** 2h 21m 2s logged

Okay so my back doesnt hurt today :yayayayayay:

I worked on the wing and installed the ESCs, tested the motors using pixhawk and they both respond properly :yayayayayay:

I do have a little concern as the ESCs are getting slightly warm, i did remove the rubber like i did on my older ESC, that doesnt seem to make it any better, the ready to sky esc i used earlier didnt have this heating problem, idk whats going on, i hope it js doesnt end bad :fear:

The good news is that i installed servos and their linkages to the alerons, i will have a flaperon configuration for nice low effort flaps.

Today the aircrafts weight is 560gs without the battery, so im assuming this will be around 750-800 grams with the 1500 3s lipo

Istg i hate soldering these thick wires, its js so tedious :heavysob:

---

## Devlog 18 — 4 months ago

**Time recorded:** 2h 23m 55s logged

Ok so i have assembled the avionics, and routed everything in aircraft,
as i expected everything does look insanely ugly now

Thats okay since i will be making a fuselage later which will hopefully
look nice

Currently i have ailerons elevator and rudder working fine with
differential thrust in action, I do need a proper place to mount the
battery aswell, along with a proper place for pixhawk, its just hanging
there with double sided tape rn.

I really wish i had a better looking fuselage :heavysob: this looks insanely ugly rn, hopefully after i confirm it flies then ill work on the fuselage.

My batteries are dead and it JUST rained so i cant go out today, maybe tomorrow i can go for a maiden

---

## Devlog 19 — 4 months ago

**Time recorded:** 1h 12m logged

today i disassembled the aircraft cuz im not gonna be able to fly it anyways rn due to rain :heavysob:

Made everything under the wing a LOT cleaner, hid the mess under a sheet of paper, it doesnt look That good, but it looks plenty good rn :yayayayayayay:

I am setup and tinkered in the firmware a bit more, idk why i have this fear of maiden launches that stops me from actually flying my models, i really need to get over that

Currently I have started working on my game too due to this rain, but ill soon go out for a fuselage less maiden.
Pray for me that it goes well. :heavy_heart:

---

## Devlog 20 — 4 months ago

**Time recorded:** 4h 35m 33s logged

This battery is not human bro. :fear:

This took me way too long to make, the most problematic part was to figure out how to get all the cells together without exploding the pack with extreme heat.

I didnt have a spot welder, all i had was nickel strips some cells and a dream, so i used my regular soldering iron and started experimenting on how to solder these packs

In the end i found that “spot soldering” worked best for me, i hope im the first one who invented this, but u basically take not that hot of a soldering iron, and then u sand the surface place the strip and dab the soldering iron on the connection to join them together, do this like 4 times for a single joint and u have quiet solid joints

While making the connections i did mess up and bit and there was some sparking not enough to burn my house thankfully :fear:

About the pack, its a 4s4p pack, my first time using 4s configuration, and i am NOT comfortable with the amount of power it delivers, its way too scary gng :fear:
Im gonna lock the throttle at 70% cuz i know damm well shit can go wrong real fast with these packs.

I did some test runs with this on my flying wing and this rc plane, using the pixhawk power module at 50% throttle i saw 11A consumption with PLENTY of power, and on my 3s lipo pack it consumed 21A at 100% so we can safely say its not bottlenecking.

Its currently 12000mah, i do have 4 more cells i bought so i can push it to 15000, but ill prolyy do it later cuz this scares me way too much

Im not kidding the sound the motor makes while using this pack is way too wild, i HOPE autopilot can handle everything n nothing goes wrong, that being said i will NOT do the maiden with this, instead ill use my 1500mah 3s lipo for that.

---

## Devlog 21 — 4 months ago

**Time recorded:** 1h 34m 17s logged

I have assembled the airframe :yayayayayay: , everything is quiet sturdy and under the estimate weight limit, i setup the flight firmware for this specific aircraft, and tuned the rates.

Unfortunately due to heavy rainfall near my area and the wing almost entirely being covered with paper, i cant go risk flying it. :sadge:

Also it gets worse as i will not be home for a month or less :heavysob: . I will be disassembling the aircraft which is quiet easy to do due to my smart design choices.

I have ordered the XPS sheets that were included in my grant, theyll reach when im not at home so making the fuselage has to wait, but that gives me PLENTY of time to design the fuselage in CAD and make it as clean and robust as possible.

On a positive note i took my 450g flying wing out to fly today, it flew quiet well, unfortunately i did manage to crash it as it didnt have a flight computer and these things are quiet hard to fly.

Thanks to stardance tho i do have autonomous flight electronics (which costs $180 btw), i can make an autonomous flying wing that will be able to do long range endurance with help of 4 extra cells i have lying around. So thatll prolly be my next project after i come back home :yayayayayay: .

With that i will thanks stardance once again for getting me all these electronics

---

## Devlog 22 — 3 months ago

**Time recorded:** 1h 39m 27s logged

This will be my last devlog before leaving my home :neodog_melt_sob:

I wont be home for a month or more now so unfortunately progress on this project will be paused. :(

Today i configured my transmitter such that if the aircraft goes beyond range of rx, it automatically comes back home.

This was a huge challenge as i didnt have those fancy transmitters with a screen to configure stuff, i have a flysky i4x that comes with JUST the sticks no configuration. :heavysob:

Fortunately, buying a flysky transmitter saved me :02smug: As flysky ibus or sbus protocol transmits the RSSI of radio signal as a pwm signal on its channel 14, To be honest i discovered that while calibrating my radio in mission planner, i was surprised and overjoyed to find that this is actually possible with my transmitter.

After finding out and a bit of tinkering later i was able to map RTL on channel 14 and reverse the channel aswell (so it turns on if transmitter disconnects). Honestly this was top 10 flysky respect moments for me.

I will be working tirelessly on my game now so be sure to follow that project aswell.

I also wanna take a moment to thank EVERYONE who has shown me so much love and support since the beginning of this project, And also to hackclub who were able to provide be with the electronics i could only dream to afford. :bunnyguy-heart:

---

## Devlog 23 — 3 months ago

**Time recorded:** 1h 21m 15s logged

IM HOME :yayayayayay:

Today as soon as i reached home i unboxed my telemetry radio and started working on my flying wing

Ill use this aircraft as a stepping stone to learn AP and its modes and if i crash hopefully the damage isnt that much :fear:

Logging time for builds irl is super hectic bruh i gotta figure out a better way to do this
0
0
43

@alex_l returned your funding request ? · 3 months ago
$1 B Tier

Hiya, this project has already been funded by Outpost! Please resubmit it as a build (not a design!) when you're done building it. Thanks!

@1 returned your funding request ? · 3 months ago
$178 S Tier

returning this as it has been funded by outpost! submit your build once you have finished building your project!

---

## Devlog 24 — 3 months ago

**Time recorded:** 57m 39s logged

FINISHED THE BUILD OF THE STEPPING STONE FLYING WING

This is the flying wing i normally take out to fly and have fun, Ive had like 60% success rate with this model (without wingtip washout), Mostly because flying wings are hard to fly and i dont know how to fly :fear:

Good thing about flight computers is that they DO know how to fly so this would be a lil bit easier

Ive added 2.5 degrees of wingtip washout on this aircraft, also ran CFD sims on the entire wing profiile and saw that the stall characteristics are like a self stablizing feedback loop

I have done all the wiring and flying wing setup in the pixhawk, i just need to go fly to use the autotune mode to get the PID right for this model

One thing that is bad with this model is that the elevon throw when its going down is WAY less than compared to that when its going up so i hope that might not fk up the plane

Ive ran several indoor tests with the motor on and off, it does stall if not thrown properly but most of the time the launch is butter, lets hope its that way tmr too

---

## Devlog 25 — 2 months ago

**Time recorded:** 26m 52s logged

Fuh me :heart-eyes:

The EXACT DAY i finished my build it has NOT stopped raining at all the airfield is completely damp and my aircraft isnt waterproof.

I have limited amount of holidays and this weather is NOT helping me, mum says if i am not able to finish it i can come back again and try then, I still have 4 days to go hopefully weather clears out and im able to ATLEAST take out the flying wing

---

## Devlog 26 — 2 months ago

**Time recorded:** 1h 36m 42s logged

Took the plane out anyway :yayayayayay:

So today i did 3 VERY short flights 2 of those were successful so ill only count 2

First flight the plane started oscillating in the pitch so i ended it short, Also cuz i ran out of ground to fly as due to heavy rainfall the fields i fly usually on are FULL of water

After this flight i committed a bit more to the second launch, got the plane in the air (I think AP did it) The tail was oscillating but it wasn’t unflappable, I had to crash the aircraft in the tree because it was heading beyond my line of sight and there was a LOT of water beyond that tree

Thankfully the aircraft received no damage in todays flight, everything was so soft the aircraft didn’t even register any of these crashes as a crash, It went good overall

I reduced the servo throws by moving the wires down a notch realized that my surfaces are not symmetric so i accounted for that checked everything chucked it in my room and it feels fine for now

Something i dont understand is why in 2nd flight did the aircraft pitch left 80 degrees for no reason and it didn’t even stabilize itself, might need to look at the logs for a few more hours to figure that out :fear:

---

## Devlog 27 — 2 months ago

**Time recorded:** 3h 40m 4s logged

I have finished the plane :yayayayayay:

This took way more than 2 hours btw, it was js such a hassle i forgot to record

Anyways the 2 hours that ARE in this post are the hours i spent analyzing the crash of the flying wing, I have zero idea why it crased, but it just rolled right and hit the ground nose down every chance it got.

I went on reddit asking about this they told me its cuz flying wings are fiddly (i dont have much exp w them either), and need to be perfect to fly
So i js moved on from that and finished the build of the full plane

I did factory reset the flight computer this time to get everything reset, and this is a note to self for future

When configuring channel 14 RSSI for Flysky TX, Remember to turn on allow_aux_reverse in RC_OPTIONS parameter for it to work

The plane is done and build (will build the fuselage later incase it crashes), Im js waiting for good weather, Im here till 7th of this month, hopefully we get a window in that time or else its wraps for me

---

## Devlog 28 — about 1 month ago

**Time recorded:** 2h 10m 34s logged

Okay so good news and bad news :yayayayayay:

Bad news being that my 1.5m span UAV unfortunately crashed, i took it out to fly yesterday and due to wings being way too high i couldnt control it and it crashed.

Good news being that my 1m span ultra stick DID fly, This is a similar UAV i started designing thats much lighter and more capable.

Enjoy the flight video, Unfortunately due to me being a shit pilot i tried to turn it towards me to get a nice shot but the turn radius was too low and it was going straight towards the power lines so i panicked and crashed it, That broke the motor mount so ill print like 5-6 of them and go to fly tmr with the pixhawk

---

## Devlog 29 — about 1 month ago

**Time recorded:** 1h 12m logged

Beautiful flight :yayayayayay:

Js look at the way it flies bro i can NOT its way too smooth

This was my first time actually flying with a flight computer and god damm was it a good experience, everything was so easy and i wasnt scared of flying it too far as i had setup RTL earlier

Unfortunately the bad news is that i had 3 flights with this plane, and in the final flight i was tryna autotune it and mid flight the motor came off the mount and fell in the ground :fear: (yes it was 70m above the ground when it happened) thankfully the goated pixhawk was able to save the plane, also i had full control over it so i was able to land the plane safely

After further inspection i figured out that the motor heat had melted the PLA mount and made the countersink screws act like wedges in wood and it js came clean off 😭 I did NOT expect that bro.

Since then i have asked for a bump and also i made the mount much thicker and in todays flight i will be ziptying the motor on :sob-wx:

Apart form that i also changed the tail for standard configuration to a V tail, currently the elevator hits the carbon boom which reduces the throw, thsi Vtail is much sturdy and cleaner lets hope for the best in todays flight

---

## Devlog 30 — about 1 month ago

**Time recorded:** 41m logged

Attained total hands off autonomy successfully :yayayayayay:
(Ignore the wonky video my mum was trying her best)

Man this is the best day in my life. :yayayayayay:

For starters ill start from yesterday, after coming home i realised i
dont have much pitch stablity cuz the elevator was hitting the carbon
spar, so i ditched conventional tail and made a Vtail instead.

After i set it up in arduplane the next step was to go out and test it,
And oh boy testing i did.

I flew first in FBW A (stablize) And it flew fkin beaut, at 30m altitude
i set it to Auto mode, I had preprogrammed 4 waypoints and then RTL in
the fc.

It flew absolutely perfectly (except for the fact that the winds was WAY
too high i could NOT fly it but the fc could) So after it finished i
tried bringing it home in FBW A mode (worst idea ever :fear: )

The wind literally yeeted it in other direction and i switched on RTL, unfortunately it was wraps :sob-wx:

The plane crashed in a gravel making facility (idk bro)

And i was surprised to find out that ABSOLUTELY NOTHING BROKE!!!!!?!!?! :yayayayayay:

THAT HAS TO BE SOME SORT OF MIRACLE BRO

Like literally the only thing broken was that ONE SINGULAR SOLDER JOIN
CAME LOOSE DIDNT EEN BREAK IT JS CAME LOOSE

So after it crashed we panicked and rushed to the facility, the security
was super helpful and i had telemetry link with it so i was able to
find it in no time :yayayayayayay:

This project was excruciating but absolutely worth it in the end, I will be flying it in more beautiful locations later

The image in the end is the aftermath of the flight (literally spotless)

---

## Devlog 31 — about 1 month ago

**Time recorded:** 32m 41s logged

Drop mechanism done :yayayayayay:

Gonna test this servo drop mech on this aircraft too, hopefully it works

Unfortunately yall have to wait with me till i go back home

---

## Devlog 32 — 21 days ago

**Time recorded:** 4h 12m 15s logged

Airplane :fat-fucking-chud: :smile-hehe: :fat-fucking-chud: :smile-hehe: :fat-fucking-chud: :smile-hehe: :fat-fucking-chud: :smile-hehe: :fat-fucking-chud: :smile-hehe: :fat-fucking-chud: :smile-hehe: :fat-fucking-chud: :smile-hehe: :fat-fucking-chud: :smile-hehe: :fat-fucking-chud: :smile-hehe: :fat-fucking-chud: :smile-hehe:

Im finally learning to properly land this airplane, i did several FBWA runs with this aircraft trying to get my approach right and landing right too

I absolutely suck at both of these things, atp im surprised ik how to build the most stable aircraft but idk how to fly the said stable aircraft :sob-pray:

We cant 100% blame my lack of skill tho cuz if yall notice we can see that the glide ratio is a bit steep, I didnt expect that from this aircraft but due to the autonomous electronics increasing the weight it might be cuz that

Since the old wing mount broke and also i wanted to design a new one with 2 servos so i can get flaps with aileron going, which will hopefully reduce my approach speed and angle

The efficiency of this aircraft is pretty solid ngl, it cruises at around 5-6A which is very good imo, with this pack i can get around 15-20mins

I also made a 4s2p pack for this aircraft using the cells i got from hackclub, i have only bench tested those, the voltage sag is kinda concerning so im not sure if i should fly with them or not

Anyways enjoy the flight and do star the repo if yall like the project so far :thumbs-up:

---

## Devlog 33 — 7 days ago

**Time recorded:** 1h 36m logged

Final flight before i say goodbye to yall :yay:

Please star the repo if u can too :yay:

As stardance is ending heres on final awesome flight video for yall

In this devlog i made custom strobe lights for this plane (thye didnt work on field)

I will be shipping this project on phantom cuz it has better prizes

I had a lot of fun building this project and i hope yall for the best too :heart-seal:

---
