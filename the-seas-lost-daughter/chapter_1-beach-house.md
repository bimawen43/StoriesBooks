# Begin  
\*  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_3_city_beach_house_day.jpg-story' width='60'>
\*Scene OUTSIDE_BEACH_HOUSE_DAY
{% endhint %}  
\*Camera Left 0  
\*  
# merm01_init_char_setup  
\*Play Music merry2  
Narrator: Before we get started, we need to set up your character.  
\*Layla Player  
### \*Goto setup_name  
# setup_name  
\*Layla Naming: What's your name? | Layla  
Narrator: Your name is {Layla Name}. Is this correct?  
# (sld_01_01_confirm_name)  
## A. Yes *Goto setup_look  
## B. No *Goto setup_name  
\***  
# setup_look  
Narrator: Next we'll set up your character's look.  
Narrator: Which face best suits your character?  
\*Layla Face Face_1  
\*Layla Outfit Sweet_and_Simple  
\*Layla Hair Beachy_Bangs  
\*Role  
# (sld_01_02_choose_face)  
## A. Face Face_1 (Button: Choose this look.)  
## B. Face Face_2 (Button: Choose this look.)  
## C. Face Face_3 (Button: Choose this look.)  
\***  
Narrator: Now choose a hairstyle!  
\*Role  
# (sld_01_03_choose_hair)  
## A. Hair Naturally_Gorgeous (Button: Choose this look.)  
## B. Hair Messy_Bun (Button: Choose this look.)  
## C. Hair Berry_Beautiful (Button: Choose this look. Cost: 16 Diamond ID: look_sld_01_hair01)  
## D. Hair Mermaid_Tail_Braid (Button: Choose this look. Cost: 16 Diamond ID: look_sld_01_hair02)  
## E. Hair Beachy_Bangs (Button: Choose this look.)  
\***  
Narrator: One last thing... We've got to choose your outfit!  
Narrator: Which style do you like the most?  
\*Role  
# (sld_01_04_choose_outfit)  
## A. Outfit Sweet_and_Simple (Button: Choose this look.)  
## B. Outfit Fun_Frills (Button: Choose this look. Cost: 16 Diamond ID: look_sld_01_clothes01)  
## C. Outfit Vacay_Princess (Button: Choose this look. Cost: 19 Diamond ID: look_sld_01_clothes02)  
## D. Outfit By_the_Pier (Button: Choose this look.)  
\***  
Layla(happy): {*Joyful I'm ready for the summer!}  
Narrator: Once you confirm your look, you can change your hair, but not your face.  
Narrator: Make sure you're okay with your selection!  
Layla: Is this my best look?  
# (sld_01_05_confirm_look)  
## A. Yes *Goto merm01_meet_sam  
## B. No *Goto setup_look  
\***  
Layla(happy): This is perfect. {*Joyful Let's go!}  
\*Stop Music  
# merm01_meet_sam  
\*  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_city_retro_house_interiors.jpg-story' width='60'>
\*Scene GRANDMA_HOUSE_DAY (Color: black)
{% endhint %}  
\*Camera Right 0  
\*  
\*Play Music light5  
Narrator: College has finally let out for the summer, and you're back at home with your grandma.  
Narrator*Top: Grandma | {Layla Name}! There's a young man at the door for you.  
Narrator: You roll your eyes.  
Layla(happy): Oh, please... It's just Sam.  
Narrator: Your grandma comes around the corner, her hand to her chest, imitating a strong Southern accent.  
Grandma(sad): I was beginning to worry you would die an old maid...  
Grandma(smile): But now... A gentleman caller at last!  
Layla(surprise): Grandma{*Joyful !}  
\*Camera Left 2  
Narrator: You go to the living room where Sam waits, holding a bouquet of flowers.  
\*Stop Music  
\*Sam Outfit Sam_Casual  
\*Play Music meetsam  
\*+ITEM_MEET_SAM_ART  
\*Stop Music  
\*Play Music light5  
\>>>  
Sam(smile): Hey, {Layla Name}.  
Layla(smile): Hi! You brought flowers?  
\>>  
Sam(shy): Am I not allowed to bring you flowers?  
Layla(surprise): I guess not. It's just...  
# (sld_01_06_meet_sam)  
## A. That kind of makes this seem like a date.  
## B. You've never done it before.  
#### A  
Narrator: Sam fiddles with the bouquet.  
Sam(shy): Is that a bad thing?  
Layla(surprise): Huh? What did you say?  
Sam(smile): Nothing! Don't worry about it.  
#### B  
Sam(shy): Well... Maybe I should bring you flowers more often.  
Layla(happy): You don't have to!  
Layla(smile): We only own, like, one vase. Where would I put them all?  
\***  
\>  
Narrator: Your grandma enters the room and pats your arm, laughing.  
Grandma(happy): Don't get your panties in a twist. The flowers are for me.  
Narrator: She plucks them out of Sam's hand and smells them.  
Sam(surprise): Actually, those were for--  
Layla(smile): How long have we known each other? At least fifteen years?  
Layla(happy): You should know by now... Grandma does what she wants.  
Layla(smile): There's no stopping her.  
\*Stop Music  
### \*Goto merm01_out_with_sam  
# merm01_out_with_sam  
\*  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_city_town_park_gazebo_parterre.jpg-story' width='60'>
\*Scene TOWN_PARK_DAY (Color: black)
{% endhint %}  
\*Camera Right 0  
\*  
\*Play Music romance  
Narrator: The two of you go to the park and walk along the path, discussing the trip you're leaving on that week.  
\>>  
Layla(happy): Can you imagine? A whole beach house and it's all ours!  
Sam(smile): Well, technically it's Addison's beach house.  
Sam: And she's not going to let any of us forget it.  
Layla(smile): I don't care as long as I get to spend a month at the beach!  
Sam(happy): What is the first thing you're going to do when we get there?  
Layla(happy): Hmmm...  
# (sld_01_07_first_thing_at_the_beach)  
## A. Go sunbathing!  
## B. Build a sandcastle!  
## C. Play in the waves!  
#### A  
Layla(smile): Sprawled out on the hot sand in my bikini...  
Layla(smile): Just soaking up those rays...  
Layla(happy): Maybe I'll find a hot guy to rub lotion on my back.  
Narrator: Sam opens his mouth to say something, then stops, fiddling awkwardly with his hands.  
Sam(shy): Yeah, that... Sounds pretty nice.  
\>  
#### B  
Sam(happy): You're a little kid at heart, aren't you?  
Layla(happy): Yep! Life's too short not to play around every once in a while.  
Sam(smile): Well, I promise to help you build it once we get there.  
\>  
#### C  
Layla(happy): What's the point of going to the ocean if we're not going to get into the ocean!  
Sam(smile): Can't argue with that logic.  
Sam: Just watch out for jellyfish.  
\>  
\***  
\*Stop Music  
\*Camera Left 4  
Narrator: You wander into the gazebo and lean on the railing.  
Layla: You know... I've never seen the ocean before.  
\>>  
Sam(surprise): What?! Never?  
Layla(sad): It's kind of far away... And my grandma doesn't really like the ocean.  
Sam: Have you told her about the trip yet?  
Narrator: You bite your lip and shake your head.  
Sam(surprise): Wait, are you serious?  
Sam(surprise): We leave Friday!  
Layla: I know! I just don't think she's going to take the news very well.  
Sam(sad): Because she doesn't want you being away for the summer?  
Layla: It's not that...  
Layla(sad): It's just kind of hard to talk about.  
Sam(sad): {Layla Name}... You know you can tell me anything, right?  
Layla*Think: I should...  
# (sld_01_08_sam_questioned)  
## A. Confide in Sam. *Goto confide_in_sam  
## B. Change the subject.  
#### B  
\*PARENT_DEATH_UNKNOWN +1  
Layla: It's fine, really. Don't worry about it.  
Narrator: You shrug one shoulder and look away.  
\*SAM_REL_CHANGE -1  
Message: Impact | That made an impact on Sam.  
Sam(sad): Alright. I can take a hint.  
### \*Goto change_the_subject  
\***  
# confide_in_sam  
\*CONFIDED_IN_SAM +1  
\*SAM_REL_CHANGE +1  
\*Play Music soft  
Message: Impact | That made an impact on Sam.  
Layla: You know my parents died when I was young, and my grandmother raised me, right?  
Sam(sad): Yeah...  
Layla(sad): Well... My parents died at sea, in a boating accident.  
Sam(sad): Oh, {Layla Name}...  
Layla(sad): My grandma has avoided the ocean ever since.  
Layla(sad): When she hears I plan on spending my summer by the ocean...  
Layla(sad): I'm worried she's going to feel like it's a betrayal.  
Narrator: He puts an arm around your shoulder.  
Narrator: His touch is warm, comforting, and familiar...  
Layla*Think(sad): I should...  
# (sld_01_08_DP1_sam_comfort)  
## A. Hug Sam.  
## B. Back away.  
#### A  
\*SAM_REL_CHANGE +1  
Message: Impact | That made an impact on Sam.  
Narrator: You lean into his embrace, pressing your face against his chest.  
Sam(sad): It'll be okay. A tragic accident like that is so rare.  
Sam(sad): Nothing's going to happen to us on this trip.  
Layla(sad): I know, but it's going to be hard convincing my grandmother of that.  
Narrator: Sam rubs your back in gentle circles.  
Sam: I could come with you... Be there when you talk to her.  
Layla: No, this is something I should do alone.  
Narrator: You squeeze him close, then step away from the hug.  
#### B  
\*SAM_REL_CHANGE -1  
Message: Impact | That made an impact on Sam.  
Narrator: You step back and his arm falls to his side.  
\***  
# change_the_subject  
Layla(smile): Anyway... I'm still really excited to go on this trip.  
Layla(smile): Have you started packing yet?  
Sam(happy): You know me... I've been ready to go for a week now.  
Layla(happy): I haven't even started.  
Layla(smile): Maybe I could get you to pack for me...  
Sam(happy): Hey, don't try to get out of doing your own work.  
\>  
Narrator: The two of you spend time together, walking around and talking until it's time to go home.  
\*  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_city_retro_house_interiors.jpg-story' width='60'>
\*Scene GRANDMA_HOUSE_DAY (Color: black)
{% endhint %}  
\*Camera Left 0  
\>  
\*  
Narrator: Sam walks you to your door.  
Sam(smile): You're going to tell your grandma about the trip tonight, right?  
Layla(smile): Yep.  
Sam(smile): Good. Text me if you need anything.  
Narrator: Instead of leaving, he hovers in the doorway, as if waiting for something.  
\>>  
Layla(surprise): Sam?  
# (sld_01_09_sam_hovering)  
## A. Do I have something on my face?  
## B. Is something wrong?  
#### A  
Sam(surprise): No! Your face is fine. Better than fine.  
Layla(happy): Oh yeah?  
Sam(shy): Yeah. Um...  
#### B  
Sam(shy): Uh...  
\***  
Narrator: He opens his mouth as if he's about to say something, but stops himself.  
### \*Goto tell_me_anything (Condition: CONFIDED_IN_SAM = 1)  
### \*Goto merm01_tell_grandma  
# tell_me_anything  
Layla(smile): You know, this whole friendship thing goes both ways..  
Layla(smile): You can tell me anything, too.  
\*SAM_REL_CHANGE +1  
Narrator: Sam runs a hand through his hair, laughing at himself.  
Sam(shy): Am I that obvious?  
Layla(happy): You're a terrible liar. It's one of the things I love about you.  
Narrator: Sam smiles at you a moment, his expression warm.  
Sam(shy): ...  
# merm01_tell_grandma  
Sam(surprise): Sorry... I'm just really excited for this trip.  
Layla(happy): Me too!  
\>  
Sam(smile): Alright, well... take care!  
Narrator: He nearly trips backwards down the stairs as he leaves.  
Layla*Think: What was that all about?  
\*Camera Right 2  
Narrator: You wander into the kitchen where your grandmother sits, sipping a cup of coffee.  
Layla(sad): Hey, Grandma? There's something I need to tell you.  
Narrator: She pauses, cup still raised to her lips, and quirks an eyebrow at you.  
Grandma: What is it, dear?  
Layla: My friends and I have a trip planned for the summer.  
Layla: So I'll be gone for a whole month.  
Grandma(smile): {Layla Name}! Goodness, you made me worry something was wrong.  
Grandma(happy): Have fun with your friends, dear.  
Grandma(smile): I'm not so old yet that I need you watching over me every second of every day.  
Layla(sad): It's not just that...  
Layla(sad): The house we're renting... It's a beach house. It's by the ocean.  
\*Stop Music  
Narrator: Your grandma suddenly stands to her feet.  
\*Play Music doubts  
\>>  
Grandma(angry): No. You can't go.  
Layla(surprise): Grandma...  
# (sld_01_10_grandma_objection)  
## A. Please, I know you don't like it, but I'll be careful.  
## B. I'm an adult. You can't stop me from going.  
#### A  
Grandma(angry): It's not about being careful.  
Grandma(sad): The ocean is a wild and dangerous place.  
Grandma(sad): No matter what precautions you take, things can change so fast...  
#### B  
\*GRANDMA_REL_CHANGE -1  
Message: Impact | That made an impact on your Grandmother.  
Grandma(angry): I see. Is that how it's going to be?  
Grandma(angry): I'm not some tyrant trying to ruin your fun out of spite, {Layla Name}.  
Grandma(angry): There are real dangerous out there with real, serious consequences.  
\***  
Narrator: Her voice breaks and you realize she's crying.  
Grandma(cry): I just want to protect you...  
Layla(surprise): Grandma, please don't cry!  
### \*Goto parents_death_story (Condition: PARENT_DEATH_UNKNOWN = 1)  
### \*Goto grandma_ocean_why  
# parents_death_story  
Grandma(cry): Your parents... When they died...  
Narrator: She looks at you a long moment, but doesn't say anything.  
Layla(sad): I know, Grandma. You don't have to tell me again.  
Layla(sad): It was a boating accident. They... They drowned.  
### \*Goto grandma_ocean_why  
# grandma_ocean_why  
Grandma(sad): Your mother, Skyla... She loved the ocean.  
Grandma(angry): And it killed her.  
Narrator: She sighs, her shoulders drooping. She suddenly seems very, very old.  
Grandma(sad): I swore to protect you. I promised her I would keep her daughter safe.  
Grandma(sad): For twenty years, I've done that.  
Layla(sad): Grandma...  
# (sld_01_11_grandma_worried)  
## A. You've done a great job taking care of me.  
## B. You can't protect me forever.  
#### A  
Layla(smile): You have been the absolute best parent to me.  
Layla(smile): I love you so much.  
\*GRANDMA_REL_CHANGE +1  
Message: Impact | That made an impact on your Grandmother.  
Narrator: Your grandmother's hand drifts to her necklace, tugging it nervously.  
Grandma(sad): I love you, too.  
#### B  
Narrator: Her lip trembles but she nods slowly.  
Grandma(cry): I know you're right. You're all grown up now...  
Grandma(sad): You have to make your own choices.  
\***  
Narrator: She glances up at you, smiling sadly.  
Grandma(sad): There are so many other places to vacation...  
Grandma(sad): You could rent a log cabin, or a small apartment in New York City...  
Grandma(sad): Why do you have to go to this beach house?  
Layla(sad): Because...  
# (sld_01_12_why_have_to_go)  
## A. It's where my friends are going.  
## B. I can't hide from the ocean forever.  
## C. I need to see it for myself.  
#### A  
\*GRANDMA_REL_CHANGE -1  
\*OCEAN_WHY_FRIENDS +1  
Grandma(angry): I didn't raise you to follow along with whatever your friends want you to do.  
Grandma(angry): You're better than that.  
Layla(angry): I am better than that! I'm not going to stay home just because you tell me to, either!  
Narrator: The two of you glare at each other, and finally, your grandma sighs.  
#### B  
\*OCEAN_WHY_FACE_FEARS +1  
Layla: What happened to my parents was terrible, but I am not my parents.  
Layla(sad): I want to face this. I can't spend my whole life afraid.  
\*GRANDMA_REL_CHANGE +1  
Narrator: Your grandmother steps close to you and places a warm hand on your cheek.  
Grandma(smile): Skyla would be so proud to see the woman you have become.  
#### C  
\*OCEAN_WHY_CONNECTION_MOM +1  
Layla: You said my mother loved the ocean... I want to find out why.  
Layla(sad): I feel like it's almost a part of me... Like I'll understand her more once I'm there.  
\*GRANDMA_REL_CHANGE +1  
\>  
Narrator: Your grandmother looks at you sadly for a long moment, then sighs deeply.  
\***  
\*Play Music light5  
Grandma: It seems there's no stopping you.  
Narrator: Her nervous hands worry at the locket around her neck.  
\>>  
Grandma(sad): Will you promise me one thing?  
Layla(sad): Anything. What is it?  
Grandma(sad): Don't go into the ocean.  
Grandma(sad): Dip your toes in, walk the shore, take a boat ride...  
\>>>  
Grandma(sad): But please... Please don't go under the water.  
\>  
Layla*Think: That's such an oddly specific request...  
Layla*Think(sad): But I guess... If that's how my mother died...  
Grandma(sad): Promise me.  
Layla*Think(sad): Poor Grandma...  
# (sld_01_13_need_a_promise)  
## A. I promise. I won't go into the water.  
## B. I'll be safe when I swim, okay?  
#### A  
\*PROMISED_GRANDMA +1  
\*GRANDMA_REL_CHANGE +1  
Message: Impact | That made an impact on your Grandmother.  
Narrator: She hugs you close.  
Grandma(smile): Thank you.  
Layla(smile): I'll be okay, Grandma. I promise.  
Narrator: Her grip tightens briefly, then she steps away.  
#### B  
\*DID_NOT_PROMISE_GRANDMA +1  
\*GRANDMA_REL_CHANGE -1  
Message: Impact | That made an impact on your Grandmother.  
Grandma(sad): ...  
Narrator: She looks at you a long moment, then turns away.  
\***  
Grandma: Please be safe. That's all I ever want for you... Just be safe, and be happy.  
Layla(smile): I will, Grandma. I promise.  
\*Stop Music  
### \*Goto merm01_the_beach_house  
# merm01_the_beach_house  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_black.jpg-story' width='60'>
\*Scene BLACK
{% endhint %}  
Narrator: A few days later...  
\*  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_3_city_beach_house_day.jpg-story' width='60'>
\*Scene OUTSIDE_BEACH_HOUSE_DAY
{% endhint %}  
\*Camera Right 0  
\*  
\*Play Music light6  
Narrator: You and Sam arrive at the beach house!  
Layla(happy): So... This is going to be our home for the next month.  
Maddie: {Layla Name}!! Aaaahh!!  
Sam(happy): Aaand there's the welcoming party.  
Narrator: Maddie sprints down the drive and barrels into you, nearly knocking you over with her hug.  
Layla(surprise): Oof!  
Layla(happy): My best friend - the human tornado.  
Shaun(smile): Complete with entourage.  
Narrator: Maddie's boyfriend, Shaun, helps Sam with the luggage, while Addison follows behind him.  
Maddie(happy): I missed you! I missed you! I missed you!  
Layla(happy): I missed you, too!  
Addison: You were barely apart for two weeks.  
Maddie(smile): Yeah, but it felt like forever!  
Narrator: You pry your friend off of you and the whole group moves into the house.  
\*  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_city_beach_house_inside.jpg-story' width='60'>
\*Scene BEACH_HOUSE_INSIDE_DAY
{% endhint %}  
\*Camera Right 0  
\*  
Layla(surprise): Oh my god! Look at this place!  
Addison(happy): Isn't it gorgeous? My family comes here every summer.  
Layla(surprise): Wow...  
# (sld_01_14_the_beach_house)  
## A. Must be nice to have money.  
## B. You must have so many great memories here.  
#### A  
\*ADDISON_REL_CHANGE -1  
Addison(surprise): It is. I mean, you're not wrong there.  
Addison: But you just bought a plane ticket to fly halfway across the country during tourist season.  
Addison: And we both attend a private university that isn't exactly cheap.  
Layla: So?  
Addison: So maybe lose the attitude.  
Narrator: Addison turns on her heel and walks over to the boys standing a few feet away.  
Layla(surprise): Damn.  
Maddie(sad): Be nice, {Layla Name}. This is her house. We're just guests.  
#### B  
\*ADDISON_REL_CHANGE +1  
Addison(happy): I do! I learned to ride a bike on the front driveway.  
Addison(happy): And I actually had my first kiss on the beach out back.  
Maddie(happy): Oooh! Was he cute?  
Addison(smile): Ehhh...  
Layla(happy): Haha. Was he a good kisser?  
Addison(sad): Ehhh...  
Maddie(happy): So it was terrible.  
Addison(sad): Aren't all first kisses terrible?  
Narrator: Shaun comes up behind Maddie and wraps his arms around her.  
Shaun(happy): Our first kiss was pretty magical...  
Addison: Ugh. Don't even start.  
\***  
Sam(smile): So what's the plan for the evening?  
Maddie(happy): Well tomorrow we're waking up bright and early to check out the tide pools!  
Layla(surprise): Wait...  
# (sld_01_15_the_tide_pool)  
## A. What's a tide pool?  
## B. Why do we have to get up so early?  
#### A  
Shaun(surprise): When the tide is low, the ocean levels around here drop.  
Shaun(smile): They leave behind small puddles of ocean water...  
Shaun(happy): And there are loads of cool animals that live in them!  
Maddie(happy): Yeah! Like starfish and sea urchins!  
Addison: But you can only see them for a short period of time when the tides are low.  
Layla(surprise): That sounds really cool!  
#### B  
Maddie(happy): Ha! Lazy sleepyhead.  
Layla(happy): It's a legitimate question!  
Addison(smile): The tide pools are only visible when the tides are at their lowest.  
Addison(smile): And low tide is first thing in the morning tomorrow.  
Shaun(happy): Addison is our resident expert on all things ocean around here.  
Addison(shy): Stop... I just looked it up online.  
\***  
Sam(surprise): Waking up at the ass crack of dawn... These better be some cool fish.  
Addison: There aren't actually many fish, but there's plenty of other sea creatures...  
Addison(shy): Oh, sorry. I see what you mean.  
Sam(happy): You're fine. I didn't realize you knew so much about this.  
Narrator: Addison tucks a lock of hair behind her ear.  
Addison(shy): I just wanted this trip to be great for everyone...  
Addison(shy): I tend to get a little obsessed when I'm focused on something.  
Narrator: Maddie watches Addison and Sam, then comes to stand beside you. She casually rests her elbows on the counter and speaks low under her breath.  
Maddie: Is it just me... Or does Addison have a crush on Sam?  
Layla(surprise): I'm sure she's just--  
Narrator:  Addison giggles loudly at something Sam said.  
Maddie: No. She definitely likes him.  
Maddie: How do we feel about this?  
\>>  
Layla(surprise): Why are you asking me?  
Maddie(surprise): You've known him since the dawn of time practically. You're the best judge.  
\>  
Maddie(surprise): Plus, I always kind of thought you two had a thing going.  
Layla(surprise): A thing?  
# (sld_01_16_layla_and_sam)  
## A. I mean... I kind of have a crush on him...  
## B. We're friends! Strictly friends.  
#### A  
\*CRUSH_ON_SAM +1  
Maddie(happy): Ha! I knew it.  
Maddie: So now we need to figure out how he feels about you...  
Maddie(surprise): We'll plan some events that put you two together in a romantic setting...  
Layla(surprise): Hey, don't go planning one of your crazy schemes...  
Narrator: She flutters her lashes at you innocently.  
Maddie(happy): Schemes? Me? Never...  
Layla(sad): Maddie...  
Maddie(happy): Trust me! I have the perfect idea!  
#### B  
\*NO_CRUSH_ON_SAM +1  
Maddie: Alright, fair enough.  
Maddie: But the question is... Is she good enough for our Sam?  
Layla(happy): 'Our' Sam?  
Narrator: Shaun steps up beside Maddie and stage-whispers at the two of you.  
Shaun(smile): What are you two talking about over here?  
Maddie(happy): Only the best idea I've ever had!  
\***  
Narrator: Maddie claps twice, commanding everyone's attention.  
Maddie(happy): Since it's our first night together in the beach house, we need to celebrate!  
Maddie(happy): I'm thinking... bonfire on the beach!  
Sam(happy): Oooh that sounds like fun.  
Addison(smile): We actually have all the stuff for a fire pit, too. I can set it up.  
Shaun(happy): Good friends, a roaring fire, the waves crashing... Sounds ideal.  
Maddie(smile): What do you think, {Layla Name}? You're the final vote!  
Layla(surprise): Oh man... Way to put me on the spot here.  
Layla: I think...  
# (sld_01_17_bonfire)  
## A. A bonfire sounds great! (Cost: 16 Diamond ID: plot_sld_01_sam) *Goto bonfire_prem  
## B. We shouldn't stay out late if we're getting up early... *Goto no_bonfire_prem  
\***  
# no_bonfire_prem  
Maddie(sad): Oh... Yeah, that's true..  
Shaun(smile): I guess one of us had to be the responsible one.  
Layla(sad): Sorry guys... Maybe we can do a bonfire another night?  
Addison(smile): Sure! Sounds like a plan.  
Narrator: The five of you hang out in the house and go to bed early.  
### \*Goto merm01_next_day  
# bonfire_prem  
\*DID_BONFIRE_PREM +1  
\*  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_3_city_beach_house_night.jpg-story' width='60'>
\*Scene OUTSIDE_BEACH_HOUSE_NIGHT (Color: black)
{% endhint %}  
\*Camera Right 0  
\*  
Maddie(happy): Woohoo! I can't wait to set everything on fire.  
Addison(surprise): Uh... She does know that's not really what a bonfire is about, right?  
Shaun(smile): Don't worry. I'll be sure and supervise!  
\*Camera Left 3  
Narrator: The five of you hurry down to the beach and set everything up.  
Sam(surprise): Maddie, I've lit a fire before. Chill.  
Maddie(surprise): But it needs to be bigger!  
Narrator: Addison flops down in the sand next to you.  
Addison(sad): I don't know how you two can be roommates in college...  
Addison(sad): All that chaotic energy doesn't make you want to scream?  
Layla(happy): Haha... You get used to it, I promise.  
Narrator: Soon a roaring fire washes everything in a warm glow.  
Shaun(smile): Alright guys... any requests?  
Narrator: He picks up his guitar and strums a few chords.  
Layla(smile): You should play...  
# (sld_01_17_DP1_shaun_play_song)  
## A. Something romantic! *Goto bonfire_romance  
## B. Something we can dance to! *Goto bonfire_dancing  
\***  
# bonfire_romance  
\*BONFIRE_ROMANCE_COMPLETE +1  
Shaun(happy): You got it!  
Narrator: He plucks at the guitar strings and a sweet, gentle melody drifts through the air.  
Sam(shy): Romantic, huh?  
Narrator: He joins you and Addison in the sand.  
Addison(shy): It's a beautiful night... Romance is definitely fitting.  
### \*Goto bonfire_romance_crush_on_sam (Condition: CRUSH_ON_SAM = 1)  
# bonfire_romance_crush_on_sam  
Narrator: Maddie skips over to you and whispers in your ear.  
Maddie(smile): You're doing great, but still! Better make a move before Addison does!  
Layla*Think(shy): Make a move...?  
### \*Goto bonfire_romance_part_two  
# bonfire_romance_part_two  
Narrator: You glance over at Sam and see him already staring at you.  
\>>>  
Sam(shy): ...  
\>>  
Addison(shy): ...And that's why I think it's so important, you know?  
Layla*Think(surprise): Oh crap! Addison was talking and I wasn't even listening...  
\>  
Addison(surprise): Sam? Do you agree?  
Sam(surprise): Oh! Um... Yeah.  
Narrator: Addison tucks her hair back behind her ears and smiles at him, but he's still looking at you.  
Sam(smile): So... I think this is your first official time on a beach, right {Layla Name}?  
Addison(surprise): It is? I didn't realize you'd never been to the ocean before!  
Layla(smile): Yeah... It's all really exciting.  
Sam(happy): Is it everything you hoped it would be?  
Layla(smile): Well...  
# (sld_01_17_DP2_seaside_night)  
## A. I haven't seen it during the day yet!  
## B. The company makes it better.  
#### A  
Layla(surprise): I can barely see it at night. It's too dark.  
Addison(sad): You're right...  
Sam(smile): You can see plenty of the ocean tomorrow when we visit the tide pools!  
Layla(happy): I'm looking forward to it.  
#### B  
Layla(shy): I'm glad I get to see the ocean for the first time with you, Sam.  
\*Sam FLIRT +1  
Sam(shy): Me too.  
Addison(angry): ...  
\***  
### \*Goto bonfire_prem_part_two (Condition: BONFIRE_DANCING_COMPLETE = 1)  
### \*Goto bonfire_prem_transition_to_second_song  
# bonfire_dancing  
\*BONFIRE_DANCING_COMPLETE +1  
\*Play Music romance  
Shaun(smile): Your wish is my command!  
Narrator: Shaun thumps his hand on the guitar to set the rhythm of a fast and cheerful song.  
Maddie(happy): Woo!  
Sam(happy): Come on! Aren't you going to dance?  
Narrator: He holds out his hand to you, grinning.  
Sam(shy): Dance with me?  
Layla*Think(smile): I should...  
# (sld_01_17_DP3_dancing)  
## A. Take his hand.  
## B. Dance with Maddie instead!  
#### A  
Narrator: You reach out and place your hand in his.  
Narrator: For a moment, your breath catches in your throat at how warm his hand is...  
Narrator: And how perfect it feels... Like it's always belonged there.  
\>>>  
Sam(happy): Come on!  
\>  
Narrator: He tugs you to your feet and into his arms.  
Narrator: The music is fast, and the two of you are twirling and moving around in the fire in perfect sync.  
\>>  
Layla(happy): Quick, dip me!  
Narrator: Sam bends you backward into a low dip, his face hovering over yours.  
\*Sam FLIRT +1  
Sam(smile): ...  
\>  
Narrator: Then he pulls you back up again with a dizzying rush.  
Maddie(happy): Damn! You guys have skills.  
Sam(happy): Our high school PE class had a whole section on ballroom dancing.  
Layla(happy): It's actually a lot of fun.  
Addison: It definitely looked like fun.  
Narrator: You turn and notice Addison sitting on the ground, sullenly jabbing a stick into the sand.  
#### B  
\*ADDISON_SAM_FLIRT_VAR +1  
Layla(happy): Hmmm... Better idea!  
Narrator: You turn and throw your arm around Maddie's waist.  
Maddie(surprise): Woah!  
Layla(happy): Dance with me!  
Narrator: In a fit of giggles, the two of you perform every crazy dance you remembered from middle school.  
Addison(happy): Oh my god. Do you two remember this?  
Narrator: She tries to imitate something from a music video, but twists awkwardly in the sand and stumbles.  
Addison(surprise): Ah!  
Sam(surprise): I got you!  
Narrator: Sam catches her at the last second, steadying her to her feet with a hand on her elbow.  
Addison(shy): Oh... Thank you.  
Sam(happy): Don't sweat it.  
\***  
\*Stop Music  
### \*Goto bonfire_prem_part_two (Condition: BONFIRE_ROMANCE_COMPLETE = 1)  
### \*Goto bonfire_prem_transition_to_second_song  
# bonfire_prem_transition_to_second_song  
Narrator: The song comes to a close, and all of you applaud Shaun.  
Addison(happy): Encore! Encore!  
### \*Goto bonfire_dancing (Condition: BONFIRE_ROMANCE_COMPLETE = 1)  
### \*Goto bonfire_romance (Condition: BONFIRE_DANCING_COMPLETE = 1)  
# bonfire_prem_part_two  
\*Play Music merry2  
Narrator: The song draws to a close, the final notes fading on the breeze.  
Shaun(smile): Okay, my hands are tired. I need a break.  
Shaun(happy): And definitely need some Maddie time.  
Narrator: Maddie skips over and drops into her boyfriend's lap.  
Addison: Those two are just too much sometimes...  
Sam(smile): Seems like the perfect time to escape.  
Narrator: He grabs your hand and starts running, tugging you after him.  
\>>  
Layla(surprise): Ahh! Where are we going?!  
Sam(happy): Not far!  
\>  
Narrator: True to his word, he stops barely twenty feet away.  
Sam(shy): This is your first time seeing the ocean...  
Sam(shy): I thought you should have a little peace and quiet to properly enjoy it.  
Layla(happy): Awww. Sam!  
# (sld_01_17_DP4_enjoy_peace)  
## A. You're the sweetest guy I know.  
## B. But I was already enjoying it!  
#### A  
\*Sam FLIRT +1  
Sam(shy): Nah... That can't be true.  
Narrator: He bumps your shoulder with his.  
#### B  
Sam(happy): Yes, but not <i>properly!</i>  
Layla(smile): Alright, Mr. Ocean Master... How should I be enjoying it?  
\***  
Sam(shy): Here... Like this.  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_city_beach_night_sky_star.jpg-story' width='60'>
\*Scene OCEAN_NIGHT
{% endhint %}  
### \*Goto bonfire_enjoy_ocean_romantic (Condition: CRUSH_ON_SAM = 1)  
### \*Goto bonfire_enjoy_ocean (Condition: NO_CRUSH_ON_SAM = 1)  
# bonfire_enjoy_ocean_romantic  
\*Stop Music  
Narrator: Sam steps behind you and puts one hand on your waist. He takes your hand with the other.  
\*Play Music romance  
\*Sam FLIRT +1  
Sam(happy): You see the horizon? The line where the water meets the sky?  
Layla(smile): Just barely... It's getting too dark to see clearly...  
Narrator: He lifts your hand, curving your fingers so that he can point with your hand.  
\>>>  
Sam(shy): Right there...  
\>  
Narrator: He points into the distance with your own hand.  
Layla(smile): Okay, I see it.  
Narrator: He's standing so close to you... You can feel along your skin when he speaks to you in a low voice.  
### \*Goto bonfire_enjoy_ocean  
# bonfire_enjoy_ocean  
Sam(smile): Focus on the horizon. Listen to the sounds of the waves.  
Sam(smile): Feel the sand beneath your feet, and the spray of the water.  
Narrator: You focus on everything he's describing, doing as he says.  
Sam(smile): Take it all in... The sound of seagulls, the salty smell of the sea...  
Sam(smile): Let it wash over you until everything else fades away.  
Layla(shy): Okay...  
Narrator: The ocean fills every single one of your senses.  
Narrator: Soon you don't hear your friends, or see the light of the bonfire...  
Narrator: All you can see is the ocean.  
Narrator: All you can feel is the ocean.  
Layla*Think(surprise): It almost feels like nothing exists except me and the ocean.  
Layla*Think(smile): Like I'm floating in the sea... Surrounded by it...  
Layla*Think(surprise): I can almost hear a voice calling out to me...  
Layla*Think(sad): A sad, mournful voice... Something pulling in my chest...  
\*+MAGIC_ANIMATION_QUICK  
\*Stop Music  
Layla(surprise): Gyah!  
\*Play Music moment  
Narrator: You stumble backwards into the sand, blinking away the afterimages of the flash of light...  
\>>>  
Layla*Think(surprise): What the hell was that?!  
\>>  
Sam(surprise): {Layla Name}? Hey, are you okay?  
Layla(surprise): I think so...  
Sam(surprise): What happened?  
Layla(surprise): Well, I was focusing just like you said, and...  
# (sld_01_18_magic_symbol)  
## A. It was like the ocean was calling to me.  
## B. Maybe I'm more exhausted than I realized...  
#### A  
\*SAM_REL_CHANGE +1  
\*CONFIDED_IN_SAM_ABOUT_OCEAN +1  
Sam(sad): Calling to you?  
Layla(sad): Yeah... It was like a voice. Not one I hear with my hears, but in my heart.  
Layla(shy): I'm sorry, that probably sounds ridiculous...  
Message: Impact | That made an impact on Sam.  
Sam(sad): No. If you say that's what happened, I believe you.  
Sam(smile): Besides, history is full of the stories of sailors saying the exact same thing.  
Sam(smile): To some people, the ocean is a magical force.  
Sam(shy): It's kind of cool that you're one of them.  
\>  
Narrator: He smiles at you a moment too long to be casual before springing into action again.  
#### B  
Sam(sad): You have had a long day of travelling...  
Sam(smile): I'm sorry I accidentally lulled you to sleep... That wasn't what I was going for at all.  
Layla(happy): It was really nice up until end!  
\>  
\***  
Narrator: Sam holds out a hand to you and pulls you to your feet.  
Sam: Let's get you inside. You should probably rest. It's getting late anyway.  
Layla(sad): Yeah... Good idea.  
Narrator: Sam stays by your side, explaining to the others and then walking you back to the beach house.  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_black.jpg-story' width='60'>
\*Scene BLACK
{% endhint %}  
Narrator: But as you fall asleep that night... You can't help but remember...  
\*+MAGIC_ANIMATION_QUICK  
### \*Goto merm01_next_day  
# merm01_next_day  
\*  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_city_ocean_rocky_beach_cave.jpg-story' width='60'>
\*Scene SEA_CAVE_DAY
{% endhint %}  
\*Camera Left 0  
\*  
Narrator: The five of you get up early and head out for a rocky shore famous for its tide pools.  
\>>  
Layla(surprise): Wow!  
\>  
Addison(smile): Isn't it beautiful?  
Sam(happy): This is already worth it and we haven't even found one of the pools yet.  
Narrator: You pick your way across the rocks, careful of the slippery ground and uneven terrain.  
Sam(surprise): Woah!  
Narrator: He wobbles, windmilling his arms wildly.  
Layla(surprise): Sam!  
Layla(surprise): Quick! I need to...  
\*Time 7 (Default: B)  
# (sld_01_19_TC_sam_wobbling)  
## A. Steady him!  
## B. Move out of the way!  
#### A  
Narrator: You grab onto his arm, letting him lean on you until he regains his balance.  
\>>  
Sam(surprise): Nice reflexes, {Layla Name}!  
Layla(happy): I saved your life. Now you owe me.  
Sam(happy): You may have saved my dignity, but I don't think that was particularly life-threatening...  
Layla(happy): Oh, okay. Next time I'll just let you fall, then.  
\>  
#### B  
Narrator: You jump out of the way just as Sam crashes to the ground.  
Shaun(surprise): Yo, dude! Are you alright?  
Sam(sad): I'm fine... My ego may never recover...  
Maddie(happy): Yeah, especially since I got it all on video.  
Narrator: Sam hangs his head with a groan.  
\***  
Addison(surprise): Guys, I found one! It's full of animals! Come check it out!  
Narrator: You hurry over to Shaun, and all of you crouch down around the wide, shallow pool.  
# searching_test  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_city_ocean_rocky_tidepool.jpg-story' width='60'>
\*Scene TIDEPOOL
{% endhint %}  
Layla(surprise): Oh my god! Look at them all!  
Maddie(surprise): Can we touch them?!  
Addison(happy): You can definitely touch the starfish, and the anemone if you're very gentle.  
Addison(surprise): But watch out for the orange nudibranches. The rest of them are fine, but the orange ones sting.  
Shaun(happy): Yes ma'am!  
Sam(surprise): Nudibranches?  
Addison(happy): Yeah! Those cool-looking colorful slug things.  
Narrator: You look down into the pool...  
Narrator: Which creature do you check out first?  
### \*Goto searching_tidepool  
# searching_tidepool  
\*Searching  
## A. ANEMONE  
## B. NUDIBRANCH_STINGING  
## C. STARFISH  
#### A  
\*SEARCHED_ANEMONE +1  
\*ANEMONE Completed  
Narrator: You reach your hand into the pool and gently stroke the anemone's fronds.  
\*+ANEMONE_ANIMATION  
\>>  
Layla(happy): Oh! It feels so soft on my fingers.  
\>  
Maddie(surprise): Really? I want to try!  
Narrator: She thrusts her hand into the anemone's waving tendrils, then yanks her hand back.  
Maddie(surprise): Ow!  
Addison(angry): I said be <i>gentle!</i>  
### \*Goto searching_tidepool_last (Condition: SEARCHED_STARFISH = 1)  
### \*Goto searching_tidepool  
#### B  
\*SEARCHED_NUDIBRANCH_STINGING +1  
\*NUDIBRANCH_STINGING Completed  
Narrator: You gently poke the orange nudibranch and--  
Layla(surprise): Yikes! That hurt...  
Narrator: A tiny pink sting on your finger reminds you to be careful!  
### \*Goto searching_tidepool  
#### C  
\*SEARCHED_STARFISH +1  
\*STARFISH Completed  
Narrator: The starfish squirms slowly at your touch, wiggling its arms.  
\*+STARFISH_ANIMATION  
\>>  
Layla(happy): Is he ticklish? Sorry to invade your space, little buddy...  
Sam(happy): He's thinking -- "It's too early in the morning to have humans poking me!"  
\>  
Layla(happy): Go back to sleep, little star. Sorry for waking you!  
### \*Goto searching_tidepool_last (Condition: SEARCHED_ANEMONE = 1)  
### \*Goto searching_tidepool  
\***  
# searching_tidepool_last  
\>>>  
Addison(surprise): Oh, look there!  
\>  
Narrator: A little fuzzy creature peeks its head out from behind a rock.  
Shaun(happy): He's come to join the party!  
Maddie(happy): They look like little bunnies!  
Sam(surprise): And you're sure he won't sting us?  
Addison(smile): Unlike the other ones, these are harmless.  
Maddie(surprise): See if you can pet him, {Layla Name}!  
\*Searching  
## A. NUDIBRANCH_FRIENDLY *Goto nudibranch_magic  
\***  
# nudibranch_magic  
\*NUDIBRANCH_FRIENDLY Completed  
\*Play Music light6  
Narrator: You hold your finger against the rock beside the little bunny nudibranch.  
Narrator: After a few moments, he inquisitively bumps your hand with its face.  
Maddie(surprise): Aww! Is he sniffing you?  
Shaun(happy): He's not a dog...  
Narrator: The little thing slowly wriggles onto your fingertip, crawling along your hand.  
\>>  
Sam(happy): You made a friend!  
Layla(surprise): Will he be okay if I pull him out of the water?  
\>  
\*+ANIM_NUDIBRANCH_FRIENDLY  
Addison: Hmmm... Cup a little water in your hand for him to hang out in.  
Narrator: You do as she suggests, and the tiny sea slug wanders around your palm inside the shallow pool of water.  
Maddie(happy): This is so cool. I have to get pictures.  
Narrator: You hold him close to you, whispering into your hand.  
Layla(happy): Hi little guy... How are you doing?  
Narrator: The black antenna sway in the water in your hand.  
Narrator: You find yourself drawn in, watching him explore.  
\*Stop Music  
Layla*Think(smile): He's so cute... And seems so peaceful...  
\*Play Music magic  
\*+MAGIC_ANIMATION_QUICK  
\*Stop Music  
\>>>  
Layla(surprise): Ah!  
\>  
\*Play Music oceandance  
Narrator: You jerk back, dropping the nudibranch back into the pool. He floats harmlessly to the bottom.  
Sam(surprise): Addison, I thought you said he couldn't sting her!  
Layla(surprise): Did none of you see that?  
Shaun: ...See what?  
Layla(surprise): That flash!  
Narrator: Your friends look at each other, then all slowly shake their head.  
Layla(sad): Weird...  
# (sld_01_20_the_flash)  
## A. Maybe it was light reflecting off something on the beach.  
## B. There was some kind of weird pulse of energy!  
#### A  
Addison(surprise): Oh, that makes sense. There's unfortunately a lot of trash in the ocean.  
Addison(sad): Like glass bottles, or cans...  
Maddie(smile): But glass bottles turn into sea glass!  
Shaun(surprise): I bet we can find some around here, then!  
Narrator: The two jump up and race off. Addison sighs, getting up to slowly follow them.  
#### B  
\*ERRATIC +1  
Layla(surprise): How did you not notice that?  
Addison(sad): What is it you think you saw?  
Layla(sad): Just some kind of... I don't know... Electricity?  
Maddie(sad): ...From a slug?  
Layla(sad): You think I'm crazy, don't you?  
Message: Impact | Your friends are worried about you.  
Narrator: Maddie ruffles your hair affectionately.  
Maddie(happy): Oh, we know you're crazy. But it's part of your charm.  
Narrator: She laughs and jumps up to find another pool.  
\***  
\>>  
Sam(sad): You sure you're ok?  
Layla(sad): Yeah, I'm fine.  
Layla(sad): Maybe I'm just tired. I'll rest here a bit. You can go on ahead.  
\>  
Narrator: Sam hesitates, but you wave him off and he eventually gives you space.  
Layla*Think(angry): I know what I saw. What I felt. This happened yesterday too, what is going on?  
Layla*Think(angry): That's the second time in less than a day. Something is going on.  
Narrator: When you look out at the ocean, you can almost feel it again...  
Narrator: That tug in your chest, a mournful voice calling out to you.  
Layla*Think(sad): Ugh... But what do I do about it?  
Narrator: You get up and wander closer to the water.  
Narrator: The rocky outcropping slopes downward, and you follow the narrow pathway down the side of the little cliff face.  
Narrator: As you get closer to the water, that <i>call</i> intensifies.  
Layla*Think(sad): It feels like missing someone who isn't there anymore, grieving for them.  
Layla*Think: But I haven't lost anyone.  
\*  
{% hint style="info" %}
<img src='https://ustories.saiyunyx.com/update/CDN_C/CDN/BGPics/bg_city_ocean_rocky_beach_cave.jpg-story' width='60'>
\*Scene SEA_CAVE_DAY
{% endhint %}  
\*Camera Left 0  
\*  
\*Camera Right 3  
Narrator: The outcropping leads you to a sea cave. You step inside, standing on the dry ledge above a deep pool of water.  
Layla*Think(sad): I wish I knew what was happening to me...  
Narrator: You stare down into the depths of the water in the cave.  
Narrator: A dark shape moves below the surface.  
Layla(surprise): Oh!  
Narrator: You lean closer, trying to get a better look...  
Narrator: When something splashes up from the water!  
\*Stop Music  
\>>>  
Layla(surprise): Oh my god!  
\>  
\*Play Music the_man  
\*+ITEM_MEET_ZALE_ART  
\*Zale Name ???  
\*Zale Face Zale_Shirtless  
\>>  
Zale(smile): Oh. Hey.  
Layla(surprise): <i>Oh my god!!</i>  
# End  
