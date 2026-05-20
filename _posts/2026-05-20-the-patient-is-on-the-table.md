---
layout: post
title: "The Patient is on the Table"
date: 2026-05-20
author: Buddy Patton
description: "On AI-assisted development, a 19th century physician, and the hardest part of moving fast"
---

### On AI-assisted development, a 19th century physician, and the hardest part of moving fast

So, picture this. It's Tuesday morning. A branch gets pushed with a PR description that lists fifteen acceptance criteria. All green. Tests passing. Feature complete.

The junior dev opens it, scrolls for thirty seconds, and quietly closes the tab. *That's too much to review. That's not how we do things.*

The senior dev glances at the author, sees it was largely AI-assisted, and mentally files it under "not my problem." They've seen AI slop before. They'll wait for it to fall apart on its own.

The digital product manager stares at their sprint board. They wrote those fifteen stories yesterday. It's ten in the morning. They don't know whether to be relieved or terrified - because if this is real, what does next sprint look like? What does their *job* look like?

They close the tab too.

And just like that, everyone goes back to their tickets. Linear. Methodical. One story at a time. The branch sits there, untouched, running perfectly on a dev server nobody is logging into.

### The Last Time This Happened

In 1847, a Hungarian physician named Ignaz Semmelweis noticed something that should have been front page news. Women giving birth in the maternity ward staffed by medical students were dying at nearly five times the rate of women in the midwife ward. He tracked the difference to one thing: the medical students were coming straight from performing autopsies without washing their hands.

He introduced mandatory handwashing with chlorinated lime solution. Mortality dropped from ten percent to around one. He had the data. He published it. He stood in front of his colleagues and showed them exactly what was happening and exactly how to stop it.

They ignored him. Not because the data was wrong. Because accepting it meant admitting that their hands - the hands of trained, credentialed, experienced physicians - had been killing people. That was too much to hold. So they just... kept not washing their hands.

Semmelweis died in an asylum in 1865. Germ theory was confirmed shortly after. His colleagues eventually got credit for the insight they spent twenty years refusing to act on.

### This Is Not a New Problem

The branch sitting in your repository right now is not a PR review problem. It is not a code quality problem. It is not even really an AI problem.

It is a Semmelweis problem.

The junior dev isn't afraid of the code. They're afraid of what it means *if the code is good* - that the thing they've been learning to do slowly and carefully might be learnable differently. The senior dev isn't skeptical of the output. They're skeptical of the implication - that years of hard-won velocity might now be table stakes. The PM isn't confused about the features. They're quietly panicking about a world where fifteen stories disappear before lunch and the entire team's capacity model goes sideways.

And so everyone scrubs back in the old way. Not because it's better. Because it's *known.*

### Clean Hands Don't Save Everyone

Here's the part nobody wants to say out loud: Semmelweis was right **and** patients still died.

Handwashing dropped mortality dramatically. It did not eliminate it. Surgery is still dangerous. Infections still happen. Clean hands are not a guarantee - they're a practice. A discipline. A baseline that makes everything else possible.

AI-assisted development is the same. The branch will sometimes have bugs. The inferred UI will sometimes be wrong. The spec will have gaps the model filled with reasonable guesses that turn out to be unreasonable in production. None of that is an argument against the practice. It's an argument for *reviewing it* - which is exactly what the PR is sitting there waiting for someone to do.

AI-assisted code _with_ reviews and testing IS the hygiene practice. You are washing the code. The fact that a reviewed, tested, AI-assisted branch occasionally ships a bug is not an excuse to avoid it - it's a reason to build the review culture around it. We didn't stop washing hands because some patients still died. We got better at surgery.

### The Velocity Trap

There's one more thing worth naming because it's the one that keeps product managers up at night.

If a team ships fifteen stories in a day once, that becomes the reference point. Not a ceiling - a floor. Stakeholders don't average it out. They anchor to it. And suddenly a two-week sprint that delivers eight thoroughly verified stories looks like underperformance, because last month someone pushed a branch that did fifteen before lunch.

That's a real danger. And the answer to it is not to hide what's possible. It's to build the process that makes it repeatable and reviewable - so that when leadership asks why this sprint only closed eight stories, the answer is "because we verified all eight thoroughly" and not "because we only pulled eight tickets."

Speed without a review gate is just risk you haven't been billed for yet.

### So. Are We Washing Our Hands?

The PR is open. The tests are passing. The features work.

At some point someone has to walk into the operating room and look at the patient on the table. Not to rubber stamp it. Not to accept that everything the model inferred was correct. But to do the actual work of a senior engineer in this moment - which is verification, judgment, and the architectural awareness to know what needs to change before this goes to production.

Semmelweis couldn't make his colleagues wash their hands. He had the data, the results, and the receipts, and it still wasn't enough - because the problem was never the data.

The branch isn't asking you to abandon everything you know. It's just asking you to open it.

Are we going to wash our hands, or are we going to keep operating without them?

---

*May 2026 · Buddy Patton*