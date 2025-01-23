# MyDECIDE

## Background

MyDECIDE was one part of the DECIDE project. The DECIDE project tested an adaptive sampling approach by encouraging biological recorders to generate higher value biological records by prompting changes to the locations where they collected data. The project was enabled by a web application (called the DECIDE Recorder Tool ) which provided users a means to identify high priority geographic locations for recording butterflies and moths in Great Britain; however, the app provided no direct feedback to the user. Recorders could use the DECIDE Recorder Tool to identify locations in any focal landscape (5km radius) that were high priority for recording based on uncertainty from species distribution models. In MyDECIDE, we sent participants data-generated emails containing ‘data stories’ about butterfly recording. All the data stories related to the locality where the participant had recently recorded; some were generically about recording in that area (‘non-personalised’), while some made explicit reference to the person’s own records ('personalised’), and there were four versions of each, designed to appeal to different recorder motivations. Each recorder received a different data story (or the control non-dynamic newsletter) each time the emails were sent out. The emails contained user-specific hyperlinks that linked to specific content or a view within the Tool to track user engagement from the data story in the MyDECIDE email to the DECIDE recorder tool.

We co-designed a set of digital feedback options (denoted as ‘data stories’) with potential participants, including both personalised and non-personalised versions. We sought to design options that appealed to different motivations of citizen scientists. Participants (n = 847) subscribed to receive occasional emails, each consisting of one data story. The impact of the data stories was assessed by (i) evaluating preference between different data stories through questionnaires, and (ii) evaluating impact of receiving feedback through a quantitative analysis of participants’ recording activity during the study period, compared to a matched background sample of non-participant recorders .

## Who was involved

 * Simon Rolph - UKCEH
 * Cagatay Turkay - University of Warwick
 * Michael Pocock - UKCEH
 * Tom August - UKCEH
 * Zoe Randle - Butterfly Conservation
 * Advaith Siddharthan- Siddharthan

## External references

 * DECIDE app: [decide.ceh.ac.uk](https://decide.ceh.ac.uk/opts/scoremap)
 * Information page on UKCEH website: https://www.ceh.ac.uk/our-science/projects/decide
 * Development codebase: https://github.com/simonrolph/DECIDE-WP3-newsletter 

## Motivation

The primary objective of the feedback was to drive traffic to the recorder app to support the reseach aims of the DECIDE project, however we then used this as an opportunity for research on the role of personalised automated feedback in influencing recording behaviour.

## Ideation/design process

 * The design of data stories was guided by a mix of methods, including literature reviews, co-design workshops, and iterative prototyping. Initial inspiration and guidelines were drawn from visualisation and narrative storytelling research, focusing on the "annotated chart" genre, which suits email formats and supports an author-driven approach. This resulted in a generic data story narrative structure populated by recorder data. 
 * To cater to different motivations, research on citizen scientists' motivations informed the development of data story ideas. These motivations were extrinsic (e.g., career development), intrinsic (e.g., environmental contributions), or hybrid (e.g., social or fun). The design process began with generative sketching, producing 22 sketches considering recorder motivations, data characteristics, and project goals. 
 * These sketches were distilled into six design dimensions across two categories: methods of persuasion (Purpose, Social Mechanism, Temporality) and content dimensions (geographic, temporal, and taxonomic scope). From these, eight viable concepts were identified and refined through co-design workshops with citizen scientists. 
 * Four data stories were selected for further development, chosen for their engagement potential, diversity, and alignment with the design dimensions. These were iteratively refined.

## Tech stack

 * R and R markdown - for data processing and generating the content
 * Blastula R package - for producing html in email format and for sending the emails (via SMTP)

## Included content

### Concepts

 * A set of 8 personalised feedback visualisation concepts produced by the project team

### Prototypes

Early implementations

### Implementations

Four data stories, each with a personalised and non-personalised version. The identity of the recorder has been removed from the email content. The format is HTML.

 * Great find
   * [Personalised](https://biologicalrecordscentre.github.io/recorder-feedback-repository/projects/MyDECIDE_2022/implementations/great_find_personalised.html) 
   * [Non-personalised](https://biologicalrecordscentre.github.io/recorder-feedback-repository/projects/MyDECIDE_2022/implementations/great_find_non_personalised.html) 
 * Extra mile
   * [Personalised](https://biologicalrecordscentre.github.io/recorder-feedback-repository/projects/MyDECIDE_2022/implementations/extra-mile_personalised.html) 
   * [Non-personalised](https://biologicalrecordscentre.github.io/recorder-feedback-repository/projects/MyDECIDE_2022/implementations/extra-mile_non_personalised.html) 
 * Community
   * [Personalised](https://biologicalrecordscentre.github.io/recorder-feedback-repository/projects/MyDECIDE_2022/implementations/community_personalised.html) 
   * [Non-personalised](https://biologicalrecordscentre.github.io/recorder-feedback-repository/projects/MyDECIDE_2022/implementations/community_non_personalised.html) 
 * Impact
   * [Personalised](https://biologicalrecordscentre.github.io/recorder-feedback-repository/projects/MyDECIDE_2022/implementations/impact_personalised.html) 
   * [Non-personalised](https://biologicalrecordscentre.github.io/recorder-feedback-repository/projects/MyDECIDE_2022/implementations/impact_non_personalised.html) 
 * [Control email](https://biologicalrecordscentre.github.io/recorder-feedback-repository/projects/MyDECIDE_2022/implementations/control_email.html) 

### Code

Code can be found here: https://github.com/simonrolph/DECIDE-WP3-newsletter, specifically you can find the R markdown templates here: https://github.com/simonrolph/DECIDE-WP3-newsletter/tree/main/newsletter_templates