---
author: Fiona
comments: true
date: 2009-03-24 10:51:24
layout: post
slug: radical-recommendations-thinking-out-loud
title: 'Radical recommendations: thinking out loud'
wordpress_id: 112
categories:
- linked data
---

Last night I was watching a few news clips on the BBC News website, and at the end of each video was links to "more like this". I made a comment on Twitter:


> "End of BBC news videos on their site suggests 'more like this'. Don't really want to watch 'more like this' if I'm watching sad news."


[Jodi Schneider](http://www.twitter.com/jschneider) responded:


> "@[blisspix](http://twitter.com/blisspix) That suggests mood-based recommendation for news outlets. Interesting! "More like this" "Opposite mood" etc."


Now that's an interesting idea, and it got me thinking about recommendation systems in general. Mostly I've been unsatisfied with everything from Amazon to iTunes Genius. Their algorithms are, to my mind, too blunt.

[Etsy's explore options](http://www.etsy.com/buy.php) (colours, pounce, time machine, geolocator, etc) are an amazing leap forward into more meaningful browsing and recommendation. Whether you are into handcrafts or not, this site is an excellent example of making the most of metadata.

But we can go much further, radical recommendations, and I think it's something librarians can and should be involved with. We have a longstanding strength in [readers' advisory](http://en.wikipedia.org/wiki/Reader%27s_advisory) and I think you'd be hard-pressed to find a librarian who has not heard of Nancy Pearl's [Book Lust](http://www.nancypearl.com/).

There are other efforts already to provide online recommendations on what to read next, like [ReadMe](http://mssv.net/wiki/index.php/ReadMe) from MetaFilter, [What do I Read Next?](http://www.schoollibraryjournal.com/article/CA6625217.html?industryid=47061) from Gale, and both human and automated recommendations in [LibraryThing](http://www.librarything.com/). Yet they are not at the depth I would like to see - the depth that people like Nancy Pearl provide. Now to be clear, I don't want to replace humans and the strength of emotion and individuality in recommendation, but I do want a more reliable way to explore what I should read, watch, or listen to next. And that's likely to be people-generated. I do want a recommendation that will take into account mood, but also things such as -



	
  * Am I buying this item for the library? Then I care about how durable the book is, how up to date it is, how relevant it is to courses.

	
  * Am I buying this item for me, to read or listen to on a train/plane trip/while sitting by a pool on vacation? I'm going to want something different for all of those.

	
  * What are the instruments being played in the music? I don't really like auto-tune or drum machines, for example.


The very human nature of recommendations though, is exactly what makes it so difficult.  I find music recommendations particularly troublesome, whether from [AllMusic](http://www.allmusic.com/), [Amazon](http://www.amazon.com), iTunes Genius or [Last.fm](http://www.last.fm/). They are usually too broadly applied to really be of use or don't reflect how I feel. For example, the ‘mood' for my favourite band, Radiohead, includes the following:



	
  * [Cold](http://www.allmusic.com/cg/amg.dll?p=amg&sql=77:13094)

	
  * [Epic](http://www.allmusic.com/cg/amg.dll?p=amg&sql=77:13093) 
	
  * [Sprawling](http://www.allmusic.com/cg/amg.dll?p=amg&sql=77:13024)

	
  * [Austere](http://www.allmusic.com/cg/amg.dll?p=amg&sql=77:12992) 
	
  * [Paranoid](http://www.allmusic.com/cg/amg.dll?p=amg&sql=77:11319)

	
  * [Tense/Anxious](http://www.allmusic.com/cg/amg.dll?p=amg&sql=77:11280)

	
  * [Cathartic](http://www.allmusic.com/cg/amg.dll?p=amg&sql=77:11249) 
	
  * [Distraught](http://www.allmusic.com/cg/amg.dll?p=amg&sql=77:13166)

	
  * [Insular](http://www.allmusic.com/cg/amg.dll?p=amg&sql=77:13099) 

And I don't feel that way at all when I listen to their music, so these options really don't help me.

How can we use the strength of individual listeners and readers? And how can this be done while protecting privacy? In libraries, we have been stepping into recommendations at the catalogue level only tentatively, both because we don't actually have any of that data most of the time and to protect the privacy of individuals. Is there a way to collect deep, meaningful recommendations about people who like particular books + videos + websites + information without creating a dangerous profile? That will be a key challenge of the Semantic Web.

So how can recommendations be improved, made more granular, more relevant? Small, distributed pockets may be a way. Information collected at the listening level (eg last.fm, iTunes Genius) could be queried against opinions of dozens of reviewers, and hundreds of fans, and against statistical data like "bands that have supported this band on tour", "bands that covered this track" ([available in MusicBrainz](http://musicbrainz.org/show/release/relationships.html?releaseid=650071) ) and information about what guitars they play with. There shouldn't be just one entry on AllMusic for a band, but rather many different pieces of information scattered across the web, connected using Linked Data giving strength and flexibility to be able to say "I am looking for happy music made in a cold climate in the mid 90s with slightly political lyrics that has a similar instrument profile to Ride" and in the next minute want to listen to dance music, and be able to find just what you're looking for.

Much of this is part of the vision for the Social Semantic Web, Alexandre Passant from DERI has a great slidedeck on this topic:


[The Social Semantic Web and Linked Data](http://www.slideshare.net/terraces/the-social-semantic-web-and-linked-data-presentation?type=powerpoint)

View more [presentations](http://www.slideshare.net/) from [Alexandre Passant](http://www.slideshare.net/terraces).



On a related note, the author of [Collective Intelligence in Action](http://www.manning.com/alag/) was [recently interviewed by ReadWriteWeb about recommendations](http://www.readwriteweb.com/archives/recommendation_systems_interview_satnam_alag.php), particularly in the US service, Netflix.

Do you have ideas or examples of great recommendation systems? Leave a comment!
