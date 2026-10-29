+++
title = "Ideas"
weight = 15
description = "A collection of my ideas for all kinds of things: Telegram, YouTube, education, Yandex.Radio and so on."

[taxonomies]
tags = ["ideas", "systematization"]

[extra]
image = "img/thumbnail.jpg"
button = { text = "Repository of this page", link="https://github.com/optozorax/ideas" }

[extra.translation]
from = "ru"
by = "Claude Opus 5.5"
+++

# Introduction

I constantly come up with ideas for all kinds of apps and websites. And I write them down. This page is a collection of the ones I'm not ashamed to publish on the internet. It will be updated from time to time as new ideas come up. I hope it inspires you.

I also believe that instead of criticizing, you can suggest ideas for improvement: first, it's more positive, and second, it's more constructive.

## A website for ideas

I have a dream: a website where you can suggest your own ideas to all kinds of services, upvote and downvote other people's ideas, and comment on them.

Here's how I see this website:

* You can create a section for suggesting ideas for any website or app, or even for a topic as global as school education. Sections are created by users, then moderators merge them if duplicates were created, and the actual owners, if they need it, verify an official page that they promise to monitor.
* You can subscribe to each such section, so that ideas for these services show up in your feed.
* The feed works according to the principle described below.
* Each idea can have sub-ideas, and users vote on them separately inside it.

The point of this website would also be not only to suggest ideas but to polish them to perfection. After all, one person sees an idea only from their own point of view, while another can suggest how to extend it so that it works for them too.

And of course, this website must have a section for suggesting ideas for the website itself. This comes first, because if the website for ideas can't improve itself based on ideas, why should anyone else?

I would use this website very actively, and it would become my second home after Klavogonki (a Russian online typing race site).

I'll honestly admit that I was inspired by this: [WMmail.ru](https://web.archive.org/web/20190523155023/http://wmmail.ru/index.php?cf=idea-viewallidea&type=30&i_search=0&i_name=&itype=-1&iuid=0) (in Russian).

## Ideas for Klavogonki

