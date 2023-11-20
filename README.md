# Demon Races
The English demon race names felt off to me from the first MegaTen game I played, and I feel they are overall very poor localizations that obscure important information about the races and how they relate to one another. So, I've taken it upon myself to make patches for the various SMT games that change the demon races to names I think are better.

I don't know Japanese myself, so I can only go off machine translations and kanji dictionaries to get an idea of the original race names. I'm aware this means I'm likely missing tons of nuance and context. If you do know Japanese and can think of better translations, please tell me!

## Guiding Principles
I'm not changing the race names just for the sake of changing things. I believe the official race names actively impede gameplay, and any revisions should strive to correct that first and foremost. Here are some examples of the major issues that need to be addressed, in order of importance:
1. **Untranslated Races**. This is completely inexcusable and the localizers should be deeply ashamed of themselves. You do not just *give up* on translating vital terms. Some of them, such as "Kishin" and "Amatsu", are genuniely unique cultural terms and I would accept an argument they're better off untranslated; but "Jirae", "Jaki", "Yoma", "Megami", and "Touki" are not those.
2. **Negotiation Intuition**. Especially in the earlier SMT games, demon races provide important information about how to negotiate with demons, or if they could be negotiated with at all. The English localization is poor at conveying this; for example, the "Wilder" race, which is just a nonsense word. What the hell is a "Wilder"? Why can I negotiate with a "Beast" just fine, but "Wilders" will break my bones while cackling every time I try to talk? Because it's so obvious that a "Wilder" is an evil version of a "Beast", right. The revised names should make these things clearer.
3. **Fusion Intuition**. The fusion formulas frequently send players scrambling to look up a chart. Some of them were pretty arbitrary even in the original Japanese, but several formulas were made even less intuitive by the English localization. For example, in Japanese, the recipe for making Avians is extremely intuitive: combining a regular "Demon Bird" (妖鳥) with an angel, "Holy Beast" (聖獣), or "Godly Beast" (神獣) imbues it with holiness, turning it into a "Spiritual Bird" (霊鳥). This intuition is totally lost in the English localization, where Avians and Flights/Birds just sound like synonyms of each other with no clear distinction. Similarly, one creates a "Godly Beast" (神獣) by combining a Beast with any kind of god demon, an intuition broken by localizing "Godly Beast" as "Avatar", a word that maintains the divinity connection but not the beast connection. Revised race names should make the relationships between races clearer where possible.
4. **Remove Ambiguity**. In the previous point I discussed how the English localization broke connections between certain races. However, it's also guilty of the opposite problem: Implying connections where none exist. For example, "Lady" and "Femme" are synonyms, yet in gameplay terms they are completely unrelated to one another. In Japanese, this false connection does not exist: "Ladies" are 地母神 ("Mother Goddess") and "Femmes" are 鬼女 ("Ogre Woman"), clearly very different things despite both being feminine. Preserving *only* the feminine element, the least important component, of both names was a poor localization choice that should be avoided in the revised names.

## Issues
There is a major issue to any project of this type: Space limitations. The Japanese race names are written in kanji, which can express an entire word with only a single character, and their literal translations are often two words or more. Converting this to a phonetic alphabet obviously requires a lot more space, which not every game has. Some areas, such as the dedicated status screens, are quite generous in terms of available space, but others are strictly limited to 9, 7, or even a paltry 6 characters. It's sometimes possible to eke out more space by editing the UI display code (I did this for SMT2), but that's typically difficult and not my area of expertise. Compromises with the guiding principles will likely be necessary in light of this fact.

One way around this would be if abbreviated versions could be substituted into cramped text fields; the Aeon Genesis fan translation of *SMT: if* does for equipment and demon names, but I'm not skilled enough at programming to replicate their algorithm in other games.

