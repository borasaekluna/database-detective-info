# database-detective-info
The official GitHub repository for information about the Database Detective: Minor Crimes Division game.

Database Detective is out NOW on Steam!
https://store.steampowered.com/app/3950130/Database_Detective_Minor_Crimes_Division

## Solo Dev Q&A & Behind-the-Scenes (Database Detective Release Celebration) Highlights
An expandable FAQ/Q&A highlights from the official livestream event. Answers include a combination of paraphrasing and direct quotes.

Watch the full livestream VOD on Twitch at [https://www.twitch.tv/moonchildofthenorthforest](https://www.twitch.tv/videos/2824080943)
or on YouTube at [https://www.youtube.com/playlist?list=PLUqUtyhvpF_4](https://www.youtube.com/playlist?list=PLUqUtyhvpF_4)

## Directly DBD Related

<details>

<summary> Question </summary>

### Add a header (optional)

Answers go here (can use other markdown: code blocks, images/screenshots from stream VOD, etc)

</details>

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
Not really, honestly. I don’t really view other indie games as competition, and I don’t think that one of our games would really overshadow the other. We were actually in talks of doing a bundle before their release date got announced, so we were already in touch.

What’s funny, though, is that the date was very specific. The general idea is that you don’t want to release your game during Next Fest. If your game is upcoming, it’s basically free publicity, so there’s no reason not to have your game be part of Next Fest. Your game has to be upcoming and not already released. 

Then it just so happened that we had basically the same exact plan, which was a funny coincidence. And there were also a lot of detective games coming out that week, which was crazy. There were like five detective games released that week.

</details>

<details>

<summary> How many emails have you gotten from the "HelpMe" website? </summary>

### How many emails have you gotten from the "HelpMe" website?

A lot of emails. It’s funny, because I’m going to make some short social media content about this, which was kind of the intention. I remember someone subscribed me to the Taco Bell newsletter. Someone sent me a photo of their face, which I thought was funny. It was just a weird little thing.

You know what’s funny? I’ve talked to Luna about this. That email used to be my phone number. I actually had my phone number attached to it. The idea is that it feels more personal, which makes it more fun. But yeah, you could dox me very easily. 

*Sorry to anyone who would've wanted to call Thomas /j*

</details>

<details>

<summary> Question </summary>

### Question

Answer

</details>

<details>

<summary> Question </summary>

### Question

Answer

</details>

<details>

<summary> Question </summary>

### Question

Answer

</details>

<details>

<summary> Question </summary>

### Question

Answer

</details>

<details>

<summary> Question </summary>

### Question

Answer

</details>

<details>

<summary> Question </summary>

### Question

Answer

</details>

<details>

<summary> Question </summary>

### Question

Answer

</details>

<details>

<summary> Question </summary>

### Question

Answer

</details>



