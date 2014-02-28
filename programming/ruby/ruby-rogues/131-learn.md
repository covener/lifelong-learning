## 129 RR Sharpening Tools with Ben Orenstein

I’m a huge believer in the power of habits. I think the things you can manage to make yourself do regularly can have incredible results. And so, a few years ago, I’d say five years ago, I decided to get kind of serious about making my environment really excellent and improving my efficiency that way. And so, I got in this habit of spending the first ten or 15 minutes of my day on tool sharpening. And so, what I started was I started a little text file that I would add to during the day. So, when I was doing something that felt inefficient or felt like whenever I had that inkling, “There must be a better way of doing this,” I’d add it to the list. And then I’d pull one of them off in the morning.

And so, I started most mornings by just doing something simple like making an alias for a command I use in the shell a lot. Or something like, I finally need to research how the Vim expression register works and go do some diving on a readme or something like that. And I thought of it as sort of slowly sanding down the rough edges of my environment. So, anything that kind of like irked me, I would try to spend a little time on every morning. And what I found was not very long of this, I was noticeably faster at the things I needed to do every day. And it was starting to have a huge impact on my productivity. And so, I started talking about that.

__Keep a tool sharpening list.__

To me, I spend a lot of my time on my own machine. And the changes and optimizations I’ve made have sped me up substantially. In a way, it’s some of my secret sauce, I think. It’s probably why I’m so fast at certain things. My vimrc at this point is almost ten years old. It’s got ten years of improvements in there. And that’s actually pretty huge.

But I will say that I do pay the penalty, which is I’m lousy to pair with. Everything is remapped.

it’s not about speed. It’s going back to what you said earlier Ben about anything that irked you. It’s the rough edges. It’s the annoyances. 

I was actually going to say that a different way and that is it’s about flow. And if you can stay in the flow, in the groove, while you’re working, then you get more done. You feel more satisfied with what you did as opposed to when you have those interruptions. Even if they’re small ones, it breaks that flow and it interrupts the way that you work. And that’s really what it boils down to usually for me, when I optimize something like that.

I don’t know if I explicitly set out with that goal. I got lucky in picking Vim a long while back and finding out that it’s insanely customizable. But I haven’t thought about that for new tools so much, except to think that I almost could never leave Vim because of how great it is for me now.

One thing I do is I embrace my typos. Sometimes I come across a variable that shows up in my app a lot that I just cannot type correctly and I’ll just do an alias for the incorrectly typed version to the correctly typed version.

I’m pretty good at writing macros. I’m usually reasonably aggressive about using them when I have to make a bunch of changes. There’s a little bit of an art to writing a macro that you can just replay a bunch of times. It’s like writing a little generalized procedure for text editing. But once you get the hang of it, you can use them to do some pretty impressive things.

If you watch his Destroy All Software videos and stuff, he talks about it some in there. But in a project, he will just map leader keys in Vim on the fly. Like I’m doing this thing a lot where I bounce over and run this test or something and so he will just define that as leader key there while he’s working.

And if I have one-off tasks for a project, I’m pretty good at writing macros. I’m usually reasonably aggressive about using them when I have to make a bunch of changes. There’s a little bit of an art to writing a macro that you can just replay a bunch of times. It’s like writing a little generalized procedure for text editing. But once you get the hang of it, you can use them to do some pretty impressive things.

So, I can’t type initialize either. I have a thing that expands to that entire method, actually.

There’s a meditation in practicing typing. But that gets down to flow. So if you want to stay in flow, you can eliminate your mistakes or you can embrace your mistakes. So when you practice typing something correctly, you can eliminate that mistake. I sort of embrace that, “Hey, my fingers want to type initialize incorrectly all the time.” So, let’s just say that’s okay and figure out a way to get around it.

