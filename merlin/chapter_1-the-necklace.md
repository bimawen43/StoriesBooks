# Begin  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_black.jpg-story' width='60'>
\*Scene BLACK
{% endhint %}  
Narrator: Chapter One | The Necklace  
\*Play Music introduction  
\*  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_medieval_merlin_opening_animation.jpg-story' width='60'>
\*Scene OPENING
{% endhint %}  
\*Camera Left 0  
\*  
\*Camera Right 4  
Narrator: Camelot, 5th Century.  
Narrator: After a long and bloody war, Uther was victorious, and brought many years of peace to Camelot.  
Narrator: King Uther has outlawed witchcraft, and ordered the death of all druids, practitioners of magic.  
Narrator: But the Druids never forgot, and their hatred simmered beneath the surface...  
\*Stop Music  
\*Play Music dream  
\*  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_medieval_cottage_bedroom_day.jpg-story' width='60'>
\*Scene INSIDE_BEDROOM_DAY
{% endhint %}  
\*Camera Right 0  
\*  
Narrator: Your family has been living happily in the countryside of Camelot. Today, you turn eighteen.  
Narrator: Tutorial | Please tell us what to call you first.  
\*Merlin Player  
\*Merlin Naming: What's your name? | Merlin  
# creat_the_role  
\*Merlin Face Face_1  
\*Merlin Outfit Green_Robe  
\*Merlin Hair Flaxen_Curls  
Narrator: Tutorial | Choose your look.  
\*Role  
# (mm_01n_01_choose_face)  
## A. Face Face_1 (Button: Choose This Look!)  
## B. Face Face_2 (Button: Choose This Look!)  
## C. Face Face_3 (Button: Choose This Look!)  
## D. Face Face_4 (Button: Choose This Look!)  
\***  
Narrator: Tutorial | Splendid! Now choose a hairstyle you like.  
\*Role  
# (mm_01n_02_choose_hair)  
## A. Hair Flaxen_Curls (Button: Choose This Hair!)  
## B. Hair Plaited_Hair (Button: Choose This Hair!)  
## C. Hair Blonde_Bun (Button: Choose This Hair! Cost: 16 Diamond ID: look_mm_01_hair02 Message: Your hairstyle will add a lot to your look!)  
## D. Hair Long_Braid (Button: Choose This Hair! Cost: 21 Diamond ID: look_mm_01_hair01 Message: Your hairstyle will add a lot to your look!)  
## E. Hair Dark_Straight (Button: Choose This Hair!)  
\***  
Narrator: Tutorial | You look great! Which outfit do you prefer?  
Narrator: Tutorial | Please note that the outfit you wear will <color=maroon>impact how the story unfolds</color>, so it is very important to <color=maroon>dress appropriately</color> for the occasion.  
\*Role  
# (mm_01n_03_choose_outfit)  
## A. Outfit Green_Robe (Button: Choose This Outfit!)  
## B. Outfit Red_Robe (Button: Choose This Outfit! Cost: 19 Diamond ID: look_mm_01_clothes02 Message: A beautiful robe that grants you confidence and strength.)  
## C. Outfit Square_Cut_Collar_Robe (Button: Choose This Outfit! Cost: 16 Diamond ID: look_mm_01_clothes03 Message: A beautiful robe that grants you confidence and strength.)  
\***  
### \*Goto change_cost_outfit_done (Condition: Merlin Outfit = Square_Cut_Collar_Robe)  
### \*Goto change_cost_outfit_done (Condition: Merlin Outfit = Red_Robe)  
### \*Goto change_free_outfit_done (Condition: Merlin Outfit = Green_Robe)  
# change_cost_outfit_done  
\*Gain Cost_Clothes  
# change_free_outfit_done  
Narrator: Tutorial | Very good, {Merlin Name}, your tale is about to begin. Are you happy with your appearance?  
Merlin: This Style...  
\*Model  
# (mm_01n_04_confirm_look)  
## A. I'd like to try something else. *Goto creat_the_role  
## B. It's perfect! Let's begin! *Goto mom_get_hurt  
\***  
\*Stop Music  
# mom_get_hurt  
\*  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_medieval_cottage_bedroom_day.jpg-story' width='60'>
\*Scene INSIDE_BEDROOM_DAY
{% endhint %}  
\*Camera Left 0  
\*  
\*Play Music tense  
Narrator*Top: Father | Come quickly, {Merlin Name}!  
Narrator: You hear your father's voice and quickly run out the door.  
\*Asher Name Father  
\*+shade1  
Asher(sad): Help me get your mother on the bed, {Merlin Name}!  
Merlin(surprise): Mother!  
Narrator: Your mother is laid out on a plank carried by two men. Hearing your voice, she tries to get up...  
\*Kate Name Mother  
Kate(sad): {Merlin Name}...  
Narrator: She grips her wound, crying out in pain, lips trembling.  
Merlin(surprise): {*Shake Mother! My God, what happened to you?}  
\*Camera Right 3  
Narrator: You carefully prop up your mother and feel her body tremble as you help move her to the bed.  
Narrator: When you look down, your hands and chest are covered in her blood.  
\>>  
Merlin(sad): {*Shake Mother... What...}  
Asher(angry): Keep her talking. Keep her awake. I've got to stop the bleeding...  
Narrator: Your mother struggles to open her eyes.  
Kate(sad): {Merlin Name}... don't be afraid.  
Narrator: You grab her hands.  
Merlin*Think(sad): Her skin is so cold...  
Merlin(sad): Hold on, Mother. You'll be alright.  
Narrator: She smiles weakly and nods, then her eyes fall shut.  
Merlin*Shout(sad): Mother! Mother!  
Narrator: Your father checks her pulse.  
Asher(sad): She's unconscious but still breathing.  
Narrator: Your mother moans from the pain, sweat beading on her brow.  
Merlin(angry): Who did this to her?!  
Asher(angry): What do you think? Those lords up in the manor!  
Narrator: You clench your fists, filled with anger.  
Merlin(angry): After what they did to the baker's daughter... ruining the blacksmith's life... and now this?!  
Asher(sad): I know.  
Merlin(angry): It's like they barely see us as human beings.  
Asher(sad): Help me clean the wound.  
Narrator: You fight to hold back the tears and wash her wound with clean water.  
Narrator: She gasps in agony and clutches the bedsheet in a death grip.  
\>>>  
Merlin(sad): Sorry, Mother, I know it hurts...  
\>>  
Merlin(sad): ...  
# (mm_01n_05_mother_hurt)  
## A. I'll make them pay.  
## B. We must find a healer for her... now!  
#### A  
Merlin(sad): I'll go to the manor tomorrow...  
Asher(surprise): {*Shake No! I forbid you!}  
Merlin(angry): But you see what they did to mother...  
Asher(angry): And they'll do the same to you!  
Merlin(sad): I cannot stand by and do nothing while she suffers!  
Narrator: Tears fill your father's eyes. He turns away from you, watching your mother's face.  
Asher(sad): I'm sorry... It's all my fault—I couldn't protect her. Oh, Kate...  
Narrator: He gently touches your mother's hair as he says her name.  
Asher(sad): {Merlin Name}, I beg of you... do not go to the manor. I can't lose you too.  
Merlin(sad): Father...  
#### B  
Asher(sad): We can't afford a healer. We can only pray to God that she recovers.  
Merlin(angry): This isn't fair!  
Asher(sad): Life rarely is...  
Narrator: You kneel by mother's bed and cross yourself.  
Merlin(sad): Please, Lord, make her well again!  
\***  
\*Stop Music  
# birthday_gift  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_black.jpg-story' width='60'>
\*Scene BLACK (Color: Black Time: 2)
{% endhint %}  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_medieval_cottage_bedroom_night.jpg-story' width='60'>
\*Scene INSIDE_BEDROOM_NIGHT
{% endhint %}  
\*Play Music oceandance  
\*Camera Left 0  
Narrator: The hours stretch into the night as you sit with your father. The bright moonlight seems especially cold tonight.  
\*Camera Right 3  
Kate(sad): Water...  
Narrator: You hurry over and see your mother's eyes slowly open.  
Merlin(happy): {*Shake Mother!}  
Asher(smile): Thank God you're awake.  
Narrator: You offer her water. She takes a sip with her parched lips and suddenly starts coughing.  
Merlin(smile): Take it easy, mother.  
Narrator: She gulps down the water, then leans back on the pillow.  
Merlin(sad): Tell me what happened, Mother.  
Kate(sad): It was an accident... I fell from a ladder...  
Narrator: She looks away from you.  
Asher(angry): You didn't get those injuries from falling.  
Kate(smile): Forget it... that's not important. What's important is that we're still together.  
Kate(smile): I thought I'd never see you again... and on your birthday...  
Merlin(smile): Shh, it's alright.  
Narrator: She holds your hands and you gently kiss her on the forehead.  
Kate: Open the cabinet by the bed, {Merlin Name}.  
Narrator: You open it and see a necklace with a small stone hanging off it.  
\*Play Sound s_magic_skill_01  
\*Item  
# (mm_01n_06_necklace_claim)  
## A. Stone_Necklace A gift from mother for your birthday  
\***  
Kate(smile): You turn eighteen today, {Merlin Name}, and this is for you. Happy birthday!  
Asher(smile): Happy birthday, {Merlin Name}!  
Merlin(sad): Oh... Thank you both!  
Kate(smile): Asher, put it on for her. I want to see her wear it.  
Narrator: Your father gently puts it around your neck. You caress the smooth stone and feel oddly comforted.  
Merlin(cry): Thank you, Mother.  
# (mm_01n_07_wear_necklace)  
## A. This is the best birthday present ever.  
## B. I'm just glad you're alright.  
#### A  
Narrator: Your mother smiles at you and squeezes your hand.  
Kate(smile): I'm glad you like it.  
#### B  
Merlin(sad): I'd trade a thousand necklaces if it meant keeping you alive and well.  
Narrator: Your mother squeezes your hand.  
Kate(smile): Hush, now. Let your mother spoil you on your birthday.  
\***  
Asher(smile): Okay, get some rest, Kate.  
Kate: You're right. I have to work tomorrow. We're counting on the pay this month.  
Asher(angry): Have you gone mad? You can't even stand, much less work!  
Kate(sad): But how are we going to live without money coming in?  
Asher(sad): Don't worry... I'll figure something out.  
Merlin(sad): I can go work at the manor in Mother's place, Father.  
Asher(angry): You're not going anywhere, {Merlin Name}! We'll get through this.  
Narrator: His stern tone leaves no room for debate, so you swallow your unspoken words.  
\*Stop Music  
# goodbye_parents  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_black.jpg-story' width='60'>
\*Scene BLACK (Color: Black Time: 2)
{% endhint %}  
\*  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_medieval_cottage_bedroom_day.jpg-story' width='60'>
\*Scene INSIDE_BEDROOM_DAY
{% endhint %}  
\*Camera Right 0  
\*  
\*Play Music tenderness  
Narrator: Next morning, you wake early, kissing your mother's cheek as she sleeps.  
Merlin*Think: Don't worry, Mother. I can take care of myself.  
Narrator: You gently close the door behind you and leave home.  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_medieval_manor_courtyard.jpg-story' width='60'>
\*Scene YARD_POOL (Color: Black Time: 2.5)
{% endhint %}  
Narrator: You stand in front of the manor and give yourself a pep talk.  
Merlin*Think(angry): Okay... Smile. You're an innocent, nonthreatening girl here to work.  
Merlin*Think: Keep it together. Keep smiling. Deep breaths. You can do this.  
Narrator: You slip through an ivy-covered walkway and see a man lecturing a group of servants.  
\*Flynn Name Steward  
\>>  
Flynn: As the High Steward, I am deeply disappointed with how lazy you lot have been.  
Flynn(angry): If I catch you idling again, you'll be sweeping pig stalls for the next week!  
\>  
Merlin(surprise): Wow, he's strict. This may be harder than I thought...  
# introduce_yourself  
Flynn(angry): Now, back to work. No more slacking off!  
Narrator: The steward turns and heads your way.  
Merlin*Think: I should...  
# (mm_01n_08_meet_flynn)  
## A. Approach him and introduce myself.  
## B. Wait for him to notice me.  
#### A  
Merlin(smile): How do you do, sir? I hope I'm not interrupting you.  
Narrator: He raises an eyebrow in surprise and looks you up and down.  
#### B  
Narrator: You wait respectfully in the corridor, and as he passes by, he stops to look you up and down.  
\***  
\*Condition  
## A. (Condition: Cost_Clothes >= 1)  
## B. (Condition: Cost_Clothes < 1)  
#### A  
Flynn(smile): And who is this fair lady?  
Flynn(happy): Such a classy and well-dressed young lady!  
Flynn(happy): You are as refreshing as a beautiful rose after dealing with servants all day.  
Flynn(happy): How may I help you?  
#### B  
Flynn: What is this?  
Flynn: We don't give charity to beggars here, woman. You'd best run along now.  
\***  
Merlin(sad): Actually, sir...  
Flynn: Do not call me "Sir." I'm Flynn Redrick, the High Steward for Lord Chesterfield.  
Merlin(smile): Pardon me, esteemed High Steward Flynn Redrick!  
Narrator: You curtsy deeply, and Mr. Redrick stands tall, pleased.  
\*Flynn Name Mr. Redrick  
Flynn(smile): Who are you and what business do you have here?  
Merlin(smile): I am {Merlin Name}, Kate Smith's daughter.  
Flynn(surprise): ...  
Merlin(smile): I've come to work in my mother's place.  
Narrator: His expression hardens.  
Flynn(angry): You shouldn't be here.  
Narrator: He pulls out a handful of copper coins and puts them in your hand.  
Flynn(angry): Here, take these and leave.  
Merlin(surprise): But...  
Flynn(angry): Leave before I call the guards.  
Merlin(surprise): Wait! I assure you I can do the job...  
\*Play Music magic  
Narrator*Top: Female voice | Head Steward...  
\*Camera Right 1  
Narrator: You turn around and see a nervous maidservant with a basket of apples in hand.  
\*Reese Name Maid  
Reese(sad): Can someone else deliver the apples, please?  
Flynn(angry): Are you trying to get out of work, Reese?  
\*Reese Name Reese  
Reese(sad): I'll do anything else! It's just...  
Narrator: She glances toward the tourney grounds, then lowers her head and sobs quietly.  
Flynn(angry): Damn that blasted game...  
Narrator: He mutters under his breath, still staring daggers at the girl.  
Merlin*Think: Game...?  
\>>  
Merlin(smile): Give it to me! I'll deliver the apples.  
Reese(sad): Wait...  
\>  
Narrator: You quickly take the basket from the girl's hands and put on your sunniest smile.  
Merlin(happy): Where am I taking the basket to?  
Flynn(angry): Now see here...  
Narrator: The maidservant points at the distant grounds and you head off.  
\>>  
Merlin*Think(smile): It's just delivering apples... I don't see what all the fuss is about.  
Flynn(angry): Come back! You have no idea what's going on!  
Narrator: You don't stop, taking off before he can catch you.  
\*Camera Left 3  
Narrator: You run past the stone road and the colorful pennants of the tourney grounds quickly come into view.  
# bring_apple  
\*  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_medieval_grassland_Range.jpg-story' width='60'>
\*Scene ARCHERY
{% endhint %}  
\*Camera Left 0  
\*  
\*Play Music tension2  
Narrator: You can hear the excitement from a distance—gathering squires form a circle, waving their fists merrily and shouting.  
\*Victor Name Guard  
\*Barry Name Guard  
Narrator: Squire | Come on, I can't wait! Let's start!  
Narrator: Squire | He's so scared... Let's see if we can make him shit his pants.  
Narrator: You push through the crowd and see a manservant standing alone in the circle.  
\*Camera Right 1.5  
\*John Name Nobleman  
John: Fetch me an apple, Hardy!  
\*Hardy Name Hardy  
\*Camera Left 1.5  
Merlin*Think(surprise): An apple?  
Narrator: A man comes out of the crowd and snatches an apple from your basket.  
Hardy(smile): I'll take that.  
\*Camera Right 1.5  
John: Go put it on!  
Hardy(smile): Yes, my lord.  
Narrator: Hardy puts the apple on top of the manservant's head.  
Narrator: The servant's knees shiver profusely, near to buckling.  
John(smile): Alright, let the fun commence!  
Narrator: The young nocks an arrow and aims it at the servant's head, deliberately adjusting it up and down to relish in his target's fear.  
Victor(smile): Look, he pissed himself!  
Narrator: The squires once again guffaw in delight.  
Narrator: Suddenly, someone pulls you away from the crowd. You turn around and see the maid who gave you the apples.  
\*Camera Left 1.5  
\>>  
Merlin(surprise): Reese?  
Reese(sad): I finally found you. Did they hurt you? Hurry and come with me.  
Merlin(surprise): Who was that man? What is going on?  
Reese(angry): You are so rash, child. Joining in their circle like that...  
Narrator: Reese rambles on as she clutches your hand in such a tight grip that it’s starting to turn blue.  
\>  
Merlin(angry): No!  
Merlin(sad): My gut is telling me that my mother's wound has something to do with that nobleman...  
Reese(angry): We have to go, quickly!  
Narrator: Tutorial | Throughout the story, you'll encounter <color=maroon>diamond options</color>. Here comes one now.  
Narrator: Tutorial | Such options can unlock <color=maroon>unique scenes</color> and boost <color=maroon>relationships</color> with characters, revealing their personalities.  
Merlin: ...  
# (mm_01n_09_go_to_archery)  
## A. No! I need to find out who that nobleman is. (Cost: 16 Diamond ID: plot_mm_01n_nobleman) *Goto watch_archery  
## B. You are right.  
#### B  
Narrator: Reese drags you through the crowd. You struggle to keep up.  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_medieval_manor_courtyard.jpg-story' width='60'>
\*Scene YARD_POOL
{% endhint %}  
Reese(sad): What happened to your mother?  
Merlin(sad): She returned home yesterday covered in blood!  
Reese(sad): Oh my God. I hope she's alright!  
Merlin(sad): She's... stable for now.  
Reese(sad): Promise me you'll go home now and take good care of her.  
Reese(sad): I'm sure she wouldn't want you to be here, either.  
Merlin(sad): She nearly died yesterday! How could I remain indifferent?!  
Merlin(sad): You work here. Please tell me who that nobleman is.  
Reese(sad): It's none of your concern.  
Merlin(angry): I should not have listened to you. I could have found out the truth by myself!  
Narrator: Suddenly, you hear a gruff voice.  
Narrator*Top: Man's Voice | Hey you. Servant girl. Come here!  
Narrator: You turn around and see Hardy staring at you from a distance.  
\>>  
Merlin(surprise): Me?  
\>  
Narrator: You run to Hardy.  
\*  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_medieval_grassland_Range.jpg-story' width='60'>
\*Scene ARCHERY
{% endhint %}  
\*Camera Right 0  
\*  
Hardy(angry): Get rid of this dead body immediately.  
### \*Goto bury_the_dead  
\***  
# watch_archery  
\*Stop Music  
\*Play Music tension7  
Narrator: The crowd stills.  
Narrator: Nobleman | Watch carefully, everyone!  
\*Camera Right 1  
Narrator: The field is deathly silent as the young noble releases the arrow...  
\>>  
Merlin(sad): {*Intense No, no...}  
\>  
\*+ARCHERY_ANIMATION  
Narrator: Cheers erupt around you as the servant's body falls limply to the ground.  
John(smile): ...  
Hardy(smile): You are definitely the best archer in Camelot, my lord.  
Barry(happy): Indeed, such an impeccable shot!  
Narrator: The noble glances at the surrounding squires and revels in their flattering cheers.  
\*Camera Left 1.5  
Merlin(angry): ...  
# (mm_01n_09_DP1_meet_lord)  
## A. So he's the one who hurt Mother.  
## B. He is murdering people in broad daylight!  
#### A  
Reese(sad): What happened to your mother?  
Merlin(sad): She returned home yesterday covered in blood!  
Reese(sad): Oh my God. I hope she's alright!  
Merlin(sad): She's... stable for now.  
Reese(sad): Promise me you'll go home now and take good care of her.  
Reese(sad): I'm sure she wouldn't want you to be here, either.  
#### B  
Reese(sad): Quiet, or someone might hear you and we'll both be in trouble!  
Merlin(angry): But this is deplorable!  
Reese(angry): Don't be so childish, young lady!  
Merlin(angry): Childish?! Making sport of other people's pain is childish. I'm just...  
Reese(sad): Go home! Now! It's all my fault—I should have stopped you.  
\***  
Merlin(angry): I'm not going anywhere.  
Reese(angry): ...Fine.  
Narrator: Reese scowls at you, then hurries away.  
\*Stop Music  
\*Play Music tense  
\*Camera Right 1  
Narrator: In the center of the crowd, the nobleman nocks another arrow and casually sweeps his aim around , making the squires step back in panic.  
John: Hmm... this is boring.  
Narrator: He shoots the arrow into a tree above the squires' heads and chucks the bow. Hardy rushes to catch it.  
Hardy(smile): I know a place you will surely find interesting, my lord.  
Narrator: The noble laughs in pleasure as Hardy whispers into his ear.  
John(smile): Great idea, my good man!  
Hardy(smile): As long as it pleases you, my lord.  
Narrator: The nobleman glances back at the dead man.  
John: Someone clean this mess up.  
Narrator: He rides off on horseback with the squires quickly following behind.  
Narrator: Hardy gives the corpse on the ground a kick with his boot in disgust.  
Hardy(angry): Hey you. Servant girl. Come here!  
\>>  
Merlin(surprise): Me?  
\>  
Narrator: You run to Hardy.  
Hardy(angry): Get rid of this dead body immediately.  
# bury_the_dead  
Narrator: You glance at the body, a cold sinking feeling in your gut.  
\>>  
Merlin: ...  
# (mm_01n_10_bury_task)  
## A. I'm not sure how to do this, sir...  
## B. The High Steward ordered me to do something else...  
#### A  
Hardy(angry): I don't care how you do it! You need to clean this place up before the lord comes back.  
Merlin(surprise): But I...  
Narrator: Hardy looms over you, his strength evident as he casts a shadow around you.  
Hardy(angry): Keep talking and you'll be lying there with him.  
Merlin(sad): Yes, sir.  
Narrator: You give the corpse a nervous glance and feel his eyes staring back at you, sending a chill up your spine.  
#### B  
Hardy(angry): Shut your mouth and do as you're told!  
Merlin(angry): ...  
Hardy(angry): Insolent lass!  
\***  
Hardy(angry): Do it! And feed the horses when you're finished!  
\>  
Narrator: Hardy turns around and leaves. You're alone on the tourney grounds, looking down at the corpse.  
Merlin(sad): Poor man...  
Narrator: You hear a low-voiced prayer coming from behind you.  
Narrator*Top: Man's voice | May your soul rest in peace...  
Narrator: You turn around...  
\*Stop Music  
\*Play Music farewell  
\*Lancelot Name Manservant  
\>>  
Lancelot(sad): My God! Poor Chuck...  
\>  
Narrator: A manservant makes a cross over his chest while looking at the body.  
Lancelot(sad): Thank you for taking care of Chuck's... body.  
Lancelot: My name is Lancelot. What is yours?  
\*Lancelot Name Lancelot  
Merlin: My name is {Merlin Name}.  
Lancelot(sad): You shouldn't have to do this... Let me handle it from here.  
Merlin: ...  
# (mm_01n_11_lancelot_help)  
## A. I can handle it myself.  
## B. Thank you. You are so kind!  
#### A  
Lancelot(surprise): Aren't you afraid of handling a corpse?  
Merlin(sad): There's nothing to be afraid of, he merely went to another world.  
Lancelot(smile): It's not often I see a girl as brave as you.  
#### B  
Merlin(sad): Thank you. I wouldn't know what to do if it weren't for you.  
Lancelot(smile): You must have been scared out of your wits. Don't worry, I will take care of everything.  
Narrator: Lancelot puts a reassuring hand on your shoulder.  
Lancelot(angry): I can't believe Hardy would leave the body behind like this.  
\***  
Merlin: Did you know Chuck?  
Lancelot(sad): Yeah. I worked with him in the mill. He was so diligent, honest and hospitable...  
Merlin(sad): Was he a good man?  
Lancelot(sad): He really was. He didn't deserve to be treated like this.  
Merlin(sad): Why is it always the good ones? The nobleman murdered a civilian in broad daylight, just for fun!  
Lancelot(sad): He had a beautiful wife. She just gave birth to an adorable son...  
Lancelot(sad): Now a loving mother loses her husband, and a child is deprived of his father.  
Merlin(angry): I can't believe things like this actually happen.  
Narrator: You clench your fists in anger.  
Merlin(sad): Poor Chuck. But at least we can bury him with dignity.  
Lancelot(sad): How about burying him in the woods?  
Lancelot: The nobles barely come to that place. At least he could rest in peace there.  
Merlin(smile): Good idea.  
Narrator: Lancelot picks up the body and puts it onto the handcart next to him, and you two push it out of the arena together.  
\*Stop Music  
# mm01_in_forest  
\*Play Music suspicion  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_medieval_forest_road_junction_day.jpg-story' width='60'>
\*Scene FOREST_PATH_DAY
{% endhint %}  
Merlin: Lancelot, who was that man with the bow?  
Lancelot(angry): That's Lord Chesterfield of Deva County. The manor belongs to his family.  
\*John Name Lord Chesterfield  
Merlin: I see...  
Lancelot: You didn't know?  
Merlin(sad): This is my first day working in my mother's place.  
Lancelot: Your mother works in the manor?  
Merlin(sad): Yes, but she came back yesterday with a terrible wound...  
Lancelot(surprise): Are you the daughter of Mrs. Smith?  
Merlin(surprise): Yes! Do you know her?  
Lancelot(sad): She is a very kind lady who's helped me often...  
Merlin(sad): Then can you tell me...  
# (mm_01n_12_mother_hurt_reason)  
## A. What happened to her?  
## B. Did Lord Chesterfield hurt my mother?  
#### A  
Merlin(sad): You know how she got hurt, right?  
Lancelot(sad): ...  
Narrator: Lancelot lowers his head and sighs.  
Lancelot(sad): Some things we are better off not knowing, {Merlin Name}.  
#### B  
Merlin(angry): It was Lord Chesterfield who hurt my mother,  wasn’t it?  
Lancelot(sad): That's not important...  
Lancelot(sad): Go home and never come back after your day's work is done. Do it for Mrs. Smith.  
\***  
Merlin(sad): But...  
Lancelot(sad): Do you trust me?  
Lancelot: Do you believe I'm a man who speaks the truth? That I have no reason to wish you harm?  
Merlin(sad): I... Yes.  
Lancelot(sad): Then please. Promise me you'll go home today and drop this matter.  
Narrator: You stare into his earnest face, knowing he won't drop the subject until you promise.  
Merlin(sad): Okay... I will.  
Narrator: Lancelot lets out a sigh, tension leaving his face.  
Lancelot(smile): Alright... What do you think of that area, there?  
Narrator: You look at where Lancelot is pointing and see a distant meadow teemed with lush flowers.  
Merlin(smile): I'm sure Chuck would approve.  
Narrator: The two of you bury Chuck in silence, then each say a prayer for his soul.  
Narrator: On the trip back, the forest is so quiet, there is no sound save for the squeaking of the handcart wheels.  
Merlin*Think: It's so peaceful here... a world away from the craziness of the manor...  
Lancelot: Tired, {Merlin Name}?  
Merlin(sad): My mother was always too tired to lift her arms when she got home. Now I know why...  
Lancelot(sad): The work is never done as long as we can still move. Hardy's whip will make sure we're never idle...  
Narrator: Thinking of your mother doing the back-breaking work you just did, anger flares inside of you again.  
Merlin(angry): My mother worked so hard for them for years! Yet they still hurt her!  
Lancelot(sad): How is she doing?  
Merlin(sad): She was bleeding so much. Her clothes were stuck to her when they brought her home.  
Lancelot(angry): Damn those bastards!  
Narrator: Lancelot clenches his fists in anger.  
Lancelot(angry): Someday... I'll be strong enough to stop things like these from happening.  
Lancelot: You know... there are people who mount warhorses.  
Lancelot(smile): And protect the kingdom and citizens with their swords.  
Merlin(surprise): You mean the knights?  
Lancelot(smile): That's right! The knights!  
Lancelot(smile): The knights are loyal, compassionate, and grant mercy to those who ask.  
Lancelot(smile): They always assist and never threaten ladies, never get into useless squabbles.  
Merlin(smile): A great ideal.  
\*Play Music romance  
Merlin(smile): ...  
# (mm_01n_13_knight_dream)  
## A. You don't sound like an ordinary servant. (Cost: 12 Diamond ID: plot_mm_01n_Lancelot)  
## B. You admire them a lot.  
#### A  
Merlin(smile): Why do you know so much?  
Lancelot(smile): When the elder Lord Chesterfield was still alive, he sent me to accompany his son in his classes.  
Lancelot(smile): That's how I had the chance to learn.  
Merlin(sad): The elder Lord Chesterfield allowed you to accompany his son to class? He must have liked you.  
Lancelot(smile): Yes. He treated me so well... As if I were his own child.  
Lancelot(smile): And not just me, but everyone in the manor.  
Lancelot(smile): He took care of everyone. And everyone in the manor loved him...  
Merlin(smile): Sounds like he was a great man.  
Lancelot(sad): Yes. When he died, I was still a child. Then, his son, Lord Chesterfield inherited the manor.  
Lancelot(sad): That's when everything changed.  
Narrator: Lancelot lets out a long sigh.  
Lancelot(angry): The young Lord Chesterfield, has turned this place into hell.  
Lancelot(angry): I must get out of here one day.  
Merlin(sad): ...  
#### B  
Lancelot(smile): Well... Why shouldn't I? They're what men are supposed to be.  
Lancelot(smile): I wish I knew more about them.  
\***  
# Lancelot_love_you  
Narrator: A breeze picks up, making the trees roar softly as their leaves dance in the wind.  
Narrator: Suddenly, you stumble, your head swimming.  
\>>>  
Lancelot(surprise): Careful!  
\>  
Narrator: Lancelot grabs a hold of you before you fall.  
Narrator: Your Stomach | <i>Growl...</i>  
Narrator: You hold your empty belly, embarrassed.  
\>>  
\*Play Music m_kiss_romance_classical  
Merlin(shy): Excuse me...  
Lancelot(smile): My fault for forgetting it's lunch time. You must be famished!  
Merlin(sad): I'm so hungry that I could eat a cow.  
Narrator: The two of you take a break on a rock by the roadside.  
Lancelot(sad): I'm sorry I didn't realize...  
Merlin(surprise): No, please... don't apologize.  
# (mm_01n_14_lancelot_apologize)  
## A. This is embarrassing enough as it is.  
## B. You're so sweet, Lancelot.  
#### A  
Lancelot(smile): There's nothing to be embarrassed about...  
Narrator: You bury your face in your hands and hear him laughing.  
Merlin(sad): Are you laughing at me?  
Lancelot(happy): Sorry, no... It's just that you looked so adorable like that.  
Merlin(shy): Adorable...?  
#### B  
Merlin(smile): You don't even know me, yet you've been kind to me all day.  
Lancelot(shy): I was unaware I had to know someone before I could be kind to them.It’s a rarity finding someone so kind.  
Merlin(smile): It's rare to find someone who's kind at all.  
Merlin(sad): Cruelty is much more common.  
Narrator: Images of the young lord and his cronies laughing and cheering flashes through your mind. You shake your head to to clear your thoughts.  
Merlin(smile): You're a good man, Lancelot. I'm glad I met you today.  
Lancelot(happy): ...!  
\***  
Narrator: He stares at you a moment, his eyes going soft, before he clears his throat.  
Lancelot(smile): You know... If you're up for it, I could catch some fish for lunch.  
Lancelot(happy): I make a mean grilled trout.  
Merlin(surprise): But we don't have a fishing pole, or any nets...  
Narrator: He makes a show of checking in all directions for eavesdroppers, then leans in close to you, whispering conspiratorially.  
\>>>  
Lancelot(smile): What if I told you I had a way of catching fish without any lines or nets?  
\>>  
Merlin(smile): Then I'd have to accuse you of witchcraft, sir.  
Lancelot(happy): Ha! It's nothing so amazing as that.  
Merlin(smile): Then how...  
Narrator: He shrugs with false, playful innocence.  
Lancelot(smile): If you want to know... you'll have to let me show off for you.  
Merlin(happy): Oh really?  
Lancelot(smile): Yes. Let me take you fishing for lunch.  
Lancelot(smile): You can take the leftovers home to your mother to help her recuperate.  
# mm01_fishing  
Lancelot(smile): What do you say?  
\*Model  
# (mm_01n_15_lancelot_barbecue)  
## A. Sorry, I'd rather head back instead.  
## B. Yes, let's go! (Cost: 19 Diamond ID: plot_mm_01_Lancelot)  
#### A  
Merlin(sad): I'm sorry, but all I can think about is finishing work so I can go home and check on my mother.  
Lancelot(sad): It's alright. I understand how you feel.  
### \*Goto hunting_game  
\*Stop Music  
#### B  
Lancelot(smile): I guarantee you'll love my grilled fish.  
\*Stop Music  
### \*Goto barbecue_riverside  
\***  
# barbecue_riverside  
\*Play Music chirp  
Narrator: You follow Lancelot through the bushes. The grass is soft and the sound of birds chirping rings in your ears.  
Merlin(smile): You seem to know this place well... Do you come here often, Lancelot?  
Lancelot(smile): Yes. I feel at peace here.  
Merlin(smile): I wouldn't expect something like this to exist so close to the ranch.  
\>>>  
Lancelot(smile): Finding something so beautiful in a place filled with such ugliness makes it all the more precious.  
\>>  
Narrator: His eyes meet yours and a gentle smile plays at his lips.  
Merlin(shy): Oh...  
# (mm_01n_15_DP1_sweet_words)  
## A. Pfft. Sweet talker...  
## B. I bet you say that to all the girls.  
#### A  
Merlin(smile): I don't fall for pretty lines or flattery, you know.  
Lancelot(happy): Ouch! It wasn't a line... I meant it sincerely.  
#### B  
Lancelot(smile): What other girls?  
Narrator: You raise an eyebrow at him and he laughs.  
\***  
Lancelot(happy): What sort of man do you take me for?  
Lancelot(shy): To be honest with you, I haven't had the chance to befriend many women....  
Merlin(surprise): Really? Why is that?  
\>  
Narrator: He rubs the back of his neck, looking away awkwardly.  
Lancelot(shy): It's, um... Well...  
Lancelot(surprise): Oh, look! We're here.  
Narrator: He hurries ahead and you can't help but smile.  
\*  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_medieval_forest_streamlet_bonfire.jpg-story' width='60'>
\*Scene BARBECUE_AT_THE_RIVER
{% endhint %}  
\*Camera Right 0  
\>  
\*  
\*Play Music burning2  
Narrator: You scoop a handful of creek water and enjoy the cool liquid running down your throat as you drink it.  
Merlin(smile): So how do you plan on catching fish without a line?  
Lancelot(smile): Allow me to demonstrate!  
Narrator: When you turn around, Lancelot is already barefoot with his pant legs rolled up. He grabs a long sharp stick and wades into the water.  
Narrator: He kicks up water and splashes you on purpose.  
Merlin(happy): Hey!  
\*Lancelot Face Sammy_Naked  
Lancelot(happy): Haha!  
\>>  
Merlin*Think(happy): I should...  
# (mm_01n_15_DP2_play_water)  
## A. Get him drenched.  
## B. Be gentle.  
#### A  
\>  
Narrator: Returning the favor, you get a big scoop with your skirt and fire back.  
Narrator: <i>Splash!</i>  
Lancelot(happy): You monster! I'm soaked...  
Merlin(happy): Well, you deserve it!  
#### B  
\>  
Narrator: You kick water back at him, careful not to get either of you too wet.  
Merlin(happy): Take that!  
\***  
\*Play Music m_kiss_romance_classical  
\>>>  
Lancelot(smile): I'm happy to see you smile like that. Your smile brightened up my day.  
Merlin(shy): Oh? Um...  
\>>  
Lancelot(smile): Alright, no more splashing or we'll scare the fish.  
\>  
Narrator: Fixated on a black fish not too far off, Lancelot stalks it slowly and raises the stick...  
Lancelot: Steady now...  
Narrator: He plunges the stick into the water. The fish writhes as he pulls it to the surface.  
\>>  
Lancelot(happy): Got it!  
Merlin(happy): That was incredible!  
Narrator: Lancelot tosses the fish at you.  
Merlin(happy): Wow! It's bigger than I thought!  
Narrator: You put the fish down, roll up your sleeves and walk to the bank.  
Merlin(smile): Alright, my turn!  
Lancelot(smile): Oh, it's not as easy as it looks.  
\*Lancelot LOVE +1  
\>  
Narrator: He hands you the stick. You tread carefully into the water.  
Narrator: You can feel smooth rocks under your feet and weeds brushing your ankles.  
Lancelot: Stay calm, focus, slow your breathing...  
Narrator: You pick out a target among the school of fish...  
\>>  
Merlin(angry): Hya!  
\>  
Narrator: The thrust sloshes water all about. When the water settles, all you see is an empty stick.  
Merlin(sad): ...  
Lancelot(smile): I told you, fish are more slippery than you think.  
Merlin(angry): I can do this!  
Narrator: You bend over and look for a new target...  
\>>  
Merlin(smile): A-ha!  
Narrator: You aim carefully and lunge the stick downward...  
Merlin(surprise): Argh!  
Narrator: You lose your balance.  
\>>>  
Lancelot(surprise): {Merlin Name}!  
\>>  
Narrator: He rushes over and you fall into his arms.  
\>>>  
Merlin(shy): Lancelot...  
\>>  
Narrator: He steadies you upright, then pulls away.  
Lancelot(shy): Ahem...  
Narrator: There's a long, silent pause.  
Merlin(smile): Um, how about we grill the fish?  
Lancelot(happy): Oh yes, I'm starving!  
\>  
\*Camera Left 3  
Narrator: Lancelot gathers dry branches and skillfully builds a makeshift barbecue. Before long, the scent of grilled fish fills the air.  
\*Lancelot Face Sammy_Manor  
Lancelot(smile): Here.  
Narrator: You take a big bite out of the fish. It has a good, smoky flavor.  
Merlin(happy): Oh my! This is delicious!  
Lancelot(smile): We can do this again if you like.  
\*Lancelot LOVE +1  
Merlin(shy): ...  
Narrator: The two of you waste little time devouring the fish. Lancelot wraps what's left over in leaves.  
Lancelot(smile): Here, may your mother recover soon.  
Merlin(smile): Thank you.  
Narrator: You and Lancelot lay down on the ground, enjoying the breeze and the scent of the wildflowers.  
\>>>  
Lancelot(smile): {Merlin Name}...  
\>  
Narrator: You turn back and see him. You realize he's laying so close to you, you could even count his eyelashes.  
Narrator: Lancelot raises his hand, and tucks your hair back behind your ear.  
Merlin*Think(smile): I should...  
# (mm_01n_15_DP3_hold_hands)  
## A. Hold his hand.  
## B. Ask to go back.  
#### A  
Narrator: You move your hand slowly and touch Lancelot's hand...  
Lancelot(surprise): {Merlin Name}!  
\*Lancelot LOVE +1  
Merlin(shy): What?  
Lancelot(smile): You... well... nothing...  
Narrator: Lancelot wraps his hand around yours and squeezes lightly.  
Narrator: The two of you share a quiet moment with the warm sun on your cheeks.  
Lancelot(smile): We should go back before someone notices we're gone...  
Merlin(sad): Do we have to?  
Narrator: Lancelot gives your hand another squeeze before pulling you to your feet.  
#### B  
Narrator: You blush and look away, avoiding his eyes.  
Merlin(shy): We should head back...  
Lancelot(surprise): Sorry! I didn't mean to make you uncomfortable.  
Merlin(smile): It's fine...  
\***  
Narrator: You brush the dirt from your clothes and head back, feeling much lighter than you did before.  
# hunting_game  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_medieval_manor_courtyard.jpg-story' width='60'>
\*Scene YARD_POOL
{% endhint %}  
\*Play Music tension2  
Narrator: You arrive at the manor just as the blast of a horn sounds across the estate.  
Narrator: It's followed by a woman screaming and the sound of men cheering.  
Merlin(surprise): What's going on?  
Lancelot(angry): Damn it! That dreadful game! {Merlin Name}, run!  
Narrator: You look back and see a group of squires following Hardy as he rides his horse.  
Hardy(smile): Gather round! Gentlemen, it's time for your favorite game!  
Hardy(smile): I'm sure you wouldn't want to pass up the opportunity to make some money!  
Narrator: You see a long line of servants being herded like sheep.  
Merlin(angry): Haven't they had enough for today?!  
Lancelot(angry): They'll never have enough.  
Victor(happy): Oh look! Seems we've missed two.  
Barry(happy): Get them!  
\*+shade2  
Merlin(surprise): {*Shake No!} I'm not...  
# End  
