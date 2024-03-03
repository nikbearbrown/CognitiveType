# The Cognitive Type Project - Mapping Typography to Cognition

The Cognitive Type Project is focused on developing computational tools to enable the design of typefaces with varying cognitive properties. This initiative aims to empower typographers to craft fonts that enhance click-through rates for online ads, improve reading levels in children's books, enable dyslexics to create personalized type, or provide insights into customer reactions to textual content in media. A significant challenge in research related to mapping typography to cognition is the creation of thousands of typefaces with minor variations, a process that is both labor-intensive and requires the expertise of skilled typographers. Cognitive science research highlights that the design and form of letters, along with the text's overall layout, are crucial in determining the ease of reading and other cognitive properties of type such as perceived beauty and memorability. These factors affect not only the legibility and clarity of information presentation but also the likability of a typeface.

Our research is committed to generating publicly available datasets and establishing foundational models that link the detailed anatomy of type with eye-tracking data from individuals interacting with text. By enriching existing datasets with insights into the physical and cognitive impacts of typefaces, we strive to illuminate the role of typography in reading comprehension and aesthetic appreciation. To this end, we are taking several approaches for easily creating cognitive type, that is, type that can be assessed for cognition. We have developed a lexical database mapping thousands of typographic terms to representational images. We use languages like Metafont and tools like Variable Fonts to create cognitively relevant glyphs. We use generative models to generate type and understand the typographic latent space.

Finally, we are constructing a foundational model, inspired by AI systems like Midjourney and DALL·E, to facilitate the creation of an open-source text-to-type model. This model will enable typographers or researchers to specify the visual characteristics of a font, such as serif type, x-height, or bowl shape, translating the complex terminology of typeface classification into clear images for integration into typography software like FontForge or use in cognitive studies.

## Introduction 

Reading serves as a crucial mechanism for information acquisition and learning. The structure of letters and the overall design of typography play significant roles in the legibility of text, the clarity of information presentation, and the fluency of reading experiences. Research highlights the influence of typography on these aspects (Beier et al., 2017; Brath and Banissi, 2016; Gasser et al., 2005; Beier and Larson, 2013; Cacali, 2016; Bessemans, 2016a,b). A deeper understanding of how font types affect recall and comprehension is essential for effectively conveying critical information. Studies have indicated that serif fonts tend to facilitate better recall of information than sans serif fonts, suggesting the profound impact font choice can have on readability and comprehension. While the selection of fonts may seem arbitrary, it's clear that different typefaces yield distinct cognitive outcomes, with certain ones enhancing readability and aesthetic appeal more significantly. Despite this, the specific visual attributes of typefaces, such as serif styles or x-heights, and their direct effects on readability and aesthetic quality, have not been thoroughly investigated. This gap in research underscores the need for further exploration into how typography can optimize the reading experience and information retention.

### Assessing the Cognitive Properties of Text

Assessing the cognitive properties of text involves a variety of established techniques, each designed to measure how textual characteristics influence comprehension, recall, and engagement. These techniques include:

- **Eye Tracking:** Measures where and for how long a reader looks at different parts of a text, providing insights into reading patterns, comprehension difficulties, and interests.
- **Reading Speed Tests:** Evaluate how quickly text can be read while maintaining comprehension. This can help in understanding the legibility and readability of different fonts or layouts.
- **Recall and Comprehension Tests:** After reading, participants are asked to recall information or answer questions about the text. This assesses how well information is understood and retained.
- **Dual-Task Methodology:** Involves having participants perform a secondary task while reading to measure cognitive load. The impact of text layout or typography on cognitive effort can be evaluated by how it affects performance on the secondary task.
- **fMRI and EEG:** Neuroimaging techniques like functional Magnetic Resonance Imaging (fMRI) and Electroencephalography (EEG) can observe brain activity in response to reading text. These methods can uncover the neural correlates of language processing and cognitive engagement.
- **Think-Aloud Protocols:** Participants verbalize their thoughts while reading, offering insights into their cognitive processes, strategies, and areas of difficulty.
- **Usability Testing:** In the context of digital texts, usability tests can assess how easily users can navigate, find information, and fulfill tasks, highlighting the cognitive impact of design choices.
- **A/B Testing:** Comparing two versions of a text to see which performs better in terms of reader engagement, comprehension, or preference. This can be particularly useful in digital environments for optimizing content presentation.

These methods can be used individually or in combination to provide a comprehensive understanding of how different aspects of text affect cognitive processing, engagement, and overall reading experience.


# References for Cognitive Type


