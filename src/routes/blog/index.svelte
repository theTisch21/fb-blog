<script context="module">
	import { browser, dev } from '$app/env';

	// we don't need any JS on this page, though we'll load
	// it in dev so that we get hot module replacement...
	export const hydrate = dev;

	// ...but if the client-side router is already loaded
	// (i.e. we came here from elsewhere in the app), use it
	export const router = browser;

	// since there's no dynamic data here, we can prerender
	// it so that it gets served as a static asset in prod
	export const prerender = true;
</script>

<svelte:head>
	<title>Blog</title>
	<meta name="description" content="It's a blog" />
</svelte:head>


<script lang="ts">
	import reddit1 from "./Picture8.png"
	import reddit2 from "./Picture9.png"
	import reddit3 from "./Picture10.png"
	import birb from "./birb.jpg"
</script>
<head>
	<script async src="https://platform.twitter.com/widgets.js" charset="utf-8"/>
</head>

<div class="content">
	
	<h1>BLOG</h1>
	<h2>PLEASE NOTE: If twitter is <strike>censored</strike> blocked on your network, Tweets will be converted to plain text for your convenience. All the twitter quotes and reddit screenshots are hyperlinked, simply click them to go to the original thread.</h2>

	<p>
		I came across this interesting controversy the other day. It was this advertisement from Gillette, a razor company, published in 2019. <iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/koPmuEyP3a0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe><br> The ad attempts to take a stand against toxic masculinity and violence among men and encourages men to be the best they can be to others. The interesting thing about it was that the ad really ticked off a lot of men. They took to twitter in storms, with loads of angry tweets. After looking into the matter, it’s clear that People who feel attacked by this ad feel this way because their sense of masculinity is being attacked, and therefore they feel like a victim to the feminist movement.

The overwhelming negative response to the ad was quite extreme. Here are a couple examples:
<blockquote class="twitter-tweet"><p lang="en" dir="ltr"><a href="https://twitter.com/Gillette?ref_src=twsrc%5Etfw">@Gillette</a> has made it clear they do not want the business of masculine men. <br><br>I will grant their wish.<br><br>I have used <a href="https://twitter.com/hashtag/Gillette?src=hash&amp;ref_src=twsrc%5Etfw">#Gillette</a> razors since they sent me a free sample on my 18th birthday, and will no longer buy any of their products.</p>&mdash; Rule The Wasteland (@MongoAggression) <a href="https://twitter.com/MongoAggression/status/1084948065906118656?ref_src=twsrc%5Etfw">January 14, 2019</a></blockquote>
<blockquote class="twitter-tweet"><p lang="en" dir="ltr">I’ve been shaving since I was 12, since the beginning I used Gillette because that’s what my father used, now I will never use it again, and neither will my father, collectively been your customers for 50+ years never again <a href="https://twitter.com/hashtag/BoycottGillette?src=hash&amp;ref_src=twsrc%5Etfw">#BoycottGillette</a> <a href="https://twitter.com/hashtag/Gillette?src=hash&amp;ref_src=twsrc%5Etfw">#Gillette</a></p>&mdash; Ary (@ary31574363) <a href="https://twitter.com/ary31574363/status/1085011524354097152?ref_src=twsrc%5Etfw">January 15, 2019</a></blockquote><blockquote class="twitter-tweet"><p lang="en" dir="ltr">We r boycotting them coz they r promoting the <a href="https://twitter.com/hashtag/FeministMafia?src=hash&amp;ref_src=twsrc%5Etfw">#FeministMafia</a> narrative while they make their money from us..the victims of the feminists...</p>&mdash; Sandeep Mukherjee (@Libertarian196) <a href="https://twitter.com/Libertarian196/status/1085589002378452992?ref_src=twsrc%5Etfw">January 16, 2019</a></blockquote> 

