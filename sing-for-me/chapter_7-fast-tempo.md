# Begin  
# sing07_threatening_message  
\*  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_city_concert_venue_night.jpg-story' width='60'>
\*Scene CONCERT_VENUE
{% endhint %}  
\*Camera Right 0  
\*  
Avery(surprise): AAAH!  
Narrator: You stare in horror at the dead mouse you just pulled from your pocket.  
Narrator: The sound of its body hitting the pavement echoes through your head.  
Sam(surprise): {Avery Name}!  
Narrator: Sam sprints toward you.  
Sam(surprise): I heard you shout. What happened?  
Avery(sad): I'm fine. Someone pushed me, and...  
Narrator: You gesture to the dead mouse.  
Sam(angry): You don't mean...  
Avery(sad): Yeah. They slipped that into my pocket.  
Sam(angry): {Avery Name}, if they hurt you...  
Narrator: Sam looks back and forth down the alleyway, fists clenched.  
Avery: It's no use. They ran off.  
Sam(sad): Are you sure you're okay?  
Avery: I'm just...  
## A. Shaken and angry.  
## B. Glad you're here.  
#### A  
Avery(sad): If they'd had a weapon, I could be dead right now.  
Avery(angry): I should've heard them coming, or at least been able to fight them off.  
Sam: You were caught by surprise. It's not your fault.  
#### B  
Narrator: Sam puts a reassuring hand on your arm.  
\*Sam REL +1  
Sam: You're safe now. I promise.  
\***  
Sam: Come on, let's get out of here. I'll take you and Kylie home.  
Avery: Lucas should come too. We need to talk.  
\*  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_2_city_apartment_interior_night.jpg-story' width='60'>
\*Scene APARTMENT_INTERIOR_NIGHT
{% endhint %}  
\*Camera Left 0  
\*  
Narrator: When you're all gathered in your living room, you take a deep breath.  
Avery(sad): I've been getting texts from an unknown number for the last few weeks.  
Avery(sad): <i>'Stay away from him or you'll be sorry'<i/>... that kind of thing.  
\*Condition  
## A. (Condition: SHOWED_KYLIE_TEXT_5 >= 1)  
## B. (Condition: KEPT_TEXT_SECRET_5 >= 1)  
#### A  
Kylie(sad): I told {Avery Name} not to do anything hasty.  
Kylie(sad): The police can't take action unless it's a direct threat.  
#### B  
Kylie(surprise): <i>What?</i> And you didn't tell me?  
Avery(sad): I didn't want you to worry.  
Kylie(angry): I work for the <i>police.</i> If anyone could help you with this, it's me.  
\***  
Sam: You think things could get violent?  
Avery(sad): The dead mouse was clear enough.  
Avery(angry): They want me to know what will happen to me if I keep ignoring them.  
Kylie: It's obvious what this is about, right?  
Kylie(sad): None of this started until {Avery Name} met Lucas.  
Narrator: You all turn to stare at Lucas. He looks down at his hands.  
Lucas(sad): ...  
Avery(sad): Lucas...?  
Lucas: I've been getting messages too.  
Sam(angry): <i>What?</i>  
Lucas: I didn't think anything of it. I get hate mail all the time...  
Sam(angry): Lucas, how many times have I told you to report death threats to me?  
Lucas(sad): Not now, Sam. I'm too tired.  
Avery: No one outside of this room has any idea that I even know Lucas...  
Avery: Except for Barry and the security staff, of course.  
Kylie: Well, Hoodie Stalker clearly recognized you today. They know who you are.  
Lucas(sad): Maybe Barry was right all along. Maybe you should stay away from me.  
Avery(surprise): Just roll over and do what the blackmailer wants?  
Kylie(sad): I've read about cases like this one. If the stalker's initiated physical contact...  
Sam(angry): Then it's personal now. They won't stop.  
\*Condition  
## A. (Condition: GOT_HOODIE >= 1)  
Narrator: You lift up the stalker's hoodie, showing everyone the logo.  
Avery: At least I got this. The woman could be an employee at this Phil's Seafood place.  
\*Kylie REL +1  
Kylie: That was smart thinking, {Avery Name}. Any information is vital right now.  
\*Sam REL +1  
Sam: Not many people would be brave enough to chase their assailant down like that.  
\*Lucas REL +1  
Lucas: I'm just glad you didn't get hurt. That's all that matters.  
\***  
Sam: If you want my advice, you shouldn't be unarmed.  
Narrator: Sam pulls a foldable knife out of his pocket and hands it to you.  
Sam: It's not much, but it could make all the difference when it comes to self-defense.  
Narrator: You flip the knife open, admiring the sharp blade.  
Avery(happy): I'd definitely feel safer if I had this on me...  
\*Item  
## A. ITEM_KNIFE Take the knife! (Cost: 10 Diamond)  
## B. Give it back.  
#### A  
\*Gain KNIFE_7  
Avery(happy): Thanks, Sam. Can you show me how to use it?  
\*Sam REL +1  
Sam(happy): 'Course. Here, hold it in a grip like this...  
Narrator: Sam quickly runs you through some basic self-defense moves.  
\*Kylie REL +1  
Kylie(happy): Looking badass, {Avery Name}!  
\*Lucas REL +1  
Lucas: I hate this kind of violence. But if it keeps you from getting hurt...  
Narrator: You carefully fold up the knife and slip it into your pocket.  
Avery(happy): I feel safer already.  
#### B  
\*REFUSED_KNIFE +1  
Avery: Thanks, but I wouldn't know the first thing about using this...  
Avery(sad): I'd probably just end up losing a finger.  
Narrator: You hand the pocketknife back to Sam.  
\***  
Sam: I'll keep my security team on full alert tonight, just to be safe.  
Sam: We're not really equipped to guard <i>two</i> people, but—  
Lucas: {Avery Name} can stay at my place tonight.  
Avery(surprise): Your place?  
Sam(surprise): Lucas, do you really want to risk that right now?  
Lucas: You said yourself that this apartment is literally a break-in waiting to happen.  
Lucas(sad): No offense, Kylie.  
Kylie(sad): None taken. You get what you pay for.  
Avery: Ky, will you be okay here alone? The stalker's still out there.  
Kylie: Please, Hoodie Stalker's made it clear who they care about and it's not me.  
Sam: It <i>will</i> be easier to guard you both if you're in the same place...  
Lucas: Then we're all agreed. {Avery Name} stays with me tonight.  
\*Avery Outfit Reset (Condition: PREM_ROCK = 1)  
\*Kylie Outfit Reset (Condition: PREM_ROCK = 1)  
\*  
\*Scene PENTHOUSE_NIGHT  
\*Camera left 0  
\*  
Narrator: Later that night, you step into the penthouse suite of the nicest hotel in the city.  
Avery(surprise): You <i>live</i> here?  
Lucas: For now.  
Narrator: Lucas steps into the room and tosses his jacket onto a sleek leather chair.  
Sam: I'll have someone posted right outside the door.  
Sam: If you hear anything suspicious, or get any messages—  
Lucas: I know the drill, Sam. We're good.  
Narrator: With a nod to you, Sam leaves you and Lucas alone in the suite.  
Lucas(sad): I know it's not homey like your place. Sorry about that.  
Avery: Lucas, this place is...  
## A. Amazing. I'd kill to live here!  
## B. So impersonal. Like a hotel.  
#### A  
Avery(happy): I mean, look at this view! It's incredible.  
Narrator: Lucas gives you a small smile.  
Lucas(happy): I'm glad you like it.  
#### B  
Avery(sad): There's nothing of <i>you</i> in here.  
Lucas(sad): It's just a temporary living situation for me.  
\***  
Lucas: I move around so much, it's not really worth it to settle down anywhere.  
Avery: So you're always on the road?  
Lucas: Pretty much. When I'm not touring, I'm in the studio.  
Avery(sad): That must be hard.  
Lucas: I'm used to it.  
Narrator: Lucas rubs a hand over his eyes, flopping down onto a loveseat.  
Lucas: Anyway, there's plenty of room for two. Make yourself at home.  
Narrator: You slowly wander around the suite, complete with a guest bedroom and a Jacuzzi.  
Avery(happy): I don't think I'd <i>ever</i> get used to this...  
Lucas(happy): To be honest, I'm glad to have the company.  
Lucas(smile): What's the point of all this if you can't share it?  
Avery(happy): I'm glad you invited me.  
Lucas (happy): Take a look around. Don’t leave out any details when you write your article.  
Avery (surprise): Lucas, are you saying…?  
Lucas (happy): I thought it over. I want you to write about me, {Avery Name}.  
Avery: You’re sure? Bethany said it has to be personal…  
Lucas: I’m sure. I wouldn’t trust this to anyone but you.  
Lucas(happy): Besides, my songwriting’s been better than ever since I met you…  
Lucas(happy): If you can be my muse, why can’t I be yours?  
Avery(happy): Lucas, you have no idea what this means to me! Thank you!  
Lucas(happy): From now on… I’m an open book. Be gentle with me.  
Narrator: Lucas smiles at you, his eyes warm and trusting.  
Avery(happy): (I should…)  
## A. Thank him with a kiss.  
## B. Promise him it will be worth it.  
#### A  
\*KISSED_LUCAS +1 (Condition: KISSED_LUCAS = 0)  
Narrator: You hurry over to Lucas and grab his face with both hands, pressing a kiss to his lips!  
\*LUCAS_REL_CHANGE +1  
Lucas (happy): {Avery Name}…  
Avery (happy): You won’t regret this. I promise.  
Narrator: He kisses you back, tender and sweet.  
Lucas (smile): I’m not sure this is professional. Is it part of your research?  
Avery (smile): Nope. This is just for me.  
#### B  
Avery (happy): I’m going to put my heart and soul into this article…  
Avery (happy): The world deserves to see the real you. And you deserve to be seen.  
\*LUCAS_REL_CHANGE +1  
Lucas (happy): You’ve got a lot of faith in me, {Avery Name}…  
Avery (happy): That’s ‘cause I know the real you now. And I want everyone else to know him too.  
Narrator: Lucas nods, his shoulders relaxing like a weight’s been lifted.  
Lucas (happy): I can’t wait to see what you write.  
\***  
Lucas (happy): Now that we’ve got that figured out…  
Avery (happy): Why do you look like you’ve got a surprise in store?  
Lucas (happy): You haven’t seen all the perks of mi casa yet.  
Avery (happy): Oh? Do tell.  
Lucas (happy): I’ve got a hot tub that will blow your mind.  
Lucas(happy): I know you're probably ready to crash, but if you want to unwind a bit...  
Narrator: Lucas jerks his head toward the Jacuzzi, a questioning look in his eyes.  
Avery(happy): (Should I take advantage of this penthouse and stay up late with Lucas?)  
Avery(smile): (This could be my chance to take our relationship to the next level!)  
Avery(happy): Right now, I want...  
## A. You, me, and a hot tub. (Cost: 25 Diamond)  
## B. Some sleep. I'm exhausted.  
#### A  
### \*Goto jacuzzi_with_lucas  
#### B  
Lucas: Of course. It's probably best if we both get some rest.  
Lucas: I'll be in the other room if you need me, okay?  
Avery: Got it. Goodnight, Lucas.  
\***  
### \*Goto sing07_lucas_livestream  
# jacuzzi_with_lucas  
\*JACUZZI_WITH_LUCAS +1  
\*Lucas REL +1  
Lucas(smile): Go ahead, then. I'll join you in a minute.  
\*Camera right 2  
Narrator: While Lucas orders room service, you walk over to the Jacuzzi and fill it with water.  
Avery(happy): This is just what I need...  
Narrator: You quickly strip down and step into the hot tub, sinking down into the warmth.  
### \*Goto female_avery (Condition: AVERY_FEMALE = 1)  
### \*Goto male_avery (Condition: AVERY_MALE = 1)  
# female_avery  
\*Avery Outfit Avery_Shirtless (Tag: Record)  
### \*Goto lucas_romance  
# male_avery  
\*Avery Outfit Avery_Shirtless_Male (Tag: Record)  
### \*Goto lucas_romance  
# lucas_romance  
Avery(happy): Mm...  
Narrator: Steam rises up around you as you tilt your head back against the edge of the Jacuzzi.  
Avery(happy): This feels amazing.  
\*Lucas Outfit Lucas_Shirtless (Tag: Record)  
Lucas(happy): Is there room for one more? *Model  
## A. Definitely!  
## B. We'll have to get cozy...  
#### A  
Avery(happy): Come on in, the water's warm.  
#### B  
Narrator: You let your gaze sweep over the smooth lines of Lucas's chest.  
Avery(smile): But I think we can make it work.  
\***  
\*Lucas REL +1  
Lucas(happy): You sure know how to make it look inviting.  
Narrator: Lucas sets a tray of fruits and chocolates next to the hot tub and steps into the water.  
Lucas(happy): Help yourself to a bite to eat. And there's champagne.  
Avery(happy): I expect nothing less from <i>the</i> Lucas Lucky.  
Avery(smile): By the way, can we talk about the fact that you call your fans 'Luckies'?  
Lucas(happy): They like it. And it makes them feel more familiar...  
Lucas: Less like a nameless, faceless mass.  
Narrator: You both fall silent for a moment, lost in your own thoughts.  
Narrator: When you glance at Lucas again, you notice that his smile is gone.  
Avery: What are you thinking about?  
Lucas(shy): Oh. It's nothing.  
Avery: You know you're a horrible liar, right?  
Narrator: He runs a hand through his hair, letting the water drip down over his face.  
Lucas(sad): I can't help thinking that what happened tonight was my fault.  
Avery(sad): Lucas...  
## A. You did nothing wrong.  
## B. Let's forget it happened.  
#### A  
Avery(sad): Blaming yourself won't fix anything.  
Lucas(sad): I know. But if I'd gone to Sam sooner, or warned you to be more careful...  
Avery: It wouldn't have changed anything. It's not your fault.  
\*Lucas REL +1  
Lucas: ...Thanks, {Avery Name}.  
#### B  
Avery: I don't want to think about it.  
Lucas: You're right. Let's put it out of mind for now.  
\***  
Narrator: Lucas shifts a bit closer to you, water droplets gleaming on his skin.  
Lucas: It's too late to change what happened, but we <i>can</i> control this moment...  
Lucas: Tonight is about you, and whatever you want.  
Avery(happy): In that case, I want...  
## A. A kiss. *Goto lucas_kiss  
## B. A backrub. *Goto lucas_backrub  
\***  
# lucas_kiss  
\*KISSED_LUCAS +1 (Condition: KISSED_LUCAS = 0)  
Narrator: Lucas gently cups your face in his hands, drawing you closer...  
Narrator: When there's just a breath of air between you, he pauses.  
Avery(happy): Lucas...  
\*Lucas REL +1  
Lucas(happy): Give me a minute. I want to look at you.  
Narrator: Your face heats up as Lucas stares deeply into your eyes, his thumb stroking your cheek.  
Avery(shy): What happened to giving me anything I want?  
Lucas(smile): You're right. I'm being selfish.  
Narrator: Finally, his lips meet yours. The kiss is slow and thorough, taking your breath away.  
Lucas(happy): I can be generous too...  
Narrator: Lucas runs his hands over your shoulders and down your arms...  
Narrator: The heat from the water enhances every sensation, his touch warm and soft.  
Avery(happy): Mm, this is better...  
Narrator: You kiss him harder, letting your hands explore the planes of his body.  
Narrator: You trace teasing patterns on his skin, and he lets out a soft moan.  
Lucas: Tell me what you want, {Avery Name}...  
Avery: I want...  
## A. You. All of you.  
## B. To slow down.  
#### A  
Narrator: Lucas pulls back to meet your gaze, his eyes bright and full of emotion.  
Lucas(happy): {Avery Name}, I want to do this right.  
Narrator: His fingers trace over your torso, slow and gentle, dipping lower under the water...  
Lucas(happy): I want to take our time...  
Narrator: You gasp as pleasure sparks through you, arching into his touch.  
Avery(happy): Don't stop...  
Narrator: You reach for him, catching his lips in a passionate kiss as your bodies move together...  
Narrator: Water splashes over the sides of the Jacuzzi, but you're too absorbed in each other to care.  
Avery(happy): <i>Yes...</i>  
Narrator: Your breathing is synchronized, eyes locked together, bathed in desire and warmth...  
\*Scene PENTHOUSE_NIGHT (Color: white)  
\*Camera right 2  
Narrator: Later, you're lying comfortably in each other's arms, resting in the hot tub.  
Narrator: Lucas presses a gentle kiss to your temple.  
#### B  
Lucas: Of course. Being close to you is all I ever need.  
Narrator: Lucas kisses you one more time, gentle and sweet.  
Lucas(happy): But don't think I'm done spoiling you yet.  
Avery(happy):  What did you have in mind?  
Lucas(smile): Stay right there. Don't move.  
Narrator: Lucas hops onto the side of the hot tub and lights some scented candles.  
Avery(smile): Mm, very luxurious.  
Lucas(smile): And for the finishing touch...  
Narrator: He carefully pours two glasses of champagne, handing one to you.  
Avery(smile): Cheers!  
Narrator: You clink your glasses together as Lucas joins you in the water again.  
Lucas(smile): Here's to us. And to finding joy no matter the circumstances.  
Narrator: You take a sip, savoring the flavor, and let yourself relax...  
\*Scene PENTHOUSE_NIGHT (Color: white)  
\*Camera right 2  
Narrator: Later, you're leaning comfortably against Lucas's shoulder, resting in the hot tub.  
Narrator: He presses a soft kiss to your temple.  
\***  
### \*Goto end_lucas_jacuzzi  
# lucas_backrub  
\*Lucas REL +1  
Lucas(happy): Lucky for you, I'm a bit of an expert.  
Narrator: Lucas settles behind you in the hot tub, bringing his hands to your shoulders.  
Avery(happy): When does a celebrity like you get to practice his massage skills?  
Narrator: He starts to knead your muscles with sure, steady movements.  
Narrator: Immediately, you feel your body starting to unwind.  
Lucas: I have a lot of muscle pain...  
Lucas: It's expected, when you're practicing choreography and spending hours on flights.  
Avery(sad): I didn't know. Is it bad?  
Lucas: I can usually ignore it. But when it flares up, I have to go to a professional.  
Lucas(happy): Good news is I've picked up a trick or two.  
Narrator: His hands move lower down your spine, seeking out each sore spot.  
Avery(happy): Lucas, that feels amazing...  
Avery(happy): If I fall asleep like this, I'm holding you responsible.  
Lucas(happy): Go right ahead. I'll make sure you don't drown.  
Avery(smile): <i>That</i> would be a fun scandal for you to cover up.  
Narrator: Lucas laughs, the sound almost as soothing as his hands on your back.  
Narrator: A smile tugging at your lips, you let yourself drift away in relaxation...  
\*Scene PENTHOUSE_NIGHT (Color: white)  
\*Camera right 2  
Narrator: Later, you're leaning against the side of the hot tub, your body loose and comfortable.  
### \*Goto end_lucas_jacuzzi  
# end_lucas_jacuzzi  
Lucas(happy): I know it can't make up for earlier, but I hope this helped take your mind off things.  
Message: You enjoyed a luxurious night with Lucas in his penthouse Jacuzzi!  
Avery(happy): Right now, everything's perfect.  
\*Avery Outfit Reset  
\*Lucas Outfit Reset  
### \*Goto sing07_lucas_livestream  
# sing07_lucas_livestream  
\*  
\*Scene PENTHOUSE_DAY  
\*Camera left 0  
\*  
Narrator: In the morning, you're woken early by the sound of Lucas moving around.  
Avery: Are you setting up a tripod?  
Lucas: I always do a livestream the day after a concert.  
Lucas(sad): I know it's not ideal, but my fans will think something's wrong if I don't show up.  
Avery: It's fine. I wasn't planning to leave this early, but...  
Lucas(surprise): Oh, you don't have to leave!  
Avery(sad): I'm pretty sure Hoodie Stalker will be out for blood if I'm in your livestream.  
Lucas(happy): Think you can stay quiet and out of sight?  
Avery(surprise): Isn't that too risky?  
Lucas: Honestly, I've been dreading this livestream for days...  
Lucas(happy): If you're here, I'll have something else to focus on. A fun distraction.  
Avery: Okay...  
## A. I can't wait to mess with you.  
## B. But I still think it's reckless.  
#### A  
\*ENCOURAGED_LUCAS +1  
Avery(smile): I hope you're good at keeping a straight face.  
\*Lucas REL +1  
Lucas(smile): Don't worry, I'm a professional.  
#### B  
\*CAUTIONED_LUCAS +1  
Avery: We can't afford to slip up. We'll have to be careful.  
Lucas: It'll be fine. I'm a professional.  
\***  
Narrator: You hide out of sight as Lucas waves to the camera with a cheerful smile.  
Lucas(smile): Good morning, Luckies! Did you miss me?  
Narrator: He leans in close to read his fans' comments.  
Lucas(smile): I look cute today? I thought I <i>always</i> look cute!  
Avery(happy): (He seems so natural when he does this...)  
Narrator: Lucas continues to flirt with the camera, showing off his best angles.  
Narrator: Just as you're starting to get bored, he meets your eye and winks.  
Lucas(happy): Am I lonely here by myself? But you're forgetting something important...  
Lucas(smile): I'm never alone when I have your love with me!  
Narrator: It takes all your effort to stifle a laugh as Lucas shamelessly hams it up.  
Narrator: He sees you struggling to stay quiet and his grin gets even wider.  
Avery(happy): (Two can play at that game! I should...)  
## A. Make funny faces.  
## B. Act sexy.  
## C. Glare at him.  
#### A  
Narrator: While Lucas watches you from the corner of his eye, you stick your tongue out!  
Avery(smile): (Come on, I <i>know</i> you want to laugh...)  
Lucas(happy): Did you all like the concert? I think I did well!  
Narrator: He keeps his composure, effortlessly maintaining a one-sided conversation.  
Avery(smile): (Okay, I'll step it up...)  
Narrator: You puff out your cheeks and cross your eyes!  
Lucas(smile): My favorite song to perform is definitely... ah, <i>ahem!</i>  
Narrator: Lucas bursts into laughter, hiding it behind a fake coughing fit.  
Avery(smile): (Gotcha!)  
Lucas(smile): Sorry, everyone! I guess my throat's a little dry.  
#### B  
Narrator: While Lucas watches you from the corner of his eye, you slowly run a hand through your hair.  
Avery(happy): (Come on, look at me...)  
Lucas(happy): Did you all like the concert? I think I did well!  
Narrator: He keeps his composure, effortlessly maintaining a one-sided conversation.  
Avery(happy): (Okay, I'll step it up...)  
Narrator: You trail your hand down your neck, fixing Lucas with a sultry stare.  
Narrator: When you're sure that you have his attention, you bite your lip.  
Lucas(surprise): My favorite song to perform is definitely, uh... What was I saying?  
Narrator: Lucas's face heats up and he stumbles over his words.  
Avery(smile): (Gotcha!)  
Lucas(shy): Sorry, everyone! Your compliments are making me flustered.  
#### C  
Narrator: While Lucas watches you from the corner of his eye, you give him a hard glare.  
Avery: (Come on, Lucas, don't lose focus...)  
Lucas(happy): Did you all like the concert? I think I did well!  
Narrator: He keeps his composure, maintaining a one-sided conversation with his fans...  
Narrator: But you notice the way his eyes keep flitting back to you.  
Lucas(happy): My favorite song to perform is definitely, uh...  
Avery(sad): (Don't give us away!)  
Narrator: You give him a pointed glare, and he gulps.  
Lucas(smile): Well, I'll let you guess! Write your answers in the comments.  
Avery(happy): (Phew! Good recovery!)  
\***  
Narrator: The rest of the livestream goes smoothly...  
Narrator: Until suddenly you feel the urge to sneeze!  
Avery(surprise): (Oh no... I need to hold it in...)  
Avery(surprise): Ah... ah...  
\*Time 10 (Default: C)  
## A. Choo!  
## B. ...  
## C. ACHOO!  
#### A  
Narrator: You can't hold back the sneeze, but you muffle it as best you can!  
Lucas(surprise): Huh? You're asking if I heard a noise just now?  
Narrator: Lucas looks up from the comments to shoot you a panicked glance.  
Avery(sad): (Sorry!)  
Lucas: Nope, didn't hear a thing. Must be an issue with the video quality.  
#### B  
Narrator: You hold back the sneeze, staying silent!  
Avery(surprise): (Whew, that was close!)  
Narrator: Lucas looks up from the comments to shoot you a grateful smile.  
\*Lucas REL +1  
Lucas(happy): ...  
#### C  
Narrator: You let out an explosive sneeze!  
Lucas(surprise): Oh! Uh, sorry about that...  
Narrator: Lucas looks up from the camera to shoot you a panicked glance.  
Avery(sad): (I'm so sorry!)  
Lucas(sad): That was just, uh... my manager stepped into the room for a moment...  
Lucas: Nothing to worry about!  
\***  
Narrator: Lucas wraps it up by blowing kisses to the camera.  
Lucas(smile): Thank you, Luckies! Bye! I love you!  
Narrator: The minute he ends the livestream, you hear a loud knock.  
Avery(surprise): Sounds like someone was waiting for you to finish...  
Narrator: You hurry to the door and throw it open.  
Sam(angry): {Avery Name}. Lucas.  
Narrator: A fuming Sam pushes past you and storms into the room.  
Lucas(sad): Sam, I can explain—  
Sam(angry): Are you two <i>insane?</i>  
Avery(surprise): What did we do?  
Narrator: Sam turns on you, a vein pulsing in his neck.  
Sam(angry): Hiding in the room while Lucas was live? Really?  
Sam(angry): This is <i>exactly</i> the kind of risky behavior you should be avoiding right now!  
Lucas(sad): I thought it would help me get through the livestream...  
### \*Goto your_fault (Condition: ENCOURAGED_LUCAS = 1)  
### \*Goto not_your_fault (Condition: CAUTIONED_LUCAS = 1)  
# your_fault  
Lucas(sad): And {Avery Name} agreed it would be fine.  
Avery(sad): I just wanted to have some fun.  
Sam(angry): I expected better of you, {Avery Name}...  
Sam(angry): If not for your sake, then at least for Lucas's.  
### \*Goto sing07_leave_with_sam  
# not_your_fault  
Lucas(sad): The whole thing was my idea. {Avery Name} tried to talk me out of it.  
Avery(sad): I knew it was reckless, but...  
Sam(angry): Yeah, I know how Lucas gets when his mind is set on something.  
\*Sam REL +1  
Sam: At least you didn't encourage him.  
### \*Goto sing07_leave_with_sam  
# sing07_leave_with_sam  
Lucas(sad): Did you just come here to lecture us?  
Sam: No. I came to take {Avery Name} home.  
Sam(sad): I didn't want you going alone. It might not be safe.  
Avery: Oh. Thanks, Sam.  
Lucas: That's really thoughtful of you—  
Sam(angry): I don't want to hear another word from you, Lucas.  
Sam(angry): We're gonna have a talk later.  
Narrator: You quickly start to gather your things while Sam waits impatiently.  
Lucas(sad): ...Get home safely, {Avery Name}.  
\*  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_2_city_restaurant_exterior_day.jpg-story' width='60'>
\*Scene RESTAURANT_EXTERIOR_DAY
{% endhint %}  
\*Camera left 0  
\*  
Narrator: Sam walks you outside toward a row of black cars.  
Avery(sad): Hey, you were...  
## A. Too harsh in there.  
## B. Right. We messed up.  
#### A  
Avery(angry): It was way out of line.  
Sam(surprise): 'Out of line'? It's my <i>job</i> to keep Lucas safe...  
Sam(angry): What do you expect me to do when you two step right into danger?  
#### B  
Avery(sad): I should've known better than to go along with something like that.  
\*Sam REL +1  
Sam: I don't blame you, {Avery Name}. I blame Lucas.  
\***  
Avery: He said he's familiar with death threats. I figured he knows what he's doing.  
Sam: Lucas has never had a sense of self-preservation...  
Sam(sad): But now he needs to think about <i>you.</i>  
Avery(sad): You're really worried about me, aren't you?  
Sam: I know I get overprotective, but this is a real threat.  
Sam(sad): And I can't be in two places at once, looking out for both of you.  
Avery: You shouldn't feel responsible for me.  
Avery: You're <i>Lucas's</i> bodyguard, not mine.  
Sam: If you're asking me not to care so much about you, it's too late.  
Avery(sad): Sam...  
Sam: I never wanted you to get tangled up in my life. But you did.  
Narrator: You both fall silent, hesitating when you reach the cars.  
Sam: I can have one of Lucas's drivers take you home from here...  
Narrator: His gaze falls on a sleek black limo, and he raises an eyebrow at you.  
Sam: Unless you'd rather borrow Lucas's ride?  
Avery(surprise): Take the limo? Can I really do that?  
Sam: As long as I'm with you, you can.  
Sam: To be honest, I hate to leave your side right now...  
Sam(happy): And the limo is much more <i>private.</i> But it's up to you.  
Avery: (If we take the limo, it could help us work out this unresolved tension...)  
Avery(happy): (And this could be my chance to take our relationship to the next level!)  
Avery: I want to...  
## A. Take the limo! (Cost: 25 Diamond)  
## B. Just go home.  
#### A  
### \*Goto limo_with_sam  
#### B  
Sam: I'll tell the driver to take you straight there.  
Narrator: Sam helps you into one of the simple black cars, closing the door behind you.  
### \*Goto sing07_cliffhanger  
limo_with_sam  
\*LIMO_WITH_SAM +1  
\*Sam REL +1  
Sam(happy): Good choice.  
Narrator: Sam says a few words to the driver and opens the door to the limo for you.  
\*  
\*Scene LIMO_BACKSEAT  
\*  
Narrator: You slide into the backseat, looking around at the luxurious interior.  
Avery(happy): Wow. Fancy.  
Narrator: Sam climbs in behind you.  
Sam(happy): Not bad, right?  
Narrator: He closes the partition to give you some privacy as the driver pulls away from the curb.  
Sam: {Avery Name}, listen...  
Sam(sad): I'm sorry for losing my temper back there.  
Avery: Sam...  
## A. It's okay. I get it.  
## B. You <i>should</i> be sorry.  
#### A  
Avery: You care about me and Lucas. That's why you got so upset.  
\*Sam REL +1  
Sam: I'm glad you understand.  
#### B  
Avery: Lucas and I needed to take a break from all this worrying...  
Avery(sad): And you ruined that for us.  
Sam(sad): That's 'cause I <i>care</i> about you two idiots. For better or worse.  
\***  
Sam(sad): If there's one thing I can't stand, it's feeling helpless.  
Sam(angry): Standing outside that door, knowing it would just look more suspicious if I interrupted...  
Avery(surprise): Was it really that risky? No one could see me.  
Sam(sad): Fans can pick up the smallest sounds, or catch a reflection in a window...  
Sam(sad): I know it's hard, but the last thing we want is to give the stalker more ammo.  
Avery(sad): So, what... you want to put me in a bulletproof room somewhere?  
Avery(sad): Keep me locked away so I'll never get hurt?  
Sam: Tempting.  
Avery: I'm not as breakable as you think, Sam...  
Avery:  You don't need to treat me like I'll shatter from just one touch.  
Narrator: Sam leans back against the leather seat, raising an eyebrow at you.  
Sam: You sure about that?  
Narrator: You roll your eyes and shift closer to him on the seat.  
Avery(happy): Need me to prove it?  
Sam(happy): If you think you can.  
Avery(happy): (I should...)  
## A. Kiss him. *Goto sam_kiss  
## B. Arm wrestle! *Goto sam_arm_wrestle  
\***  
# sam_kiss  
\*KISSED_SAM +1 (Condition: KISSED_SAM = 0)  
Narrator: You swing your leg over Sam's and straddle him on the limo seat.  
Sam (shy): {Avery Name}...?  
Avery(smile): You wanted me to prove it. Now shut up.  
Narrator: He opens his mouth to speak, but you interrupt him with a kiss!  
\*Sam REL +1  
Sam(happy): Mm...  
Narrator: Sam wraps his arms around you as your lips move hungrily against his.  
Narrator: You dig your fingers into his biceps, feeling his muscles clench as you push him back against the seat.  
Avery(happy): Didn't take much for me to pin you down, did it?  
Narrator: Sam breaks off the kiss for a moment, a dangerous glint in his eyes...  
Narrator: And then he tightens his arms around your waist and easily flips you!  
Avery(surprise): Whoa!  
Narrator: Your back hits the plush leather seat. Sam hovers over you with a smirk.  
Sam(smile): Only because I let you.  
Avery(smile): But I didn't break, did I?  
Narrator: You gasp as Sam grips your waist, then glides his hands down your thighs...  
Sam(happy): Hmm, but I'm not done with you yet...  
Narrator: His hands are confident as they trace your body, but his touch is surprisingly gentle.  
Narrator: Despite how easily he manhandled you into the seat, you feel safe in his arms.  
Avery: Sam...  
## A. Keep going.  
## B. Slow down.  
#### A  
### \*Goto sam_hookup  
#### B  
Sam: Whatever you want, {Avery Name}.  
Narrator: Sam kisses you softly and helps you sit back up.  
Narrator: He keeps his arm around your shoulder, and you lean into him.  
Avery(happy): I don't want to rush this...  
Avery(smile): And the driver will probably appreciate our restraint.  
Narrator: Sam chuckles, brushing his lips against your cheek.  
Sam(happy): You're right, of course.  
\*Sam REL +1  
Sam(happy): Besides, just being here with you is more than enough.  
Narrator: You twist your head to look at him, smiling at the soft look in his eyes.  
Avery(happy): You're secretly a romantic, aren't you?  
Avery(smile): I <i>knew</i> this hard exterior was just a front.  
Sam(smile): I hope you know you're sworn to secrecy.  
Narrator: You mime zipping your lips and throwing away the key.  
Avery(smile): I won't say a word.  
### \*Goto end_sam_limo  
sam_hookup  
Narrator: He pulls away from you for a moment, studying your face.  
Sam: Are you sure?  
Avery: <i>Yes.</i> I want you, Sam.  
Narrator: As soon as the words leave your mouth, he crushes his mouth to yours in a passionate kiss.  
Narrator: You tug at his shirt, trying to lift it, and he pulls back just long enough to tear his clothes off.  
\*Sam Outfit Sam_Shirtless (Tag: Record)  
Sam(happy): Better? *Model  
## A. Hell yeah. Now come back here.  
## B. Stay there, I like this view...  
#### A  
Narrator: Impatiently, you tug Sam back down to you and catch his lips in another kiss.  
#### B  
Narrator: Sam subtly flexes his muscles while you sweep your gaze over his chest and abs.  
\***  
Avery(happy): You're way too hot for your own good.  
\*Sam REL +1  
Sam(happy): Speak for yourself...  
Narrator: Sam helps you shed your own clothes, kissing each inch of skin that you uncover.  
### \*Goto avery_female (Condition: AVERY_FEMALE = 1)  
### \*Goto avery_male (Condition: AVERY_MALE = 1)  
# avery_female  
\*Avery Outfit Avery_Shirtless (Tag: Record)  
### \*Goto sam_romance  
# avery_male  
\*Avery Outfit Avery_Shirtless_Male (Tag: Record)  
### \*Goto sam_romance  
# sam_romance  
Avery(happy): Mm, that feels so good...  
Narrator: Your breathing quickens as he gently bites the dip above your hipbone.  
Sam(happy): I want to make you scream, {Avery Name}...  
Narrator: He looks up at you, holding your gaze as his mouth drags over your skin.  
Avery(shy): But the driver will hear us...  
Sam: Don't care. All I care about is you.  
Narrator: You gasp and arch up into his touch, raking your hands over his sculpted body.  
Narrator: The gentle rumbling of the limo's motor vibrates through your body as you lose yourself...  
Avery(happy): <i>Sam...</i>  
Narrator: Sam's lips find yours again as you hold him close, wrapped up in each other...  
\*Scene LIMO_BACKSEAT (Color: white)  
Narrator: When the limo finally comes to a stop, you're lying against Sam's chest in the backseat.  
Narrator: You smile at each other as you pull your clothes back on, smoothing out the wrinkles.  
\*Avery Outfit Reset  
\*Sam Outfit Reset  
### \*Goto end_sam_limo  
# sam_arm_wrestle  
Avery(smile): You and me. Let's go.  
Narrator: You brace your elbow on the armrest, grinning at Sam.  
Sam(smile): Sure you don't want to save your dignity?  
Narrator: Sam cocks an eyebrow at you, giving his biceps a subtle flex.  
Avery(smile): Bring it.  
\*Sam REL +1  
Sam(smile): Okay then. Your funeral.  
Narrator: Sam clasps your hand in his, a confident smile on his face.  
Avery(smile): Three... two... one... go!  
Narrator: Your arm strains as you push against Sam's strong grip!  
Narrator: His face is calm and relaxed, not even breaking a sweat as he keeps up a steady force.  
Avery(angry): Come... on...  
Narrator: You give it all you've got, and his arm starts to lower by one inch... then two...  
Avery(smile): Ha! Not so strong now...  
Sam(smile): Oh, you mean this isn't just the warmup?  
Narrator: Sam suddenly pushes your arm down in one smooth motion!  
Avery(surprise): Hey!  
Sam(smile): Sorry, did you want me to go easy on you?  
Avery(happy): For the record...  
## A. You totally cheated!  
## B. I just wanted to hold hands.  
#### A  
Sam(surprise): What? No I didn't!  
Avery(smile): Yeah? Where's the proof?  
Sam(smile): You saying you want a rematch?  
Avery(surprise): Uh, that's okay! I'll just let you have this one.  
#### B  
Narrator: You look down at your hands, still clasped together.  
Avery(smile): So who's the real winner here?  
Sam (shy): Huh? You're kidding, right?  
Narrator: You squeeze Sam's hand, laughing as his face heats up.  
Avery(smile): Not so confident now, are we?  
\***  
Avery(happy): Anyway, I think I've proven my point...  
Avery(happy): You may be stronger than me, but I didn't break.  
Narrator: Sam blinks at you.  
Sam(surprise): Huh. You're right.  
\*Sam REL +1  
Sam(happy): Maybe I <i>have</i> been underestimating you.  
Avery(smile): It's okay. Just don't do it again.  
### \*Goto end_sam_limo  
# end_sam_limo  
Narrator: You look out the window to see that you've arrived outside your apartment.  
Message: You enjoyed a limo ride with Sam and deepened your relationship!  
Avery(happy): Guess this is my stop. Thanks for the escort home.  
Sam(happy): Trust me, it was my pleasure.  
### \*Goto sing07_cliffhanger  
# sing07_cliffhanger  
\*  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_2_city_apartment_interior_night.jpg-story' width='60'>
\*Scene APARTMENT_INTERIOR_NIGHT
{% endhint %}  
\*Camera right 0  
\*  
Narrator: Later that night, your doorbell rings...  
Avery(surprise): (This can't be good.)  
Narrator: You walk to the door, looking through the peephole... but no one's there.  
Avery(angry): (Screw it. I'm not gonna hide in here.)  
Narrator: You take your pocketknife out and grip it tightly, ready to defend yourself. (Condition: GOT_KNIFE = 1)  
Narrator: Taking a deep breath, you fling the door open and step outside!  
\*  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_2_city_apartment_exterior_night.jpg-story' width='60'>
\*Scene APARTMENT_EXTERIOR_NIGHT
{% endhint %}  
\*Camera left 0  
\*  
Narrator: A blank envelope lies on your doorstep.  
Narrator: Cautiously picking it up, you break the seal and pull out a piece of paper...  
Narrator: Note | <b>This is your last warning. No more games.</b>  
Narrator: Note | <b>Lucas is mine...  and I'll do whatever it takes to get you out of my way.</b>  
# End  