I became even more convinced that I want a website for ideas when Klavogonki unexpectedly got a section for suggesting ideas: [http://klavogonki.reformal.ru/proj/?mod=one](https://web.archive.org/web/20190610122840/http://klavogonki.reformal.ru/proj/?mod=one) (in Russian). I immediately wrote a whole lot.

Then, as I kept using Klavogonki, even more cool ideas came to me. *And in general, they came much more readily precisely once there was a place to write them down.* Here you can see my ideas: [http://reformal.ru/users/1311323-optozorax/?what=idea](https://web.archive.org/save/http://reformal.ru/users/1311323-optozorax/?what=idea) (in Russian).

{{ <image path="img/klavogonki.png" /> }}

But unfortunately, they're not very eager to implement them, even what would seem to be the simplest one, like switching to https. But that's a whole other story.

# Ideas for Telegram

* **Chat folders.**
	* An unlimited number of folders. You can give them your own names and choose whether to get notifications from them.
	* You can set a folder where all new chats and contacts are added automatically. This would be very useful for popular people, so they don't lose their chats among millions of messages from fans.
	* I would create these folders:
		* Frequent chats
		* Rare chats
		* Channels
		* Groups
		* Wasted chats
		* Work
	* Of course, you could say that Telegram now lets you move chats to the archive. Yes, I agree, that's cool, but it's not enough.
	* Business people could split their chats into: Work/Personal life.
	* And let's not forget about nested folders, for example:
		* Work
			* Chats about one service
			* Chats about another service
			* Chats with my team
			* Chats with other colleagues
		* Personal chats
			* Family
			* Friends
			* Exes
* **Expanded favorite stickers.**
	* Right now you can add only 5 stickers to favorites.
	* The number of stickers there should be unlimited.
	* It should be possible to sort favorite stickers into folders, and to reorder and move them around inside folders however you like.
	* When you use a sticker, another person tapping it could get access either to your favorites or to the original pack of that sticker. (Whichever you choose in the settings.)
	* For now, this problem can be partially solved with [@stckrRobot](https://t.me/@stckrRobot).
* **Bumping a message.**
	* When chatting with friends, I very often remind them of my message with a dot:
		{{ <image path="img/telegram_repeat.en.png" /> }}

	* I personally do this so often that I think it deserves a whole separate feature for bumping a message.
	* And preferably, it should be possible to do this bump as a reply to the other person's message. Because they often ask a question without noticing that it was already answered above.
* **Reacting to messages with emoji.**
	* Very often we reply like this: `++++++++++++++`. Instead of cluttering the chat with a whole new message, you could add the ability to put this plus on the message as a green emoji. Examples of where this already exists: github, instagram.
		{{ <image path="img/reaction.png" /> }}

	* Examples of emoji that could be used as a marker on a message:
		* Heart
		* Plus
		* Eyes (as in "I watched the video or read the article you sent me")
		* Like, dislike.
	* The problem is keeping track of when these emoji are added. To support that, a chat needs a separate section where you can see them in chronological order and jump to the message that got the emoji. You'd also need a separate checkbox in the settings, like whether to send notifications about them or not — another headache.
	* I also think any emoji should be allowed, but the most frequent ones should be shown at the top.
* **Searching stickers by keywords.**
	* There are stickers with Druzhko (a Russian TV host who became a meme), and a bunch of meme stickers where the words matter more than the picture. I'd like to search for them by words, the way emoji are searched by words now, even the most unusual ones 🤬.
	* Honestly, I can't imagine how this would work: maybe the authors would add these phrases themselves, and it would be up to them; maybe users would train algorithms and suggest their own names for stickers.
* **Multiple Saved Messages.**
	* Saved Messages is basically a chat with yourself. Over a long time of using Telegram, I've realized that it's the perfect place for:
		* Transferring stuff from the computer to the phone and back.
		* Storing course manuals and books for studying.
		* Storing videos and articles recommended by friends.
		* Storing ideas.
	* That's why I think there should be multiple Saved Messages, so as not to mix all this information but keep it in separate streams.
	* This problem can already be solved very nicely with private channels. Here's how I did it:
		{{ <image path="img/channels.en.png" /> }}
* **Grouping short messages**.
	* On social networks we're used to sending each message right away instead of putting a period or starting a new line, which leads to pictures like this:
		{{ <image path="img/many_messages.en.png" /> }}
	* It's really irritating when a person writes in such tiny messages and you get a notification for every word; it's also infuriating that they take up so much space.
	* My suggestion: group them into one, cutting down the amount of empty space accordingly, and send the notification about a new message only when the person hasn't been typing for 15-30 seconds, or when they've pressed an "I'm definitely done" button.
	* This also happens because the message input field is too small and inconvenient for long messages, so to see what you've already written, it's easier to send messages right away.
	* Maybe even make some kind of buffer where you can put together messages, images, stickers and forwarded messages, and then send it all in one go.
* **Spoiler**.
	* Lets you hide a message under a spoiler, marking that it contains something not meant for other eyes.
	* A message under a spoiler opens with a click, and the next time you open the chat you have to open it again. Or it can be opened forever by doing a special action.
	* It could have a marker showing whether it has been opened, as is done for voice messages.
	* Perfect for sending NSFW photos and other messages not meant for prying eyes.
* **Maximum control over notifications.**
	* There are four types of notifications:
		* Neither a visual banner nor a sound.
		* Only a visual banner.
		* Only a sound.
		* Both a visual banner and a sound.
	* Each of these notification types should be selectable:
		* As the default
		* For each chat
		* For each group conversation
		* For each group conversation, when you're mentioned with `@`
		* For folders.
* **Mention everyone with @all.**
	* You can already notify everyone with a pinned message, but I'd like to mention everyone with `@all`.
	* But since this feature could be overused, you could make it so that only moderators or administrators can mention everyone like that.
	* This could be useful not for public chats, but for small private ones.
* **Notification modes for different folders.**
	* While working at a company where Telegram was used for work communication, I ran into the problem that after leaving work I couldn't properly find my personal chats, and they got mixed up with the work ones.
		* Or at work I get notifications from personal chats, so I mute them, and then at home I forget to unmute them and don't get any notifications.
	* Splitting chats into work/non-work can be done with folders.
	* And then you can make different modes, for example:
		* "Work" mode — you get all notifications from the "Work" folder and none from the other folders.
		* "Home" mode — chats in the "Work" folder don't send notifications, while the other chats do, so you can get distracted by all sorts of nonsense.
		* Naturally, all these modes should be fully customizable.
* **Urgent mention.**
	* People go and set up millions of notification blocks, and sometimes there's something really urgent and important, so you could introduce a special kind of mention where the person gets a notification no matter what, and it always comes with sound and vibration.
	* It can only be used in private chats.
	* Everyone who uses it must understand that they're pulling the person away from whatever they're doing.
* **Recent downloads tab.**
	* Sometimes you download big files and forget that you downloaded them, or lose track of where they are.
	* That's why there should be a tab showing all files that are downloading and the recently downloaded ones.
* **A json file could be used for all kinds of complex settings.**
	* Like in Sublime, where all settings are set through a json file, this could be done for complex or rarely used Telegram settings.
	* No graphical interface is needed there, just a minimal text description.
	* Adding such settings costs very little, yet a huge crowd of geeks would find it convenient.

# Ideas for YouTube

* **Adding your own voiceover to a video.**
	* A huge share of YouTube videos are translations. Why start new channels for translations and upload the same footage, when you could just introduce an `add voiceover` feature, similar to subtitles?
	* This way all the voiceovers of a video would be in one place.
	* You could subscribe to a person who makes voiceovers or subtitles and get foreign videos they've dubbed in your feed.
* **The open source principle for subtitles.**
	* Any user can edit subtitles (fix errors, translation inaccuracies, start timings), and this works like a commit.
	* You can view character-by-character and line-by-line diffs against the previous version.
	* Users can vote for subtitles.
	* The author of the subtitles can accept commits into the official version.
* **Adding comments to favorites.**
	* Needs no explanation: sometimes comments are so good that just reading them once isn't enough. You can come back to them again and again.
* **An interface for timestamps.**
	* In the comments people often write things like: there was a cool moment at `1:33`; a breakdown of the video: `1:33` — one thing, `2:33` — another, etc.; the moment the thumbnail picture comes from, etc.
	* It would be really nice to be able to jump through the video using these timestamps, to save watching time and find your way around the video better.
	* These timestamps could be added by users, who could also vote on them. In the settings you could choose whether to show timestamps at all.
	* You could also make it so that only timestamps with a certain rating are shown on the video. Positive or negative.
	* I was inspired by the same kind of markers in MPC HC:
		{{ <image path="img/time_points.png" /> }}
* **A menu that hides instantly when watching on a PC.**
	* The idea is again taken from MPC HC; the following gif explains it perfectly:
		{{ <video_gif path="img/instantly_web.mp4" in_list={true} /> }}
	* Why do we need YouTube's hiding after a few seconds? It's really annoying, especially when you've accidentally moved the mouse. We've been using YouTube for ages, we know the menu is at the bottom and at the top, just make it hide instantly already!
* **Recommendations to your viewers.** YouTube already has a recommendation with the caption `Liked by viewers of %username%` underneath, and you could add a recommendation like `%username% recommends this video`, where `%username%` is a person you're subscribed to.
* **"Video previews".**
	* The idea comes from the fact that sometimes, while browsing coub.com, I come across interesting things, follow the link to the YouTube video they were taken from, and watch some great stuff I wouldn't have watched judging by the thumbnail or the title.
	* So YouTube itself could have something like coub, where people could cut the juiciest moments from their videos to get others interested in watching them.
	* This way clickbait thumbnails might have less influence on the decision to watch a video, and maybe YouTube would become a better place.

# Ideas for Yandex.Radio

* **Artist avatars.**
	* Somewhere next to the track you could show the avatars of all the artists who took part in making the song.
	* That way you wouldn't need to parse the name and try to remember who that is, since images are much easier and better to remember.
	* Just please, don't change the avatars as often as the song covers, otherwise you won't have time to remember one before it changes.
* **Listening statistics.**
	* I'd like to see listening statistics for each song:
		* Number of full listens
		* Number of skips
	* I'd also like to sort all songs by these parameters, for example to find your most beloved songs that you never skip, or the ones you listen to a lot.
	* Since this feature is fairly expensive in terms of resources, it could be given only to premium users.
	* Thanks to this you could even remove your least favorite songs that for some reason you liked, but kept skipping, or listened to like one and a half times.
* **Liking a song that's already liked** 
	* Sometimes the radio picks a song so well that you want to give it another like, but the like is already there.
	* For this you could put a heart, which means that the song fits perfectly right now.
	* Based on this information, you could try to train your algorithms to maximize the number of these hearts.
	* Then you need to explain to users that this heart will be used to recommend songs to them better, and then they'll be more willing to give them.
	* You can't put this heart on a song you've just given a regular like.

# Ideas for Sublime:

* **Pinned tabs.**
	* Like in a browser, I'd like to pin tabs, which:
		* Become as compact as possible
		* Have a fixed position that changes only manually with the mouse
	* Opening a new file can't move these pinned tabs, they're always 1, 2, 3 and so on.
	* I'd like to be able to manually assign these tabs a custom color, icon or emoji.
* **Color coding for tabs.**
	* I'd like tabs to show different file types in different colors, for example:
		* `cpp` in one color, `h` in another.
	* The color could be set either manually or by some rule based on the file name.

## Remote sublime

`Remote Sublime` is a plugin for Sublime that lets you open files from a remote machine. I used it at work when I had to work on a virtual machine.

* **Project organization.**
	* Like projects in regular Sublime, I'd like to have projects on the remote machine. I got tired of always opening all the files by hand.
* **A more stable connection.**
	* So that the bottom bar always shows whether this file is connected in remote sublime or not.
	* If not, so that you can press a button to try to reconnect, and reconnect all open files.
* **Showing the path in the status bar.**
	* Since files in this plugin are actually opened in the `/tmp` folder, I'd like the real path on the remote machine to be shown at the very bottom.
* **Syncing modifications with the remote machine.**
	* If something like `git` modifies a file that's currently open via this plugin, it doesn't get updated in sublime; I'd like that to be supported.

## Plain Tasks

`Plain Tasks` is a plugin for organizing todo lists.

{{ <image path="img/todo.en.png" /> }}

* **Keeping the nesting of all lists when archiving.**
	* The current behavior just mixes all the items into one mess.
* **Better archiving of parent items.**
	* So that parent items that still have unfinished sub-items don't get archived.
* **Moving tasks to the completed ones.**
	* I'd like all completed or cancelled tasks to be moved up automatically so they don't clutter the view, and you can see the unfinished tasks.
	* But it's better not to do this by default; let there be a hotkey for it, or a setting that makes it the default.
* **A special "info" item**
	* There are already three kinds of items:
		* Task
		* Done
		* Cancelled
	* I'd like one more kind of item that marks additional information attached to a task; it could get the color blue and the symbol ⓘ or 🅘.
* **Blocking tasks.**
	* Sometimes one task blocks another, and when there are a lot of such tasks, too much effort goes into parsing which tasks are available to do.
	* You could set blockers with some kind of tags.
	* Then tasks that can't be done at this stage could be shown in gray, and tasks that can be done in black.

# Customizable multi-feed.

* A `feed` is the place where information piles up from the sources you've subscribed to on YouTube, VK, etc.
* There are several kinds of feeds:
	* `Chronological` — here information is sorted by the date it appeared.
	* `Smart` (recommendation-based) — here information is sorted by all sorts of clever algorithms based on your interests.
* There are also several kinds of information sources:
	* Those that post rarely, and really good stuff.
	* Those that post often, and not as good.
* So the chronological feed and people who post rarely are best friends, just like the smart feed and people who post often.
* *My suggestion:* let the user create as many feeds as they like and choose the type of each feed: chronological or smart; and accordingly, when subscribing to someone, choose which feed their information goes to.
* *An example from my life:* I once subscribed to Ilya Varlamov (a popular Russian blogger) on YouTube, and I was also subscribed to a bunch of other people. But Varlamov posts a video every day, so his videos drowned out everyone else's in my feed, and I forgot about them and didn't get around to watching them; so, to my great regret, I had to unsubscribe from Varlamov. If I had been able to create another feed, I would have created it and put Varlamov there, sorted by relevance to me.
* The feed must also have a `hide` button for when you've watched a news item/video.
* For Twitter in particular I'd do this:
	* Split retweets and regular tweets into two feeds.
	* I'd put people's own tweets into a chronological feed, and retweets into a smart one.
	* This way I definitely won't miss personal tweets from the people I'm interested in, and from their retweets I'll see the most relevant ones.

An interesting [article](https://habr.com/ru/post/416555/) (in Russian) on Habr on this topic.

# Ideas for education

* **Open source books.**
	* The idea is that all books for universities and schools would be commissioned from the start on the condition that not only their pdf is freely available, but also their source code (preferably on github, and preferably in `.tex` format).
		* Especially interested independent people could make their own versions of these books, with blackjack and LaTeX.
	* This way people could fix tpyos and wrong answers, and open issues on parts that are explained unclearly.
	* Based on this data, the next time books are commissioned, all the criticism and wishes could be taken into account for the new books. And less work would be needed, since the ready-made material of the current books could be reused.
		* It would be possible to find the authors of the most successful forks of a book and invite them to help write the new version of the current book.
		* Or to find the best reviewers for new versions of books the same way.
		* These books could be provided to other Russian-speaking countries for a fee.
	* You could also do conditional compilation, so that different versions could be generated from each book with different flags:
		* The full version with explanations, comments, etc.
		* Only definitions (to refresh your memory).
		* Only problems.
		* Only answers to the problems.
		* etc.
		* A version of the textbook for schools with an advanced curriculum in the subject.
		* Of course, to implement this idea, every part of the book would have to be tagged with metadata about what that part is.
	* Right now all school books are made in such a way that they can only be printed, and the pdf isn't published anywhere, not even for money.
	* And that's really bad, because I'd rather not carry all these kilograms of textbooks around, but have them on an e-reader.
	* There will also be no more need to commission new books that could potentially be worse than the old ones (after all, if the government commissions new books, people will notice and immediately pelt it with electronic poop).
		* From now on books will only get better than their old versions.
	* All schools should use the same publicly available textbooks.
		* If a textbook doesn't do some of the things a teacher needs, the teacher can describe the problem in an issue, or make a pull request proposing changes that improve the textbook from their point of view.
	* All university course manuals should also be open source and the same everywhere.
		* Whether you study at Moscow State University or at some dump of a college, you'll have the same manual everywhere, and if you're a smart person on a small budget, you'll be able to learn all the hard stuff from that manual.
* **A contest for the best problem.**
	* You could hold contests for money or other prizes, where schoolchildren come up with the most interesting and creative problems for math, geometry and other subjects.
	* After all, students sometimes know better what they'd find interesting.
	* The best problems would then go into textbooks.
	* For the hardest problems, detailed articles on how to solve them could be written, and a collection of such articles could be printed.
* **All gradebooks are electronic and open by default.**
	* A gradebook here means the place where grades are recorded.
	* At least at university, open gradebooks motivated me to do my assignments better, so I'd be at the top in points.
	* Parents will be able to track grades without any buggy electronic diaries.
	* The homework for the next lesson/class could be written in the same gradebooks.
	* This system could be built once and then used by the whole country.
	* With a system like this it immediately becomes clear what you're getting points and grades for; otherwise you sometimes run into teachers with their own quirks who give points for who knows what and how.
* **Abolish school uniforms.**
	* Everyone just hates them, and they cost a pretty penny.
	* If there are any non-idiotic arguments for keeping them, I'll be glad to hear them.
	* You could study the experience of countries where school uniforms have already been abolished and compare it with our country.
	* But if this is done, the whole country should be given a couple of years' notice before the decision, so that sellers and manufacturers of school uniforms can prepare.
* **Teach touch typing.**
	* Everything is obvious here: we live in the 21st century, and this skill should be developed professionally.
	* Kids do learn to type without looking, but not with all ten fingers.
		* Moreover, what they learn is dynamic typing, which has no system that would let them make fewer mistakes or keep improving their speed steadily in the future.
	* Kids would find it really interesting to learn typing on sites like Klavogonki.
	* This has to be done precisely in childhood, because that's when the brain learns most easily.
	* They should also be told about other layouts and other keyboards, and maybe the finger zones should be changed a bit to more comfortable ones.
		* Maybe we should introduce our own keyboards with an ergonomic key arrangement and programmability. With blank keycaps from the start, so you can't peek at them.
* **Explain why things are needed.**
	* In my opinion, everyone who studies nowadays wants to know how this knowledge will be useful in life. They ask this question because nobody wants to do something useless. And doing something you consider useless just because some authority said so doesn't fly with today's young people. And I agree with them.
	* In math, after explaining the derivative, you could tell how it's used in advanced science and in which professions it's used. And the same with every topic. This would take relatively little time, but it's much better than what we have now.
	* Plus, everyone keeps talking about introducing critical thinking lessons in schools. Well, questions about why this or that subject is needed are the best manifestation of critical thinking. It should be encouraged by answering such questions.
	* And if you can't explain why something is needed, maybe it isn't needed at all? (For example: complicated trigonometric equations)

# Odds and ends

* When I set a stopwatch or a timer on my phone, it should be shown in the status bar at the top, next to the clock, if I've turned on such a setting.

# General principles behind these ideas

* Don't mix the frequent with the rare.
* Let users create categories.
* More customization for the Customization God.
* Turn routine actions into features.

# A few observations about ideas

* The best way to come up with new ideas for a product is to use it every day.
* Ideas come much more readily when you have a place to write them down where they'll be appreciated.