## Name Changes
|Original |New |&nbsp; |Original |New |&nbsp; |Original |New
|--- |--- |--- |--- |--- |--- |--- |---
|Megami |Goddess  ||Foul   |Wretch    ||Entity/Geist  |Ancient
|Jirae  |Erdgeist ||Wood   |Flora     ||Godly         |Almighty
|Yoma   |Spirit   ||Wilder |Monster   ||Herald/Seraph |Archangel
|Jaki   |Wicked   ||Tyrant |Archdemon/Archfiend ||Meta          |Metahuman
|Touki  |Warrior  ||Lady   |Mother    ||Haunt/Ghost   |Revenant
|Genma  |Liminal  ||Zealot |Madman    ||Fury          |Destroyer/Omega
|Spirit |Wraith   ||Vile   |Devil     ||UMA           |Cryptid
|Flight |Bird     ||Divine |Angel     ||Holy          |Guardian
|Fairy  |Fae      ||Femme  |Fatale    ||Avatar        |Beast God/Eidolon
|Snake  |Drake    ||Night  |Nightmare ||Avian         |Herald
|Drake  |Wyrm     || | || |

Additionally, I prefer to change **Mother Harlot → Whore of Babylon** whenever possible. I'm familiar the second name but I've never heard the first outside of SMT.

