"Steal The Show" by wuwingw

Release along with cover art. Release along with a website. Release along with an interpreter. Release along with the source text.

Chapter One - Setting The Scene

Use full-length room descriptions.

When play begins, say "It's the day of your school's annual talent competition. Being the singing enthusiast that you are, winning this thing this afternoon is the goal you've been building up towards ever since you came fourth last time. The school very rudely declined your request to be excused from all the morning lessons so that you could prepare, and that's why you've just had to put up with a double period of Chemistry, your least favourite subject.

Thankfully the lesson's drawing to an end now, just after a mind-numbingly dull demonstration by the teacher. He, suddenly looking rather flustered, notices the time and realises that he's late for a meeting. You're unlucky enough to be the first person to catch his eye, and you hear him ask you to do him a favour and tidy up the mess on his desk from his practical demonstration.

With that, he disappears, and your classmates (most of whom had packed up about five minutes ago in their eagerness for lunch) quickly leave after him. All of them apart from Leila Carlson, that is. She came second in the talent competition last year and is determined to win this time. You hate each other with mutual enthusiasm.

'Ready to lose this afternoon?' she sneers. Without waiting for a reply, she leaves the room, laughing. God you hate her."

Chapter Two - The Engine

Section One - Variables

A person can be invisib or visib. A person is usually visib. The player is visib.

A thing can be read or not read. A thing is usually not read.

A person can be favoured or not favoured. A person is usually favoured. The player is not favoured.

Use scoring.

Every turn:
	if the score is 5:
		say "[bold type]That's as far as I've got with this game so far. Thanks for playing it! I hope you enjoyed it, despite the little hiccups it undoubtedly contains. Please check back in the future for its completion![roman type]"

Section Two - Rules

The describe what's on scenery supporters in room descriptions rule is not listed in any rulebook.

Section Three - Spicing It Up

Instead of taking a fixed in place thing:
	say "Even if that were viable, it would be a tad pointless."
	
Instead of entering a not enterable thing:
	say "You aspire to be a singer, not a contortionist."
	
[Instead of singing, say "Save that for later."]
Instead of jumping, say "You aspire to be a singer, not an acrobat."
Instead of sleeping, say "You've had way too much coffee for that to be an option."

Singing is an action applying to nothing. Understand "sing" as singing.

Carry out singing:
	if the player is invisib:
		say "It would be amusing to watch everyone freak out, but you'd rather not. Your voice is so uniquely wonderful, after all, that people would recognise it.";
	otherwise:
		say "Save that for later."

Talking is an action applying to nothing. Understand "talk" as talking. Instead of answering someone that, try talking. Instead of telling someone about, try talking. Instead of asking someone about, try talking. Instead of asking someone for, try talking.

Instead of talking:
	if the player is invisib:
		say "It would be amusing to watch everyone freak out, but you'd rather not. Your voice is so uniquely wonderful, after all, that people would recognise it.";
	otherwise:
		say "You don't feel the need."
		
The description of the player is "Definitely worthy of winning the talent competition this year. [if wet]Although, not with some chemical all over your arm![end if][if invisib] However, you've somehow managed to turn yourself, well, invisible.[end if]".

Section Four - Scenes

Beginning is a scene. Beginning begins when the timetable is read. Beginning ends when the Table of Leila Being Annoying is empty.
Lunch is a scene. Lunch begins when play begins.
Meddling is a scene. Meddling begins when Beginning ends. Meddling ends when Niamh is not favoured.
Moving is a scene. Moving begins when Meddling ends. Moving ends when the player is in the dining room.
Serving is a scene. Serving begins when Moving ends. Serving ends when Niamh is invisib.
Lunching is a scene. Lunching begins when Serving ends. Lunching ends when Rosanna is not favoured.
Decisions is a scene. Decisions begins when Lunching ends.

Selling is a scene.
Stephing is a scene.
Jessing is a scene.
[Anning is a scene.]
Victing is a scene. Victing begins when the player carries the guitar. Victing ends when Victoria is not favoured.

Chapter Three - Hello World

Section One - The Chemistry Classroom and Storeroom

Chapter Four - The Game

Section One - Oops

A person can be wet or not wet. A person is usually not wet. The player is not wet.

Chemistry Classroom is a room. The description of the Chemistry Classroom is "You're in one of the several labs in the school. There are lots of cupboards for storing equipment and a whiteboard for the teacher's use. In front of the board is the teacher's desk, and next to it there's a piece of paper stuck to the wall. There is a storeroom to the west, and the exit of the classroom is to the north."

The Random Room is a room.

The cupboard is scenery in the Chemistry Classroom. "There probably used to be some differences between the cupboards, such as one being for glassware, one being for pipettes... This school was never the best at staying organised though. You feel like you can dump random equipment in here and not feel guilty about it." The cupboard is an opaque closed openable container. Understand "cupboards" as cupboard. 

Instead of searching the cupboard:
	If the cupboard is open:
		say "It's full of everything and anything - if its contents are in any way arranged, the system is beyond your comprehension.";
	Otherwise:
		continue the action.

The whiteboard is scenery in the Chemistry Classroom. "The board is currently covered in various diagrams of the structure of atoms." Understand "board" or "diagram" or "diagrams" or "atom" or "atoms" as the whiteboard.

The desk is scenery in the Chemistry Classroom. The desk can be tidy or untidy. The desk is untidy. Understand "teacher's desk" or "table" as the desk. The printed name of the desk is "the teacher[']s desk".
Instead of examining the desk:
	say "Behind this wooden thing is where the teacher stands when he's teaching. [if untidy]Some of the remnants of his latest demonstration remain, namely [a list of things on the desk]. Better get a move on and tidy that up.[otherwise]It's looking very clean, if you say so yourself.[end if]". 
Instead of rubbing the desk, say "You just need to get rid of the stuff on it."

Every turn:
	If the number of entries in the list of things on the desk is 0:
		now the desk is tidy;
	Otherwise:
		now the desk is untidy.