<p>The men involved are upset, but after looking at all the tweets, it’s clear that they feel their sense of masculinity is being attacked. However, the ad only attacks misogyny and sexual harassment and assault, not anything stereotypically manly like being strong and angry. In fact, the ad even features a man encouraging a girl to say, “I am strong”. Since the ad never targets general manliness, One tweeter said this: <blockquote class="twitter-tweet"><p lang="en" dir="ltr">You mean this ridiculous vomit bag of feminist dogma commercial...yep me to.</p>&mdash; Troy Miller (@troymation) <a href="https://twitter.com/troymation/status/1086337746224979969?ref_src=twsrc%5Etfw">January 18, 2019</a></blockquote> <p>In contrast, a healthy masculine response would instead attempt to shoot down the negative behavior of men. Take this response for example: </p><blockquote class="twitter-tweet"><p lang="en" dir="ltr">You appear to be saying &quot;masculine men&quot; are those that engage in the negative examples shown in the add. If that is what you believe a masculine man should be, I pity those on the receiving end of your &quot;masculinity&quot;.</p>&mdash; Mark Bowyer 👂👍👌 (@clipperride) <a href="https://twitter.com/clipperride/status/1085210977568804865?ref_src=twsrc%5Etfw">January 15, 2019</a></blockquote><br><p>

In this response, Mark makes the claim that the negative examples shown in the ad are not proper masculinity. Rather than reinforce the negative stereotypes set before men, Mark is attempting to break free of the idea that masculinity involves assault and bullying. Even though many of the angry men perceive themselves as masculine, they see themselves that way because they believe masculinity involves bullying and assault. Here are some more examples of healthy masculine responses:
<blockquote class="twitter-tweet"><p lang="en" dir="ltr">Yes, not abusing women just be a difficult concept for you.</p>&mdash; Jam G (@TwitTheTweetz) <a href="https://twitter.com/TwitTheTweetz/status/1085287813610913792?ref_src=twsrc%5Etfw">January 15, 2019</a></blockquote> <p>
To get a clearer picture, I visited the reddit community r/MensRights, a community for discussing issues surrounding men’s issues. <a href="https://www.reddit.com/r/MensRights/comments/tuxzk8/joan_collins_warns_antimaleness_ruining/"><img src={reddit1} alt="u/Heavy_Grand2526 - Joan Collins Warns Anti-Maleness Ruining Generation of Young Men Suffering from Being Labeled Toxically Masculine"></a> <a href="https://www.reddit.com/r/MensRights/comments/ag1qkr/new_the_best_men_can_be_gillette_campaign_gushes/"><img src={reddit2} alt="u/AndrewLevin - Gillette campaign gushes with hatred and contempt for men and boys."></a>
It’s interesting how like the twitter feed, people are assuming that the attack on sexual harassment and bullying is an attack on masculinity. u/DaLordOfDarkness stated that “It’s funny that society want makes to be weak, and then wonder why no girls want them”. This comment clearly shows how closely aggression and bullying and manliness are perceived to members of the reddit and twitter feeds here. They’re also pushing the idea that the commercial is pandering. <a href="https://www.reddit.com/r/MensRights/comments/ag1qkr/comment/ee3ofmt/?utm_source=share&utm_medium=web2x&context=3"><img src={reddit3} alt="u/XteveMcQueen - Some good “get woke, go broke” in the comment section. One post had product list to avoid. Was about to get a new toothbrush - throwing my Oral-B system in the trash in the morning and about to get on amazon for non-Gillette razors. Pandering bullshit ads like that piss the fuck out of me."></a>
From these responses, we can conclude that people are upset because they feel their sense of masculinity is being attacked, even though the ad targeted unhealthy masculinity. My goal with this post is to highlight this issue so that we can work to bring a stop to it. If we don’t, who knows how many more men and women will suffer from these awful stereotypes.

	
</p>
	<br>
	<br>
	<div class="author">
		<h1>About the author</h1><img src={birb} alt="The author's bird, named Pickle" width="100px" style="border-radius: 50%"><br>
		<h2>Hi! I'm Sam Tischaefer. I'm a student taking UW Comp at Eastlake high school. I've written about encryption, language, culture, and margins and centers. During my free time, I play video games, practice cello, and hang out with my bird named Pickle! (Pictured above)</h2>
	</div>
	
</div>

<style>
	.content {
		width: 100%;
		max-width: var(--column-width);
		margin: var(--column-margin-top) auto 0 auto;
	}
	.author {
		width: 70%;
		margin:auto;
	}
	.author h1 {
		font-size: 3em;
	}
	.author h2 {
		font-size: x-large;
	}
</style>