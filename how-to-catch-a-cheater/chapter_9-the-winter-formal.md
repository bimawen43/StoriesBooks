# Begin  
\*Play Music m_illusion1  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_city_fancy_restaurant.jpg-story' width='60'>
\*Scene INT_FANCY_RESTAURANT (Color: Black)
{% endhint %}  
Narrator: Matt follows your eyes to the woman, and then almost jumps out of his chair, as if he just saw a ghost.  
\>>>  
Matt(terror): No...  
\>  
Narrator: He flies up from the chair, and bolts out of the door, almost tackling a waiter on his way.  
\>>  
Rosie(surprise)*Shout: Matt!  
\>  
Narrator: Startled out of your mind by his reaction, you try to spot him and the woman from the window.  
Rosie(surprise)*Think: There's Matt... but where's the woman?  
Narrator: She's gone.  
Narrator: You see Matt scouting for her in the rain before he walks back inside, looking pale as a ghost.  
Rosie(sad): Matt...  
# (htcac_09_01_mysterious_woman)  
## A. Did you know that woman?  
## B. Are you okay?  
#### A  
\>>>  
Rosie(sad): Who was that woman? Did you know her?  
Matt(sad): I— I don't feel so good. I think I'm gonna go.  
Matt(sad): Please clear my schedule for the rest of the day, {Rosie Name}.  
#### B  
\>>>  
Rosie(sad): Are you okay? You look pale.  
Matt(sad): Actually, no, I don't feel so good right now. I think I'm gonna go.  
Matt(sad): Please clear my schedule for the rest of the day, {Rosie Name}.  
\***  
\>  
Narrator: You nod as Matt gets up, grabbing his stuff and quickly leaves the restaurant.  
Rosie(sad)*Think: That was so strange...  
\*  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_city_apartment_livingroom_night.jpg-story' width='60'>
\*Scene INT_ROSIES_APARTMENT_NIGHT (Color: Black)
{% endhint %}  
\*Camera Right 0  
\*  
\*Play Music m_blue_epilog_sadness  
\*Lou Outfit Lou_Red_shirt  
Narrator: Later that night, you invite Lou over to talk about what happened earlier.  
Rosie(sad): I'm telling you, Lou, I've never seen him look that... scared.  
Lou(confuse): That is weird. What did she look like?  
Rosie: I couldn't see her face; she was wearing a hoodie.  
Lou(sad): Creepy...  
Rosie(sad): Yup. I wish I knew why Matt reacted the way he did.  
\>>  
Lou(smile): You're too nosy for your own good, {Rosie Name}.  
\*Condition  
## A. (Condition: ADOPT_DOG >= 1)  
## B. (Condition: NO_DOG >= 1)  
#### A  
Lou(happy): Isn't that right, {Puppy Name}? Curiosity killed the puppy.  
\>  
Puppy(surprise): Nnn?!  
Lou(happy): I'm just kidding! Curiosity killed the cat.  
Puppy(happy): Waf!  
#### B  
Rosie(smile): I know, I know.  
\***  
\>>  
Lou: But, that said, I think I know someone who can help you dig up some information.  
Rosie(smile): Hmm...  
# (htcac_09_02_dig_up_something)  
## A. Let me guess... you?  
## B. Who is it?  
#### A  
Rosie(smile): Let me guess, it's you, right?  
Lou(happy): What? No, silly, my baby sister, Sheila.  
Rosie(shy): Oh...  
Lou(happy): Although, I think I would be pretty good at digging up information too.  
#### B  
Rosie(surprise): Really? Who?  
Lou(smile): My baby sister, Sheila.  
\***  
Rosie(smile): I've met Sheila a few times before. She's great!  
Lou: Yeah, and she's a journalist, she's been working in New York for quite a few years now.  
\>>>  
Lou(smile): She's <b>knows everything about everyone</b> who's worth knowing stuff about.  
Rosie(smile): Like Matt.  
Lou(smile): Exactly like Matt.  
\>>  
Lou(confuse): And if she doesn't already know who that girl could be, she can find out for sure.  
Rosie(sad): I don't know, Lou, it's not like I have to know.  
Lou(confuse): What are you talking about?  
Lou(smile): If she's an ex-girlfriend of his, and you could figure out who she is...  
Lou(smile): You could learn so much about what he's looking for in a woman.  
Rosie(confuse): Or what he's not looking for...  
Lou(happy): Exactly! I see pros only in this, and I'm sure Sheila would love to help you.  
Lou(smile): Would you like me to call her and ask her to come over?  
# htcac09_invite_sheila  
Rosie(smile)*Think: Should we invite Sheila over and do a little digging on the mysterious woman?  
# (htcac_09_03_invite_sheila)  
## A. Invite Sheila over. (Cost: 22 Diamond ID: plot_htcac_09_sheila)  
## B. Leave it be.  
#### A  
\*Gain INVITE_SHEILA_OVER_9  
Rosie(happy): I guess I was blessed with a nose like this for a reason. Please invite her over.  
Lou(happy): Alrighty.  
\>  
#### B  
\*Gain LEAVE_IT_BE_9  
Rosie(smile): No, it's really none of my business.  
Rosie(sad): You should've seen his face, Lou, it was pure pain. I don't want to make anything worse.  
\>  
Lou(smile): Okay, I understand, and I respect that. I should go and open the bar.  
Rosie(smile): Yes, and I should probably pack a bag for the weekend.  
Rosie(sad): Sigh...  
Lou(sad): What is it?  
Rosie(sad): I didn't have time to go look for a nice gown to wear to the Winter Formal.  
Lou(smile): But you aren't leaving until tomorrow at noon, right? You still got time then.  
Lou(happy): How about I stop by tomorrow before you leave, and we can go look for one. Sounds good?  
Rosie(happy): Sounds great! Thank you so much, Lou. You're the best.  
Lou(smile): Oh, honey, I know. I'll see you tomorrow.  
Narrator: You give Lou a tight hug before she leaves you to your packing.  
### \*Goto htcac09_merge_formal  
\***  
\*Sheila Name Sheila  
\*Sheila Outfit Sheila_Carry_Laptop  
Narrator: Lou walks into your living room to call her sister, and a short while later, Sheila arrives carrying her laptop.  
\*Camera Left 2  
Lou(smile): Hey, sis.  
Sheila(happy): Little Lou, how are you?  
Narrator: Sheila ruffles Lou's hair lovingly, and Lou sighs. She's almost a head taller than her big sister.  
\*Sheila Outfit Sheila_No_Laptop  
Rosie(happy): Sheila, thank you so much for coming.  
Sheila(smile): Of course, {Rosie Name}. If there's a story to get or to tell, I'll always be there.  
Sheila: When Lou told me what this was about, I already had an idea who the woman could be, but it's just a hunch.  
Rosie(smile): Well, let's go sit down in the living room, and get you and your laptop settled in.  
\*Camera Right 2  
Narrator: You all sit down on the couch, Sheila, with her laptop on her lap, already looking concentrated.  
\*Sheila Outfit Sheila_Carry_Laptop  
\>>  
Sheila: Alright, tell me what you remember about the woman.  
Rosie(sad): I honestly don't have much to go on at all other than she was wearing a black tracksuit.  
Rosie(sad): Her face was covered, and she was kind of far away.  
Rosie: All I know is that she's got a slim figure, small frame, and Matt seemed like he'd seen a ghost.  
Sheila(surprise): A ghost, you say? That's very interesting. Could it be...  
Narrator: Sheila types away on her keyboard. You and Lou observe her.  
Rosie*Think: I should ask Sheila if knows if...  
# (htcac_09_03_DP1_ask_sheila)  
## A. Matt lost someone close to him?  
## B. She could be an ex-girlfriend?  
#### A  
Rosie(confuse): Could it be someone Matt thought he lost?  
Sheila(smile): My thoughts exactly, {Rosie Name}.  
Sheila(confuse): And if I'm right about this, it could be a huge story!  
#### B  
Rosie(confuse): Could she be an ex-girlfriend or something?  
Sheila(smile): Hmm, the one I have in mind wasn't exactly his girlfriend, but there were speculations...  
Sheila: If I'm right about this, it could be a huge story!  
\***  
Lou(surprise): Who do you think she is then?  
Sheila(confuse): It's three years ago now, so you might not remember, especially not you {Rosie Name}.  
Sheila(smile): I mean, since you didn't move to New York until recently.  
Lou(confuse): Spit it out already, sis.  
\>>>  
Sheila(smile): Alright, alright. <b>Chrissy Moretz</b>.  
\>>  
Lou: Doesn't ring a bell.  
Rosie(confuse): Wait, it does for me... I just don't remember where I've seen that name before.  
Sheila: Well, she was <b>Matt's first assistant</b>. I think I can find a picture of her too.  
Narrator: Sheila turns her laptop to you and Lou, revealing a pretty dark-haired girl.  
Sheila: Does she look familiar to you?  
Rosie(confuse): I mean, her hight and her build could very well be who we saw.  
Lou: What happened to her, then?  
\*Play Music m_intense_classical_tension_boreal_01  
\>>>  
Sheila: See, that's where it gets interesting. She <b>disappeared</b>.  
Rosie(surprise): What do you mean?  
Sheila(sad): Matt reported that one day she didn't show up for work, and he couldn't reach her.  
Sheila: And then later that day already they had an idea what had happened.  
\>>  
Rosie(sad)*Think: I think she...  
# (htcac_09_03_DP2_first assistant)  
## A. Was killed.  
## B. Killed herself.  
#### A  
Rosie(sad): W-Was she killed?  
Sheila: No, but the police thought so at first...  
Sheila: ... When someone found some of her belongings down by the Hudson River.  
Sheila(sad): Like her shoes.  
Sheila: They even suspected Matt for some time...  
Rosie(surprise): No, really?!  
Sheila: Yeah, until they found what they described as a suicide letter in her apartment.  
#### B  
Rosie(sad): D-Did she commit suicide?  
Sheila(sad): That's what they think, yes, but not their first thought.  
Sheila: At first, they thought it was murder; they even suspected Matt.  
Rosie(surprise): What? Really?  
Sheila: Yeah. They found some of her belongings down by the Hudson River, like her shoes, and later...  
Sheila: They found a letter in her apartment.  
Lou(sad): A suicide letter?  
Sheila: That's what they ended up ruling it as.  
\***  
Sheila(sad): Since they never found her body, and she never showed up again.  
Rosie(sad): Well, with no proof of her death, she could be the one we saw.  
Lou: That could explain Matt's reaction too, right?  
Rosie: Right.  
Lou(confuse): So, are you going to ask him about her, {Rosie Name}?  
Rosie: Yes, I'll ask him...  
# (htcac_09_03_DP3_ask_matt)  
## A. Directly.  
## B. Subtly.  
#### A  
\*Gain ASK_MATT_DIRECTLY_9  
#### B  
\*Gain ASK_MATT_SUBTLY_9  
\***  
Rosie(smile): But the time needs to be right. I think that right now, he needs some space.  
Lou(smile): Good idea.  
Message: Good job | You uncovered some important information about Chrissy Moretz.  
Rosie(smile): Well, thank you for your help, Sheila. I really appreciate it.  
Sheila(happy): Anytime! Please let me know if you find out whether or not our theory turns out to be true.  
\>  
Rosie(sad)*Think: I couldn't let Sheila make a story about something that so visibly upset Matt.  
Rosie(sad): Sheila, I know you'd love a good story, and as much as I think you deserve it, I can't tell you.  
Rosie(sad): I know whoever Matt saw, really shook him to his core.  
Rosie: And whoever it was, they share a story that's difficult for Matt to remember.  
\*Sheila Outfit Sheila_No_Laptop  
Sheila(smile): You really care about him, don't you?  
Rosie(smile)*Think: What do I say?  
# (htcac_09_03_DP4_care_about_matt)  
## A. Yes, I care a lot about him.  
## B. No, I just need him to trust me.  
#### A  
\*Gain CARE_ABOUT_MATT_9  
Rosie(shy): I guess I do care a lot about him.  
Lou(happy): Aw!  
Sheila(smile): *Sigh* the things I do for love. Fine, I'll let you have this story to yourself, {Rosie Name}.  
#### B  
Rosie(smile): No, I just need him to trust me. I work very closely with him, after all.  
Rosie(smile): If he confides in me about it and then a story breaks about, he'll suspect me.  
Sheila(smile): I understand.  
\***  
Sheila(happy): But will you tell me? For personal use only? I'd just like to know if I'm right.  
Rosie(smile): Alright then, I owe you that much.  
\>  
Narrator: You drink another cup of coffee and chat bit before Sheila heads home again, leaving you and Lou alone once more.  
\*Play Music m_gently_classical_white_river_02  
\*Camera Left 3  
Rosie(smile): Thank you for your help tonight, Lou. I should probably start packing for the weekend.  
Lou(smile): Of course. Anytime.  
Rosie(sad): Sigh...  
Lou(sad): What is it?  
Rosie(sad): I didn't have time to go look for a nice gown to wear to the Winter Formal.  
Lou(smile): But you aren't leaving until tomorrow at noon, right? You still got time then.  
Lou(happy): How about I stop by tomorrow before you leave, and we can go look for one. Sounds good?  
Rosie(happy): Sounds great! Thank you so much, Lou. You're the best.  
Lou(smile): Oh, honey, I know. I'll see you tomorrow.  
Narrator: You give Lou a tight hug before she leaves you to your packing.  
# htcac09_merge_formal  
\*Play Music m_gently_romance_butterflies_love_01  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_city_toggery_boutique_shop.jpg-story' width='60'>
\*Scene INT_CLOTHING_STORE_DAY (Color: Black)
{% endhint %}  
Narrator: The next day, Lou stops by as promised, and you head to the mall to look for the perfect gown.  
Rosie(smile): So, how are you and Brisa doing?  
Lou: I don't really know, to be honest. I feel like we're moving very slow.  
Lou(sad): I'm kinda afraid that if we move any slower, we'll start going backward.  
Rosie*Think: I should encourage Lou to be...  
# (htcac_09_04_encourage_lou)  
## A. Patient.  
## B. Brave.  
## C. Insisting.  
#### A  
\*Gain LOU_PATIENT_9  
Rosie(smile): Well, as long as you're feeling you're moving forward, even if it's slow progress...  
Rosie(smile): Then I think all you can do is be patient.  
\*LOVE +1  
Lou(smile): You're right. This is probably the pace Brisa is comfortable with.  
Message: Good job | You gave Lou some good advice.  
#### B  
\*Gain LOU_BRAVE_9  
Rosie(smile): Honestly, I think Brisa is a bit scared.  
Rosie(smile): Maybe she needs you to be the brave one and take charge?  
\*LOVE +1  
Lou(smile): Maybe you're right.  
Message: Good job | You gave Lou some good advice.  
#### C  
\*Gain LOU_INSISTING_9  
Rosie(smile): Brisa probably has her reasons for going slow, or for holding back a little.  
Lou(sad): Yeah, but I don't know the reasons.  
Rosie(smile): Yet. You just need to be more insisting until then.  
Lou: Uhm... I'm not sure being insisting is the right way to go, but I guess I could give it a try.  
Message: Careful | You didn't give Lou the best advice.  
\***  
Lou(happy): Anyway, we're not here to talk about my love life, are we?  
Lou(surprise): Oh, look at that one!  
Narrator: Lou dart across the store and pulls out a beautiful ice blue dress.  
Lou(happy): If this dress doesn't scream snow queen, then I don't know what does.  
Rosie (surprise): Wow, it kind of reminds me of Elsa's transformation dress!  
Lou(happy): Exactly, what's not to love? This dress is going to make you the belle of the ball!  
Lou: Here, try it on!  
Narrator: Be the belle of the ball at the Winter Formal with this eye-catching gown!  
\*Rosie Outfit Record  
\*Role  
# (htcac_09_05_choose_gown)  
## A. Outfit Snow_Queen_Gown (Cost: 29 Diamond ID: look_htcac_09_snow_queen)  
## B. Outfit Blue_Belle_Dress  
\***  
\*Condition  
## A. (Condition: Rosie Outfit = Snow_Queen_Gown)  
## B. (Condition: Rosie Outfit = Blue_Belle_Dress)  
#### A  
\*Gain PERMIUM_OUTFIT_9  
Rosie(happy): How could I say no to looking like queen Elsa?  
Lou(happy): Right? Oh, my God, you look incredible, {Rosie Name}.  
Lou(confuse): You're not making it easy on poor Mr. Dalton, that's for sure.  
Rosie(happy): That's kind of the point.  
#### B  
Rosie(smile): I don't know, I think this other one is a bit more mature.  
Lou(smile): Okay, then, suit yourself.  
\***  
Rosie(smile): Alright, I guess I'm all settled then. It didn't take long, either.  
\*Condition:  
## A. (Condition: ADOPT_DOG >= 1)  
## B. (Condition: NO_DOG >= 1)  
#### A  
Narrator: The sales assistant neatly wraps up your dress and puts it in a bag for you.  
\*Rosie Outfit Reset  
Rosie(smile): I think we have time to go grab a coffee before I leave.  
Lou(smile): Okay, cool, but then we head back, right? I'm starting to need my puppy fix.  
Rosie(happy): Alright, and thanks for looking after him again, Lou.  
Lou(happy): No, thank you!  
#### B  
Narrator: The sales assistant neatly wraps up your dress and puts it in a bag for you.  
\*Rosie Outfit Reset  
Rosie(smile): Alright. I think we have time to go grab a coffee before I leave.  
Lou(happy): Sounds good.  
\***  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_city_inside_car_day.jpg-story' width='60'>
\*Scene INT_MATTS_CAR_DAY (Color: Black Time: 2.5)
{% endhint %}  
\*Play Music m_suspense_mystery_intense_just_us_league_01  
\>>R  
Matt(smile): {Rosie Name}.  
Rosie(smile): Hello, Matt.  
\*Condition  
## A. (Condition: INVITE_SHEILA_OVER_9 >= 1)  
## B. (Condition: INVITE_SHEILA_OVER_9 < 1)  
#### A  
Narrator: You feel slightly weird seeing him again after what Sheila told you about. About Matt being suspected of murder.  
Rosie(sad)*Think: It's probably best if I don't talk about it just yet.  
#### B  
Narrator: You feel slightly weird seeing him again after the incident at the restaurant.  
Rosie(sad)*Think: It's probably best if I don't talk about it just yet.  
\***  
Matt(smile): So, are you ready for tonight?  
Rosie: Uhm...  
# (htcac_09_06_ready_for_tonight)  
## A. Yeah.  
## B. Not really.  
#### A  
Rosie(smile): I don't really know what to expect, so I guess I'm as ready as I'll ever be.  
Matt(happy): Well, let me enlighten you then.  
#### B  
Rosie(sad): ...  
Matt: Nervous?  
Rosie(sad): Is it that obvious?  
Matt(smile): I'm sorry to tell you that you're as easy to read as an illustrated children's book.  
Rosie(sad): Great... It's just; I have no idea what to expect at all.  
Matt(smile): Let me enlighten you then.  
\***  
Matt(smile):  Let's see... You can expect lots of boring small talk, delicious, expensive food and wine-  
Matt(smile): And plenty of it. You can expect long anecdotes from Mr. Silverstein and...  
Rosie(smile): And?  
Matt(shy): Maybe someone will ask you to dance too?  
Narrator: Matt leans back into the comfortable leather seats, searching your face for a reaction.  
Rosie(shy): You think so? Do you think someone will ask me to dance?  
Matt(smile): Maybe. I'm just sharing my experience.  
Rosie(smile)*Think: I should...  
# (htcac_09_07_ask_you_dance)  
## A. Flirt with him.  
## B. Joke about it.  
#### A  
\*Gain FLIRT_DANCE_9  
Rosie(shy): Well, to be honest, you're the only one I'd like to dance with.  
Rosie: I mean, I know you could handle me being a klutz.  
\*Matt ROMANCE +1  
Matt(happy): I'm not too sure about that, but I would try. I wouldn't want you to embarrass me.  
Rosie(happy): Wow, that's so selfless of you, Mr. Dalton.  
Matt(happy): I know.  
#### B  
\*Gain JOKE_DANCE_9  
Rosie(happy): Well, whoever he is, I hope he brought his safety shoes then.  
Narrator: You say, tongue in cheek, making Matt laugh, and the corners of his eyes crinkle.  
Matt(smile): I'd take the chance.  
Narrator: Seriousness suffuses Matt's features, but you can still trace the hint of a smile on his lips.  
\***  
Rosie(smile): But Ashley probably wouldn't be too thrilled about seeing you dance with me.  
Matt(sad): Oh... right, Ashley. Listen, {Rosie Name}. There's something I've been meaning to tell you...  
Narrator: Matt starts, but he's interrupted by his phone ringing.  
Matt(sad): Uhm... excuse me, I have to get this.  
Rosie(sad)*Think: Was he about to tell me the truth about his relationship with Ashley? But why?  
\>R  
Narrator: You look out the window. The snow has finally reached the state of New York, and you silently watch it fall.  
Narrator: Matt's phone call is longer than expected, and he ends up talking right until you arrive at Mr. Silverstein's impressive mansion.  
\*Play Music m_gently_romance_butterflies_love_01  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_city_silverstein_manor_ext_dusk.jpg-story' width='60'>
\*Scene EXT_SILVERSTEIN_MANOR_DUSK (Color: Black Time: 2.5)
{% endhint %}  
Narrator: The chauffeur helps you out of the car, grabbing your bag for you.  
Rosie(surprise): Wow!  
# (htcac_09_08_arrive_the_manor)  
## A. Look at that house!  
## B. Look at all the snow!  
#### A  
Rosie(surprise): Will you look at that house!  
Narrator: Matt quirks an eyebrow at you, chuckling a bit as he walks around the car to stand next to you.  
\>>  
Rosie(smile): What?  
Matt(smile): Nothing. It's just your high-end real estate virginity is kind of refreshing.  
#### B  
Rosie(Surprise): Look how much snow has fallen here!  
Narrator: Matt quirks an eyebrow at you, chuckling a bit as he walks around the car to stand next to you.  
\>>  
Rosie(smile): What?  
Matt(smile): Nothing. It's just, you're standing in front of a huge mansion, yet you're more impressed by the snow.  
Rosie(happy): So?  
Matt(happy): Nothing, it's just refreshing, I guess.  
\***  
\>  
Matt(smile): Come on, let's go inside.  
Narrator: Matt gently puts a hand on the small of your back and leads you to the front door.  
\*  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_city_manor_bedroom_int_day.jpg-story' width='60'>
\*Scene INT_SILVERSTEIN_MANOR_BEDROOM_DAY (Color: Black)
{% endhint %}  
\*Camera Right 0  
\*  
\*Camera Left 2  
\*Camera Middle 1  
Narrator: You're escorted to your room by a staff member. It's huge and spacious.  
Rosie(happy)*Think: Wow, this is all for me? They could fit five beds in here!  
Rosie(smile)*Think: Alright, I've got some time to settle in before I need to get ready for the dinner.  
Narrator: You unpack your things, and putting your dress on.  
\*Condition  
## A. (Condition: PERMIUM_OUTFIT_9 >= 1)  
## B. (Condition: PERMIUM_OUTFIT_9 < 1)  
#### A  
\*Rosie Outfit Snow_Queen_Gown  
Rosie(happy)*Think: I'm glad I chose to wear this beautiful dress.  
Rosie(smile)*Think: It'll help me keep my nerves in check and give me a boost of confidence.  
Rosie*Think: Hmm, a nice hairstyle that fits this look would be the cherry on top!  
#### B  
\*Rosie Outfit Blue_Belle_Dress  
Rosie(smile)*Think: This dress is cute, but it's a little simple.  
Rosie(smile)*Think: A nice hairstyle would help glam up this look, for sure!  
\***  
\*Rosie Hair Waves_With_Hair_Clip (Tag: Record)  
Narrator: Do you want to finish your look with a stunning hairstyle that's fit for a snow queen?  
Rosie(happy): Soft waves with a sparkly hair clip.  
\*Model  
# (htcac_09_09_pay_hairstyle)  
## A. Keep hair as it is.  
## B. I like this! (Cost: 16 Diamond ID: look_htcac_09_hair)  
#### A  
\*Rosie Hair Reset  
Rosie(smile)*Think: Nah, I think I'm good.  
#### B  
\*Gain PREMIUM_HAIR_9  
Rosie(happy)*Think: Dang, I'm good. This hairstyle is pretty much perfection.  
\***  
Narrator: You apply the finishing touches, like makeup and perfume, before you put on your most trusted pair of heels and head out to the ballroom.  
\*  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_city_silverstein_manor_night.jpg-story' width='60'>
\*Scene INT_SILVERSTEIN_MANOR_NIGHT (Color: Black)
{% endhint %}  
\*Camera Left 0  
\*  
\*Camera Right 2  
\*Matt Outfit Matt_Fancy_Tuxedo  
\*Silverstein Outfit Silverstein_Evening_Dress  
\*Ashley Outfit Ashley_Silver_Dress  
\*Condition  
## A. (Condition: PERMIUM_OUTFIT_9 >= 1) *Goto htcac09_premium_entrance  
## B. (Condition: PERMIUM_OUTFIT_9 < 1) *Goto htcac09_no_premium_entrance  
\***  
# htcac09_premium_entrance  
Narrator: Two men dressed in suits open the large glass doors for you to enter the ballroom. You smile at them humbly.  
Narrator: Once inside, you realize you're at the top of a large marble staircase, looking over the dining room and the dance floor and all its guests.  
Narrator: And like when Cinderella entered the ball, everyone turns to take in your beauty.  
Rosie(surprise)*Think: Frigg, they're all looking at me.  
Narrator: Then, you hear heels echo behind you. You turn around and see Ashley's face.  
\*Play Music m_mystery_intense_tension_some_of_you  
Narrator: You see, she's wearing the dress from the charity gala. She gives you a not-so-subtle elevator look.  
Rosie(smile): Hello, Ms. Silverstein.  
Ashley(sad): Oh... I... didn't know you were coming.  
Narrator: Ashley looks down herself, straightening her dress insecurely. You recognize the dress. It's the same the wore on the night of the Charity Gala.  
Narrator: Ashley nibbles on her bottom lip, and clears her throat.  
\>>>  
Ashley(angry): Where did you get that dress? The thrift store?  
Narrator: Ashley tries to walk in front of you, undoubtedly knowing you'll be a tough act to follow.  
\>>  
Rosie*Think: Should I let Ashley walk in front of me or have her follow me?  
# (htcac_09_10_to_the_front)  
## A. Let Ashley go first.  
## B. Have her follow.  
#### A  
\*Play Music m_romance_sexy_city_bolereando_01  
\*Gain ASHLEY_FIRST_9  
Rosie*Think: Oh, what the heck. If it means so much to her.  
\>  
Narrator: You let Ashley walk down first. She looks kind of surprised to see you step aside, and also relieved.  
Ashley(confuse): Hm.  
Narrator: She fakes a smile and straightens her back, but she's not fooling anyone.  
Narrator: She tries her best to take up as much space on the stairs as she can, but it's as useless as Pluto trying to block the sun from shining.  
#### B  
\*Gain ASHLEY_FOLLOW_9  
Rosie(confuse)*Think: I don't think so, Ashley. Take a number.  
\>  
Narrator: You step in front of Ashley, claiming the stairs for yourself.  
Ashley(sad): ...  
\***  
Rosie(smile)*Think: I bet Ashley hopes I'll fall down the stairs and break my neck right now. I should...  
# (htcac_09_11_walk_stairs)  
## A. Smile, and look sweet.  
## B. Strut, and look sexy.  
#### A  
\*Gain ROSIE_SWEET_9  
Rosie(shy): ...  
Narrator: You decide to smile at everyone you get eye contact with as you slowly move down the stairs, and they sheepishly smile back, as if starstruck.  
Narrator: People crane their necks to get a good look at you, and that's when you catch Matt's eyes lingering on you.  
Narrator: He tries to keep the small-talk going with Mr. Silverstein, but his eyes can't help but give away where his attention lies.  
Message: Impact | You charmed everyone!  
#### B  
\*Gain ROSIE_SEXY_9  
\*Play Music m_romance_sexy_city_bolereando_01  
Rosie: ...  
Narrator: You decide to strut as you move down the stairs, whipping your hair out of your face.  
Narrator: People crane their necks to get a good look at you, and that's when you catch Matt's eyes lingering on you.  
Narrator: He tries to keep the small-talk going with Mr. Silverstein, but his eyes can't help but give away where his attention lies.  
Message: Impact | You captivated everyone!  
\***  
\*Camera Middle 1  
\*Condition  
## A. (Condition: ASHLEY_FIRST_9 >= 1)  
## B. (Condition: ASHLEY_FOLLOW_9 >= 1)  
#### A  
Narrator: You move across the floor to greet Mr. Silverstein and Matt, and naturally, Ashley, who's holding Matt's arm a little more tightly tonight.  
#### B  
Narrator: You move across the floor to greet Mr. Silverstein and Matt.  
Narrator: Ashley follows you, and the second she reaches Matt, she grabs hold of his arm possessively.  
\***  
Silverstein(happy): Ms. Winter, you look, as your last name suggests, like a frosty winter's morning.  
Silverstein: Stunning, absolutely stunning.  
Ashley(angry): Got a little too much to drink already, Daddy?  
Narrator: Ashley snarls before looking at you with nothing but disgust in her eyes, but Mr. Silverstein doesn't listen.  
Silverstein(smile): Are you sure it's not a princess and not an assistant you've got there, Mr. Dalton?  
### \*Goto htcac09_merge_premium_outfit  
# htcac09_no_premium_entrance  
Narrator: Two men dressed in suits open the large glass doors for you to enter the ballroom. You smile at them humbly.  
Narrator: Once inside, you realize you're at the top of a large marble staircase, looking over the dining room and the dance floor and all its guests.  
Narrator: And like when Cinderella entered the ball, everyone turns to look at who's coming down the stairs next.  
Rosie(surprise)*Think: Frigg, they're all looking at me.  
Narrator: You move your way down the stairs quickly, slightly uncomfortable having all these eyes follow you.  
Narrator: You move across the floor to greet Mr. Silverstein and Matt, and naturally, Ashley, who's holding Matt's arm.  
\*Condition  
## A. (Condition: PREMIUM_HAIR_9 >= 1)  
## B. (Condition: PREMIUM_HAIR_9 < 1)  
#### A  
Silverstein(happy): Ms. Winter, good to see you, you look lovely tonight.  
Narrator: Mr. Silverstein gestures to the sparkling hair clip in your hair, and Ashley crinkles her pointy nose.  
Ashley(confuse): Got a little too much to drink already, Daddy?  
#### B  
Silverstein(happy): Ms. Winter, good to see you. What a nice dress you're wearing.  
Ashley(confuse): Got a little too much to drink already, Daddy?  
\***  
Narrator: Ashley snarls before looking at you with nothing but disgust in her eyes, but Mr. Silverstein doesn't listen.  
Silverstein(smile): You're a natural beauty, you don't need a fancy gown, does she, Mr. Dalton?  
# htcac09_merge_premium_outfit  
Narrator: It's obvious to you that Mr. Silverstein is trying to test Matt himself.  
Ashley(angry): Ahem!  
Narrator: But fortunately, Ashley interrupts him for attention.  
Silverstein(smile): Yes, yes, you too, my little hummingbird.  
Narrator: But it's not enough.  
\>>  
Silverstein(smile): How do you manage to work when an enchantress like her is around?  
Rosie(sad)*Think: Oh, be quiet, you fool!  
Matt(sad): Uh...  
\>  
Message: Get Ready | Timed choice coming up!  
Rosie(confuse)*Think: I need to take control of this conversation quickly before he makes Matt suspicious!  
Rosie(confuse)*Think: I need to talk about...  
\*Time 7 (Default: A)  
# (htcac_09_12_TC_control_conversation)  
## A. The... The... The.  
## B. The weather.  
## C. The mansion.  
#### A  
\*Gain TIME_FAIL_9  
Rosie(sad)*Think: Oh, my God, I'm completely blank! Think, {Rosie Name}!  
Narrator: But nothing comes to mind. Matt looks at you, and for a moment, it's as if he knows everything.  
Message: Be careful | Matt is now suspicious and highly uncomfortable.  
\>>>  
Matt(angry): Ms. Winter is a beautiful woman, Mr. Silverstein, <i>no doubt about that</i>.  
Matt: But I'm always professional.  
\>  
Narrator: Matt is visibly very uncomfortable, and to your dismay, you notice him pulling Ashley closer...  
Narrator: ... As if he feels the need to prove he's standing by his end of the deal, that he's loyal.  
Silverstein(sad): Hm. I should probably invite everyone to take a seat. The food will be ready shortly.  
Narrator: Mr. Silverstein glances skeptically at Matt one last time before he leaves you.  
Rosie(sad)*Think: Oh, crap. Now Matt's probably not going to relax around me all night...  
#### B  
\*Gain TIME_WIN_9  
Rosie(happy): Can you believe the weather? How perfect is it that it started snowing today?  
Rosie: Just in time to make your Winter Formal even more festive, huh, Mr. Silverstein?  
Silverstein(smile): What? Oh, yes, yes.  
Silverstein: That reminds me, I should probably invite everyone to take a seat. The food will be ready shortly.  
Narrator: Mr. Silverstein smiles at you all before he leaves.  
Message: Good job | You took control of the conversation.  
Rosie(smile)*Think: Phew. That was close, but I think that did the trick.  
#### C  
\*Gain TIME_WIN_9  
Rosie(happy): It's such a beautiful house you've got, Mr. Silverstein. I've never seen anything like it before.  
Rosie(smile): Did you have it renovated, or was it like this when you bought it?  
Silverstein(smile): What? Oh, I had it renovated. Everything is new.  
Rosie(smile): You've got great taste. And the table decorations are beautiful.  
Silverstein(smile): Thank you.  
Silverstein: That reminds me, I should probably invite everyone to take a seat. The food will be ready shortly.  
Narrator: Mr. Silverstein smiles at you all before he leaves.  
Message: Good job | You took control of the conversation.  
Rosie(smile)*Think: Phew. That was close, but I think that did the trick.  
\***  
Narrator: Mr. Silverstein walks to the first plateau on the staircase and clears his throat loudly.  
Silverstein(happy): Please move to the dining hall and take a seat. The entre will be served shortly.  
\*Camera Left 1.5  
Narrator: Everyone does as he says. You see Matt sit down next to Mr. Silverstein, and then a couple sits down apposite Matt and Mr. Silverstein.  
Narrator: You and Ashley share a look as you both realize...  
\>>  
Rosie(surprise)*Think: There's only one spot left next to Matt!  
# (htcac_09_13_only_one_spot)  
## A. Do what it takes to get it!  
## B. Let Ashley have it.  
#### A  
\*Gain STEAL_SEAT_9  
Rosie(angry)*Think: Since there are no place cards, this seat might as well be mine.  
Narrator: Ashley grabs the chair next to Matt and pulls it out.  
Rosie(happy): Why thank you, Ashley!  
Ashley(surprise): Hey!  
Narrator: You sit down in the chair. Neither Matt nor Mr. Silverstein saw anything. You're safe.  
Ashley(angry): Hell no! That's {*Attention MY} seat!  
\>>R  
Rosie: I'm sorry, I don't see your name anywhere?  
\>R  
Ashley(angry): Daddy! She took my seat!  
Silverstein(sad): ...  
Narrator: Mr. Silverstein looks at you, and you fear he'll tell you to get up from the chair and leave it to Ashley. That would be so embarrassing.  
Narrator: But then he smiles at you. You just proved to him you're willing to play dirty.  
Silverstein(smile): Ashley, these are our guests.  
Silverstein: Be a good hostess and take the seat next to Ms. Winter instead.  
Silverstein: After all, she doesn't know anyone but Mr. Dalton. You do.  
Narrator: Ashley's expression hardened. She crossed her arms, and her lips drew back in a snarl.  
Ashley(angry): Fine.  
\>  
Rosie(smile)*Think: Not my proudest move, but Mr. Silverstein told me to do what I have to do to sleep with Matt.  
\*Matt ROMANCE +1  
Matt(smile): ...  
Narrator: The dinner is nice, and the food is amazing, but most importantly, you feel you share a lot of meaningful conversations with Matt...  
Narrator: ... Thanks to your seat next to him.  
#### B  
\*Gain GIVE_SEAT_9  
\>>R  
Rosie(smile)*Think: I should probably give Ashley this seat. After all, she can't suspect I'm after Matt.  
Narrator: You step aside, letting Ashley claim the seat, and she does, like a hawk catching a mouse.  
Narrator: You sit down next to her. It's easy to tell she's not interested in talking to you, as she turns her chair away from you to face Matt.  
Rosie(sad)*Think: Matt's really the only person I can talk to, but she's blocking me from doing so.  
Rosie*Think: I guess it'll be a quiet dinner for me.  
Narrator: And just as predicted, you barely get to say a word to Matt throughout the entire dinner.  
\>R  
\***  
\*Camera Right 2  
Narrator: After the dinner, people slowly move toward the dancefloor.  
Ashley(happy): Come on, Matthew, dance with me!  
\>>  
Rosie(sad)*Think: God, I feel so misplaced here. I think I need a bit of a break.  
\>  
Narrator: You decide to walk to your room. Matt spots you leaving.  
Matt: Not right now, Ashley. Excuse me for a moment.  
\*  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_city_manor_bedroom_int_night.jpg-story' width='60'>
\*Scene INT_SILVERSTEIN_MANOR_BEDROOM_NIGHT (Color: Black Time: 2.5)
{% endhint %}  
\*Camera Left 0  
\*  
\*Play Music m_gently_melancholy_rage_one_step_closer_02  
Rosie(smile)*Think: That was better. No need to pretend to fit in here.  
Narrator: You hear knocking on your door.  
Rosie(surprise): Oh?  
Narrator: You open the door and are immediately met by Matt's dark brown eyes, trying to read your face.  
\>>  
Rosie(smile): I suppose you saw me leaving?  
Matt(smile): Yeah. I just wanted to check if everything is okay? Can I come in?  
Rosie(shy): Sure. Come in.  
\>  
Narrator: You step aside, and Matt strolls inside, looking around your room.  
Matt(sad): So? Are you okay?  
Rosie*Think: How do I reply?  
# (htcac_09_14_matts_care)  
## A. No, I don't fit in.  
## B. Yes, it's all just new to me.  
#### A  
Rosie(sad): Honestly, no. I don't fit in here. I feel like such an outsider.  
Matt(smile): And so what if you don't fit in? You don't have to. It was never part of the job description.  
Rosie(shy): Right...  
Matt(shy): And, to be honest, you're kind of the only person in this house I can stand right now.  
#### B  
Rosie(smile): I guess. It's all just very new to me. I feel a bit overwhelmed.  
Matt(smile): Understandable, but you're not heading to bed already, are you?  
Matt(shy): Because you're kind of the only person in this house, I can stand right now.  
\***  
Rosie(confuse): Really? And what about Ashley?  
Matt(sad): Of course, I can stand Ashley and Mr. Silverstein, but all they talk about are... superficial things.  
Matt: Conversations with them are just dull and empty. It's not like that with you.  
Rosie(shy)*Think: Aw...  
Narrator: Matt takes a step closer to you, lifting his hands.  
\>>  
Matt: {Rosie Name}, there's something I want to tell you.  
\*Condition  
## A. (Condition: TIME_FAIL_9 >= 1)  
#### A  
Matt(confuse): And I know I said I'm always professional earlier, but I just have to be personal right now.  
\***  
Matt: The more I get to know you, the more I feel the need to be <b>completely honest</b> with you.  
Rosie(surprise)*Think: Is this it? Is he finally going to tell me about his deal with Mr. Silverstein?  
Narrator: Matt sighs, then lifts his chin.  
Matt(sad): I'm not marrying Ashley out of love. I made a deal with Mr. Silverstein.  
Matt: He's promised to make me CEO of Silverstein Corp. if I marry Ashley.  
Rosie(sad): Matt...  
Matt(sad): I know what you're thinking...  
Matt(sad): <i>"What kind of man would throw away his personal life, the chance of finding true love for a job?"</i>  
Rosie(sad): Well, kinda, but in a less judgemental way. I just wonder why it's necessary?  
Rosie: I mean, you're COO, aren't you naturally "next in line"?  
Matt(sad): I don't know. I would think so, but when Mr. Silverstein made me the offer...  
\>>>  
Matt: He made sure to let me know that <b>he's considering other guys</b> in Silverstein Corp.  
\>>  
Matt(sad): Some have more experience than me; others have better contacts or are closer to Mr. Silverstein.  
Rosie(angry): So, he basically told you marrying Ashley is the only way you'd be offered this position?  
Matt(sad): I guess he did.  
Rosie(sad): That's...  
# (htcac_09_15_matt_tell_the_ture)  
## A. Clever.  
## B. Manipulative.  
#### A  
Rosie(confuse): Clever, unfair, but still a clever way to get Ashley what she wants, too, that spoiled brat.  
#### B  
Rosie(confuse): Manipulative as hell. He'll give Ashley whatever she wants, that spoiled brat.  
\***  
Matt(confuse): It is. And Mr. Silverstein knows how much I want it. How hard I've worked.  
Matt(sad): It would kill me to see him give the position to someone else when I'm the COO. It should be me.  
Matt(sad): So, I took the deal.  
\>>>  
Rosie(sad): W-Why did you feel the need to tell me this, Matt?  
\>>  
Matt(sad): Because there's more.  
Matt(sad): Mr. Silverstein had me promise to prove myself worthy of Silverstein Corp. and Ashley.  
Matt: He's basically told me to stop partying and stop dating, but...  
Rosie(sad): Yes...?  
\>>>  
Matt(sad): But then <b>I met you</b>.  
Matt: The day I made a deal with him was the night I met you. That's why I was at "Lou's Bar" and drinking.  
\>>  
Matt(sad): I was kind of "mourning" the death of my love life. It sounds stupid, but it is what it is.  
Rosie(surprise)*Think: I can't believe he's admitting to all of this, being so vulnerable with me.  
Rosie(sad)*Think: Is he going to admit he's got feelings for me too?  
Rosie(sad): It doesn't sound stupid at all. I would've done the same.  
Rosie(sad)*Think: I was actually doing the same thing, mourning the death of love and my expectations of it.  
Matt(sad): The reason I'm telling you this is because you're somehow <b>making me second guess this deal</b>.  
Rosie(smile): How?  
Matt(smile): Well, you've been reminding me that there are other things to life than work.  
\>  
Narrator: You can hear the music playing downstairs. It's a nice, slow song.  
Narrator: Matt takes yet another step closer to you, extending his hand...  
Matt(smile): You've been reminding me to have a little fun sometimes...  
Rosie(happy): Are you asking me to dance, Mr. Dalton?  
Matt(smile): Yes, I believe I kinda promised you one. What do you say? Wanna live a little, Ms. Winter?  
Rosie(smile)*Think: How do I respond to his invitation?  
# (htcac_09_16_dance_invite)  
## A. Just take his hand.  
## B. Absolutely.  
## C. Hesitate.  
#### A  
Rosie(shy): ...  
Narrator: You give him a tender smile as you place your hand in his.  
#### B  
Rosie(happy): I'd love to, Mr. Dalton.  
#### C  
Narrator: You hesitate for a moment.  
Matt(happy): I'm finally trying to have some fun, and now you're considering rejecting me?  
Rosie(happy): No, no... It's just... I mean, I'm just surprised. That's all.  
Narrator: You finally put your hand in his, and he closes it gently.  
\***  
Narrator: He pulls you closer, putting his other hand softly on the small of your back.  
Narrator: You put your hand on his shoulder. The fabric of his suit feels soft on your skin.  
Narrator: His cologne tingles your senses, and as you feel him looking down at you...  
Narrator: ... The hairs on the back of your neck stand up like flowers in the morning sun.  
\*Camera Middle 2  
Narrator: He leads you around the room until you're standing in front of the lit fireplace.  
Narrator: Its glow illuminates Matt's features, his sharp cheekbones casting shadows on his face.  
Narrator: You feel breathless as you sense his lips moving closer to yours.  
Narrator: His eyes shift from your eyes to your lips as if he's accessing whether or not you want this.  
\>>  
Rosie(surprise)*Think: Is he really going to kiss me?  
# End  