The measuring cylinder is a portable undescribed thing on the desk. The description of the cylinder is "This can just go in the cupboard."
The beaker is a portable undescribed thing on the desk. The description of the beaker is "This can just go in the cupboard."
The half-filled flask is a portable undescribed thing on the desk. The description of the flask is "It contains some sort of acid that the teacher was using.[if not edible] It should be kept out of the way of clumsy Year 7s.[end if]"

Instead of dropping the cylinder, say "I'm not sure that counts as tidying up." Instead of dropping the beaker, say "I'm not sure that counts as tidying up." Instead of dropping the flask, say "I'm not sure that counts as tidying up."
	
After inserting the cylinder into the cupboard:
	say "Good job.";
	now the cylinder is off-stage.
After inserting the beaker into the cupboard:
	say "There you go.";
	now the beaker is off-stage.
Instead of inserting the flask into the cupboard:
	say "There might be somewhere better to put it, where clumsy Year 7s can't get to it."

The Storeroom is west of the Chemistry Classroom. "This room contains the various chemicals needed for Chemistry experiments, and it also acts as an office for the one and only Chemistry teacher. You can see a shelf full of various bottles and flasks. The main classroom is back to the east."

Instead of going west from the Chemistry Classroom:
	if the desk is untidy:
		say "Maybe you should finish up in here first. You're not that desperate for lunch.";
	otherwise if the player is carrying the cylinder:
		say "The empty equipment should be left here.";
	otherwise if the player is carrying the beaker:
		say "The empty equipment should be left here.";
	otherwise if the storeroom is dark:
		say "It's locked.";
	otherwise:
		continue the action.
		
Instead of going north from the Chemistry Classroom:
	if the desk is untidy:
		say "Maybe you should finish up in here first. You're not that desperate for lunch.";
	otherwise if the player is carrying the cylinder:
		say "The empty equipment should be left here.";
	otherwise if the player is carrying the beaker:
		say "The empty equipment should be left here.";
	otherwise if the player is carrying the flask:
		say "What exactly do you plan on doing with that acid? (you don't hate Leila [italic type]that[roman type] much)[line break]";
	otherwise:
		continue the action.

The shelf is a scenery supporter in the storeroom.

Instead of examining the shelf, say "It's full of bottles and containers of all shapes and sizes."
Instead of searching the shelf, try examining the shelf.
The chemicals are scenery on the shelf. The description of the chemicals is "Best not to touch anything". Understand "chemical" or "bottle" or "bottles" or "container" or "containers" as the chemicals. The chemicals are plural-named.

After putting the flask on the shelf:
	say "That should do it.";
	now the flask is edible.

Instead of taking the flask:
	if the flask is edible:
		say "It looks fine where it is.";
	otherwise:
		continue the action.

Before eating or drinking the flask:
	say "What? Do you have a death wish?";
	stop the action.
	
Instead of going east from the storeroom:
	if the flask is edible:
		if the player is visib:
			if the player is not wet:
				say "As you turn to leave, you stumble over your shoelaces and accidentally spill a glass of some brightly-coloured chemical all over your arm. You should probably wash that off somewhere...";
				now the player is wet;
				continue the action;
			otherwise:
				continue the action;
		otherwise:
			continue the action;
	Otherwise:
		continue the action.
		
The First Floor Corridor is north of the Chemistry Classroom. "This is the floor where the science labs are found. The Chemistry classroom is to the south, Physics to the southeast, Biology to the northwest, and there's also a bathroom to the northeast. You can go up to the second floor or down to the ground floor from here.[if Lunch is happening][paragraph break]The place is utterly deserted because everyone's either queuing for lunch or eating it.[end if]"

The First Bathroom is northeast of the First Floor Corridor. "It's one of the smaller bathrooms in the school, literally conisisting of just one cubicle and a sink. The exit lies to the southwest." The printed name of the First Bathroom is "Bathroom".

The cubicle is scenery in the First Bathroom. "It's everything you'd expect a toilet cubicle to be."The cubicle is an enterable container. Instead of entering the cubicle, say "You don't need to right now."

The sink is scenery in the First Bathroom. "It's an everyday ceramic sink, with a tap that's dripping slightly."

Washing is an action applying to nothing. Understand "wash arm" and "wash my arm" or "use sink" or "use the sink" or "wash" or "wash chemical" or "wash me" as washing.  Instead of switching on the sink, try washing. 
The tap is scenery in the First Bathroom. "It's dripping slightly. You wonder how much water it's wasted in its lifetime." Instead of switching on the tap, try washing. Instead of opening the tap, try washing. Instead of turning the tap, try washing. Instead of touching the tap, try washing.

Check washing:
	if the player is not in the first bathroom:
		say "I hate to point out the obvious, but there's no sink here.";
		stop the action;
	otherwise if the player is not wet:
		say "That doesn't seem necessary.";
		stop the action.

Carry out washing:
	now the player is not wet;
	now the player is invisib.
	
Report washing:
	say "You go to wash your arm in the sink, but then you realise something rather peculiar - you can't actually see your arm. Or your hand. Or any part of you or your clothing, for that matter... What was in that glass you spilt?
	
You feel yourself start to panic. This is not good. You can't win a competition if nobody can even see you! How is this even possible?

There'd better be some sort of remedy for this back in that storeroom..."

Every turn when the player is wet:
	if the player has been wet for one turn:
		say "[one of]Your arm is beginning to feel a bit weird[or]Okay, your arm is feeling really weird now[or]This spillage had better not somehow affect your award-worthy singing voice[stopping]."
	
Section Two - Now What

The Physics Classroom is southeast of the First Floor Corridor. "This lab is mainly used for Physics. You can see various equpiment around the room, such as variable power supplies and cables.[if player is invisib] I doubt you'll find anything to remedy your, uh, invisibility in here.[end if] The corridor is back to the northwest."

