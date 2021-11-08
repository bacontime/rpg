


# A Metric System for Faerun

In many tabletop roleplaying games, 
the **round** of 6 seconds, 
and the **space** or **square** of 5 feet 
serve as basic units of measurement for game mechanics.
Just for fun, let's try to actually construct a 
system of measurement using these as our base units for time  and distance.

The self-imposed rules of the exercise are as follows:
- Derived units are expressed simply in terms of base units. ([Coherence](https://en.wikipedia.org/wiki/Coherence_(units_of_measurement)))
- Larger or smaller units use a consistent exponential power (Though I'm not sticking to decimal).
- And if possible, the resulting system should feel psuedo-medieval, be intuitive to a 21st century American, and be useful for rules of thumb in a tabletop rpg.




## Units of Time.

One of the starting points is that our base unit of time is the **round**, which is equal to to 6 seconds.

Here's an interesting observation:
A 24-hour day is equal to 14400 = 120 times 120 rounds. 
This suggests the use of a base-120 system of units,
which is handy for that psuedo-medieval feel,
because ["hundred" used to refer to units of 120](https://en.wikipedia.org/wiki/Long_hundred#English_unit).
<!--There's also a bit of hobbit flair, because this gives you an excuse to drop "eleventy" into your in-game dialect.-->

Whenever you see "_hundred_" in the rest of this post, you should interpret it as a "long hundred", meaning 120.
For example:

- The base unit of time is the **round** (6 seconds).
- There are a hundred rounds in a **turn** (12 minutes),
- a hundred turns in a **day**,
- a hundred days in a **season** (120 days),
- and roughly a hundred seasons in a **career** (40 years).

And the nice thing about 120 is that it has lots of devisors, so all the other units of time we're used to slot right in [^normaltimeunits]. 

[^normaltimeunits]: A minute is 10 rounds, an hour is 5 turns, a month is a quarter-season, etc.
And a year of 365 days is *a bit more than* 3 seasons, but eh.
This is a fantasy world, so if that bothers you, then you can totally just make the year a bit shorter.
Nobody will even notice.
I've also seen "watch" (sixth of a day, 4 hours, 20 turns) and "march" (third of a day,  8 hours, 40 turns) used as convenient rpg units.

Also, I don't see such a tiny unit being useful in ttrpg time counting, but we can also go one level smaller. 
1/120th of a round is 50 milliseconds.
Just for fun, let's call this a **tick**[^minecraftreference].

[^minecraftreference]: In same video games, the state of the world is updated at a rate seperate from the framerate. The length of time between each update of the game's physics engine is called a "gametick" or "tick". I used to play way too much Minecraft, and in Minecraft, the physics engine of the game updates 20 times a second (once every 50 milliseconds). This unit of time is important for understanding various in-game contraptions. For comparison [here is a 20hz metronome (Warning: loud and annoying sound.)](https://www.youtube.com/watch?v=Zk0LGDBRlCo). I can easily imagine a wizard's workshop full of the background noise of various whatzits softly hissing and clicking at that frequency.





## Units of distance

The size of a square on a tabletop rpg grid is 5 feet. 
Calling the unit of length a "square" would be rather confusing.
<!--We could also call it the "space", but there's a slightly more interesting option:-->
Classically, [the Roman _pace_ was 5 Roman feet](https://en.wikipedia.org/wiki/Pace_(unit)),
so let's call our base unit of length the "pace" (even though it's slightly longer than a Roman pace).
And then in-universe, "space" could be a pormanteau of "square pace", making the battle-grid diagetic.

- There are a hundred **fingerwidths** (half an inch)[^fingerwidthexplanation] in a pace.
- The base unit of distance is the **pace** (5 feet).
- There are a hundred paces in a **field** (600 feet),
- and a hundred fields in a **hex** (about 13.6 miles or 11.85 nautical miles).

The reason for calling 600 feet a "field" is twofold.
Firstly, the traditional american unit of length is the "football field", which is precisely half of this distance.
And secondly, 600 ft is a wee bit shorter than the [660 foot furlong](https://en.wikipedia.org/wiki/Furlong), 
which was traditionally the length an oxen could plow, and hence the width of a field.

It's more traditional to have a 12 mile hex in rpg maps,
but we can comfort ourselves by pretending that all those old rpg modules meant *nautical* miles.
<!--https://thealexandrian.net/wordpress/17320/roleplaying-games/hexcrawl-part-2-wilderness-travel-->
<!--https://paperelemental.blogspot.com/2021/08/NA-hexmaps.html-->

[^fingerwidthexplanation]: Annoyingly there is [no folksy old name for a length of half an inch](https://en.wikipedia.org/wiki/English_units#length). A *third* of an inch is called a barleycorn, and a *sixth* of an inch is called a pica. There are also units called "digit" and "finger", which are 3/4 and 7/8 of an inch, respectively. But I just measured my fingers, and with the exception of the thumbs, they're all closer to half an inch wide. I guess the units were based on big meaty working-man fingers? Maybe "halfinch" isn't such a bad name on its own though. 


## Units of speed.

The unit of speed is **paces per round**. 
It's coherent, and that's the unit of speed which is actually used in game mechanical terms.
Easy peasy.

A side of effect of the consistent exponents is that 
paces per round, fields per turn, and hexes per day are all equivalent units.
That's great for reckoning distances and travel times.
Take a look at how many spaces a character can move in a round on the battlemap. That's the same number of hexes they can move in a day on the worldmap, if they travel all night. Divide by three to get a more reasonable 8 hour travelling day, and double it to get a speed which will drive them to the brink of exhaustion.

Here is a table of speeds for comparison:

|   Description   | Paces/Round | Hex/8hr | mi/hr | km/hr |
|:---------------:|:-----------:|:-------:|:-----:|:-----:|
| Sloth Top Speed |     1/3     |         |  0.2  |  0.3  |
|  Tortoise Speed |      1      |         |  0.6  |  0.9  |
|     Crawling    |      3      |    1    |  1.7  |  2.7  |
|    Brisk Walk   |      6      |    2    |  3.4  |  5.5  |
|   Typical Run   |      12     |    4    |  6.8  |  11.0 |
|   Sailing Ship[^citationforboatspeed]  |      12     |         |  6.8  |  11.0 |
|   Athletic Run  |      18     |    6    |  10.2 |  16.5 |
|    Bike Ride    |      24     |    8    |  13.6 |  22.0 |
|   Clipper Ship  |      30     |         |  17.1 |  27.4 |
|  Cheetah Sprint |     120     |    40   |  68.2 | 109.7 |

Horses can gallop at up to 60 paces per round, but this speed isn't sustainable. 
Over a long distance, horses can travel at about the same average speed as a person on foot[^horsesource]: 2-3 hexes per day.

[^horsesource]: Source: Something I vaguely remember a friend once telling me.

[^citationforboatspeed]: Based on the numbers for East India Company ships in the early 1800s in a fresh breeze.
Kelly, M, and C Ó Gráda (2018), “[Speed under Sail during the Early Industrial Revolution](https://voxeu.org/article/speed-under-sail-during-early-industrial-revolution)”, CEPR Discussion Paper 12576.

And a little calculator:

<iframe src="https://instacalc.com/55199/embed" width="450" height="350" frameborder="0"></iframe>


### Sidenote: Units of Acceleration

The unit of acceleration is **paces per round per round**, or pc/rd^2 for short.

Acceleration from gravity at the Earth's surface is about 232 pc/rd^2. 
That's very close to 240 = 2 * 120, and it's a fantasy world,
so if that's the kind of thing that bothers you, you can crank up gravity about four percent to make *g = 2 fields per round per round = 2 fingerwidths per tick per tick*  exactly.

It's worth noting that it takes about 1 round for a human to reach terminal velocity.

Also, it takes about 1 round for a typical sedan to reach highway speeds of 120 paces per round[^carzerosixtycite].

[^carzerosixtycite]: I just skimmed through [this list of car acceleration speeds](https://www.0-60specs.com/0-60-times/). The sedan model names I recognized take around 4-6 seconds to go from 0mph to 60mph. Increase that number a bit, and you get 1 round to reach cheetah speed.

Those are the only acceleration comparisons that come to my mind.







## Force, Mass, and 

All we're missing to get a full system of measurement (for mechanics at least; we're not getting into electrodynamics here)
is a base unit for force or weight or mass. 

If 








## Units used in TUtbAD

- mile
    - six miles
    - half mile 
    - two miles 
    - 24 miles
    - 12 miles
    - five miles
    - mile and a half
- square mile
    - hundred and twenty square miles
- "thirty feet"
- paces
- fifty pounds
- minute
    - ten/five/five minutes 
- hour
    - half/2/12
- bell
    - quarter bell  
    - alfric and zuki show up at the pub at second bell, mizuki at third, verity at fourth, dawn around first 
    - (pub opens at noon, so if verity gets up at noon, she can't start working right at open, but Verity starts playing at noon, so...)  
    - market opens at third bell
    - fric wants to dungeon at sixth. that's how long isra waits too
    - kitchen shuts down at ninth bell
    - quarter bell of lone time after set of music
    - ([Old ship bells system](http://derelllicht.com/files/Ships_Bell_Code_Info.pdf) doesn't seem to work. Day is 6 watches of 4 hours each, but then aren't enough bells there.
    - If 
- week
- month
    - Garos months (weekly rotation)  
- day
- second
- year
- sixth bell
- cup (kinda)
- barrel (kinda)
- pound
   - ten/thirty/fifty/half



"hundred people"


"hexilization"


## Dozenal measurement systems

### John Volan Primel System

#### Primel Time

- 12 dwells in a day. (Each dwell is two hours.) 
- 12 breathers in a dwell. (Each breather is ten minutes.)
- 12 trices in a breather. (Each trice is 50 seconds.)
- 12 lulls in a trice. (Each lull is 4 and 1/6 seconds.)
- 12 twinklings in a lull. (Each twinkling is a bit more than a third of a second.)
- And the base unit is a vibe or *timel*, which is 1/12 of a twinkling.

#### Primel position, speed, acceleration, etc.

- The fundamental unit is the acceleration from gravity at earth's surface, called an *accerlerel* or *gravity*. I think *grav* would also be a cute name. It's abuot 9.8 m/s/s or 32 ft/s/s.
    - A specific location is given for measuring the gravity strength, which results in a slightly lower number than SI gravity. This position was chosen to make the conversions between Primel and SI exact.
- The unit of speed and velocity is the *velocitel* or *speedel* or *accerlerel timel* or *gravity vibe*, which happens to be approx 1.02 km/h or .93 ft/s  
- The unit of length is called a *lengthel* or *morsel length*, equal to a *gravity vibe^2*, and approximately 1/3 of an inch (archaically called a barleycorn)
    - Thus the unit of velocity can also be defined as *one morsel per vibe* 
    - In colloquial terms, 12 morsel lengths makes a hand length (slightly smaller than the customary 4 inch hand).
    - 12 hands makes an ell length (slightly larger than the old english 45 inch ell).
    - 144 ell lengths makes a stadial length, which is exactly 558 feet, and slightly smaller than the Greek stadion.
    - 12 stadial lengths makes a dromal length (about 1.27 miles, exactly 6696 feet).
    - 12 dromals makes an internal, which is about 15.2 miles, and the limit of a Roman march
    - 3 dozen morsel lengths is about one foot.
    - Powers of two can similarly be accomodated to approximating US volume units.
- The *Areanel* is simply a square morsel or *morsel area*. It's about a tenth of a square inch.
    - A dozen morsel areas is called a stamp area. A dozen of those is a hand area or square hand.
- The *Volumel* is simply a cubic morsel length or *morsel volume*. It's about a tenth of a teaspoon.
    -  A hand volume (cubic hand length) is almost exactly a quart, and about .95 Liters.
    -  A dozen hand volumes is a bucket volume (3 gallons)
    -  A dozen bucket volumes is a drum volum (36.27 gallons, in the range of what's called a "barrel").


#### Other Primel Units

- The *densitel* is the density of water at (4 degrees C)
- The unit of mass is called a *massel* or a *morsel mass*, and is the mass of a cubic morsel of water. It's about .55 grams.
    - Similarly a dozen dozen dozen massels is called a *hand mass*, and is a bit larger than a kilogram.
    - A *bucket mass* is about 25 pounds.
    - A *drum mass* is about 303 pounds.
    - An *ell mass* is about 3632 pounds.
- The *forcel* or *morsel force* is equal to a *gravity massel*, and is aprroximately 5.4 milliNewtons
    - A *hand force* us about 9.34 N  
- The *energel* or *morsel energy* is equal to a *forcel morsel*, and is approximately 44.3 microJoules, or 443 ergs.
    - Likewise for work and heat, except they are contextually called *workel* and *heatel*.
    - A *hand work* is about .92 Joules.
- A hand-pressure (one hand force per hand area) is about .96 kPA




## Binary units? Base-60 units?