* Bessemans, A. (2016a). Typefaces for children’s reading. *TMG J. Media Hist.*, 19, 1–9. doi: 10.18146/2213-7653.2016.268
* Bessemans, A. (2016b). Matilda: a typeface for children with low vision. *Digit. Fonts Reading* 2016, 8–34. doi: 10.1142/9789814759540_0002
* Beier, S., Sand, K., and Starrfelt, R. (2017). Legibility implications of embellished display typefaces. *Visible Lang.*, 51, 112–133.
* 8. Beier, S., and Larson, K. (2013). How does typeface familiarity affect reading performance and reader preference? *Inf. Design J.*, 20, 16–31. doi: 10.1075/idj.20.1.02bei
* Bigelow, C. (2019). Typeface features and legibility research. *Vis. Res.*, 165, 162–172. doi: 10.1016/j.visres.2019.05.003
* Brath, R., and Banissi, E. (2016). Using typography to expand the design space of data visualization. *J Design Econ. Innov.*, 2, 59–87. doi: 10.1016/j.sheji.2016.05.003
* Celhay, F., Boysselle, J., and Cohen, J. (2015). Food packages and communication through typeface design: the exoticism of exotypes. *Food Qual. Prefer.*, 39, 167–175. doi: 10.1016/j.foodqual.2014.07.009
* Childers, T. L., and Jass, J. (2002). All dressed up with something to say: effects of typeface semantic associations on brand perceptions and consumer memory. *J. Consum. Psychol.*, 12, 93–106. doi: 10.1207/S15327663JCP1202_03
* Dressler, E. (2019). *Understanding the Effect of Font Type on Reading Comprehension/Memory Under Time-Constrains*. Omaha: University of Nebraska at Omaha.
* Gasser, M., Haffeman, J. B. M., and Tan, R. (2005). The influence of font type on information recall. *N. Am. J. Psychol.*, 7, 181–188.
* Hyndman, S. (2016). *Why Fonts Matter*. London: Virgin Books, An Imprint of Ebury Publishing.
* Koch, E. B. (2012). Emotion in typographic design: an empirical examination. *Visible Lang.*, 46, 206–228.
* Larson, K., Hazlett, R. L., Chaparro, B. S., and Picard, R. W. (2006). Measuring the Aesthetics of Reading. Proceedings of HCI, People and Computers XX–Engage, 41–56.
* Larson, K., and Picard, R. (2005). The Aesthetics of Reading. Available at: https://affect.media.mit.edu/pdfs/05.larson-picard.pdf (Accessed June 6, 2022).
* Lewis, C., and Walker, P. (1989). Typographic influences on reading. *Br. J. Psychol.*, 80, 241–257. doi: 10.1111/j.2044-8295.1989.tb02317.x
* Mackiewicz, J. (2005). How to use five letterforms to gauge a typeface’s personality: a research-driven method. *J. Tech. Writ. Commun.*, 35, 291–315. doi: 10.2190/LQVLEJ9Y-1LRX-7
* McLean, R. (1997). *The Manual of Typography*. London: Thames and Hudson.
* Mead, J. A., and Hardesty, D. M. (2018). Price font disfluency: anchoring effects on future price expectations. * J. Retail.*, 94, 102–112. doi: 10.1016/j.jretai.2017.09.003
* Oppenheimer, D. M., and Frank, M. C. (2008). A rose in any other font would not smell as sweet: effects of perceptual fluency on categorization. *Cognition*, 106, 1178–1194. doi: 10.1016/j.cognition.2007.05.010
* Price, J., McElroy, K., and Martin, N. J. (2016). The role of font size and font style in younger and older adults predicted and actual recall performance. *Aging Neuropsychol. Cogn.*, 23, 366–388. doi: 10.1080/13825585.2015.1102194
* Tobii Pro (2017). *Tobii Studio User’s Manual (Version 3.4.8)*. Stockholm: Tobii AB.
* Pušnik, N., Podlesek, A., and Možina, K. (2016). Typeface comparison − does the x-height of lower-case letters increased to the size of upper-case letters speed up recognition? *Int. J. Ind. Ergon.*, 54, 164–169. doi: 10.1016/j.ergon.2016.06.002
* Shaikh, A. D., Chaparro, B. S., and Fox, D. (2006). Perception of fonts: perceived personality traits and uses. *Usability News* 8.
* Velasco, C., Beh, E. J., Le, T., and Marmolejo-Ramos, F. (2018a). The shapes associated with the concept of ‘sweet and sour’ foods. *Food Qual. Prefer.*, 68, 250–257. doi: 10.1016/j.foodqual.2018.03.012
* Velasco, C., Woods, A. T., Marks, L. E., Cheok, A. D., and Spence, C. (2016). The semantic basis of taste-shape associations. *PeerJ*, 4, 1–23. doi: 10.7287/PEERJ.PREPRINTS.1366
* Wilkins, A., Cleave, R., Grayson, N., and Wilson, L. (2009). Typography for children may be inappropriately designed. *J. Res. Read.*, 32, 402–412. doi: 10.1111/j.1467-9817.2009.01402.x
* Woods, R. J., Davis, K., and Scharff, L. F. V. (2005). Effects of typeface and font size on legibility for children. *Am. J. Psychol. Res.*, 1, 86–102.
* Wu, R., Shah, E. D., and Kardes, F. R. (2019). “The struggle isn’t real”: how need for cognitive closure moderates inference from disfluency. *J. Bus. Res.*, 109, 585–594. doi: 10.1016/j.jbusres.2019.03.042