The equipment is scenery in the Physics Classroom. Instead of doing anything to the equipment, say "It's stuff that's best left alone." Understand "power supplies"or "supplies" or "power supply" or "supply" or "cable" or "cables" as the equipment.

The Biology Classroom is northwest of the First Floor Corridor. "This is the main Biology lab, and ever since the teacher conducted an experiment on decomposition, it's smelt a bit off.[if player is invisib] There's unlikely to be anything to help you here.[end if] The corridor is to the southeast."

The Science Floor is a region. The First Floor Corridor, Biology Classroom, Chemistry Classroom, Physics Classroom, Storeroom and First Bathroom are in the Science Floor.

Instead of smelling:
	if the player is in the Biology Classroom:
		say "Eesh.";
		stop the action;
	if the player is in the Lunch Queue Corridor:
		say "You can already smell the fish and chips. You're too focused on wanting to win the competition to feel hungry though.";
		stop the action;
	if the player is in the dining room:
		say "The fish and chips smells brilliant, but no, your mind is on thwarting Leila and winning this competition.";
		stop the action;
	if the player is in the locker room:
		say "A mixture of deodarant and old socks.";
		stop the action;
	otherwise:
		continue the action.
		
Instead of going south from the First Floor Corridor:
	if the storeroom is dark:
		continue the action;
	otherwise if the player is invisib:
		say "Just after you walk back into the Chemistry classroom, none other than your teacher comes in after you, muttering irritatedly about a cancelled meeting. He seems to see straight through you, confirming your worst suspicions, and instead nods contentedly at the cleaned-up desk. Then, to your horror, he goes to the door of the storeroom and locks it shut before pocketing the key. With that, he leaves the classroom.[paragraph break]If there was any remedy in the storeroom, you won't be getting to it until the teacher comes back to unlock the door. And who knows when that will be?";
		now the storeroom is dark;
		continue the action;
	otherwise:
		continue the action.
		
The timetable is scenery in the Chemistry Classroom. The description of the timetable is "It's the timetable of when there are lessons happening in this room.[if player is invisib][paragraph break]You scan down the column for Friday, and see that there'll be another lesson in here last period. In other words, the storeroom won't be unlocked until the teacher comes back for that lesson.[end if]".
Understand "piece of paper" or "paper" as the timetable.
Instead of taking the timetable, say "There's no point."
After examining the timetable:
	if the timetable is read:
		continue the action;
	otherwise if the player is invisib:
		now the timetable is read;
		say "Looks like you're stuck being invisible until then, but hey, that might not be so bad? Maybe you could seize this opportunity to up your chances for this afternoon. Leila [italic type]was[roman type] asking for trouble earlier... Now, where is she?";
	otherwise:
		continue the action.
		
Section Three - To The Lunch Queue

The East Ground Floor Corridor is below the First Floor Corridor. "This is the main corridor of the school with your typical blue carpet. It extends further to the west. To the east is an exit leading into the front courtyard. Reception is found to the north, and to the south is the school's music classroom. You can go up to the first floor from here.[if Lunch is happening][paragraph break]The place is utterly deserted because everyone's either queuing for lunch or eating it.[end if][if Beginning is happening][paragraph break]You swear you can hear Leila's horrible and nasal voice to the west, towards the dining room.[end if]".

The typical blue carpet is scenery in the east ground floor corridor. "Does anyone ever vacuum this place?"

The Second Floor Corridor is above the First Floor Corridor. "On this floor is a general-purpose classroom to the north, as well as the art workshop to the south. You can do down to the first floor from here.[if Lunch is happening][paragraph break]The place is utterly deserted because everyone's either queuing for lunch or eating it in the dining room.[end if]".

The General Classroom is north of the Second Floor Corridor. "You occasionally have Maths lessons in here. The exit is back to the south."

Instead of going up from the First Floor Corridor:
	if the player is wet:
		say "You don't really fancy keeping this possibly-dangerous chemical on your arm for much longer! You'd best find somewhere to wash it off.";
	otherwise if the storeroom is dark:
		if the timetable is not read:
			say "You should find out when you ought to come back to un-invisiblise yourself first. There must be a timetable somewhere in the Chemistry classroom.";
		otherwise:
			continue the action;
	otherwise if the timetable is not read:
		say "You'd really prefer to make sure there was a way to turn yourself un-invisible before you went around wandering the school. This is the absolute last thing you needed before today's competition!";
	otherwise:
		continue the action.

Instead of going down from the First Floor Corridor:
	if the player is wet:
		say "You don't really fancy keeping this possibly-dangerous chemical on your arm for much longer! You'd best find somewhere to wash it off.";
	otherwise if the storeroom is dark:
		if the timetable is not read:
			say "You should find out when you ought to come back to un-invisiblise yourself first.";
		otherwise:
			continue the action;
	otherwise if the timetable is not read:
		say "You'd really prefer to make sure there was a way to turn yourself un-invisible before you went around wandering the school.";
	otherwise:
		continue the action.

Reception is north of the East Ground Floor Corridor. "Reception consists of a counter[if the receptionist is in reception], behind which the receptionist is sitting[end if]. Directly opposite the counter is the block of teachers['] pigeonholes where homework is handed in. The main corridor is to the south."

The West Ground Floor Corridor is west of the East Ground Floor Corridor. "This part of the main corridor has a large skylight, letting the sunlight stream through. It extends further to the east. To the north is the corridor that leads to the dining room[if Lunch is happening], and it's currently packed full of people queuing for lunch[end if]. The one and only locker room lies to the west.[if Beginning is happening][paragraph break]Leila's annoying voice is getting louder.[end if]".

The large skylight is scenery in the west ground floor corridor. "It's a nice touch to this otherwise dreary corridor." Understand "sunlight" or "light" or "steram" as the skylight.

To say state presence:
	say "[if leila is in the lunch queue corridor]Leila and her disciples are here, begging to be meddled with.[end if][line break]".

