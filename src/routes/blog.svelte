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

<div class="content">
	<h1>BLOG</h1>

	<p>
		Before getting to the article, I want to acknowledge that times are hard and we’re all in a different place mentally. This blog post covers topics like misogyny, sexism, violence, and it includes discussion surrounding the (yet unconfirmed) supreme court decision surrounding Roe vs. Wade. I’ve added a switch to enable content warnings for these topics. Enable content warnings: [ ]
I came across this interesting controversy the other day. It was this advertisement from Gillette, a razor company, published in 2019. YouTube https://youtu.be/koPmuEyP3a0 The ad attempts to take a stand against toxic masculinity and violence among men and encourages men to be the best they can be to others. The interesting thing about it was that the ad really ticked off a lot of men. They took to twitter in storms, with loads of angry tweets. Forbes even published an article attacking the ad, but later published a critical review of the ad. After looking into the matter, it’s clear that the people angry at this ad are angry because they are attacked for conforming to the stereotypes set for them.
The overwhelming negative response to the ad was quite extreme.       
   
The men involved are upset, but after looking at all the tweets, it’s clear that they feel their sense of masculinity is being attacked. However, the ad only attacks misogyny and sexual harassment and assault, not anything stereotypically manly like being strong and angry. In fact, the ad even features a man encouraging a girl to say, “I am strong”. Since the ad never targets general manliness, it can only mean that the people attacked by this ad feel that manliness is tied to being anti-feminist and misogyny. In contrast, a healthy masculine response would instead attempt to shoot down the negative behavior of men. Take this response for example:  
In this response, Mark makes the claim that the negative examples shown in the ad are not proper masculinity. Rather than reinforce the negative stereotypes set before men, Mark is attempting to break free of the idea that masculinity involves assault and bullying. Even though many of the angry men perceive themselves as masculine, they see themselves that way because they believe masculinity involves bullying and assault.
Another reason I think they were angry was because they thought that all men were being attacked in the ad. This is similar to the classic outcry of “Not all men” raised when discussing sexual assault. [Screenshot of tweet that says that]. [Add] I ended up looking at the reddit forum of /r/MensRights.    
It's pretty awful stuff, but the same sort of idea as the twitter feeds. 

	</p>

</div>

<style>
	.content {
		width: 100%;
		max-width: var(--column-width);
		margin: var(--column-margin-top) auto 0 auto;
	}
</style>