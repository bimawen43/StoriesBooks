# Begin  
\*  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_city_town_street_day.jpg-story' width='60'>
\*Scene TOWN_STREET_DAY
{% endhint %}  
\*Camera Left 0  
\*  
Narrator: As you and Sam are walking back from your clinic visit, you see two familiar faces walking down the street.  
\*Play Music m_intense_upsetting_descent  
\>>>  
Zale: ...  
\>  
Layla(surprise)*Think: Oh no...  
\>>>  
Caden: ...  
\>  
Layla(sad)*Think: Those two will attack each other on sight...  
\>>>  
Sam(smile): ...  
\>>  
Layla(surprise)*Think: And Sam will get caught up in the middle of it.  
Layla(sad)*Think: Someone's going to get hurt and my life will get a lot more complicated.  
Layla(angry)*Think: I need to do something.  
\>  
\*Stop Music  
\*Play Music m_melancholy_gently_present_standard_01  
Sam: Hey, are you alright?  
Layla(surprise): Um... Well...  
Layla(surprise)*Think: What do I do?!  
# (sld_07_01_what_do_i_do)  
## A. Lie to him. *Goto merm07_sam_lie  
## B. Tell him the truth.  
#### B  
\*Gain MERM07_TOLD_SAM_TRUTH  
Layla: I saw someone I know. Two someones, actually.  
Sam(surprise): Oh? I didn't know you knew anyone who lived here.  
Layla(surprise): I don't! They're not really from around here...  
Narrator: Sam looks more and more confused the longer you talk.  
Layla: Yeah... So I wanted to go say hi to them if that's okay.  
\>>  
Sam: Okay... I'll come with you.  
\>  
Layla(surprise): No! They hate each other. It'll be a huge mess.  
Layla(sad): I'll just go over there. You head home, okay?  
Narrator: You try to step away but Sam gently holds onto your arm.  
\*ERRATIC +1  
\>>  
Sam(sad): ...{Layla Name}, are you <i>sure</i> you're alright?  
Layla(sad): I'm fine, Sam. Really. I know I must sound crazy...  
\>  
Narrator: You take a deep breath and think of a plausible lie.  
Layla: I wasn't sure how to tell you...  
### \*Goto merm07_sam_lie  
\***  
# merm07_sam_lie  
Layla(sad)*Think: I need an excuse to send Sam home without me.  
Layla: The thing is...  
# (sld_07_02_lie_to_sam)  
## A. I have a therapy appointment.  
## B. I need to pick up some tampons.  
## C. I can't explain, but trust me?  
#### A  
\*Gain SAM_LIE_THERAPY  
\>>  
Layla(shy): You guys were right... It's a good idea. The appointment is actually right now...  
Sam(smile): That's great, {Layla Name}. Text me if you want someone to walk you back, okay?  
\>  
Layla(smile): Thanks! Seeya later...  
Sam(smile): And {Layla Name}, I'm proud of you for getting some help, okay?  
Layla(sad): Thanks, Sam... I, uh... I've got to go.  
Narrator: You jog across the street, trying to ignore the guilty feelings in your heart.  
#### B  
\*Gain SAM_LIE_TAMPONS  
Sam(shy): Oh, uh... Do you need help with that, or --  
\>>  
Sam(surprise): I mean, of course you don't need help! I just --  
Layla(smile): It's fine! I'll meet you back at the place.  
\>  
Narrator: You take off at a jog, waving over your shoulder.  
Layla(smile)*Think: Boys are so predictable.  
#### C  
\*Gain SAM_LIE_TRUST  
\>>  
Layla(sad): There's something I need to do... I can't tell you what it is.  
\>>>  
Layla(sad): I just need you to trust me.  
\>>  
Narrator: Sam looks at you for a moment, concerned... then sighs.  
Sam(sad): {Layla Name}... Of course I trust you, but --  
\>  
Layla: Good. Then go on back to the house and I'll meet you there later, okay?  
Sam(sad): ...Okay.  
Narrator: Sam turns to go, giving you a sad, confused look as you dash across the street.  
Layla*Think: At least he still trusts me this much...  
\***  
\>>  
Layla*Think: Now... Next problem.  
Narrator: Zale is waiting at a traffic signal down the block.  
\>  
Zale: ...  
Narrator: While Caden glares at a homeless woman trying to sell him flowers.  
Caden(angry): ...  
Layla(sad)*Think: I need to keep them from meeting... Who should I approach first?  
# (sld_07_03_keep_from_meeting)  
## A. Zale! *Goto merm07_approach_zale  
## B. Caden! *Goto merm07_approach_caden  
\***  
# merm07_approach_zale  
\*Gain APPROACHED_ZALE_FIRST  
\*Stop Music  
\*Play Music m_sea_mermaid_intense_02  
\*Camera Right 2  
Narrator: You dash over to intercept Zale, who waves as you approach.  
Zale(happy): Hey, {Layla Name}. Fancy meeting you here.  
Layla: Uh-huh. Didn't you come here specifically to see me?  
Zale(smile): As much as I like seeing your pretty face, I do have other things to do.  
\>>  
Layla(shy): I know that!  
Narrator: As you talk, you loop your arm through Zale's and steer him away from Caden.  
Layla(smile): ...  
# (sld_07_04_CP_approach_zale)  
## A. What <i>are</i> you doing here?  
## B. Shouldn't you be investigating in the ocean?  
#### A  
\>  
Narrator: Zale's expression hardens as he glances around at the passing crowds.  
#### B  
\>  
Zale: I was, but Tai got a lead on the Deep Sea Clan's plans.  
\***  
Zale: There's a covert operation happening here on land.  
Zale: We think the Shadow himself is disguised as a human to spy on you.  
\>>  
Layla(sad): Oh... Really?  
# (sld_07_05_CP_caden_disguise)  
## A. I had no idea...  
## B. Actually, I think I saw him... *Goto merm07_tell_zale  
#### A  
\>  
Layla(surprise): I haven't seen him.  
Narrator: You feign innocence, steering him by the elbow onto another block.  
Narrator: But the instant you round the corner, you hear Zale gasp.  
### \*Goto merm07_zale_caden_meet  
\***  
# merm07_tell_zale  
Zale(surprise): You saw him?! Where?  
Layla: He was over that way. I didn't want him to see you.  
\*Zale FLIRT +1  
\>>>  
Zale(shy): Were you... Trying to protect me?  
\>>  
Layla(shy): Maybe... I just knew you two would try to kill each other.  
\*Gain TOLD_ZALE_ABOUT_CADEN_ON_LAND  
\>  
Message: Impact | That made an impact on Zale.  
Narrator: Zale grins at you, his eyes soft with affection.  
Zale(smile): Don't worry about protecting me. I can handle him.  
Zale: Which way did you see him go?  
Narrator: You point down the street and the two of you hurry to catch up.  
Narrator: When you finally see him, you sense Zale's muscles tensing.  
### \*Goto merm07_zale_caden_meet  
# merm07_approach_caden  
\*Gain APPROACHED_CADEN_FIRST  
\*Stop Music  
\*Play Music m_sadness_melancholy_gently_casual_desire  
\*Camera Right 2  
Narrator: You hurry across the street to intercept Caden, who eyes you warily as you approach.  
\*Condition  
## A. (Condition: CHOSE_CADEN_PUNCH = 1)  
## B. (Condition: CHOSE_CADEN_FLIRT = 1)  
#### A  
Caden: Are you here to punch me again?  
Layla: Maybe. That depends on you.  
#### B  
\>>  
Layla(smile): Miss me?  
\>  
Narrator: Caden scowls at you, but you think you spot a hint of a blush on his cheeks.  
Caden: Not even a little bit.  
\***  
Caden: What do you want?  
Layla: You aren't here to see me? Isn't that what you were ordered to do?  
Caden(angry): Are you really that eager to die?  
\*Play Sound s_street  
Narrator: Someone on the sidewalk turns and stares at you, alarmed.  
\>>  
Layla(sad): Come on, let's go somewhere where we can talk.  
\>  
Narrator: You try to steer him away from the busy street but he won't budge.  
Layla(angry): Alright, look.  
# (sld_07_06_CP_approach_caden)  
## A. People are staring. That's not very <i>covert</i>.  
## B. I cooperated with you. So return the favor.  
#### A  
Narrator: Caden's eyes flick to the left and right, surveying the crowded sidewalk.  
Caden: Point taken.  
Layla(angry): So let's talk somewhere a little less public. Okay?  
#### B  
Layla(angry): You made me lie to Zale and hear you out.  
Layla(angry): The least you can do is return the favor.  
Narrator: Caden glares at you, about to argue, then sighs.  
Caden(angry): Fine. Lead the way.  
\***  
\*Stop Sound  
Narrator: Reluctantly, Caden follows you as you lead him down the sidewalk and away from Zale.  
Narrator: You're about to turn onto a less-crowded street when you see...  
### \*Goto merm07_zale_caden_meet  
# merm07_zale_caden_meet  
\*Stop Music  
\*Play Music m_rage_tension_restless  
\>>>  
Zale(angry): <i>You!</i>  
\>  
Caden(angry): Shallowtider.  
\>>  
Layla(sad)*Think: Oh crap...  
\>  
Narrator: Both men subconsciously reach for weapons... Zale to his back, Caden to his wrists.  
Narrator: Both of them come up empty.  
Caden(angry): Why are you here? This has nothing to do with you.  
\*Condition  
## A. (Condition: Zale FLIRT >= 3)  
## B. (Condition: Zale FLIRT < 3)  
#### A  
Zale(angry): If it has to do with {Layla Name}, then it has to do with me.  
#### B  
Zale(angry): Well it sure as hell doesn't have to do with <i>you.</i>  
\***  
\*Play Sound s_street  
Narrator: Around you, people are watching with interest. A few have pulled out their phones to record the fight.  
Layla(sad)*Think: Damnit, this is exactly what I didn't want to happen.  
\*Stop Sound  
Caden(angry): If we were in the ocean, you'd be dead by now.  
Zale(smile): Ha! It'll be much easier to take you out on land.  
Narrator: You can see the faint glow of Zale's tattoo through his sleeve.  
Layla(surprise)*Think: What should I do?!  
# (sld_07_07_zale_caden_meet)  
## A. Be reasonable.  
## B. Yell at them.  
#### A  
Narrator: You push to stand between them, a hand held up to stop each of them.  
\>>>  
Layla(sad): Guys! Please listen to me.  
\*Play Sound s_street  
\>>  
Layla: There are people watching, <i>recording</i> this fight you two are having.  
\>  
Caden(surprise): Recording?  
Zale: Yeah, see those little plastic rectangles in everyone's hands?  
Zale: Those are cell phones. They can record <i>moving pictures</i>...  
Caden(angry): I <i>know</i> how it works. But why would anyone be interested?  
Layla(angry): Maybe because you're yelling in the street like this is a reality show!  
\*Stop Sound  
#### B  
Narrator: You push between them yell at the top of your lungs.  
\>>  
Layla(angry): <i>Enough!</i>  
Narrator: Both boys stare at you, stunned.  
Layla(angry): The two of you are going to listen and do what I say. <i>Now.</i>  
\>  
Caden: ...Speak then.  
\***  
Layla: You don't want anyone on land knowing mermaids exist, right?  
Zale: Yes.  
Caden: It's the one thing we <i>can</i> agree on.  
Layla(angry): Then you need to watch what you are <i>yelling about</i> around people.  
Layla: Both of you need to calm down so we can talk.  
Caden(angry): Talk? What is there to talk about?  
Zale(angry): How about you start with why you're here?  
Narrator: Their words are tense, but both of them make an effort to keep their voices down as they walk with you.  
Caden: This isn't your territory. I don't have to explain myself.  
Caden(angry): Or did you forget your people don't own <i>everything.</i>  
Layla(angry): Guys!  
# (sld_07_08_argue)  
## A. What did I <i>just</i> say?!  
## B. Please stay calm!  
\***  
\*Stop Music  
\*Play Music tension7  
\*Camera Left 2  
Narrator: Over Caden's shoulder you see Sam walking across the street.  
\>>>  
Sam(smile): ...  
\>  
Layla(surprise)*Think: What?! I thought he was going back home!  
Narrator: You see your friends chatting together as they head in your direction.  
\>>>  
Maddie(happy): ...  
\>  
Layla(surprise)*Think: Maddie's with him. Damnit, are they all here?!  
Zale(surprise): {Layla Name}? You okay?  
Layla(surprise): Uhh... We need to get off the street.  
Caden: Where do you propose we --  
Layla(surprise): Hurry! Just go in there!  
Narrator: You push both boys through the doors of a clothing store.  
\*Stop Music  
\*Play Music m_rage_crisis_final_boss_01  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_city_toggery_boutique_shop.jpg-story' width='60'>
\*Scene BOUTIQUE (Color: Black)
{% endhint %}  
Caden: What are we doing here?  
Layla(sad): We're hiding.  
# (sld_07_09_hiding_for_what)  
## A. What, the 'Shadow' can't recognize that?  
## B. It's dangerous! Stay down.  
## C. My friends <i>cannot</i> see you two.  
#### A  
Layla: It's called being <i>covert.</i>  
Narrator: Zale and Caden stare at you as you hide behind a rack of clothes, peeking out of the window.  
Caden: ...Yes, you're a master of stealth.  
#### B  
Narrator: You duck behind a rack of clothes but both boys move towards the window.  
Layla(surprise): No! What are you doing?!  
Zale: You said there was danger.  
Caden: We can handle it.  
Layla(angry): Not that kind of danger!  
#### C  
Zale(surprise): Why not?  
Layla: Didn't you <i>just</i> say humans can't find out about us?  
Layla(sad): They already think something's up. If they see you two...  
\***  
\*Play Sound s_welcome_bell  
Narrator*Top: Store Clerk | Excuse me, can I help you find anything?  
Layla(shy): Oh, no! We're good. I actually, um...  
Narrator: You see Sam and Maddie have made it almost to the shop's front door.  
\>>  
Layla(surprise)*Think: Oh god!  
\>  
Narrator: You snatch a dress of the rack and push the boys to the back of the store.  
Layla(surprise): Actually I need to try this on. Come on, guys, I need your opinions!  
Zale(sad): Where are we going?  
Layla(angry): More hiding! Come on, move!  
Narrator: You herd both boys to the back of the store when a bell chimed over the door.  
\*Play Sound s_welcome_bell  
Narrator*Top: Store Clerk | Welcome! Let me know if you need help.  
Maddie(happy): Thank you, but we're fine.  
Layla(surprise)*Think: No!  
Caden: This is ridiculous. Can't we --  
\*Play Sound s_pull_curtain_01  
Narrator: You shove both of them into a dressing room and quickly swipe the curtain shut.  
\*Stop Music  
\*Play Music m_mystery_tension_heartbeat_01  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_city_fitting_room.jpg-story' width='60'>
\*Scene FITTING_ROOM (Color: Black)
{% endhint %}  
Narrator: It's a narrow fit. The three of you are forced against each other in the tight space.  
\>>  
Caden(angry): Is this really necessary?  
Zale(surprise): What's going on?  
Narrator: You're pressed up against Zale's body, his warmth radiating through you, as you face Caden.  
Layla(sad): I said we needed a private place to talk, right? Well...  
# (sld_07_10_hiding_in_fitting_room)  
## A. This is pretty private.  
## B. This will have to do for now.  
\***  
Narrator: You gesture to the space around them, accidentally brushing your hand against Zale's chest.  
Layla(shy): So... let's talk. Just keep your voices down... Whisper, maybe.  
Narrator: They both look at you like you've lost your mind.  
Caden(angry): Is this some human tradition I'm unaware of?  
Narrator: He's so close, you have to tilt your face up just to see him. You can feel Zale's breath at the back of your neck.  
\*Condition  
## A. (Condition: ZALE_IS_HOT = 1)  
## B. (Condition: CADEN_HOT = 1)  
#### A  
\*Play Sound heartbeat1  
Narrator: Your heart is pounding, and you're very aware of every shift of Zale's muscles behind you.  
\>>>  
Layla(shy)*Think: Calm down, {Layla Name}... Get a grip! This is not the time!  
#### B  
\*Play Sound heartbeat1  
Narrator: Your heart pounds loud in your ears as you try not to stare too openly at Caden's body so close to you.  
\>>>  
Layla(shy)*Think: Calm down, {Layla Name}... Get a grip! This is not the time!  
\***  
\>  
Narrator: You swallow hard, trying to focus.  
\>>  
Layla(sad): Just, uh, tell me...  
# (sld_07_11_trying_to_focus)  
## A. Why do you hate each other?  
## B. Why does my power matter so much?  
#### A  
Zale: Our clans are at war with each other.  
Layla(surprise): But you don't know each other personally?  
Layla: With how angry you both were, I thought there was some history there.  
Caden(angry): There is plenty of history between our clans.  
#### B  
Zale(surprise): I told you we could sense your magic from miles away.  
Caden: Power like that is rare. It could heal -- or destroy -- an entire clan.  
Layla(sad)*Think: He did say he followed me looking for a weapon.  
Caden(sad): It could determine who wins the war.  
\***  
Layla(sad): Why are your clans at war?  
Zale(angry): <i>His</i> clan has been raiding our towns, attacking us unprovoked.  
Caden(angry): Unprovoked. Right. What do you call hoarding resources then?  
Caden(angry): My people are starving because yours overfish and keep everything to yourselves.  
\>>>  
Zale(angry): Overfishing?! My people are barely scraping by --  
Caden(angry): You don't know the <i>meaning</i> of barely scraping by.  
\*Stop Music  
\*Play Music m_rage_crisis_final_boss_02  
\>>  
Narrator: You stumble back as Zale surges forward...  
\*+ZALE_CADEN_FIGHT  
\*Play Sound s_hit_body  
\*+shade1  
\*-shade1  
Layla(surprise): Oh my god!  
# (sld_07_12_zale_caden_fight)  
## A. Zale! Stop!  
## B. Caden! Calm down!  
#### A  
Narrator: Zale shoves Caden back against the wall.  
Narrator*Top: Sales Clerk | Is everything alright in there?  
Layla(surprise): We're fine! Thank you!  
Zale(angry): You're taking his side?  
Narrator: You lower your voice to a hiss.  
Layla(angry): Caden didn't attack anyone. You did.  
#### B  
Narrator: Zale shoves Caden back against the wall.  
\***  
\*Condition  
## A. (Condition: TOLD_ZALE_ABOUT_CADEN = 1)  
## B. (Condition: TOLD_ZALE_ABOUT_CADEN = 0)  
#### A  
Narrator: Caden tugs his shirt back into place, glaring daggers at Zale.  
Caden(angry): What did you expect from a Shallowtider, {Layla Name}?  
Narrator: He says the name of Zale's clan like he's spitting on it.  
Zale(angry): That's it!  
### \*Goto merm07_zale_leaves  
#### B  
Zale: ...Caden?  
Caden(angry): That's my name, asshole.  
Narrator: Zale turns to you, his eyes narrowing.  
Zale: But how did <i>you</i> know that?  
Layla(surprise): Um... I...  
### \*Goto merm07_said_cadens_name  
\***  
# merm07_said_cadens_name  
\*Stop Music  
\*Play Music tension2  
\*Condition  
## A. (Condition: APPROACHED_CADEN_FIRST = 1)  
## B. (Condition: APPROACHED_ZALE_FIRST = 1)  
#### A  
Narrator: Caden angles his body to draw Zale's attention onto him.  
Caden: I told her. She ran into me first on the sidewalk before finding you.  
Narrator: Zale glares at Caden, but relaxes his tense muscles.  
Zale(angry): I don't like you being on a first-name basis with this guy.  
Caden(angry): None of us like this situation, Shallowtider.  
#### B  
Narrator: No good excuse comes to mind, and a hurt expression crosses Zale's face.  
Zale(sad): I see...  
Message: Impact | That made an impact on Zale.  
Caden(angry): You don't own her, you know. She's allowed to speak to whoever she wants.  
Zale(angry): Stay <i>out</i> of this!  
\***  
### \*Goto merm07_zale_leaves  
# merm07_zale_leaves  
\*Stop Music  
\*Play Music m_intense_tension_assembling_01  
Narrator: Zale draws back his arm and punches Caden straight in the jaw.  
Layla(surprise): Oh my god!  
Narrator: Caden falls back, grabbing the curtain and ripping the entire thing out of the wall as he falls.  
\*Play Sound s_tumble_01  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_city_toggery_boutique_shop.jpg-story' width='60'>
\*Scene BOUTIQUE (Color: Black)
{% endhint %}  
\>  
Zale(angry): That's for every village your soldiers have ransacked.  
Narrator: Zale steps over Caden, heading for the door.  
Layla(sad): Zale!  
# (sld_07_13_zale_leave)  
## A. Call out to him.  
## B. Grab his arm.  
#### A  
Layla(surprise): Zale, wait!  
Zale(angry): No! I've had enough.  
Layla(sad): I'm sorry, I --  
Zale(sad): I'll come find you. I just need a minute.  
#### B  
Narrator: You grab hold of his sleeve and he whirls to glare at you.  
\>>  
Zale(angry): Let go of me.  
Layla(sad): I'm sorry, I --  
\>  
Zale(sad): ...Let me cool off, okay? I'll talk to you later.  
\***  
\*Play Sound s_footstep_01  
Narrator: He turns on his heel and storms out of the boutique.  
Maddie: Did anyone get hurt?  
Sam: Stay back, it could be dangerous.  
Layla(surprise)*Think: Oh crap!  
Caden: ...  
\*Stop Music  
\*Play Music m_melancholy_tension_heartbeat  
Narrator: Caden looks at the fear on your face, then back at the boutique where Sam's footsteps are coming faster.  
\>>>  
Caden: Stay quiet.  
\*Play Sound s_inhale_fear  
Layla(surprise): What are you -- Mmff!  
\>  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_black.jpg-story' width='60'>
\*Scene BLACK (Time: 0.2)
{% endhint %}  
Layla(angry)*Think: He threw the curtain over me!  
Narrator: You hear your friend's voices come closer and closer.  
Narrator*Top: Sam's Voice | Are you alright, sir? We heard a crash...  
Narrator*Top: Caden's Voice | Oh I'm fine! You should see the other guy.  
Layla(surprise)*Think: Is that what Caden sounds like when he's being friendly?!  
Narrator: You hear Sam's awkward laugh, the one he makes when he's nervous.  
Narrator*Top: Sam's Voice | Right... Okay, just wanted to check. Seeya.  
Narrator: Sam's footsteps retreat and you hear him leave the store.  
\*Stop Music  
\*Play Music magic  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_city_toggery_boutique_shop.jpg-story' width='60'>
\*Scene BOUTIQUE (Color: Black)
{% endhint %}  
Layla(surprise): Wow.  
# (sld_07_14_caden_guile)  
## A. Okay, I'm impressed.  
## B. You were so friendly!  
#### A  
\>>  
Layla(smile): That was some really quick thinking.  
Caden: Really? It wasn't exactly a masterful strategy.  
Layla(angry): Do you ever just take a compliment?  
\>  
Narrator: Caden scowls and turns away from you.  
\*Caden FLIRT +1  
Caden(shy): Anyway, we need to go.  
#### B  
Layla(happy): I didn't know it was possible.  
Caden(angry): Yes, you found me out. I'm an actual person.  
Narrator: His voice is sarcastically deadpan.  
Caden: Whatever will I do now that you know my secret.  
\***  
Narrator*Top: Sales Clerk | Excuse me! Are you going to pay for that?  
Narrator: The angry store employees glare at you and the mess you've made. You realize you're still holding the dress you were 'trying on'.  
Layla(surprise): Oh! Um... Well...  
Layla*Think: Would this even look good on me? I just grabbed it at random...  
Narrator: You try to imagine what it would look like...  
\*Layla Outfit Prem_Sunny_Smile (Tag: Record)  
Layla(smile): ...  
\*Layla Outfit Reset  
Layla(surprise): Well... It is pretty, but I'm not sure if yellow is my color...  
Caden: Really? I think you'd look good in yellow.  
Caden: It suits you.  
Layla(shy): Oh...  
Narrator: Sales Clerk | Well?  
\*Layla Outfit Prem_Sunny_Smile (Tag: Record)  
Layla(smile)*Think: What should I do?  
\*Model  
# (sld_07_14_pay_dress)  
## A. Apologize and leave.  
## B. Buy the dress! (Cost: 19 Diamond ID: look_sld_07_sunny_smile)  
#### A  
\*Layla Outfit Reset  
Layla(sad): I'm sorry, but we really have to go...  
Narrator: The workers in the shop all glare at you as you quickly duck out of the store.  
#### B  
\*Gain PREM_SUNNY_SMILE  
Narrator: You pay the shop clerk, then quickly change into the dress.  
Layla(smile): Hopefully that makes up for... some... of the trouble we caused them.  
Narrator: Caden's gaze sweeps over the dress, then pulls back up to your face distractedly.  
Caden: Huh? Oh... Yeah, they can't be too mad...  
Narrator: He clears his throat and hurries to leave the shop.  
Layla*Think: What was that about...  
\***  
### \*Goto merm07_caden_romance_upsell  
# merm07_caden_romance_upsell  
\*Stop Music  
\*Play Music merry2  
\*  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_city_town_street_day.jpg-story' width='60'>
\*Scene TOWN_STREET_DAY (Color: Black)
{% endhint %}  
\*Camera Right 0  
\*  
\*Camera Left 3  
Narrator: You search the street for Zale or Sam but see no familiar faces.  
\*Camera Right 3  
Layla(sad): I guess the coast is clear...  
Layla(sad)*Think: When this is over, I'll have a lot of apologies to make...  
\*  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_3_city_town_center_day.jpg-story' width='60'>
\*Scene TOWN_CENTER_DAY (Color: Black)
{% endhint %}  
\*Camera Left 0  
\*  
\*Camera Middle 3  
Narrator: You walk to the park, where families are picnicking and little kids are running around having fun.  
Narrator: Caden follows you, wincing as he tenderly touches his jaw.  
Layla(sad): Does it hurt?  
Caden(angry): You ever been punched in the face before? Of course it hurts.  
Layla(sad): You need to put ice on it.  
Caden: Ice? Hmm... We have a cooling ointment underwater, but I suppose ice would work.  
Narrator: You look around and spy a food truck in front of the city's main park.  
Layla(sad)*Think: I should...  
# (sld_07_15_take_care_of_caden)  
## A. Take care of Caden. (Cost: 22 Diamond ID: plot_sld_07_caden) *Goto prem_caden_nachos  
## B. Say goodbye.  
#### B  
\*Stop Music  
\*Play Music magic  
Layla: I guess, uh... Take care?  
Narrator: You give Caden an awkward wave and step backward.  
Layla(sad): Although... I guess you're just going to keep watching me, aren't you?  
Caden: I have my orders, yes.  
Layla(angry): Stalking people is incredibly creepy, you know.  
Narrator: Caden shrugs one shoulder.  
Caden: My orders remain. I have to discover if you're the person my master seeks.  
\>>  
Layla(angry): I'm not.  
Caden(smile): You're very confident of that.  
\>  
Narrator: Caden steps into your space, his height making you lean back.  
Caden: But I'm not so sure.  
Narrator: He's so close, you could reach out and touch him easily.  
Layla(surprise): You know, I--  
### \*Goto merm07_altogether  
\***  
# prem_caden_nachos  
\*Camera Left 3  
\*Gain GOT_NACHOS_WITH_CADEN  
\*Stop Music  
\*Play Music m_sea_beneath_gently  
Layla: Come on... Let's get you fixed up.  
Narrator: You buy nachos from the food truck and they kindly give you a bag of ice as well.  
Caden: This really isn't necessary.  
Layla(smile): Oh?  
# (sld_07_15_DP1_is_not_necessary)  
## A. You want your soldiers to know you got punched?  
## B. Hush and let me help you.  
#### A  
Caden(shy): ...Fine, give me the ice.  
#### B  
Narrator: Caden gives you a look but hushes as asked.  
\***  
Narrator: The two of you walk over to a picnic table and sit down.  
\*Stop Music  
\*Play Music moment  
Layla*Think: I should...  
# (sld_07_15_DP2_ice_for_caden)  
## A. Care for him myself.  
## B. Let him do it.  
#### A  
Layla(smile): Hold still.  
Caden: What are you --  
Narrator: You gently press the ice pack to his jaw.  
\>>>  
Layla: Is that okay? Does it hurt?  
Caden(shy): You're fine.  
\>>  
Narrator: You adjust the pack, your fingers delicate on his face for balance.  
Caden(shy): Um... This is kind of...  
Narrator: Caden's voice is rough and quiet, and his gaze is lowered so his lashes fan against his cheek.  
Layla(sad): I can stop --  
Caden(sad): No, it's fine... Just...  
\*Caden FLIRT +1  
Caden(shy): No one's ever done this for me before.  
Narrator: He takes the ice from you and this time you let him.  
#### B  
Narrator: You hand him the ice and sit beside him as he presses it to his jaw.  
Caden: Thank you for this. You are... surprisingly kind.  
Layla(smile): Why is that so surprising?  
Narrator: His eyes are downcast, his voice full of sorrow as he speaks.  
Caden: I haven't met much kindness in my life. It's rare. Precious.  
\***  
Narrator: Caden seems lost in thought, so you dig into your nachos.  
Narrator: After a few quiet moments, he finally notices you.  
\>>  
Caden: What is that... <i>mess</i> you're eating?  
Layla(happy): Nachos! It's tortilla chips topped cheese, salsa, guacamole...  
Caden: I don't know what half those words mean.  
Layla: Hmm... I guess mermaids wouldn't have Mexican food.  
Caden: There are mer off the coast of your Mexico but they don't eat... <i>that.</i>  
\>  
Layla(surprise): Oh!  
# (sld_07_15_DP3_mermaid_food)  
## A. What are they like?  
## B. Are there mermaids all over the world?  
#### A  
Layla(happy): Did you have to speak Spanish to talk with them?  
Caden(surprise): No... They actually spoke the dialect of the native humans.  
Layla(surprise): Wow! Why do your clans not speak the same?  
Caden: Our clans learned English from pirates, according to history.  
Layla(happy): So the old stories are real after all...  
Caden(smile): Yes, but not the part where we drowned sailors and ate them.  
#### B  
Caden: Of course. Most remain carefully hidden and we're not in contact.  
Caden: But a few are, and we've heard stories of others.  
Layla(surprise): Are there arctic mermaids?  
Caden(surprise): Ah, no... The selkies are better suited to arctic climates.  
Layla(surprise): Selkies are real?!  
Narrator: You startle a laugh out of Caden. His laughter is low, rich, and soft.  
Caden(smile): You're amazed by such ordinary things.  
Layla(smile): They're only ordinary in your world, not mine.  
\***  
\*Stop Music  
\*Play Music m_romance_beauty_love  
Narrator: Caden reaches for a bite of your nachos.  
\>>>  
Caden: May I?  
Layla(happy): Of course!  
\>>  
Narrator: You watch him struggle to scoop toppings onto his chip and get it to his mouth without spilling.  
Layla(happy): And the verdict is...?  
Caden: Mm... It tastes good, but it's so <i>messy</i>.  
Layla(happy): Yeah... But some of the best things in life are messy.  
\>  
Narrator: A soft, small smile lights up Caden's face, and he seems more relaxed than you've seen so far.  
Layla(shy)*Think: There's just something about him...  
Layla(shy): Caden...  
Caden(smile): Hmm?  
Layla(shy): I was wondering --  
### \*Goto merm07_altogether  
# merm07_altogether  
Layla(surprise): Ow!  
Narrator: A little boy crashes into you from behind, knocking you off-balance.  
Narrator: Your arms pinwheel for a moment then latch onto Caden's jacket to break your fall.  
\>>>  
Layla(surprise): Aah!  
\*+shade1  
\*Play Sound s_tumble_01  
\*-shade1  
Narrator: As you crash together, you squeeze your eyes shut, prepared to hit the ground hard, but --  
Caden: You okay?  
Narrator: Caden is on top of you, one hand cradling your head, his arms around your body to break your fall.  
\>>  
Layla(surprise)*Think: Oh my god...  
# (sld_07_16_caden_cradling)  
## A. (He has fast reflexes!)  
## B. (He's holding me in his arms!)  
#### A  
Layla(surprise): You move fast.  
Narrator: Caden smirks at you, his voice quiet for only you to hear.  
Caden(smile): Told you I could have killed you if I wanted.  
Layla(surprise): Is that supposed to be comforting?!  
Caden(smile): You're still alive, aren't you?  
#### B  
Layla(shy): Um, Caden... You...  
Narrator: You can feel his heartbeat, the soft fabric of his shirt beneath his jacket.  
Layla(shy)*Think: He smells really, really good...  
\*Caden FLIRT +1  
Caden: Can you move?  
\***  
Narrator: Your legs are tangled together. You can feel every move his body makes.  
Layla(shy): Um... Yeah...  
\>  
\*Play Sound s_cough_01  
Narrator: Someone clears their throat and you suddenly realize you have an audience.  
\*Stop Music  
\*Play Music m_suspense_fear_intense_many_01  
Zale(angry): ...Can you get off of her?  
Layla(surprise): Zale! There you are!  
Narrator: Caden rises in a graceful, fluid motion, and holds his hand out to help you up.  
Narrator: Zale holds out his own hand like a challenge.  
Layla(sad)*Think: Does everything have to be a competition with these two...  
# (sld_07_17_help_you_up)  
## A. Take Zale's hand.  
## B. Take Caden's hand.  
## C. Stand up by yourself.  
#### A  
Narrator: You grab Zale's hand and he hauls you to your feet.  
#### B  
Narrator: Caden takes your hand and pulls you up with surprising, easy strength.  
#### C  
Layla(angry): Ugh.  
Narrator: You stand up on your own, glaring at both of them.  
\***  
Zale(angry): Is there something going on between you two?  
Layla(surprise): There was a kid... I tripped, and --  
Zale(angry): Not that. I want to know what he's <i>doing</i> here.  
Caden: I'm here for exactly the same reason you are.  
Narrator: He points to you, but keeps his eyes on Zale.  
Caden: You're hoping her power can be useful to you and your clan.  
\>>  
Layla*Think: ...Useful?  
# (sld_07_18_useful_power)  
## A. Zale is my friend.  
## B. Zale is helping me understand my powers.  
## C. ...Why <i>are</i> you here, Zale?  
#### A  
Layla(angry): He's here because he cares about me.  
\>  
Narrator: Caden's gaze turns cold.  
Caden: Does he? And did he care about you <i>before</i> your powers manifested?  
#### B  
Caden: And he's doing this out of the kindness of his heart, huh?  
Layla(sad): Sometimes people are nice, Caden.  
\>  
Caden(sad): But usually they're not. Not unless they want something.  
#### C  
\>  
Zale: We heard <i>Caden</i> was looking for you on land, so I came to protect you.  
Layla(sad): But Caden hasn't done anything to me. He's not a threat.  
Zale(angry): He <i>is</i> a threat!  
Layla(angry): Why? I'm not part of your clan, or your war, or any of it!  
Caden: But he wants you to be. Just like I'm hoping you'll help my clan.  
\***  
\*Stop Music  
\*Play Music m_tension_rage_mystery_forest_fear_02  
Narrator: Zale is strangely quiet, no longer arguing or picking fights with Caden.  
\>>  
Layla(sad): Zale?  
Zale(sad): ...  
\>  
Caden: How did you two meet?  
Layla: I just... ran into him. Twice on land, and then right after --  
Zale(sad): He's trying to make me the bad guy here. I'm not.  
Narrator: He sighs deeply and runs a hand through his hair.  
Zale: Before we met... Tai had sensed strong magic on land.  
\*Condition  
## A. (Condition: CONFIDED_IN_ZALE_ABOUT_FLASHES = 1)  
## B. (Condition: CONFIDED_IN_ZALE_ABOUT_FLASHES = 0)  
#### A  
Zale: Those flashes you told me about? They were small bursts of magic.  
#### B  
Zale: You were giving off these little pulses of magical energy... like a beacon.  
Layla(surprise)*Think: Or like those flashes I kept seeing...  
\***  
Zale(sad): {*Intense I tracked them to their source, worried it was a threat.}  
Zale: And what I found was <color=#ff6ec7>you</color>.  
Caden: So your orders were the same as mine. Follow her, <i>investigate</i> her --  
Zale(angry): It wasn't <i>like that!</i> No one ordered me to do anything!  
Layla: I see...  
# (sld_07_19_no_orders)  
## A. You were spying on me too. *Goto merm07_confront_zale  
## B. Was kissing just part of your plan? (Condition: KISSED_ZALE = 1) *Goto merm07_confront_zale_kiss  
## C. I understand. It's not a big deal.  
## D. Caden, stop trying to make Zale look bad!  
#### C  
\*Gain STOOD_UP_FOR_ZALE  
Narrator: You think about everything you've been through with Zale over the past few days.  
Layla*Think: He calmed me down from a panic attack, taught me how to swim...  
\>>  
Layla: It's okay, Zale. I get it. The magic may have led you to me...  
Layla(smile): But you've been nothing but kind and good to me. I trust you.  
\>  
Caden(angry): ...  
### \*Goto merm07_friend_fight  
#### D  
\*Gain STOOD_UP_FOR_ZALE  
Layla(angry): You're twisting the situation and manipulating everything. Cut it out!  
Caden: Was anything I said not true?  
Layla(angry): No, but you left out a lot of important parts.  
Layla: Zale helped me through some terrifying moments over the last week.  
Layla: He's been a good friend to me, and I trust him a lot more than I trust you.  
### \*Goto merm07_friend_fight  
\***  
# merm07_confront_zale  
\*Gain FEEL_ZALE_BETRAYED_YOU  
\*Stop Music  
\*Play Music m_sadness_ambient_namaste02  
Layla(sad): I thought you were my friend, helping me because you cared...  
Zale(surprise): {Layla Name}, I <i>do</i> care!  
Zale(surprise): When I started searching for the magic, I didn't expect to find you.  
Zale(sad): I didn't know you'd be so smart, or so much fun to talk to, or --  
Narrator: He makes a frustrated sound, balling his hands into fists.  
Zale(sad): I'm not good at this. I've never lied to you. I've always been myself.  
Layla(sad): But then...  
# (sld_07_20_CP_searching_magic)  
## A. Why didn't you tell me until now?  
## B. You knew about my magic all along.  
#### A  
Zale(sad): I wanted you to get to know my clan, to <i>want</i> to help us on your own.  
Zale(sad): I didn't want to overwhelm you since you were so new to...  
#### B  
Layla(sad): I was so scared, worried I was crazy...  
Narrator: He moves to take your hands in his.  
Zale(sad): I wanted to tell you, but what if I was wrong? I couldn't reveal...  
\***  
Narrator: His eyes flick to Caden for a brief moment, and you remember you have an audience.  
Layla*Think: Caden doesn't know I thought I was human for years...  
Layla(sad)*Think: Maybe I should be more careful about who I trust.  
\*Condition  
## A. (Condition: KISSED_ZALE = 1) *Goto merm07_confront_zale_kiss  
## B. (Condition: KISSED_ZALE = 0) *Goto merm07_friend_fight  
\***  
# merm07_confront_zale_kiss  
\*Stop Music  
\*Play Music romance  
Zale(sad): {Layla Name}... No. Never.  
Narrator: He steps into your space, grasping your hands in his own.  
\>>  
Zale(sad): If anything, Tai has warned me again and again not to get so close to you.  
Zale(smile): But I can't help it. You're... the best surprise.  
Layla(shy): Zale...  
Zale(sad): I'm so glad we met. It might not have been under the best circumstances...  
Zale(smile): But I absolutely don't regret it.  
\>  
Narrator: Caden rolls his eyes.  
Caden(angry): God, do you hear yourself? It's revolting.  
Zale(smile): Jealous is a bad look on you.  
Caden(angry): Why the hell would I be jealous of --  
Narrator: He stops, staring over your shoulder.  
### \*Goto merm07_friend_fight  
# merm07_friend_fight  
\*Stop Music  
\*Play Music m_rage_tension_dark  
Caden(sad): Damn...  
Layla(surprise): What is it?  
Narrator: His gaze focuses on something behind you. You turn to see...  
Sam(surprise): {Layla Name}?  
\*Camera Middle 2  
Narrator: All four of your friends are standing right there in the park.  
Layla(surprise): Sam! Maddie!  
# (sld_07_21_friends_greeting)  
## A. Hi you guys!  
## B. What are you doing here?  
## C. This isn't what it looks like!  
#### A  
Narrator: You greet them with a friendly smile, but none of them return it.  
#### B  
Maddie(angry): You first.  
#### C  
Caden: ...Smooth.  
Narrator: You try to elbow him in the ribs, but he dodges you.  
\***  
Addison: Sam's been texting you for a while, now. Didn't you get the messages?  
Layla(sad): Uh, my phone was off...  
\*Condition  
## A. (Condition: SAM_LIE_THERAPY = 1)  
## B. (Condition: SAM_LIE_TAMPONS = 1)  
## C. (Condition: SAM_LIE_TRUST = 1)  
#### A  
Maddie(angry): And who is this? Sam said you were seeing a therapist.  
Layla(sad): I, uh...  
#### B  
Maddie(angry): Uh-huh. And it takes <i>hours</i> just to get tampons.  
Layla(surprise): Well, that is...  
#### C  
Sam(sad): Is this what you needed me to trust you about?  
\***  
\*Condition  
## A. (Condition: SAM_ROMANCE = 1)  
## B. (Condition: SAM_ROMANCE = 0)  
#### A  
Narrator: Sam shoots a panicked glance at Caden, Zale... and how close you're standing to them.  
Sam(sad): So, um... How do you all know each other?  
#### B  
Narrator: Sam swallows hard, but puts on a smile as he greets the mermen.  
Sam(smile): Hi, I'm Sam. I don't think we've met.  
\***  
Maddie(angry): Who's this guy? {Layla Name}, who are these people?  
Shaun(sad): Mads, hey. Calm down...  
Maddie(angry): Say one more word and you're sleeping on the couch.  
Narrator: Shaun shuts his mouth with a click.  
Addison(sad): Well? Who are these guys?  
Layla(surprise)*Think: Tell them...  
# (sld_07_22_friends_question)  
## A. They're who rescued you.  
## B. They're your cousins.  
## C. You're dating them. *Goto merm07_dating_option  
#### A  
Layla(surprise): Remember those guys I said helped me get back home?  
Narrator: You gesture at Zale and Caden.  
Layla(surprise): This is them!  
Maddie(surprise): Oh! Thank you both so much for taking care of her!  
Caden(smile): It was no problem.  
Narrator: Zale glares at Caden, but graciously accepts Maddie's thanks.  
### \*Goto merm07_erratic_check  
#### B  
Layla: These are my cousins.  
Sam(sad): I've met your cousins... But not these two.  
Layla(sad): They're distant cousins.  
Narrator: You glance at Zale and Caden, who look nothing alike.  
Layla(sad): ...Very distant cousins.  
### \*Goto merm07_erratic_check  
\***  
# merm07_dating_option  
\*Stop Music  
\*Play Music m_blue_epilog_sadness  
Layla(surprise): I've kind of been seeing them.  
Sam(sad): What?  
Addison: 'Seeing' as in... dating?  
Shaun: Wait. Which one?  
Layla(surprise): Well, I --  
Narrator: Caden smiles easily at your friends, feigning charming shyness.  
Caden(shy): Nothing's actually official. It's just casual, really.  
Caden(shy): We were actually on a date right now.  
Zale(angry): Excuse me?  
Sam(sad): A date?  
Layla(surprise): Actually...  
# (sld_07_23_explain_dating)  
## A. Yeah, it was a date. (Condition: GOT_NACHOS_WITH_CADEN = 0)  
## B. Yeah, it was a date. (Condition: GOT_NACHOS_WITH_CADEN = 1)  
## C. I wouldn't call it a 'date.'  
#### A  
Zale(angry): Seriously?  
Layla(shy): It was a spur-of-the-moment thing... Not really planned...  
Sam(sad): So you lied about it?  
Layla(shy): I wasn't thinking... I didn't know how to tell you...  
Layla(sad): I'm so sorry.  
#### B  
Zale(angry): Seriously?  
Layla(shy): It's not a big deal, we just got nachos together.  
Sam(sad): Not a big deal? But you were willing to lie about it.  
Layla(shy): I wasn't thinking... I didn't know how to tell you...  
Layla(sad): I'm so sorry.  
#### C  
Layla(sad): We met up by accident. I really wouldn't call it a date.  
Sam: Oh...  
Narrator: Sam is wary, but his expression seems slightly less sad than before.  
\***  
Addison: Why lie about it at all?  
Maddie(angry): Yeah, that's the part we're upset about, {Layla Name}.  
Maddie(angry): Date whoever you want. I don't care. But don't <i>lie.</i>  
Maddie(angry): This just isn't like you at all.  
\*ERRATIC +1  
Layla(sad): I'm so sorry, Mads...  
### \*Goto merm07_erratic_check  
# merm07_erratic_check  
\*Stop Music  
\*Play Music m_blue_mystery_decline_02  
\*Condition  
# (sld_07_24_erratic_check)  
## A. (Condition: ERRATIC = 0)  
## B. (Condition: ERRATIC >= 3)  
## C. (Condition: ERRATIC <= 2)  
#### A  
Message: Impact | Your friends still trust you.  
Maddie(sad): Please don't lie to me, {Layla Name}. I'm worried about you.  
Narrator: Your best friend wraps you up in a hug. Over her shoulder, you see Sam.  
Sam(sad): ...  
Narrator: He's looking at Zale and Caden like they stole something precious to him.  
#### B  
Message: Erratic | Your friends are deeply worried.  
Maddie(sad): I'm scared for you, {Layla Name}. You're kind of freaking me out.  
Shaun(sad): It's like ever since we came here, you're a different person.  
Layla(surprise): Guys! I promise I'm the same person!  
Layla(sad)*Think: I just... sometimes have a tail now.  
Addison: It's not a bad idea to see a therapist, {Layla Name}.  
Shaun: Yeah, there's no shame in it. Mental health is as important as physical health.  
Layla(sad): I'll think about it...  
Layla(sad)*Think: If I make any more mistakes, they might do something drastic...  
#### C  
Message: Erratic | Your friends know something's up.  
Maddie(sad): I just wish you'd talk to us... about <i>whatever</i> is going on with you.  
Layla(sad)*Think: I promise, Maddie... I would if I could...  
Shaun: If you ever need to talk, you know we're here for you.  
Sam(sad): You can always come to me, {Layla Name}.  
Layla(sad): Guys... You're so sweet... But I promise I'm fine.  
\***  
Narrator: An awkward silence falls over the group.  
Maddie(sad): We were about to text you and see if you wanted to meet up for dinner.  
Maddie(sad): But I kind of want a break from you right now.  
Layla(surprise): Mads...  
# (sld_07_25_want_a_break_from_you)  
## A. That's fair, I guess.  
## B. I'm so sorry.  
#### A  
Layla(sad): I'll see you guys back at the house, then?  
#### B  
Maddie(sad): I'm sorry too.  
\***  
### \*Goto merm07_zale_sam_romance_upsell  
# merm07_zale_sam_romance_upsell  
Narrator: You hug your friends goodbye one last time, feeling so much distance growing between you.  
Layla(sad)*Think: I hate this.  
Narrator: Zale puts a warm hand on your shoulder as your friends walk away.  
Narrator: Sam is the only one hesitating, torn between going with the group or staying with you.  
Zale(sad): Hey. We should probably talk, but... That looked rough.  
Narrator: You nod without speaking, feeling the hot tears welling up in your throat as you stare at the ground.  
Zale: That <i>'Caden'</i> asshole slipped away during the argument.  
Zale: It's just you and me.  
Sam(sad): And me.  
Narrator: You look up and see Sam standing there, expression full of concern.  
Sam(sad): What do you need, {Layla Name}?  
Layla(sad): Right now all I want is...  
# (sld_07_26_what_do_you_need)  
## A. ...to talk to Zale. (Cost: 24 Diamond ID: plot_sld_07_zale) *Goto prem_merm07_zale  
## B. ...you, Sam. (Cost: 24 Diamond ID: plot_sld_07_sam) *Goto prem_merm07_sam  
## C. ...to be alone.  
#### C  
Narrator: Zale gives your shoulder a squeeze, then pulls away.  
Sam(sad): Okay. Text me if you need anything, alright?  
Layla(sad): Okay... Thank you...  
Zale(sad): I'll see you around.  
Narrator: The two boys walk away, leaving you to sort out your thoughts and feelings on your own.  
### \*Goto merm07_final_scene  
\***  
# prem_merm07_zale  
\*Stop Music  
\*Play Music suspicion  
\*Gain DID_ZALE_PREM_AFTER_FIGHT  
\>>  
Layla(sad): Zale, we really need to talk.  
Narrator: He sighs deeply and rubs the back of his neck.  
Zale(sad): Yeah, okay.  
Narrator: You hug Sam goodbye, then walk with Zale to the beach side of the park.  
\*Camera Right 3  
Layla(sad): Where do we start?  
Zale: Well... Tonight I learned that you've been fraternizing with the enemy.  
Layla(sad): ...  
# (sld_07_26_A_DP1_enemy_fraternizing)  
## A. He's your enemy, not mine.  
## B. I'm using him for information.  
#### A  
\*CADEN_CAUSE +1  
Zale(sad): Yeah... That's the part that hurts.  
Zale: You talked with the townspeople he attacked. How can you be on his side?  
Layla(sad): He didn't kill anyone. He was raiding their food stores.  
Narrator: Zale takes a deep breath then lets it out in a rush.  
\>  
Zale(sad): I don't want to fight with you. We'll have to agree to disagree for now.  
#### B  
Zale(surprise): Wait... Really?  
Layla: He approached me at first because he had something to tell me.  
Zale: And did he?  
Narrator: You shrug, remembering that night in the witch's garden.  
Layla(sad): He said his 'master' is searching for someone.  
Layla(sad): They think that person is me.  
Narrator: Zale thinks about this for a long moment.  
\>  
Zale: I'll have to ask Tai if he knows what that's about.  
\***  
\*Stop Music  
\*Play Music seawave  
Narrator: The ocean waves lap at the shore with a steady, reassuring rhythm.  
\*Stop Music  
### \*Goto merm07_zale_trust_check_1  
# merm07_zale_trust_check_1  
\*Condition  
## A. (Condition: TOLD_ZALE_ABOUT_CADEN_ON_LAND = 1) *Goto merm07_zale_trust_check_2  
## B. (Condition: TOLD_ZALE_ABOUT_CADEN_ON_LAND = 0) *Goto merm07_zale_apology  
\***  
# merm07_zale_trust_check_2  
\*Condition  
## A. (Condition: TOLD_ZALE_ABOUT_CADEN = 1)  
## B. (Condition: TOLD_ZALE_ABOUT_CADEN = 0) *Goto merm07_zale_apology  
#### A  
\*Stop Music  
\*Play Music m_romance_beauty_love  
Message: Impact | Zale remembered your actions.  
Zale: Thank you for telling me about Caden, about what was going on.  
Zale(smile): I like knowing that you're on my side. That I can trust you.  
Narrator: He holds up a hand as if he's about to arm wrestle you.  
Layla(surprise): What's this?  
Zale(smile): Sorry... It's a symbolic gesture among mer warriors.  
Zale(smile): We do this as a promise to the other that we have their back.  
Narrator: You reach up and place your hand in his. He grasps it firmly, pulling your entwined fists against his chest.  
Zale(shy): Usually the other person pulls as well... It's a strength thing.  
Narrator: You can feel his heartbeat under your hand as he gently holds it over his chest.  
Zale(shy): But this works too...  
Narrator: He clears his throat, trying not to smile any more than he already is.  
### \*Goto merm07_zale_romance  
\***  
# merm07_zale_apology  
\*Stop Music  
\*Play Music m_gently_lifting_dreams_01  
Layla(sad): I'm sorry I lied to you.  
Narrator: Zale sighs deeply and hangs his head.  
Zale(sad): We haven't known each other very long, and you've been through a lot.  
Zale(sad): But I hope you learn that I'm someone you can trust... With anything.  
Layla(shy): I'll keep that in mind.  
### \*Goto merm07_zale_romance  
# merm07_zale_romance  
Zale: I have to admit... Seeing you today with Caden, and that other guy...  
Zale(shy): I may have gotten a little, uh...  
Layla(smile): Jealous?  
Zale: Your words, not mine.  
Layla(smile)*Think: I should...  
# (sld_07_26_A_DP2_zale_jealous)  
## A. Put my head on his shoulder.  
## B. Snuggle close.  
#### A  
Narrator: With a happy sigh, you rest your head on his shoulder.  
\*Zale FLIRT +1  
Zale(shy): Getting comfy?  
Layla(smile): Yes... You make a very nice pillow.  
#### B  
Narrator: You tuck yourself against his side. He puts an arm around you and rests his hand on your hip.  
\*Zale FLIRT +1  
Zale(smile): There... this is nice. Just you, me, and the ocean.  
\>>  
Layla(happy): And all the people at the park.  
Zale(happy): Shh, don't ruin the moment.  
\>  
\***  
Narrator: Zale kisses the top of your head, sending butterflies dancing in your chest.  
\>>  
Zale(smile): You know what my favorite thing is about you have legs?  
Layla(happy): That they're hot as hell?  
Zale(happy): That... But also...  
Narrator: Zale drops on his back in the sand, grabbing you by your hips and lifting you on top of him.  
Layla(surprise): Woah!  
\*Stop Music  
\*Play Music m_intense_sprightly_connection  
Narrator: Your knees dig into the sand on either side of his hips as you stare at him.  
Zale(happy): <i>This.</i> Can't do this with a tail.  
\>  
Layla(shy)*Think: I should...  
# (sld_07_26_A_DP3_tease_zale)  
## A. Rock my hips and tease him.  
## B. Get off of him.  
#### A  
Narrator: You roll your hips and watch him part his lips, eyes suddenly intense.  
Layla(smile): What? Don't like that?  
Narrator: A low growl sounds in Zale's throat as he holds onto your hips so you can't move.  
Zale: {Layla Name}... You're driving me crazy.  
Narrator: You feign innocence, wiggling your body under his touch.  
Layla(happy): Is that so...  
#### B  
Narrator: You roll off of him just as quickly as he pulled you up.  
Layla(smile): Next time <i>ask</i> before you do that.  
Zale(smile): Ah... So you're saying there'll be the next time.  
Narrator: You cover his smug face with your hand, laughing.  
Layla(happy): Cut it out!  
Narrator: Zale puts his arms around you and kisses your cheek.  
Zale(happy): Never.  
\***  
Layla(smile)*Think: I want to...  
# (sld_07_26_A_DP4_flirt_with_zale)  
## A. Kiss him.  
## B. Hold him close.  
#### A  
\*Gain KISSED_ZALE  
Layla(happy): Why haven't you tried to kiss me yet?  
Narrator: Zale wastes no time. He pulls you close to him, his large hands cupping your face as he kisses you.  
Narrator: There's salt spray on his lips as his hand tangles in your hair, the other pressing your hips against his own.  
Zale: {Layla Name}...  
Narrator: He groans low in his throat, each kiss intense, claiming you.  
Narrator*Top: Voice | Ahem...  
Narrator: You look up and see a young mother glaring at the two of you and shepherding her children away.  
Layla(surprise): Oh crap... We're uh... kind of in public.  
Narrator: Zale reluctantly releases you, settling for putting his arm around you in a way that is much more family-friendly.  
Zale: When we get back to the ocean...  
Narrator: You can hear how much he wants you in the rough sound of his voice against your ear.  
\>>  
Zale: I'm going to kiss you for as long as I want and won't let anybody stop me.  
Layla(smile): Is that a promise?  
\>  
Narrator: He kisses you again, sealing the deal, then settles for laying beside you in the sand.  
#### B  
Narrator: You cuddle against him, feeling warm and safe in his arms.  
Zale(smile): I wish things could be like this forever.  
Layla(smile): Me too.  
\***  
Narrator: The two of you hold each other close, enjoying the sun on your face and the sound of the waves.  
### \*Goto merm07_final_scene  
# prem_merm07_sam  
\*Stop Music  
\*Play Music m_gently_romance_heavenly  
\*Gain DID_SAM_PREM_AFTER_FIGHT  
\>>  
Sam(smile): {Layla Name}...  
Narrator: Sam steps forward and you practically melt into his arms as he holds you close.  
Sam(smile): You always have me.  
Narrator: Zale steps away awkwardly, a conflicted expression on his face.  
\>  
Zale(shy): I'll leave you two alone, then...  
\*Camera Right 3  
Narrator: You and Sam walk towards the beach, your shoulders bumping as you go.  
Sam: Can I ask --  
Layla(sad): If it's at all related to what just happened, the answer is no.  
Layla(sad): I can't take any more of that.  
Sam(shy): No... I was going to ask... Can I hold your hand?  
Layla(shy): Sam...  
# (sld_07_26_B_DP1_holding_hand)  
## A. Yes of course.  
## B. You don't have to ask.  
#### A  
Sam(shy): ...  
#### B  
Sam(smile): Yes I do. I'm a gentleman.  
Layla(happy): Even about holdings hands...?  
\***  
Narrator: Sam slips his hand into yours. Your fingers interlock like they were meant to be together.  
\>>  
Sam(shy): I know this is all very junior high, but... I've wanted to do that for years.  
Layla(shy): Years?  
\>  
Narrator: You find a place to sit and the two of you watch the waves as they roll into the shore.  
Sam(smile): Do you remember Mr. Bergenheimer's class? In junior high?  
Layla(happy): I think so. Didn't he make us do those awful projects?  
Sam(smile): The ones to help us 'find our passion'...  
Sam(surprise): I didn't think they were that bad.  
Sam: Do you remember yours?  
Layla(smile): My 'passion' in middle school was...  
# (sld_07_26_B_DP2_passion_in_the_school)  
## A. Dance.  
## B. Animals.  
## C. Outer Space.  
## D. Video Games.  
#### A  
Layla(happy): My dream was to be a backup dancer and go on tour with pop stars.  
#### B  
Layla(happy): I wanted to be a veterinarian my whole life...  
Layla(sad): Until I realized I'd have to actually do <i>surgery</i> on the animals.  
#### C  
Layla(happy): I had those glow-in-the-dark stars stuck all over my room.  
#### D  
Layla(happy): Twelve-year-old me would have <i>died</i> to learn about game streamers.  
Layla(surprise): 'You mean that's an actual job?!' I can hear it now.  
\***  
Sam(happy): Exactly. Well... We'd been best friends since kindergarten--  
Layla(happy): Yeah, I know. I was there.  
Narrator: Sam bumps his shoulder into yours, laughing.  
\>>  
Sam(happy): Are you going to let me tell you my sappy story or not?  
Layla(smile): Sorry... Go ahead.  
Narrator: There's a wistful expression on Sam's face as he remembers.  
Sam(smile): We'd been studying poetry in another class. All these sonnets about love.  
Sam(smile): I thought they were ridiculous. Feelings like that can't be real.  
\>  
Layla(happy): At twelve? Of course not.  
# (sld_07_26_B_DP3_love_poetry)  
## A. Girls have cooties.  
## B. Love poetry is a grand conspiracy.  
\***  
Sam(happy): Exactly. But...  
\*Stop Music  
\*Play Music m_gently_melancholy_deck_the_halls_01  
\>>  
Sam(smile): You were delivering your report and I couldn't stop watching you.  
Sam: It was like I suddenly, really <i>saw</i> you.  
Sam(shy): You were so happy, sharing what you loved with everyone. You were... shining.  
Layla(shy): Sam...  
Narrator: He ducks his head, running his thumb across your knuckles.  
Sam(shy): We were just kids then, but from that moment on, you were the only girl for me.  
\>  
Layla(shy): Wow...  
# (sld_07_26_B_DP4_be_the_only_girl)  
## A. That's incredibly sweet.  
## B. Do you still feel that way?  
#### A  
Layla(shy): I'm not even sure what to say to that...  
Narrator: Sam kisses the top of your hand, smiling shyly up at you.  
Sam(smile): You don't have to say anything. I just wanted you to know.  
#### B  
Narrator: Sam's voice is soft with emotion as he meets your eyes.  
Sam: Yes.  
\***  
Sam: I don't want to put pressure on you, or rush you, or ruin this in any way.  
\*Condition  
## A. (Condition: SAM_ROMANCE >= 1)  
## B. (Condition: KISSED_SAM >= 1)  
#### A  
Sam(smile): But I'm really looking forward to that date you promised me.  
### \*Goto prem_merm07_sam_date  
#### B  
Sam(shy): But I can't stop thinking about that kiss.  
Narrator: His gaze drops to your lips, his own parting at the memory.  
### \*Goto prem_merm07_sam_date  
\***  
Sam(smile): But I hope you'll give me a chance.  
# prem_merm07_sam_date  
\*Stop Music  
\*Play Music m_intense_sprightly_connection  
Layla(shy): Sam...  
# (sld_07_26_B_DP5_sam_romance)  
## A. Kiss me already. *Goto prem_merm07_sam_kiss  
## B. I'm looking forward to our date.  
## C. I'm not sure how I feel about you.  
#### B  
Sam(smile): I have everything planned out already, too. It's going to be perfect.  
Narrator: You poke him in the chest.  
Layla(surprise): Don't stress out about it! It doesn't have to be 'perfect.'  
Sam(happy): You're wrong, but okay.  
Layla(smile): Ugh.  
#### C  
\*SAM_ROMANCE -1  
Layla(sad): I'm not saying no or never, but you've been my friend for so long...  
Layla(sad): It's going to take me a minute to think of you differently.  
Sam(surprise): No, no... no pressure! I told you... Our friendship comes first.  
Sam(smile): I want you to want me back, but only if it's natural.  
Sam: Don't force yourself. Let's just have fun, okay?  
Layla(smile): Okay.  
\***  
Narrator: The two of you huddle together on the beach, falling into companionable silence as you listen to the waves.  
### \*Goto merm07_final_scene  
# prem_merm07_sam_kiss  
\*Gain SAM_ROMANCE  
\*Gain KISSED_SAM  
\>>  
Sam(smile): So bossy...  
Narrator: He smiles into the kiss, low laughter vibrating against your hands as you press against him.  
Narrator: When he finally parts his lips to kiss you deeply, it feels like you're seeing stars.  
Sam(smile): {Layla Name}...  
Narrator: Gently, carefully, he leans you back into the sand, bracing himself and leaning over you.  
Narrator: You twine your arms around him, kissing him, savoring the feel of him.  
Layla(shy): Mmm...  
# (sld_07_26_B_DP6_kiss_sam)  
## A. You've wanted this for years, huh?  
## B. Who taught you how to kiss like that?  
#### A  
Narrator: Sam presses his forehead against yours, his eyes still closed.  
\>>>  
Sam: I dreamed of kissing you every single night in high school.  
\>>  
Layla(smile): You could have kissed me at any time, you know.  
Sam(shy): That's... so much easier said than done.  
#### B  
\>>>  
Sam(surprise): There are some surprisingly helpful videos on the internet...  
Layla(happy): Wow, nevermind. Forget I asked.  
\***  
\>  
Narrator: You press your lips to his again, holding him close.  
\*Stop Music  
\*Play Music seawave  
Narrator: The two of you talk and kiss and hold each other, tangled in the sand, listening to the waves.  
\*Stop Music  
### \*Goto merm07_final_scene  
# merm07_final_scene  
\*Stop Music  
\*Play Music the_man  
\*  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_3_city_beach_house_day.jpg-story' width='60'>
\*Scene OUTSIDE_BEACH_HOUSE_DAY (Color: Black)
{% endhint %}  
\*Camera Right 0  
\*  
Narrator: Hours later, you return to the beach house, feeling a little better.  
Layla: Alright, deep breath... Maybe Maddie will be merciful and let me live...  
\*Condition  
## A. (Condition: DID_SAM_PREM_AFTER_FIGHT = 1)  
#### A  
Sam(smile): Don't worry... You know Maddie loves you. She'll come around.  
\***  
\*  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_city_beach_house_inside.jpg-story' width='60'>
\*Scene BEACH_HOUSE_INSIDE_DAY
{% endhint %}  
\*Camera Right 0  
\*  
Narrator: But when you step into the living room...  
Grandma(sad): We need to talk.  
\>>>  
Layla(surprise): Grandma?!  
# End  