The Lunch Queue Corridor is north of the West Ground Floor Corridor. "During lunchtime, this place is always crammed with students shouting, singing and trying to push in the queue. Having had to put up with it for several years now, you're used to it.[if unvisited] Obviously, now that you're invisible, people seem to be knocking into you accidentally a lot, but none of them really seem to notice anything bizarre. Fish and chips is the only thing on their mind right now.[end if] The dining room is further north.[if unvisited][paragraph break]You pick Leila out of the crowd quickly, surrounded by her seven disciples as you like to call them. You hate them too, but not nearly as much as you hate her.[end if][if not unvisited][state presence][end if]".

Leila is an undescribed woman in the Lunch Queue Corridor. The description of Leila is "You hate her. You hate her stupid brunette hair and her stupid voice. You want to make sure she has no chance at winning."

The crowd is a backdrop. "You hope they're all ready to applaud you this afternoon." The crowd is in the lunch queue corridor and the west ground floor corridor. Understand "people" or "students" or "student" or "shouting" or "queue" or "pack" as the crowd.

The group of disciples is an opaque enterable scenery container in the Lunch Queue Corridor. "They're all equally awful if they can bear to be around Leila all of the time."

Instead of doing anything other than examining the group of disciples:
	if the noun is the group of disciples:
		say "You make no sense sometimes.";
	otherwise:
		continue the action;

Sel is a woman in the group of disciples. The description of Sel is "From what you know, Sel is obsessed with fashion. Really obsessed. She apparently makes her own clothes using the equipment in the school's art workshop."
Stephanie is a woman in the group of disciples. The description of Stephanie is "She's literally always chewing gum, even though it's banned in the school. From rumours you've heard, she's actually a very good singer, but Leila somehow forced her into being a dancer for her entry instead."
Jessica is a woman in the group of disciples. The description of Jessica is "She's always wearing nerdy glasses, which is fair enough, because she's probably one of the smartest people in the year, not that you'd like to admit it. Why she's idiotic enough to put up with Leila, you don't know."
Anne is a woman in the group of disciples. The description of Anne is "Her skirt is even shorter than Leila's, and all the teachers hate her because she never studies for anything and never hands in any of her homework."
Rosanna is a woman in the group of disciples. The description of Rosanna is "Blonde, ditsy, and very very clumsy."
Victoria is a woman in the group of disciples. The description of Victoria is "She thinks she's a lot better at playing guitar than she actually is. You know she owns a very nice guitar, though."
Niamh is a woman in the group of disciples. The description of Niamh is "She seems to be out of school a lot because she's falling ill all the time. Suddenly, her eyes widen and her mouth opens, like she's about to sneeze - but she manages to hold it in."

["'Sel, you've put the jacket I told you to personalise into my locker, right?' says Leila to one of her disciples."
"'I hope you've practised that guitar part to perfection, Victoria,' says Leila to one of her disciples."
"'Stop chewing gum, Stephanie!' says Leila to one of her disciples."]

Table of Leila Being Annoying
event description
"'I expect all of you to dance perfectly behind me in my performance tonight!' says Leila to her disciples."
"'Rosanna, I hope your clumsiness is at a low today,' says Leila to one of her disciples."
["'Sel, have you put the jacket you personalised for me into my locker yet?' says Leila to one of her disciples."]
["'I hope you've practised that guitar part to perfection, Victoria,' says Leila to one of her disciples."]
"'Stephanie, stop chewing gum!' says Leila to one of her disciples. 'Hey,' Stephanie says hotly, 'Don't complain or I'll quit the group and enter solo. Do you want more competition?' Leila bristles but remains silent."
"'You better not have a cold anymore, Niamh,' says Leila to one of her disciples. 'It's disgusting when you sneeze.'"
"Leila seems to have vented out all her irritation and is now impatiently tapping her foot, waiting for the queue to advance. Now, if only you could think of some way to make sure none of those disciples were performing with Leila this afternoon... That would definitely dampen her chances!"

Every turn during Beginning:
	if the player is in the Lunch Queue Corridor:
		say "The queue shifts forward a little bit.[if the Table of Leila Being Annoying is not empty][line break][end if]";
		repeat through the Table of Leila Being Annoying:
			say "[event description entry][paragraph break]";
			blank out the whole row;
			stop.

Every turn during Meddling:
	say "The queue shifts forward a little bit."
	
Every turn during Meddling:
	if Meddling has been happening for exactly ten turns:
		say "Niamh sniffs a little too loudly, and Leila throws her a glare.";
	if Meddling has been happening for exactly 15 turns:
		say "Niamh's face scrunches up, like she's trying her best to hold in a sneeze."

Instead of going from the Lunch Queue Corridor:
	if Beginning is happening:
		say "You should stick around; eavesdropping on Leila is bound to be useful.";
	otherwise if Meddling is happening:
		say "There's still mischief to be done here.";
	otherwise:
		continue the action.

Instead of going south from the Lunch Queue Corridor:
	if Moving is happening:
		say "You think it might be fun to trail Leila into lunch.";
	otherwise:
		continue the action.
		
		[we got up to here in fixing it ish idk]
		
Section Four - Achoo

Sneezing is an action applying to nothing. Understand "sneeze" or "cough" or "sniff" or "achoo" as sneezing.

Check sneezing:
	if the player is not in the Lunch Queue Corridor:
		say "You don't feel the need to.";
		stop the action;
	otherwise if Beginning is happening:
		say "You don't want to interrupt anything Leila might say next.";
		stop the action;
	otherwise if Niamh is not favoured:
		say "No need for that anymore.";
		stop the action;
	otherwise:
		continue the action.

Carry out sneezing:
	increase the score by 1;
	now Niamh is not favoured;
	now Niamh is scenery;
	now Niamh is off-stage.
		