So, I have one of these typo situations where instead of git push I would type git pusa over and over again. So I said, “Okay, well this is dumb. Let me just map git pusa to git push.” So I did that for a while. And I was like, “Why am I typing such a long thing all the time?” So, I re-aliased that to g push. No, so I wanted to go to gp eventually. It was my final destination. I was like, “Okay, let’s do two characters.” Only I kept typing my old alias which was gpush, one word. So then, when I realized I wasn’t using gp, I had gpush just echo “Use gp” and then actually call gp itself. So, I got a little reminder every time I use my wrong slightly longer alias.

This is actually a really good habit. When teaching other people, when they do the long version, I try to make them do the short version afterwards three times in a row. And one of the things that I do in Vim is I disable the commands that I don’t want to be using anymore. So, if people come on my computer, I’ve disabled escape, I’ve disabled backspace, and I’ve disabled the arrow keys. And I’m working on maybe disabling hjkl.

There’s big value in that. And this is something I recommend in basically all my Vim talks, which is when I’m trying to learn a new command, if I realized I’ve missed an opportunity to use it, I’ll back up and then redo it using the correct command. Because the thing you’re trying to build is that muscle memory. You’re trying to build that automatic, “I want this to happen therefore my fingers just do the right thing.” And you don’t get that if you don’t actually think, “Hey, I need this to do this,” and then experience it happening with the right command.

Right after this call, I’m going to go disable capital Q in vim.

When I give Vim talks, I always tell people don’t use the arrow keys. 

I look at the field of things that I don’t know and determining the things that I want to level up on can be really daunting sometimes. There’s so much out there.

BEN:  It’s basically sorted by agony.

If you haven’t used Hipmunk before, it’s a service for searching flights and their default sort is agony, which I think is great. And agony is a combination of how long your layovers are, how long the total travel time is, how much it costs, and it folds in a bunch of different factors. And that’s what my sorting is by. It’s just this general sense of what’s going to give me a good payoff because I do it a lot versus how painful is it when I have to do it manually. It’s a combination of a few different things.

I’ve written a lot of Ruby over the last couple of years and I’m okay at it. I’ve written a lot of Rails apps in particular, so I’m getting the hang of Rails in general, but I haven’t forced myself into a wildly new programming paradigm in a little while. So I’m trying to be better about this. I’ve been dabbling around with Clojure and a little bit of Elixir and I have this goal of giving myself a couple of different projects that are wildly outside the realm of web programming. So I want to build a little interpreter or compiler or something, maybe some sort of graphics programming and just peel off one or two projects that are really different than what I do every day to force myself out of my comfort zone.

I’ve actually planned a retreat for myself in February. I was on Twitter lamenting that I haven’t read all of SICP, the Structure and Interpretation of Computer Programs, which is what MIT uses to teach its computation classes. And I was lamenting. I was like, “I can’t believe I haven’t read this whole thing. It’s like the bible for writing programs.” And Chris Hunt who’s someone I know from some conferences, works at GitHub, was saying, “Oh man, I had to Google what that was.” So I was like, “We should totally just get a cabin and go read that book for a couple of weeks,” and he’s like, “I’m in.” So in February, I’m going. We actually ended up choosing Costa Rica. And we got a place near the beach and we’re going to basically bring the book and not come out until we’ve read the whole thing and done a bunch of exercises.

When we talk about sharpening tools, I think about the tools that I use to write code but not my understanding of programming or my ability to write different languages. I think of those as two different things. Do you think of them more as the same thing?

That’s a good question. I don’t know. I haven’t pondered it actively. At the end of the day, it’s like how good are you at getting things done with code when you want to? So I think the tools are part of that and if you improve the tools, you’ll be a little faster for certain reasons. And if you improve the wetware of your brain by becoming a better programmer and having knowledge of more techniques and things to try, that probably also helps. So, I think if you consider it as you have one end goal which is working software that does something, I think it is just a continuum.

It really adds to your understanding of things, too. just whipping open an editor and making it do something different, once you’ve done that you get a new appreciation for how does this thing work and what can I make it do when I really want to, or things like that. And that information, you go forward with that information. In the future you may decide, “Well this is a new little mini-language I’m using, so maybe it makes sense to write a grammar for my particular editor so that it can syntax highlight it correctly,” or things like that. It expands your thinking a bit.