## Patches
### SMT1
Hit a snag due to an inability to find an English translation-compatible ROM to work with. I'd like to do the PSX version now that there's an English translation out for it, but [I can't decompress the text data.](https://forum.xentax.com/viewtopic.php?p=193294#p193294) Contact me if you know how to do so.

### SMT2
IPS patch can be downloaded here or on [Romhacking.net](https://www.romhacking.net/translations/6712/). The patch also includes my quality-of-life improvements to the original Aeon Genesis translation patch, mainly because they let you actually see the fancy new race names. Atlas instruction files are included here if you would like to make your own edits.

### SMT if
IPS patch can be downloaded here or on [Romhacking.net](https://www.romhacking.net/translations/6733/). Atlas instruction files are included here if you would like to make your own edits.

There are currently some problems with race names getting truncated in the fusion screen, which only allows race names up to 8 characters. This could be fixed with a subroutine to print shortened forms, like what already exists for demon names and items, but I don't know how to do that.

### SMT3
* **Switch**: If you have a Switch CFW that supports LayeredFS, the modded file can be downloaded here or on [GameBanana](https://gamebanana.com/mods/458671). I have also included the text files if you want to make your own edits; they can be added to the common_en file with Unity compilation programs such as UABE Avalonia.
  * The file provided here also provides more detailed Magatama info (advanced counterparts of basic Magatama are labeled as such, notes that Sophia teaches you both healing and Light magic, etc.) and capitalizes stat abbreviations, because I think it looks better that way. If only want one of the changes, you'll have to dump a fresh common_en file from your game and manually import the specific text files you want.
* **PC**: I don't have access to this version, but I would like to mod it if possible.
* **PS2**: I've judged this unnecessary for now given the existence of the HD version.

### SMTV
If you have a Switch CFW that supports LayeredFS, the modded file can be downloaded here or from [GameBanana](https://gamebanana.com/mods/477191). The relevant uasset files are also provided here if you would like to make your own edits.

### Digital Devil Saga
xDelta patches can be downloaded here or on Romhacking.net ([DDS1](https://www.romhacking.net/hacks/7935/), [DDS2](https://www.romhacking.net/hacks/7916/)).

### Devil Survivor
xDelta patches can be downloaded here or on [Romhacking.net](https://www.romhacking.net/hacks/8008/). Cartographer text dumps are provided here if you'd like to make your own edits; note that the game uses SHIFT-JIS encoding, for which a table has been provided in the root directory. (No Atlas this time, because I stupidly didn't realize Atlas would work until after I had done everything by hand.) Patches for *2* and *Overclocked* are in progress.

## Explanations
Reasoning documentation for all the changes.

* Megami translates directly to "Goddess".
* Jirae is a Romanization of the Japanese *Chirei* (地霊), which Google tells me means "Earth Spirit". That certainly describes the creatures included under the race. "Gaian" would have been perfect, but that's already taken by followers of the Ring of Gaea; maybe that's why the localizers gave up? Since English doesn't have a good term for this I also gave up and used a foreign loanword: "Erdgeist", the German word for the same concept. Unfortunately, at 8 characters this one is too long for some games. Alternates:
  * "Terran", which technically fits but its predominant association in pop culture is what aliens call humans.
  * "Earthen", but I don't like adjective race names and it may look too similar to "Erthys".
* Jaki (邪鬼) is literally "Evil Demon" according to Google. That sounds redundant in English, and any variant on "demon" is going to be tortured when this is a game where everything is a demon. I chose to just emphasize the "evil" part to settle on "Wicked", which also works as a noun.
* Yoma (妖魔) means "Mystical Demon" or "Apparition" according to Google. I assume this word refers to a concept that doesn't translate well to Western mythology, but given the specific demons included in the race (mystic beings like djinn and minor gods like apsaras) I feel the general "Spirit" covers them.
* **Spirit → Wraith**: Of course, that means we have to change the "Spirit" race. "Spirit" does not at all convey that these are specifically supposed to be *evil* spirits, which is important because players need to know which races are and aren't friendly. I think the more menacing "Wraith" conveys this.
* Touki (闘鬼) means "Battle Spirit" according to Google. They're the neutral counterpart to the Brute race, which I think "Warrior" conveys. Pretty baffled why the official localization gave up on this one.
* Genma (幻魔) means an illusory creature. [Eirikr](https://personacentral.com/nocturnal-revelations-the-legacy-of-shin-megami-tenseis-first-localization-part-2/) proposes a translation of "Liminal", which I like; it's an adjective, but one that works as a noun.
* **Entity → Ancient** because that's what they are. The Japanese (威霊) means "Spirit of Authority", which doesn't fit with the actual members of this race in my opinion.
* **Godly → Almighty** because come on, this is *the* God we're talking about here. I can see why the localization used the more waffling "godly", as the Japanese is "Godly Spirit" (神霊) rather than the Japanese word for "god", but seriously. If we're supposed to believe YHVH is on a different level than all the other gods we encounter, his race name better have some oomph to it. "Almighty" has the bonuses of being a Christian term, a common epithet for Yahweh, and connection to the in-game Almighty element.
* **Divine → Angel** & **Herald → Archangel** because that's what they are (and what they are in Japanese). I can understand why the localizers didn't translate them this way; it creates confusion with the Angel and Archangel demons, the former of which is becomes the absurdity that is "Angel Angel". The Japanese got around this by writing the race names in kanji and the demon names in katakana, but English has no equivalent trick. My solution is to change the "Angel" demon to "Angelus", which is the Latin word for it.
* **Tyrant → Archdemon**: The Japanese (魔王) means "Demon Lord" and I felt that leaving out the "demon" part in a game about demons is a glaring oversight. I can see the reasoning here if you interpret "demon lord" as "evil lord", but come on. These are the big bad major story bosses, they need more oomph. "Archdemon" works well for this purpose, and as a bonus makes for a nice parallel with "Archangel", as the two races are of approximately equal importance.
  * Alternate: **Archfiend**, which saves a few pixels in VWF. I don't like this because it creates a false connection with the "Fiend" race, but sometimes space limitations require it. (And, admittedly, it does sound cooler than "Archdemon".)
* **Meta → Metahuman** should be self-explanatory.
* **Flight → Bird** should need no explanation. Why they didn't do it that way in the first place is beyond me. "Flight" is an action, not a creature, Atlus.
* **Wood → Flora** should need no explanation. This is basically the Pokemon "Grass" problem all over again. What may have tripped them up is that the Japanese (妖樹) means "tree", but the race obviously covers way more plants than just trees (and there's the issue that the "good" plant race is already localized as "Tree"). I would also like some way to convey that they're evil, but I can't think of any words for "evil plant". Possible alternatives:
  * "Weed" would at least somewhat convey the evilness, but makes them sound minor and pathetic when the race does contain quite powerful demons.
  * "Toxic" would convey the evilness well, but the plant connection is weaker. "Toxic" sounds like it should encompass general gross or slime monsters as well.
  * "Maneater" conveys evilness and has a connection to the idea of man-eating plants, but it's a weak connection.
* **Avian → Herald**: This one I'm still workshopping. The Japanese (霊鳥) means "Spiritual Bird", which English does not have a concise term for. "Herald" is at least not just a synonym for "Bird", but its bird connection is tenuous. Really hard to think of a one-word term for this.
  * GameBanana user Sanda_Cracker0803 [has another proposal](https://gamebanana.com/posts/11076803): "Wonder", based on the archaic term "bird of wonder" used to refer to the phoenix. It's still a stretch, but avoids confusion with the vanilla Herald race. 
* **Avatar → Beast God**: When I hear "avatar" I just think of a human avatar, not an animal one. Probably because Western culture is so Christian, and Christianity doesn't have a lot of positive associations with animals? The race is primarily composed of demons who are just straight-up gods, so "Beast God" seems the most accurate.
  * For games with harsher text limits, **Eidolon** is a big stretch, but hopefully the overlap between SMT and Final Fantasy players is enough to lean on the latter's use of the word.
* **Wilder → Monster** because "wild" does not mean "evil" and the entire point of these things is that they're the evil counterpart to the Beast race. "Monster" hopefully better conveys that they are not to be messed with.
* **Holy → Guardian** because you can't just throw out the word "holy" and expect people to assume it means "holy beast", Atlus. "Guardian" isn't *uniquely* beastly, but animals are used to guard things and this conveys that they are specifically good dogs. I lengthen it to "Guardian Beast" where possible to avoid ambiguity.
* **Snake → Drake** & **Drake → Wyrm**: So, the main problem with the dragon races are that they're basically "good dragon (竜神), neutral dragon (竜王), evil dragon (邪竜)", but English doesn't have a concept of a "good dragon"; pretty much all dragon words have evil or monstrous connotations. Since the Dragon race is unilaterally comprised of Eastern dragons hopefully that minimizes confusion there, but then what do you call the others? I don't like "Snake", because the connection is less obvious in English than it is in Japanese, as snake demons and dragons are pretty distinct things here. I think "Drake" works to convey the idea of a "lesser dragon", but then we need a new name for the evil dragons. I used "Wrym" because, well, it just sounds eviler in my opinion, and it also conveys the image of a slithering snake creature, preserving that aspect.
* **Fairy → Fae**: The Aeon Genesis *SMT: if* translation makes this change with the reasoning that people associate "fairy" too much with the specific image of a pixie, and that this is better because it's a more general word. I agree with this. (Unfortunately, Aeon Genesis made the mistake of using "Fey" when they meant "Fae", so I have to fix that in the *SMT: if* patch too.)
* **Lady → Mother** is because the Japanese (地母神) means "Mother Goddess", at least according to Google, which I'm inclined to believe because that's what members of this race are. I'm honestly baffled the official localization didn't go with this, especially given how confusing "Lady" is when "Femme" also exists. I was very confused whether the two were supposed to be related the first time I played.
  * Conflict: "Mother" is also Mem Aleph (*Strange Journey*)'s race. Personally, I don't care about this too much. Not every final boss needs to have a truly unique race. If space limits permit, it might be possible to change it to "Great Mother", since she can't be obtained by the player so menu space contraints are not an issue.
* **Fury → Destroyer** or **Omega** is to avoid confusion with the Greek Furies, which are also present in the franchise.
  * "Destroyer" can run into text limits in some games, so "Omega" is a more economical alternative. (Unfortunately, thanks to my knowledge of the ABO fandom, I can't use it with a straight face.)
* **Night → Nightmare** should hopefully need no explanation. The only issue is character limits, as some games are limited to 7 characters or even less.
  * To avoid confusion, the "Nightmare" demon can be renamed to "Marre", an older name for the same creature.
* **Femme → Fatale**. I think this is supposed to mean "femme" in the context of "femme fatale", but I'd rather make that explicit. The feminine ending on "Fatale" combined with the demons all being women should make the connotation clear, I think.
* **Vile → Devil**: The Japanese (邪神) means "Evil God" according to Google, so I assume they were using "vile" in the sense of "morally vile". However, I'm going to go out on a limb here and say that the vast majority of people think "gross" when they hear "vile", not "immoral". I initially thought this was related to the Foul race because the words mean the same darn thing. "Devil" expediently conveys both the "evil" and "godlike" components.
  * Conflict: "Devil" is also Lucifer's race in SMT3. Probably not a huge issue.
* **Zealot → Madman**: The Japanese is "Mad God" (狂神), and "Madman" better telegraphs the maddening requirements needed to fuse them. (Deeply confused how "Zealot" is a remotely appropriate translation here.)
* **UMA → Cryptid**: Means the same thing but doesn't send players scrambling to look up an acronym.
* **Haunt → Revenant**: This race always confused me a lot. They're different from Undead, somehow, and they're called ghosts, even though they contain obviously corporeal entities like ghouls (and literal ghosts are covered by a different race). I think the idea is that they are the same person who has come back, while Undead are a demon pupetting an unrelated corpse? If so, "Revenant" conveys that.
* **Foul → Wretch**: As with "Holy", I don't like using adjectives as race names. I feel that "wretch" conveys a stronger image, and better communicates that they are weak, pathetic failures.
  * Alternative: **Anathema**, **Pariah**, or **Abomination**. The Japanese (外道) literally means "Wrong Path", but colloquially means heterodoxy or heresy. The idea of these things being heretical by their nature is so interesting, and that's not at all conveyed by just calling them "foul". However, I feel like "Anathema" and "Pariah" make them sound too important, which conflicts with their patheticness. "Abomination" would be perfect, but it's way too long.

### Game-Specific Races
#### Shin Megami Tensei II
* **Jirae → Dwarf** (rather than "Terran") due to the elves vs. dwarves subplot making that feel more apropos. (Note that I couldn't change the message strings, so the NPC dialogue and such will still call them "Chirei".)
* **Godly → The One God**. This is accurate to YHVH's title in Megami Tensei II (唯一神, "Only God"), and given SMT2 both echoes this beat from MT2 and features YHVH at his most villainous, I wanted to use this instead of the less dramatic "Almighty". (Also, it's hilariously ironic given SMT2 features two YHVHs.)
#### Shin Megami Tensei III
* **Vile → Wicked** (rather than "Devil") to preserve the grammar of the negotiation dialogue "You're talking to me knowing I'm Vile?" As there is no Jaki race in SMT3, this isn't an issue.
* **Haunt → Undead** rather than Revenant because there's no regular Undead in SMT3.
* **Corpus → Body** means the same thing but is less pretentious.
* **Zoa → Splinter**: I have no idea what the localizers were trying to convey, but the Japanese is "Separated Soul" (分霊, used to refer to the division of Shinto gods when moving them between temples) and this conveys the idea they're born of Albion, which is kind of important to understanding his gimmick.
* **Hallel → Redeemed**: "Hallel" is a *prayer*; using it to denote a class of creatures is nonsensical. It's like they were desperately scraping the bottom of the barrel for whatever vaguely Judeo-Christian word hadn't been used already. The Japanese is "Seraph", which is also dumb because that's not what they are. I'm just going to go with "Redeemed" because that *is* what they are.

Additionally, the Demi-fiend's unique races were changed. Few of these are accurate to the Japanese, but the Japanese is mostly word salad as far as I can tell, so I chose to focus on making their alignments clearer. I generally "punched up" the titles to give them more oomph, and tried to follow a pattern of tier 1 = followers/initiates, tier 2 = spiritual leaders, tier 3 = supernaturally empowered humans, and tier 4 = gods.
* **Votary → Paladin** & **Soldier → Brute**
* **Expert → Master** & **Battler → Heretic**
* **Saint → Messiah**, **Master → Ascendant**, & **Slayer → Antichrist**
* **Spirit → Almighty** (Japanese is the same term localized as "Godly" elsewhere), **Phenom → Deity**, & **Lord → Devil**
* **King → King of Kings**, because "King" alone does not have the punch of conveying you are *stronger than God*. This has the double bonus of being both a Jesus reference and a logical description of the rank that requires you to be master of everything.
#### Shin Megami Tensei V
* **Haunt → Wraith** rather than Revenant because there's no Spirit race and they are primarily composed of demons who are classified as Spirit or Ghost in other games.
* **Matter → Ehyeh** (Hebrew for "I am" and one of the names of God). "Matter" is a technically correct translation for 事象 (which broadly just means "thing"), but I felt that was neither relevant nor logical for Lucifer. "I am" matches the (I asssume) deliberate understated simplicity of 事象 and can also be read as an echo of the phrase "I think, therefore I am," which is relevant to the game's theme of Knowledge being a fundamental part of gods' personhood. As a bonus, it matching one of God's names is very fitting for certain spoilery reasons.
  * Credit goes to **@tgam2005** on the SMT modding Discord for this suggestion.
* **Omagatoki → Witching Hour** because that's what "Omagatoki" means. I cannot fathom the balls-out confidence the SMT localizers must have to claim they can't translate a term Google Translate can, but I continue to do their job for them.
* Angel's fusion message is tweaked to avoid referencing the Angel race, making it sound less clunky.
* Whore of Babylon's fusion message is slightly changed to reduce repetitiveness.

Additionally, Lahmu's title card still introduces him as "Vile". This title is a texture rather than text, so I can't edit it without additional tools.
#### Soul Hackers
* **Great → Great Spirit** because that's literally what Manitou is and literally what the Japanese (大霊) is. Stop using adjective names, localizers, this is an enemy-exclusive race, you don't have to abbreviate it.
#### Digital Devil Saga
* **Fiend (DDS1) / Nether → Mystic**. "Fiend" is a different race in the rest of the franchise, so it was a very poor choice in this case. The Japanese is just "Demon Tribe" (魔族) which isn't helpful, but the term is translated as "Magica" elsewhere in the series and its constituents are specifically the most mystical/magical/esoteric demons.
* In DDS1, **Demon → Brute** & **Evil → Icon** for consistency with DDS2.
* **Light → Angel** is self-explanatory.
* **Death → Reaper**: The Japanese is "shinigami", which is translated as "Reaper" in the rest of the series.
* **Fury & Tyrant → God**: These are the titles for Vishnu and Shiva, respectively. They make no sense for either (Vishnu is a *preserver*, not a destroyer; Shiva is not a "demon lord"), so I just gave them the same title as Brahman since they're part of Brahman in Hindu theology.
* **Fiend (DDS2) → Judge**: In Japanese Satan's title is the same word used for "the Devil", which makes no sense when he is not only a different being from Lucifer but of opposite alignment in SMT. I'm making an executive decision and giving him a completely different title that fits his actual identity.
#### Devil Survivor
* **Avatar → Mythic** (rather than Eidolon) because there's no Holy race to conflict with it and "Eidolon" was too long. (Also, most of the demons under this race are Holy in other games anyway.)
* **Snake → Wyrm** (rather than Drake) because the demons under this race *are* genuinely snakelike (with the exception of Pendragon), so I chose the term that maintains a sense of slithery worminess.
* **Touki → Brute** (rather than Warrior) because there's no Brute race to conflict with it and most of the demons under this race are considered Brutes in other games.
* **Avian** remains unchanged due to the absence of other bird races.

Additionally, I took a few liberties with the demon birth messages, since they're unique to each demon in Devil Survivor. Heqet introduces herself as a "beast god", Airavata as a "divine steed", and Lucifer as "king of Hell". I think this is better for the demons who don't quite fit with the established names, especially since DeSu lumps a lot of races together.
#### Strange Journey
* **Awake → Awakened**. Why do the localizers love adjective races so much?
* **Empty → Void**. It keeps happening! The Japanese is "Nihilistic Great Spirit" (虚大霊) for the curious, so "Nihilist" would also be valid.
* **Soil → Terran**. The *one* time they manage a noun name and it's this mess. The Japanese is "Great Person of the Earth" (大地人).
* **Root → Almighty** because the Japanese is the same term that's localized as "Godly" in the rest of the series. What were the SJ localizers smoking, seriously?

## Further Work
I would also like to change the title image for the games to "Resurrection of the Goddess" or "Revelations", because it really grinds my gears that the title was left untranslated even though it has a direct English translation. However, this would require graphic design work, which I have no skill in.