Report sneezing:
	say "You move towards Niamh and deliver the biggest and most convincing fake sneeze you can, and then you hastily step back out of the way. Immediately, Leila's face scrunches up with disgust.[paragraph break]'Niamh!' she yells. 'I thought you said your cold was gone! Ew! Stay away from me!'[paragraph break]Niamh's confused and upset face is gold. 'But it wasn't-' she tries, but Leila's not having any of it.[paragraph break]'You are so not performing with me; I can't have you sneezing in the middle of my winning performance!' Leila cries. Niamh's expression becomes even more dismal as a result, almost to the extent that you pity her. But not quite. Rubbing her eyes, she leaves the lunch queue and disappears out of the corridor.[paragraph break]One down, six to go."
	
Instead of attacking someone:
	say "You aspire to be a singer, not a wrestler.";

Instead of attacking Leila:
	say "You're trying to be subtle here."
Instead of tripping Leila:
	say "That will annoy her, yes, but other than that, it's not going to help."


Tripping is an action applying to one thing. Understand "trip [someone]" or "trip up [someone]" or "poke [someone]" or "tickle [someone]" or "shove [someone]" as tripping.

Instead of pushing something:
	if the noun is a person:
		try tripping the noun;
	otherwise:
		continue the action.

Check tripping:
	if the noun is not Rosanna:
		say "You wouldn't gain much from doing that.";
		stop the action;
	otherwise if Lunching is happening:
		say "That's a bit hard, seeing as she's sitting down.";
		stop the action;
	otherwise:
		continue the action.
		
Report tripping:
	say "You successfully get Rosanna to lose her footing, but a couple of the other disciples help to keep her upright and Leila doesn't notice a thing."
	
Instead of attacking Rosanna:
	if Lunching is happening:
		say "Rosanna flinches a little bit, but she doesn't move enough to knock over Leila's cup.";
	otherwise:
		say "You successfully get Rosanna to lose her footing, but a couple of the other disciples help to keep her upright and Leila doesn't notice a thing."
	
Section Five - Into Lunch

Every turn during Moving:
	if Moving has been happening for exactly one turn:
		say "Leila and her disciples finally reach the front of the queue, and proceed into the dining room to be served their fish and chips. Rosanna, the clumsy one, stumbles over thin air, and Leila rolls her eyes in exasperation.";
		now Leila is in the dining room;
		now the group of disciples is in the dining room.
		
The Dining Room is north of the Lunch Queue Corridor. "The room was redone three or four years ago, and it's now very modern and very colourful compared to what it used to be. At the eastern end is where people are served their food, and then you move towards the various rows of tables to find a seat. The lunch queue corridor is to the south, but to save students the effort of shoving back and forth through the chaos, there's another exit to the east.[if unvisited][paragraph break]Leila and the disciples are about to be served.[end if]"

The Courtyard is east of the Dining Room. 

Instead of going from the Dining Room:
	if Serving is happening:
		say "Be patient! A good opportunity is bound to come up once they settle down...";
	otherwise if Lunching is happening:
		say "No, no, there's definitely something you can do here...";
	otherwise:
		continue the action.

After going south from the Dining Room:
	if Decisions is happening:
		say "You bravely push back through the crowds of hungry students until you're back out of the lunch queue corridor.";
		now the player is in the West Ground Floor Corridor.
		
Report going east from the Dining Room:
	if Decisions is happening:
		say "You decide there's not much more you can do here, which is good - you want to be able to take full advantage of the rest of the school being relatively empty. You head outside into the..."

Every turn during Serving:
	if the player has been in the dining room for exactly one turn:
		say "Leila and the disciples are helping themselves to fish and chips.";
		say "[line break]'Anne, you handed in your History homework, right?' Leila asks. 'Yeah,' says Anne dismissively, 'I think.' Leila narrows her eyes. 'You possibly getting a detention this afternoon is a serious matter,' she growls.";
	if the player has been in the dining room for exactly two turns:
		say "Leila and the disciples are now filling cups of water to put on their trays.";
		say "[line break]'Actually doing your homework on time really isn't that bad, you know, Anne,' says Jessica, readjusting her glasses. Anne rolls her eyes. 'Well, of course the person who's willing to spend an evening at a Maths lecture would say that!' she exclaims, and everyone apart from Jessica laughs.";
	if the player has been in the dining room for exactly three turns:
		say "Leila and the disciples are now taking cutlery from the boxes.";
	if the player has been in the dining room for exactly four turns:
		say "Leila and the disciples finally find an empty table and settle down to eat.";
		now Niamh is invisib;
		now Niamh is in the random room.
		
The cutlery is scenery in the dining room. "Don't be getting any overdramatic ideas now..."

The tray is scenery in the dining room.

The food is scenery in the dining room. "It smells so good... But eating isn't on your list of priorities right now." Understand "fish" or "chips" or "fish and chips" as the food.
		
The lunch tables are scenery in the dining room. "There's lots of tables, and they're mostly full.[if Leila is in the dining room] Leila and her disciples are sat at one.[end if][if Lunching is happening] All of them are cutting up and eating their fish, other than Rosanna who is eating her chips with her fingers. Her fork lies tantalisingly close to the edge of the table.[end if]". The lunch tables are plural-named. Understand "table" or "tables" or "rows" as the lunch tables. The lunch tables are a supporter.

Every turn during Lunching:
	say "Leila and the disciples are sitting down eating. [if a random chance of 1 in 4 succeeds]Leila takes a sip of her cup of water, which sits rather close to one of Rosanna's arms.[end if]".
	
Leila's cup is scenery in the dining room. "Leila's cup of water,[if not spilled] which is simply begging to be knocked over[otherwise] which has been knocked over[end if]."

Leila's cup can be spilled or not spilled. Leila's cup is not spilled.

Knocking is an action applying to one thing. Understand "knock [something]" or "knock over [something]" or "spill [something]" as knocking.

Instead of pushing Leila's cup, try knocking Leila's cup. Instead of taking Leila's cup, say "You can't just pour it on her head and hope nobody will find it suspicious, if that's what you're thinking."

Check knocking:
	if the noun is Leila's cup:
		say "You need to find a way to do it that very clearly frames someone.";
		stop the action;
	if the noun is Rosanna's fork:
		if Rosanna is favoured:
			continue the action;
		otherwise:
			say "The damage has already been done.";
			stop the action;
	otherwise:
		say "You make no sense sometimes.";
		stop the action.
		
