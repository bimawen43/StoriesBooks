# Begin  
\*Play Music durnk  
\*  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_3_city_beach_house_night.jpg-story' width='60'>
\*Scene OUTSIDE_BEACH_HOUSE_NIGHT
{% endhint %}  
\*Camera Left 0  
\*  
\*Condition  
## A. (Condition: DID_METEOR_SHOWER_PREM >= 1)  
## B. (Condition: DID_METEOR_SHOWER_PREM < 1)  
#### A  
\*+METEOR_SHOWER  
Narrator: You and Sam lay on the beach beneath a meteor shower.  
#### B  
Narrator: You and Sam are on the beach beneath the stars.  
\***  
Sam(smile): I'm in love with you, {Layla Name}.  
\>>>  
Layla(surprise)*Think: {*Joyful Oh my god...!}  
Narrator: Emotions swirl through you so fast you feel lightheaded.  
\*Play Sound s_seawave  
Layla(surprise)*Think: Tomorrow's my last day on land...  
\>>  
Layla(sad)*Think: I don't know when I'll see him again...  
Layla(sad)*Think: Would he still love me if he knew I was a mermaid?  
\*Stop Sound  
\>  
Sam: ...{Layla Name}?  
Layla(surprise): Sorry! You surprised me!  
Sam(shy): ...  
Layla*Think: I need to tell him I'm leaving.  
# (sld_09_01_leaving)  
## A. I love him too, but...  
## B. I don't want to hurt him, but...  
#### A  
\*Gain LOVES_SAM  
\***  
\>>  
Layla(sad): Sam...  
Sam(sad): Oh no.  
Layla(sad): I wish I could--  
Sam(sad): Hey, no. I get it. You don't feel the same. That's fair.  
\*Condition  
## A. (Condition: LOVES_SAM = 1)  
## B. (Condition: LOVES_SAM = 0)  
#### A  
Layla(shy): I never said I don't feel the same.  
Sam(surprise): Then... Does that mean--  
#### B  
Layla(sad): Hey. Let me finish.  
Sam(sad): Sorry.  
\***  
\>  
\*Stop Music  
\*Play Music pity  
Layla(sad): What I'm <i>trying</i> to tell you is that now is a really bad time.  
Layla(sad): My whole life is a mess right now.  
Sam(sad): What do you mean? Are you talking about falling from the cliff?  
Narrator: You shake your head, feeling the pressure of all the lies building up inside of you.  
Layla(sad): The thing is...  
# (sld_09_02_mess_life)  
## A. I've learned something about my family.  
## B. I'm going home tomorrow.  
#### A  
Layla(sad): My grandma just told me a family secret.  
Layla(sad): I can't talk about it, but it's... a lot to think about.  
Narrator: Sam reaches for you, taking your hand in his.  
\>>  
Sam(sad): I'm sorry... I had no idea.  
Narrator: You force an awkward laugh.  
Layla(smile): Yeah, well, neither did I until a few days ago.  
Layla(sad): But... Because of all this, I'm going home tomorrow.  
\>  
#### B  
\>>  
Sam(surprise): What? Why?  
Layla(sad): There's... some things going on with my family right now.  
Sam(sad): Oh no... Is your grandma okay?  
Layla(smile): She's fine, don't worry!  
Layla: But I've learned more about my parents, and...  
Layla(sad): I just need time to process.  
\>  
\***  
Sam: That's alright. I hate that you have to cut your vacation short...  
Sam(smile): But I'll just see you when I get back.  
Layla(sad): It might be a little longer than that...  
Layla(sad)*Think: And even then, only for a week at a time...  
Layla(sad): I'm sorry... Like I said, there's just so much going on right now.  
\*Stop Music  
\*Play Music m_gently_romance_heavenly  
Narrator: He looks at you seriously and you can feel how much he cares about you.  
Sam(sad): How can I help?  
Layla(sad): You could...  
# (sld_09_03_sam_care_about)  
## A. Just hold me close.  
## B. Tell the others for me.  
#### A  
\>>  
\*Sam FLIRT +1  
Sam(smile): That I can definitely do.  
Narrator: He pulls you closer into his arms and you bury your face against his neck.  
Layla(smile)*Think: He smells so good...  
\>  
#### B  
Layla(sad): I don't want to have to explain everything...  
Sam(smile): Hey, say no more. I've got it covered.  
\***  
Narrator: You stare up at the sky, your mind buzzing with thoughts.  
Layla(smile)*Think: Sam has always been there for me...  
\*Condition  
## A. (Condition: LOVES_SAM = 1)  
#### A  
\>>  
Layla(shy)*Think: He... he loves me. <i>Sam loves me.</i>  
Sam(happy): What are you giggling about? This is a serious moment.  
Layla(shy): ...I, um... I remembered what you said.  
Sam(shy): Oh...  
\>  
Narrator: You smile softly to yourself as Sam looks away, fidgeting.  
\***  
Layla*Think: I'm leaving tomorrow... Who knows when I'll be back on land...  
Layla: Hey, Sam...  
# (sld_09_04_sam_hookup)  
## A. Do you want to spend the night together? (Cost: 21 Diamond ID: plot_sld_09_sam) *Goto merm09_prem_sam_hookup  
## B. It's getting late. Let's go inside.  
#### B  
Sam(smile): Right. You probably have to pack, don't you?  
Layla(shy)*Think: ...Packing. Right. I better pretend to do that.  
Layla(smile): Something like that... heh.  
Narrator: You follow Sam into the house, not sure if you'll be getting any sleep that night.  
### \*Goto merm09_visit_grandma  
\***  
# merm09_prem_sam_hookup  
\*Stop Music  
\*Play Music m_intense_romance_sexy_love_01  
\*Gain PREM_MERM09_SAM_HOOKUP  
\>>  
\*Sam FLIRT +1  
Sam(surprise): Do you mean as in--  
Narrator: He clears his throat and runs his hands through his hair.  
Sam(shy): I mean, sure. Yeah. That sounds good. Let's do... that.  
\>  
\*Camera Middle 3  
Narrator: You take Sam's hand as the two of you head back into the house.  
Layla(shy)*Think: I can't stop smiling.  
\*  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_city_beach_house_inside_night.jpg-story' width='60'>
\*Scene BEACH_HOUSE_INSIDE_NIGHT
{% endhint %}  
\*Camera Right 0  
\*  
Sam(smile): I feel like I should have lit candles or something...  
Layla(happy): I don't need candles.  
# (sld_09_04_DP1_lit_candles)  
## A. I just need you.  
## B. Besides, they're a fire hazard.  
#### A  
\>>  
Sam(surprise): ...  
Narrator: You head up the stairs but Sam tugs your hand, pulling you back into his arms.  
Sam(smile): I can't believe this is really happening.  
Layla(smile): We'll never make it upstairs at this rate...  
\>  
Narrator: With a soft kiss to the top of your head, Sam lets go so you can walk.  
#### B  
Sam(happy): Where's your sense of romance?  
Narrator: You stick your tongue out at him.  
\***  
\*Stop Music  
\*Play Music m_romance_sexy_flirt_sleeplessness  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_city_mediterranean_style_bedroom_night.jpg-story' width='60'>
\*Scene SAM_BEDROOM_NIGHT
{% endhint %}  
\*Gain KISSED_SAM  
\*Gain SAM_ROMANCE  
Narrator: Sam leads you to his bedroom. Moonlight streams through the windows.  
Layla(shy)*Think: My heart is pounding... Is this really happening?  
Sam(shy): Every time I see you, I want to kiss you.  
Layla(smile): Sam...  
# (sld_09_04_DP2_sam_sweet)  
## A. You're so sweet.  
## B. Even in the morning when my hair's a mess?  
#### B  
\>>  
Sam(happy): <i>Especially</i> in the morning when your hair's a mess.  
Layla(shy): Oh...  
\>>>  
Sam(smile): And when you blush like that... And when you tease me...  
\>>  
Layla(shy): I'm not blushing.  
Sam(happy): I want to kiss you every time you do something that makes me love you.  
Sam(shy): Which is... all of the time.  
Layla(shy): Sam... You're so sweet...  
\>  
\***  
Sam: I'm not always sweet.  
Narrator: He walks you to the edge of his bed until you sit down and look up at him.  
\>>  
Sam(smile): Like I really want to push you back onto this bed...  
Narrator: He kisses your temple, then speaks low and soft.  
\>>>  
Sam(smile): And feel your bare skin against mine...  
Layla(surprise)*Think: Oh my god! Sam... Wow...  
Layla*Think: I should...  
# (sld_09_04_DP3_bare_skin)  
## A. Kiss him.  
## B. Pull him on top of me.  
#### A  
Narrator: You tilt your face up, and Sam meets you halfway, kissing you softly.  
Layla(smile): Sam...  
Narrator: He deepens the kiss, pressing forward, guiding you to lie back on the bed.  
#### B  
Narrator: You grab Sam's shirt and pull him down on top of you.  
\>>>  
Sam(surprise): Woah!  
Layla(smile): I couldn't resist.  
\***  
Narrator: You look up at him, feel the strength in his arms as he leans over you.  
\>>  
Sam(smile): {Layla Name}...  
Narrator: He kisses you passionately. His lips trail over your jaw and to your neck.  
Layla(surprise): Sam...  
Narrator: Your bodies tangle together, wrapped up in each other.  
Narrator: You slip your hands under his shirt and slide them up over his chest.  
Sam(surprise): {Layla Name}...  
Narrator: He holds you close, kissing your neck as your hands roam over his back.  
\>>>  
Sam(smile): You know you can just take it off...  
Layla(happy): I was getting there...  
\>  
Narrator: You tug on the fabric and pull it up over his head.  
\*Sam Outfit Sam_Shirtless  
Sam(smile): God... You have no idea how badly I want you.  
Narrator: You lift your hips up, pressing them close to his.  
\>>  
Layla(smile): I think I have some idea.  
Sam(smile): Ha. I just want to make sure you want this as much as I do.  
\>  
Layla(smile): Sam...  
# (sld_09_04_DP4_next_move)  
## A. I definitely want you.  
## B. I'd rather stop now.  
#### A  
\*Stop Music  
\*Play Music m_romance_sexy_love_late_nights_03  
\>>  
Sam(happy): Mmm... {Layla Name}.  
Narrator: He fumbles with your clothes as he kisses your bare shoulders.  
\*Layla Outfit Underwear (Tag: Record)  
Layla(shy): Sam...  
Sam(happy): I can't get enough of you.  
Narrator: He trails kisses down your throat and lower, exploring your body...  
Layla(surprise): Oh...  
Narrator: His touch makes your heart pound harder as you tangle together on the bed.  
Sam: I've got you, {Layla Name}.  
Narrator: Your bodies move together. You can't help moaning as he presses closer.  
\*Stop Music  
\>>>  
\*Play Sound heartbeat1  
Layla(surprise): {*Attention Sam... Sam... I--}  
\*Play Music m_romance_sexy_love_late_nights_03  
Narrator: You cry out, clinging to Sam as he groans against your shoulder.  
Sam(surprise): {Layla Name}...  
\>  
Narrator: Panting hard, the two of you hold each other, snuggling close, trying to catch your breath.  
#### B  
Sam(smile): Fair enough.  
Narrator: He shifts to lay beside you, and you rest your head on his chest.  
\***  
Narrator: He rubs your back and plays with your hair as you nestle close to him.  
\>>  
Sam(smile): You're so beautiful...  
Sam(smile): I wish we could stay like this forever.  
Narrator: You think about tomorrow night, shifting into a mermaid and leaving Sam again...  
Layla(sad): I wish we could, too...  
\>  
Narrator: You rest in Sam's arms, easily falling asleep to the sound of his heartbeat.  
\*Layla Outfit Reset  
\*Sam Outfit Sam_Casual  
# merm09_visit_grandma  
\*Stop Music  
\*Play Music m_gently_melancholy_deck_the_halls_01  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_3_city_town_center_day.jpg-story' width='60'>
\*Scene TOWN_CENTER_DAY (Color: Black Time: 5)
{% endhint %}  
Narrator: The next day, you and your grandma take a walk through town.  
\*Camera Left 3  
Grandma(sad): How are you handling everything?  
Layla(sad): It's a lot to take in...  
# (sld_09_05_handle_everything)  
## A. But I think I'm doing okay.  
## B. And I hate lying to everyone.  
#### A  
Layla(smile): I'm glad I know the truth about my mother, and about who I am.  
Layla: Even if it's not the easiest truth.  
#### B  
Layla(angry): I don't like lying to Sam, or Maddie... I hate it!  
Layla(sad): And it hurts to know that if I told them the truth, they wouldn't believe me.  
Grandma(sad): I know those feelings all too well.  
\***  
Narrator: The two of you walk over to a picnic table and sit down together.  
Grandma: There is something I wanted to give you.  
Narrator: She pulls out a box, simple and beautiful, and places it on the table between you.  
\>>  
Layla(surprise): What's this?  
Grandma(smile): It belonged to your mother, a sort of keepsake box.  
Grandma(smile): It was supposed to be a jewelry box.  
\>  
Narrator: You slide the box toward you and run your hands along the top.  
\*Item  
# (sld_09_06_show_box)  
## A. Memory_Box_Lock Take it.  
\***  
\>>  
Layla(smile): This was my mother's?  
Grandma(happy): Don't get too excited. It isn't much.  
Layla(happy): It's everything. Thank you!  
Grandma(smile): There is one other thing... A small piece of magic I could teach you.  
Grandma: The ability to detect memory imprints on an object.  
\>  
Layla(surprise): Memory imprints?  
# (sld_09_07_memory_imprints_spell)  
## A. What does that mean?  
## B. I think I've seen that on TV.  
#### B  
Grandma(happy): Well, this will be far less flashy than TV makes it out to be.  
\***  
Grandma: If someone has strong emotions surrounding an object, it leaves an impression.  
Grandma: A traumatic or powerful event could also leave an impression.  
Layla(surprise): And I'll be able to see those events?  
Grandma(smile): Not always 'see', but I can teach you to sense them.  
Grandma: You can practice on your mother's memory box and use the ability anywhere.  
Layla(surprise)*Think: This sounds useful... And I'll learn more about Mom.  
Layla(surprise)*Think: Do I want to learn to read an object's history?  
# (sld_09_08_learn_magic)  
## A. Yes, teach me! (Cost: 20 Diamond ID: magic_sld_09_sense) *Goto merm09_prem_learn_sense_objects  
## B. I don't think I need that.  
#### B  
Grandma: Alright. The memory box is yours regardless.  
### \*Goto merm09_searching_memory_box  
\***  
# merm09_prem_learn_sense_objects  
\*Stop Music  
\*Play Music m_gently_melancholy_sadness_fortress_europe_01  
\*Gain MAGIC_SENSE_OBJECTS  
\*Condition  
## A. (Condition: MAGIC_SHIELD = 1)  
#### A  
Layla(surprise): I learned one spell already as a mermaid. A shield spell.  
Grandma: I don't know mermaid magic, but the principals should be the same.  
\***  
Narrator: Your grandma reaches into her purse and removes a lumpy clay object.  
Layla: What the heck is that thing?  
Grandma(smile): Practice. Hold it in your hand and quiet your mind.  
Grandma(smile): Imagine yourself reaching out, asking a question, being open.  
Grandma(happy): This spell is about listening and receiving what might be there.  
Grandma(smile): Unlike a lot of spells which focus and force your will.  
Layla: Got it.  
Narrator: You close your eyes, feeling the strange shape of the object against your palm.  
\>>  
Layla*Think: I want to portray...  
# (sld_09_08_DP1_portray)  
## A. An outstretched hand.  
## B. A friend ready to listen.  
## C. An interview.  
#### A  
Narrator: You picture yourself extending a hand, ready to receive.  
#### B  
Narrator: You give the impression of an old friend getting coffee to catch up.  
#### C  
Narrator: You imagine yourself as an interviewer with pencil and paper, ready to take notes.  
\***  
Grandma: Keep your mind open and clear, ready to hear what the memory has to say.  
\>  
\*Stop Music  
\*Play Music m_mystery_tension_heartbeat_01  
Narrator: You listen hard, waiting...  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_city_magic_sense_objects.jpg-story' width='60'>
\*Scene BG_MAGIC_SENSE_OBJECTS
{% endhint %}  
\*+MAGIC_DREAM  
Narrator: <i>Small hands. Messy clay and paint. A warm glow of pride.</i>  
Edith(cry): Mom... I don't think I can do this... How can I raise a kid?!  
Narrator: <i>Home from school. Tiny feet run across the floor.</i>  
Narrator*Top: VOICE | <i>Look! Look !</i>  
Edith(sad): Not now, {Layla Name}, I... Oh?  
\>>  
Edith: That's a lovely... thing you made... What is it?  
Narrator*Top: VOICE | <i>A heart! For you! I love you!</i>  
Edith(surprise): ...!  
Edith(cry): Oh, {Layla Name}, sweetie...  
Narrator: <i>Warm hug. Hot tears. We're going to be okay.</i>  
\>  
\*  
\*Stop Music  
\*Play Music m_gently_melancholy_sadness_fortress_europe_01  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_3_city_town_center_day.jpg-story' width='60'>
\*Scene TOWN_CENTER_DAY
{% endhint %}  
\*Camera Left 0  
\>>  
\*  
Layla(surprise): ...Woah.  
Grandma(smile): What did it show you?  
Layla(surprise): I think I saw...  
# (sld_09_08_DP2_the_image)  
## A. Me as a toddler.  
## B. You after your mom died.  
\***  
Grandma: Yes. You were maybe three years old?  
Grandma(happy): It was Mother's Day.  
Grandma: I was having a rough time. I didn't know how to raise a child.  
Grandma(sad): And it was especially difficult after my mother passed away.  
Grandma(happy): Then you came running up to me with this craft you'd made at school.  
Narrator: She takes it from you, looking at it fondly.  
Grandma(smile): It's a heart. You gave it to me and said you loved me.  
Layla(happy): Awww!  
Grandma(smile): It just hit me at that moment that everything was going to be okay.  
Narrator: She nudges the box closer to you.  
Grandma(smile): Go on. Have a look.  
\>  
### \*Goto merm09_searching_memory_box  
# merm09_searching_memory_box  
\*Stop Music  
\*Play Music m_sprightly_fairy_meeting_long  
Layla(smile)*Think: Which item should I look at?  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_city_memory_box.jpg-story' width='60'>
\*Scene MEMORY_BOX
{% endhint %}  
\*Searching  
# (sld_09_09_SP_open_box)  
## A. FLOWERS (Condition: FLOWERS < 1) *Goto merm09_searching_flowers  
## B. PEARLS (Condition: PEARLS < 1) *Goto merm09_searching_pearls  
## C. PAPERS (Condition: PAPERS < 1) *Goto merm09_searching_papers  
## D. SEASHELL (Condition: SEASHELL < 1) *Goto merm09_searching_shell  
\***  
# merm09_searching_flowers  
\*Stop Music  
\*Play Music m_tension_rage_mystery_forest_fear_01  
\*FLOWERS Completed  
\*MOM_BOX +1  
Narrator: You touch the dried wildflowers.  
\*Item  
# (sld_09_10_A_dried_flowers)  
## A. Dried_Flowers Touch it.  
\***  
Narrator: They're so brittle you fear they'll crumble to dust.  
\*  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_3_city_town_center_day.jpg-story' width='60'>
\*Scene TOWN_CENTER_DAY (Color: White)
{% endhint %}  
\*Camera Left 0  
\>>  
\*  
Grandma(smile): Your mother was fascinated by the plants and animals on land.  
Grandma(happy): We took her to the zoo and she was happier than half the kids there.  
Layla(happy): That's adorable.  
\*Condition  
## A. (Condition: MAGIC_SENSE_OBJECTS >= 1)  
#### A  
Grandma(smile): Go ahead and try to listen to these memories.  
Narrator: You focus, clearing your mind and listening...  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_city_seaside_clifftop_sunset.jpg-story' width='60'>
\*Scene CLIFFTOP (Color: White)
{% endhint %}  
\*Skyla Outfit Skyla_Human  
Skyla(sad): ...  
Narrator: <i>Soft petals. So many colors. Beautiful and strong.</i>  
Skyla(sad)*Think: This might be the last time I see these flowers.  
\*  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_3_city_town_center_day.jpg-story' width='60'>
\*Scene TOWN_CENTER_DAY (Color: White)
{% endhint %}  
\*Camera Left 0  
\>>  
\*  
Grandma(sad): Are you crying?  
Narrator: You touch a hand to your cheek and find a tear there.  
Layla(surprise): These aren't my tears... They were my mother's.  
Grandma(sad): I'm sorry, {Layla Name}. I hoped this box would have happy memories.  
Layla: No, it's alright. I want to know everything, even if it's sad.  
\***  
### \*Goto merm09_searching_memory_box (Condition: MOM_BOX < 4)  
### \*Goto merm09_goodbye_grandma (Condition: MOM_BOX >= 4)  
# merm09_searching_pearls  
\*Stop Music  
\*Play Music m_melancholy_gently_present_standard_01  
\*PEARLS Completed  
\*MOM_BOX +1  
\*  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_3_city_town_center_day.jpg-story' width='60'>
\*Scene TOWN_CENTER_DAY (Color: White)
{% endhint %}  
\*Camera Left 0  
\>>  
\*  
Layla(surprise): Do you know why this was broken?  
Grandma: Hmm. It might have fallen apart with time. I don't recognize it...  
Grandma: Your mother didn't wear much jewelry. She loved nature and simple things.  
\*Item  
# (sld_09_10_B_pearl_bracelet)  
## A. Pearl_Bracelet_Broken Touch it.  
\***  
Layla*Think: There's got to be a story behind this.  
\*Condition  
## A. (Condition: MAGIC_SENSE_OBJECTS >= 1)  
#### A  
Narrator: You clear your mind, listening for the pearls' secrets...  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_city_magic_sense_objects.jpg-story' width='60'>
\*Scene BG_MAGIC_SENSE_OBJECTS
{% endhint %}  
\*+MAGIC_DREAM  
Skyla: Carry my heart on the tides. Hear me and grant my wish.  
Narrator: <i>Skyla rips the bracelet's cord. Pearls rain into the box.</i>  
Narrator: <i>A hope. A prayer. A message. She presses the pearl to her lips.</i>  
Skyla(smile): Help my daughter be happy.  
Narrator: <i>She holds the pearl against the waves and lets it wash out to sea.</i>  
Skyla(smile): Let her find love.  
Narrator: <i>Another whispered prayer. Another pearl into the ocean.</i>  
Skyla(sad): ...Keep her safe.  
\*  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_3_city_town_center_day.jpg-story' width='60'>
\*Scene TOWN_CENTER_DAY
{% endhint %}  
\*Camera Left 0  
\>>  
\*  
Layla(surprise): They were... magic? She was asking the sea for blessings.  
Grandma(surprise): Skyla was powerful. If she asked, the sea would answer her.  
Layla(smile)*Think: And all she wanted was for me to be okay.  
\***  
### \*Goto merm09_searching_memory_box (Condition: MOM_BOX < 4)  
### \*Goto merm09_goodbye_grandma (Condition: MOM_BOX >= 4)  
# merm09_searching_papers  
\*Stop Music  
\*Play Music m_gently_lifting_dreams_01  
\*PAPERS Completed  
\*MOM_BOX +1  
\*Item  
# (sld_09_10_C_letter_papers)  
## A. Letter_Paper Touch it.  
\***  
Narrator: You glance through the stack of papers but...  
\*  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_3_city_town_center_day.jpg-story' width='60'>
\*Scene TOWN_CENTER_DAY (Color: White)
{% endhint %}  
\*Camera Left 0  
\>>  
\*  
Layla(sad): These aren't in English. They aren't in any language I've seen...  
Grandma: Yes... I assumed it was the mer language.  
Layla: All the mer I've met just speak English.  
Narrator: The two of you stare at the symbols, trying to make sense of them.  
Grandma: I think these are written by different people. The handwriting...  
Layla(surprise): Did she know anyone else on land?  
Grandma: Not that I know of.  
\*Condition  
## A. (Condition: MAGIC_SENSE_OBJECTS >= 1)  
## B. (Condition: MAGIC_SENSE_OBJECTS < 1)  
#### A  
Layla(smile): There's one way to find out.  
Narrator: You run your fingertips over the letters, listening with your heart and mind...  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_city_magic_sense_objects.jpg-story' width='60'>
\*Scene BG_MAGIC_SENSE_OBJECTS
{% endhint %}  
\*+MAGIC_DREAM  
Narrator*Top: ??? | <i>...you must accept his proposal. You're the only one who can...</i>  
Narrator*Top: Skyla | <i>...listens to you. I'm so afraid, Alunis. He's dangerous. I'm not...</i>  
Layla(angry)*Think: All I can get are fragments... I have to focus...  
Narrator*Top: Skyla | <i>...pregnant. This changes everything for me. My child is too important to...</i>  
Narrator*Top: ??? | <i>...find a way to keep you both safe.</i>  
Layla(angry)*Think: Focus... Harder...  
\*  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_3_city_town_center_day.jpg-story' width='60'>
\*Scene TOWN_CENTER_DAY
{% endhint %}  
\*Camera Left 0  
\>>  
\*  
Layla(surprise): What happened?!  
Grandma: You tried too hard to force things. This magic doesn't work that way.  
Grandma: You can only take what the memory is willing to give.  
Layla(sad): Damn. There's got to be some way to read these. Hmmm...  
#### B  
Layla(sad): Hmmm...  
\***  
Layla*Think: If it's a mer language, maybe someone can read them.  
Layla(sad)*Think: I wish I could bring these underwater with me.  
### \*Goto merm09_searching_memory_box (Condition: MOM_BOX < 4)  
### \*Goto merm09_goodbye_grandma (Condition: MOM_BOX >= 4)  
# merm09_searching_shell  
\*Stop Music  
\*Play Music m_gently_snug_romance_dancing_star_01  
\*SEASHELL Completed  
\*MOM_BOX +1  
Narrator: You lift the shell in your hands.  
\*Item  
# (sld_09_10_D_seashell_legend)  
## A. Seashell_Legend Touch it.  
\***  
Narrator: Etched into the opalescent surface are words.  
Narrator: The Shell | <i>Skyla Beliril and Leden Avos</i>  
Narrator: The Shell | <i>May the home we build together last for eternity.</i>  
\*  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_3_city_town_center_day.jpg-story' width='60'>
\*Scene TOWN_CENTER_DAY (Color: White)
{% endhint %}  
\*Camera Left 0  
\>>  
\*  
Layla(surprise): Leden Avos... Is that... my father?  
Grandma: It is. That was given to your mother at her engagement ceremony.  
Grandma: Each of them receives one half of the same shell.  
Layla: That's kind of romantic.  
# (sld_09_11_CP_the_same_shell)  
## A. But they didn't love each other.  
## B. But my father was horrible.  
#### A  
Grandma(sad): Skyla hoped for love. Many arranged couples fall in love over time.  
#### B  
Narrator: Your grandma puts her hand over yours, patting it gently.  
Grandma(sad): No one chooses their parents, {Layla Name}.  
Grandma(sad): At least you had a mother who loved you dearly.  
\***  
\*Condition  
## A. (Condition: MAGIC_SENSE_OBJECTS >= 1)  
#### A  
Narrator: You cradle the shell in your hands and wait, listening to its secrets.  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_city_magic_sense_objects.jpg-story' width='60'>
\*Scene BG_MAGIC_SENSE_OBJECTS
{% endhint %}  
\*+MAGIC_DREAM  
Narrator: <i>A man's large hands holding both halves of the shell.</i>  
Narrator: <i>Longing. Hope. Loneliness. Guilt. A heavy burden.</i>  
Layla(surprise)*Think: Are these my father's feelings?  
Narrator*Top: Man's Voice | Is the inscription alright? Will she like it?  
Layla(surprise)*Think: He sounds nervous... and so young.  
Layla(sad)*Think: Let me see his face...  
Narrator: For a moment, you almost see a shadowy form... But then...  
\*  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_3_city_town_center_day.jpg-story' width='60'>
\*Scene TOWN_CENTER_DAY
{% endhint %}  
\*Camera Left 0  
\>>  
\*  
Layla(angry): Damnit!  
Layla(sad): I lost it.  
Grandma(smile): It's a frustrating magic. It only shows what it wants you to see.  
Narrator: You sigh and put the shell back down.  
\***  
### \*Goto merm09_searching_memory_box (Condition: MOM_BOX < 4)  
### \*Goto merm09_goodbye_grandma (Condition: MOM_BOX >= 4)  
# merm09_goodbye_grandma  
\*Stop Music  
\*Play Music m_blue_mystery_decline_02  
Narrator: You replace the items and close the box's lid.  
Grandma: How are you feeling?  
Layla: Well...  
# (sld_09_12_feeling)  
## A. I still have so many questions.  
## B. I feel closer to her.  
## C. I miss Mom.  
#### A  
Layla(sad): I never really get any answers... Just more questions.  
Layla: I wish I could read the letters, or know more about my father.  
Grandma(sad): I wish I could help you. I never knew much about him either.  
#### B  
Layla(smile): Touching the things she thought were precious...  
Layla(happy): It make her feel more real somehow. Thank you for showing me this.  
#### C  
Layla(sad): Is it possible to miss someone you never even met?  
Grandma(smile): She's your mother. Of course it's possible.  
Grandma: If you ever need to talk about it... Know that you're never alone.  
Layla(smile): Of course, Grandma.  
\***  
\>  
Narrator: You slide the box across the table to her.  
Layla: Can you keep this safe for me?  
Grandma: Of course... You're going back to the ocean, aren't you?  
Grandma(sad): When do you go back, dear?  
Layla(sad): ...Tonight. Before sunset.  
Grandma(surprise): Then I'm glad I came when I did! I nearly missed you.  
Narrator: She heaves a sigh, worry weighing on her shoulders.  
Grandma(sad): I hoped to keep you safe from all of this.  
Grandma(sad): The mer world is beautiful but it is also dangerous.  
Layla(sad): I know.  
# (sld_09_13_the_mer_world)  
## A. The human world is the same.  
## B. I wish I didn't have to go.  
#### A  
Grandma(smile): I suppose that's part of raising children...  
Grandma(smile): You can't protect them forever.  
#### B  
Grandma(sad): Just take it one day at a time, {Layla Name}.  
Grandma: We'll find a way to make this work.  
\***  
\>>  
Layla(sad): Grandma... Do you think there's any way you can do the spell again?  
Layla(sad): Put me back to the way I was so I can go back to my human life.  
Grandma(sad): I wish I could... But I don't have nearly that much power.  
Grandma(sad): Even back then, I couldn't have done it alone. And now...  
Layla(sad): I understand...  
Layla*Think: Everyone keeps saying I have strong magical power...  
Layla*Think: Maybe I can find a way to change myself back.  
\*Camera Middle 2  
Narrator: The two of you talk for a while longer, then say your goodbyes.  
\*Stop Music  
\*Play Music m_romance_beauty_love  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_3_city_beach_house_day.jpg-story' width='60'>
\*Scene OUTSIDE_BEACH_HOUSE_DAY (Color: Black Time: 5)
{% endhint %}  
Narrator: It's late in the afternoon and the sun will be going down soon.  
Layla(sad)*Think: It's time to say goodbye.  
Sam(smile): You have everything packed and ready to go?  
Layla(surprise): Oh, uh... Yeah. My grandma took care of it.  
\>>  
Sam(sad): I'll miss you, {Layla Name}.  
Layla(sad): Sam...  
# (sld_09_14_goodbye_sam)  
## A. I'll miss you, too.  
## B. Try not to have too much fun without me.  
#### A  
Narrator: A wistful expression crosses Sam's face as he gazes at you.  
Sam(smile): I'll call you everyday.  
#### B  
Sam(smile): If we do have fun, I'll text you loads of pictures.  
\***  
\>  
Layla(surprise): That's not necessary! I won't really have my phone with me...  
Layla(sad): Me and Grandma need some time alone.  
Sam(surprise): Oh! Yeah, alright. That makes sense.  
\*Condition  
## A. (Condition: SAM_ROMANCE >= 1)  
## B. (Condition: SAM_ROMANCE < 1)  
#### A  
Narrator: Sam hugs you close, kissing the top of your head.  
\>>  
Sam(smile): I finally get to do things like that... and you're leaving.  
Layla(smile): I'm sorry! You can do plenty of that when I return.  
#### B  
Narrator: Sam gives you a warm hug.  
Sam(smile): Have a good trip.  
\***  
\*Camera Right 3  
Narrator: You pretend to walk to the road, conscious of Sam's eyes on you.  
Layla(sad)*Think: ...This is so awkward... I hate lying like this.  
Narrator: You hear the door to the house open and shut and check...  
Layla(sad): Phew. He finally went inside.  
Narrator: You hurry and make your way to the beach to meet Zale.  
\*Camera Left 4  
\*Stop Music  
\*Play Music m_sadness_ambient_namaste03  
\*Zale Face Zale_Shirtless  
Narrator: Zale beckons to you from the shallow water.  
\>>  
Zale(smile): Hey. Took you long enough.  
Layla(shy): Sorry... Sneaking out was harder than I thought it'd be.  
Narrator: Zale smiles up at you from the water, a hand extended, ready to pull you back into the world of mer beneath the sea.  
Narrator: You hesitate.  
Layla(sad): Do you know... when I'll be able to come back here?  
Zale(sad): I'm not sure... Could be a few days, if we rush to the sea witch and back, but...  
Layla(sad): Longer, if we're going to try and learn what's happening.  
Narrator: You turn to look back at the beach house, some of the lights still on in the rooms where your friends are still awake.  
Layla(sad): Zale...  
# (sld_09_14_walk_with_zale)  
## A. Could we spend some time on land together? (Cost: 18 Diamond ID: plot_sld_09_zale) *Goto prem_zale_land_goodbye  
## B. Okay... I'm ready to go.  
#### B  
Narrator: You take a deep breath, and mentally say goodbye to your life on land.  
Layla(sad)*Think: I'll be back soon... I promise...  
### \*Goto merm09_transformation_confrontation  
\***  
# prem_zale_land_goodbye  
\*Play Music m_gently_romance_heavenly  
Zale(sad): Of course, {Layla Name}. There isn't a lot of time left, but--  
Layla(sad): Just a few moments... That's all I need.  
Narrator: Zale swims to a rock rising above the shallow water and sits on it, his tail still mostly hidden in the swelling tides.  
Narrator: You slip off your shoes and join him, splashing through the water until you can sit beside him.  
Layla(sad): Thank you. This whole... 'Living two lives' thing...  
# (sld_09_14_DP1_living_two_lives)  
## A. It's a lot harder than I thought.  
## B. Can be a little exciting, even if it's exhausting.  
#### A  
Zale(sad): Yeah... I think I told you that I work with a lot of mer who spend time on land.  
Layla: You mentioned it a little...  
Zale(sad): All of them struggle with this. You're not the only one.  
Narrator: He puts a friendly hand on your shoulder and gives it a light squeeze.  
#### B  
Zale(smile): Exciting, huh?  
Layla(smile): Well... I feel like I'm some kind of secret spy sometimes. I have this whole double life...  
Layla(sad): Lying to everyone wears me out, though. I'm not cut out for this sort of thing.  
Narrator: Zale gives you a sad smile, and pats your shoulder with friendly affection.  
\***  
Layla*Think: I should...  
# (sld_09_14_DP2_zale_comfort)  
## A. Lean my head on Zale's shoulder.  
## B. Share about my life on land.  
#### A  
\*Gain LAND_GOODBYE_ZALE_CUDDLE  
Narrator: You rest your head on Zale's shoulder, and he shifts to put his arm around you, holding you close.  
\*Zale FLIRT +1  
Zale(smile): ...  
Narrator: He rests his head on yours and you both stare back at the beach, watching the palm trees wave their leaves in the evening breeze.  
\***  
Zale: I'm excited for you to see more of the ocean, learn more about what it means to be mer...  
Zale(sad): I sometimes forget how much of your life really belongs on land.  
Layla(smile): Oh, you know... Just my friends, my family, my school... My whole life...  
Layla(smile): What's funny... When I was a little kid, I wanted to be a mermaid.  
Zale(smile): Cause of the movie?  
Layla(happy): Of course! I would wrap a blanket around my legs, pretending it was a tail.  
Layla(smile): Guess I got my wish, huh.  
Zale: {Layla Name}... You were always a mermaid. The whole time.  
Layla(smile): Yeah, but it doesn't feel like it. This all feels like... still very not real.  
Narrator: You listen to the sound of the waves as they swell against the beach, thinking about the world you're leaving and the one you're going back to.  
Layla*Think: I want to...  
# (sld_09_14_DP3_thanks_zale)  
## A. Kiss him.  
## B. Keep things friendly.  
#### A  
Narrator: You turn to see Zale staring at you in the moonlight, smiling softly. You tilt your face up and he kisses you softly.  
\*Zale FLIRT +1  
Zale(smile): {Layla Name}...  
Narrator: He slides a hand into your hair and kisses you again, his thumb at your jaw so he can tip your face back, deepening the kiss.  
Narrator: Zale holds you close, the two of you lost in each other's touch.  
Zale(smile): For what it's worth...  
Zale(smile): That seemed very real to me.  
Layla(shy): Yeah... It did...  
Narrator: He grins at you, then sighs a little sadly.  
#### B  
Layla(smile): Thank you for listening, Zale.  
Zale(smile): Anytime.  
Narrator: Zale's expression dims.  
\***  
Zale: I don't want to rush you, but...  
Layla: I know... It's time.  
Narrator: Zale takes your hand, kindly hurrying you along.  
### \*Goto merm09_transformation_confrontation  
# merm09_transformation_confrontation  
Zale: You don't have much time left. Step into the water.  
\*Play Music m_intense_tension_assembling_01  
Narrator: You hurry, splashing into the ocean until it's almost to your waist.  
Layla(surprise): So how does this work? What's going to happen?  
Zale: When the spell wears off, you'll transform back naturally.  
Zale(smile): Don't worry... It shouldn't be as exciting as it was last time.  
Layla(smile): Exciting is certainly one word for it...  
Narrator*Top: Sam | ...{Layla Name}?  
\>>>  
Layla(surprise): Oh no...  
\>  
Narrator: You turn and see Sam on the beach glancing from you to Zale then back again.  
Sam(sad): I thought you were going home...  
Sam(angry): What is going on?!  
Layla(surprise): Sam...  
# (sld_09_15_explain)  
## A. I can explain!  
## B. I <i>am</i> going home.  
#### A  
Sam(angry): You've been <i>explaining</i> things for days.  
Sam(angry): Was all of it a lie?  
#### B  
Sam(sad): Didn't realize that meant skinny-dipping with some guy.  
Layla(angry): That's not what's happening. And he's not <i>some guy.</i>  
\***  
\>>  
Layla(sad): You don't understand, I--  
Layla(surprise): {*Attention <i>Aah!</i>}  
\>  
\*Play Sound transformation  
\*+MAGIC_ANIMATION_QUICK  
Narrator: A flash of light envelops you. You can feel your body changing...  
\*Condition  
## A. (Condition: Layla Face = Face_1)  
## B. (Condition: Layla Face = Face_2)  
## C. (Condition: Layla Face = Face_3)  
#### A  
\*Layla Face Face_White_Merm  
#### B  
\*Layla Face Face_Black_Merm  
#### C  
\*Layla Face Face_Asian_Merm  
\***  
\*Condition  
## A. (Condition: PRECIOUS_PEARL >= 1)  
## B. (Condition: PRECIOUS_PEARL < 1)  
#### A  
\*Layla Outfit Prem_Precious_Pearl  
#### B  
\*Layla Outfit Free_Merm  
\***  
Layla(sad): Damnit.  
\>>>  
Sam(surprise): {Layla Name}...?! What... What is going on?  
\>>  
Zale(sad): He saw everything. You might as well tell him.  
Layla(sad): Sam... I'm a mermaid.  
# End  