I did an automation one time. I have it tab complete when I’m doing ssh commands or scp commands when I’m copying a file off of a server. I went through and made it work so that I can start typing a directory name and I can tab complete it on the remote server. And it was neat to figure out what was involved in that. Obviously, I have to make some kind of connection and get a listing of the files at that point and filter it out. It was cool.

I think that this process of beginning to make the world around you conform to what you would like expands in a grand way where you start seeing yourself as someone who can affect the world. And it becomes a lot more than about your tools or about your skills or about figuring out how to write a script. But seeing that, “Oh, this thing out there in the world doesn’t work the way it should or it’s too painful or it’s too complicated, and I can fix that.”

I think I’ve always had a healthy disregard for the way things are “supposed to work”. I’ve always been a little bit of a disruptive force in the organizations I’ve been a part of. When people are like, “Well, we don’t do it that way,” or, “No, it has to be like this. You need permission from that person,” or something, I disregard that pretty wildly and frequently. So, I guess it’s not shocking that I feel that way in my tools. I feel that way in my code. I feel that way in organizations I’m in. That’s just a general mentality, I suppose.

I don’t have a lot of patience for things that seem foolish or slow or just could be improved. I’m very fortunate to be at thoughtbot which is a company that really, really embraces changing processes for the better. There’s almost no resistance towards change. If you can make a reasonable case for why it will be better, which is really an amazing thing. But I’m reasonably frequently a person that will try to make some change happen when it seems like something is broken.

I had a nightmare of a first programming job. It was a wonderful job in the sense that they took me with no experience and were willing to train me and gave me that first credential of has worked professionally as a programmer before to get me on my way. But in pretty much every other sense, it was awful.


So for instance, they gave everybody 15-inch monitors or 13-inch or some tiny screen. And being a developer, if I have more screen real estate, I will really be faster. I will make you more money if you buy me a bigger monitor. So, I made this case and was turned down. I said, “Okay, well you’re making the completely wrong decision but fine. What I’m going to do is go out and buy my own.” So, I went out and bought my own and said, “Okay, I just want to let you guys know I bought my own monitor and I’m going to be bringing this in.” And they said, “No, you can’t do that because if you do and it catches on fire, our building isn’t covered by that insurance policy so you can’t even fix this yourself.”

And there were a lot of other examples like this where the process was what the process was and they really, really didn’t want anyone to disrupt it. And I was completely miserable. And I almost got fired from this job. And I thought at the time it was because I was a really bad worker or I was really lazy or something. I felt really bad about it. But when I think back on it now and I look at what I’m able to do today, I think it was really just that I was extremely unhappy because I had no ability to shape my environment and it just completely sapped all my motivation and happiness.

I think in companies that aren’t so pathologically averse to change, then absolutely. I wouldn’t tell everyone as a blanket statement that if you’re unhappy because your job has some bad processes, you should quit. But sometimes, that is the right answer. I think maybe on average, people are a little too afraid to try to change processes where they work. I have a lot of friends that will tell me, “I can’t go over there and get this promotion because this VP hasn’t approved it,” or something.

How do you get better at pushing the right leaders? I think you just start small. It’s harder to change certain things. So I think you start with little stuff. And then you work your way up to the bigger things you want to ask for. I think that’s probably the best way to do it. For instance, the one I think a lot of people screw up is it starts with your salary negotiation. So it starts before your first day at the job. I know a lot of people that are offered X and they say, “Great, sounds good,” and then they sign and that’s it.

And if I could convince every person in the world that ever takes a job to just answer that with one thing, it’s, “Well, I was really hoping for X plus whatever,” anything that you feel comfortable with, and just see what they say, I think people on average could be making a lot more money. And so it starts with little things like that, just being willing to negotiate and push back just a hair every once in a while. And then you build up to the bigger things.

One of the things with smaller companies is that they’re not getting everything they want done anyway, so if you’re finding a way to get something done, they’re just going to thank you for it.