Carry out knocking:
	now Rosanna's fork is meddled;
	now Rosanna is not favoured;
	now Rosanna is off-stage;
	increase the score by 1;
	now Leila's cup is spilled.

Report knocking:
	say "You push Rosanna's fork off the edge of the table, and it hits the ground with a loud clatter. Leila and the disciples all immediately turn to look at Rosanna, who blushes, before trying to bend down to reach her fork. To your joy, her elbow hits Leila's cup, spilling water all over the brunette. You have to resist the urge to cheer.[paragraph break]'Rosanna!' Leila screeches. 'Why are you always so clumsy?' she continues furiously as she steals Sel's napkin to dry herself. 'I am not risking you falling over this afternoon! You are so out!'[paragraph break]Unlike Niamh, Rosanna doesn't even try to question it. She swallows, picks up her tray of food and silently leaves the table, leaving her fork discarded on the floor.[paragraph break]Another one down, five to go."

Rosanna's fork is scenery in the dining room. "Rosanna's fork.[if not meddled] She's not using it at the moment.[otherwise] Thanks to you, it's now lying on the floor with nobody to rescue it.[end if]". Understand "fork" as Rosanna's fork.

Rosanna's fork can be meddled or not meddled. Rosanna's fork is not meddled.

Instead of taking Rosanna's fork:
	say "People are bound to notice that something's up if a fork randomly starts floating in midair."
	
Instead of pushing Rosanna's fork, try knocking Rosanna's fork.

Section Five - Freedom

Exotic is a region. The Locker Room, reception and the Music Classroom are in Exotic.

Instead of going to Exotic:
	if Beginning is happening:
		say "You should track Leila down first.";
	otherwise:
		continue the action.

The description of the Courtyard is "The courtyard is essentially just the free space around the sides of the school building. It's partly lawn and partly patio. During the summer, people like to bring packed lunches and eat outside, but today isn't nearly warm enough. People also like to leave their bags here whilst they have lunch, which is why there's a massive pile in the corner.There's an entrance into the dining room to the west, and a path to the south leads round to the front entrance of the school.[if Lunch is happening][paragraph break]The place is utterly deserted because everyone's either queuing for lunch or eating it.[end if]"

The East Ground Floor Corridor is south of the Courtyard.

The Random Room is east of the East Ground Floor Corridor.

Instead of going east from the East Ground Floor Corridor:
	if Beginning is not happening:
		say "You head out of the front door and round the school building, finding yourself in the...";
		now the player is in the Courtyard;
		stop the action;
	otherwise:
		say "You should track Leila down first.";
		stop the action.

Report going south from the courtyard:
	say "You walk around the side of the school building and head in through the front doors, ending up in the..."

The Locker Room is west of the West Ground Floor Corridor. "The only locker room in the school - it's just as well it's huge. There are rows and rows of blue lockers, arranged by yeargroup and then alphabetically. It doesn't smell that great. The corridor is back to the east.[if Lunch is happening][paragraph break]The place is utterly deserted because everyone's either queuing for lunch or eating it.[end if]"

Section Six - Cutting The Strings

The Music Classroom is south of the East Ground Floor Corridor. "The room has large old-fashioned windows, a wooden floor and, most significantly, a piano. You sometimes come in here to practise alone after school. The storeroom for students['] instruments is to the southeast. The exit lies to the north."

The piano is scenery in the Music Classroom. "It's not of the best quality, and its surface is covered in scratches from ungrateful students."

Playing is an action applying to one thing. Understand "play [something]" as playing.

Check playing:
	if the noun is not the piano:
		say "You make no sense sometimes.";
		stop the action;
	otherwise if the noun is the guitar:
		continue the action;
	otherwise:
		continue the action.
		
Report playing:
	say "[one of]The place is deserted, so you quickly rattle through one of your favourite pieces by Gershwin.[or]The place is deserted, so you briefly practise the piano part for this afternoon's perfromance.[or]That's enough for now - you should get back to thwarting Leila![stopping]"
	
The Instruments Storeroom is southeast from the Music Classroom. "It's a small and dimly lit room with various shelves for putting instruments of all sorts on. You're surprised at how tidy it is today - normally it's a mess. Still, it'll take some searching through them to find anything. The main classroom is to the northwest."

The shelves are scenery in the Instruments Storeroom. "They're all very full." The shelves are plural-named. The shelves are a supporter. Understand "shelf" as the shelves.

The guitar is on the shelves. The guitar can be meddled or not meddled. The guitar is not meddled. The description of the guitar is "Victoria's fancy acoustic guitar,[if not meddled] currently with all six strings intact[otherwise] now with each of the strings cut[end if]." The guitar is undescribed. Understand "strings" or "string" as the guitar.

Instead of examining the guitar:
	if the guitar is on the shelves:
		say "You don't know exactly where it is yet.";
	otherwise:
		continue the action.

Instead of searching the shelves:
	if the guitar is on the shelves:
		say "You methodically scan through the various labelled instruments, and aha! Your efforts are rewarded when you find Victoria's guitar. You take it down from the shelf.";
		now the player carries the guitar;
	otherwise:
		say "You've found what you need. Any further searching would probably risk causing an avalanche of expensive instruments."
	
Instead of playing the guitar:
	if the guitar is not meddled:
		say "You hesitantly strum a few strings, but you really have no idea what you're doing.";
	otherwise:
		say "Seeing as all the strings are cut, that's leaning a bit on the impossible."
		
Instead of dropping the guitar:
	if the guitar is not meddled:
		say "You want to make sure there'll be no way Victoria can accompany Leila this afternoon.";
		stop the action;
	otherwise:
		continue the action.
		
After dropping the guitar:
	say "You leave the ruined guitar on the ground. Once Victoria manages to find it, she'll be forced to drop out of Leila's entry.";
	now Victoria is not favoured;
	increase the score by 1.
		
