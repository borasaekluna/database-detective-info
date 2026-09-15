# Database Detective Info 
`database-detective-info` is the official GitHub repository for information about the [Database Detective: Minor Crimes Division](https://store.steampowered.com/app/3950130/Database_Detective_Minor_Crimes_Division) game.

**Instagram** [https://www.instagram.com/databasedetective/](https://www.instagram.com/databasedetective/)
**YouTube** [https://www.youtube.com/@thomashsuster](https://www.youtube.com/@thomashsuster)
**TikTok** [https://www.tiktok.com/@database.detective](https://www.tiktok.com/@database.detective)

[Database Detective Trailer](https://youtu.be/LuWbSgne2bw?si=fAeTA5fFkkWauqT-)
[Database Detective on Steam](https://store.steampowered.com/app/3950130/Database_Detective_Minor_Crimes_Division)

Solo Dev Q&A & Behind-the-Scenes (Database Detective Release Celebration)
Available to watch on Twitch & YouTube!
Twitch [https://www.twitch.tv/moonchildofthenorthforest](https://youtube.com/playlist?list=PLUqUtyhvpF_4&si=dd_6gbnHriuDDRDu) 
*(full livestream VOD)*
YouTube [https://www.youtube.com/playlist?list=PLUqUtyhvpF_4](https://www.youtube.com/playlist?list=PLUqUtyhvpF_4)
*(playlist of 15-minute segmented videos from the full VOD)*

## Jump to:
[General FAQ (incl. some pre-release questions)](https://github.com/borasaekluna/database-detective-info/blob/rough_01/README.md#general-faq-incl-some-pre-release-questions)

[Solo Dev Q&A & Behind-the-Scenes (Database Detective Release Celebration) Highlights](https://github.com/borasaekluna/database-detective-info/blob/rough_01/README.md#solo-dev-qa--behind-the-scenes-database-detective-release-celebration-highlights)

[Directly DBD Related](https://github.com/borasaekluna/database-detective-info/blob/rough_01/README.md#directly-dbd-related)

[Bonus / Extra Questions](https://github.com/borasaekluna/database-detective-info/blob/rough_01/README.md#bonus--extra-questions)

We've created our multi-purpose Feedback Form (bug reports/feature requests/other suggestions/etc) here: 
[https://forms.gle/jzoHDEPSmvUTxZP78](https://forms.gle/jzoHDEPSmvUTxZP78)
This has our most preferred #1 method (most organized/efficient), so please do prioritize the form (instead of Steam/Discord) if you can~


<!-- Q&A TEMPLATE
<details>

<summary> Question </summary>

### Add a header (optional)

Answers go here (can use other markdown: code blocks, images/screenshots from stream VOD, etc)

</details>
-->

## General FAQ (incl. some pre-release questions)

<details>

<summary> Game release when? </summary>

### Game release when?

July 17th, 2026

</details>

<details>

<summary> But at what cost?! </summary>

### But at what cost?!

Only $12.75 during two-week 15% launch discount, then returning to $14.99 base price. *(Prices will be localized by purchasing power.)*

</details>

<details>

<summary> Localization (languages/translations)? </summary>

### Localization (languages/translations)?

No plans for localization *for now*... The game has a *lot* of specific graphics and hand-drawn designs, that would be quite complicated to rework/redesign, especially for a small indie game/developer. Some cases are specifically really hard to localize since they incorporate wordplay that would be hard to translate into other languages. `(RELEASE UPDATE: Potential community contributed localization plan... We'll announce this when we are ready.)`

</details>

<details>

<summary> I know some SQL already, but my query won’t work?? </summary>

### I know some SQL already, but my query won’t work??

There’s actually lots of different versions/spinoffs of SQL languages! So there may be some small differences between whichever one you know and the one used in DBD, but most of it should be very similar. The game uses SQLite! *Some syntax may not be included depending on complexity/advanced (see next question response).*

</details>

<details>

<summary> Will there be (advanced SQL syntax example here)? </summary>

### Will there be (advanced SQL syntax example here)?

The base game is meant cover/include SQL that would be part of something more like an introductory course, so players from various backgrounds & skill levels can still have fun with this detective game! (*If* we were to design some bonus cases/challenges with advanced SQL, it would probably make more sense as a DLC/optional add-on, but not requiring advanced skills in order to complete the main game. *But no plans for that at the moment.*)

</details>

<details>

<summary> What happens if I choose the wrong suspect? </summary>

### What happens if I choose the wrong suspect?

~~If you get a single case wrong, the game will move on and you'll get a message from your supervisor. If you give additional wrong answers, you'll get the chance to submit another answer.~~ It's actually a bit complicated to explain the consequences exactly, *but maybe it's best if you don't arrest the wrong suspect, eh Detective? We ARE doing very serious work here, you know.*

</details>

<details>

<summary> Can we replay cases/levels or skip to specific ones? </summary>

### Can we replay cases/levels or skip to specific ones?

~~In the current version of the full game, you will only unlock the ability to replay specific cases after you've completed all of the existing ten, but this may change in future updates.~~ `(RELEASE UPDATE: You can now skip to levels that you've completed at any time.)`

</details>

<details>

<summary> How come my friend and I have different data? </summary>

### How come my friend and I have different data?

Some details/data within cases are randomly generated, including the names of the suspects and the tables themselves.

</details>

<details>

<summary> I really enjoyed the game! Is there any way for me to directly support/donate you as a solo developer (like Kofi, Patreon, or even a Steam Supporter Pack DLC, etc)? </summary>

### I really enjoyed the game! Is there any way for me to directly support/donate you as a solo developer (like Kofi, Patreon, or even a Steam Supporter Pack DLC, etc)?

> Thank you so much! The best way to support me is to purchase the game and wishlist what I make next. Purchasing through Steam directly also has its benefits, as it impacts how much Valve promotes the game algorithmically (through the Discovery Queue, daily deals, etc) so you're still helping me in that way! 

*(and of course, you can spread the word to your friends/family/coworkers/teachers/students/etc, which a lot of you have already been doing! :o7:  It's been super fun reading your stories about it^^)*

</details>


## Solo Dev Q&A & Behind-the-Scenes (Database Detective Release Celebration) Highlights
An expandable FAQ/Q&A highlights from the official livestream event. Answers include a combination of paraphrasing and direct quotes.

Watch the full livestream VOD on Twitch at [https://www.twitch.tv/moonchildofthenorthforest](https://www.twitch.tv/videos/2824080943)
or on YouTube at [https://www.youtube.com/playlist?list=PLUqUtyhvpF_4](https://www.youtube.com/playlist?list=PLUqUtyhvpF_4)

## Directly DBD Related

<details>

<summary> Do cases rerandomize when you restart? </summary>

### Do cases rerandomize when you restart?

Yes, they do rerandomize. The data itself is refreshed to a different set of data. But the queries you wrote should still work, you just need to rerun them again. The point of that was so you're not just relying on a specific answer, like "X and Y are the people responsible". You actually have to work through the case.

For example, the help that people can give is only going to be teaching you how to do it or sharing queries. But it won't be directly skipping to giving an answer key kind of thing. Since the point of the game is to use SQL, for you to experience using SQL and running queries.

</details>

<details>

<summary> Will you implement any old style virus like the one with the letters falling or windows misbehaving (like the silly software Desktop Goose 🪿 ) that will make a task more difficult? </summary>

### Will you implement any old style virus like the one with the letters falling or windows misbehaving (like the silly software Desktop Goose 🪿 ) that will make a task more difficult? 

That would be fun. Like something that messes up your query. I think that would be more annoying than anything. Because this game isn’t really mechanically goofy like that. It is kind of goofy, but not in that way. You know what’s funny? I got a comment once that said, “I just want to do SQL. I don’t want to do detective work. There’s too much detective work in this game.” So I don’t want to make things frustrating.
</details>

<details>

<summary> Can we edit saved tables queries? Like, just EDIT them.
 </summary>

### Can we edit saved tables queries? Like, just EDIT them.

With something like ALTER on a result that was saved as a table? You can’t really do that, because it’s basically just saving a result. But you can just adjust your query create a new result table.

</details>

<details>

<summary> The credits implied this but just wanted to confirm, did you voice the supervisor yourself? He's incredible. </summary>

### The credits implied this but just wanted to confirm, did you voice the supervisor yourself? He's incredible.

Thomas: No, it’s not me, unfortunately. That was a lie.
Luna: Yeah, that was a lie. It was actually me, the unpaid intern.

Yes, it was indeed Thomas himself. 

</details>

<details>

<summary> How much art outsourcing was there? </summary>

### How much art outsourcing was there?

There is no art outsourcing, except for just the inclusion/featuring of fanart on one specific website, and two icon assets from Windows 95, although some animation was added to them for the game. 

In the Moleman fans section, that was all just for this page, where I compiled fan art just for Detective Moleman. This is more like a fun little reference thing, not for the base game.

I will say that the only two assets that I did not draw are these two icons right here. The web browser and the music player. These are from the Windows 95 icon set that I just copied and pasted. They haven't gone after me yet. I hope they don't. But I did do the animation where, when you hover over it, it switches icons.

</details>

<details>

<summary> Were there any specific challenges when making the game that stuck out for you? </summary>

### Were there any specific challenges when making the game that stuck out for you?

There were a lot. You can get more specific, but drawing takes a long time. There were challenges in numerous ways. I think the hardest thing was just keeping focused. I'd been doing this part-time. There was a time when some of the cases were done, but not the book and not the parser. Because there's the whole SQL parsing that needed to be done. I was just thinking, "Oh, there's still like a year ahead." I think the programming itself was actually relatively easy, since I'm a software engineer by profession. A lot of it was the parser. 

The parser was probably the most difficult thing I had to write. That one's specifically just for the error messaging, it will let you know where the SQL goes wrong. Everything else was pretty straightforward. Even that is just a pain because of how much syntax it needs to support. And it still doesn't support a lot.

Whenever you type a query in the game and click submit, it goes through this parser, then the parser checks if what you wrote is valid SQL. The specific version of SQL backend that actually runs your query is SQLite. (That's the engine that stores the data and gives you responses.) This is something separate.

SQLite doesn't give you very good error messages. Sometimes if you write something wrong, it just says "syntax error." And you're like, "Okay, where did I go wrong?" So the idea behind this parser was that it would give you very specific error messages, so you know exactly where your query went wrong.

This is also one of the reasons why localization is going to be a pain, because there are a lot of strings that I have to extract. There's a lot of work involved in making sure all those messages are clear. Especially because when someone gets an error, you want them to understand what went wrong and how they can fix it. The goal is not just to tell someone they made a mistake, but to help them learn from it. That's kind of the whole philosophy behind the system.

It's not just a game mechanic. It's also part of teaching SQL. Because if you're learning, a generic error message isn't very useful. You need something that points you in the right direction, and that was one of the bigger challenges with making this. Balancing the accuracy of SQL with making it approachable. I had to decide what parts were important to include, and what parts would just get in the way.

</details>

## Bonus / Extra Questions

<details>

<summary> Were you worried about releasing a (albeit very different) desktop-style puzzle game on the same day as another? (referring to bundled game on Steam) </summary>

### Were you worried about releasing a (albeit very different) desktop-style puzzle game on the same day as another? (referring to bundled game on Steam)

> Not really, honestly. I don’t really view other indie games as competition, and I don’t think that one of our games would really overshadow the other. We were actually in talks of doing a bundle before their release date got announced, so we were already in touch.

> What’s funny, though, is that the date was very specific. The general idea is that you don’t want to release your game during Next Fest. If your game is upcoming, it’s basically free publicity, so there’s no reason not to have your game be part of Next Fest. Your game has to be upcoming and not already released. 

> Then it just so happened that we had basically the same exact plan, which was a funny coincidence. And there were also a lot of detective games coming out that week, which was crazy. There were like five detective games released that week.

</details>

<details>

<summary> How many emails have you gotten from the "HelpMe" website? </summary>

### How many emails have you gotten from the "HelpMe" website?

> A lot of emails. It’s funny, because I’m going to make some short social media content about this, which was kind of the intention. I remember someone subscribed me to the Taco Bell newsletter. Someone sent me a photo of their face, which I thought was funny. It was just a weird little thing.

> You know what’s funny? I’ve talked to Luna about this. That email used to be my phone number. I actually had my phone number attached to it. The idea is that it feels more personal, which makes it more fun. But yeah, you could dox me very easily. 

*Sorry to anyone who would've wanted to call Thomas /j*

</details>

<details>

<summary> Does Database Detectives take place in the same universe as Jay's Walkin'? (Thomas's previous game, available on Steam for free) </summary>

### Does Database Detectives take place in the same universe as Jay's Walkin'? (Thomas's previous game, available on Steam for free)

*Short answer: Yes. Long answer: Watch the livestream recording for the whole backstory/origins/etc.*

</details>

<details>

<summary> As follow-up to the first question, do your actions as the player character in Jay's Walkin' constitute minor crimes? </summary>

### Question

> 100%.

</details>

<details>

<summary> Does Moonchild Luna es "hijo de la luna" in Spanish? </summary>

### Question

*Maybe? I don't really know Spanish, so I'm unsure if that translates to "son/child/offspring of the moon", but the reason behind the "moonchild/moonkid" part of my name refers directly to [my story/lore of being a young moon](https://www.youtube.com/watch?v=0JPNlucxbik). As in, it's not that my parent is the (Earth's) moon, but rather that I myself am a moon that is younger than other moons. Although, masculine/feminine word language-wise ("hijo"), it works either way, as my character is meant to be sort of genderless/genderfluid as a non-human. (I'm Canadian, so I'm just basing my Latin-root-language logic off of what I know from French.)*

</details>






