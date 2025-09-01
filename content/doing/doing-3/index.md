---
title: "Tech Editing"
author: "K.J. McGuire"
authorAvatarPath: ""
date: "2025-08-31"
summary: " "
description: ""
toc: false
readTime: false
autonumber: true
math: false
tags: ["", ""]
showTags: false
hideBackToTop: false
fediverse: "@username@instance.url"
---
I've spent most of my professional life editing other people's writing. I have yet to find work I enjoy more. It's why I abandoned a physics career to return to a career in technical writing. I still get some grief about this from others who seem to think working as a tech writer and editor isn't enough for someone with a physics education. But I edit because it's what I enjoy doing. And after years struggling as mediocre physicist, it's nice to do something I'm actually good at.

Now, if there's something I enjoy more than editing, it's having opinions about how it should be done. Here I share a few of those opinions. Although I sometimes express these opinions with an air of authority, I acknowledge that they are merely that. Opinions. I loathe excess timidity and the irksome, predominantly *female* tendency to qualify each opinion with *I think . . .* or *In my opinion . . .* . If this sounds a lot like griping, that's probably because it is.


**Editing priorities.** I've known editors to fixate on the finer points of a style guide while neglecting a document's bigger issues. I'm talking about debating whether "life cycle" should be one word or two or the minimum number of times an acronym should appear in a document to justify introducing it. Meanwhile the document itself is incoherent and amateurish. Professional editing is much more than just fixing grammar mistakes and applying *The Chicago Manual of Style*. I've had disagreements with fellow editors over what we should be prioritizing in a document. My view is that it's our job to make a document sound professional. For many documents, that means a lot of rewriting. Simply fixing the grammar in a poorly written document without addressing the writing itself is like slapping a coat of paint onto a dilapidated house. You first need to replace the rotting beams and fix the cracked foundation. Otherwise you end up with a structure that might look good from a distance but if you look closer, you see the whole thing is a mess.

Ambiguous, nonsensical sentences. Wordy, repetitious paragraphs. A complete lack of logical flow. These are just a few of the issues that a skilled editor ought to fix. I understand how easy it is to lapse into editor autopilot, to read without thinking, to scan for grammatical accuracy only and conformance to the style guide. But this is lazy editing. To put it another way, if a team of subject matter experts cobbles together an incoherent and disjointed engineering plan, who really cares that they introduce an acronym they never use again or place a colon after "including" before a bullet list? The document will still be unreadable after you fix those things. It isn't that usage standards aren't important; but they're the paint you put on the house after you've fixed the crumbling structure.


**Mindless adherence to so-called writing rules.** There are many of these in American English: *you must never end a sentence with a preposition*, *you should eliminate the word "that" as much as possible* . . . The one that irks me the most is the misguided prejudice against passive voice. Professional writers need to graduate from the idea that active voice is *always* better. Just because your Word application flags a passive clause doesn't mean there's anything wrong with it. This is another case of working on autopilot. The first rule of editing should be **don't leave the document worse than you found it**. I've seen active voice edits that were entirely unnecessary and actually mangled the original sentence. Consider, for example,

> Documents such as the *Program Emergency Plan* and *Hazard Mitigation Report* are subject to internal review, but they are managed by the safety team.

changed to

>Management by the safety team of certain documents, including the *Program Emergency Plan* and *Hazard Mitigation Report*, are subject to internal review.