They also tend to have fewer codified policies and procedures. If there’s an employee handbook that officially spells out something, once they’re like, “Okay, we’re a grownup company now and we need an HR department and we need to have policies in place to handle all the scenarios that come up,” that’s when I think you tend to find the most resistance to change because it’s like, “Well it says right here in the employee handbook that no, you can’t take a month off.” But when you’re in a smaller company, they haven’t had that parental oversight come in and so you just go talk to the CEO who’s one level removed from you, or maybe two, and say, “Hey, I want to do this thing,” and they say, “Well, okay. We haven’t done this before but that’s fine.”

__I think people, they tend to not try to improve things enough. I think they also tend to not quit enough. There are so many jobs out there and there are so many different companies that have different cultures and different ways of doing things that I often see people struggling to try to make something work that is probably never going to work when the company and you would both be happier if you went and did your thing somewhere else. I think a lot of people have a fear of letting go of that job and they probably shouldn’t.__

When you’re in a tough situation, you can either move to a different situation (improve the situation) or improve yourself. So when you’re stuck in a job you don’t like, you can either fix what’s wrong with the job, you can quit and go take a different job, or you can change something about yourself, maybe it’s learning a new skill or what have you. And I think depending on what’s up in the whole situation, one of those choices is going to be better than the other sometimes. So I think that quitting is a great thing to do in a lot of cases, but it’s not like the, “Oh yeah, I just want to quit this job.”

So I think that the tool sharpening, it’s great at the technical and the scripting and the tool use level. But there’s also stuff you could do at the organizational level and process and interpersonal. Even things like, “Hey, let’s use something like Pivotal Tracker in this project,” which can change the focus of what you’re doing from, “Oh, I’m trying to bang on JIRA to get it to work right,” to, “Oh, now I’m not wasting all the time on that. We can actually spend more time talking about the issues that we’re trying to solve.”

Alfred, SizeUp (window management), Vimium for Chrome.

The thing for me is I view going to the mouse as a [cache miss]. It’s like my hands are already on the keyboard and now I have to move them all the way over to the slow part of the world. Like I’ve gone down to disk– But my hands were already on the keyboard. So if I could have done this with the keyboard then this would have been faster. I would have saved that travel time.

Kinesis keyboard.

Yeah, I think we haven’t hit the limits of human ability to control these things. Foot pedals plus a little voice control plus both hands, I think we can be folding this all together into something pretty awesome.

The most important one is I work at a standing desk at home and we have standing desks here at thoughtbot. I think the best tool sharpening is not sitting all day, because sitting is the slow death. Anything that gets you moving more is better. So when I’m sitting, I sit in the Aeron which I like, has nice support, has a keyboard tray to get my hands a little bit lower so they’re in a comfortable position and that keyboard is easy on my hands. I had some RSI issues a few years ago, which was really scary. And I actually delayed taking my job at thoughtbot because I was battling these issues and I was worried I was going to start my first day and be, “Oh, I can’t program for a couple of weeks, you guys.” So I started getting really serious about my setup. And that’s when I made those changes. Keyboard tray, Aeron chair, good keyboard. Recently added in the standing desk routine. And those have all been really good. Because the most important tool is your health. You’ve got to keep that sharp. If you’re sick or hurting, in pain, you’re not going to be able to do good work. So you’ve got to really stay on top of that stuff. And it’s so much easier to instill good habits and to try to be healthy now than to try to erase some nasty damage you’ve done by a few years of bad habits. So even if you’re not feeling these pains or worried about those right now because you’re 20 and it doesn’t seem like a big deal, I’d encourage you to try to get in good habits early and never have to worry about it.

GeekDesk standing desk.

Which is great because it goes up and down. Because standing all day isn’t awesome either. You want to be able to alternate between the two. Or at least I do. That’s what works best for me. So I mix between bouts of each. Very happy with the GeekDesk.

