---
title: "Week 3: Spoken Language Processing in a Visual Context"
# subtitle: ""
author: "Yiling Huo"
date: \today
bibliography: eye-tracking-method.bib
csl: elsevier-vancouver.csl
reference-section-title: "References"

header-includes: 
  - \usepackage{gb4e}

nocite: |
  @tanenhaus2007eye; @huettig2011using

# Pandoc md YAML
geometry: "left=2cm,right=2cm,top=2cm,bottom=2cm"

# cd github\eye-tracking-workshop-slides\_handout

# pandoc week3.md -o week3.pdf -d default.yml
---

Research on eye movements in reading has a history of more than a century. In contrast, eye movements have only started to become a popular measure in studies of spoken language processing within the last couple of decades. In these studies, participants' eye movements to a visual display are recorded as they follow instructions, listen to sentences, or generate utterances about the "visual world". The visual world paradigm allows researchers to study real-time language comprehension and production in natural tasks. 

# The visual world paradigm

In a typical visual world experiment, the participants hear an utterance while looking at an experimental display, while their eye movements are recorded for later analyses. 

## The visual display

Typically, the visual display includes the object(s) mentioned in the utterance as well as a few distractors. The visual display can take the form of a semi-realistic scene, an array of objects, or even printed words. The visual display is typically presented 1-2 seconds before the onset of the utterance (preview time) and stays in view until the offset of the auditory stimuli. In some versions of the visual world paradigm, the visual display can be presented first, and a spoken sentence follows while a blank screen is shown. Such a setup is useful in the studies of short-term memory in language comprehension. 

![Typical visual world displays. Extract from @huettig2011using. \label{vwe-display}](img\vwe-display.jpg){width=30%}

## The auditory stimuli

## The task

## The linking hypothesis

Data collected in a visual world experiment is essentially the gaze position at particular time points in each trial. How to link these position data with language processing? The assumption that provides the link between language processing and eye movements in the visual world is essentially that **the activation of a linguistic representation determines the probability that a participant will shift attention to the corresponding picture and thus make a saccadic eye movement to fixate it**. Therefore, when gaze positions are averaged across multiple trials, researchers can calculate the proportion/probability of looks to the target object, representing activation of the target word. 

![Proportion of looks to each object in the visual display when listening to instructions such as "Pick up the beaker". Extract from @allopenna1998tracking. \label{allopenna}](img\allopenna.png){width=45%}

## Production studies

In production studies, participants see sets of objects or cartoons of events or actions. No spoken input is presented, but instead the participants are asked to describe what they see. Researchers typically determine which objects are inspected, in which order they are inspected, and when they are inspected relative to the participants' speech output. This provides information about the ways speakers coordinate the generation of utterance plans with the overt articulation. 

# Using the visual world paradigm to study...

## Word recognition

### Allopenna et al. (1998) @allopenna1998tracking {-}

Allopenna et al. (1998) had participants follow spoken instructions to pick out objects shown on the screen (e.g. "Pick up the beaker."). Four objects were shown on the screen: the referent (beaker), a cohort (beetle), a rhyme (speaker), and an unrelated object (carriage). Allopenna et al. observed a (non-linear) rising curve for the probability of fixating on the referent, and a rising-then-falling curve for the probability of fixating on phonologically overlapping objects (the cohort and the rhyme). This provides evidence for a continuous lexical access model during spoken word recognition where all candidates that are temporarily consistent with the speech signal are activated before the speech signal provides enough information to identify the single correct lexical item. 

## Sentence processing

### Cooper (1974) @cooper1974control  {-}

One of the first classic studies of spoken language in the visual world was by Roger Cooper (1974). Cooper tracked participants' eye movements as they listened to stories while looking at a display of pictures. He found that participants initiated saccades to pictures that were named in the stories, as well as pictures that were associated with words in the story (Africa - lion, zebra, snake). Moreover, fixations were often generated before the end of the word. This provides important evidence that visual attention is highly correlated with spoken sentence processing. 

![Example visual display in @@cooper1974control. Extract from @cooper1974control. \label{cooper1974}](img\cooper-1976-visual.png)

### Effect of the visual context: Tanenhaus et al. (1995) @tanenhaus1995integration {-}

To fully understand any visual world experiment, we need to be aware that the visual display itself may have an effect on how the listeners interpret the sentence. Tanenhause et al. (1995) is one of the most classic studies that demonstrate this. Tanenhaus and colleagues presented participants with sentences such as “Put the apple on the towel in the box”, where the first prepositional phrase (“on the towel” in the example) is temporarily ambiguous between denoting the destination of the apple or its current location. In the one-referent condition of the experiment participants saw just one apple on a towel, an empty towel, a box, and a pencil. In the two-referent condition there were two apples: one on a towel and one on a napkin. In this condition, a modifier was needed to inform the listener which of the two apples should be moved. They found that there were significantly more early looks to the empty towel in the one-referent than in the two-referent condition. This is strong evidence that listeners can use visual information immediately to disambiguate sentence structures. Not only does this study tell us to be a bit careful about the visual display when designing a visual world experiment, it also shows that language processing is subject to a broad range of linguistic as well as non-linguistic constraints. 

![Typical sequence of eye movements in the two conditions of @tanenhaus1995integration. Extract from @tanenhaus1995integration. \label{tanenhaus1995}](img\tanenhaus1995.png){width=45%}

### Ambiguities

#### Snedeker and Trueswell (2004) @snedeker2004developing

## Speech production