Instead of taking the guitar:
	if the guitar is not meddled:
		try searching the shelves;
	otherwise:
		say "There's nothing more you need to do to it.";
		stop the action.
		
Scissorcutting is an action applying to two things. Understand "cut [something] with [something]" as scissorcutting.

Check scissorcutting:
	if the noun is the guitar:
		if the second noun is the scissors:
			try cutting the guitar;
	otherwise:
		say "You make no sense sometimes."
		
Instead of cutting the guitar:
	if the player carries the scissors:
		say "You cut every single one of the six strings, and, somewhat worryingly, you don't feel guilty about it at all.";
		now the guitar is meddled;
		try dropping the guitar;
	otherwise:
		say "It's a good idea, but you don't have anything to do it with.";
		stop the action.
		
The Art Workshop is south of the Second Floor Corridor. "It's a large and airy room that you can imagine would be a nice place to work on a painting. There's a set of drawers for supplies against one of the walls. The corridor is back to the north."

The drawers are an opaque openable closed scenery container in the Art Workshop. "It's a very wide set of drawers, and you imagine they're probably as disorganised as the cupboards in the Chemistry classrooom." Understand "set of drawers" or "set" or "drawer" as the drawers. The drawers are plural-named.

The scissors are in the drawers. The description is "They're pretty big as far as scissors go." The scissors are plural-named. The indefinite article is "a pair of".

Instead of searching the drawers:
	if Victing is happening:
		if the scissors are in the drawers:
			say "You open each drawer and look through, until you find yourself a strong-looking pair of scissors. Bingo.";
			now the player carries the scissors;
			stop the action;
		otherwise:
			say "You've already found what you need.";
			stop the action;
	otherwise if the guitar is meddled:
		say "You've already found what you need.";
		stop the action;
	otherwise:
		say "It's a bit pointless, seeing as you don't actually know what exactly you're looking for, and you know for a fact these drawers are even less organised than the Chemistry cupboards.";
		stop the action.
		
Instead of opening the drawers, try searching the drawers.

[just an idea - have the room descriptions etc. use vocab related to that subject. so "imagine" or art, "predict" for sciences....]

Section Seven - The Failed Intellectual

[put the master key at reception
have a folder with anne's history teacher's name written on it
can't put scissors into steph's locker until both vict and sel are not favoured
whiteboard/noticeboard in the corridor]

The rows of lockers are scenery in the Locker Room. "You'll have to specify whose locker - there's a lot of them in here." The rows of lockers are plural-named. Understand "rows" or "row" or "lockers" or "locker" as the rows of lockers. The rows of lockers are an opaque container.

Instead of doing anything to the rows of lockers, say "You'll have to specify whose locker - there's a lot of them in here. "

Leila's locker is in the rows of lockers. Understand "Leila's locker"  or "Leila's" as Leila's locker. The description is "The label reads 'Leila Carlson'." Leila's locker is an openable closed container.

Stephanie's locker is in the rows of lockers. Understand "Stephanie's" or "Steph's" as Stephanie's locker. The description is "The label reads 'Stephanie Gold'." Stephanie's locker is a locked container. Understand "Steph's locker" as Stephanie's locker.

Anne's locker is in the rows of lockers. Understand "Anne's" as Anne's locker. The description is "The label reads 'Anne Reed'." Anne's locker is a locked container.

After unlocking something (called the chosen locker) with the master key in the locker room:
	try opening the chosen locker.
	
Instead of unlocking Leila's locker with the master key:
	try opening Leila's locker.

A history folder is in Anne's locker.
Instead of examining the history folder:
	say "A red history folder, with 'Mr Wilson' written down its spine - that must be the name of Anne's history teacher."
Instead of searching the history folder:
	say "You flip through but you can't seem to find anything that looks like homework to be handed in."
Instead of taking the history folder:
	say "There's no point in taking it."
Instead of cutting the history folder:
	say "A nice thought, but that will turn the disciples against each other, not against Leila."

Random locker is in the rows of lockers. Understand "Rosanna's" or "Selena's" or "Sel's" or "Jessica's" or "Victoria's" or "Niamh's" as the random locker. Instead of doing anything to the random locker, say "You don't need to do anything with her locker."


The receptionist is a woman in Reception. "[if distracted]The receptionist is fumbling around trying to fix her monitor.[otherwise]The receptionist is busy tapping away at her computer.[end if]". The description of the receptionist is "[if distracted]She's currently trying to figure out why her monitor's suddenly gone blank.[otherwise]She doesn't look like she wants to be interrupted in whatever it is she's doing on the computer.[end if]". The receptionist can be distracted or not distracted. The receptionist is not distracted.

The counter is scenery in Reception. "Made of wood, and not particularly fascinating." The counter is a supporter.

The recep's desk is scenery in Reception. "It's a low table behind the counter[if untidy], and on it you can see the locker room's master key[end if]." The recep's desk can be untidy or tidy. The recep's desk is untidy. Understand "receptionist's desk" as the recep's desk.

The master key is scenery on the recep's desk. "It's the key that can open every single locker in the locker room. It seems foolish until you think about how common it is for people to lose their own keys." The master key unlocks Leila's locker and Stephanie's locker and Anne's locker.

Instead of taking the master key:
	if the receptionist is distracted:
		say "Whilst the receptionist is occupied, you quickly reach out over the counter and snatch the key.";
		now the player carries the master key;
		now the recep's desk is tidy;
	otherwise:
		say "The receptionist would notice."

Instead of doing anything other than examining the master key:
	if the noun is the master key:
		say "The receptionist would notice.";
	otherwise:
		continue the action;

The block of pigeonholes is scenery in Reception. "Each teacher has their own pigeonhole here. They're arranged alphabetically." The block of pigeonholes is an opaque container. Instead of searching the block of pigeonholes, say "You need to know whose pigeonhole you're looking for before you go looking. There must be some way you can find out who Anne has for History..."

