# Pollinator Monitoring Scheme (PoMS) Recorder Feedback Demonstrator

## Background

This work was carried out under Natural Capital Ecosystem Assessment concept note 109 as a demonstrator of the recorder feedback extensible codebase.

The UK Pollinator Monitoring Scheme (UKPoMS) is a monitoring scheme collecting systematic data on the abundance of bees, hoverflies and other flower-visiting insects at a national scale. These data will form an invaluable resource from which to measure trends in pollinator populations and target conservation efforts. UK PoMS is a partnership funded jointly by the UK Centre for Ecology & Hydrology (UKCEH) and Joint Nature Conservation Committee (JNCC). In this demonstrator we aim to apply the Recorder Feedback system within a limited scope use case. We decided to use UK PoMS as a demonstrator of the Recorder Feedback system because it showcases flexibility of Recorder Feedback system to work with structured environmental monitoring in addition to species monitoring (biological recording)

## External references

 * [UK PoMS website](https://ukpoms.org.uk/)

## Motivation

The content development team came up with the following possible motivations:

Data-centric:
 * We’d like more FIT Counts
 * We'd like more Counts from locations that have not previously been recorded, especially the under-populated parts of the country
 * We'd like Counts to be done repeatedly in the same place
 * We'd like as many Counts as possible from the target flowers (without excluding people who aren't able to find a target flower)
 * We’d like people to make a FIT Count if they haven't done one for a while (to avoid temporal gaps)

Recorder-centric:
 * FIT Counters want to see how their records compare to other people
 * FIT Counters want to see impact of their monitoring, and recognition of effort
 * Meet the curiosity needs of FIT Counters
 * Provide competitiveness (for those who find that motivating), between themselves (this year versus last year) or others (you versus average)
 * Feeling part of a collective effort / community
 * Highlight reaching certain milestones or achievements

We also considered possible adverse impacts we wanted to avoid:
 * Reporting actual insect counts, we risk presenting data that could be used to summarise results, undermining the role of the formal annual reports.
 * Make someone feel inadequate by comparing to average e.g. person A did 1 count compared to average of 5, does this motivate or deter?
 * Users feeling that the personalised feedback is “nagging” them to do more FIT Counts, especially if they are already doing as many as they can.

## Ideation/design process

 * An ethics application was made to the UKCEH Human Ethics Research Committee to undertake the work.
 * The content development team (Simon Rolph, Martin Harvey, Claire Carvell, Abigail Lowe) used an internal workshop to conceptualised ideas for PoMS personalised feedback 
 * The personalised feedback was implemented using the Recorder Feedback Content codebase. Versions of the feedback were shared with the content development team, and we used iterative feedback to improve the content.
 * We identified a limited pool of FIT Counters to participate in the trial demonstrator. We sent an email to them inviting them to be a participant in the trial.
 * We sent an email containing the personalised feedback to the trial participants.
 * Short interviews (30 minutes) were held with six participants, transcripts were recorded.

## Challenges and lessons learnt

What were the main issues you encountered doing this work and how to did overcome them, or what would you do differently?

## Tech stack

 * Recorder feedback extensible R code: https://github.com/BiologicalRecordsCentre/recorder-feedback-content

## Included content

### Concepts

 * [5 data story concepts from internal ideation workshop](https://github.com/BiologicalRecordsCentre/recorder-feedback-repository/tree/main/projects/PoMS_2024/concepts/UK_PoMS_Demonstrator_concepts.pdf)

### Implementations

 * [An example of the demonstrator personalised feedback email](https://biologicalrecordscentre.github.io/recorder-feedback-repository/projects/PoMS_2024/implementations/poms_personalised_feedback.html)

### Code

See the code developed as a fork of the recorder-feedback-content repository: https://github.com/simonrolph/recorder-feedback-content-PoMS