In this real-life example (I've replaced the nouns to protect the source) the editor recognized the passive clause but couldn't think of a good fix. The rewritten sentence is ungrammatical and nonsensical. But there really wasn't anything wrong with the original sentence. You **could** change the passive clause into "but the safety team manages them," but I think the original sounds more natural. Really, there's nothing wrong with it, and flipping the subject changes the meaning slightly.

Passive voice is one of those topics I feel I must throw some authoritative weight behind, because if you just Google "passive voice" you'll likely stumble upon the same simplistic arguments and contrived examples you first encountered in high school. I present [this article](http://www.lel.ed.ac.uk/~gpullum/passive_loathing.pdf) by British--American linguist Geoffrey Pullum. He gives many examples of how well-educated writers and even respected language authorities have misdiagnosed the issue. No wonder the passive voice urban legend is so pervasive.  

But forget about authoritative arguments for a moment and just stop and think about it. Passive voice is sometimes the best choice. Consider this sentence:

> JFK was assassinated on November 22, 1963.

How would you rewrite it into active voice?

> A gunman assassinated JFK on November 22, 1963.

Is the second sentence better? The answer is---it depends. When you make the subject of the sentence the assassin, you shift the focus from the victim to the perpetrator. You effectively change the meaning of the sentence. If this was your intention, then it's a good edit. But unless the passage is meant to highlight the assassin, the first sentence is better.

> The assassination of JFK occurred on November 22, 1963.

This is also active voice. Is it better than the first sentence? Again, it depends. It's a bit less concise and a bit more formal than the first sentence. I suppose it would depend on the context. Does the sentence match the tone of the rest of the document? Does it fit in stylistically with the surrounding text? I suspect most people would never register anything wrong with the original, passive voice sentence. That's because passive voice has a rightful place in English. You shouldn't need a language authority to convince you of that. Just pick up any well-regarded piece of writing and read carefully. You will find instances of passive voice.  

**When it comes to document creation, the tech writers are subject matter experts:** I have had to push back on the practice of mangling perfectly good sentences to force them into the active voice, the contention being that the customer wants active voice. OK, but does the customer really understand what active voice is? I assume the customer also wants their document to make sense, be factually accurate, and sound professional. As a hired expert, it's my job to look beyond what the customer is literally asking for to see what they really want. Usually what they really want is a well-written, convincing document that expertly addresses the topic at hand using concise language written for the intended audience. They just don't always know how to ask for that, so they fall back on what they learned in school, such as *Write in active voice*.

As professional editors, it can fall on us to (gently and tactfully) remind others that, when it comes to document creation, we're the experts. I think editors have a harder time with this than other professionals. People take their writing very personally and can feel insulted when an editor comes in and changes their work. There seems to be this attitude among educated people that they must know how to write professionally because they went to school and are intelligent. Fixing their writing is tantamount to telling them they're stupid, it would seem. I've had to reassure engineers who took offense because I did more than just fix their misspellings and commas. I've had to sooth them with words like "It's OK... I've seen much worse... You're the expert on the content, I'm just here to make sure your expertise is clearly communicated . . ." I'm not just blowing my own horn when I say writing and editing are difficult skills to master. Just anyone can't do it well. After many years doing it professionally, I'm still learning how to do it better.

**Artificial intelligence cannot replace a highly skilled technical writer . . . (yet?).** I have a lot to say about generative AI and its role in document creation. I will leave most of those thoughts for a future post. For now, here's my hot take.

Technical writers should learn to use AI and will need to if they wish to remain competitive. LLMs like ChatGPT are great tools for automating routine tech writer tasks, suggesting edits, and catching typos. Like many other professional roles, I think the role of tech writer is largely going to morph into AI interfacer. But it will be many years before AI can fully replace a highly skilled tech writer. Yes, AI can write an entire article for you seemingly on point and free of typos. But if you look closely, you'll begin to notice the clichés and redundancies, the vague and vacuous statements, the half-truths and outright hallucinations. The output still requires substantial rework by a skilled editor if it is to sound authentic and professional. Best to use AI at the beginning and the end of a writing task, to create the original outline and perform the final proofread, and leave the actual writing to the humans. My biggest concern is that factual inaccuracies will creep in unnoticed by the editor if SMEs use the tool to write the draft. This happened to me recently. I worked on a document I knew had been rewritten by AI starting from a human-generated draft. Knowing this, I managed to spot a factual mistake that wasn't in the original because I have enough domain knowledge, but I doubt I caught every mistake because I lack subject expertise. My hope is that AI forces us all to become better writers, but I worry standards will just drop. Perhaps there will then emerge a cottage industry for human-generated writing and editing. Or perhaps I'll just be out of a job.