Mr Wilson's pigeonhole is an undescribed thing in the block. Understand "mr wilson" or "mr wilsons" or "mr wilson's" or "wilson" or "wilsons" or "wilson's" or "wilsons pigeonhole" or "mr wilsons pigeonhole" as Mr Wilson's pigeonhole.
Instead of examining Mr Wilson's pigeonhole, say "The pigeonhole belonging to Mr Wilson, with various sheets of paper inside." Mr Wilson's pigeonhole is a container.
Anne's homework is in Mr Wilson's pigeonhole. The description is "Anne's history homework, addressed to Mr Wilson. It's actually quite neat, like she's put a lot of effort into it."
Instead of searching Mr Wilson's pigeonhole:
	if Anne's homework is in Mr Wilson's pigeonhole:
		say "You go through the sheets, and relatively near the top you find one with Anne's name at the top. You take it.";
		now the player carries Anne's homework;
	otherwise:
		say "There's nothing more of interest here - just a satisfying lack of Anne's homework."
Instead of cutting Anne's homework:
	if the player carries the scissors:
		say "You happily cut the sheet of paper into a handful of small snippets, which you go on to sprinkle throughout random pigeonholes. If all goes well, Anne will end up in detention and be forced to miss the performance!";
		now Anne is not favoured;ƒ
		increase the score by 1;
		now Anne's homework is off-stage;
	otherwise:
		say "You don't have any scissors, so you just tear the sheet of paper up and scatter the pieces throughout random pigeonholes. If all goes well, Anne will end up in detention and be forced to miss the performance!";
		now Anne is not favoured;
		increase the score by 1;
		now Anne's homework is off-stage.

The computer is scenery in Reception. "It sits on the receptionist's desk. It's nothing fancy - and from this angle, all you can really see is the cable leading from the back of the monitor."

The cable is scenery in Reception. "It plugs into the back of the monitor and then disappears down out of view." The cable can be meddled or not meddled.

Instead of pulling the cable:
	if the cable is not meddled:
		say "You reach forward over the counter and loosen the cable slightly. The receptionist frowns, wiggles the mouse and clicks repeatedly, before sighing with frustration and ducking down under the desk to try to find the cause of the problem.";
		now the receptionist is distracted;
		the receptionist realises in three turns from now;
		now the cable is meddled;
	otherwise:
		say "No need to."
		
At the time when the receptionist realises:
	say "The receptionist discovers the loose cable behind the monitor and reinserts it with an angry mutter.";
	now the receptionist is not distracted;
	now the cable is not meddled	.
	
Section Eight - The Latest Fashion

The jacket is in Leila's locker. The description is "This must be the jacket Selena personalised for Leila.[if notmeddled] It looks rather too nice for your liking.[otherwise] You quite like how it looks from the back now.[end if]". The jacket can be jacketmeddled or returned or notmeddled. The jacket is notmeddled.

Report opening Leila's locker:
	say "To your surprise, it opens without needing a key. Leila must have left it unlocked so that Sel could put the jacket in[if the jacket is in Leila's locker] - you can see it inside[end if].";
	stop the action.

The permanent marker is in the General Classroom. "There's a black permanent marker lying around, looking lonely." The description is "If only you could somehow use this to draw a moustache onto Leila's face without her noticing..." Understand "pen" as the permanent marker.

Instead of cutting the jacket:
	if the player carries the scissors:
		say "I doubt Leila would believe that Sel would cut up her own work. You need another method to frame her.";
	otherwise:
		say "What, with your fingers?"
		
Doodling is an action applying to one thing. Understand "draw on [something]" or "doodle on [something]" or "write on [something]" or "scribble on [something]" as doodling.

Check doodling:
	if the player carries the permanent marker:
		if the noun is not the jacket:
			say "Unless you want to test out your artistic skills, there doesn't seem to be much point in that.";
			stop the action;
		otherwise:
			if the player carries the jacket:
				if the jacket is notmeddled:
					continue the action;
				otherwise:
					say "You've done enough to ensure Leila will be angry with Sel.";
					stop the action;
			otherwise:
				say "You need to be holding the jacket first.";
				stop the action;
	otherwise:
		say "You don't have anything to do that with.";
		stop the action.
		
Carry out doodling:
	now the jacket is jacketmeddled.
	
Report doodling:
	say "You scrawl the words 'KICK ME' onto the back of the jacket in big block capitals."
	
Instead of inserting the jacket into Leila's locker:
	if the jacket is jacketmeddled:
		say "You put the jacket back the way you found it. Hopefully, Leila will think the little message on the back was Sel's handiwork. That will definitely lead to trouble!";
		now the jacket is in Leila's locker;
		now the jacket is returned;
		try closing Leila's locker;
	otherwise:
		continue the action.

After closing Leila's locker:
	if the jacket is returned:
		say "You shut Leila's locker again. Job done.";
		increase the score by 1;
		now Sel is not favoured;
		stop the action;
	otherwise:
		continue the action.
	
Section Nine - Product Placement

The pile of bags is scenery in the Courtyard. "A heap of satchels and rucksacks and many more besides because there's a serious lack of bag racks in this school." Understand "pile" or "bags" as the pile of bags.

The bag is scenery in the Courtyard. Instead of doing anything to the bag, say "None of the bags look interesting enough for that sort of attention."

The packet of gum is in the Random Room. The description is "Cherry flavoured."The packet of gum can be meddled or not meddled. The packet gum is not meddled.

Instead of searching the pile of bags:
	if the packet of gum is not meddled:
		say "You randomly sift through the pile and unwittingly unlodge a packet of gum from an unzipped rucksack. It falls to the ground of the courtyard.";
		now the packet of gum is meddled;
		now the  packet of gum is in the Courtyard;
	otherwise:
		say "[one of]You randomly sift through the pile again, but nothing else reveals itself.[or]You need to find better hobbies.[stopping]"

The gum is edible. Instead of eating the gum, say "You were never a fan of the stuff."
	