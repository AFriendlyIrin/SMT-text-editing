# Demon Races
The English demon race names felt off to me from the first MegaTen game I played, and I feel they are overall very poor localizations that obscure important information about the races and how they relate to one another. (To say nothing of all the races they didn't even bother to translate at all. >_>) Be honest: Did you know that "Beast", "Avatar", "Holy", and "Wilder" were all part of the same family before you looked it up in a guide? The Japanese words for those races are all variants on "beast", so the connection is obvious. Many demon races and families are similar.

So, I've taken it upon myself to make patches for the various SMT games that change the demon races to names I think are better.

I don't know Japanese myself, so I can only go off machine translations to get an idea of the original race names. I'm aware this means I'm likely missing tons of nuance and context. If you do know Japanese and can think of better translations, please tell me!

## Name Changes
|Original |New |&nbsp; |Original |New
|--- |--- |--- |--- |---
|Megami |Goddess  ||Entity |Forgotten
|Jirae  |Terran   ||Godly  |God
|Jaki   |Maneater ||Tyrant |Devil
|Touki  |Warrior  ||Lady   |Mother
|Genma  |Phantom  ||Fury   |Destroyer
|Yoma   |Spirit   ||Wood   |Plant
|Spirit |Wraith   ||Vile   |Wicked
|Divine |Angel    ||Avatar |Beast God
|Herald/Seraph |Archangel ||Wilder |Monster
|Flight |Bird     ||Holy   |Mythic
|Avian  |Herald   ||Fairy  |Fey
|Snake  |Drake    ||Night  |Nightmare
|Drake  |Wyrm     ||Femme  |Fatale             
|Haunt/Ghost  |Revenant ||Foul   |Wretch

## Patches
### SMT1
Coming soon.

### SMT2
IPS patch can be downloaded here or on [Romhacking.net](https://www.romhacking.net/translations/6712/). The patch also includes my quality-of-life improvements to the original Aeon Genesis translation patch, mainly because they let you actually see the fancy new race names. Atlus instruction files are included here if you would like to make your own edits.

### SMT if
IPS patch can be downloaded here or on [Romhacking.net](https://www.romhacking.net/translations/6733/). Atlus instruction files are included here if you would like to make your own edits.

There are currently some problems with race names getting truncated in the fusion screen, which only allows race names up to 8 characters. This could be fixed with a subroutine to print shortened forms, like what already exists for demon names and items, but I don't know how to do that.

### SMT3
* **Switch**: If you have a Switch CFW that supports LayeredFS, the modded file can be downloaded here. I have also included the text files if you want to make your own edits; they can be added to the common_en file with Unity compilation programs such as UABE Avalonia.
* **PC**: I don't have access to this version, but I would like to mod it if possible.
* **PS2**: I have no idea how to mod PS2 games.

Notes:
* The Phantom demon is renamed to "Wraith", because the Spirit/Wraith race is not present in this game.
* I changed Haunt to "Undead" rather than "Revenant", since there is only one type of undead here.
* The Tyrant race is unchanged so that Lucifer can remain a special boy.

### DS/3DS games (Strange Journey, Soul Hackers, Devil Survivor)
Progress currently stalled, as Atlus DS games use nonstandard encryption. The [Atlus Packer by CUE](https://www.romhacking.net/utilities/871/) is supposed to be able to decrypt it, but it doesn't seem to work for these games. Contact me if you have a solution.

## Explanations
For the curious, here are my justifications for the changes.

* Megami translates directly to "Goddess".
* Jirae is a Romanization of the Japanese *Chirei* (??????), which Google tells me means "Earth Spirit". That certainly describes the creatures included under the race. "Gaian" would have been perfect, but that's already taken by followers of the Ring of Gaea; maybe that's why the localizers gave up? I just used the Roman word for the same thing, "Terran".
* Jaki (??????) is literally "Evil Demon" according to Google. That sounds redundant in English, and any variant on "demon" is going to be tortured when this is a game where everything is a demon. So I decided to ignore that and use a word based on the lore surrounding the included demons: Maneater. Crucially, this conveys the important information that they are evil and not open to communication, which an untranslated word does not. It does create some confusion with the Man Eater demon, though.
* Yoma (??????) means "Mystical Demon" or "Apparition" according to Google. I assume this word refers to a concept that doesn't translate well to Western mythology, but given the specific demons included in the race (mystic beings like djinn and minor gods like apsaras) I feel the general "Spirit" covers them.
* **Spirit ??? Wraith**: Of course, that means we have to change the "Spirit" race. "Spirit" does not at all convey that these are specifically supposed to be *evil* spirits, which is important because players need to know which races are and aren't friendly. I think the more menacing "Wraith" conveys this.
* Touki (??????) means "Battle Spirit" according to Google. They're the neutral counterpart to the Brute race, which I think "Warrior" conveys. Pretty baffled why the official localization gave up on this one.
* Genma (??????) means an illusory creature. "Phantom" seems a pretty cut-and-dry translation for this one. It even synergizes with their racial ability in Devil Survivor ("Phantasm").
  * To avoid confusion, the Phantom demon can be renamed to any number of other ghosty words; English has plenty.
* **Entity ??? Forgotten** because that's what they are.
* **Godly ??? God** because come on, this is *the* God we're talking about here. I can see why the localization used the more waffling "godly", as the Japanese is "Godly Spirit" (??????) rather than the Japanese word for "god", but come on. If we're supposed to believe YHVH is on a different level than all the other gods we encounter, his race name better have some oomph to it.
* **Divine ??? Angel** & **Herald ??? Archangel** are because that's what they are (and what they are in Japanese). I can understand why the localizers didn't translate them this way; it creates confusion with the Angel and Archangel demons, the former of which is now the absurdity that is "Angel Angel". The Japanese got around this by writing the race names in kanji and the demon names in katakana, but English has no equivalent trick. If you can think of some way to make that work in English, I'm all ears.
* **Tyrant ??? Devil**: The Japanese (??????) means "Demon Lord" and I felt that leaving out the "demon" part in a game about demons is a glaring oversight. I can see the reasoning here if you interpret "demon lord" as "evil lord", but come on. These are the big bad major story bosses, they need more oomph. In a setting heavily based on Christian theology, I think "Devil" packs that appropriate punch, especially because several of them are literally fallen angels. (There is the issue that in *Nocturne* Lucifer has his own unique race that is already localized as "Devil", but eh.)
* **Flight ??? Bird** should need no explanation. Why they did it that way in the first place is beyond me. "Flight" is an action, not a creature, Atlus.
* **Wood ??? Plant** should need no explanation. This is basically the Pokemon "Grass" problem all over again. What may have tripped them up is that the Japanese (??????) means "tree", but the race obviously covers way more plants than just trees. I would also like some way to convey that they're evil, but I can't think of any words for "evil plant".
* **Avian ??? Herald**: "Avian" does not at all convey that these are specifically *holy* birds, which is pretty important information for fusing them. English doesn't have a good word for this, but since "Herald" is now free, I chose to use it. It's close enough.
* **Avatar ??? Beast God**: When I hear "avatar" I just think of a human avatar, not an animal one. Probably because Western culture is so Christian, and Christianity doesn't have a lot of positive associations with animals? Using two words for a race is awkward and pushes up against character limits, but I didn't feel anything else was right for a race that includes literal gods like Anubis.
* **Wilder ??? Monster** because "wild" does not mean "evil" and the entire point of these things is that they're the evil counterpart to the Beast race. "Monster" hopefully better conveys that they are not to be messed with.
* **Holy ??? Mythic** because you can't just throw out the word "holy" and expect people to assume it means "holy beast", Atlus. "Mythic" is still an adjective, which is awkward, but the jump to "mythical beast" is a much smaller one. Given the race includes things like unicorns, I feel it's also more accurate.
* **Snake ??? Drake** & **Drake ??? Wyrm**... Well, the main problem here is that the dragon races are basically "good dragon, neutral dragon, evil dragon", but English doesn't have a concept of a "good dragon"; pretty much all dragon words have evil or monstrous connotations. Since the Dragon race is unilaterally comprised of Eastern dragons hopefully that minimizes confusion there, but then what do you call the others? I don't like "Snake", because the connection is less obvious in English than it is in Japanese, as snake demons and dragons are pretty distinct things here. I think "Drake" works to convey the idea of a "lesser dragon", but then we need a new name for the evil dragons. I used "Wrym" because, well, it just sounds eviler in my opinion, and it also conveys the image of a slithering snake creature, preserving that aspect.
* **Fairy ??? Fey**: The *SMT: if* translation makes this change with the reasoning that people associate "fairy" too much with the specific image of a pixie, and that "fey" is better because it's a more general word. I agree with this.
* **Lady ??? Mother** is because the Japanese (?????????) means "Mother Goddess", at least according to Google, which I'm inclined to believe because that's what members of this race are. I'm honestly baffled the official localization didn't go with this, especially given how confusing "Lady" is when "Femme" also exists. I was very confused whether the two were supposed to be related the first time I played.
* **Fury ??? Destroyer** is to avoid confusion with the Greek Furies, which are also present in the franchise.
* **Night ??? Nightmare** should hopefully need no explanation. I can only assume the official localization shortened it because of character limits, but by now most of the games can handle 9-character strings.
  * To avoid confusion, the "Nightmare" demon can be renamed to "Marre", an older name for the same creature.
* **Femme ??? Fatale**. I think this is supposed to mean "femme" in the context of "femme fatale", but I'd rather make that explicit. The feminine ending on "Fatale" combined with the demons all being women should make the connotation clear, I think.
* **Vile ??? Wicked**: The Japanese (??????) means "Evil God" according to Google, so I assume they were using "vile" in the sense of "morally vile". However, I'm going to go out on a limb here and say that the vast majority of people think "gross" when they hear "vile", not "immoral". I initially thought this was related to the Foul race because the words mean the same darn thing. If the emphasis is supposed to be that they're evil, then they should have a word that conveys that unambiguously.
* **Haunt ??? Revenant**: This race always confused me a lot. They're different from Undead, somehow, and they're called ghosts, even though they contain obviously corporeal entities like ghouls (and literal ghosts are covered by a different race). I think the idea is that they are the same person who has come back, while Undead are a demon pupetting an unrelated corpse? If so, "Revenant" conveys that.
* **Foul ??? Wretch**: As with "Holy", I don't like using adjectives as race names. I feel that "wretch" conveys a stronger image, and better communicates that they are weak, pathetic failures.
  * Alternative: **Anathema**, **Pariah**, or **Abomination**. The Japanese (??????) literally means "Wrong Path", but colloquially means heterodoxy or heresy. The idea of these things being heretical by their nature is so interesting, and that's not at all conveyed by just calling them "foul". However, I feel like "Anathema" and "Pariah" make them sound too important, which conflicts with their patheticness. "Abomination" would be perfect, but it's way too long.
