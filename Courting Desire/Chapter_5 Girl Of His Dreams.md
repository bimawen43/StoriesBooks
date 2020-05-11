# Begin  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_medieval_fancy_dressing_room.jpg-story' width='60'>
\*Scene COURTING_DESIRE_INTRO
{% endhint %}  
Narrator: Chapter Five | <color=olive>Girl Of His Dreams</color>  
\*Play Music m_intense_romance_acoustic_symphony_01  
# cd05_explanation  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_medieval_fancy_sitting_room.jpg-story' width='60'>
\*Scene FANCY_17TH_SITTINGROOM (Color: Black)
{% endhint %}  
Narrator: You are all gathered in the salon in the Royal Palace, where Philippe has just unveiled a painting...  
Narrator: Of a girl that looks exactly like you!  
Armand(sad): So the reason you painted this is because...  
Philippe: I wanted to find her.  
Narrator: Everybody turns to look at you.  
Alice(surprise): How?  
Philippe: By painting her likeness, and then having several footmen out looking for her.  
Narrator: He shrugs lightly, as if embarrassed by having said that.  
\>>  
Alice(smile): Oh! Like Prince Charming looking for Cinderella using the glass slipper!  
Philippe(surprise): I beg your pardon?  
Alice: Umm, never mind.  
Alice: So... I don't suppose you've had any luck finding this... dream girl?  
Narrator: Philippe stares at you thoughtfully.  
Philippe: Not until today.  
Narrator: Philippe looks like he has more to say... but he suddenly seems to catch himself.  
\*Condition  
## A. (Condition: ANNE_STAYS >= 1)  
#### A  
Narrator: He glances at Anne, and suddenly it's as if he realizes that he has spoken too much.  
\***  
\*Play Music m_gently_lifting_dreams_02  
Narrator: Philippe draws himself up, and suddenly, is all easy charm again.  
Philippe: I'm sorry. Perhaps I should not have told you all about this.  
Narrator: He turns and smiles ruefully at you.  
Philippe(smile): It's just that... I was so shocked when I recognized you.  
Armand(sad): It is rather shocking, yes.  
Philippe(smile): Besides, I should know better than to impose this ugly painting upon your eyes.  
Narrator: He shrugs, embarrassed.  
Philippe: I am no artist, excuse me.  
\*Condition  
## A. (Condition: ANNE_STAYS >= 1)  
#### A  
Narrator: Anne simpers.  
Anne(smile): It's a work of art, Philippe! Such masterful strokes, and the colors!  
\***  
Narrator: You look at the painting again.  
Narrator: It is pretty, and well painted enough, such that he managed to capture your features...  
Narrator: But it's true that it's far from being a masterpiece.  
\*Condition  
## A. (Condition: INSIDE_INFO >= 1)  
#### A  
Alice*Think: Jeanne said that Philippe can't stand people who suck up to him...  
Alice*Think: And that I shouldn't be afraid to state my opinions.  
\***  
Alice: I think...  
# (cd_05_01_opinions_of_the_painting)  
## A. It's exquisite, perfectly painted!  
## B. It's the most beautiful art I've ever seen!  
## C. It's not professional, but it's pretty. (Condition: INSIDE_INFO >= 1)  
#### A  
Narrator: Philippe stares at you with a sceptical look.  
\>>  
Philippe: Right...  
### \*Goto cd05_philippe_reflect  
#### B  
Narrator: Philippe lifts an eyebrow.  
\>>  
Philippe: You must not have seen a lot of art, then.  
### \*Goto cd05_philippe_reflect  
#### C  
### \*Goto cd05_annestays02  
\***  
# cd05_annestays02  
\*Condition  
## A. (Condition: ANNE_STAYS >= 1)  
#### A  
Narrator: Anne gasps in shock at your audacity.  
\***  
Narrator: Philippe bursts out in laughter, and grins.  
\*Philippe Romance +1  
Philippe(smile): Not many people dare to truly speak their minds to me.  
Philippe(smile): It's refreshing to find someone who does.  
Message: Not A Suck Up | Philippe appreciates your honesty!  
Alice*Think(happy): I made a good impression on Philippe thanks to Jeanne's advice!  
# cd05_philippe_reflect  
Philippe: Lady {Alice Name}... would you like to keep this humble painting?  
\*Condition  
## A. (Condition: ANNE_STAYS >= 1)  
#### A  
Anne(angry): What??  
\***  
Alice(surprise): Huh? You mean, you want to give it to me?  
Philippe(smile): Yes. That is, if you want it.  
Narrator: Tutorial | Accepting the painting from the Prince will increase <color=purple>Romance</color> with him, as well as raise Court Opinion of you!  
Alice(smile): I...  
# (cd_05_02_accepted_the_painting)  
## A. Would be honored to accept it! (Cost: 18 Diamond ID: item_cd_05_Philippe_painting)  
## B. Couldn't possibly accept such a gift.  
#### A  
\*Gain PHILIPPE_PAINTING  
Message: Prestigious Present | You accepted the painting from Philippe!  
\*Court +1  
Alice(shy): Thank you so much, your Highness.  
\*Philippe Romance +1  
Philippe(smile): It's my pleasure to give it to you.  
Narrator: Tutorial | You have raised your standing in Court!  
Narrator: Philippe rings for the footmen.  
\*Philippe Opinion +1  
Philippe: Please have the portrait wrapped up for Lady {Alice Name}.  
#### B  
Message: Prestigious Present | You chose not to accept the painting from Philippe.  
Alice: It must have taken you hours to paint this. I couldn't take it away from you.  
Narrator: Philippe stares at you some more, before suddenly turning away.  
Philippe: Please excuse me... I need to gather my thoughts.  
Narrator: He bends and picks up the cloth that was covering the painting, and deftly covers it back again in one swift motion.  
Narrator: Then he walks over to the mantelpiece and picks up a bell, and rings it.  
Narrator: The two footmen who carried the painting and easel come back into the room.  
Philippe: Please bring it back to my study.  
\***  
Narrator: The two footmen bow, and set about removing the painting and easel.  
Narrator: Philippe turns on his heels and starts to walk towards the door as well.  
Alice*Think(surprise): He's leaving??  
Armand(surprise): Where are you going?  
Philippe: I'm just heading outside for some fresh air.  
Philippe(sad): I need to... think about things.  
Philippe: I'll meet you in Louis' chamber in half an hour.  
Philippe: I'll send word right now so that Louis and Therese know to expect us.  
Armand: Alright, see you there.  
Narrator: Philippe strides out of the salon.  
\*Condition  
## A. (Condition: ANNE_STAYS >= 1)  
#### A  
Alice*Think: Maybe it was details that he was uncomfortable sharing with Anne in the room...  
\***  
\*Play Music m_gently_classical_white_river_01  
Alice*Think: I wonder if I follow him... will he tell me, if it's just the two of us?  
Narrator: Tutorial | Following Philippe will let you spend some alone time with him and increase his <color=purple>Relationship</color> with you, as well as learn more about the painting!  
Alice*Think: Should I follow Philippe?  
# (cd_05_05_follow_philippe)  
## A. Follow Philippe! (Cost: 21 Diamond ID: plot_cd_05_philippe)  
## B. Just stay in the salon.  
#### A  
\*Gain KNOW_DREAM  
### \*Goto cd05_premiumphilippe  
#### B  
\*Gain STAY_PUT  
### \*Goto cd05_askarmand  
\***  
# cd05_premiumphilippe  
\*Play Music m_intense_classical_tension_rage_bellissimo_02  
Message: Alone Time | You chose to go after Philippe!  
Alice*Think: A prince painted a portrait of me...  
Alice*Think: There's no way I'm letting this go without finding out more about it!  
Alice: Armand...  
Armand: You need to go ask him about it.  
Alice(surprise): Yes, how did you-  
Armand(smile): I would be surprised if you didn't feel curious.  
Armand: Go on, I'll see you at the King's chamber later.  
Alice(smile): Yes, see you there.  
Narrator: You pick up your skirt, and walk hurriedly out of the salon as well.  
\*Condition  
## A. (Condition: ANNE_STAYS >= 1)  
#### A  
Narrator: As you're leaving, you hear Anne's petulant voice complaining...  
\>>  
Anne(angry): Now she's got Philippe painting her as well??  
Anne(angry): Is she a witch??  
Armand(angry): Anne, please guard your tongue.  
\***  
\*  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_medieval_palace_garden_fountain_day.jpg-story' width='60'>
\*Scene PALACE_GARDEN_FOUNTAIN_DAY (Color: Black Time: 0.5)
{% endhint %}  
\*Camera Left 0  
\*  
Narrator: You pick up your pace once you leave the salon...  
Narrator: And catch up with Philippe just as he is stepping into the grounds of the royal garden.  
Alice*Think: Huff... huff... This dress isn't easy to run in!  
\*Camera Right 2  
Narrator: Hearing your footsteps, Philippe stops and turns around in surprise.  
\>>  
Philippe(surprise): Are you chasing after me?  
Narrator: You stop running, and take a few seconds to catch your breath.  
Alice(shy): Yes, I am.  
\>  
Narrator: Philippe takes in your flushed, dishevelled appearance, breaks into a grin, and bows.  
\*Philippe Romance +1  
Philippe(smile): Well then, how may I help you?  
Alice*Think: I can really see why so many women are crazy about him...  
Alice*Think: I bet flirting comes easily to him.  
Narrator: You walk up to him, trying not to blush.  
\>>  
Alice: Won't you tell me more about it? The painting?  
Philippe: You really want to know?  
Alice: Of course I do!  
Narrator: Philippe sighs.  
Philippe: I dreamed of you. Or someone who looks like you.  
Alice: Okay, now I really need to know more.  
Alice: Just exactly what happens in these dreams?  
Philippe: They are usually more or less the same...  
Philippe: I'm riding my horse in the woods, at night, for some reason...  
Philippe: When I come upon a maiden in a clearing, illuminated by the moonlight.  
Philippe: She's strangely dressed, her clothes in a strange style that I have never seen before...  
Alice*Think(surprise): !!!  
\*Play Music m_blue_epilog_sadness  
Philippe: I try to catch you, but you always stay just out of reach.  
Alice(surprise): "Catch" me? Why are you trying to catch me?  
Narrator: Philippe breaks into a wicked grin, and your heart skips a beat.  
\>>>  
Philippe(smile): Why do you think?  
Alice(shy): <i>Oh.</i>  
Philippe: I ask you who you are, and where you're from.  
Philippe(sad): Then, you start drifting away.  
Philippe(sad): I beg you to stop, and answer me, but you never do.  
Alice: Oh. Well, I, er... apologize.  
\>>  
Narrator: Philippe bursts into laughter.  
\*Philippe Romance +1  
Philippe: You're so different from any girl I've ever met.  
Alice: I've been getting that a lot recently.  
Philippe: Really? So tell me...  
Philippe: Who ARE you? And where are you from?  
\*Condition  
## A. (Condition: INSIDE_INFO >= 1)  
#### A  
Alice*Think: Jeanne said that I should be <b>mysterious</b> and hard to get...  
\***  
Alice: ...  
# (cd_05_05_DP2_status)  
## A. Insist you're just a normal girl.  
## B. Change the subject.  
## C. Give a mysterious reply. (Condition: INSIDE_INFO >= 1)  
#### A  
\>  
Alice: I'm just plain old {Alice Name}, that's all.  
Narrator: Philippe stares at you, then shrugs.  
Philippe: Perhaps I'm over thinking this.  
Philippe: Anyway, we should be heading back.  
\*Camera Left 1  
Narrator: He starts striding back towards the palace, and you follow him as he leads the way to the King's chamber.  
#### B  
\>  
Alice: I think it's been half an hour, hasn't it?  
Alice: His Majesty must be waiting for us.  
Philippe: You're right. We should be heading back.  
\*Camera Left 1  
Narrator: He starts striding back towards the palace, and you follow him as he leads the way to the King's chamber.  
#### C  
\>  
Alice: It's really complicated...  
Alice: And you probably won't believe me anyway.  
\*Camera Left 1  
Narrator: You spin around and start to walk off.  
Narrator: Behind you, you hear Philippe laugh incredulously, before he catches up with you and walks beside you.  
Message: Mysterious Girl | You pique Philippe's curiosity!  
\>>  
\*Philippe Romance +1  
Philippe(smile): You're not failing to disappoint at all.  
Narrator: He leans in slightly and whispers in your ear.  
\>>>>  
Philippe(smile): And I <b><i>will</i></b> catch you.  
Alice(shy): We'll see about that.  
\***  
### \*Goto cd05_kingchamber  
# cd05_askarmand  
\*Play Music m_blue_epilog_sadness  
\>  
Alice*Think(sad): I'll just stay here with Armand.  
Alice*Think: Maybe Armand knows something more about this painting?  
Narrator: You turn to Armand, who was already looking at you.  
\>>  
Alice: Armand...  
Armand: I don't know anything about this painting, Philippe hasn't mentioned it before today.  
Narrator: Armand has a strange expression on his face, which you can't decipher.  
Alice*Think: I really do think he may be jealous.  
### \*Goto cd05_annespeaks (Condition: ANNE_STAYS >= 1)  
### \*Goto cd05_leaveroom (Condition: ANNE_STAYS = 0)  
# cd05_annespeaks  
Anne: I wouldn't think too much of it, if I were you.  
Alice*Think: And... of course Anne has to give her two cents as well.  
Anne: There's probably some perfectly good reason for it.  
Alice: Yeah?  
# (cd_05_06_CP_annes_opinion)  
## A. Like what?  
## B. Pity I'm not interested to hear your theories.  
#### A  
Narrator: The girl shrugged.  
Anne: Maybe you're a witch and you've cast an evil spell on him.  
Narrator: You can't help but roll your eyes...  
Narrator: However, you notice Armand immediately stiffens up.  
\>>>  
Armand(angry): Anne, please be careful and think before you throw around accusations like that.  
Armand(angry): You know that accusing someone of witchcraft is an extremely serious matter.  
Anne(angry): I'm just saying.  
#### B  
Narrator: You yawn purposely.  
\***  
Narrator: The girl closes her mouth and glares at you.  
Anne(angry): Anyway, don't get all cocky just because of some painting.  
Narrator: She flounces out of the salon.  
\>>  
Alice(sad): I REALLY should have taken you up on your offer to get rid of her for today, shouldn't I?  
Narrator: Armand sighs and smiles at you.  
Armand: Don't think about her anymore.  
Armand: Come on, it's time for us to visit the King and Queen.  
Narrator: You both stand up, and Armand offers his arm to you once again.  
Armand: Ready?  
Alice: Ready.  
### \*Goto cd05_kingchamber  
# cd05_leaveroom  
Armand: Come on, it's time for us to visit the King and Queen.  
Narrator: You both stand up, and Armand offers his arm to you once again.  
Armand: Ready?  
Alice: Ready.  
### \*Goto cd05_kingchamber  
# cd05_kingchamber  
\*  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_medieval_king_antechamber_day.jpg-story' width='60'>
\*Scene KING_ANTECHAMBER (Color: Black)
{% endhint %}  
\*Camera Left 0  
\*  
\*Camera Right 4  
### \*Goto cd05_enterwithphilippe (Condition: KNOW_DREAM >= 1)  
### \*Goto cd05_enterwitharmand (Condition: KNOW_DREAM = 0)  
# cd05_enterwithphilippe  
\*Play Music m_romance_beauty_love  
Narrator: You enter the King's antechamber with Philippe leading the way.  
Narrator: Armand and Anne are already standing in one corner of the room, waiting.  
\*Condition  
## A. (Condition: ANNE_GOAWAY >= 1)  
#### A  
Narrator: Anne looks agitated.  
\>>  
Anne(sad): I searched <b><i>everywhere</i></b>. Are you <i>sure</i> you left this letter in the palace?  
Armand: Huh, maybe I have it somewhere at the Hotel after all.  
Armand: But I appreciate all your effort to help me find it.  
Anne(sad): You'd better.  
\***  
Narrator: Philippe walks over to Armand, and they start conferring in hushed, serious voices.  
### \*Goto cd05_seeguard  
# cd05_enterwitharmand  
Narrator: You enter the King's antechamber with Armand leading the way.  
Narrator: Philippe and Anne are already standing in one corner of the room, waiting.  
\*Condition  
## A. (Condition: ANNE_GOAWAY >= 1)  
#### A  
Narrator: Upon seeing the both of you enter, Anne approaches Armand, looking agitated.  
\>>  
Anne(sad): Armand, I searched <b><i>everywhere</i></b>. Are you <i>sure</i> you left this letter in the palace?  
Armand: Huh, maybe I have it somewhere at the Hotel after all. But I appreciate all your effort to help me find it.  
Anne(sad): You'd better.  
\***  
Narrator: Armand walks over to Philippe, and they start conferring in hushed, serious voices.  
### \*Goto cd05_seeguard  
# cd05_seeguard  
\>  
Alice*Think: They must be discussing the state of the King's health.  
Narrator: There's a guard standing in the other end of the room, before a door that must lead to the King's bedchamber.  
\*Palaceguard2 Name Palace Guard  
Palaceguard2: ...  
\*Camera Middle 2  
Narrator: You continue looking around you, eyes wide with wonder.  
Narrator: The room is so beautiful, so lavish...  
Narrator: It really brings home the fact that you are about to meet the King and Queen of France.  
\>>  
Alice: Armand...  
# (cd_05_07_do_not_panic)  
## A. Does the King normally take visitors in his chamber?  
## B. We won't be disturbing him, will we?  
#### A  
Narrator: Anne rolls her eyes and snickers derisively.  
Anne(smile): Of course <i>not</i>.  
Alice(sad): Oh... I was just wondering why-  
\>  
Philippe(sad): Louis is not yet well enough to leave his bed.  
Alice(sad): Of course, how silly of me.  
#### B  
Armand: Not at all. Louis has indicated how he appreciates all visitors at the moment.  
Narrator: Anne mutters something under her breath.  
\>  
Anne: Maybe not <i>all</i> visitors.  
Philippe: He's quite bored having to be bed-bound, while recovering.  
Philippe(sad): The time passes slowly, as you can imagine.  
Alice: Yeah, I get what you mean.  
\***  
\*Camera Right 1  
Narrator: Just then, a woman's voice calls from the adjoining room.  
Narrator*Top: VOICE | Are they all arrived? Let them in, Artus.  
\*Palaceguard2 Name Artus  
Narrator: Artus steps aside, and bows.  
Palaceguard2: Your Highness, your Grace, if you please.  
Alice*Think(sad): This is it...!  
Narrator: The four of you enter the next room...  
\*  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_medieval_king_chamber_day.jpg-story' width='60'>
\*Scene KING_CHAMBER_DAY (Color: Black)
{% endhint %}  
\*Camera Left 0  
\*  
\*Camera Right 4  
\*Play Music m_gently_lifting_dreams_01  
Narrator: Where you are greeted by a lavish, gold gilded room, with a grand four poster bed.  
Narrator: There is a grand lady standing beside the bed, in the most majestic silk dress you have ever seen.  
\>>  
Alice*Think: That must be the Queen!  
Narrator: She is young and beautiful, but her expression is solemn.  
Narrator: She smiles gently as she looks at your group, her gaze stopping on you in curiosity.  
\>  
Therese(smile): Philippe, Armand. How kind of you to visit.  
Narrator: As you continue looking round the room, you see a stern looking man in somber clothes standing in one corner...  
\*Rene Name ???  
\*Camera Middle 1  
\>>>  
Rene(angry): ...  
\>  
Narrator: Another finely dressed young lady stands beside him.  
\*Marie Name ???  
\>>>  
Marie: ...  
\>  
Alice*Think: I wonder who they are?  
\*Camera Right 1  
\*Louis Outfit Louis_Pyjamas  
Narrator: It is then that you notice the pale looking young man reposing in the bed, propped up by silk pillows.  
Narrator: His expression is drawn, as if he is in pain, but he's also smiling as he extends a hand towards your group.  
Alice*Think: That must be the King!  
\>>  
\>R  
Louis(smile): Philippe, my dear brother.  
Narrator: Philippe approaches the bed swiftly and the both of them embrace.  
Philippe(smile): Louis, you are looking better today!  
Louis(smile): Yes, by the grace of God, I'm feeling better too.  
\>  
Narrator: Anne walks up to the King, and curtsies.  
Anne: Your Majesty.  
\>>  
\>R  
Louis: Lady Anne.  
\*Camera Middle 2  
Narrator: Anne curtsies to Queen Therese as well, then walks over to join the man and other young lady in the corner of the room.  
Narrator: You watch as she whispers something into the ear of the other young lady...  
Narrator: Who turns around to stare at you and scowl.  
\>>>  
Marie(angry): ...  
\>  
Alice*Think(surprise): Huh?  
\*Camera Right 2  
Narrator: Armand walks up quickly and kneels beside the bed, and kisses Louis' hand.  
\>>  
\>R  
Louis(smile): Ah... Armand, it is good of you to return again today.  
Louis(smile): Your presence gives me great comfort.  
Armand(smile): My dear Louis, how can I stay away?  
Narrator: Armand straightens up, as Louis's attention turns to you.  
Louis: Who have you brought with you, Armand?  
Armand: Louis, Therese, this is Lady {Alice Name}.  
Narrator: You quickly drop into a curtsy.  
\>  
Alice(shy): Your Majesties.  
\>>  
\>R  
Louis(surprise): Lady {Alice Name}? I don't think I've heard of you before.  
Therese: Where are you from?  
\>  
Alice(sad): I... um...  
Narrator: You glance quickly at Armand for help.  
Armand: Lady {Alice Name} seems to have had some kind of traumatic experience...  
Armand: ...And lost her memory.  
\>>  
\>R  
Louis(surprise): Oh!  
Armand: I found her wandering quite helplessly in the market yesterday...  
Armand: With no chaperone, no idea of where she came from, or how to get home.  
Therese(sad): Oh, poor dear!  
Armand: I decided to take her in my charge and help her until she can find her way home.  
Louis: And quite rightly so, Armand, good man.  
\>  
Alice*Think(smile): Thank you, Armand!  
Narrator: Out of the corner of your eye, you see Anne, the other young lady, and the man frowning suspiciously at you.  
\>>>  
Anne(angry): ...  
Marie(angry): ...  
Rene(angry): ...  
\>  
Alice*Think(sad): <i>They</i> don't seem to be quite as ready to believe Armand's explanation.  
Narrator: Queen Therese steps forward and smiles kindly at you.  
\>>  
Therese(smile): Don't worry my dear!  
Therese(smile): You are just as welcome here in the Palace, as you are in Armand's hotel.  
### \*Goto cd05_impressthem (Condition: Alice Outfit = Blue_Silk_Dress)  
### \*Goto cd05_renespeaks  
# cd05_impressthem  
Narrator: Both Louis and Therese peer at you carefully, taking in your appearance...  
Message: First Impressions Count | You made a good first impression on the King and Queen!  
Narrator: And they both smile!  
\>>  
\>R  
\*Louis Opinion +1  
Louis(smile): There is no doubt that you are indeed a lady.  
\>>  
\*Therese Opinion +1  
Therese(smile): That's a beautiful dress! You have good taste, my dear!  
\*Court +2  
Alice(happy): Thank you.  
Therese(smile): I can see that we will have many things to talk about, with regards to fashion.  
### \*Goto cd05_renespeaks  
# cd05_renespeaks  
\*Play Music m_intense_upsetting_descent  
\*Camera Middle 1  
Narrator: Suddenly, the man standing in the corner speaks.  
\>>>  
Rene: Just out of curiosity, Armand...  
Rene: How do you know that this young girl is indeed a lady...  
Rene: And not some tramp with ulterior motives, pretending to be suffering from memory loss?  
Narrator: You feel yourself flush deeply at his words, and you see Armand stiffening in anger.  
\*Camera Right 1  
Armand(angry): Rene, she's under my charge and protection, and I will not abide anyone calling her a <i><b>tramp</b></i>.  
\>>  
Alice*Think(surprise): Rene... that name rings a bell...  
Alice*Think(surprise): That's right! Jeanne mentioned him, Rene Mazarin, Royal Advisor to the King!  
Alice*Think: So that other young lady must be... Marie Mazarin, Anne's sister!  
\>  
\*Rene Name Rene Mazarin  
\*Camera Middle 1  
Rene: Calm down, Armand.  
Rene: It's my job to watch out for anybody who could potentially cheat or harm the King.  
\*Marie Name Marie  
Marie: Daddy has a point. He only has his Majesty's well being at heart.  
\*Camera Right 1  
Alice*Think(sad): What should I do?  
# (cd_05_08_rene_slander)  
## A. Speak up and defend yourself.  
## B. Keep quiet.  
#### A  
\*Stop Music  
\*Play Music m_gently_lifting_dreams_02  
Alice: Excuse me.  
Narrator: Everyone turns to look at you.  
\>>  
Alice(sad): I understand that me suddenly showing up here, like this, looks strange...  
Alice(sad): Especially in times like this.  
Alice(sad): But I don't have any "ulterior motives". I just want to find my way back home.  
Therese(sad): Oh! But of course, my poor girl!  
#### B  
Alice*Think(sad): If I try to say anything, it will only make matters worse.  
\>>>  
Armand(angry): And what "ulterior motives" might this young girl have, pray tell?  
\*Camera Middle 1  
Rene: Perhaps she's a spy, sent here to report back to whoever sent her.  
Rene(angry): Perhaps she's an assassin...  
\*Camera Right 1  
Narrator: Therese gasps.  
Armand(angry): You are reaching, sir, with these far-fetched and ridiculous accusations.  
Armand(angry): Just so you know, she didn't even plan on being here.  
Armand(angry): It was <i><b>I</b></i> who insisted that she come into my charge, as I was worried for her safety...  
Armand(angry): Upon witnessing her being attacked by thugs in broad daylight.  
\***  
\>>  
\>R  
Louis: That's quite enough.  
Louis: Rene, I understand where you are coming from.  
Louis: But I don't want to hear another word accusing this girl of anything, without any proof.  
Louis(angry): Do you understand?  
\*Camera Middle 1  
Rene: Yes, your Majesty.  
Narrator: Rene shoots you a poisonous glare, before composing his face into a neutral mask.  
\*Camera Right 1  
Alice*Think(sad): He really doesn't seem to like me very much.  
Narrator: Louis closes his eyes and takes a deep breath, his face a mask of pain.  
\*Play Music m_blue_epilog_sadness  
Therese(sad): Oh, Louis! You have over-exerted yourself, you must rest!  
Narrator: Louis opens his eyes and smiles weakly.  
Louis(smile): I'm fine, my love.  
Louis(smile): I want them to stay longer, I can rest later.  
Louis(sad): The hours are long, staying in bed like this.  
\>  
Narrator: Therese smiles lovingly back at Louis, reaching to touch his face.  
\>>  
\>R  
Louis: You know what would lift my spirits tremendously?  
Louis(smile): Having my musician come in here and play and sing a song for us.  
\>  
Therese(smile): I shall send word for him right now.  
\*Camera Left 2  
Narrator: Therese walks over to door and speaks to the guard, Artus, who sends for the musician immediately.  
Narrator: Soon, a young man with a wispy moustache arrives, carrying a lute.  
\*Camera Right 2  
Narrator: He bows to the King and Queen, then stands there with a sad look on his face.  
\>>  
\>R  
Louis: Ahh, Henri, play something for us.  
Narrator: Henri gesticulates wildly, then resumes looking sad in silence.  
Louis(surprise): What is the matter?  
Narrator: Henri points to his throat, and gesticulates some more.  
Philippe: It seems like Henri has... laryngitis and cannot sing?  
Narrator: Henri nods his head sadly.  
Therese(sad): Oh no!  
Louis: Oh, well... Can you at least play music?  
Louis: Or do you have arthritis and cannot play as well?  
\*Play Music m_romance_sprightly_spanish_rose_01  
\>  
Narrator: Henri nods quickly, and starts plucking at his lute with his long fingers.  
Narrator: The sweet sound of music fills the air.  
Narrator: Louis looks hopefully at the rest of you.  
\>>  
\>R  
Louis: Maybe one of you can sing?  
Alice(surprise): That's funny, that tune has the same chords as the chorus of La Vie En Rose...!  
Narrator: Unconsciously, you start humming along to it.  
Louis(surprise): Do you know this song?  
Alice: Oh, not exactly, it just sounds a little like another song that I know...  
Louis(smile): Oh, then will you not sing? I would like that very much!  
Alice(surprise): Me? Oh no, I couldn't-  
Louis(smile): What if someone else were to sing with you?  
Therese(smile): Yes! Perhaps you can sing a duet, with Armand, or Philippe!  
Narrator: Both men turn and smile at you.  
Philippe(smile): I wouldn't mind at all.  
Armand(smile): It would be my pleasure.  
Alice(shy): Oh! But... I'm afraid I don't know any of your songs.  
Philippe(smile): I can teach you a simple one...  
Armand(smile): Or you can teach me a song that you know.  
\>  
Narrator: Tutorial | Singing for the King will increase his and the Queen's <color=purple>opinion</color> of you...  
Narrator: Tutorial | As well as unlock a special scene with Armand or Philippe, and increase Romance with him!  
Louis: Please! It will be such a pleasant distraction from the pain.  
\*Item  
# (cd_05_09_sing_for_the_king)  
## A. ITEM_PHILIPPE Sing with Philippe. (Cost: 20 Diamond ID: plot_cd_05_Philippe_sing)  
## B. ITEM_ARMAND Sing with Armand. (Cost: 20 Diamond ID: plot_cd_05_Armand_sing)  
## C. ITEM_NOTHING Insist you can't sing.  
#### A  
Narrator: Louis looks pleased, and Therese claps her hands happily.  
### \*Goto cd05_singphilippe  
#### B  
Narrator: Louis looks pleased, and Therese claps her hands happily.  
### \*Goto cd05_singarmand  
#### C  
### \*Goto cd05_dontsing  
\***  
# cd05_singphilippe  
\*Play Music m_gently_snug_away_in_a_manger_02  
\*Philippe Romance +1  
Philippe(smile): Come on, I'll teach you a simple love song.  
Alice(smile): This will be fun.  
Narrator: He turns and bows to Louis and Therese.  
Philippe: Please excuse us for a few minutes.  
Therese(happy): I can't wait to hear the duet!  
\*Camera Left 1  
Narrator: You follow Philippe out to the antechamber.  
\*  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_medieval_king_antechamber_day.jpg-story' width='60'>
\*Scene KING_ANTECHAMBER (Color: Black)
{% endhint %}  
\*Camera Right 0  
\*  
\>>  
Philippe(smile): Alright, it might be a bit too much to teach you the entire song...  
Philippe(smile): So maybe let's just aim for a verse, and the chorus.  
Philippe(smile): I'll start with the first two lines, you sing the next two lines...  
Philippe(smile): And we'll sing the chorus together. How does that sound?  
Alice(smile): Yes! Okay!  
Philippe(smile): Great. Okay, this is one of Louis' and Therese's favorite songs...  
\*Play Music m_romance_sprightly_spanish_rose_01  
Narrator: Philippe starts singing a 17th-century love song.  
Narrator: He has a beautiful baritone voice, and he stares deeply into your eyes while he sings.  
Narrator: You feel yourself start to blush...  
Alice*Think(shy): I have to focus!  
Narrator: As he sings, you do your best to learn it by heart.  
Alice(sad): This is really difficult. The sentence structure is so archaic...  
Philippe(smile): Don't worry, I have faith in you.  
Narrator: He guides you through the song one more time.  
Alice(smile): I think I've got it!  
Philippe(smile): Good!  
\*Play Music m_gently_snug_away_in_a_manger_02  
Narrator: He means in closer to you, and winks...  
\>>>  
Philippe(smile): This has been the most fun I've ever had teaching someone to sing.  
Alice(shy): I...  
# (cd_05_09_DP2_exercise_with_philippe)  
## A. Enjoyed it tremendously too.  
## B. Hope that they will like it.  
#### A  
\*Philippe Romance +1  
Philippe(smile): We should spend more time together.  
Narrator: You blush, dazzled by the full force of his charm.  
Alice(shy): ...  
#### B  
Philippe(smile): I'm sure they will love it.  
\***  
\>  
Philippe(smile): Ready to dazzle them?  
Alice(smile): Ready.  
\*  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_medieval_king_chamber_day.jpg-story' width='60'>
\*Scene KING_CHAMBER_DAY (Color: Black)
{% endhint %}  
\*Camera Left 0  
\*  
\*Camera Right 2  
Louis(smile): Are both of you ready?  
Philippe(smile): Yes.  
\*Play Music m_romance_sprightly_spanish_rose_01  
Narrator: Philippe murmurs the title of the song to Henri, and the musician starts strumming his lute.  
Narrator: Philippe starts singing, in his beautiful baritone...  
\>>  
Philippe(smile): <color=orange><i>♬ Cessés, ô divine beauté... ♬</i></color>  
Philippe(smile): <color=orange><i>♬ De faire a ma foy ce reproche... ♬</i></color>  
Narrator*Top: <color=orange><i>Cease, O divine beauty... To make my faith this reproach...</i></color>  
Narrator: Soon, it's your turn.  
Alice(smile): <color=orange><i>♬ Des que l'amour fut mon tourment... ♬</i></color>  
Alice(smile): <color=orange><i>♬ Je gravé de dans ma mémoire... ♬</i></color>  
Narrator*Top: <color=orange><i>As soon as love was my torment... I engraved in my memory...</i></color>  
Narrator: And then, the both of you sing the chorus together in harmony.  
Philippe(happy): <color=orange><i>♬ N'estoit que vostre bien-veillance... ♬</i></color>  
Alice(happy): <color=orange><i>♬ Est une fleur d'amour qui ne dure qu'un jour. ♬</i></color>  
Narrator*Top: <color=orange><i>It was only your kindness... A flower of love that lasts only one day.</i></color>  
\*Stop Music  
\*Play Sound s_applause  
Narrator: As the both of you end your duet, Louis, Therese, and Philippe burst into applause.  
\*Play Music m_kiss_romance_classical  
\>>  
\>R  
\*Louis Opinion +1  
Louis(happy): <i><b>Bravo!!</b></i>  
\*Therese Opinion +1  
Therese(happy): Oh, that was too beautiful and moving!  
Louis(smile): My dear girl, you have cheered me up immensely!  
\>  
\*Court +2  
Alice(shy): Thank you. I'm glad you liked it.  
Narrator: Even Henri puts down his lute and starts clapping.  
Marie(angry): Just a regular little song bird, isn't she?  
Anne(sad): I can sing too, why didn't anyone ask me to sing?  
Marie(angry): Oh, do be quiet, Anne.  
Narrator: Philippe turns to you and takes your hand, raising it to his lips.  
Philippe(smile): It was a pleasure.  
Armand(smile): A beautiful performance, indeed.  
Armand(smile): I hope that I will have the pleasure of singing with you the next time.  
### \*Goto cd05_leavechamber  
# cd05_singarmand  
\*Play Music m_gently_snug_away_in_a_manger_02  
\*Armand Romance +1  
Armand(smile): Come on, teach me one of your songs.  
Alice(smile): This will be fun.  
Narrator: Armand turns and bows to Louis and Therese.  
Armand: Please excuse us for a few minutes.  
Therese(happy): I can't wait to hear the duet!  
\*Camera Left 1  
Narrator: You follow Armand out to the antechamber.  
\*  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_medieval_king_antechamber_day.jpg-story' width='60'>
\*Scene KING_ANTECHAMBER (Color: Black)
{% endhint %}  
\*Camera Right 0  
\*  
\>>  
Armand(smile): Alright, do you have a song in mind?  
Armand(smile): How about that one that you were humming?  
Alice: La Vie En Rose?  
Armand: La Vie En Rose? Sounds interesting.  
Armand: Is this one of your modern songs from your time?  
Alice: Yes, it was written in 1945, and sung by Edith Piaf, a famous French singer then.  
Armand(smile): Well then, I would love to learn it.  
Narrator: You giggle at the thought of a 17th-century nobleman singing a modern love song.  
Alice(smile): Okay! So maybe let's just aim for two verses, and the chorus.  
Alice(smile): I'll start with the first verse, you sing the second...  
Alice(smile): And we'll sing the last verse together. How does that sound?  
Armand(smile): Great.  
\*Play Music m_romance_sprightly_spanish_rose_01  
Narrator: You start teaching him the song, and he repeats the lines after you.  
Narrator: He has a beautiful baritone voice, and he stares deeply into your eyes while he sings.  
Narrator: You feel yourself start to blush...  
\>>>  
Alice*Think(shy): I have to focus!  
Armand(surprise): This song is so different to anything I've ever heard before!  
Alice(happy): Haha yeah, I can imagine!  
Narrator: You guide him through the song one more time.  
Armand(smile): I think I've got it!  
Alice(smile): Good!  
\*Play Music m_gently_snug_away_in_a_manger_02  
Narrator: He means in closer to you, and winks...  
Armand(smile): This has been the most fun I've ever had learning to sing a song.  
Alice(shy): I...  
# (cd_05_09_DP3_exercise_with_armand)  
## A. Enjoyed it tremendously too.  
## B. Hope that they will like it.  
#### A  
\*Armand Romance +1  
Armand(smile): We should spend more time together.  
Narrator: You blush, dazzled by the full force of his charm.  
Alice(shy): ...  
#### B  
Armand(smile): I'm sure they will love it.  
\***  
\>  
Armand(smile): Ready to dazzle them?  
Alice(smile): Ready.  
\*  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_medieval_king_chamber_day.jpg-story' width='60'>
\*Scene KING_CHAMBER_DAY (Color: Black)
{% endhint %}  
\*Camera Left 0  
\*  
\*Camera Right 2  
Louis(smile): Are both of you ready?  
Armand(smile): Yes.  
Narrator: You turn to Henri, and instruct the musician the chords of the songs.  
Narrator: You clear your throat and take a deep breath... Then launch into the first verse of La Vie En Rose.  
\*Play Music m_romance_sprightly_spanish_rose_01  
Narrator: Everybody's eyes are fixed on you, as you sing in a sweet, clear voice.  
\>>  
Alice(smile): <color=orange><i>♬ Quand il me prend dans ses bras... ♬</i></color>  
Alice(smile): <color=orange><i>♬ Il me parle tout bas... ♬</i></color>  
Alice(smile): <color=orange><i>♬ Je vois la vie en rose... ♬</i></color>  
Narrator*Top: <color=orange><i>When he takes me in his arms... and speaks to me sweetly... everything is beautiful...</i></color>  
Narrator: Armand continues the next verse, in his beautiful baritone...  
Armand(smile): <color=orange><i>♬ Elle me dit des mots d'amour... ♬</i></color>  
Armand(smile): <color=orange><i>♬ Des mots de tous les jours... ♬</i></color>  
Armand(smile): <color=orange><i>♬ Et ça me fait quelque chose... ♬</i></color>  
Narrator*Top: <color=orange><i>She speaks words of love to me... ordinary words... that change me...</i></color>  
Narrator: And then, the both of you sing the last verse together in harmony.  
Armand(happy): <color=orange><i>♬ Alors je sens en moi... ♬</i></color>  
Alice(happy): <color=orange><i>♬ Mon coeur qui bat. ♬</i></color>  
Narrator*Top: <color=orange><i>So I feel inside me... My heart beating.</i></color>  
\*Stop Music  
\*Play Sound s_applause  
Narrator: As the both of you end your duet, Louis, Therese, and Philippe burst into applause.  
\*Play Music m_kiss_romance_classical  
\>>  
\>R  
\*Louis Opinion +1  
Louis(happy): <i><b>Bravo!!</b></i>  
\*Therese Opinion +1  
Therese(happy): Oh, that was too beautiful and moving!  
Louis(smile): My dear girl, you have cheered me up immensely!  
\>  
\*Court +2  
Alice(shy): Thank you. I'm glad you liked it.  
Narrator: Even Henri puts down his lute and starts clapping.  
Marie(angry): Just a regular little song bird, isn't she?  
Anne(sad): I can sing too, why didn't anyone ask me to sing?  
Marie(angry): Oh, do be quiet, Anne.  
Narrator: Armand turns to you and takes your hand, raising it to his lips.  
Armand(smile): It was a pleasure.  
Philippe(smile): A beautiful performance, indeed.  
Philippe(smile): I hope that I will have the pleasure of singing with you the next time.  
### \*Goto cd05_leavechamber  
# cd05_dontsing  
Alice(sad): I'm so sorry, but I'm really not much of a singer.  
Therese(sad): Ah, pity.  
\>>  
\>R  
Louis: Perhaps next time, then.  
### \*Goto cd05_leavechamber  
# cd05_leavechamber  
\>>  
\>R  
Louis(smile): It was delightful to make your acquaintance, lady {Alice Name}.  
Louis(smile): I hope you'll come back to visit me again soon.  
Alice(smile): Thank you, Your Majesty, I definitely will!  
Louis: Armand, Philippe, will you stay for a while longer?  
Louis: I would like to discuss with you some matters.  
Armand: Of course.  
Marie: Let's leave the men to converse.  
\>  
Narrator: You follow the two women's lead and curtsy, and the three of you leave the King's chambers.  
\*  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_medieval_king_antechamber_day.jpg-story' width='60'>
\*Scene KING_ANTECHAMBER (Color: Black)
{% endhint %}  
\*Camera Right 0  
\*  
\*Camera Left 3  
\*Play Music m_melancholy_tension_heartbeat  
Alice*Think: Maybe I should just wait here for Armand to come out...  
Narrator: Suddenly, you notice that both women have stopped and turned around to face you.  
\>>>  
Anne(angry): ...  
Marie(angry): ...  
\>>  
Alice(surprise): Uh... Is something the matter?  
Marie(angry): Yes, something is very much the matter.  
Marie(angry): I don't know who you are, exactly, but you need to stay away from Philippe!  
Alice(surprise): Excuse me??  
Alice*Think(sad): Why is this happening again???  
Marie(angry): You heard me!  
Marie(angry): <b><i>Stay away from my fiance!</i></b>  
# End  
