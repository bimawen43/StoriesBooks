# Begin  
\*Play Music m_sadness_ambient_namaste02  
\*  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_city_beach_house_inside.jpg-story' width='60'>
\*Scene BEACH_HOUSE_INSIDE_DAY
{% endhint %}  
\*Camera Right 0  
\*  
Narrator: You come home after an emotional day arguing with your friends to find...  
Grandma(sad): We need to talk.  
\>>  
Layla(surprise): Grandma?!  
Layla(surprise)*Think: ...Oh my god, I never called her.  
\*Condition  
## A. (Condition: DID_SAM_PREM_AFTER_FIGHT >= 1)  
## B. (Condition: DID_SAM_PREM_AFTER_FIGHT = 0)  
#### A  
\>  
Sam(sad): I'll leave you two alone...  
\*Play Sound s_close_door_02  
Narrator: He ducks around you and heads upstairs. A moment later, a door shuts softly behind him.  
#### B  
\>  
\*Play Sound s_close_door_02  
Narrator: You hear a door shut somewhere in the house and realize your friends are making themselves scarce.  
\***  
\>>  
Grandma(angry): Sit.  
Narrator: You sit, feeling like a little kid about to get scolded.  
Layla(sad): Grandma...  
# (sld_08_01_grandma_appear)  
## A. I'm sorry I didn't call.  
## B. You must have been so worried.  
\***  
Grandma(sad): Oh, {Layla Name}...  
Narrator: With a heavy sigh, her anger fades, replaced by sad weariness.  
\>>>  
Grandma(sad): Nearly twenty years trying to protect you from your fate...  
Grandma(sad): And you jump right into it with both feet.  
Layla(surprise): My fate?  
Grandma(angry): Don't play dumb with me, girl. You're a terrible liar.  
\>>  
Narrator: She puts a hand over her eyes and sighs again, then lowers her voice so only you can hear.  
Grandma: I'm talking about you being a mermaid.  
Layla(surprise): Oh my god...  
# (sld_08_02_terrible_liar)  
## A. You knew?!  
## B. Are you a mermaid too?  
#### A  
Grandma(sad): Yes... I knew. I helped forge the spell that kept you safe.  
#### B  
Grandma(smile): Yes. I'm only a half-mermaid,and have lived most of my life on land.  
\***  
\>>>  
Layla(sad): Grandma, I --  
Grandma(sad): First... You need to know... I'm not biologically your grandmother.  
Layla(surprise): {*Joyful ...Oh.}  
\>>  
Narrator: She takes your hands in hers and squeezes them gently.  
Grandma(sad): Your mother was my half-sister.  
Grandma(sad): I'd understand if you wanted to call me Edith instead of 'Grandma'...  
Layla(surprise): What? No... That would be too weird. I couldn't.  
Narrator: She pats your hands, expression still sad.  
Layla(surprise): Does this mean... Was my mother a mermaid?  
Grandma(smile): She was.  
Narrator: Your grandma smiles sadly as she remembers.  
\>>>  
Layla(sad): Do you have photos of her as a mermaid? I'd love to see them...  
Grandma(sad): No... We had to keep our secret safe. Evidence like that is too risky.  
Grandma: But maybe...  
Narrator: She thinks for a moment, then nods decisively.  
\>>  
Grandma: It's time I tell you the truth about your parents, {Layla Name}.  
Grandma: I might have enough power to do a spell to let you <i>see</i> the truth.  
Grandma: It will let you relive my memories and see your mother in her mermaid form.  
Layla(surprise): You can do that?  
# (sld_08_03_relive_memories)  
## A. Can we try? I want to see my mom.  
## B. Are you sure you'll be okay?  
#### A  
Grandma(smile): I thought you'd say that.  
\>  
#### B  
Grandma(happy): I'm not so old and fragile as all that. Not yet, at least.  
\>  
\***  
Grandma(smile): Come on. Let's get comfortable... This will take a while.  
### \*Goto merm08_flashback  
# merm08_flashback  
\*Stop Music  
\*Play Music m_tension_rage_mystery_forest_fear_01  
\*Camera Left 2  
Narrator: The two of you get drinks and settle in for a long evening.  
Grandma: Before I do the spell, let me explain some things...  
\>>  
Grandma: My father, your biological grandfather, was a merman.  
Grandma: He had two wives. A mer wife in the sea, and a human wife on land.  
Layla(surprise): What?  
# (sld_08_04_biological_grandfather)  
## A. He was cheating?!  
## B. Were his wives okay with that?  
\***  
\>  
Grandma(sad): It wasn't the ideal arrangement, but... He was from a noble house.  
Grandma(sad): He was expected to marry a mermaid and have heirs.  
Grandma: My mother was his true love, but he could not have a human wife...  
Grandma(sad): Such partnerships are forbidden among mer society, especially high society.  
Layla(sad): I'm getting serious Jane Austen vibes here. He was an underwater Duke?  
Grandma(smile): Something like that.  
Layla: If you're half-mermaid, then you're the daughter of his land wife.  
Grandma: And your mother was the daughter of the wife under the sea.  
Narrator: She holds out both hands between you, palm up.  
\>>  
Grandma: Take my hands and open your mind. Try to think of nothingness.  
Layla*Think: I'll imagine...  
# (sld_08_05_open_the_mind)  
## A. An empty room.  
## B. The blackness of space.  
## C. A desert.  
\***  
\>  
Narrator: You relax your shoulders, let your thoughts drift...  
\*+MAGIC_ANIMATION_QUICK  
Narrator: Until an image begins to form in your mind...  
\*+FLASHBACK_ANIMATION  
\*  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_3_city_wharf_boardwalk_pedestrian_street.jpg-story' width='60'>
\*Scene BOARDWALK (Color: White Time: 0.1)
{% endhint %}  
\*Camera Left 0  
\*  
Narrator: Tutorial | Now playing as <color=olive>Edith</color>!  
\*Stop Music  
\*Edith Player  
\*Edith Name Edith  
\*Play Music m_motherguitar  
Edith(surprise)*Think: Woah... it worked!  
\>>  
Edith(happy)*Think: Wow, look at these clothes. 90's grunge, huh?  
\>  
Narrator*Top: ??? | Edith! You made it!  
Narrator: A woman's voice calls to you from beneath the pier. She waves to you, beckoning you to join her.  
Narrator: Your feet move on their own, bringing you into the shallow, shadowy water...  
\*Skyla Face Skyla_Mermaid  
\>>  
Skyla(sad): Edith, I'm so glad you came. I wasn't sure if you would.  
Edith(surprise)*Think: Mom! Oh wow...  
# (sld_08_06_young_skyla)  
## A. (She's beautiful!)  
## B. (She's so young!)  
\***  
\>  
Narrator: You speak as Edith, kneeling down in the sand beside the mermaid.  
Edith: Skyla, I told you before. I'm mad at our dad, but not at your mom... or you.  
Skyla(sad): I'm glad... Because I need your help.  
Edith(surprise): What is it?  
Skyla(sad): A few months ago... I got married.  
Edith(sad): Why don't you seem happy about that?  
Narrator: Your mother sighs and flops onto her back in the water.  
\>>  
Skyla(sad): It was an arranged marriage. Don't make that face!  
Edith: What face?  
Skyla(sad): I can feel your judgment from here. I'm not upset about the arranged part.  
Skyla(sad): But he... I think he married me to use my magic.  
Edith(surprise)*Think: Her magic...  
# (sld_08_07_use_the_magic)  
## A. (My mother had magic, too!)  
## B. (People want to use my magic, too.)  
\***  
\>  
Edith: As opposed to marrying you for your wealth or status?  
Edith: How is that really any different?  
Narrator: Your mother waves a hand, dismissing Edith's argument.  
\>>  
Skyla(sad): It wasn't all that different... until I got pregnant.  
Edith(surprise): You're pregnant?!  
Skyla(smile): Yes... I'm not very far along yet, but...  
Skyla(sad): My husband is obsessed with this child. He has 'plans' for him.  
Skyla(sad): With his magic and mine combined, the child will be immensely powerful.  
Edith(sad): Oh no...  
Skyla(sad): I'm afraid of what he'll do once the child is born.  
\*Stop Music  
\*Play Music oceandance1  
Edith(sad)*Think: My father...  
# (sld_08_08_your_father)  
## A. (He wanted to use me.)  
## B. (He made my mother miserable.)  
\***  
Edith(sad)*Think: Grandma always told me my parents both loved me...  
Edith(sad)*Think: That my parents were in love... That we were a happy family.  
\>>>  
Edith(cry)*Think: She wanted to protect me from this truth.  
\>  
Narrator: Your vision swims as the memory blends into another.  
\*Play Sound s_magic_skill_01  
\*+MAGIC_ANIMATION_QUICK  
\*Stop Sound  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_black.jpg-story' width='60'>
\*Scene BLACK
{% endhint %}  
Narrator: Months have passed.  
\*Play Music m_rage_tension_dark  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_city_seaside_clifftop_sunset.jpg-story' width='60'>
\*Scene CLIFFTOP (Color: Black)
{% endhint %}  
Dorothea(surprise): Edith, remember to only pick the ones with the pointed leaves.  
Edith: I know, mom. I've gathered herbs before.  
Dorothea(sad): I'm sorry... I'm so worried about Skyla.  
Dorothea(sad): It's been two weeks since we've heard from her...  
Edith(sad): I know. I'm worried, too.  
Edith(sad)*Think: Two weeks?  
# (sld_08_09_leave_two_weeks)  
## A. (It's okay. I know the end of this story.)  
## B. (He'd better not hurt her!)  
#### A  
Edith(sad)*Think: I have to be born, so she has to be fine... right?  
#### B  
Edith(angry)*Think: I can't believe my mother went through so much!  
\***  
Narrator: You watch Edith's hands carefully gather herbs and bundle them together.  
Edith(sad): Do you think this spell will really work?  
Dorothea(angry): It has to. There's no other way.  
Narrator: Edith puts her arms around her mother's shoulders, squeezing her in a hug.  
\>>  
Edith(sad): You really don't think he'd hurt her, do you? Doesn't he need her?  
Dorothea(sad): He might not kill her, but these magical experiments he's doing...  
Dorothea(sad): Skyla said it's draining his life force, making him weak. It's painful.  
Dorothea(angry): And the second the baby is born, he's going to involve Skyla.  
Edith(surprise)*Think: Magical experiments?  
# (sld_08_10_magical_experiments)  
## A. (I need to learn more about this!)  
## B. (This sounds dangerous.)  
\***  
\>  
Dorothea(sad): We need to get her out of there.  
Edith(sad): She said it's getting harder and harder to sneak away... He's watching her.  
Narrator: The two women go silent, both engrossed in their own worries and fears.  
Dorothea: ...Keep gathering herbs. We need as much as we can to save her.  
\*Play Sound s_magic_skill_01  
\*+MAGIC_ANIMATION_QUICK  
\*Stop Sound  
\*Play Music m_tension_rage_mystery_forest_fear_01  
Narrator: The memories slowly fade away, replaced by the ordinary beach house.  
\*  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_city_beach_house_inside.jpg-story' width='60'>
\*Scene BEACH_HOUSE_INSIDE_DAY (Color: White Time: 0.5)
{% endhint %}  
\*Camera Left 0  
\*  
Layla(sad): What happened?  
Grandma(sad): The next image I have to show you is the night we performed the spell.  
\>>  
Grandma(sad): This story doesn't have a happy ending. I want to be sure you're ready for it.  
Layla: Grandma...  
# (sld_08_11_full_flashback)  
## A. I'm ready. Show me what happened. (Cost: 20 Diamond ID: plot_sld_08_edith) *Goto prem_merm08_full_flashback  
## B. I want to know... But spare me the details. *Goto merm08_free_grandma_convo  
\***  
# prem_merm08_full_flashback  
\>  
\*+FLASHBACK_ANIMATION  
Narrator: More months have passed. The baby has finally been born.  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_city_beach_sky_night_meteors.jpg-story' width='60'>
\*Scene OCEAN_NIGHT_METEORS (Color: White Time: 0.5)
{% endhint %}  
\*+MAGIC_CIRCLE_STDBY  
\*Gain GRANDMA_FLASHBACK  
\*Stop Music  
\*Play Sound s_seawave  
\*Play Music m_melancholy_tension_heartbeat  
\*Skyla Face Skyla_Human  
Narrator: Tonight, the three women will cast the spell.  
Dorothea(sad): She's late.  
Edith(sad): Give her time... We can wait all night if we have to.  
Dorothea(sad): What if something happened to her? What if she can't escape? What if--  
\*Play Sound s_magic_combat_01  
Narrator: You hear a commotion coming from further down the beach and see the flickering light of magic.  
\*Stop Music  
\*Play Music m_rage_crisis_final_boss_02  
Edith(surprise): What is that?  
Narrator: Edith and Dorothea run toward the sound and find Skyla battling Deep Sea Clan soldiers in the shallow water.  
\>>  
Soldier(angry): Return with us at once, Lady Beliril!  
Skyla(angry): I will not!  
\>  
\*Play Sound s_skill_shield  
\*+SHIELD_MAGIC_ANIMATION  
Narrator: Skyla puts up a magic barrier, fending off the soldier's attacks.  
Edith(surprise)*Think: Mom!  
# (sld_08_11_shield_magic)  
## A. （I know that spell!） (Condition: MAGIC_SHIELD >= 1)  
## B. （Please be okay...）  
## C. （Wait, where's the baby?）  
#### A  
Edith(smile)*Think: My mother used the same magic.  
#### B  
Edith(sad)*Think: I've been born... After this, who knows what happens...  
\***  
Narrator: A baby screams from a tangle of wet blankets on the beach.  
\>>  
Skyla(surprise): ...  
Narrator: The sound pulls Skyla's focus, making her falter.  
Soldier(angry): Got you!  
Narrator: He grabs Skyla by the arm while her shield is down and pulls her deeper into the water.  
\>>>  
Edith(surprise)*Shout: No!  
\>>  
Soldier(angry): I don't want to hurt you... Please come back peacefully!  
\>  
\*Play Sound s_skill_shield  
\*+SHIELD_MAGIC_ANIMATION  
Narrator: There's a flash of light, and suddenly the soldier is encased in a magic bubble, unable to move.  
Soldier(surprise): ...  
\>>  
Edith(surprise): Did you do that?  
Dorothea(angry): I did.  
Narrator: Dorothea holds the baby in her arms.  
Dorothea(sad): It won't stop them forever. We have to do this spell <i>now</i>.  
\>  
Skyla(sad): There were more soldiers following me, too. We must hurry!  
Narrator: The three women run to where the spell has been set up.  
Edith(sad)*Think: This is it...  
# (sld_08_11_DP2_spell_set_up)  
## A. (This is where they make me human.)  
## B. (It's time to find out the truth.)  
\***  
\*Stop Music  
\*Play Music m_rage_tension_intense_chasing_time_01  
Narrator: You watch Edith's hands as she lights candles and places bundles of herbs.  
Dorothea: Skyla, stand there. The three of us form a triangle to draw on all our powers.  
Dorothea: As the most powerful among us, you need to be the upper point.  
Skyla: Got it.  
Narrator: Skyla lays her baby down in the center of the casting.  
\>>  
Skyla(smile): Don't be frightened, little one. I'll be right here watching you.  
Edith(sad)*Think: Mom...  
Narrator: She kisses the baby's forehead, then takes her place at the head of the triangle.  
\>  
Dorothea: Let us begin.  
Narrator: The three women dip their herb bundles into the candle flames one by one. Their bodies begin to glow.  
\*+MAGIC_CIRCLE_START  
Narrator: As sweet smoke fills the air, the haze makes the glow seem like a halo around each of the women.  
\*-MAGIC_CIRCLE_START  
\*+MAGIC_CIRCLE_STDBY  
Edith(surprise)*Think: Wow...  
# (sld_08_11_DP3_casting)  
## A. (This is nothing like the sea witch's magic.)  
## B. (They're real witches!)  
#### A  
Edith(surprise)*Think: I know she said land witches were different, but wow!  
#### B  
Edith(surprise)*Think: This is so cool... Who knew grandma had this kind of power?!  
\***  
Dorothea(surprise): With the power of the land and sea, we bind this child to her human form.  
Narrator: A tension builds in the air, magic crackling as the breeze stirs their hair into a frenzy.  
Dorothea(surprise): She has forsaken her ocean home. Ground her to the earth, to the--  
\>>  
Skyla(surprise): Aahh!  
\*Stop Music  
\*Play Music m_rage_crisis_final_boss_01  
Narrator: One of the soldiers has snuck up on Skyla and placed a knife to her throat.  
\>>  
Soldier(angry): Nobody move. She's going home. You can't stop us.  
\>>>  
Dorothea(surprise): No! Release her! She can't leave the circle!  
\>  
Narrator: The soldier doesn't listen. He pulls Skyla backward, dragging her away.  
Edith(surprise): Aahh!  
Narrator: The tension <i>snaps</i> like a rubber band, the magic breaking from Skyla and slamming into Edith and Dorothea instead.  
\>>  
Edith(surprise): We have to save her!  
Dorothea(angry): Don't move! The spell cannot be stopped once it's begun!  
Dorothea(sad): We have to finish it, or we both could die.  
Narrator: You can feel the tension in Edith's body... how badly she wants to save Skyla.  
Narrator: The baby lets out a loud cry.  
Dorothea(sad): This is what Skyla wanted. The baby comes first. That's what she said.  
Edith(sad): I know. Okay. Let's... let's continue.  
\>  
Edith(sad)*Think: Mom...  
# (sld_08_11_DP4_skyla_leave)  
## A. (They should go after her!)  
## B. (They made the right decision.)  
#### A  
Edith(angry)*Think: Mom left and she didn't die! There had to be a way to save her!  
#### B  
Edith(sad)*Think: But I wish there had been another way.  
\***  
Dorothea(sad): Let this child be bound to the earth, transformed by it...  
\*+MAGIC_CIRCLE_START  
Narrator: The glow intensifies, settling on the mother and daughter until the cliff seems bathed in light.  
\*-MAGIC_CIRCLE_START  
\*+MAGIC_CIRCLE_STDBY  
Dorothea(surprise): Let the will of her mother's heart strengthen our magic...  
Dorothea(surprise): And cast this child into a new form!  
\*+MAGIC_CIRCLE_START  
Narrator: The wind whips around them harder, the candle flames dancing wildly.  
\*-MAGIC_CIRCLE_START  
\*+MAGIC_CIRCLE_STDBY  
Dorothea(angry): Drazara Beliril Avos to {Layla Name} Sky Dawson!  
\*Play Sound s_magic_skill_01  
\*+MAGIC_ANIMATION_QUICK  
\*Stop Sound  
Narrator: A familiar magical burst rings through the spell, a blast of light making Edith shield her eyes.  
\*  
\*-MAGIC_CIRCLE_STDBY  
\*  
\*Play Music m_gently_melancholy_sadness_fortress_europe_01  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_city_seaside_clifftop_sunset.jpg-story' width='60'>
\*Scene CLIFFTOP (Color: White Time: 2.5)
{% endhint %}  
Edith(surprise): Did it work?  
Narrator: Bone deep exhaustion fills Edith's body. All of her muscles ache.  
Dorothea: Only time will tell if it lasts. But for now...  
Narrator: She unwraps the baby, letting {Layla Name}'s tiny human legs wiggle in the air.  
\>>  
Edith(smile): That's good news at least. We can always redo the spell if it fades.  
Dorothea(sad): No... We can't. Don't you feel it? That weariness in your body?  
Dorothea(sad): We've drained too much of our lifeforce. It would be dangerous to try again.  
Narrator: Baby {Layla Name} fusses and cries, and Edith takes her into her arms.  
Edith(smile): Hi {Layla Name}. My name's Edith.  
\>  
Narrator: She looks over to Skyla's empty space in the spell.  
Edith(sad): I'm going to be taking care of you for a little while.  
\*  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_city_beach_house_inside_night.jpg-story' width='60'>
\*Scene BEACH_HOUSE_INSIDE_NIGHT (Color: White Time: 2.5)
{% endhint %}  
\*Camera Left 0  
\*  
Narrator: When you are finally out of Edith's memories, the sun had already gone down.  
\*Layla Player  
Layla(surprise): Woah.  
# (sld_08_11_DP5_out_of_memories)  
## A. You were so powerful!  
## B. My father is nothing like I thought.  
## C. My mother loved me so much.  
#### A  
\>>  
Grandma(smile): Oh, I don't know about that. My mother was much more powerful.  
Layla(happy): I never knew you were a witch...  
Grandma(surprise): Hush yourself! That's not something you can go around telling people.  
#### B  
Grandma(sad): I'm so sorry, {Layla Name}. I had hoped you would never need to know...  
Grandma(sad): I wanted you to have a father you could admire and look up to.  
\>>  
Layla(sad): Grandma...  
Narrator: You take her hand in yours and give it a warm squeeze.  
Layla(sad): I had you, my mom, your mom... So many people in my life to look up to.  
Layla(sad): I don't need him.  
#### C  
\>>  
Grandma(sad): She did. She wanted you to be safe and happy more than anything.  
\***  
Layla(sad): So what happened after that? When the spell overloaded you...  
Layla(sad): Was Dorothea right? That it drained your lifeforce?  
### \*Goto merm08_what_happened  
# merm08_free_grandma_convo  
Grandma: We were working on a spell to keep you in human form your entire life.  
Grandma(sad): It was a powerful, difficult spell. We knew it was dangerous.  
Grandma(sad): We felt the risks were worth it.  
Layla(surprise): So what happened? I mean, obviously the spell worked.  
Grandma: The night we were going to cast the spell...  
Grandma(sad): Your mother was followed by some of her husband's soldiers.  
Layla(sad): Oh no...  
Grandma(sad): They snuck up on us. During the spell, they pulled your mother from it.  
Grandma(sad): The spellwork was spread across the three of us. When she was removed...  
Grandma(sad): The spell overloaded me and my mother.  
Layla(surprise): But...  
# (sld_08_12_CP_overloaded)  
## A. You're okay, right?  
## B. You both survived, didn't you?  
\***  
Grandma(smile): I'm fine. But...  
### \*Goto merm08_what_happened  
# merm08_what_happened  
\*Stop Music  
\*Play Music m_sadness_melancholy_gently_casual_desire  
\>>  
Grandma(sad): It drained us. My mermaid immortality was lost.  
Layla(sad): Lost?  
Grandma(sad): Both my mother and I aged prematurely... Too much of our lifeforce was lost.  
Grandma: She passed away only a few years after the spell was cast.  
Layla(sad): I'm so sorry.  
Grandma(smile): It's also why I decided to tell you I was your grandmother.  
Layla(sad): So then... What happened to my mother?  
\>  
Narrator: She stares out the window, deep sadness in her eyes.  
Grandma(sad): I don't know. She never contacted us again.  
Layla(sad): Do you think...  
# (sld_08_13_never_contacted)  
## A. She's still alive?  
## B. He had her killed?  
#### A  
Grandma(sad): I'd like to believe that. But it's been so long...  
#### B  
Grandma(sad): Skyla seemed to believe him capable of anything.  
Grandma: But he was so interested in having a child... I don't know if he would go that far.  
\***  
\*Play Sound s_stair2  
Narrator: You hear a creak on the stairs and look up to see Shaun.  
\*Stop Sound  
\*Stop Music  
\*Play Music moment  
Shaun(smile): Maddie was adamant we give you some alone time, but could we grab a snack?  
Grandma(happy): Poor starving young people... We've been talking for far too long.  
Grandma(smile): I'll get out of your hair soon, dear.  
Shaun(smile): Thank you, ma'am.  
Narrator: He slips back upstairs and your grandma laughs.  
\>>  
Grandma(smile): It's getting late. I can stop by later to keep talking.  
Layla(surprise): You're not staying here?  
\>  
Narrator: She waves you off and stands to her feet.  
Grandma(smile): You think I want to stay with a bunch of rowdy youths? Tch.  
Layla(happy): I would hardly call us that.  
Grandma(smile): I'm staying at a hotel in town. I'll come over another time, alright?  
Grandma(surprise): Oh! Before I forget...  
Narrator: She reaches into her bag and pulls out a folded green top.  
Layla(surprise): What's this?  
Grandma(smile): It belonged to your mother. I found it while I was looking for some old things of hers.  
Narrator: You hear your friends come down the stairs, and Maddie comes up behind you.  
Maddie(surprise): Something of your mom's?  
Grandma(smile): I'm not sure if it's your style, but...  
Grandma(smile): It's something you can wear both in and out of the water.  
Narrator: She gives you a significant look as she says this.  
Layla(surprise)*Think: Something my mother wore as a mermaid!  
Maddie(happy): Well.. go try it on!  
Narrator: You take the top from your Grandmother and quickly step into another room to change...  
\*Layla Outfit Prem_Siren_Song_Human (Tag: Record)  
Layla(shy): Well... What do you think?  
Narrator: You hear a clang as Sam heavily sets down the plate he was holding.  
Sam(shy): Wow, {Layla Name}...  
Maddie(happy): Damn... Your mom had some style.  
Layla(shy): You think so?  
Grandma(smile): If you don't like it, you don't have to keep it. I'm not sure if the fashions have changed...  
Layla*Think: Should I keep it?  
# (sld_08_14_pay_clothes)  
## A. Yes! Wear your mother's outfit. (Cost: 29 Diamond ID: look_sld_08_siren_song)  
## B. No, it's not my style...  
#### A  
Layla(happy): Of course I want it! It's lovely. And it makes me feel closer to her.  
Grandma(smile): I'm so glad, dear.  
Narrator: As you move to walk her to the door, you can't help but notice Sam staring at you.  
Sam(shy): ...  
Grandma(happy): Careful, Sam... I think you're drooling a little.  
Layla(surprise): Grandma!  
Narrator: She waves you off, laughing.  
#### B  
\*Layla Outfit Reset  
Layla(smile): Thank you for bringing it... I'm just not sure it's for me.  
Narrator: Your grandma takes it back, smiling at you.  
Grandma(smile): It's fine, dear... I wasn't sure if you'd like it or not.  
\***  
Narrator: You see her off, making sure to give her a long, warm hug in a private moment between you before she goes.  
\>>>  
Layla: Thank you... for telling me everything.  
# (sld_08_14_warm_hug)  
## A. I'm glad to finally know the truth.  
## B. I know it must have been hard for you.  
\***  
\>>  
Grandma(smile): It's good that you know. It's been... difficult.  
Grandma(sad): It's hard keeping something a secret from the ones you love.  
Layla(sad): I think I know exactly how that feels.  
\>  
### \*Goto merm08_next_day  
# merm08_next_day  
\*Stop Music  
\*Play Music m_deliberate_thought_ability  
\*  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_city_beach_house_inside.jpg-story' width='60'>
\*Scene BEACH_HOUSE_INSIDE_DAY (Color: Black)
{% endhint %}  
\*Camera Right 0  
\*  
Narrator: By the time you wake up, it's already well past noon.  
Layla(sad)*Think: I was tossing and turning all night. My brain wouldn't shut off.  
\>>  
Maddie(happy): Look who finally woke up!  
Shaun(happy): You missed lunch. Little shack down the road has the <i>best</i> burgers.  
Layla(smile): That sounds amazing...  
\>  
Narrator: Out the window, you see a familiar figure on the beach.  
Layla(surprise): I'll be right back.  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_3_city_beach_house_day.jpg-story' width='60'>
\*Scene OUTSIDE_BEACH_HOUSE_DAY
{% endhint %}  
Narrator: You step outside in the bright afternoon sunlight.  
\*Stop Music  
\*Play Music suspicion  
Zale(smile): Hey.  
Layla(smile): Hey yourself. It might not be the best idea to come around here...  
Layla(sad): My friends might stage an intervention if they see you.  
Zale(surprise): Do I want to know what that is?  
Layla(surprise): Uh... Interventions are a human culture thing. They're... very painful.  
Narrator: Zale nods, expression serious.  
\>>  
Zale: Then I'll be quick. I just came to remind you...  
Zale(sad): Tomorrow's your last day. The transformation will wear off by sundown.  
Layla: My last day...  
# (sld_08_15_zale_reminding)  
## A. I can't wait to be a mermaid again!  
## B. I don't want to leave yet.  
#### A  
Zale(happy): Yeah? I bet you've completely forgotten how to swim already.  
Layla(surprise): No! It's like riding a bike... isn't it?  
Zale(happy): I've never ridden a bike so I wouldn't know.  
\>  
#### B  
Zale(sad): I'm sorry. It's not forever... You can always come back.  
Layla(sad): But I can't <i>stay</i> back. I'll always be tied to the ocean.  
Zale(sad): There are whole mer communities that live a split life like that.  
\>  
Layla(sad)*Think: Like my mother and Edith's father, split between two lives.  
Zale(sad): You could go to them, learn how they cope with it.  
Layla(sad): I don't think I'm ready for that just yet.  
\***  
Narrator: Zale puts a hand on your shoulder and smiles.  
Zale(smile): Anyway... I'll be waiting on the beach for you tomorrow night.  
Narrator: He walks away, leaving you standing on the back porch.  
Layla: One more day...  
Narrator: There's a tap on the porch door and Sam steps out of the house.  
\*Stop Music  
\*Play Music m_romance_beauty_love  
Sam(smile): I was a little worried you were going to sleep all day.  
Layla(happy): I kind of <i>did</i> sleep all day.  
Sam(shy): Well you're awake for the most important part.  
Layla(smile): Oh? What's that?  
\*Condition  
## A. (Condition: SAM_ROMANCE >= 1)  
#### A  
\>>  
Sam(shy): I was hoping we could have our date today... right now, actually.  
Layla(happy): Sure! You've been 'planning' it for so long... I can't wait to see it.  
Sam(surprise): Oh, so no pressure or anything...  
Narrator: You give him a little poke in the arm.  
Layla(smile): I'm just teasing. But I do want to know what it is.  
\>  
\***  
### \*Goto merm08_surprise  
# merm08_surprise  
Sam(happy): I have a surprise for you. It's not for a few hours, but...  
Sam(smile): While we wait, I thought we could have a picnic on the beach.  
Layla(surprise): A surprise? Can I have a hint?  
\>>  
Sam(smile): A hint... Oh! Your surprise requires it to be dark for it to... work.  
Layla: ...  
# (sld_08_16_the_surprise)  
## A. There are so many dirty ways I could take that.  
## B. Is it animal, mineral, or vegetable?  
#### A  
\*Sam FLIRT +1  
Sam(shy): What?! No! I just mean it happens at night...  
Layla(smile): ...  
Sam(angry): Ugh. There is nothing dirty about my surprise.  
Layla(happy): If I say I'm disappointed will you blush even harder?  
Narrator: Sam gives you a playful shove and turns his face away from you.  
#### B  
Sam(smile): It's a...  
Sam(surprise): ...Okay I'm not actually sure. A mineral... maybe?  
Layla: Curiouser and curiouser.  
Sam(happy): No more questions! I won't let you spoil it!  
Layla(happy): But figuring it out is half the fun of a surprise!  
Narrator: Sam gives you a playful shove, laughing.  
\***  
\>  
Sam(happy): Do you want a picnic on the beach or not?  
Layla(happy): Yes, sorry. I'll behave. Maybe.  
Narrator: Sam grabs a basket and a blanket from inside the house and the two of you walk down to the beach.  
\*Camera Left 2  
Narrator: You lay out the blanket while Sam unpacks the basket.  
Layla(surprise): Sam... Did you make all of this?  
Sam(shy): It's just sandwiches...  
\>>  
Layla(surprise): No, these are <i>fancy</i> sandwiches. They're paninis!  
Layla: Is this homemade bread?  
Sam(smile): No, but I did buy it at an artisanal bakery Maddie found online.  
Narrator: You take a bite and nearly groan at how good it is.  
Layla(happy): Mmm... This is amazing. I want to eat your cooking every single day.  
Sam(smile): Is that a promise?  
\>  
Layla(surprise): Sorry? Did you say something?  
Sam(smile): Nothing.  
\*Stop Music  
\*  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_3_city_beach_house_night.jpg-story' width='60'>
\*Scene OUTSIDE_BEACH_HOUSE_NIGHT (Color: Black Time: 3.5)
{% endhint %}  
\*Camera Left 0  
\*  
\*Play Music m_gently_romance_heavenly  
Narrator: The two of you enjoy your picnic, talking and laughing until the sun goes down.  
\>>  
Layla(smile): So... When is this surprise?  
Sam(happy): Just a little while longer.  
Narrator: You rub your arms, shivering in the light breeze.  
Layla(sad): Did you happen to bring another blanket? It's chilly with the sun down.  
Sam(surprise): You can use the picnic blanket... Or, um...  
Narrator: He opens his arms for you to cuddle closer.  
Sam(shy): I hear body heat is pretty warm.  
Layla(smile)*Think: I should...  
# (sld_08_17_light_breeze)  
## A. Cuddle up to him.  
## B. Take the blanket.  
#### A  
\*Gain MERM08_SAM_CUDDLE  
Narrator: You scoot over on the blanket and tuck yourself against him.  
\*Sam FLIRT +1  
Sam(shy): That's better, right?  
Layla(smile): It's perfect.  
Narrator: Sam puts his arm around you. His hand finds yours and you twine your fingers together.  
Layla(smile): This close, I can feel your heartbeat.  
\*Play Sound heartbeat1  
Layla(happy): It's racing.  
Sam(shy): Is it? I don't know why that would be...  
\>  
#### B  
Layla(smile): I'll take one cozy blanket, please.  
Narrator: The two of you scoot off the blanket and dust the sand off before wrapping it around you.  
Layla(happy): That's better.  
\***  
\*Play Sound s_sam_bell  
Narrator: Sam's phone plays a twinkling melody and he swipes the screen to silence it.  
\*Stop Sound  
Layla(surprise): You can take that if you need to.  
\>>  
Sam(happy): It's an alarm. Your surprise is about to start!  
Layla(happy): Finally! Can I know what it is now?  
Sam(happy): It's a meteor shower!  
Layla(surprise): Really? There's one happening tonight?  
Sam(happy): Yep! We'll have to stay up late to catch the really good part, though.  
Sam(surprise): So I completely understand if you need to get some sleep.  
\>  
Layla: How late are we talking?  
Sam(shy): Um... like three in the morning maybe. It won't get good until then.  
Layla*Think: Should I watch the romantic meteor shower with Sam?  
# (sld_08_18_meteor_shower)  
## A. Yes! (Cost: 24 Diamond ID: plot_sld_08_sam)  
## B. I can't stay up too late.  
#### A  
\*Stop Music  
\*Play Music m_gently_snug_romance_dancing_star_01  
\*Gain DID_METEOR_SHOWER_PREM  
\>>  
Layla(happy): This is so cool. I can't wait! Or, well... I guess I have to wait.  
Sam(smile): I'm sure we'll find some way to pass the time.  
\>  
Narrator: You stare up at the starry sky with anticipation, and Sam chuckles.  
### \*Goto merm08_wishes  
#### B  
\*Stop Music  
\*Play Music m_gently_lifting_dreams_01  
Sam(happy): That's fine. The internet said it'll start slowly and build...  
Sam(smile): You still might be able to catch a shooting star if you look closely.  
Layla(happy): Okay. I'll go inside after we see one.  
### \*Goto merm08_wishes  
\***  
# merm08_wishes  
\*Condition  
## A. (Condition: MERM08_SAM_CUDDLE = 0)  
## B. (Condition: MERM08_SAM_CUDDLE >= 1)  
#### A  
Narrator: Sam leans over and points to the eastern part of the sky.  
\>>  
Sam: It'll come from over there. So watch that space.  
Narrator: You throw him a playful salute.  
Layla: Roger that, commander.  
#### B  
Narrator: Sam takes your hand in his and points with it to the eastern part of the sky.  
\>>  
Sam(smile): The shower will come from that direction, so watch closely.  
Narrator: You look at the side of his face, so close with your shoulders touching.  
Layla(shy): Okay... I'll do that.  
\***  
\>>>  
Sam(smile): Do you have your wish ready?  
Layla(surprise): My wish?  
Sam(shy): Yeah... It's an old tradition. You make a wish on a shooting star.  
Sam(smile): But you have to think the wish before the star burns out.  
Layla(smile): So you like to be prepared in advance?  
Sam(shy): Well... it doesn't hurt, right?  
Layla(happy): So what are you wishing for?  
Narrator: He puts a finger to his lips in the shushing motion.  
\>>  
Sam(smile): If you tell someone, it doesn't come true.  
Layla(happy): You won't tell me?  
# (sld_08_19_tell_the_wish)  
## A. There sure are a lot of rules to this.  
## B. What if I ask really nicely?  
#### A  
\>  
Layla(happy): And you're taking them so seriously. You're like a little kid.  
#### B  
Sam(happy): Is that the theme for this evening?  
Sam(happy): You trying to make me tell you secrets?  
Layla(smile): I don't know... got any more secrets I should know about?  
Narrator: Sam's cheeks burn a little too pink for you not to notice.  
Sam(shy): They wouldn't be secrets anymore if I told you what they are.  
\>  
\***  
Narrator: A streak of light in the sky catches your attention and you gasp.  
Layla(surprise): Was that a shooting star?!  
Sam(happy): It was! They're fast, so you have to keep your eyes open.  
Narrator: With newfound dedication, you focus on the sky, waiting...  
\*Wait 1  
Narrator: And waiting...  
\*Wait 1  
\*Condition  
## A. (Condition: DID_METEOR_SHOWER_PREM = 0) *Goto merm08_make_a_wish  
## B. (Condition: DID_METEOR_SHOWER_PREM >= 1) *Goto prem_sam_meteor_shower  
\***  
# merm08_make_a_wish  
\*Stop Music  
\*Play Music m_deliberate_thought_ability  
Narrator: Finally you see it! A bright twinkle streaking down to earth.  
Layla(surprise)*Think: I wish...  
# (sld_08_22_make_a_wish)  
## A. For Sam to kiss me!  
## B. For Zale to be mine!  
## C. To see Caden again!  
## D. To find my mom!  
#### A  
\*Gain WISH_SAM  
Narrator: You smile as you wish for Sam to kiss you.  
#### B  
\*Gain WISH_ZALE  
Narrator: You squeeze your eyes shut, hoping for your relationship with Zale to grow.  
#### C  
\*Gain WISH_CADEN  
Narrator: You picture Caden's face and wish to see him again soon.  
#### D  
\*Gain WISH_MOM  
Narrator: With a hand pressed to your heart, you wish for your mother to be safe, and for you to see her again.  
\***  
\*Condition  
## A. (Condition: DID_METEOR_SHOWER_PREM = 0) *Goto merm08_free_sam_ilu_scene  
## B. (Condition: DID_METEOR_SHOWER_PREM >= 1) *Goto prem_sam_meteor_shower_part_2  
\***  
# prem_sam_meteor_shower  
\*Stop Music  
\*Play Music m_gently_romance_heavenly  
Narrator: You catch yourself yawning.  
\>>  
Sam(smile): You sure you can stay up until three?  
Layla(angry): Yes! I'm determined. I will not miss this meteor shower!  
Sam: Well... You'll hurt your neck staring up at the sky like that all night.  
\*Condition  
## A. (Condition: MERM08_SAM_CUDDLE >= 1)  
## B. (Condition: MERM08_SAM_CUDDLE = 0)  
#### A  
Narrator: Sam nudges you, guiding you backwards.  
\>>>  
Sam(smile): Lay down. It'll be a lot easier to see the sky that way.  
\>  
Narrator: The two of you fall back onto the sand, laying side by side.  
Narrator: You snuggle up on his chest, humming happily to yourself to feel his arms around you.  
#### B  
Sam: You should lay down. It'll be a lot easier that way.  
Narrator: You stretch out in the cool sand, snuggling your blanket tight around you.  
Narrator: Sam lays down beside you. You're close enough, you can feel his body heat radiating off of him.  
\>  
Layla(smile): You're right, this is a lot better.  
Narrator: Sam's voice is rough when he speaks.  
Sam(surprise): Y-yeah, it's... amazing.  
Narrator: In the pale glow of the moon, you can see his pulse dancing wildly in his throat.  
\***  
Layla(smile): Hmmm... Your heart seems to race every time we get a little closer.  
Sam(shy): Huh... I don't know why that would be...  
Narrator: The two of you stare up at the sky, waiting for the stars to fall.  
\*Play Sound s_seawave  
Narrator: Your eyelids droop as the relaxing sound of the ocean and Sam's close warmth lull you into a soft sleep...  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_black.jpg-story' width='60'>
\*Scene BLACK (Time: 3)
{% endhint %}  
\*Stop Music  
\*Play Music m_gently_snug_romance_dancing_star_01  
\*  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_3_city_beach_house_night.jpg-story' width='60'>
\*Scene OUTSIDE_BEACH_HOUSE_NIGHT (Color: Black)
{% endhint %}  
\*Camera Left 0  
\*  
Narrator: When you open your eyes, you find yourself cuddled up tightly against Sam with the blanket thrown over both of you.  
\>>  
Layla(shy)*Think: Oh no...  
# (sld_08_20_CP_soft_sleep)  
## A. How did we end up like this?!  
## B. I hope I didn't drool on him in my sleep...  
#### A  
Layla(shy)*Think: I must have snuggled up to him in my sleep...  
Layla(shy)*Think: For, um... warmth.  
#### B  
Narrator: You quickly inspect his t-shirt for any potential wet places...  
Layla(surprise)*Think: Phew... I'm good.  
\***  
\>  
Narrator: From where your head rests against Sam's shoulder, you sneak a peek at his face.  
Sam(smile): ...  
Narrator: Sam is staring up at the sky, a bright smile on his face.  
\>>  
Layla(smile): What's got you so happy?  
Sam(happy): A beautiful girl fell asleep in my arms. Why wouldn't I be happy?  
Layla(shy): Why do you have to be so...  
# (sld_08_21_CP_sam_be_happy)  
## A. Sweet.  
## B. Corny.  
#### A  
\*Sam FLIRT +1  
Sam(happy): I can't help it!  
Sam(smile): I've been bottling up all these feelings for you for so long...  
Layla(happy): You have a lot saved up? Got to get them out of your system?  
Sam(shy): Something like that.  
\>  
#### B  
Sam(surprise): Corny!? But I mean it!  
Layla(happy): Hmm... Are you sure you don't rehearse these lines of yours?  
Sam(shy): Well... Okay, that one I may have been practicing while you were asleep.  
Layla(happy): I knew it.  
\>  
\***  
Layla(sad): So... Did I miss the meteor shower?  
Sam(happy): Nope. You woke up right on time. It should be starting any minute now.  
Layla(surprise): Okay! I'm back on sky watch duty.  
Narrator: Sam laughs at you focus intently on the night sky, looking for signs of shooting stars.  
\*Wait 1  
Narrator: You stare hard...  
\*Wait 1  
### \*Goto merm08_make_a_wish  
# prem_sam_meteor_shower_part_2  
Narrator: That first falling star is followed by another... and another...  
\*+METEOR_SHOWER  
\*Stop Music  
\*Play Music m_intense_romance_sexy_love_01  
Narrator: Soon the sky is full of dazzling streaks of light.  
\>>  
Layla(surprise): {*Joyful Oh my god!}  
Sam(happy): {*Joyful It's amazing.}  
Narrator: Sam holds you close, kissing the top of your head as you exclaim over the shooting stars.  
\>>>  
Sam(smile): Did you remember to make a wish?  
Layla(shy): I did... I wished that--  
\>>  
Sam(surprise): No! Don't tell me or it won't come true.  
\*Condition  
## A. (Condition: WISH_SAM = 0)  
## B. (Condition: WISH_SAM >= 1)  
#### A  
Layla(happy): Okay, okay. I won't.  
#### B  
Layla(smile): Hmm... But this is a wish only you can make come true.  
Sam(shy): Oh? What is that?  
Narrator: Your lips brush against Sam's ear as you whisper your wish to him.  
Layla(smile): I wished for you to kiss me.  
Narrator: When you pull back, there's a passionate fire in his eyes.  
Sam: Yes please.  
\>  
### \*Goto prem_sam_kiss  
\***  
Narrator: The meteor shower twinkles in the sky above your heads.  
Layla(smile): You know what would make this moment perfect?  
# (sld_08_23_CP_perfect_moment)  
## A. If you kissed me right now. *Goto prem_sam_kiss  
## B. If wishes really could come true.  
#### B  
Sam(smile): I think they can. Mine is about to.  
Layla(surprise): Oh? And you still can't tell me what you wished for?  
\>>  
Sam(smile): I asked for courage.  
Narrator: You raise an eyebrow at him, and he continues.  
Sam(shy): ...Courage to tell you...  
Narrator: He takes a deep breath.  
### \*Goto merm08_end  
\***  
# prem_sam_kiss  
\*Stop Music  
\*Play Music m_mystery_romance_sexy_lust_love_02  
\*Gain SAM_ROMANCE  
\*Gain KISSED_SAM  
Narrator: Sam kisses you softly at first... but at the first taste of your lips he groans.  
\>>  
Sam(surprise): God, {Layla Name}...  
Narrator: He leans over you in the sand, one hand in your hair as he kisses you, the other holding himself up.  
Narrator: Your legs tangle together as he kisses you again and again beneath the falling stars.  
Layla(shy): Wow...  
Narrator: Sam presses his forehead to yours, breath unsteady.  
Sam(shy): Hey... Can I tell you something?  
Layla(smile): Sure... What is it?  
### \*Goto merm08_end  
# merm08_free_sam_ilu_scene  
Layla(happy): Did you make your wish?  
Narrator: Sam is looking at you with warm affection in his gaze.  
Sam(smile): Yeah... I did.  
Layla(happy): And you still can't tell me what it is?  
Sam(shy): I don't know... maybe I can...  
Narrator: He smiles at you under the stars as the waves fall softly against the shore.  
Sam(smile): I wished you would react well when I tell you...  
### \*Goto merm08_end  
# merm08_end  
Sam(smile): I'm in love with you, {Layla Name}.  
Layla(surprise)*Think: Oh my god...!  
# End  
