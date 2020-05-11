# Begin  
## A. (Condition: Rosie Outfit = Beautiful_Blush_Gown) in_pinkdress  
## B. (Condition: 0 = 0) in_blckdress  
# in_pinkdress  
## A. (Condition: PREMIUM_HAIR_4 >= 1)  
## B. (Condition: NO_PREMIUM_HAIR_4 >= 1)  
### \*Goto merge_compliment5  
# in_blckdress  
## A. (Condition: PREMIUM_HAIR_4 >= 1)  
## B. (Condition: NO_PREMIUM_HAIR_4 >= 1) merge_compliment5  
# merge_compliment5  
# htcac05_mr_silverstein  
## A. (Condition: Rosie Outfit = Beautiful_Blush_Gown) *Goto htcac05_follow_matt  
## B. (Condition: 0 = 0) *Goto htcac05_next_morning  
# htcac05_follow_matt  
## A. (Condition: SPILL_DRINK_4 >= 1)  
## B. (Condition: NO_SPILL_4 >= 1)  
# htcac05_next_morning  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_city_silverstein_cafeteria_day.jpg-story' width='60'>
\*Scene INT_SILVERSTEIN_CAFETERIA_DAY (Color: Black Time: 2)
{% endhint %}  
\*Rosie Outfit Reset  
\*Rosie Hair Reset  
\*Brisa Outfit Brisa_Work  
\*Play Music m_suspense_mystery_intense_just_us_league_01  
Narrator: The following Monday.  
Brisa(smile): So, how did the gala go? I'm still sad I couldn't go.  
Rosie(smile): It was okay.  
Rosie: Mr. Silverstein promised me I'd get more personal experiences with Matt outside of Silverstein Corp.  
Brisa(happy): Your job seems so exciting and mysterious! Any way I can help?  
Rosie(sad): I don't suppose you can magically make him and I grow closer?  
Brisa(smile): Nah, I guess that only happens when you really get to know someone, their likes, and dislikes.  
Rosie(sad): I've tried to look him up because I obviously can't just ask him out, but the information is limited.  
Rosie: I don't understand why. He's kind of a celebrity, right? I mean, to New York City at least.  
Rosie: There should be plenty of things to find on him.  
Brisa(confuse): Actually, I can tell you why that is. Silverstein Corp. has its very own Corporate Image manager.  
Brisa(smile): And she tries her best to keep all the juicy gossip from the tabloids to protect the company.  
Brisa(confuse): I bet she's got a lot of interesting stuff on her computer.  
Rosie(sad): I wish I had access to it.  
Rosie: That way, I could probably get some more insights on who Matthew Dalton really is.  
Brisa: Actually, you don't need to get to her computer to gain access.  
Rosie(surprise): What? How do you know?  
Brisa(smile): Well, as the CEO's secretary, it's my job to make sure everything is in order.  
Brisa: ... And that requires access to all the folders and files in the company's database.  
Narrator: You can't believe what you're hearing. You lean in closer to her and whisper.  
Rosie(surprise): Are you telling me you could look into that folder if you wanted to?  
\>>  
Brisa: Hmm... technically, yes, the only problem is I can't do it on my computer.  
Brisa: I can gain access, but the Corporate Image folder is pretty important, obviously.  
Brisa: So, only the Corporate Image manager, Mr. Silverstein, and Mr. Dalton...  
Brisa: ... Have that folder on their computers.  
Brisa: Now, I don't have access to the 22nd floor where the office of the Corporate Image manager is...  
Brisa(smile): But you probably have a spare key to Mr. Dalton's office, yes?  
Rosie: Yes, but he's in there all the time?  
Rosie: And whenever he's not, it's probably for a meeting, and I usually accompany him to those.  
Brisa(confuse): Which is why we need to do it at night when no one is around.  
Brisa(smile): As Mr. Dalton's assistant, you've got access to the front doors, too, right? Because I don't.  
Rosie: I do, I've got the password.  
Brisa(happy): Perfect!  
Rosie: But Brisa...  
# (htcac_05_04_brisa_help)  
## A. Why are you helping me?  
## B. Do you really want to do this?  
#### A  
Rosie(sad): Why are you helping me? You could lose your job if we get caught.  
\>>>  
Brisa(smile): Besides you being my friend? I kinda want you to succeed in seducing Mr. Dalton.  
\>>  
Rosie(surprise): Why?  
#### B  
Rosie: Are you sure you want to do this? I mean, you could lose your job.  
\>>>  
Brisa: Only if we get caught. I want this.  
\>>  
Rosie(surprise): Why?  
\***  
Brisa(sad): Well, there are multiple reasons but...  
Brisa: Ashley has been nothing but arrogant, condescending...  
Brisa: ... And rude to me every time I've been in contact with her.  
Brisa(smile): And Mr. Dalton is a good man, ruthless and kinda scary, but he's nothing like her.  
Brisa: Ashley doesn't deserve him.  
Rosie(smile): I agree.  
Brisa(happy): Let's do it then. Meet me outside Silverstein Corp. tonight.  
Rosie(happy): Let's do it! Cue spy music!  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_city_company_mansion_streets_night.jpg-story' width='60'>
\*Scene EXT_SILVERSTEIN_CORP_NIGHT
{% endhint %}  
\*+RAIN  
\*Play Music m_suspense_mystery_intense_just_us_league_01  
\*Play Sound s_rain2  
Brisa(happy): I can't believe we're doing this, {Rosie Name}. It's so exciting!  
Rosie(sad): It is, but it's also very important that we don't get caught, Brisa. We could both lose our jobs.  
Rosie(sad): Mr. Silverstein might've hired me, but if we get caught by the security guards...  
Rosie: ... Who's patrolling around inside, then Matt will hear about it.  
Rosie(sad): And I doubt that Mr. Silverstein would be able to save us for poking around in that folder.  
Brisa(smile): Right. I'll focus on the mission.  
Rosie(sad): Good. There are security cameras, too, right?  
Brisa(smile): Yeah, but I doubt they'll be looking through them unless something is reported stolen.  
Brisa(smile): And we're not stealing anything. They'll never know we were there.  
Rosie(smile): Alright.  
Brisa(sad): It's probably better we don't get seen though.  
Brisa: I mean, just so we don't have to try lie and explain why we're here. Quickly in, quickly out.  
Rosie(smile): Good call, let's go.  
Narrator: You swipe your card across the lock, typing in the password, and the two of you enter the lobby.  
# htcac05_sneak_in  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_city_silverstein_looby.jpg-story' width='60'>
\*Scene INT_SILVERSTEIN_LOOBY (Color: Black)
{% endhint %}  
\*Play Music m_melancholy_sadness_gently_a_mystical_experience_01  
Narrator: You tiptoe to the elevators and push the button.  
\*Play Sound s_steps1  
Brisa(smile): So far, so good.  
\>>>  
Rosie(surprise): Do you hear footsteps?  
\>  
Narrator: Brisa nods. She quickly peeks around the wall to see if it's a guard.  
Brisa: It's a guard, but he's walking away from us.  
Brisa(smile): As long as we keep quiet and only whisper, I think we'll be fine.  
Narrator: Then, the elevator arrives, notifying you, and most probably the guard too, with a loud ding.  
Brisa(terror): Oh, no!  
\*Play Sound s_steps1  
Narrator: Sure enough, you hear the footsteps have stopped, but then they resume walking, and this time, they're getting closer.  
Rosie(surprise): Oh, no!  
\*Time 7 (Default: C)  
# (htcac_05_05_TC_footsteps)  
## A. Hide behind the potted plant.  
## B. Get inside the elevator.  
## C. Freeze.  
#### A  
Rosie(surprise): Hurry, behind that plant!  
Brisa(surprise): The plant? Are you su—  
\*Play Sound s_steps1  
Narrator: You push Brisa behind the plant, hearing the footsteps echo through the massive lobby as they get closer.  
Narrator: The guard finally comes into view. He looks around, scratching his head before he shrugs and, to your relief, leaves.  
Message: Good call! | You stayed out of sight.  
Narrator: You sneak back out from behind the plant, your heart in your throat.  
Brisa(smile): I can't believe that worked. Good call, {Rosie Name}.  
\*-CLOSE_ELEVATOR +OPEN_ELEVATOR  
Narrator: You quietly enter the elevator and press the button to the top floor.  
### \*Goto top_floor_a  
#### B  
\*Play Sound s_steps1  
Rosie(surprise): Hurry, get inside the elevator! Quickly!  
\*-CLOSE_ELEVATOR +OPEN_ELEVATOR  
Narrator: You push Brisa inside, pressing the button to the top floor a million times before the door finally closes.  
### \*Goto top_floor_b  
#### C  
\*Play Sound s_steps1  
Rosie(terror): ...!  
Brisa(surprise): {Rosie Name}! Let's go!  
\*-CLOSE_ELEVATOR +OPEN_ELEVATOR  
Narrator: Brisa pushes you into the elevator. She presses the button to the top floor a million times before the door finally closes.  
\*  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_city_desk_office_reception_night.jpg-story' width='60'>
\*Scene INT_SILVERSTEIN_TOP_FLOOR_NIGHT (Color: Black)
{% endhint %}  
\*Camera Left 0  
\*  
Message: Whoops! | You almost got caught!  
Brisa(angry): You can't just freeze up like that, {Rosie Name}.  
Rosie(sad): I don't know what happened. I'm sorry.  
Brisa: Just wake up, okay?  
Rosie(smile): Yes.  Phew, I hope the guard will just brush it off as the elevator acting up...  
### \*Goto merge_elevator  
\***  
# top_floor_a  
\*  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_city_desk_office_reception_night.jpg-story' width='60'>
\*Scene INT_SILVERSTEIN_TOP_FLOOR_NIGHT (Color: Black)
{% endhint %}  
\*Camera Left 0  
\*  
Rosie(smile): I hope the guard will just brush it off as the elevator acting up...  
### \*Goto merge_elevator  
\***  
# top_floor_b  
\*  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_city_desk_office_reception_night.jpg-story' width='60'>
\*Scene INT_SILVERSTEIN_TOP_FLOOR_NIGHT (Color: Black)
{% endhint %}  
\*Camera Left 0  
\*  
Message: Good call! | You stayed out of sight.  
Brisa(surprise): That was close! Good call, {Rosie Name}.  
Rosie(smile): I hope he'll just brush it off as the elevator acting up...  
### \*Goto merge_elevator  
\***  
# merge_elevator  
Brisa(happy): —Or maybe he thinks the place is haunted!  
Rosie(smile): Yes, or that. But if that's not the case, let's hurry and get what we came for.  
Brisa(smile): Right.  
\*Camera Right 1  
Narrator: You walk towards Matt's office, pull out your keycard, and swipe it across.  
# htcac05_matts_office  
\*  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_city_edifice_top_office_night.jpg-story' width='60'>
\*Scene INT_MATTS_OFFICE_NIGHT  (Color: Black)
{% endhint %}  
\*Camera Right 0  
\*  
\*Play Music m_illusion1  
\>>R  
Brisa: Alright, let me see.  
Narrator: Brisa sits down at Matt's computer, locating the corporate image folder.  
Brisa: Dammit. There's a lock on it, but not like a password, more like it's encrypted.  
Rosie(sad): Oh, crap... I guess this is it then.  
Brisa(confuse): Hold on, let me try something.  
Narrator: Brisa types away, her fingers dance across the keyboard as elegantly as a ballerina across her stage.  
Brisa(smile): Alright, I'm in.  
\>R  
Rosie(surprise): What? You're some kind of hacker or something?  
\>>R  
Brisa(happy): Well, no, but my brother, who's actually working in cybersecurity...  
Brisa: ....Taught me a few things when I wanted to hack my ex's Facebook account.  
\>R  
Rosie(confuse): Why would you want to do that?  
Brisa(smile): I suspected there was someone else. Here, go ahead, look through the folder.  
\>>R  
Narrator: You sit down in front of the computer screen, starting to scroll through the many articles and interviews on Matt, Ashley, and Mr. Silverstein.  
Rosie: So, was he cheating on you?  
Brisa(sad): She... and yes, she was.  
Rosie*Think: I should say...  
# (htcac_05_06_cheating_brisa)  
## A. I'm sorry.  
## B. Did you get revenge?  
## C. You're into girls?  
#### A  
Rosie(sad): I'm really sorry to hear that, Brisa.  
Brisa(smile): I wish I had known there was such a thing as fidelity inspectors back when I was dating Shannon.  
Brisa(smile): It would've been a lot easier to find out about her affair like that...  
Brisa: ... Than having to learn the basics of hacking.  
Brisa(confuse): Silverstein Corp. should seriously consider upgrading their cybersecurity actually.  
Rosie(smile): Probably.  
Brisa(smile): Anyway, now you know why I find your job so interesting.  
Brisa(smile): I mean, you're truly saving people a lot of time.  
Rosie(smile): I like to think I am too.  
#### B  
Rosie(angry): Did you get revenge on her?  
Brisa(smile): No, I figured it was punishment enough that she lost me.  
Rosie(smile): I'm sure it was.  
#### C  
Rosie(sad): I'm so sorry to hear that.  
Brisa(smile): Thanks, but it's her loss.  
Rosie(smile): It really is. So, you're into girls?  
Brisa(happy): I am, and always have been.  
Rosie(smile): Cool. We still have a lot to learn about each other, huh?  
Brisa(happy): Yeah. But if we don't lose our jobs tonight, we'll have plenty of time to get to know each other.  
Rosie(smile): True.  
\***  
Narrator: Brisa leans in behind you, reading the articles with you.  
Rosie: There's a lot of articles about his previous hook-ups, and his dating life in general.  
Brisa(smile): Funny how many of these girls resemble you. You could be his type.  
Rosie(smile): His type?  
# (htcac_05_07_be_his_type)  
## A. You think so?  
## B. Doesn't matter.  
#### A  
Rosie(shy): You think so?  
Brisa(smile): Yeah.  
Brisa(surprise): Girl, you're blushing! Are you into him? Like, for real?  
Rosie(surprise): What? No! Of course not.  
#### B  
Rosie: Even if that was true, it doesn't matter. He's going to marry Ashley.  
Brisa(smile): Why do you sound so disappointed?  
Rosie(surprise): I'm not, I'm just stating a fact.  
\***  
\>  
Brisa(confuse): Mhm-hmm.  
Rosie: This is interesting. This entire blog is dedicated to Matt.  
Brisa(smile): Obsessed much?  
Rosie: It hasn't been updated in a while, but she seems to know a lot about him.  
Brisa(smile): Look at that. She mentions he collects rare coins. Isn't that a bit ironic? I mean, he's loaded.  
Rosie(smile): My dad used to collect coins too. I think my mom's got his collection somewhere at home.  
Brisa(happy): I'd say you just found some valuable information. Pun intended.  
Message: Good job! | You and Brisa discovered Matt is a coin collector!  
Rosie(happy): I think we did too. Let's get out of here.  
Narrator: You and Brisa sneak out undetected, making sure you leave everything as you found it.  
\>R  
# htcac05_brisa_into_girl  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_city_company_mansion_streets_night.jpg-story' width='60'>
\*Scene EXT_SILVERSTEIN_CORP_NIGHT
{% endhint %}  
\*+RAIN  
\*Play Music m_gently_modern_blue_moon_01  
\*Play Sound s_rain2  
Rosie(smile): Brisa, I don't know how to thank you for this.  
Brisa(happy): No thank you, just gifts.  
Rosie(smile): No, really, I owe you one, okay?  
Brisa(shy): Actually, maybe you can help me with one thing...  
Rosie(smile): Anything.  
\>>  
Brisa(shy): Could you maybe put in a good word for me with Lou?  
Rosie(surprise): You mean—  
Brisa(shy): Yeah... I might have a small crush on her. She mentioned she's into girls too, so I thought—  
Brisa(shy): I mean, only if you're okay with it?  
Brisa(shy): I know it could be a bit awkward for you, especially if things don't work out.  
Rosie(smile)*Think: Am I okay with it?  
# (htcac_05_08_into_girls)  
## A. Of course, I am!  
## B. Just be careful.  
#### A  
Rosie(happy): Of course, I am! I'd love to see two of my good friends get together.  
Rosie(smile): And I honestly think you would make a cute couple.  
Brisa(happy): I kinda think so too.  
Brisa(shy): So, does this mean you'll do it?  
Rosie(happy): Duh! I'd be honored to play your matchmaker.  
Brisa(smile): Thank you so much, {Rosie Name}.  
#### B  
Rosie(smile): I am, but of course, I wouldn't want any of you to suffer heartbreak, you're both my good friends.  
Rosie(smile): As long as you're careful, then I don't see why not.  
Rosie(smile): Thanks for being considerate of me being in the middle.  
Rosie(happy): But for the record, I don't think it will be awkward. I actually think you'd make a cute couple.  
Brisa(shy): I'd like to think we would too.  
Brisa(shy): Does that mean you'll do it?  
Rosie(happy): I'd love to. It's not hard to put in a good word for you, Brisa.  
Brisa(shy): Aw, thank you so much, {Rosie Name}.  
\***  
Rosie(smile): Anyway, I'll see you tomorrow.  
Brisa(smile): See you tomorrow.  
Narrator: You and Brisa part ways. On the way home, you think about what you're going to say to Lou.  
# htcac05_chat_with_lou  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_city_girls_bedroom_night.jpg-story' width='60'>
\*Scene INT_ROSIES_BEDROOM_NIGHT (Color: Black Time: 2)
{% endhint %}  
\*Play Music m_gently_classical_white_river_02  
\*Rosie Outfit Comfy_Pj's (Tag: Record)  
\*+TWINKLING_FAIRY_LIGHTS  
Rosie(smile)*Think: I'm so ready to get a good night's sleep.  
Narrator: As you jump into your bed, your phone vibrates.  
Rosie(smile)*Think: Lou's texting me.  
\*Show Chat Lou  
Lou: I have a confession, {Rosie Name}.  
Rosie: Oh? Spill.  
Lou: I think I have a crush.  
Rosie: Wow...  
# (htcac_05_09_lou_have_a_crush)  
## A. Let me guess. Brisa?  
## B. Who is it?  
#### A  
Rosie: Let me guess... Brisa? (;  
Lou: You know me too well.  
#### B  
Rosie: Who? Do I know her? ：o  
Lou: You certainly do. It's Brisa.  
Rosie: Cute (;  
\***  
Lou: Do you think she'd be interested in me?  
Lou: I mean, after you left us alone that night, she told me she's gay but idk.  
Lou: I think I felt sparks, but maybe it's in my head.  
Rosie: I should...  
# (htcac_05_10_lous_sparks)  
## A. Tell Lou the truth.  
## B. Be indirect.  
#### A  
\*Gain TELL_LOU_TRUTH_5  
Rosie: Honestly, Brisa told me something tonight. I think it'll make you really happy.  
Lou: No... she didn't?! ：o  
Rosie: Oh, yes.  
Lou: She likes me too? Really?  
Rosie: Very much.  
Lou: Omg. Thanks for telling me, {Rosie Name}.  
#### B  
\*Gain INDIRECT_BRISA_5  
Rosie: Well, Brisa has been saying nice things about you too, Lou, so maybe it's not in your head.  
Lou: She has? ：o  
Rosie: I think it would a good idea to pursue it.  
Lou: Wait... she likes me? What did she say? ：o  
Rosie: All I can say is that I don't think the sparks you felt were in your head.  
Lou: Omg. Excuse me while I faint.  
\***  
Rosie: Haha, I think you would be a great match (:  
Lou: Are you sure you're okay with it? I don't want to complicate your work with my love life.  
Rosie: Don't be silly, Lou. My work shouldn't get in the way of your love life.  
Lou: Thank you, {Rosie Name} ：') Anyway, I gotta go. TTYS.  
Rosie: Alright. Talk soon ：*  
\*Hide Chat Lou  
Rosie(happy)*Think: Nothing like a little love to keep you warm on a cold fall night.  
Narrator: You lay down and quickly drift off to sleep.  
Narrator: But later that night, you're haunted by a reoccurring nightmare of yours.  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_black.jpg-story' width='60'>
\*Scene BLACK
{% endhint %}  
\*Play Music m_horror3  
\*+NIGHTMARE_VERSION_ANIMATION  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_city_girls_bedroom_night.jpg-story' width='60'>
\*Scene INT_ROSIES_BEDROOM_NIGHT
{% endhint %}  
Rosie(sad): No... No...  
Narrator: Do you want to get a glimpse of your past and see what broke your heart, leading you to become a fidelity inspector?  
Rosie(sad): Can I take it?  
# (htcac_05_11_face_nightmare)  
## A. Enter your nightmare. (Cost: 18 Diamond ID: plot_htcac_05_nightmare) *Goto htcac05_nightmare  
## B. I'll pass. *Goto htcac05_rosie_wakeup  
\***  
# htcac05_nightmare  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_city_retro_bedroom_day.jpg-story' width='60'>
\*Scene INT_OLD_BEDROOM_DAY (Color: White Time: 2)
{% endhint %}  
\*Play Music m_blue_epilog_sadness  
\*Gain SEE_NIGHTMARE_5  
Mom(happy): Oh, you look so beautiful, {Rosie Name}.  
\*Rosie Outfit Wedding_Dress  
Rosie(smile): Thanks, Mom.  
Rosie(sad): ...  
Mom(sad): Are you okay, sweetie?  
Rosie(sad): Yeah... I just wish Dad could've been here.  
Mom(smile): Me too. He would've been so proud to walk you down the aisle today.  
Narrator: Difficult memories of your father's accident push a few tears to your eyes.  
Rosie(smile): I'm happy I have you to do it for him, though.  
Rosie(smile): Dad would've loved Ben too, right?  
Mom(happy): Of course, he would've.  
Mom(smile): Ben's personality is far from similar to your dad's.  
Mom: In fact, I don't think they could've been more different.  
Mom(smile): People say that a woman tends to find a man who resembles her dad.  
Mom: And a man tends to look for a woman who resembles his mom.  
Mom(smile): That happened to be true for me, but it isn't true for you.  
Mom: But it's not really that odd since Paul passed away when you were only eight years old.  
Rosie*Think: Talking about Dad makes me think about...  
# (htcac_05_11_DP1_father_memory)  
## A. My favorite memory with him.  
## B. The day he died.  
#### A  
\*Gain BEST_MEMORY_5  
Rosie(smile): ... My favorite memory of him.  
Mom(happy): The one where you'd go pick chestnuts, every year on the 1st of October?  
Mom: And then make chestnut animals with them?  
Rosie(happy): No, but I love that one too.  
Rosie(smile): Remember when we'd go to the cinema in town, every Saturday?  
Mom(smile): Yes?  
Rosie: Remember we'd drive in our old blue pickup truck, the one with only one passenger seat?  
Mom(smile): Oh, yeah.  
Rosie(happy): And do you remember how I was a really chubby kid too?  
Mom(happy): You weren't that chubby.  
Rosie(happy): Mom... I was, and I know you thought so too because you were always driving.  
Rosie(happy): And I know you only did that so I didn't have to sit on your lap, but Dad's, to and from the cinema.  
Mom(shy): I just preferred to drive.  
Rosie(happy): Don't lie to me, I know you hate driving, you always have.  
Mom(happy): Fine, you had a little extra baby fat. But so what?  
Rosie(happy): You're unbelievable.  
Rosie(smile): Anyway, I remember always falling asleep in Dad's arms on the way home.  
Rosie(smile): I felt so safe, so loved.  
Rosie(smile): I would always wake up when he carried me up the stairs.  
Rosie(shy): But I pretended to sleep so that he'd put a dollar under my pillow.  
Mom(smile): Oh, honey.  
Rosie(sad): I wish I had a chance to tell him that. He would've laughed.  
\>>  
Mom(smile): He already knew that, {Rosie Name}.  
\>>>  
Rosie(surprise): He did?  
\>>  
Mom(smile): Of course, he did. He knew you loved him very much too.  
Rosie(cry): Mom...  
Narrator: You hug your mom, letting a few tears stream down your face in memory of your dad.  
#### B  
\*Gain THE_DAY_HE_DIED_5  
Rosie(sad): ... The day he died.  
Mom(sad): I know, honey. It was a terrible year.  
Mom(sad): People talked about his accident for months, which didn't help at all either.  
Narrator: The media called it a freak accident. Your dad's tractor somehow turned over during harvesting, landing on top of him. He died instantly.  
Rosie(sad): It all taught me an important lesson; the importance of saying goodbye, saying I love you.  
Rosie(sad): Nothing hurts more than having to walk around every day and wonder if he knew.  
Mom(sad): Oh, {Rosie Name}. He knew how much you loved him.  
Mom(sad): He'd be heartbroken to hear you've been doubting that.  
Rosie(sad): Are you sure?  
Mom(smile): There's nothing in the world that I'm surer of.  
Rosie(smile): Thanks, Mom.  
Narrator: You and your mother hug each other tightly. You feel lighter after crying a bit for your father.  
\***  
Mom(smile): I should go get ready too.  
Rosie(smile): Okay.  
Narrator: Just as your mom exits your old bedroom, you hear your phone ping.  
Rosie*Think: Might as well check my phone while I wait for Mom to return.  
Narrator: You grab your phone from your nightstand and see you've got a text from an unknown number.  
Rosie(sad)*Think: Hmm...  
Narrator: You read the text and see the photos that were attached to it.  
Rosie(terror)*Think: {*Attention What?!}  
Narrator: As you read the message that forever imprinted itself on your retina, every muscle in your body goes limp.  
Narrator: Your legs collapse from under you. Your stomach churns, threatening to banish your breakfast from your body.  
Rosie(cry)*Think: This can't be real. This isn't happening, not today! Not on our wedding day!  
\>  
Narrator: Panic takes control over you. Your chest rises and falls with rapid breaths as you feel yourself starting to hyperventilate.  
\*Stranger Name Unknown  
\*Show Chat Stranger  
Stranger: I wouldn't marry him. Would you?  
\*Hide Chat  
Narrator: The unknown sender attached screenshots, each one worse than the one before.  
Narrator: The screenshots showed dirty sexting conversations, follow-ups on dates, invitations to dates...  
Narrator: ... And the occasional picture of a male's genitalia that you, unfortunately, recognize as Ben's.  
Rosie(cry)*Think: These messages are over a year old. Ben's been cheating on me for over a freaking year?!  
Rosie(cry)*Think: What am I going to do?  
### \*Goto htcac05_rosie_wakeup  
# htcac05_rosie_wakeup  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_city_girls_bedroom_night.jpg-story' width='60'>
\*Scene INT_ROSIES_BEDROOM_NIGHT (Color: White Time: 2)
{% endhint %}  
\*Rosie Outfit Comfy_Pj's  
\>  
Rosie*Shout(terror): Gasp!  
Rosie(sad): Sigh...  
\*Condition  
## A. (Condition: ADOPT_DOG >= 1)  
## B. (Condition: NO_DOG >= 1)  
#### A  
Narrator: You're awoken by {Puppy Name} licking your face.  
Puppy(sad): Nnn..?  
Rosie(smile): I'm okay. Thanks for getting me out of there.  
Puppy(happy): Waf!  
Narrator: {Puppy Name} snuggles up to you, going back to sleep, but you struggle to fall asleep again.  
Rosie(sad): Dang it...  
#### B  
Rosie(sad)*Think: Guess I won't get much more sleep tonight.  
Narrator: As you predicted, you don't sleep much more that night.  
\***  
# htcac05_work  
\*  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_city_desk_office_reception.jpg-story' width='60'>
\*Scene INT_SILVERSTEIN_TOP_FLOOR_DAY (Color: Black)
{% endhint %}  
\*Camera Right 0  
\*  
\*Play Music m_gently_snug_lullaby_01  
\*Matt Outfit Matt_Suit  
\*Rosie Outfit Reset  
Narrator: You arrive at work. Brisa is already at her desk, typing away on her computer.  
Rosie(sad): Morning...  
Brisa(fear): Gasp!  
Rosie(surprise): What?!  
Brisa(surprise): Girl, have you ever heard of concealer? Your dark circles are literally haunting.  
Rosie(sad): I know...  
Rosie(sad): I haven't slept much tonight.  
Brisa(smile): Oh, the good kind of no sleep or?  
Rosie(sad): No, definitely not the good kind. Nightmare.  
Brisa(sad): Oh, I'm sorry.  
Narrator: Brisa leans in closer and whispers.  
Brisa(sad): Do you think it happened because we broke into—  
\>>>  
Brisa(terror): —Hey, Mr. Dalton!  
\*Camera Left 1  
Matt(angry): ...  
\>  
Narrator: Before Brisa can finish her sentence, Matt approaches you, looking serious, angry even.  
Narrator: You and Brisa share a concerned look. Did he find out somehow?  
Matt(angry): Ms. Winter, we need to talk.  
Rosie(surprise): Oh, okay.  
Brisa(sad): ...  
Narrator: Brisa turns pale, and you gulp as you follow Matt to his office.  
\*  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_city_edifice_top_office.jpg-story' width='60'>
\*Scene INT_MATTS_OFFICE_DAY (Color: Black)
{% endhint %}  
\*Camera Right 0  
\*  
\*Play Music m_gently_rage_romance_lullaby_02  
Narrator: Matt sits down at his desk, looking at his computer screen.  
Rosie(sad)*Think: This isn't looking good.  
Matt(angry): I hate to do this...  
Rosie(surprise)*Think: Oh, no! He's firing me!  
Matt(angry): It's really inconvenient and not what I had imagined would happen already, but...  
Rosie(sad)*Think: This is it.  
Matt(confuse): I have to go to Atlanta immediately, and I have to bring you with me. It's a very important meeting.  
Rosie(surprise): W-What?  
Matt: I know. It's only for a day, and we'll stop by your place so that you can pack the essentials.  
Rosie(surprise)*Think: Phew!  
Rosie(smile): Okay, sure. Whatever you need, Mr. Dalton.  
\*Condition  
## A. (Condition: ADOPT_DOG >= 1)  
#### A  
Rosie: Let me just call Lou and ask her to dog-sit {Puppy Name}.  
Matt(smile): Sure.  
\***  
Narrator: You're relieved, to say the least. You and Brisa's secret remain undiscovered, for now.  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_city_girls_bedroom_day.jpg-story' width='60'>
\*Scene INT_ROSIES_BEDROOM_DAY (Color: Black)
{% endhint %}  
Narrator: You're back home again, packing a bag for today's surprise trip to Atlanta.  
Rosie(smile)*Think: It was a good thing I checked the weather forecast for Atlanta.  
Rosie(smile)*Think: It's apparently snowing there.  
Rosie(confuse)*Think: But we're still going on a business trip, so I need to look professional.  
Rosie(smile)*Think: I should get dressed into something warm yet stylish.  
\*Role  
# (htcac_05_12_pay_coat)  
## A. Outfit Pretty_in_Plaid (Cost: 19 Diamond ID: look_htcac_05_red_coat)  
## B. Outfit White_Turtleneck_Sweater  
\***  
\*Condition  
## A. (Condition: Rosie Outfit = Pretty_in_Plaid)  
## B. (Condition: Rosie Outfit = White_Turtleneck_Sweater)  
#### A  
\*Gain PREMIUM_OUTFIT_5  
Message: Wow | You look great!  
Rosie(happy)*Think: This outfit is perfect! It's got the best of both worlds.  
#### B  
\*Gain NO_PREMIUM_OUTFIT_5  
Rosie(smile)*Think: I think this is appropriate.  
\***  
Narrator: You pack the rest of your necessities before heading out, where Matt is waiting for you.  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_city_inside_car_day.jpg-story' width='60'>
\*Scene INT_MATTS_CAR_DAY
{% endhint %}  
\>>R  
Rosie(smile): Hey.  
\*Condition  
## A. (Condition: Rosie Outfit = Pretty_in_Plaid)  
## B. (Condition: Rosie Outfit = White_Turtleneck_Sweater)  
#### A  
Narrator: As you enter the car, Matt's eyes fall upon your outfit.  
Matt(smile): You look good. Red suits you.  
Rosie(happy): Thank you. I can be a bit of a challenge to dress nicely while staying warm.  
Matt(sad): It's not that cold outside yet though.  
#### B  
Matt(smile): Hey.  
Rosie(smile): Sorry I'm late. I had to find something warm to wear.  
Matt(sad): It's not that cold outside yet though.  
\***  
Rosie(smile): No, but it's apparently snowing in Atlanta right now.  
Matt(surprise): It is?  
Rosie(confuse): I assume you didn't pack anything warm then?  
Matt(sad): It doesn't matter. I'll make do with my suit.  
Rosie(smile): We've got time to go back to your place so that you can get changed.  
Matt(sad): Hmm... alright then. I just don't exactly know what I should wear.  
Matt(shy): I usually get help with that from the sales assistants where I buy my clothes.  
Rosie(happy): Well, I can help you with that if you'd like?  
Matt(smile): Okay, then. Let's do it. Back to my place please, Michael.  
Narrator: Michael nods and makes a u-turn.  
Matt(sad): Snow...  
Rosie(smile): Yeah...  
# (htcac_05_13_snowing)  
## A. I love snow.  
## B. I hate snow.  
#### A  
Rosie(happy): I love snow, but you can't enjoy it if you're not properly dressed.  
Rosie(smile): So, I always make sure to bring the right clothes.  
#### B  
Rosie(smile): I hate being cold. I prefer watching the snow from my window, nice and cozy and warm.  
Rosie(smile): But, if you're properly dressed, nothing beats a good snowball fight.  
\***  
Narrator: Matt shakes his head, smiling to himself.  
Matt: Snow is not my thing. Sure, it's pretty to look at, but it always causes so many issues on the roads.  
Matt(confuse): Always makes people late for work.  
Rosie(smile): You really look at everything in a practical light, don't you?  
Matt(smile): Thought you would've learned that by now.  
Rosie(confuse): I just find it hard to believe. There's more to life than work, you know.  
Matt: Maybe in the future, there will be more to my life than work, but for now, my life is purely work-focused.  
Matt(smile): Which is fine. I love my job.  
Rosie: Hm.  
Narrator: Matt avoids your eyes as if he's afraid his reflect uncertainty or dishonesty.  
Matt: I know this was with very short notice, but we simply couldn't fit in the meeting any other day.  
Rosie(smile): Of course. That's what I signed up for, after all.  
\>R  
Narrator: Shortly after you arrive at Matt's apartment building.  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_3_city_luxury_apartment_day.jpg-story' width='60'>
\*Scene INT_MATTS_APARTMENT_DAY (Color: Black 2)
{% endhint %}  
\*Camera Left 0  
Matt(smile): Alright, wait here. I'll go find something to wear and then you can tell me if it's terrible or not.  
Rosie(happy): Okay, sounds good.  
Narrator: Matt leaves you and you hear him rummage through his closet.  
\*Matt Outfit Matt_Winter_Coat  
Matt(smile): Okay...  
Narrator: Matt returns, looking sharp in a nice wool coat.  
Matt(smile): How is this? Is it alright?  
\*Model  
# (htcac_05_14_matt_pay_coat)  
## A. Nah, I don't know.  
## B. Yes. You should wear that. (Cost: 19 Diamond ID: look_htcac_05_matt_winter_coat)  
#### A  
\*Gain MATT_NO_PREMIUM_OUTFIT5  
Rosie(smile): Hmm. I don't know...  
Matt(sad): Too much? You know what, I'll just go grab some thermal underwear instead, just in case.  
Rosie(smile): Good idea. That will allow you to wear your suit.  
Matt(smile): Right.  
\*Matt Outfit Matt_Suit  
Matt(sad): That's fine.  
#### B  
\*Gain MATT_PREMIUM_OUTFIT5  
Rosie(shy): What are you talking about? You didn't need my help at all. You look great. Very stylish.  
Matt(smile): Thanks. This outfit wasn't that hard to put together, so maybe I didn't need you that much after all.  
Rosie(smile)*Think: I should...  
# (htcac_05_14_DP1_flirt_with_matt)  
### ## A. Flirt with him.  
### ## B. Tease him.  
#### A  
Rosie(shy): Well, I'll be here whenever you need me for anything.  
Narrator: You say, tucking some hair behind your ear sweetly, hoping he'll read into your words.  
\*Matt ROMANCE +1  
Matt(smile): Hm. I'll remember that.  
#### B  
Rosie(happy): Oh, so you only needed an excuse to ask me up to your aparment, Mr. Dalton?  
Narrator: Matt laughs before rasing a playful eyebrow at your suggestive remark and turning his palms up.  
Matt(happy): And it worked.  
\***  
\***  
Rosie(shy): We should probably get going.  
Matt(confuse): Yeah, we've got a plane to catch.  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_city_inside_car_day.jpg-story' width='60'>
\*Scene INT_MATTS_CAR_DAY (Color: Black 3)
{% endhint %}  
Narrator: Once you get to the airport, you're driven straight up to a big, black private jet with Silverstein Corp. written down its side.  
\>>R  
Rosie(surprise): Whoa! Are we flying in that?!  
Matt: We don't fly this thing if we can help it.  
Matt: Only for emergencies when we can't get seats on commercial airlines.  
Rosie: Because of the carbon footprint?  
Matt(smile): Exactly. We have to practice what we preach.  
Rosie(smile): I like that.  
Rosie(happy): But that said, I'm so excited to try this!  
\>R  
Narrator: You step out of the car to admire the jet.  
Narrator: You're greeted by a nicely dressed lady who lets you know that she's prepared coffee and snacks for the flight.  
Narrator: Matt thanks her and dismisses her before he leaves to greet the pilot.  
# htcac05_flight  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_city_private_silverstein_jet_normal_day.jpg-story' width='60'>
\*Scene INT_PRIVATE_SILVERSTEIN_JET_DAY (Color: Black)
{% endhint %}  
\*Play Music m_gently_melancholy_rage_one_step_closer_02  
Rosie(surprise): Oh, my goodness!  
Narrator: The smell of freshly brewed coffee welcomes you as you enter the luxurious business jet.  
Narrator: Its sleek interior design demands respect, and it's big enough to carry ten people.  
Rosie(happy): As if traveling in style wasn't good enough, we've even got chocolate!  
Matt(smile): Take a seat, Ms. Winter. We'll be taking off shortly.  
Narrator: You sit down in the large leather seats, opposite of Matt.  
\*Condition  
## A. (Condition: PREMIUM_OUTFIT_5 >= 1)  
#### A  
Narrator: As you cross your legs, Matt's eyes trail down you from top to bottom.  
\>>R  
Matt(smile): You look really nice today, Ms. Winter, very professional, yet stylish.  
Rosie(smile): Thank you. I'm glad I chose to wear it today, I mean, with the meeting and all.  
Matt: It suits you.  
Rosie(shy): Thank you.  
\***  
Narrator: The pilot speaks to you through the speakers, letting you know you're ready for takeoff.  
Narrator: As the jet rushes down the runway and starts to lift off the ground...  
Rosie(smile): ...  
# (htcac_05_15_lift_off)  
## A. Cling to your seat.  
## B. Look out the window.  
#### A  
Narrator: You dig your fingers into the armrests, hating the feeling of letting go of control.  
Matt: You okay?  
Rosie: I've always wanted to fly in one of these, but only because I hate flying commercial airlines.  
Rosie(sad): Too many people in there to see me freak out. I really don't like flying.  
Matt(smile): Do you do it often?  
#### B  
Narrator: You look out the window, watching the other huge city of New York become smaller and smaller.  
Rosie(smile): This is my favorite part.  
Matt: Why?  
Rosie(happy): I don't know. Maybe because it's a humbling experience to be reminded of how small we really are.  
Matt(smile): Hm. Do you fly often?  
\***  
Rosie: Only when I visit my mom. I haven't had much time to travel with everything... with work.  
Narrator: You swallow, thinking of your mother's cancer diagnoses. Matt studies you; he's about to ask questions.  
Rosie(smile): How often do you fly?  
Matt: Uh, regularly. Maybe once every two weeks?  
Rosie(smile): I see. So, tell me about the meeting.  
Narrator: Matt nods, and you pull your tablet up from your bag.  
Narrator: An hour passes with the two of you preparing for the meeting in Atlanta.  
\*Play Music m_tension8  
Narrator: But then, without warning, the jet starts to shake violently.  
\*Play Sound s_alarm_bell  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_city_private_silverstein_jet_malfunction_day.jpg-story' width='60'>
\*Scene INT_PRIVATE_SILVERSTEIN_JET_MALFUNCTION_DAY
{% endhint %}  
\*+EMERGENCY_LANDING_ANIMATION  
\>R  
Rosie(terror): {*Attention Whoa!}  
Matt(surprise): This doesn't seem right.  
Narrator: You hear the pilot speaking through the radio.  
Pilot: We have to make an emergency landing, sir. Something is wrong with the plane.  
Rosie(terror): Emergency landing?!  
Matt(surprise): Hold on!  
Narrator: The plane descends, and it's far from a smooth landing, but you hit the ground without suffering any harm.  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_city_parking_apron_snow_day.jpg-story' width='60'>
\*Scene EXT_COLD_AIRPORT_EMPTY_DAY (Color: Black)
{% endhint %}  
\*+SNOW  
\*Play Music m_gently_melancholy_rage_one_step_closer_02  
Narrator: You and Matt step out of the jet, slightly nauseous and shaken.  
\>R  
Matt: Are you okay?  
Rosie(sad): I think so... that was terrifying, but at least we didn't crash.  
Matt(sad): Where the heck are we?  
Rosie: I don't know, but it looks pretty desolate to me.  
Narrator: Matt sees the pilot exit the plane and goes over to talk to him.  
Narrator: You look around. You've undoubtedly landed in a very small town. The airport is pretty much empty.  
Rosie(smile)*Think: It's beautiful out here. I'm kind of getting hometown vibes.  
Narrator: Matt returns, looking stressed and exasperated.  
Rosie: What did the pilot say?  
Matt(sad): He said we got lucky. There something seriously wrong with the plane.  
Matt(angry): He also said that we won't get to Atlanta today and that we need to find a place to stay tonight.  
Narrator: Matt sighs, frustration rolling through his body.  
Rosie(sad): I'm sorry. Where even are we?  
Matt(sad): A town called Whitepine.  
Rosie: Hmm...  
# (htcac_05_16_whitepine_town)  
## A. Can't we take a bus?  
## B. How about a Skype meeting?  
## C. Can we postpone the meeting?  
#### A  
\*Gain BUS_5  
Rosie: Can't we take a bus or a train?  
Matt(sad): No. There is literally nothing leaving town today. Even if there were, it would take at least ten hours.  
Rosie(surprise): Ten hours?! What state are we in?  
Matt: Virginia.  
Rosie(sad): Okay...  
Matt: I'll have to try and see if I can get connected via Skype.  
#### B  
\*Gain SKYPE_5  
Rosie: Can't we have a Skype meeting then?  
Matt: We'll have to try, but I'm worried about the signal.  
#### C  
Rosie: Can we postpone the meeting?  
Matt(sad): No. One of the attendees came all the way from Shanghai.  
Matt: I'll have to try and see if I can get connected via Skype.  
\***  
Matt: Let's find a place to stay for the night.  
Narrator: Inside the airport, you're told there is no taxi here, but you manage to pay an elderly gentleman to drop you off at the town's only B&B.  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_city_snowy_inn_day.jpg-story' width='60'>
\*Scene EXT_SNOWY_B&B_DAY (Color: Black)
{% endhint %}  
Rosie: This is it.  
# (htcac_05_17_b&b)  
## A. It's so cute.  
## B. It's rather old-looking.  
## C. I'm cold, I don't care.  
#### A  
Rosie(smile): Aw, it's pretty cute. Don't you think?  
Matt: I suppose it is. Come on. I hope this place has a proper WiFi connection.  
#### B  
Rosie(sad): It looks pretty old, huh?  
Matt: I suppose it does. Come on. I hope this place has a proper WiFi connection.  
#### C  
Rosie(sad): I'm so cold. I hope they have available rooms.  
Matt: Yeah, and a proper Wifi connection. Let's go.  
\***  
Narrator: You enter the old Victorian-style house and meet the innkeeper who's a nice elderly woman.  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_city_inn_rural_bedroom_day.jpg-story' width='60'>
\*Scene INT_B&B_BEDROOM_DAY (Color: Black)
{% endhint %}  
Innkeeper(smile): This is the room.  
Rosie(smile): It's lovely.  
Matt: Yes. You can have that, Ms. Winter.  
Innkeeper(surprise): Oh, are you staying somewhere else, dear?  
Matt: No, I'll be staying here too. I'll just have another room, please.  
Innkeeper(happy): Oh, I'm sorry, but I'm only renting out this room.  
\>>>  
Matt(surprise): Only one room? You mean we need to share this?  
\>  
Rosie(confuse)*Think: This is perfect. This whole emergency landing might be a blessing in disguise.  
Rosie(smile)*Think: I have Matt all to myself, we're in a charming little town, in a romantic room...  
Rosie(smile)*Think: ... With only one bed.  
Rosie(smile)*Think: If I can't make sparks fly tonight, then I might as well throw in the towel. Let's do this!  
# End  
