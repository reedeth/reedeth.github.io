---
layout: post
title: "The Ghost in the Graph: A Recap on Time, Things, and Entanglement"
author: "Ethan Reed"
date: 2015-12-03
comments: true
category: blog
img: 12.3vis2sunday.png
---

<em>[Cross-posted from <a href="http://scholarslab.org/digital-humanities/the-ghost-in-the-graph-a-recap-on-time-things-and-entanglement/">the Scholars' Lab </a> - this is the protein-rich version of a series of related posts from <a href="http://praxis.scholarslab.org/">our Praxis site</a>, with fresh reflections on the process and product now that I’m done. If you want to see originals, check out <a href="http://praxis.scholarslab.org/memo/2015/11/02/11-2-week-project-time-through-things/">the project idea</a>, <a href="http://praxis.scholarslab.org/blog/2015/11/12/everything-i-used-in-a-seven-day-period/">the data itself as I recorded it</a>, a <a href="http://praxis.scholarslab.org/blog/2015/11/18/visualizing-everything-i-used/">first attempt at a visualization</a>, and a <a href="http://praxis.scholarslab.org/blog/2015/11/20/visualization--2-of-everything-i-used-in-a-seven-day-period/">second attempt at a series of visualizatio</a><a href="http://praxis.scholarslab.org/blog/2015/11/20/visualization--2-of-everything-i-used-in-a-seven-day-period/">ns</a>.]</em>

Time through things. This was the motivating idea behind <a href="http://praxis.scholarslab.org/memo/2015/11/02/11-2-week-project-time-through-things/">a week-long project </a>I started at the beginning of November for Praxis. Everyone on the team decided to track, monitor, or experiment with lived time in one way or another for a full week. James looked at <a href="http://praxis.scholarslab.org/memo/2015/11/11/cloud-data/">clouds</a>; Lydia at <a href="http://praxis.scholarslab.org/memo/2015/10/31/music-tracking-update/">music</a>; Gillet at <a href="http://praxis.scholarslab.org/memo/2015/11/18/outside-time/">time indoors and outdoors</a>; Bremen at policing and affect; Rachel at <a href="http://praxis.scholarslab.org/blog/2015/11/18/f-bomb/">language use</a>. I chose to think about time through things. So I wrote down in a notebook <a href="http://praxis.scholarslab.org/blog/2015/11/12/everything-i-used-in-a-seven-day-period/">everything I used in a seven day period</a>, from when I woke up to when I went to bed. Obviously what counts as “use” and what counts as a “thing” gets conceptually gritty very quickly. To stay sane, I took them in their most intuitive, ordinary senses, which means Yes, my methodology was in some ways arbitrary, but also Yes, I managed not to go nuts while seeing it through. So the data is not perfect, but it’s there!

Why did I want to do this?

If you have a chance to look at my other posts this year related to Praxis's current explorations of time and ways of representing it (<a href="http://scholarslab.org/digital-humanities/inktober-1021-when-things-break/">When Things Break</a>, <a href="http://scholarslab.org/digital-humanities/inktober-1013-time-pieces-and-graphs/">Time Pieces</a>, and <a href="http://scholarslab.org/digital-humanities/inktober-105-three-sketches/">Three Sketches</a> in particular) it becomes clear I’m interested in nonhuman and what some might call posthuman ways of thinking about time. For me, this means I’m thinking about the way time works for stuff, things, and entities that aren’t people. Which can be difficult because as humans we tend to anthropomorphize everything - humans think through human lenses. <a href="http://www.iep.utm.edu/met-phen/#H4">Jacques Derrida famously argued</a> that Western philosophy itself is anthropomorphic (and ethnocentric) - others have <a href="http://press.uchicago.edu/ucp/books/book/chicago/M/bo3637992.html">argued related things in different venues</a>. And these ideas make a lot of sense. If the human species were physically different (blind but great sense of smell; two brains per body; a strain of bacteria; <a href="https://en.wikipedia.org/wiki/Tralfamadore#Slaughterhouse-Five">four-dimensional</a>) our understandings of lots of things – basically everything – would be affected.

But even if it’s a difficult project, thinking of nonhuman and posthuman time also feels like an important project. For example, this kind of thinking might help us wrap our heads around our role in systems or entities bafflingly larger than us, like the geologic time of our planet and our power as a species to shape its geologic future. For a few of my favorite examples of this kind of thinking, see <a href="https://www.upress.umn.edu/book-division/books/hyperobjects">Timothy Morton</a>, <a href="http://www.jstor.org/stable/10.1086/596640">Dipesh Chakrabarty</a>, <a href="http://nowviskie.org/2014/anthropocene/">Bethany Nowviskie</a> and <a href="http://salvage.zone/in-print/the-limits-of-utopia/">China Miéville</a>.

A less “planetary” example would be re-thinking how we as decision-making entities are influenced or “made to do” things by the non-human entities that surround us. As <a href="http://www.jstor.org/stable/20167474?seq=1#page_scan_tab_contents">Bruno Latour wonders</a>: are you smoking the cigarette or does the cigarette smoke you? Well, as he says: both.

So how am I trying to think about posthuman or nonhuman time?

To answer this, let’s look at the data and what I did with it. My data, as <a href="http://praxis.scholarslab.org/blog/2015/11/12/everything-i-used-in-a-seven-day-period/">presented on the site</a> in big blocks of words, almost looks like a kind of poetry (maybe <a href="http://chronicle.com/article/Uncreative-Writing/128908/">uncreative poetry</a> in the vein of Kenneth Goldsmith). I took this strange data and did my best to represent it visually, both for practice with <a href="http://d3js.org/">d3 tools</a> and also to eke more meaning out of what I’d done. For this visualization and the ones below, I'm posting images rather than the graphs themselves - if you want to play around with the sometimes sluggish originals, check out the links at the top of this post.

For my first attempted visualization, I borrowed from Jason Davies’ <a href="https://www.jasondavies.com/parallel-sets/">“Parallel Sets”</a> visualization (with significant help from <a href="https://twitter.com/wayne_graham">Wayne</a>). You can find here <a href="https://github.com/jasondavies/d3-parsets">the github page I took Davies' code from originally</a>, and his <a href="https://github.com/jasondavies/d3-parsets/blob/master/LICENSE">license here</a>.

Alas, I began with his beautiful graph and turned it quickly into an incomprehensible scribble. Behold:

<img src="{{ root_url  }}/images/12.3vis1.png" alt="Visualization 1" width="934" height="704">

As a visualization of data, what I made is pretty close to nonsensical. And also unwieldy - the original doesn't load right and can slow the page down significantly. This monstrosity didn’t come as a surprise to me, as I didn’t clean my data or prep it for what the code expected. I more or less just tried to crowbar my data into Davies’ code/setup until something came out the other end that looked anything remotely like a graph. So while I don’t know exactly what’s happening here, things <em>are </em>happening. Some sort of nightmare causality is at work, even if only my laptop really knows what’s going on (or <em>not </em>going on) as it tries to make sense of what I'm feeding it.

But when I take a step back, what it comes up with also feels kind of poetic, almost like the data itself. When you mouse over one of the catastrophic clusters and happen upon a single thread, the graph tries to produce a new narrative of objects for you. The pseudo-stories are wandering and garbled, but also charming and original. For example: “spoons -&gt; mouse pad -&gt; backpack -&gt; chair -&gt; yogurt -&gt; metro card.” Or my personal favorite: “pillow -&gt; sheets -&gt; sheets -&gt; sheets -&gt; sheets -&gt; sheets.”

More useful, I think, are my <a href="http://praxis.scholarslab.org/blog/2015/11/20/visualization--2-of-everything-i-used-in-a-seven-day-period/">second round of visualizations</a> . These are <a href="http://bl.ocks.org/mbostock/4062045">force-directed graphs</a>, also from <a href="http://d3js.org/">d3js.org</a>, one of <a href="http://bost.ocks.org/mike/">Mike Bostock’s many visualizations</a>. As with Davies’ parallel sets graph, I used what Bostock had up on d3, replaced his data set with mine, and with a lot of help from <a href="http://scholarslab.org/people/eric-rochester/">Eric</a> figured out how to get it to read my .csv file.

With this method, I produced one force-directed graph for each day and a sprawling, magnificent mess at the end combining all seven days. In the graphs, each node (or point) represents a “thing” that I used. If you mouse over the node you can see which thing it represents. Every edge (or connecting line) represents a connection between those things – in this case, a connection between A and B means that A was used right after or right before B in my linear data. This means that the linearity, as well as the order of use, is collapsed in these representations. What we’re left with, however, is something new and potentially worth looking at on its own.

Different days have different shapes. Thursday’s things live in big billowing petals that loop out on long, solitary walks of minimal connection:

<img src="{{ root_url  }}/images/12.3vis2thursday.png" alt="Visualization 2 Thursday" width="934" height="704">

Sunday’s things live in much tighter, centralized clusters – most activity is shared activity, a miniature city of things:

<img src="{{ root_url  }}/images/12.3vis2sunday.png" alt="Visualization 2 Sunday" width="934" height="704">

But what do these static, force-direct graphs of relationships between things have to do with time?

According to <a href="https://www.youtube.com/watch?v=YycAzdtUIko">what I gather on the subject</a>, modern physics has some counter-intuitive insights to offer regarding our ordinary bodily understanding of time, such that our intuited experience of it doesn’t necessarily correspond to how events happen in the nether realms of relativity. For example, according to <a href="https://en.wikipedia.org/wiki/Relativity_of_simultaneity">the relativity of simultaneity</a>, one observer might see A -&gt; B -&gt; C (with accurate measurements), while another with equal accuracy observes B -&gt; C -&gt; A.

But while orders of events may be muddled, the fact of <a href="https://en.wikipedia.org/wiki/Causality_(physics)#Cause_and_effect_in_physics">causality</a> remains. So in one way of thinking, time for a person is less something that passes by moment to moment in a linear progression than it is a static line segment of every casually linked event, all existing simultaneously. In which case, static, simultaneous representations of multiple events might actually have an unusual kind of purchase when it comes to representing causal/temporal relationships.

So what happens when we try to think about this with regards to <em>stuff</em>? I'm thinking about causal relations between things that might not involve humans. For example, if humans were to disappear tomorrow (as in Weisman’s<em> <a href="http://www.worldwithoutus.com/index2.html">The World Without Us</a></em>), <em>things </em>would very well continue to interact with one another. To expand on examples from my data: a pillow getting heavier, mustier, and moldier as moisture creeps into a dilapidating room, staining the sheets on which it rests, while both weigh down on a mattress whose metal springs start to rust and give (pillow -&gt; sheets -&gt; mattress); freeze-thaw cycles crack and crumble sections of road until a telephone pole tips and snaps onto the hood of a parked convertible, sending glass onto the street (road -&gt; pole -&gt; car); and so on. Other writers have thought about this before: in <a href="http://scholarslab.org/digital-humanities/inktober-1021-when-things-break/">a previous post</a> I linked to Virginia Woolf’s depiction in <em><a href="https://en.wikipedia.org/wiki/To_the_Lighthouse">To the Lighthouse</a> </em>of a home left uninhabited for years. In Ray Bradbury’s <a href="https://en.wikipedia.org/wiki/There_Will_Come_Soft_Rains_(short_story)">“There Will Come Soft Rains”</a> from <em><a href="https://en.wikipedia.org/wiki/The_Martian_Chronicles">The Martian Chronicles</a> </em>(not available as text online, but awesomely available as <a href="https://www.youtube.com/watch?v=LzhlU8rXgHc">a recording read by Leonard Nimoy</a>), we watch from a disembodied point of view as a futuristic home in California, long abandoned, slowly breaks down, from its automated kitchenware and mouse-Roombas to the automated poetry-reading voice in the bedroom.

Point being, things can very well interact with one another without humans. There may be no humans to perceive them and thus classify these encounters as between discrete, meaningful things, but from our current vantage we can at least imagine them. In this sense, these thing-graphs are speculative.

That said, there is a ghost in the graph – a body, my body, invisible save for traces left in having connected thing-nodes through use-edges. But in these graphs, the time that body spent making those connections evaporates, like steam from a cup of coffee. And what’s left is the cup of coffee itself - and all its associates. Though these associates were used in a specific linear order, I wanted instead to think of them as bound together causally, all entangled simultaneously within a given frame of reference (24 hours). Is this a chronology? Is it a timeline? A time network?

Regardless of observers arguing over linear orders-of-events, these things on this day have been strung together. A glass of water and a faucet, a toothbrush and toothpaste: somehow, someway, they were (are!) all tangled up with one another.

Can I ever really think of “thing time” without using my very human body to think it through and write it all down? Of course not. The ghost is in the graph – the ghost (with a lot of help) put the graph online, is talking to you about the graph right now. But I can certainly try to imagine how we might think of these entanglements in less anthropomorphic ways, to de-center (in <a href="https://en.wikipedia.org/wiki/Actor%E2%80%93network_theory">the vein of Latour</a>) the role of the human as sole prime agent, mover of all things. Rather, I have tried to show how these objects have lives of their own - and how, as active shaping forces, these lives are causally, temporally, entangled with ours.