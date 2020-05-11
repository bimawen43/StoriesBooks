# Begin  
\*Play Music m_sprightly_gently_modern_parkside_01  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_city_cramped_apartment_night.jpg-story' width='60'>
\*Scene CRAMPED_APARTMENT_NIGHT
{% endhint %}  
\*Ashley Player  
# dd01_choose_name  
Narrator: Before we get started, we need to set up your character.  
\*Ashley Naming: What's your first name? | Ashley  
\*Ashley LastName: What's your last name? | Gardner  
Narrator: Your name is {Ashley Name} {Ashley LastName}. Is this correct?  
# (dd_01_01_confirm_name)  
## A. That's me! *Goto dd01_customize_player  
## B. No, I want to change it. *Goto dd01_choose_name  
\***  
# dd01_customize_player  
Narrator*Top: {Ashley Name} | I can't believe I'm late for the party!  
Narrator: You fling open the door to your one-room apartment and rush to the mirror.  
Narrator: You frantically start fixing your hair and makeup...  
\*Ashley Face Face_1  
\*Ashley Hair Blonde_Bob  
\*Ashley Outfit Free_Working_Woman  
Narrator: Choose your face...  
\*Role  
# (dd_01_02_choose_face)  
## A. Face Face_1 (Button: Choose this look.)  
## B. Face Face_2 (Button: Choose this look.)  
## C. Face Face_3 (Button: Choose this look.)  
## D. Face Face_4 (Button: Choose this look.)  
\***  
Narrator: Now choose your hair...  
\*Role  
# (dd_01_03_choose_hair)  
## A. Hair Black_Straight (Button: Choose this look.)  
## B. Hair Blonde_Bob (Button: Choose this look.)  
## C. Hair Beautiful_Braids (Button: Choose this look.)  
## D. Hair Wavy_Half_Updo (Button: Choose this look. Cost: 16 Diamond ID: look_dd_01_hair01)  
\***  
Narrator: Is this you?  
Ashley(smile): I think...  
\*Model  
# (dd_01_04_confirm_look)  
## A. No, I want to change something. *Goto dd01_customize_player  
## B. Yes, I look perfect! *Goto dd01_choose_outfit  
\***  
# dd01_choose_outfit  
Narrator: You throw open your closet and paw through your dresses.  
Ashley(surprise): I hope I have time to change my outfit!  
Ashley(surprise): The party is in a super classy hotel bar...  
Ashley(shy): ...and Ethan said he really hopes I can make it.  
Narrator: Your cheeks grow hot as you think of your long-time crush.  
Ashley(shy): It's been a while since I've seen him... hopefully he's single by now.  
Ashley(smile): I'd better choose something hot.  
Ashley: If I remember correctly, Ethan loves the color red...  
\*Role  
# (dd_01_05_choose_outfit)  
## A. Outfit Prem_Scarlet_Beauty (Button: Choose this look. Cost: 19 Diamond ID: look_dd_01_clothes01)  
## B. Outfit Free_Cute_Sweet (Button: Choose this look.)  
## C. Outfit Free_Working_Woman (Button: Choose this look.)  
\***  
\*Condition  
## A. (Condition: Ashley Outfit = Prem_Scarlet_Beauty)  
## B. (Condition: Ashley Outfit = Free_Working_Woman)  
## C. (Condition: Ashley Outfit = Free_Cute_Sweet)  
#### A  
Ashley(shy): Ethan won't be able to keep his eyes off me in this...  
#### B  
Ashley(surprise): I guess I can just go in what I'm wearing... I don't have much time.  
#### C  
Ashley: This outfit is pretty cute.  
\***  
# dd01_story_begins  
Narrator: You take a second to admire your reflection.  
Ashley(surprise): Now, I really have to go! My Uber will be here at any moment!  
Narrator: Juggling your phone, keys and wallet, you rush back out the door.  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_city_hotel_street_night.jpg-story' width='60'>
\*Scene HOTEL_STREET_NIGHT
{% endhint %}  
Narrator: The car barely has time to stop before you jump out and run into the luxurious hotel.  
Ashley(surprise)*Think: Wow... this place is way fancier than I was expecting...  
Ashley(surprise)*Think: What kind of party is this?  
\*Play Music m_gently_modern_snug_mirage_01  
\*  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_2_city_rooftop_bar_night.jpg-story' width='60'>
\*Scene ROOFTOP_BAR_NIGHT
{% endhint %}  
\*Camera Left 0  
\*  
\*Camera Right 3  
\*Camera Middle 1.5  
\*Ethan Face Ethan_With_Whisker  
\*Ethan Outfit Ethan_Suit  
\*Liam Outfit Liam_Suit  
Narrator: The elevator doors open with a ping and you step out into the rooftop bar...  
Narrator: Men and women in fancy evening wear mingle, laughing and sipping champagne.  
Ashley(surprise)*Think: Wow... everyone is so beautiful. They look like movie stars.  
Ashley(surprise)*Think: Actually... I think some of them <i>are</i> movie stars!  
Ashley(shy)*Think: Ethan has really established himself in Hollywood...  
Ethan(smile): {Ashley Name}!  
Narrator: A handsome man comes jogging over, a bright smile blossoming on his face.  
Ashley(smile): {*Joyful Ethan!}  
Ethan(smile): Hey. It's been forever.  
Narrator: He pulls you into a tight hug.  
Ethan(smile): I've missed you...  
\*Model  
# (dd_01_06_meet_ethan)  
## A. Keep the hug friendly.  
## B. Lean into him.  
#### A  
Narrator: You keep the hug short, giving him a friendly pat on the back.  
#### B  
Narrator: You sink into the embrace, letting the oaky scent of his cologne overwhelm you.  
Narrator: You both linger for a moment before he pulls back.  
\*Ethan REL +1  
Ethan(happy): ...you're still wearing the same perfume after all these years.  
Ashley(shy): ...you noticed?  
Ethan(smile): Of course. You've been using it since freshman year.  
Ashley(shy): Oh... maybe I should think about switching it up.  
Ethan(surprise): Why? It smells amazing.  
Narrator: You feel a happy flush spread across your chest.  
\>>  
Ashley(smile): {*Joyful I'll keep it then.}  
Ethan(smile): Good.  
Ethan(smile): Anyway. I'm glad you made it.  
\***  
Ethan: I was starting to think you wouldn't show.  
Ashley(sad): Sorry. The boss caught me as I was leaving...  
Ethan(sad): Seriously? I hate the way they treat you at that place.  
Ethan: They should be grateful to have someone as dedicated as you working there.  
Narrator: The warmth in his face and fondness in his eyes makes your chest feel tight.  
Ashley(shy): Ethan...  
Ethan(smile): Never mind. I'm just glad you came, fashionably late or not.  
\*Condition:  
## A. (Condition: Ashley Outfit = Prem_Scarlet_Beauty)  
#### A  
\*Ethan REL +1  
Ethan(shy): And speaking of fashionable... wow. That dress...  
Ashley(smile): What, this? Just something I pulled out of my closet.  
Narrator: You do a twirl for him, letting the skirt billow around your legs.  
Ethan(shy): It really... really suits you. The color...  
Narrator: He lets out an awkward cough and looks away, cheeks burning.  
### \*Goto dd01_get_drinks  
\***  
Ashley(surprise): I don't know about 'fashionable'...  
Ashley(shy): I'm feeling severely underdressed. You didn't say this was gonna be celebrity central.  
Ethan(smile): Hey, it's not all Hollywood types. A lot of our college friends are here too.  
Ethan(happy): ...and I don't know what you're talking about. You look amazing.  
\>  
Narrator: You can't help the smile that spreads across your face.  
# dd01_get_drinks  
Ethan: So, would you like a drink? Let me get you something.  
Ashley(smile): Do you really have time to be playing waiter? You're meant to be the host...  
Ethan(smile): If it's for you? I'll always make time.  
Narrator: He puts his arm around your shoulders, and you try not to melt against him.  
Ethan(smile): So... let me get you a drink. Anything you want.  
Ashley(shy)*Think: What if I just want you?  
Ethan(smile): They have a nice champagne I recommend... or...  
Narrator: He pauses, like he's contemplating something. Then he lowers his voice to a conspiratory whisper.  
\>>>  
Ethan: It's been way too long since we've had the chance to hang out by ourselves.  
Ethan(smile): There's a VIP lounge down on the next floor... we could catch up over a drink.  
Ethan(smile): What do you say? Just you and me...  
\>  
Narrator: Guide | Go to the lounge, catch up with Ethan in private and improve your relationship!  
Ashley(smile): That sounds great...  
# (dd_01_07_drink_with_ethan)  
## A. Let's have a drink! (Cost: 15 Diamond ID: plot_dd_01_ethan)  
## B. But you should stay at the party...  
#### A  
### \*Goto dd01_hotel_lounge  
#### B  
Ethan: I guess you're right.  
Ethan(smile): So... champagne?  
### \*Goto dd01_goto_party  
\***  
# dd01_hotel_lounge  
Ethan(smile): Come on, before someone sees me sneak off...  
\*Play Music m_romance_sexy_gently_jazzeton_01  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_city_hotel_lounge_night.jpg-story' width='60'>
\*Scene HOTEL_LOUNGE_NIGHT (Time: 2)
{% endhint %}  
Narrator: Ethan leads you to a stylish, secluded lounge.  
Narrator: Bartenders serve expensive cocktails to patrons in even more expensive outfits.  
Narrator: You approach the bar and look at the menu.  
Ashley(surprise): I could pay for a day's worth of groceries for this price.  
Ethan(smile): Don't worry about it. Get anything you like. My treat.  
Ashley(smile): Wow, Mr. Big Shot. Are you sure?  
Ethan(smile): Knock yourself out.  
Ashley(smile): I hope you don't mean that literally. That'd take a lot of fancy drinks.  
Narrator: You peruse the menu and call over the bartender.  
\*Item  
# (dd_01_07_DP1_choose_drink)  
## A. ITEM_A_Manhattan Choose it.  
## B. ITEM_Emmanuel_Rouget Choose it.  
## C. ITEM_Mocktail Choose it.  
#### A  
Narrator: The bartender garnishes it with a Maraschino cherry and hands you the glass.  
\>>  
Ethan(smile): Still your cocktail of choice, huh?  
Ashley(smile): Are you still gonna fight me on that...  
Ashley(smile): ...Mr. Ethan 'Old Fashioneds are obviously the superior whisky cocktail' King?  
Ethan(smile): No, I've learned the error of my ways. Manhattans have a lot more complexity to them...  
Ethan: Kind of like you.  
Ashley(shy): Oh...  
Narrator: You take a sip of the drink to hide your blush.  
Ashley(shy): Yup, this is definitely, uh... complex.  
#### B  
Ethan(smile): Great choice. You've come a long way since those $3 wine coolers you used to drink in college.  
Ashley(smile): Oh my god, shut up you snob. We can’t all be the children of wealthy lawyers with amazing taste in wine.  
Narrator: Ethan adopts a posh, faux-British accent.  
\>>  
Ethan(smile): It's not my fault I'm all class.  
Narrator: You let out an unladylike snort.  
Ashley(happy): You are seriously so embarrassing.  
#### C  
Narrator: The bartender mixes the mocktail with a flourish and hands you the glass.  
\>>  
Ethan(smile): Not drinking tonight?  
Ashley(smile): No, I am. Just thought I'd get started slow.  
Ethan: Good idea. We all know what happens when you get started fast...  
Ethan(smile): Remember that party in sophomore year when you got so trashed I had to carry you home?  
Ashley(surprise): Uh, no. Apparently I was so trashed I forgot.  
Ethan(smile): Seriously? I had to carry you home bridal-style and you kept telling me you loved me.  
Ashley(shy): Oh. Yeah, I must've been, uh... really drunk.  
\***  
Narrator: You take your drink and follow Ethan to a secluded sofa.  
Ethan(smile): So. How are you? Tell me everything?  
Ashley(surprise): Oh... well, I moved recently.  
Ethan(smile): That's exciting. How's the new place?  
Ashley(surprise): Uhh... it has...  
Ashley*Think: Don't mention the roaches...  
Ashley: ...it has character.  
Narrator: He peers at you for a moment, reading your expression.  
Ethan(smile): You hate it, don't you.  
Ashley(sad): I wouldn't say I <i>hate</i> it...  
Ethan: {Ashley Name}, I know everything about you. I can read you like an open book.  
Ashley(sad)*Think: Not everything... but he's not wrong this time.  
Ashley(sad): My landlord hiked the rent on my old place right before I renewed my contract.  
Ashley(sad): The new place was all I could find in my price range.  
Ethan(surprise): What a jerk. Are you doing okay?  
Ashley: ...I'm hanging in there.  
Narrator: You sip your drink.  
Ashley: So, as you best friend, are you gonna tell me what this party is about?  
Ethan(smile): Best friend privileges only go so far. I already told you, my lips are sealed.  
Ashley(shy)*Think: {*Joyful Great, now I'm thinking about his lips...}  
Narrator: Suddenly, he rests his fingertips on top of your hand.  
\>>>  
Ashley(shy): {*Joyful Uhh...}  
Ethan: We really don't see each other enough these days.  
Ashley(smile): Well, you are pretty busy, Mr. Big Shot Hollywood Director.  
Ethan(smile): Assistant director. But hopefully not for much longer.  
Ashley(happy): Oh my god, is that what this party is about?  
Ashley(happy): Are you finally gonna be at the helm of your own film?  
Ethan(smile): I just told you, you're not getting a word out of me.  
Ashley: Well... if that's the case, you deserve it. You have the talent and you put in the work.  
Ethan: I could say the same about you.  
\>  
Narrator: You try not to focus on the candlelight playing across his face.  
Narrator: It makes you want to get closer than you should, here in this secluded corner of the bar.  
Ashley: I've probably taken up too much of your time. We should get back soon.  
Ethan: You're probably right... but let's do this again soon.  
Ashley(smile): What, get drinks in a VIP cocktail lounge?  
Ethan(smile): No. Spend time together. Just you and me.  
Ashley(shy): Oh... yeah. We definitely should.  
Narrator: You finish up your drinks and leave the lounge.  
\*Play Music m_gently_modern_snug_mirage_01  
\*  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_2_city_rooftop_bar_night.jpg-story' width='60'>
\*Scene ROOFTOP_BAR_NIGHT
{% endhint %}  
\*Camera Middle 0  
\*  
Narrator: You rejoin the small crowd on the rooftop.  
Ashley: Thanks for making time for me, Ethan.  
Ethan(smile): Don't thank me. I wanted to.  
Ashley(smile): Well, I think I'm ready for another drink.  
Ethan(smile): Let me get it for you. Champagne?  
### \*Goto dd01_goto_party  
# dd01_goto_party  
Ashley(smile): I wouldn't settle for less.  
Narrator: Ethan turns toward the bar, when...  
\*Camera Right 2  
Liam(smile): Way ahead of you, buddy.  
Narrator: Another man appears, holding a bubbling crystal flute.  
\*Play Music m_sprightly_gently_modern_parkside_01  
Narrator: Something about his easy-going grin feels familiar...  
Ashley(surprise): Wait... Liam?  
Liam(happy): Hey {Ashley LastName}. Been a few years.  
Narrator: You look him up and down. Gone are the band t-shirts and ripped jeans from his college days.  
Liam(smile): It’s been a few years, huh?  
Liam(smile): Wow...  
\*Model  
# (dd_01_06_meet_liam)  
## A. I can't believe you're wearing a suit!  
## B. You look great!  
#### A  
Ashley(smile): How much did Ethan pay you to come all dressed up?  
Liam(smile): If you're gonna be like that, I'll drink this myself.  
Ashley(surprise): You can't promise me champagne then take it away! Gimme!  
#### B  
Ashley(surprise): I almost didn't recognize you for a second.  
Ashley(shy): You've... changed.  
\*Liam REL +1  
Liam(happy): I hope you mean that in a good way.  
Ashley(shy): A very good way.  
Ashley(surprise): Uh, I mean... you look very, uh...  
Narrator: Liam chuckles and holds out the champagne.  
Liam(happy): Take your foot out of your mouth and put this in it instead.  
\***  
Narrator: He passes you the glass.  
Ashley(smile): Thanks.  
Liam(smile): So. Haven't heard from you in a while...  
Ashley: Yeah... what are you doing now?  
Liam: Mostly securing funding for domestic violence shelters. Negotiating with government branches.  
Liam(smile): Lots of bureaucracy and boring stuff.  
\>>  
Ashley(smile): And to think you said you'd never be anything more than a trouble maker...  
Liam(smile): I'm still pretty good at that too.  
Liam(happy): What about you? How's editing going?  
Ashley(surprise): What?  
Liam: You said you wanted to be a magazine editor...  
Ashley(surprise): Oh, I'm still... working towards that.  
Liam(surprise): Oh?  
Ashley(sad): I'm still an assistant at that company I interned for...  
Liam(sad): The one you said treated you like 'a glorified coffee servant'?  
Ashley(sad): Uh...  
\>  
Narrator: Fortunately, Ethan smoothly interrupts.  
\*Camera Middle 1  
Ethan(smile): Thanks again for coming tonight, guys. Really. It means the world to me.  
Liam: Are you finally gonna announce what the party's about?  
Liam(smile): Wait, don't tell me. You're finally going from 'assistant director' to 'director'?  
Ashley(smile): Has the time finally come for your big Hollywood break?  
Narrator: A secretive smile crosses Ethan's face.  
Ethan(happy): Just wait and see.  
Ethan: Anyway, I need to excuse myself. I'll catch up with you later.  
Narrator: You watch him stride away, unable to hide the longing in your eyes.  
Liam: Still not over him?  
Ashley(surprise): Huh?  
# (dd_01_07_still_not_over_him)  
## A. What's that supposed to mean?  
## B. You're imagining things.  
#### A  
Ashley(surprise): What are you trying to imply?  
Liam: Nothing...  
#### B  
Ashley: I have no idea what you're talking about.  
Liam: Guess I imagined all those times you cried over him in junior year too.  
Ashley(sad): That's... that's all in the past.  
Liam: Great.  
\***  
\>>>  
Liam(sad): Except you still look at him the same way you did in college...  
Ashley(surprise): It's not... I'm not...  
Liam: Did you ever tell him?  
Ashley(angry): No. Obviously not.  
Narrator: A bitter tone creeps into your voice. Liam seems to notice it too.  
\>>  
Liam: Okay. Just wondering.  
Liam: So, smoothly changing the topic...  
Liam: What do you think he's throwing this party for?  
Ashley: I can't say for certain.  
Ashley: I pressed him for info, but he wouldn't budge...  
\*Condition:  
## A. (Condition: Ashley Outfit = Prem_Scarlet_Beauty)  
#### A  
\*Liam REL +1  
Liam(smile): Well, whatever the occasion, it was worth coming to see you in that dress.  
Ashley(happy): Wow, when did you get so smooth?  
Liam(happy): I've always been this smooth. Did you miss the memo?  
\***  
# dd01_ethan_toast  
\*Play Music m_gently_modern_snug_mirage_01  
\>  
Narrator: You're interrupted by the sound of a spoon tapping against glass.  
\*Camera Right 1  
Ethan(smile): Everyone, if I could have your attention...  
Narrator: The buzz of conversation dies as everyone turns to face him.  
Ethan(shy): So... I know you're all wondering <i>what</i> this party is about.  
Narrator: Ethan takes a deep breath, fidgeting with his tie clip.  
\>>  
Ashley(surprise): What's going on?  
Liam: Dunno... I guess we're about to find out.  
\>  
Ethan: I kept going over what to say tonight, but nothing seemed good enough...  
Ethan: So I'm just going to speak from the heart.  
Ethan(smile): Tonight, I want to celebrate a very special woman...  
Ethan(happy): Someone who's been by my side through thick and thin...  
Ethan: Who sees the best in me, but always lets me know when I'm being an idiot.  
Ethan(smile): I can't imagine my life without her in it. So...  
Narrator: His eyes catch yours for a second...  
\*Play Music m_doubt_tension_hovering_thoughts_01  
Narrator: ...but he looks away, to a striking young woman with shocking red hair.  
\>>  
Ethan(smile): {*Joyful Olivia Emmeline Bentley... will you marry me?}  
\>  
Narrator: You watch numbly as the man of your dreams, who you've loved for the last seven years...  
Narrator: ...gets down on one knee and proposes to another woman.  
\*Olivia Name Olivia  
\*Olivia Outfit Olivia_Pink_Dress  
Olivia(surprise): Oh my god... Ethan...  
Olivia(happy): YES!  
\>>  
Liam(surprise): {Ashley LastName}?  
Ashley(sad): ...I think I'm gonna need another drink.  
\>  
\*Camera Left 2  
Narrator: Half a bottle of wine and several glasses of champagne later...  
Liam(surprise): I'm not one to tell others how to live, but... shouldn't you slow down?  
Narrator: He tries to take your glass, but you snatch it back.  
Ashley(happy): I'm fine! Stop being such a square!  
Liam(surprise): A what?  
Ashley(surprise): Hey, is it just me, or is the building swaying?  
Liam(sad): It's just you.  
Narrator: He lifts a hand in front of your face.  
Liam(sad): How many fingers am I holding up?  
Ashley(surprise): Uhhh, like... twelve?  
Liam(surprise): Okay, seriously. Give the alcohol a break.  
Narrator: He reaches for your glass again...  
Ashley*Think: I should...  
# (dd_01_08_reach_for_glass)  
## A. Argue with him.  
## B. Let him take it.  
## C. Drink it.  
#### A  
Ashley(angry)*Shout: I'm fine! Don't baby me!  
Narrator: You try to push him away, and spill your drink all over the floor.  
Liam: Convincing.  
Narrator: He takes the glass from you and signals a waiter.  
#### B  
Ashley(sad): Fine... I guess I am overdoing it.  
Narrator: You give him the glass and he hands it to a passing waiter.  
#### C  
Narrator: You knock back the remainder of your wine before he can take it.  
Liam(surprise): {Ashley LastName}!  
Ashley(happy): Liam!  
Narrator: He grabs the empty glass with a sigh and hands it to a passing waiter.  
\***  
\*Play Music m_gently_lifting_dreams_01  
\>>  
Liam(sad): Come on. You always told me not to bottle stuff up. Talk to me.  
Narrator: You look into his concerned face, waiting for you to unload on him.  
Narrator: You remember all the times he listened to your worries until 3 in the morning.  
Narrator: All the times he let you cry on his shoulder when you couldn't confide in anyone else.  
Narrator: Tears start to prick your eyes but you furiously blink them away.  
Ashley(cry): I came here tonight hoping they'd broken up. That maybe I still had a chance.  
Ashley(cry): I always thought if I waited and wished hard enough...  
\>>>  
Ashley(cry): Maybe he'd realize how I felt.  
Narrator: Liam places a comforting hand on your back, like he used to in college.  
Ashley(cry): But I guess all I can do is live with my regrets now.  
Narrator: You wobble on your feet and slump against his shoulder.  
Ashley(smile): Heh... you smell like leather.  
Liam(shy): Yeah. And you're drunk.  
Narrator: He holds you close for a second, then straightens you up.  
\>>  
Liam: Are you gonna be okay?  
Ashley(sad): I dunno. Eventually. Probably not today or tomorrow.  
Liam: I think I know how to make tomorrow a little better.  
Ashley(sad): How?  
Liam: By getting some water in you.  
Liam: Let's go somewhere quiet so you can sit down, have a breather.  
Liam(smile): Hell, maybe I'll even be able to cheer you up. What do you say?  
Ashley: I...  
# (dd_01_09_sit_with_liam)  
## A. Think that sounds good. (Cost: 15 Diamond ID: plot_dd_01_liam)  
## B. Just want to go home.  
#### A  
### \*Goto dd01_sit_with_liam  
#### B  
\>  
Ashley(sad): I don't think I can handle being here anymore.  
Narrator: Liam seems a little disappointed, but he nods.  
Liam: Yeah, I get that.  
### \*Goto dd01_end_sit_with_liam  
\***  
# dd01_sit_with_liam  
\>  
Ashley: I think I need a moment away from all of... this.  
Liam: Come on... I think I saw an observation platform back there somewhere.  
Narrator: You follow Liam towards the bar where he grabs two glasses of water.  
\*Play Music m_blue_epilog_sadness  
\*  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_2_city_rooftop_dinner_night.jpg-story' width='60'>
\*Scene NIGHT_VIEW
{% endhint %}  
\*Camera Left 0  
\*  
Narrator: The two of you walk away from the other guests, until their voices fade.  
Liam: Here it is. Take a seat.  
Narrator: The secluded spot overlooks the city, and you can see the twinkling lights stretch into the distance.  
Narrator: Liam hands you some water and you sip it slowly.  
\>>  
Liam: How are you feeling?  
Ashley(sad): Drunk and heartbroken?  
Liam(sad): Right. Sorry. Stupid question.  
Ashley: Geez, look at me. This is supposed to be a happy occasion...  
Liam(sad): You've had a thing for King as long as I've known you.  
Liam: If you could fake being happy about this, you'd deserve a spot in one of his movies.  
Ashley(sad): God... married. They're getting married...  
Liam(confuse): I was kinda shocked too. I know they've been together for years, but he always seemed to...  
Liam(confuse): Never mind.  
Narrator: A wisp of a breeze blows across the roof, tossing your hair.  
Ashley(sad): Liam?  
Liam: Yeah?  
Ashley(sad): Am I ever going to be happy?  
Narrator: His lips part slightly, but no sound comes out. You can tell he's taken aback by the question.  
Liam: ...you know I can't answer that. That's all up to you.  
\>>>  
Ashley(sad): You're right. I just I wonder if I'll ever feel the way I do about Ethan for someone else...  
Ashley(sad): Or if anyone will ever feel about me the way Ethan feels about Olivia...  
Liam(sad): Course they will. Hell, maybe someone already does.  
Ashley(sad): I seriously doubt that.  
Liam: Never know. They could be right in front of you.  
\>>  
Narrator: You look at him sharply, eyes wide.  
Liam(surprise): ...like, figuratively speaking.  
Ashley: I...  
# (dd_01_09_DP1_right_in_front_of_you)  
## A. Hope there is.  
## B. Don't want anyone but Ethan.  
#### A  
\*Liam REL +1  
Liam(smile): You could be surprised.  
Liam(happy): These things can happen when you least expect it...  
Liam(shy): ...with the person you least expect.  
Narrator: He suddenly averts his eyes.  
#### B  
Ashley: I don't see myself ever getting over him...  
Ashley(sad): I don't know if I want to.  
\***  
Liam: ...you should probably finish that water.  
\>  
Narrator: You do as he says, finishing the glass.  
Ashley: Can we just stay here for the rest of the party? Do we have to go back?  
Liam: I wish. But someone's gonna miss us eventually.  
Narrator: You sigh, looking out over the view one last time.  
Narrator: Liam strokes your hair, just the tips of his fingers grazing the strands, before he stands up.  
Liam: Come on. We'd better get back.  
Narrator: You reluctantly follow him.  
\*  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_2_city_rooftop_bar_night.jpg-story' width='60'>
\*Scene ROOFTOP_BAR_NIGHT
{% endhint %}  
\*Camera Right 0  
\*  
Narrator: Back amongst the other guests, you suddenly feel light-headed.  
Ashley(sad)*Think: This is too much... everything that happened tonight, all these people...  
Narrator: You start to feel sick.  
Liam: Can I get you anything? Do you need another glass of water?  
Ashley(sad): Actually... I think it'd be better if I just went home.  
Narrator: Liam nods.  
### \*Goto dd01_end_sit_with_liam  
\***  
# dd01_end_sit_with_liam  
Liam: Let me call you a cab. Stay there, I'll be right back.  
Narrator: You wait until he's out of earshot before letting out a deep sigh.  
Ashley(sad): What am I doing with my life...?  
\*Camera Left 3  
Narrator: You walk to the roof's edge, and look out over the city lights.  
\>>  
Ashley(sad)*Think: Just when I thought things couldn't get worse...  
Narrator*Top: Olivia | Excuse me! Can I have everyone's attention please?  
Ashley(angry)*Think: Great... the last person I want to hear from...  
\>  
Narrator: Olivia, Ethan's new fiancé, is standing on a chair in the middle of the bar.  
\*Camera Middle 1.5  
Olivia(happy): Thank you for being here tonight!  
Olivia(smile): I'm so happy everyone was here to share this moment!  
Olivia(happy): It only seems right to have our loved ones beside us on the most important days of our lives.  
Olivia(smile): And that's why...  
Narrator: Suddenly she's looking right at you, a huge smile on her glowing face.  
\*Camera Left 1  
Ashley(surprise)*Think: No...  
\*Time 7 (Default: C)  
# (dd_01_10_TC_olivia_coming)  
## A. Try to hide.  
## B. Make a run for the elevator.  
## C. Stare in horror.  
#### A  
Narrator: You look around for a table to duck under, but there's nothing nearby.  
#### B  
Narrator: You consider making a break for it, but there's too many people.  
#### C  
Narrator: You stare back at Olivia in shock, knowing what's about to come.  
\***  
Olivia(happy): That's why I want to ask {Ashley Name} {Ashley LastName} to be my maid of honor!  
Olivia(happy): She's so important to both me and Ethan.  
Olivia(smile): And there's no one else I'd rather have beside me on my special day!  
Narrator: Several girls who you remember from college erupt into squeals.  
\*Girl1 Name Young Woman  
\*Girl1 Outfit Girl1_Red_Dress  
\*Girl2 Name Young Woman  
\*Girl2 Outfit Girl2_Green_Dress  
Girl1(smile): Now that's BFF goals!  
Girl2(happy): {Ashley Name}, make a speech!  
Girl1(happy): Speech! Speech! Speech!  
\*Play Music m_tension_mystery_melancholy_casual_desire  
Narrator: Everyone stares at you. You look to Liam for support, but he's on the other side of the bar.  
Narrator: Suddenly something in you snaps.  
\>>>  
Ashley(angry)*Think: They want a speech? Fine. I'll give them a speech.  
Narrator: You force a smile.  
Ashley(happy): Olivia. Ethan. Congratulations. I definitely didn't see this coming.  
Ashley(smile): Feels like just yesterday we started college, and now you two are getting m... m...  
Ashley(sad): Married.  
Narrator: You sway on your feet, suddenly feeling that last glass of wine.  
Ashley(sad): The years fly by, huh? When you're young, you think you have all the time in the world...  
Ashley(sad): Then suddenly you're 25, with a crappy apartment and job...  
Ashley(sad): ... and your best friends are getting engaged...  
Narrator: The people around you start to whisper.  
\>  
Girl1(surprise): Is she okay?  
Girl2(surprise): I think she's drunk.  
Ashley(happy)*Shout: Anyway! I'd like to propose a toast!  
Narrator: You hoist yourself up onto the roof's ledge.  
Narrator: There's a collective gasp. Everyone stares in horror as you wobble above a 360 foot drop.  
Ashley(happy): To Olivia, my best friend from college!  
Olivia(surprise): {Ashley Name}... get down...  
Ashley(happy): And Ethan!  
Ashley(happy): The man she's marrying! Even though I've always loved...  
\*Play Music *Stop Music m_tension_suspense_fear_apprehensive_at_best_01  
\*+shade1  
Narrator: And then your foot slips.  
\*-shade1  
Olivia(surprise)*Shout: No!  
Liam(terror)*Shout: {Ashley LastName}!  
Ethan(surprise)*Shout: {Ashley Name}!  
\*+shade1  
Ashley(terror): Oh, no!  
\*Time 7 (Default: A)  
# (dd_01_11_TC_foot_slips)  
## A. Scream!  
## B. Regain your footing!  
## C. Grab something!  
#### A  
\*-shade1  
Narrator: You try to scream, but the air won't leave your lungs.  
#### B  
\*-shade1  
Narrator: Your feet scrabble for purchase on the ledge...  
Narrator: But you've already lost balance.  
#### C  
\*-shade1  
Narrator: You reach out for something to steady yourself... but there's nothing.  
\***  
Narrator: You tip back in slow motion... and then you're falling.  
Narrator: A rush of air hits you like a fist. Your life flashes before your eyes.  
Narrator: Meeting Liam. Olivia. Ethan. All the good times you had together...  
Narrator: And everything that could've gone differently.  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_black.jpg-story' width='60'>
\*Scene BLACK (Color: Black Time: 2.5)
{% endhint %}  
Narrator: You squeeze your eyes shut, wondering if you'll feel the impact...  
Narrator: But it never comes.  
Ashley*Think(sad): Wha...  
Narrator: You open your eyes...  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_city_hotel_street_night.jpg-story' width='60'>
\*Scene HOTEL_STREET_NIGHT (Color: White Time: 2.5)
{% endhint %}  
Narrator: ...to find yourself suspended an inch above the concrete!  
Ashley(surprise): What the?! Am I dreaming?  
\*Sophia Name ???  
Narrator*Top: ??? | No... this is very real.  
\*Play Music m_intense_etherial_ascends_01  
\*+SOPHIA_COME_ANIMATION  
Ashley(surprise): {*Attention Ahhhhh!}  
Sophia: Hello {Ashley Name}. I have good news and bad news for you...  
Ashley(confuse): Bad news? Like tonight could get any worse...  
Sophia: So the bad news is, you're <b>dead</b>.  
Sophia: Almost.  
Ashley(surprise): I'm what?!  
\*Sophia Name Sophia  
Sophia(happy): That's where the good news comes in. I'm Sophia, your guardian angel.  
Sophia(smile): And I'm here to give you a second chance at life.  
\*Play Music m_tension_rage_mystery_forest_fear_01  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_city_etherworld.jpg-story' width='60'>
\*Scene ETHERWORLD_DAY (Color: White Time: 3)
{% endhint %}  
Narrator: Your surroundings suddenly melt away...  
Sophia: Welcome to the <i>Etherworld</i>. A place for souls that aren't quite alive... or dead.  
Ashley(surprise): But... why am I here? Why would you give me a second chance at life?  
Sophia(smile): Well, at school when you fail an exam, sometimes you get a makeup test, right?  
Sophia: This is a bit like that.  
Ashley(sad): So you're saying... I literally failed at life?  
Sophia(sad): I wouldn't say you failed... but you were dreadfully unhappy.  
Ashley(surprise)*Shout: I wasn't that unhappy!  
Ashley(confuse): Tonight was rough, but everything else is great! Like...  
# (dd_01_12_dreadfully_unhappy)  
## A. My job!  
## B. My apartment!  
## C. My love life!  
#### A  
Ashley(angry)*Shout: I'm working for a prestigious magazine, like I always wanted!  
Sophia(sad): You've basically been the coffee girl for the past 3 years.  
#### B  
Ashley(angry)*Shout: I live in a convenient location in the middle of the downtown area!  
Sophia(sad): And you're rooming with a bunch of roaches.  
#### C  
Ashley(angry)*Shout: I had a guy contact me for a second date just last week!  
Sophia(sad): The one who spent 20 minutes arguing that pizza technically counts as a vegetable?  
Ashley(sad): Uh... maybe.  
\***  
Ashley(sad): Okay, I guess you have a point.  
Ashley(surprise): So, now what? Am I born again? Will I remember this happened?  
Sophia: Just be patient. I have the answer to your questions here.  
Narrator: A worn book appears from nowhere, falling into her palm.  
\*Play Sound s_magic_skill_01  
\*Item  
# (dd_01_13_diary_claim)  
## A. ITEM_DIARY Take it.  
\***  
\>>  
Ashley(confuse): It looks familiar...  
Ashley(surprise): Wait... is that my college diary?  
Sophia(happy): Yes! To send you back, we need a tangible point in time... like a diary entry.  
Sophia: One entry, one day to relive however you see fit.  
Ashley(sad): So you're saying... I'm going back to college.  
# (dd_01_14_back_to_college)  
## A. ...okay. I'll do it.  
## B. Guess I'll just die then.  
#### A  
\*CONFIDENCE +1  
Ashley: I mean, it's literally do or die.  
#### B  
Ashley(sad): College was four long years of disappointment.  
Sophia(happy): Exactly! College is where it all went wrong. Now you can fix that!  
\***  
Ashley(surprise): But what happens if I fail?  
Sophia: Then your fate will be the same.  
Sophia(sad): You need to prevent this future from happening again. Or you will die.  
Ashley(surprise): So I need to make sure this engagement party never happens?  
Ashley(sad): Win Ethan’s heart, stop him from proposing to Olivia... or die?  
Ashley(sad): Wow, no pressure...  
Ashley: But I guess it's a chance to finally...  
# (dd_01_15_a_chance)  
## A. Find my own happiness.  
## B. Win the love of my life.  
#### A  
Ashley: I was always too afraid of failure and rejection to go after what I really wanted...  
Ashley(sad): And look where that got me.  
Ashley: But this time... things are gonna be different.  
#### B  
Ashley(sad): I lost my chance with Ethan a long time ago... I would've given anything for another opportunity...  
Ashley(shy): And now I have that.  
Ashley: I'm not going to waste it.  
\***  
\>  
Narrator: You take the diary from Sophia, running your thumb over the cover.  
Ashley(angry): Okay... my whole life is on the line. Let's do this.  
Sophia(smile): I take it we have a deal. Are you ready?  
Narrator: You nod, then open the diary and begin to read.  
\*Play Sound s_open_books  
\*Letter bg_diary_01  
\*SpineOpen Letter Open  
\*Letter Font Bradley_Hand_ITC  
Letter <i>Dear diary...</i>  
Letter <i>Today was my first day at college. I got invited to a party, but I don't know the hosts.</i>  
Letter <i>So I just stayed home and unpacked instead. I dunno. Maybe I should've gone.</i>  
Letter <i>Then again, I've got four more years' worth of college parties. I'll just go next time...</i>  
\*SpineOpen Letter Close  
Ashley(surprise): My first day of college? But I didn't even meet Ethan!  
Ashley(surprise): I can’t win his heart and prevent my death if I don’t even see him!  
Ashley(sad): You said I only get one day per entry... and my first entry is already a waste.  
Sophia: Then change that.  
Ashley: ...you say that like it's gonna be easy...  
Narrator: You look down at the diary.  
Ashley: So, how do I start?  
Sophia(smile): Touch it.  
Ashley(surprise): Excuse me?  
Sophia: Touch the page. You'll see.  
\*Play Sound s_magic_diary_open  
Narrator: You hesitantly extend a finger. A strange force emanates from the paper.  
Narrator: You touch the paper and suddenly the world explodes into a million tiny lights...  
\*Stop Music  
\*Play Music m_illusion3  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_white.jpg-story' width='60'>
\*Scene WHITE (Color: White Time: 2)
{% endhint %}  
Narrator: ...and everything goes white.  
Ashley(sad): Mmm...  
Narrator: You feel groggy, like you're just waking up.  
Ashley*Think: I knew it. It was all just a long, weird dream...  
\*Stop Music  
\*Play Sound s_car_driving  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_city_inside_car_day.jpg-story' width='60'>
\*Scene MATT_CAR_INT (Color: White Time: 2.5)
{% endhint %}  
\*Play Music m_modern_stimulate_creeping_spiders_01  
\*Ashley Outfit Free_Jeans_Tee  
\*Mom Hair Mom_Short_Hair  
\*Mom Outfit Mom_Yellow_Shirt  
Narrator: You open your eyes and let out a huge yawn.  
\>>R  
Ashley: Man, I just had the weirdest...  
Mom(happy): About time you woke up.  
Ashley(surprise): Mom?  
Mom(smile): Who were you expecting, a chauffeur?  
Ashley(surprise)*Think: There's a logical explanation here. I fell asleep in the car and got disoriented, and...  
Ashley(surprise): Wait, why do you look so young?!  
Mom(smile): Must be a little-known benefit of empty nest syndrome. My youthful glow is already coming back.  
Narrator: At the sound of her familiar laugh, a wave of emotion crashes down on you.  
Ashley(surprise)*Think: This... this is real.  
Ashley(sad)*Think: Mom... it's been months since I called her... and even longer since I visited home.  
Ashley(cry)*Think: If I'd died tonight I would've never seen her again.  
Narrator: Tears well in your eyes.  
Ashley(cry)*Think: I have to make the most of this second chance.  
Ashley(cry): Mom... I love you.  
Mom(smile): Honey, are you crying?  
Mom(smile): And to think you spent the first hour of this car ride making me promise...  
Mom(smile): ... I wouldn't cry and embarrass you...  
Ashley(angry): Mom! I'm being serious!  
Mom(happy): I know, honey. I love you too. So much.  
Narrator: She reaches over to give your hand a squeeze, and her touch is comforting.  
Mom(happy): Hey, looks like we've arrived!  
Narrator: You look out the window... and you're greeted by the sight of your old campus!  
Ashley(surprise): I'm really here!  
Mom(happy): You sure are. Time to get your admissions packet and move you into your apartment.  
Narrator: The place is totally packed with freshmen and their families.  
Mom(surprise): Uhh... do you see any parking spots?  
Ashley: Why don't you head over to the apartments? I'll go to the admissions office myself.  
Mom(surprise): Is this the same girl who was fretting about getting lost just this morning?  
Mom(smile): You must have memorized those campus maps.  
Ashley(smile): Yeah... it's like I've been here for years already, right?  
\>R  
\*Play Music m_cheerful_city  
\*  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_city_college_campus_day.jpg-story' width='60'>
\*Scene COLLEGE_CAMPUS_DAY
{% endhint %}  
\*Camera Left 0  
\*  
\*Camera Right 4  
Narrator: She drops you off near the main building and you hurry toward it, mind wandering.  
Ashley(surprise)*Think: Sophia said I only get one day per entry... so my time is seriously limited.  
Ashley*Think: I need to figure out how to meet Ethan if I want this entry to count.  
Ashley(sad)*Think: If I stay home in my dorm again, I risk reliving the past exactly as it happened...  
Ashley(sad)*Think: ...and that route leads to falling off a hotel roof.  
Narrator: Lost in thought, you don't notice there's someone in your path until you're on top of them.  
\*Play Music m_modern_stimulate_creeping_spiders_0  
Narrator*Top: Man's Voice | Hey, careful!  
Ashley(surprise)*Shout: Ahhh!  
\*Liam Outfit Liam_Casual  
Liam(surprise): ...  
Ashley(surprise): ...Liam!  
Narrator: He's younger than the man you were with an hour ago, but there's no mistaking him.  
\>>  
Liam(surprise): Do I... know you?  
Ashley(surprise): Do you <i>know</i> me? We're...  
Ashley(sad)*Think: Oh... we haven't actually met yet.  
Ashley(surprise)*Think: Ugh, I'm already messing up!  
Liam: ...are you okay?  
Ashley(surprise): Me? Yeah, I'm great! Sorry for running into you.  
Liam: Okay... So, are you gonna tell me how you know my name?  
Ashley(surprise): Oh, that's because...  
# (dd_01_16_know_his_name)  
## A. I heard your mom calling you before.  
## B. We were destined to meet.  
#### A  
Ashley(smile): I walked past you earlier and heard your mom say your name.  
Liam(confuse): I came here with my cousin.  
Ashley(surprise): Oh. Guess I mistook your cousin for your mom.  
Liam(confuse): My cousin is a man with handlebar moustache...  
#### B  
Liam: Destiny, huh? Seems kind of unfair that I didn't get your name in return.  
Liam(smile): Wanna give me a hint?  
Ashley(surprise): Oh, uh... I'm sure you'll work it out!  
\***  
Ashley(surprise): Anyway... I just remembered I need to be somewhere. Which isn't here.  
Ashley(surprise): Bye!  
\>  
Narrator: You streak off across the lawn before Liam has a chance to reply.  
\*Camera Right 2  
Ashley(sad)*Think: God, that was embarrassing...  
Ashley*Think: I have to remember that no one here knows who I am...  
Ashley(surprise)*Think: And I'm definitely not supposed to know them!  
\*Play Music m_romance_dinner_night  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_city_college_apartment_exterior_day.jpg-story' width='60'>
\*Scene COLLEGE_APARTMENT_EXTERIOR_DAY
{% endhint %}  
Narrator: You find your way to your apartment and head inside.  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_city_college_apartment_interior_day.jpg-story' width='60'>
\*Scene COLLEGE_APARTMENT_INTERIOR_DAY
{% endhint %}  
Ashley(smile): Home sweet home, huh?  
Narrator: Your mother's smile suddenly fades.  
Mom(sad): I'm gonna miss you, honey.  
Narrator: She pulls you in for a hug, and suddenly you find yourself fighting back tears.  
Narrator: You wish you could tell her everything... but you know you can't.  
Ashley(sad): Wish me luck.  
Mom: Good luck, doll. You're gonna do fine.  
Ashley: Bye mom. And... thanks for everything.  
Narrator: She gives you one last kiss on the cheek, and then just like that, she's gone.  
\>>  
Ashley*Think: Okay, if I want to get on with this changing the future thing...  
Ashley*Think: I seriously need to work out how to meet Ethan.  
Ashley*Think: Knowing him, he probably went to some event tonight... but where?  
Ashley*Think: Maybe Olivia will have some ideas when she-  
Ashley(surprise): ...wait a minute. Olivia...  
\>  
\*Play Music m_romance_sexy_gently_jazzeton_01  
Narrator: Your eyes go to the door... just as it clicks and swings open, revealing...  
Ashley(surprise)*Think: Oh no... with everything that happened I forgot that she was my...  
\*Olivia Outfit Olivia_Casual  
Olivia(surprise): Roomie! Oh my god!  
Ashley(angry)*Think: This bitch, I swear I'm gonna...  
\>>  
Olivia(happy): I'm so happy to meet you!  
Ashley(surprise): ...huh?  
Narrator: She runs over for a hug, but then suddenly reels back at the last second.  
Olivia(surprise): Oh my god, I'm sorry! Are you a hug person?  
Ashley(surprise): Oh, uh...  
# (dd_01_17_hug_olivia)  
## A. Sure?  
## B. Please, no.  
#### A  
Olivia(happy): Good, because I'm definitely a hugger.  
Narrator: She leans in again and gives you a quick squeeze. You're too shocked to protest.  
#### B  
Olivia(smile): Sorry. I'll control my hugging urges.  
Narrator: She offers you her hand instead. You give it a weak shake.  
\***  
\>  
Olivia(happy): I'm Olivia.  
Ashley: {Ashley Name}.  
Olivia(happy): It's great to meet you!  
Ashley(angry)*Think: It's your fault I'm stuck reliving my crappy college days...  
Olivia(happy): I'm so excited to have a roommate! And no parents! And my own space!  
Ashley(angry)*Think: It's your fault I lost Ethan...  
Olivia(sad): My mom and dad are like, the definition of 'helicopter parents'.  
Ashley(angry)*Think: It's your fault I <i>died</i>...  
Olivia: So, what about you? Were your parents strict about staying out late and stuff?  
Ashley(surprise): M...me?  
Olivia(smile): Yeah! Tell me more about you!  
Narrator: You feel your roaring anger reduce to a slow boil.  
Ashley(sad): Uh... No. I was... a bit of a homebody. I didn't have that many friends.  
Olivia(smile): Well, now you have me. And it's a fresh start for both of us!  
Olivia(happy): We're gonna make so many memories, just you wait...  
Olivia(surprise): Oh! Speaking of memories...  
Narrator: She runs back to her suitcase and starts digging through it.  
Olivia: I know it's in here... aha!  
Narrator: She triumphantly holds out a beautiful wooden box.  
\*Item  
# (dd_01_18_memory_box_claim)  
## A. ITEM_Memory_Box Take it.  
\***  
\*Memory_Box +1  
Olivia(smile): I brought this box to <b>store important mementos</b> from my college life...  
Olivia(smile): ...but I kinda feel like you should have it.  
Ashley(surprise): ...me?  
# (dd_01_19_a_gift)  
## A. I couldn't.  
## B. Why me?  
#### A  
Olivia(smile): Please. I insist.  
Olivia: I dunno why...  
#### B  
Olivia: I don't know...  
\***  
Olivia(smile): But something tells me you'll put it to better use than I would.  
Olivia(smile): I even have something you can put in it right now!  
Narrator: She twists a ring off her finger and plops it into the box.  
Olivia(happy): My infinity mood ring. It's nothing much... but I like to think it could symbolize everlasting friendship.  
\*Play Sound s_magic_skill_01  
\*Item  
# (dd_01_20_ring_claim)  
## A. ITEM_Infinity_Ring Take it.  
\***  
Narrator: She holds the box out to you insistently.  
Narrator: The anger and resentment you'd felt for her dulls to a simmer.  
Ashley(confuse): Oh... thank you.  
Narrator: Guide | Make the most of your college days and collect special items for your memory box!  
Narrator: Guide | Collect all <color=magenta>12</color> to unlock a <color=magenta>bonus</color> scene at the end of the story!  
Message: Infinity Ring | Collected memento 1/12.  
\*Infinity_Ring +1  
\*Play Music m_modern_romance_hovering_thoughts_01  
\>>  
Olivia(smile): I dunno about you, but I think we should start our college experience off right.  
Olivia(smile): These upperclassmen are throwing a huge party at their place...  
Olivia(happy): And we should totally go!  
Olivia(happy): They said anyone who's anyone will be there!  
Ashley(surprise)*Think: That sounds like the kind of party Ethan would go to...  
Ashley(surprise)*Think: This could be my chance to find him!  
Ashley(sad)*Think: But a party at a random person's house? Full of complete strangers?  
Ashley(sad)*Think: What if I'm intruding? What if they ask me to leave...?  
Ashley(surprise)*Think: What if Ethan isn't there and I went for nothing?  
Ashley(surprise): Uh... I don't know if I can...  
Olivia(surprise): Why not?  
Ashley(surprise): Because...  
# (dd_01_21_hesitate)  
## A. My moon is in Leo.  
## B. I'm allergic to parties.  
## C. I have to feed my goldfish.  
#### A  
Olivia(surprise): What does that even mean?  
Ashley(surprise): Uhh... it means...  
Ashley(sad): Actually, I have no idea.  
#### B  
Olivia(surprise): Like... you're allergic to alcohol?  
Ashley(surprise): No, just to parties. They make me break out in hives...  
Olivia: I'm not sure that's a thing...  
#### C  
Olivia(confuse): You have a goldfish?  
Ashley(confuse): Yes, and he's on a very strict feeding schedule.  
Olivia(confuse): ...and what's his name?  
Ashley(confuse): Uhh... Fishy McFish Face?  
Olivia(confuse): ...  
Ashley(sad): Okay, there's no goldfish.  
\***  
\>  
Narrator: You sigh.  
Ashley(sad): The truth is... I'm not really a party person.  
Olivia(sad): {Ashley Name}... do you really not want to go to the party?  
Olivia: Or do you want to go, but you're worried it's gonna be awkward and weird?  
Ashley(surprise): I...  
Ashley(sad): I guess I'm just worried.  
Narrator: She takes your hand and grips it tight.  
Olivia: I swear upon the sacred girl code that I will not leave your side the entire night.  
Olivia(smile): Unless you're using the bathroom... or hooking up with a hot guy.  
Ashley(surprise): Olivia!  
Olivia(happy): Come on, we'll have fun. And if not, say the word and we'll leave.  
Ashley(surprise): I...  
Narrator: You try to hold on to your anger, the resentment that built up for Olivia over the years...  
Narrator: ...but her words dampen it further, until it's little more than a glowing ember in your chest.  
Ashley*Think: Maybe it won't be so bad. And if there's a chance I can change the future...  
Ashley(angry)*Think: I have to do it.  
Ashley: ...okay. I'll go.  
Olivia(happy): Yay!  Okay, the party starts at 8 pm...  
Olivia(surprise): Which means we only have five hours to get ready!  
Olivia(surprise): We need to choose outfits! And shower! And do our hair! And make up!  
Ashley(surprise): But isn’t that plenty of time to...  
Olivia(surprise): Now!  
Narrator: You dutifully walk over to your suitcase...  
Ashley(sad): Wow... I definitely didn't pack with partying in mind.  
Olivia(smile): You can borrow something of mine! We look about the same size.  
Narrator: She presents you with a sexy top and skirt combo.  
Narrator: You can't help imagining how you'd look in it...  
\*Ashley Outfit Prem_Party_Girl (Tag: Record)  
Ashley(surprise): Oh...  
\*Model  
# (dd_01_22_pay_dress)  
## A. I couldn't...  
## B. Wow, I love it! (Cost: 19 Diamond ID: look_dd_01_clothes02)  
#### A  
\*Ashley Outfit Reset  
Olivia: Okay, if you're sure.  
Ashley: I'll just go as I am. I can't just take your clothes.  
Olivia(surprise): Now let's get back to getting ready! Time's wasting!  
Narrator: You walk towards the shower in a stupor.  
#### B  
\*Gain PREMIUM_OUTFIT_1  
\*CONFIDENCE +1  
Ashley(smile): Thank you!  
Olivia(happy): Don't thank me. Just go try it on! You'll look great in it!  
Narrator: She shoves the clothes into your hands. You walk towards your bedroom in a stupor.  
\***  
\*  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_city_college_campus_night.jpg-story' width='60'>
\*Scene COLLEGE_CAMPUS_NIGHT (Time: 2)
{% endhint %}  
\*Camera Right 0  
\*  
\*Olivia Outfit Olivia_Green_Dress  
Narrator: You have a feeling it's going to be a hell of a night.  
# points_count  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_black.jpg-story' width='60'>
\*Scene BLACK (Time: 2.5)
{% endhint %}  
Narrator: <color=purple>Dear Diary</color> | Chapter One Completed.  
Message: Congratulations | You have got {Memory_Box Number}/12 collected mementos!  
\*Memory_Box Show  
# End  