Vivobarefoot shoes.The theory is, look, you are an incredible machine that has been evolved over billions of years and you are designed to have your heel flat on the ground and your foot already has shock absorption, and it already has balance structures and it has support for your arch. It has everything you need and all the stuff that modern shoes give you is wrong and should be avoided. And so it’s like a seven millimeter patch of rubber that you stand on and nothing else. And it just lets your foot do its thing. And it’s already changed how I walk, which is crazy to me. I didn’t realize I was doing what they call heel striking. It’s not normal to drop all your weight on your heel as your stride moves forward. It’s more natural to place your foot down in a more balanced position and spread the weight out. But when you have shoes with thick heels on like sneakers or dress shoes, that’s the position you take. You start heel striking. So I have this as part of my gait. And I switched to these shoes and suddenly I’m slamming my heels on the ground and I can suddenly feel it for the first time. I’m like, “Wow, this is all messed up.” So I’ve been relearning how to walk, which is not something I thought I’d say at 30. But I’m totally happy with them. I feel better after wearing them. And when I stand all day in dress shoes versus when I stand all day in these shoes, it’s marked difference. It’s vastly better.

I view that with the whole tool sharpening thing, that as I dig into these processes and stuff and it has that trying these automations that I find new ways of leveraging things. I realize I no longer have to make this mistake where I forget to fire up Foreman instead of the Rails server because I have a habit to just go through this automation anyway. So if I just make that automation smart enough to make the right decision, then it just changes how things work.

Little things. We had a whole episode on coding environments where we talked about the things that weren’t writing code but the stuff that was in support of them. So I think that there’s a fair amount of overlap between that episode and what we’ve been talking about today.

I’m going to be a bit of a politician. I’m going to rephrase that question to a question that I’d rather answer, which is what’s the lamest thing I’ve done that I’m most proud of, which is my favorite remapping is I had mapped ctrl+S to the escape :w enter. So I basically gave myself a little save shortcut in vim. Leave insert mode, write the file, hit enter. And I calculated that one time. I think this saved me about a million keystrokes per programming career. And I use it, I don’t know, probably 500 times a day, maybe more. And it’s a stupid thing where it goes from escape :w enter, four keystrokes to two. But those two keystrokes get repeated so often that the savings is actually monstrous. And when you’re thinking about RSI like I am, saving a million keystrokes is a pretty big deal if you want to be programming when you’re old and gray. So that’s one of my things that I remap instantly when I’m on someone else’s computer. I just say, “I’m sorry but I have to have this command,” and then I just map C+S to that. And they’re usually okay with that.

The cool thing in this process is that you’re always measuring. You talked about how that keystroke felt natural to you, but then you’re like, “So how many keystrokes will that save me?” And I noticed in your GoGaRuCo talk you’re like, “Let’s sort my history by occurrence and stuff to see how often am I using these commands,” and stuff like that. I think that’s awesome that you have this built-in metrics analysis system.

Wow. Somebody should write a profiling tool. Like we have the profiling tools, statistical profiling where they’re just checking where your code is every millisecond or something. We could do the same thing for what we’re doing with our tools and see where we’re spending the majority of our time so that we know where to focus on.

So I have a command I run in my shell that basically pipes history and does some awking on it and does some sorting and things like that and shows me my 10 or 15 most-used shell commands. And I use that to see what I need to be more aggressive about aliasing. Like what am I typing out fully often that I don’t need to be? I don’t know of a thing like this for vim. I think Drew Neil who’s the creator of Vimcasts has started to work on this. I don’t know if he’s released it. But something that watches what you’re doing in Vim and records it and tells you, suggests optimizations that way. Because that would be handy to know.

Yeah, Josh made a pick recently for this program called Dash, a documentation viewer. And it has all these different modules you can get. Say you can have your Rails, your Ruby, your jQuery, your JavaScript documentations all in this one search bar and then you mentioned Alfred and you can install the Alfred plugins so you can literally just call up Alfred and I have it map to just an m in front of it for man. So it can just do that. And I picked it up after Josh mentioned it and was playing around with it. I can’t believe how quickly that changed things for me, just having all that documentation in one place and not having to Google it or go to the particular site that I cared about or whatever.

Kangaroo Hybrid Pro.