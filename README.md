<div class="ltx_page_content"><div class="section" id="target-section"><div id="license-tr">License: arXiv.org perpetual non-exclusive license</div></div>
<article class="ltx_document ltx_authors_1line">
<h1 class="ltx_title ltx_title_document">The Cognitive Type Project - Mapping Typography to Cognition</h1><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
<div class="ltx_authors">
<span class="ltx_creator ltx_role_author">
<span class="ltx_personname">Nik Bear Brown 
<br class="ltx_break"><span class="ltx_text ltx_font_typewriter" id="id1.1.id1">ni.brown@neu.edu</span>
<br class="ltx_break"><sup class="ltx_sup" id="id2.2.id2">1</sup>Abecedarian, LLC 
<br class="ltx_break"><sup class="ltx_sup" id="id3.3.id3">2</sup>Northeastern University
</span></span>
</div><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
<div class="ltx_dates">(March 2024)</div>
<section class="ltx_section" id="S1">
<h2 class="ltx_title ltx_title_section">
<span class="ltx_tag ltx_tag_section">1 </span>The Cognitive Type Project</h2><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
<section class="ltx_subsection" id="S1.SS1">
<h3 class="ltx_title ltx_title_subsection">
<span class="ltx_tag ltx_tag_subsection">1.1 </span>Abstract</h3><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
<div class="ltx_para" id="S1.SS1.p1">
<p class="ltx_p" id="S1.SS1.p1.1">The Cognitive Type Project is focused on developing computational tools to enable the design of typefaces with varying cognitive properties. This initiative aims to empower typographers to craft fonts that enhance click-through rates for online ads, improve reading levels in children’s books, enable dyslexics to create personalized type, or provide insights into customer reactions to textual content in media. A significant challenge in research related to mapping typography to cognition is the creation of thousands of typefaces with minor variations, a process that is both labor-intensive and requires the expertise of skilled typographers. Cognitive science research highlights that the design and form of letters, along with the text’s overall layout, are crucial in determining the ease of reading and other cognitive properties of type such as perceived beauty and memorability. These factors affect not only the legibility and clarity of information presentation but also the likability of a typeface.</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
<div class="ltx_para" id="S1.SS1.p2">
<p class="ltx_p" id="S1.SS1.p2.1">Our research is committed to generating publicly available datasets and establishing foundational models that link the detailed anatomy of type with eye-tracking data from individuals interacting with text. By enriching existing datasets with insights into the physical and cognitive impacts of typefaces, we strive to illuminate the role of typography in reading comprehension and aesthetic appreciation. To this end, we are taking several approaches for easily creating cognitive type, that is, type that can be assessed for cognition. We have developed a lexical database mapping thousands of typographic terms to representational images. We use languages like Metafont and tools like Variable Fonts to create cognitively relevant glyphs. We use generative models to generate type and understand the typographic latent space.
</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
<div class="ltx_para" id="S1.SS1.p3">
<p class="ltx_p" id="S1.SS1.p3.1">Finally, we are constructing a foundational model, inspired by AI systems like Midjourney and DALL·E, to facilitate the creation of an open-source text-to-type model. This model will enable typographers or researchers to specify the visual characteristics of a font, such as serif type, x-height, or bowl shape, translating the complex terminology of typeface classification into clear images for integration into typography software like FontForge or use in cognitive studies.</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</section>
<section class="ltx_subsection" id="S1.SS2">
<h3 class="ltx_title ltx_title_subsection">
<span class="ltx_tag ltx_tag_subsection">1.2 </span>Introduction </h3><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
<div class="ltx_para" id="S1.SS2.p1">
<p class="ltx_p" id="S1.SS2.p1.1">Reading serves as a crucial mechanism for information acquisition and learning. The structure of letters and the overall design of typography play significant roles in the legibility of text, the clarity of information presentation, and the fluency of reading experiences. Research highlights the influence of typography on aspects such as legibility, comprehension, and aesthetic appeal (Beier et al., 2013; Beier et al., 2017; Bessemans, 2016a; Bessemans, 2016b; Bigelow, 2019; Brath and Banissi, 2016; Dressler, 2019; French et al., 2013; Gasser et al., 2005; Gasser et al., 2005; Kanfer and Ackerman, 1989; Larson et al., 2006; Larson and Picard, 2005; Lewis and Walker, 1989; Oppenheimer and Frank, 2008; Price et al., 2016; Pušnik et al., 2016; Wilkins et al., 2009; Woods et al., 2005). These studies indicate that font types not only affect the ease of reading but also contribute significantly to the retention and processing of information. Serif fonts, for example, have been shown to facilitate better recall than sans serif fonts, suggesting a profound impact of font choice on readability and comprehension. Despite the apparent arbitrariness in selecting fonts, it is clear that different typefaces yield distinct cognitive outcomes, with some enhancing readability and aesthetic appeal more than others.</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
<div class="ltx_para" id="S1.SS2.p2">
<p class="ltx_p" id="S1.SS2.p2.1">However, the specific visual attributes of typefaces, such as serif styles or x-heights, and their direct effects on readability and aesthetic quality, have not been thoroughly investigated, highlighting the need for further research into how typography can enhance the reading experience and information retention. A deeper understanding of how font types affect recall and comprehension is essential for effectively conveying critical information. Studies have indicated that serif fonts tend to facilitate better recall of information than sans serif fonts, suggesting the profound impact font choice can have on readability and comprehension. While the selection of fonts may seem arbitrary, it’s clear that different typefaces yield distinct cognitive outcomes, with certain ones enhancing readability and aesthetic appeal more significantly. Despite this, the specific visual attributes of typefaces, such as serif styles or x-heights, and their direct effects on readability and aesthetic quality, have not been thoroughly investigated. This gap in research underscores the need for further exploration into how typography can optimize the reading experience and information retention.</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</section>
<section class="ltx_subsection" id="S1.SS3">
<h3 class="ltx_title ltx_title_subsection">
<span class="ltx_tag ltx_tag_subsection">1.3 </span>Assessing the Cognitive Properties of Text</h3><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
<div class="ltx_para" id="S1.SS3.p1">
<p class="ltx_p" id="S1.SS3.p1.1">Assessing the cognitive properties of text involves a variety of established techniques (Krafka K, et al., 2016; Dalmaijer, et al., 2014), each designed to measure how textual characteristics influence comprehension, recall, and engagement. These techniques include:</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
<div class="ltx_para" id="S1.SS3.p2">
<ul class="ltx_itemize" id="S1.I1">
<li class="ltx_item" id="S1.I1.i1" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span>
<div class="ltx_para" id="S1.I1.i1.p1">
<p class="ltx_p" id="S1.I1.i1.p1.1"><span class="ltx_text ltx_font_bold" id="S1.I1.i1.p1.1.1">Eye Tracking:</span> Measures where and for how long a reader looks at different parts of a text, providing insights into reading patterns, comprehension difficulties, and interests (Tobii Pro, 2017).</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</li>
<li class="ltx_item" id="S1.I1.i2" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span>
<div class="ltx_para" id="S1.I1.i2.p1">
<p class="ltx_p" id="S1.I1.i2.p1.1"><span class="ltx_text ltx_font_bold" id="S1.I1.i2.p1.1.1">Reading Speed Tests:</span> Evaluate how quickly text can be read while maintaining comprehension. This can help in understanding the legibility and readability of different fonts or layouts.</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</li>
<li class="ltx_item" id="S1.I1.i3" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span>
<div class="ltx_para" id="S1.I1.i3.p1">
<p class="ltx_p" id="S1.I1.i3.p1.1"><span class="ltx_text ltx_font_bold" id="S1.I1.i3.p1.1.1">Recall and Comprehension Tests:</span> After reading, participants are asked to recall information or answer questions about the text. This assesses how well information is understood and retained.</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</li>
<li class="ltx_item" id="S1.I1.i4" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span>
<div class="ltx_para" id="S1.I1.i4.p1">
<p class="ltx_p" id="S1.I1.i4.p1.1"><span class="ltx_text ltx_font_bold" id="S1.I1.i4.p1.1.1">Dual-Task Methodology:</span> Involves having participants perform a secondary task while reading to measure cognitive load. The impact of text layout or typography on cognitive effort can be evaluated by how it affects performance on the secondary task.</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</li>
<li class="ltx_item" id="S1.I1.i5" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span>
<div class="ltx_para" id="S1.I1.i5.p1">
<p class="ltx_p" id="S1.I1.i5.p1.1"><span class="ltx_text ltx_font_bold" id="S1.I1.i5.p1.1.1">fMRI and EEG:</span> Neuroimaging techniques like functional Magnetic Resonance Imaging (fMRI) and Electroencephalography (EEG) can observe brain activity in response to reading text. These methods can uncover the neural correlates of language processing and cognitive engagement.</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</li>
<li class="ltx_item" id="S1.I1.i6" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span>
<div class="ltx_para" id="S1.I1.i6.p1">
<p class="ltx_p" id="S1.I1.i6.p1.1"><span class="ltx_text ltx_font_bold" id="S1.I1.i6.p1.1.1">Think-Aloud Protocols:</span> Participants verbalize their thoughts while reading, offering insights into their cognitive processes, strategies, and areas of difficulty.</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</li>
<li class="ltx_item" id="S1.I1.i7" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span>
<div class="ltx_para" id="S1.I1.i7.p1">
<p class="ltx_p" id="S1.I1.i7.p1.1"><span class="ltx_text ltx_font_bold" id="S1.I1.i7.p1.1.1">Usability Testing:</span> In the context of digital texts, usability tests can assess how easily users can navigate, find information, and fulfill tasks, highlighting the cognitive impact of design choices.</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</li>
<li class="ltx_item" id="S1.I1.i8" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span>
<div class="ltx_para" id="S1.I1.i8.p1">
<p class="ltx_p" id="S1.I1.i8.p1.1"><span class="ltx_text ltx_font_bold" id="S1.I1.i8.p1.1.1">A/B Testing:</span> Comparing two versions of a text to see which performs better in terms of reader engagement, comprehension, or preference. This can be particularly useful in digital environments for optimizing content presentation.
</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</li>
</ul>
</div>
<figure class="ltx_figure" id="S1.F1"><img alt="Refer to caption" class="ltx_graphics ltx_centering ltx_img_landscape" height="102" id="S1.F1.g1" src="./The Cognitive Type Project - Mapping Typography to Cognition_files/Tobii-Pro-Glasses.png" width="299">
<figcaption class="ltx_caption ltx_centering"><span class="ltx_tag ltx_tag_figure">Figure 1: </span>Tobii Pro Glasses - Tobii Pro, 2017</figcaption>
</figure><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
<div class="ltx_para" id="S1.SS3.p3">
<p class="ltx_p" id="S1.SS3.p3.1">These methods can be used individually or in combination to provide a comprehensive understanding of how different aspects of text affect cognitive processing, engagement, and overall reading experience.</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</section>
<section class="ltx_subsection" id="S1.SS4">
<h3 class="ltx_title ltx_title_subsection">
<span class="ltx_tag ltx_tag_subsection">1.4 </span>Difficulties in Assessing the Cognitive Properties of Typefaces</h3><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
<div class="ltx_para" id="S1.SS4.p1">
<p class="ltx_p" id="S1.SS4.p1.1">It is widely acknowledged that typefaces impact cognitive processes. However, the development of new typefaces is notoriously labor-intensive. The Abecedarian Classification of Typefaces ((Brown, N., 2024b) outlines a multitude of dimensions influencing typeface style. To determine which dimensions influence cognition, researchers require a method to efficiently produce characters with particular traits. While text-to-image models such as Midjourney and DALL·E have yielded impressive visuals, they lack training in the nuances of typography and tend to produce generic characters rather than typefaces with specific features. Creating figures like those in in the book Fonts and Encodings (Haralambous, Y., 2007) would be challenging using general-purpose text-to-image models like Midjourney, DALL·E, or Bing Image Creator, as they do not specialize in typographic nuances.</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
<figure class="ltx_figure" id="S1.F2"><img alt="Refer to caption" class="ltx_graphics ltx_centering ltx_img_landscape" height="408" id="S1.F2.g1" src="./The Cognitive Type Project - Mapping Typography to Cognition_files/Font_Properties_Figure_1.png" width="538">
<figcaption class="ltx_caption ltx_centering"><span class="ltx_tag ltx_tag_figure">Figure 2: </span>Various typographic properties. Alessandrini’s dénominations préliminaires</figcaption>
</figure><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
<figure class="ltx_figure" id="S1.F3"><img alt="Refer to caption" class="ltx_graphics ltx_centering ltx_img_landscape" height="96" id="S1.F3.g1" src="./The Cognitive Type Project - Mapping Typography to Cognition_files/Font_Properties_Figure_2.png" width="538">
<figcaption class="ltx_caption ltx_centering"><span class="ltx_tag ltx_tag_figure">Figure 3: </span>Eleven types of serifs</figcaption>
</figure><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
<figure class="ltx_figure" id="S1.F4"><img alt="Refer to caption" class="ltx_graphics ltx_centering ltx_img_landscape" height="89" id="S1.F4.g1" src="./The Cognitive Type Project - Mapping Typography to Cognition_files/Font_Properties_Figure_3.png" width="538">
<figcaption class="ltx_caption ltx_centering"><span class="ltx_tag ltx_tag_figure">Figure 4: </span>The letter O from low to high contrast.</figcaption>
</figure><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
<figure class="ltx_figure" id="S1.F5"><img alt="Refer to caption" class="ltx_graphics ltx_centering ltx_img_landscape" height="96" id="S1.F5.g1" src="./The Cognitive Type Project - Mapping Typography to Cognition_files/Font_Properties_Figure_4.png" width="538">
<figcaption class="ltx_caption ltx_centering"><span class="ltx_tag ltx_tag_figure">Figure 5: </span>Some arm and termination styles.</figcaption>
</figure><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
<figure class="ltx_figure" id="S1.F6"><img alt="Refer to caption" class="ltx_graphics ltx_centering ltx_img_landscape" height="96" id="S1.F6.g1" src="./The Cognitive Type Project - Mapping Typography to Cognition_files/Font_Properties_Figure_5.png" width="538">
<figcaption class="ltx_caption ltx_centering"><span class="ltx_tag ltx_tag_figure">Figure 6: </span>Letter ’O’ shapes (perfect circle, flattened circle, rounded square, square, etc.
Figures 2 through 6 are from (Haralambous, Y., 2007))</figcaption>
</figure><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</section>
<section class="ltx_subsection" id="S1.SS5">
<h3 class="ltx_title ltx_title_subsection">
<span class="ltx_tag ltx_tag_subsection">1.5 </span>Creating Datasets Suitable for Assessing the Cognitive Properties of Typefaces</h3><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
<div class="ltx_para" id="S1.SS5.p1">
<p class="ltx_p" id="S1.SS5.p1.1">In the quest to create datasets suitable for assessing the cognitive properties of typefaces, the Cognitive Type Project has embarked on an exploratory journey utilizing a variety of innovative tools and methodologies. The project has delved into the realms of Programmatic Typography, Typography-Specific Programming Languages, Hybrid Font Design Tools, Variable Fonts, and Generative Models and Deep Learning. Each of these avenues offers unique capabilities and insights into the intricate relationship between typography and cognition. The use of MetaFont (Metafont: Knuth, D. E., 2024), a program designed to define and generate bitmap fonts, has been instrumental in creating typefaces that can be finely tuned to explore cognitive impacts. This approach, rooted in mathematical descriptions of typeface anatomy, allows for an unprecedented level of precision in font design.</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
<div class="ltx_para" id="S1.SS5.p2">
<p class="ltx_p" id="S1.SS5.p2.1">Furthermore, the project has leveraged Hybrid Font Design Tools like Glyphs, FontLab (FontLab: FontLab Ltd., 2024), and RoboFont (RoboFont: Van Rossum, F., 2024), which blend graphical user interfaces with scripting capabilities, enabling the creation and modification of typefaces with a high degree of control and creativity. The advent of Variable Fonts has introduced a new dimension of flexibility, allowing for the dynamic adjustment of font characteristics such as weight, width, and slant through a single font file. This capability is vital for creating versatile datasets that can simulate a wide range of typographic conditions. Additionally, the integration of Generative Models and Deep Learning has opened up possibilities for identifying and generating novel typeface attributes that could influence cognitive processing. These technological approaches are paving the way for the development of ”Text to Type” Foundational Models, which aim to transform the complex terminology of typeface classification into tangible, manipulable entities. By harnessing the strengths of MetaFont, Hybrid Font Design Tools, Variable Fonts, and Generative Models, the Cognitive Type Project is laying the groundwork for a new era of typography research, where the cognitive implications of type design are understood and utilized to their fullest potential. Below we overview the pros and cons of these approaches.</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
<section class="ltx_subsubsection" id="S1.SS5.SSS1">
<h4 class="ltx_title ltx_title_subsubsection">
<span class="ltx_tag ltx_tag_subsubsection">1.5.1 </span>Programatic Typography</h4><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
<div class="ltx_para" id="S1.SS5.SSS1.p1">
<p class="ltx_p" id="S1.SS5.SSS1.p1.1">The realm of programmatic typography offers an intriguing avenue for the creation of typographic art, leveraging the power of code to draw and design. Tools such as Processing (Processing: Reas, C., et al., 2024), p5.js (P5.js: McCarthy, L., et al., 2024), OpenFrameworks (OpenFrameworks: The openFrameworks Team, 2024), NodeBox (NodeBox: Lieven van Velthoven, et al., 2024), and Cinder (Cinder: The Cinder Project Team, 2024) enable designers and programmers alike to experiment with and prototype unique typographic forms and patterns. Processing, for instance, is an accessible platform that introduces beginners to the creation of glyphs through simple coding principles, emphasizing experimentation over precision. Similarly, p5.js facilitates the creation of web-based and interactive typographic elements, making it an excellent tool for integrating typography with web technologies.</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
<div class="ltx_para" id="S1.SS5.SSS1.p2">
<p class="ltx_p" id="S1.SS5.SSS1.p2.1">However, the creation of typefaces suitable for cognitive type—that is, typefaces designed with the understanding of how typographic form affects cognition—presents a more complex challenge. These tools, while wonderful for artistic endeavors, require a substantial amount of programming work to produce typefaces that are both aesthetically pleasing and functionally effective for cognitive purposes. OpenFrameworks and Cinder, with their extensive graphics libraries and capabilities for high-performance design, offer powerful resources for the creation of intricate glyph shapes. Yet, their steep learning curves and the necessity for experienced programming skills may pose barriers to those focusing solely on typography. NodeBox, with its Python-based platform geared towards generative design, excels in creating complex forms and is similarly positioned more towards typographic art than practical typeface development for cognitive applications. In essence, while these tools open up vast possibilities for artistic expression within typographic design, bridging the gap between artistic experimentation and the practical creation of typefaces optimized for cognitive enhancement remains a significant endeavor, necessitating a deep integration of design principles, cognitive science, and programming expertise.</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
<div class="ltx_para" id="S1.SS5.SSS1.p3">
<ul class="ltx_itemize" id="S1.I2">
<li class="ltx_item" id="S1.I2.i1" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span>
<div class="ltx_para" id="S1.I2.i1.p1">
<p class="ltx_p" id="S1.I2.i1.p1.1"><span class="ltx_text ltx_font_bold" id="S1.I2.i1.p1.1.1">Processing:</span> Enables beginners to create glyphs using simple coding principles, focusing on experimentation and prototyping. Processing is better suited to typographic art than cognitive type.</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</li>
<li class="ltx_item" id="S1.I2.i2" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span>
<div class="ltx_para" id="S1.I2.i2.p1">
<p class="ltx_p" id="S1.I2.i2.p1.1"><span class="ltx_text ltx_font_bold" id="S1.I2.i2.p1.1.1">p5.js:</span> Allows for the creation of web-based and interactive typographic elements using JavaScript. It integrates easily with web technologies but is not well-suited for creating complete, production-ready fonts.</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</li>
<li class="ltx_item" id="S1.I2.i3" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span>
<div class="ltx_para" id="S1.I2.i3.p1">
<p class="ltx_p" id="S1.I2.i3.p1.1"><span class="ltx_text ltx_font_bold" id="S1.I2.i3.p1.1.1">OpenFrameworks:</span> A C++ toolkit for high-performance typographic design. Offers a broad graphics library but has a steeper learning curve and is not focused on typography.</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</li>
<li class="ltx_item" id="S1.I2.i4" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span>
<div class="ltx_para" id="S1.I2.i4.p1">
<p class="ltx_p" id="S1.I2.i4.p1.1"><span class="ltx_text ltx_font_bold" id="S1.I2.i4.p1.1.1">NodeBox:</span> Geared towards generative design, excellent for crafting complex typographic forms and patterns. It is Python-based and open-source but more suited to typographic art than cognitive type.</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</li>
<li class="ltx_item" id="S1.I2.i5" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span>
<div class="ltx_para" id="S1.I2.i5.p1">
<p class="ltx_p" id="S1.I2.i5.p1.1"><span class="ltx_text ltx_font_bold" id="S1.I2.i5.p1.1.1">Cinder:</span> A C++ library for creating intricate glyph shapes but is not specifically geared towards typography. Requires experienced C++ programmers.</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</li>
</ul>
</div>
</section>
<section class="ltx_subsubsection" id="S1.SS5.SSS2">
<h4 class="ltx_title ltx_title_subsubsection">
<span class="ltx_tag ltx_tag_subsubsection">1.5.2 </span>Typography-Specific Programming Languages</h4><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
<div class="ltx_para" id="S1.SS5.SSS2.p1">
<p class="ltx_p" id="S1.SS5.SSS2.p1.1">Metafont is a description language used to define raster fonts. It is also the name of the interpreter that executes Metafont code, generating bitmap fonts that can be embedded into, for example, PostScript. Metafont was devised by Donald Knuth as a companion to his TeX typesetting system.</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
<div class="ltx_para" id="S1.SS5.SSS2.p2">
<ul class="ltx_itemize" id="S1.I3">
<li class="ltx_item" id="S1.I3.i1" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span>
<div class="ltx_para" id="S1.I3.i1.p1">
<p class="ltx_p" id="S1.I3.i1.p1.1"><span class="ltx_text ltx_font_bold" id="S1.I3.i1.p1.1.1">Metafont:</span></p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
<ul class="ltx_itemize" id="S1.I3.i1.I1">
<li class="ltx_item" id="S1.I3.i1.I1.i1" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item"><span class="ltx_text ltx_font_bold" id="S1.I3.i1.I1.i1.1.1.1">–</span></span>
<div class="ltx_para" id="S1.I3.i1.I1.i1.p1">
<p class="ltx_p" id="S1.I3.i1.I1.i1.p1.1"><span class="ltx_text ltx_font_bold" id="S1.I3.i1.I1.i1.p1.1.1">Purpose:</span> A language designed specifically for creating bitmap fonts.</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</li>
<li class="ltx_item" id="S1.I3.i1.I1.i2" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item"><span class="ltx_text ltx_font_bold" id="S1.I3.i1.I1.i2.1.1.1">–</span></span>
<div class="ltx_para" id="S1.I3.i1.I1.i2.p1">
<p class="ltx_p" id="S1.I3.i1.I1.i2.p1.1"><span class="ltx_text ltx_font_bold" id="S1.I3.i1.I1.i2.p1.1.1">Creator:</span> Devised by Donald Knuth as a complement to the TeX typesetting system.</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</li>
<li class="ltx_item" id="S1.I3.i1.I1.i3" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item"><span class="ltx_text ltx_font_bold" id="S1.I3.i1.I1.i3.1.1.1">–</span></span>
<div class="ltx_para" id="S1.I3.i1.I1.i3.p1">
<p class="ltx_p" id="S1.I3.i1.I1.i3.p1.1"><span class="ltx_text ltx_font_bold" id="S1.I3.i1.I1.i3.p1.1.1">Functionality:</span> Allows designers to define fonts programmatically with adjustable parameters and geometric equations.</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</li>
<li class="ltx_item" id="S1.I3.i1.I1.i4" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item"><span class="ltx_text ltx_font_bold" id="S1.I3.i1.I1.i4.1.1.1">–</span></span>
<div class="ltx_para" id="S1.I3.i1.I1.i4.p1">
<p class="ltx_p" id="S1.I3.i1.I1.i4.p1.1"><span class="ltx_text ltx_font_bold" id="S1.I3.i1.I1.i4.p1.1.1">Output:</span> Produces bitmap fonts, which are made up of pixels, making them resolution-dependent.</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</li>
<li class="ltx_item" id="S1.I3.i1.I1.i5" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item"><span class="ltx_text ltx_font_bold" id="S1.I3.i1.I1.i5.1.1.1">–</span></span>
<div class="ltx_para" id="S1.I3.i1.I1.i5.p1">
<p class="ltx_p" id="S1.I3.i1.I1.i5.p1.1"><span class="ltx_text ltx_font_bold" id="S1.I3.i1.I1.i5.p1.1.1">Specialization:</span> Uniquely tailored for typographic tasks, enabling the design of fonts through mathematical descriptions.</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</li>
<li class="ltx_item" id="S1.I3.i1.I1.i6" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item"><span class="ltx_text ltx_font_bold" id="S1.I3.i1.I1.i6.1.1.1">–</span></span>
<div class="ltx_para" id="S1.I3.i1.I1.i6.p1">
<p class="ltx_p" id="S1.I3.i1.I1.i6.p1.1"><span class="ltx_text ltx_font_bold" id="S1.I3.i1.I1.i6.p1.1.1">Integration:</span> Primarily used with TeX, providing a high degree of control over how characters are rendered in documents typeset with TeX.</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</li>
</ul>
</div>
</li>
</ul>
</div>
<div class="ltx_para" id="S1.SS5.SSS2.p3">
<p class="ltx_p" id="S1.SS5.SSS2.p3.1">MetaPost (MetaPost: Hobby, J. D., 2024) refers to both a programming language and the interpreter of the MetaPost programming language. Both are derived from Donald Knuth’s Metafont language and interpreter. MetaPost produces vector graphic diagrams from a geometric/algebraic description. The language shares Metafont’s declarative syntax for manipulating lines, curves, points, and geometric transformations.</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
<div class="ltx_para" id="S1.SS5.SSS2.p4">
<ul class="ltx_itemize" id="S1.I4">
<li class="ltx_item" id="S1.I4.i1" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span>
<div class="ltx_para" id="S1.I4.i1.p1">
<p class="ltx_p" id="S1.I4.i1.p1.1"><span class="ltx_text ltx_font_bold" id="S1.I4.i1.p1.1.1">MetaPost:</span></p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
<ul class="ltx_itemize" id="S1.I4.i1.I1">
<li class="ltx_item" id="S1.I4.i1.I1.i1" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item"><span class="ltx_text ltx_font_bold" id="S1.I4.i1.I1.i1.1.1.1">–</span></span>
<div class="ltx_para" id="S1.I4.i1.I1.i1.p1">
<p class="ltx_p" id="S1.I4.i1.I1.i1.p1.1"><span class="ltx_text ltx_font_bold" id="S1.I4.i1.I1.i1.p1.1.1">Purpose:</span> Based on Metafont, it focuses on creating precise technical illustrations and vector graphics.</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</li>
<li class="ltx_item" id="S1.I4.i1.I1.i2" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item"><span class="ltx_text ltx_font_bold" id="S1.I4.i1.I1.i2.1.1.1">–</span></span>
<div class="ltx_para" id="S1.I4.i1.I1.i2.p1">
<p class="ltx_p" id="S1.I4.i1.I1.i2.p1.1"><span class="ltx_text ltx_font_bold" id="S1.I4.i1.I1.i2.p1.1.1">Functionality:</span> Utilizes a similar syntax to Metafont but produces vector graphics, which are scalable and resolution-independent.</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</li>
<li class="ltx_item" id="S1.I4.i1.I1.i3" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item"><span class="ltx_text ltx_font_bold" id="S1.I4.i1.I1.i3.1.1.1">–</span></span>
<div class="ltx_para" id="S1.I4.i1.I1.i3.p1">
<p class="ltx_p" id="S1.I4.i1.I1.i3.p1.1"><span class="ltx_text ltx_font_bold" id="S1.I4.i1.I1.i3.p1.1.1">Output:</span> Generates diagrams and figures in PostScript, commonly used in technical and scientific documents.</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</li>
<li class="ltx_item" id="S1.I4.i1.I1.i4" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item"><span class="ltx_text ltx_font_bold" id="S1.I4.i1.I1.i4.1.1.1">–</span></span>
<div class="ltx_para" id="S1.I4.i1.I1.i4.p1">
<p class="ltx_p" id="S1.I4.i1.I1.i4.p1.1"><span class="ltx_text ltx_font_bold" id="S1.I4.i1.I1.i4.p1.1.1">Specialization:</span> Like Metafont, it is specialized for graphical tasks, particularly line drawings, which complements typographic designs.</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</li>
<li class="ltx_item" id="S1.I4.i1.I1.i5" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item"><span class="ltx_text ltx_font_bold" id="S1.I4.i1.I1.i5.1.1.1">–</span></span>
<div class="ltx_para" id="S1.I4.i1.I1.i5.p1">
<p class="ltx_p" id="S1.I4.i1.I1.i5.p1.1"><span class="ltx_text ltx_font_bold" id="S1.I4.i1.I1.i5.p1.1.1">Flexibility:</span> Can be used to draw shapes, plots, and various illustrations with mathematical precision, often used in academic and research settings.</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</li>
</ul>
</div>
</li>
</ul>
</div>
<div class="ltx_para" id="S1.SS5.SSS2.p5">
<p class="ltx_p" id="S1.SS5.SSS2.p5.1">Both Metafont and MetaPost stand out in the realm of programming languages for their dedicated focus on typography and graphics, respectively. This specialization is rare among programming languages, which are more commonly designed for a broad range of computing tasks. Metafont and MetaPost offer a unique approach to design that is closely aligned with the mathematical precision and programmability required for high-quality typographic and illustrative work.</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
<div class="ltx_para" id="S1.SS5.SSS2.p6">
<p class="ltx_p" id="S1.SS5.SSS2.p6.1">However, to program in Metafont and MetaPost, an understanding of geometry, algebra, and Bézier curves is essential. Knowledge of these mathematical concepts enables users to craft detailed and sophisticated designs by specifying exact mathematical descriptions of the shapes. Metafont and MetaPost scripts often resemble mathematical formulas, which describe the paths and points that make up the characters and graphics.</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
<figure class="ltx_figure" id="S1.F7"><img alt="Refer to caption" class="ltx_graphics ltx_centering ltx_img_landscape" height="272" id="S1.F7.g1" src="./The Cognitive Type Project - Mapping Typography to Cognition_files/METAFONT_Beta.png" width="538">
<figcaption class="ltx_caption ltx_centering"><span class="ltx_tag ltx_tag_figure">Figure 7: </span>The Greek Letter Beta (<math alttext="\beta" class="ltx_Math" display="inline" id="S1.F7.2.m1.1"><semantics id="S1.F7.2.m1.1b"><mi id="S1.F7.2.m1.1.1" xref="S1.F7.2.m1.1.1.cmml">β</mi><annotation-xml encoding="MathML-Content" id="S1.F7.2.m1.1c"><ci id="S1.F7.2.m1.1.1.cmml" xref="S1.F7.2.m1.1.1">𝛽</ci></annotation-xml><annotation encoding="application/x-tex" id="S1.F7.2.m1.1d">\beta</annotation><annotation encoding="application/x-llamapun" id="S1.F7.2.m1.1e">italic_β</annotation></semantics></math>) Programmed in MetaFont</figcaption>
</figure><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
<div class="ltx_para" id="S1.SS5.SSS2.p7">
<p class="ltx_p" id="S1.SS5.SSS2.p7.1">For this reason, the Cognitive Type project uses Metafont and MetaPost to create typographic training sets for generative models but feels it is unlikely to be adopted by typographers or cognitive scientists. Despite the collaboration of well-known type designers like Hermann Zapf with Knuth to create new fonts using Metafont, the system has not been widely adopted by professional type designers since its creation in 1982. Knuth attributes this to the complexity of requiring an artist to become proficient in mathematics to write a font with 60 parameters. Jonathan Hoefler commented that the Metafont system ultimately became ”a technology behind zero of your favorite fonts.” The Cognitive Type project is currently raising money to hire a Metafont and MetaPost programmer that can programmatically create millions of glyphs based on the Abecedarian Classification of Typefaces (Brown, N., 2024) for the training of ”text to type” foundation models.</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</section>
<section class="ltx_subsubsection" id="S1.SS5.SSS3">
<h4 class="ltx_title ltx_title_subsubsection">
<span class="ltx_tag ltx_tag_subsubsection">1.5.3 </span>Hybrid Font Design Tools</h4><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
<div class="ltx_para" id="S1.SS5.SSS3.p1">
<p class="ltx_p" id="S1.SS5.SSS3.p1.1">Web and UI-based systems like Glyphs (Glyphs: Schneider, G., et al., 2024), FontLab (FontLab: FontLab Ltd., 2024), and RoboFont (RoboFont: Van Rossum, F., 2024) offer a graphical user interface for designing typefaces and allow for some level of scripting to extend functionality. These are powerful tools for making changes to typefaces, creating typefaces, and producing small datasets for generative models but still require learning the tools and making changes glyph by glyph.</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
<div class="ltx_para" id="S1.SS5.SSS3.p2">
<p class="ltx_p" id="S1.SS5.SSS3.p2.1"><span class="ltx_text ltx_font_bold" id="S1.SS5.SSS3.p2.1.1">Metapolator:</span></p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
<ul class="ltx_itemize" id="S1.I5">
<li class="ltx_item" id="S1.I5.i1" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span>
<div class="ltx_para" id="S1.I5.i1.p1">
<p class="ltx_p" id="S1.I5.i1.p1.1"><span class="ltx_text ltx_font_bold" id="S1.I5.i1.p1.1.1">Description:</span> An open web tool aimed at streamlining the process of creating multiple fonts. It introduces an innovative approach by enabling work within a font design space, allowing designers to manage and manipulate many fonts simultaneously rather than focusing on individual glyphs or faces.</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</li>
<li class="ltx_item" id="S1.I5.i2" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span>
<div class="ltx_para" id="S1.I5.i2.p1">
<p class="ltx_p" id="S1.I5.i2.p1.1"><span class="ltx_text ltx_font_bold" id="S1.I5.i2.p1.1.1">Features:</span> Supports a broad, project-level view of font design, facilitating rapid experimentation and development of font families.</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</li>
<li class="ltx_item" id="S1.I5.i3" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span>
<div class="ltx_para" id="S1.I5.i3.p1">
<p class="ltx_p" id="S1.I5.i3.p1.1"><span class="ltx_text ltx_font_bold" id="S1.I5.i3.p1.1.1">Platform:</span> Web-based, accessible from any platform with internet access.</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</li>
<li class="ltx_item" id="S1.I5.i4" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span>
<div class="ltx_para" id="S1.I5.i4.p1">
<p class="ltx_p" id="S1.I5.i4.p1.1"><span class="ltx_text ltx_font_bold" id="S1.I5.i4.p1.1.1">Scripting:</span> While primarily UI-driven, the open nature of Metapolator suggests potential for customization and extension by users familiar with web technologies.
</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</li>
<li class="ltx_item" id="S1.I5.i5" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span>
<div class="ltx_para" id="S1.I5.i5.p1">
<p class="ltx_p" id="S1.I5.i5.p1.1"><span class="ltx_text ltx_font_bold" id="S1.I5.i5.p1.1.1">Licensing:</span> The project and its fonts are under the GNU General Public License v3.0 (GPL), encouraging use and extension of the source code.</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</li>
</ul>
</div>
<div class="ltx_para" id="S1.SS5.SSS3.p3">
<p class="ltx_p" id="S1.SS5.SSS3.p3.1"><span class="ltx_text ltx_font_bold" id="S1.SS5.SSS3.p3.1.1">Metaflop:</span></p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
<ul class="ltx_itemize" id="S1.I6">
<li class="ltx_item" id="S1.I6.i1" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span>
<div class="ltx_para" id="S1.I6.i1.p1">
<p class="ltx_p" id="S1.I6.i1.p1.1"><span class="ltx_text ltx_font_bold" id="S1.I6.i1.p1.1.1">Description:</span> An accessible web tool for creating and modifying typefaces based on Metafont principles. It allows users to adjust font parameters through a user-friendly interface, generating unique typefaces.</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</li>
<li class="ltx_item" id="S1.I6.i2" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span>
<div class="ltx_para" id="S1.I6.i2.p1">
<p class="ltx_p" id="S1.I6.i2.p1.1"><span class="ltx_text ltx_font_bold" id="S1.I6.i2.p1.1.1">Features:</span> Provides a modulator interface where users can tweak various aspects of a font’s appearance through sliders and controls, effectively applying Metafont’s parametric design principles.</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</li>
<li class="ltx_item" id="S1.I6.i3" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span>
<div class="ltx_para" id="S1.I6.i3.p1">
<p class="ltx_p" id="S1.I6.i3.p1.1"><span class="ltx_text ltx_font_bold" id="S1.I6.i3.p1.1.1">Platform:</span> Web-based, ensuring wide accessibility without the need for specific operating system compatibility.</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</li>
<li class="ltx_item" id="S1.I6.i4" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span>
<div class="ltx_para" id="S1.I6.i4.p1">
<p class="ltx_p" id="S1.I6.i4.p1.1"><span class="ltx_text ltx_font_bold" id="S1.I6.i4.p1.1.1">Scripting:</span> Leverages Metafont for backend processing, with the UI serving to abstract complex coding tasks into intuitive visual adjustments.</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</li>
<li class="ltx_item" id="S1.I6.i5" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span>
<div class="ltx_para" id="S1.I6.i5.p1">
<p class="ltx_p" id="S1.I6.i5.p1.1"><span class="ltx_text ltx_font_bold" id="S1.I6.i5.p1.1.1">Licensing:</span> Source code and generated fonts are licensed under the GNU General Public License v3.0 (GPL), promoting open use and community contributions.</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</li>
</ul>
</div>
<figure class="ltx_figure" id="S1.F8"><img alt="Refer to caption" class="ltx_graphics ltx_centering ltx_img_landscape" height="393" id="S1.F8.g1" src="./The Cognitive Type Project - Mapping Typography to Cognition_files/Cognitive_Type_Figure_7.png" width="538">
<figcaption class="ltx_caption ltx_centering"><span class="ltx_tag ltx_tag_figure">Figure 8: </span>Hybrid Font Design Tool - Metaflop</figcaption>
</figure><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
<div class="ltx_para" id="S1.SS5.SSS3.p4">
<p class="ltx_p" id="S1.SS5.SSS3.p4.1"><span class="ltx_text ltx_font_bold" id="S1.SS5.SSS3.p4.1.1">Glyphs:</span></p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
<ul class="ltx_itemize" id="S1.I7">
<li class="ltx_item" id="S1.I7.i1" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span>
<div class="ltx_para" id="S1.I7.i1.p1">
<p class="ltx_p" id="S1.I7.i1.p1.1"><span class="ltx_text ltx_font_bold" id="S1.I7.i1.p1.1.1">Description:</span> User-friendly software with a robust set of features for font design, scriptable with Python.</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</li>
<li class="ltx_item" id="S1.I7.i2" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span>
<div class="ltx_para" id="S1.I7.i2.p1">
<p class="ltx_p" id="S1.I7.i2.p1.1"><span class="ltx_text ltx_font_bold" id="S1.I7.i2.p1.1.1">Platform:</span> macOS-specific, requiring purchase.</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</li>
<li class="ltx_item" id="S1.I7.i3" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span>
<div class="ltx_para" id="S1.I7.i3.p1">
<p class="ltx_p" id="S1.I7.i3.p1.1"><span class="ltx_text ltx_font_bold" id="S1.I7.i3.p1.1.1">Features:</span> Offers a good balance for both beginners and professionals with its intuitive design and scripting capabilities.</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</li>
</ul>
</div>
<div class="ltx_para" id="S1.SS5.SSS3.p5">
<p class="ltx_p" id="S1.SS5.SSS3.p5.1"><span class="ltx_text ltx_font_bold" id="S1.SS5.SSS3.p5.1.1">FontLab:</span></p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
<ul class="ltx_itemize" id="S1.I8">
<li class="ltx_item" id="S1.I8.i1" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span>
<div class="ltx_para" id="S1.I8.i1.p1">
<p class="ltx_p" id="S1.I8.i1.p1.1"><span class="ltx_text ltx_font_bold" id="S1.I8.i1.p1.1.1">Description:</span> Professional software providing an extensive toolkit for crafting and refining typefaces.</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</li>
<li class="ltx_item" id="S1.I8.i2" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span>
<div class="ltx_para" id="S1.I8.i2.p1">
<p class="ltx_p" id="S1.I8.i2.p1.1"><span class="ltx_text ltx_font_bold" id="S1.I8.i2.p1.1.1">Platform:</span> Proprietary, with a cost associated with its use.</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</li>
<li class="ltx_item" id="S1.I8.i3" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span>
<div class="ltx_para" id="S1.I8.i3.p1">
<p class="ltx_p" id="S1.I8.i3.p1.1"><span class="ltx_text ltx_font_bold" id="S1.I8.i3.p1.1.1">Features:</span> Generates production-ready fonts and allows Python scripting for advanced customization.</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</li>
</ul>
</div>
<div class="ltx_para" id="S1.SS5.SSS3.p6">
<p class="ltx_p" id="S1.SS5.SSS3.p6.1"><span class="ltx_text ltx_font_bold" id="S1.SS5.SSS3.p6.1.1">RoboFont:</span></p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
<ul class="ltx_itemize" id="S1.I9">
<li class="ltx_item" id="S1.I9.i1" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span>
<div class="ltx_para" id="S1.I9.i1.p1">
<p class="ltx_p" id="S1.I9.i1.p1.1"><span class="ltx_text ltx_font_bold" id="S1.I9.i1.p1.1.1">Description:</span> Provides a highly customizable interface for designing glyphs, with Python scripting for extensive functionality.</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</li>
<li class="ltx_item" id="S1.I9.i2" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span>
<div class="ltx_para" id="S1.I9.i2.p1">
<p class="ltx_p" id="S1.I9.i2.p1.1"><span class="ltx_text ltx_font_bold" id="S1.I9.i2.p1.1.1">Platform:</span> macOS exclusive, designed to fit into a modular design workflow.</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</li>
<li class="ltx_item" id="S1.I9.i3" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span>
<div class="ltx_para" id="S1.I9.i3.p1">
<p class="ltx_p" id="S1.I9.i3.p1.1"><span class="ltx_text ltx_font_bold" id="S1.I9.i3.p1.1.1">Features:</span> Its clean UI and scripting capabilities make it versatile, though it may present a learning curve for non-coders.</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</li>
</ul>
</div>
<div class="ltx_para" id="S1.SS5.SSS3.p7">
<p class="ltx_p" id="S1.SS5.SSS3.p7.1">These tools collectively represent a spectrum of options for typeface design, from web-based applications that democratize the design process to professional-grade software offering deep customization and precision. Each has its unique strengths, catering to different needs within the typographic community.</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</section>
<section class="ltx_subsubsection" id="S1.SS5.SSS4">
<h4 class="ltx_title ltx_title_subsubsection">
<span class="ltx_tag ltx_tag_subsubsection">1.5.4 </span>Variable Fonts</h4><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
<div class="ltx_para" id="S1.SS5.SSS4.p1">
<p class="ltx_p" id="S1.SS5.SSS4.p1.1">Variable fonts (Variable Fonts, 2024), also known as OpenType Font Variations, represent a significant advancement in font technology by allowing the customization of a font’s appearance along multiple axes of variation. This flexibility means that instead of being restricted to a set number of pre-designed font weights, widths, and styles, users can fine-tune a font’s characteristics to meet their specific needs. This capability not only enhances creative freedom but also optimizes efficiency, particularly in web typography, by consolidating multiple font variations into a single file, thus reducing overall file size.</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
<div class="ltx_para" id="S1.SS5.SSS4.p2">
<p class="ltx_p" id="S1.SS5.SSS4.p2.1"><span class="ltx_text ltx_font_bold" id="S1.SS5.SSS4.p2.1.1">Common Axes of Variation in Variable Fonts:</span></p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
<ul class="ltx_itemize" id="S1.I10">
<li class="ltx_item" id="S1.I10.i1" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span>
<div class="ltx_para" id="S1.I10.i1.p1">
<p class="ltx_p" id="S1.I10.i1.p1.1"><span class="ltx_text ltx_font_bold" id="S1.I10.i1.p1.1.1">Weight (wght):</span> Controls the thickness of the strokes, ranging from thin to black. This axis allows for fine-tuning between light and bold appearances.</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</li>
<li class="ltx_item" id="S1.I10.i2" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span>
<div class="ltx_para" id="S1.I10.i2.p1">
<p class="ltx_p" id="S1.I10.i2.p1.1"><span class="ltx_text ltx_font_bold" id="S1.I10.i2.p1.1.1">Width (wdth):</span> Adjusts the overall width of the font characters, from condensed to expanded, affecting the text’s occupancy on a page or screen.</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</li>
<li class="ltx_item" id="S1.I10.i3" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span>
<div class="ltx_para" id="S1.I10.i3.p1">
<p class="ltx_p" id="S1.I10.i3.p1.1"><span class="ltx_text ltx_font_bold" id="S1.I10.i3.p1.1.1">Slant (slnt):</span> Modifies the angle of the font, simulating italic styles without needing a separate italic font file. This axis tilts the letters to the right but differs from true italics in that it doesn’t change the letterforms’ design.</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</li>
<li class="ltx_item" id="S1.I10.i4" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span>
<div class="ltx_para" id="S1.I10.i4.p1">
<p class="ltx_p" id="S1.I10.i4.p1.1"><span class="ltx_text ltx_font_bold" id="S1.I10.i4.p1.1.1">Italic (ital):</span> Enables a switch between upright and italic styles. Unlike slant, this axis can trigger a change to true italic letterforms if the font supports it.</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</li>
<li class="ltx_item" id="S1.I10.i5" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span>
<div class="ltx_para" id="S1.I10.i5.p1">
<p class="ltx_p" id="S1.I10.i5.p1.1"><span class="ltx_text ltx_font_bold" id="S1.I10.i5.p1.1.1">Optical Size (opsz):</span> Adjusts the font’s appearance for different text sizes, optimizing legibility across a range of sizes by altering character spacing, weight, and other details.</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</li>
<li class="ltx_item" id="S1.I10.i6" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span>
<div class="ltx_para" id="S1.I10.i6.p1">
<p class="ltx_p" id="S1.I10.i6.p1.1"><span class="ltx_text ltx_font_bold" id="S1.I10.i6.p1.1.1">X-Height (xhgt):</span> Influences the height of lowercase letters relative to the font’s overall size, affecting legibility and the visual density of text.</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</li>
</ul>
</div>
<div class="ltx_para" id="S1.SS5.SSS4.p3">
<p class="ltx_p" id="S1.SS5.SSS4.p3.1">These axes can be combined within a single variable font file, offering unprecedented control over typography with the potential for additional custom axes defined by type designers. The introduction of variable fonts thus marks a trans formative shift in the way fonts are used and managed, particularly in digital contexts where flexibility and efficiency are paramount.</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
<div class="ltx_para" id="S1.SS5.SSS4.p4">
<p class="ltx_p" id="S1.SS5.SSS4.p4.1">Variable fonts or OpenType Font Variations offer an innovative approach to typography by allowing designers and developers to adjust font characteristics dynamically through CSS. Here’s how the primary axes of variation in variable fonts are manipulated using CSS:</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
<div class="ltx_para" id="S1.SS5.SSS4.p5">
<ul class="ltx_itemize" id="S1.I11">
<li class="ltx_item" id="S1.I11.i1" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span>
<div class="ltx_para" id="S1.I11.i1.p1">
<p class="ltx_p" id="S1.I11.i1.p1.1"><span class="ltx_text ltx_font_bold" id="S1.I11.i1.p1.1.1">Weight (wght)</span></p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
<ul class="ltx_itemize" id="S1.I11.i1.I1">
<li class="ltx_item" id="S1.I11.i1.I1.i1" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item"><span class="ltx_text ltx_font_bold" id="S1.I11.i1.I1.i1.1.1.1">–</span></span>
<div class="ltx_para" id="S1.I11.i1.I1.i1.p1">
<p class="ltx_p" id="S1.I11.i1.I1.i1.p1.1"><span class="ltx_text ltx_font_bold" id="S1.I11.i1.I1.i1.p1.1.1">CSS Attribute:</span> <span class="ltx_text ltx_font_typewriter" id="S1.I11.i1.I1.i1.p1.1.2">font-weight</span></p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</li>
<li class="ltx_item" id="S1.I11.i1.I1.i2" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item"><span class="ltx_text ltx_font_bold" id="S1.I11.i1.I1.i2.1.1.1">–</span></span>
<div class="ltx_para" id="S1.I11.i1.I1.i2.p1">
<p class="ltx_p" id="S1.I11.i1.I1.i2.p1.1"><span class="ltx_text ltx_font_bold" id="S1.I11.i1.I1.i2.p1.1.1">Description:</span> Controls the thickness of the font strokes, offering a continuous range from light to bold. Instead of limited options like ”normal” or ”bold,” any value within the font’s weight range can be specified.</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</li>
</ul>
</div>
</li>
</ul>
</div>
<figure class="ltx_figure" id="S1.F9"><img alt="Refer to caption" class="ltx_graphics ltx_centering ltx_img_landscape" height="117" id="S1.F9.g1" src="./The Cognitive Type Project - Mapping Typography to Cognition_files/Variable_Fonts_weight.png" width="538">
<figcaption class="ltx_caption ltx_centering"><span class="ltx_tag ltx_tag_figure">Figure 9: </span>Variable Fonts Axes of Variation - Weight (wght)</figcaption>
</figure><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
<div class="ltx_para" id="S1.SS5.SSS4.p6">
<ul class="ltx_itemize" id="S1.I12">
<li class="ltx_item" id="S1.I12.i1" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span>
<div class="ltx_para" id="S1.I12.i1.p1">
<p class="ltx_p" id="S1.I12.i1.p1.1"><span class="ltx_text ltx_font_bold" id="S1.I12.i1.p1.1.1">Slant (slnt)</span></p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
<ul class="ltx_itemize" id="S1.I12.i1.I1">
<li class="ltx_item" id="S1.I12.i1.I1.i1" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item"><span class="ltx_text ltx_font_bold" id="S1.I12.i1.I1.i1.1.1.1">–</span></span>
<div class="ltx_para" id="S1.I12.i1.I1.i1.p1">
<p class="ltx_p" id="S1.I12.i1.I1.i1.p1.1"><span class="ltx_text ltx_font_bold" id="S1.I12.i1.I1.i1.p1.1.1">CSS Attribute:</span> <span class="ltx_text ltx_font_typewriter" id="S1.I12.i1.I1.i1.p1.1.2">font-style</span> for oblique styles, <span class="ltx_text ltx_font_typewriter" id="S1.I12.i1.I1.i1.p1.1.3">font-variation-settings</span> for specific slant angles.</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</li>
<li class="ltx_item" id="S1.I12.i1.I1.i2" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item"><span class="ltx_text ltx_font_bold" id="S1.I12.i1.I1.i2.1.1.1">–</span></span>
<div class="ltx_para" id="S1.I12.i1.I1.i2.p1">
<p class="ltx_p" id="S1.I12.i1.I1.i2.p1.1"><span class="ltx_text ltx_font_bold" id="S1.I12.i1.I1.i2.p1.1.1">Description:</span> Provides a degree of slant to the font, without changing to italic letterforms. Useful for a subtle emphasis or stylistic choice.</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</li>
</ul>
</div>
</li>
</ul>
</div>
<figure class="ltx_figure" id="S1.F10"><img alt="Refer to caption" class="ltx_graphics ltx_centering ltx_img_landscape" height="117" id="S1.F10.g1" src="./The Cognitive Type Project - Mapping Typography to Cognition_files/Variable_Fonts_Slant.png" width="538">
<figcaption class="ltx_caption ltx_centering"><span class="ltx_tag ltx_tag_figure">Figure 10: </span>Variable Fonts Axes of Variation - Slant (slnt)</figcaption>
</figure><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
<div class="ltx_para" id="S1.SS5.SSS4.p7">
<p class="ltx_p" id="S1.SS5.SSS4.p7.1">Variable fonts are a powerful movement in typography, suited for creating font families through control of existing weight and slant parameters like (wght, wdth, slnt, ital, opsz). Adjusting the existing standard axes like weight (wght), width (wdth), slant (slnt), etc., can be done through parameters in CSS by anyone with basic knowledge of web development and design. These predefined axes are part of the OpenType specification and are included by the font designer within the variable font file.</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
<div class="ltx_para" id="S1.SS5.SSS4.p8">
<p class="ltx_p" id="S1.SS5.SSS4.p8.1">Defining a custom axis involves not only programming knowledge but also a deep understanding of typography and typeface design. It is a more advanced task that usually requires an experienced typographer or typeface designer. Creating a custom axis involves defining what the axis will control, designing the typeface variations that correspond to different values along the axis, and correctly implementing these variations within the font file itself. This process involves using font creation software such as Glyphs, FontLab, or RoboFont, which allows the designer to draw, interpolate, and test custom variations, extending beyond simple parameter adjustments into the realm of creative and technical typeface design.</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</section>
<section class="ltx_subsubsection" id="S1.SS5.SSS5">
<h4 class="ltx_title ltx_title_subsubsection">
<span class="ltx_tag ltx_tag_subsubsection">1.5.5 </span>Generative Models and Deep Learning</h4><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
<div class="ltx_para" id="S1.SS5.SSS5.p1">
<p class="ltx_p" id="S1.SS5.SSS5.p1.1">Neural Networks, particularly disentangled <math alttext="\beta" class="ltx_Math" display="inline" id="S1.SS5.SSS5.p1.1.m1.1"><semantics id="S1.SS5.SSS5.p1.1.m1.1a"><mi id="S1.SS5.SSS5.p1.1.m1.1.1" xref="S1.SS5.SSS5.p1.1.m1.1.1.cmml">β</mi><annotation-xml encoding="MathML-Content" id="S1.SS5.SSS5.p1.1.m1.1b"><ci id="S1.SS5.SSS5.p1.1.m1.1.1.cmml" xref="S1.SS5.SSS5.p1.1.m1.1.1">𝛽</ci></annotation-xml><annotation encoding="application/x-tex" id="S1.SS5.SSS5.p1.1.m1.1c">\beta</annotation><annotation encoding="application/x-llamapun" id="S1.SS5.SSS5.p1.1.m1.1d">italic_β</annotation></semantics></math>-VAEs, can be used to identify latent features representing typeface letterforms, allowing for the potential discovery of new attributes for type classification (Issak et al., 2023). Our work in this area emphasizes that mapping the learned features of a model can reverse current heuristics and provide typographers with a new perspective on font classification. However, these models are sensitive to model structure, and much more needs to be done in this area to use this approach to extend existing type classification systems.</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
<div class="ltx_para" id="S1.SS5.SSS5.p2">
<p class="ltx_p" id="S1.SS5.SSS5.p2.1">Our work using simple generative models showed that one can create a dataset of glyphs similar to those in Google Fonts (Magre, N., &amp; Brown, N., 2022). This ”TMINST” was composed of 565,292 MNIST-style grayscale images representing 1,812 unique glyphs across various styles of 1,355 Google fonts. While we can create many high-quality glyphs, we don’t have the prompting control of ”text to image” foundational models like DALL·E and Stable Diffusion. Our belief is that while the approaches listed above are critical to training a ”text to type” foundational model, the creation of such a model would allow anyone, including non-programmers and non-typographers, to create precise and detailed glyphs for the design of typefaces. In particular, to design ”Cognitive Type” to be used by scientists to assess how differences in type affect cognition.</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</section>
</section>
<section class="ltx_subsection" id="S1.SS6">
<h3 class="ltx_title ltx_title_subsection">
<span class="ltx_tag ltx_tag_subsection">1.6 </span>”Text to Type” Foundational Models</h3><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
<div class="ltx_para" id="S1.SS6.p1">
<p class="ltx_p" id="S1.SS6.p1.1">The development of a ”Text to Type” foundational model is set to significantly impact typographic design, especially for the Cognitive Type project. This initiative strives to bridge the gap between the generative capabilities of current text-to-image models and the intricate demands of typography. Although present models can produce glyphs, they often lack the sophistication to comprehend typographic terms fully, which impedes the creation of ”Cognitive Type” or professional font families with the necessary detail and consistency.</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
<div class="ltx_para" id="S1.SS6.p2">
<p class="ltx_p" id="S1.SS6.p2.1">Such a model would not only understand typographic terminology (see Figure 11) but also apply it according to type design principles. It would enable the creation of typefaces with specific attributes—such as weight, width, slant, and x-height—by interpreting descriptive text inputs. Examples include:
</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
<div class="ltx_para" id="S1.SS6.p3">
<ul class="ltx_itemize" id="S1.I13">
<li class="ltx_item" id="S1.I13.i1" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span>
<div class="ltx_para" id="S1.I13.i1.p1">
<p class="ltx_p" id="S1.I13.i1.p1.1">Create a serif ’a’ with a single-story structure and closed aperture.</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</li>
<li class="ltx_item" id="S1.I13.i2" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span>
<div class="ltx_para" id="S1.I13.i2.p1">
<p class="ltx_p" id="S1.I13.i2.p1.1">Design a slab serif ’g’ with low stroke contrast and square terminals.</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</li>
<li class="ltx_item" id="S1.I13.i3" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span>
<div class="ltx_para" id="S1.I13.i3.p1">
<p class="ltx_p" id="S1.I13.i3.p1.1">Produce a humanist ’E’ with open apertures and a double-story structure.</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</li>
<li class="ltx_item" id="S1.I13.i4" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span>
<div class="ltx_para" id="S1.I13.i4.p1">
<p class="ltx_p" id="S1.I13.i4.p1.1">Designing a lowercase ’a’ with a slightly flared entry stroke and a pronounced curve at the top, suggestive of handwriting.</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</li>
<li class="ltx_item" id="S1.I13.i5" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span>
<div class="ltx_para" id="S1.I13.i5.p1">
<p class="ltx_p" id="S1.I13.i5.p1.1">Creating a Cyrillic character set that harmonizes visually with existing Latin characters, using diagonal stress and similar stroke weights.</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</li>
<li class="ltx_item" id="S1.I13.i6" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span>
<div class="ltx_para" id="S1.I13.i6.p1">
<p class="ltx_p" id="S1.I13.i6.p1.1">Designing a numeral ’4’ with a closed counter for better legibility at smaller sizes.</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</li>
<li class="ltx_item" id="S1.I13.i7" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span>
<div class="ltx_para" id="S1.I13.i7.p1">
<p class="ltx_p" id="S1.I13.i7.p1.1">Generating swash characters for uppercase ’A’ and ’E’ that add decorative touches while preserving legibility.</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</li>
</ul>
</div>
<figure class="ltx_figure" id="S1.F11"><img alt="Refer to caption" class="ltx_graphics ltx_centering ltx_img_square" height="527" id="S1.F11.g1" src="./The Cognitive Type Project - Mapping Typography to Cognition_files/Cognitive_Type_Figure_11.png" width="568">
<figcaption class="ltx_caption ltx_centering"><span class="ltx_tag ltx_tag_figure">Figure 11: </span>Training a Neural Network to Understand Typographic Terms</figcaption>
</figure><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
<div class="ltx_para" id="S1.SS6.p4">
<p class="ltx_p" id="S1.SS6.p4.1">A ”Text to Type” model could revolutionize typeface creation, making it more accessible to non-experts and opening new design possibilities. For the Cognitive Type project, it offers a chance to quickly prototype and test typefaces optimized for readability, legibility, and cognitive impact.</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
<div class="ltx_para" id="S1.SS6.p5">
<p class="ltx_p" id="S1.SS6.p5.1">The importance of a ”Text to Type” model also extends to cognitive science, allowing for the systematic study of how typographic variations affect reading speed, comprehension, and aesthetic preference. This could lead to advances in visual cognition and the creation of typefaces tailored to specific audiences or conditions, such as dyslexia or low vision.</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
<div class="ltx_para" id="S1.SS6.p6">
<p class="ltx_p" id="S1.SS6.p6.1">Additionally, this model would address the labor-intensive nature of typeface creation and refinement. Automating parts of the design process would greatly reduce the time and expertise needed to develop new fonts, democratizing type design and allowing a wider range of creators to contribute. This aligns with the Cognitive Type project’s goals to use technology to push the boundaries of typographic innovation and application.</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
<div class="ltx_para" id="S1.SS6.p7">
<p class="ltx_p" id="S1.SS6.p7.1">In conclusion, creating a ”Text to Type” foundational model is crucial for the advancement of the Cognitive Type project. It is set to bring unprecedented efficiency, accessibility, and scientific rigor to typeface design, fostering new creative and research opportunities. By combining the powers of current generative technologies with the specific needs of typography, this model has the potential to spur a new era of innovation in the field.</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</section>
<section class="ltx_subsection" id="S1.SS7">
<h3 class="ltx_title ltx_title_subsection">
<span class="ltx_tag ltx_tag_subsection">1.7 </span>Summary</h3><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
<div class="ltx_para" id="S1.SS7.p1">
<p class="ltx_p" id="S1.SS7.p1.1">The Cognitive Type Project delves into the development of computational tools to enable the creation of typefaces with varied cognitive properties. This ambitious initiative seeks to enhance typographers’ ability to design fonts that not only improve user engagement and reading comprehension across various media but also cater to specific needs such as dyslexia-friendly typefaces. A crucial aspect of this research lies in the challenge of generating a vast array of typefaces with subtle differences, a task that demands both significant labor and the expertise of seasoned typographers. The project aims to bridge the gap in existing research by focusing on how the design and layout of text influence readability, aesthetic appeal, and memorability, factors that are essential for effective communication.</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
<div class="ltx_para" id="S1.SS7.p2">
<p class="ltx_p" id="S1.SS7.p2.1">To achieve its goals, the project is developing publicly accessible datasets and foundational models that integrate the detailed anatomy of type with eye-tracking data, thus offering new insights into the physical and cognitive impacts of typography. Utilizing tools like Metafont, Variable Fonts, and generative models, the team is exploring innovative ways to create cognitively relevant glyphs and understand the typographic latent space. A pivotal element of their approach involves constructing an open-source text-to-type model inspired by AI systems like Midjourney and DALL·E, which would allow for the specification of visual characteristics of fonts for use in cognitive studies and typography software.</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
<div class="ltx_para" id="S1.SS7.p3">
<p class="ltx_p" id="S1.SS7.p3.1">The Cognitive Type Project underscores the importance of typography in learning and information acquisition, highlighting the influence of font design on reading efficiency and comprehension. By employing techniques such as eye tracking, reading speed tests, and neuroimaging, researchers aim to comprehensively understand how textual characteristics impact cognitive processes. This multidisciplinary approach not only promises to enhance the design flexibility and accessibility of digital products but also supports the creation of ”Cognitive Type” for scientific evaluation of typographic effects on cognition.</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
<div class="ltx_para" id="S1.SS7.p4">
<p class="ltx_p" id="S1.SS7.p4.1">However, the endeavor faces challenges, notably in the creation of new typefaces, as current text-to-image models lack the nuanced understanding of typography required for this task. The project advocates for the development of a ”Text to Type” foundational model, which could revolutionize typeface design by making it accessible to a broader audience, including those without programming or typographic expertise. This model would facilitate the design of typefaces with precise cognitive objectives, contributing significantly to the fields of typography and cognitive science. In essence, the Cognitive Type Project is at the forefront of merging technological innovation with typographic design to explore how typography can optimize cognitive outcomes and information retention.
</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</section>
<section class="ltx_subsection" id="S1.SS8">
<h3 class="ltx_title ltx_title_subsection">
<span class="ltx_tag ltx_tag_subsection">1.8 </span>References</h3><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
<div class="ltx_para" id="S1.SS8.p1">
<ol class="ltx_enumerate" id="S1.I14">
<li class="ltx_item" id="S1.I14.i1" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">1.</span>
<div class="ltx_para" id="S1.I14.i1.p1">
<p class="ltx_p" id="S1.I14.i1.p1.1">Beier, S., and Larson, K. (2013). How does typeface familiarity affect reading performance and reader preference? <span class="ltx_text ltx_font_italic" id="S1.I14.i1.p1.1.1">Inf. Design J.</span>, 20, 16–31. <a class="ltx_ref ltx_href" href="https://doi.org/10.1075/idj.20.1.02bei" title="">doi: 10.1075/idj.20.1.02bei</a></p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</li>
<li class="ltx_item" id="S1.I14.i2" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">2.</span>
<div class="ltx_para" id="S1.I14.i2.p1">
<p class="ltx_p" id="S1.I14.i2.p1.1">Beier, S., Sand, K., and Starrfelt, R. (2017). Legibility implications of embellished display typefaces. <span class="ltx_text ltx_font_italic" id="S1.I14.i2.p1.1.1">Visible Lang.</span>, 51, 112–133.</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</li>
<li class="ltx_item" id="S1.I14.i3" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">3.</span>
<div class="ltx_para" id="S1.I14.i3.p1">
<p class="ltx_p" id="S1.I14.i3.p1.1">Bessemans, A. (2016a). Typefaces for children’s reading. <span class="ltx_text ltx_font_italic" id="S1.I14.i3.p1.1.1">TMG J. Media Hist.</span>, 19, 1–9. <a class="ltx_ref ltx_href" href="https://doi.org/10.18146/2213-7653.2016.268" title="">doi: 10.18146/2213-7653.2016.268</a></p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</li>
<li class="ltx_item" id="S1.I14.i4" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">4.</span>
<div class="ltx_para" id="S1.I14.i4.p1">
<p class="ltx_p" id="S1.I14.i4.p1.1">Bessemans, A. (2016b). Matilda: a typeface for children with low vision. <span class="ltx_text ltx_font_italic" id="S1.I14.i4.p1.1.1">Digit. Fonts Reading 2016</span>, 8–34. <a class="ltx_ref ltx_href" href="https://doi.org/10.1142/9789814759540_0002" title="">doi: 10.1142/9789814759540_0002</a></p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</li>
<li class="ltx_item" id="S1.I14.i5" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">5.</span>
<div class="ltx_para" id="S1.I14.i5.p1">
<p class="ltx_p" id="S1.I14.i5.p1.1">Bigelow, C. (2019). Typeface features and legibility research. <span class="ltx_text ltx_font_italic" id="S1.I14.i5.p1.1.1">Vis. Res.</span>, 165, 162–172. <a class="ltx_ref ltx_href" href="https://doi.org/10.1016/j.visres.2019.05.003" title="">doi: 10.1016/j.visres.2019.05.003</a></p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</li>
<li class="ltx_item" id="S1.I14.i6" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">6.</span>
<div class="ltx_para" id="S1.I14.i6.p1">
<p class="ltx_p" id="S1.I14.i6.p1.1">Brath, R., and Banissi, E. (2016). Using typography to expand the design space of data visualization. <span class="ltx_text ltx_font_italic" id="S1.I14.i6.p1.1.1">J Design Econ. Innov.</span>, 2, 59–87. <a class="ltx_ref ltx_href" href="https://doi.org/10.1016/j.sheji.2016.05.003" title="">doi: 10.1016/j.sheji.2016.05.003</a></p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</li>
<li class="ltx_item" id="S1.I14.i7" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">7.</span>
<div class="ltx_para" id="S1.I14.i7.p1">
<p class="ltx_p" id="S1.I14.i7.p1.1">Brown, N. (2024a). The Cognitive Type Project - Mapping Typography to Cognition. Retrieved from <a class="ltx_ref ltx_url ltx_font_typewriter" href="https://github.com/nikbearbrown/CognitiveType/tree/main/Papers/The_Cognitive_Type_Project_Mapping_Typography_to_Cognition" title="">https://github.com/nikbearbrown/CognitiveType/tree/main/Papers/The_Cognitive_Type_Project_Mapping_Typography_to_Cognition</a></p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</li>
<li class="ltx_item" id="S1.I14.i8" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">8.</span>
<div class="ltx_para" id="S1.I14.i8.p1">
<p class="ltx_p" id="S1.I14.i8.p1.1">Brown, N. (2024b). The Abecedarian Classification of Type. Retrieved from <a class="ltx_ref ltx_url ltx_font_typewriter" href="https://github.com/nikbearbrown/CognitiveType/tree/main/Papers/The_Abecedarian_Classification_of_Type" title="">https://github.com/nikbearbrown/CognitiveType/tree/main/Papers/The_Abecedarian_Classification_of_Type</a></p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</li>
<li class="ltx_item" id="S1.I14.i9" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">9.</span>
<div class="ltx_para" id="S1.I14.i9.p1">
<p class="ltx_p" id="S1.I14.i9.p1.1">Brown, N. (2024c). The Abecedarian Visual Typographic Lexicon. Retrieved from <a class="ltx_ref ltx_url ltx_font_typewriter" href="https://github.com/nikbearbrown/CognitiveType/tree/main/Papers/The_Abecedarian_Visual_Typographic_Lexicon" title="">https://github.com/nikbearbrown/CognitiveType/tree/main/Papers/The_Abecedarian_Visual_Typographic_Lexicon</a></p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</li>
<li class="ltx_item" id="S1.I14.i10" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">10.</span>
<div class="ltx_para" id="S1.I14.i10.p1">
<p class="ltx_p" id="S1.I14.i10.p1.1">Brown, N. (2024d). Cognitive Type Project. Retrieved from <a class="ltx_ref ltx_url ltx_font_typewriter" href="https://github.com/nikbearbrown/CognitiveType/" title="">https://github.com/nikbearbrown/CognitiveType/</a></p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</li>
<li class="ltx_item" id="S1.I14.i11" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">11.</span>
<div class="ltx_para" id="S1.I14.i11.p1">
<p class="ltx_p" id="S1.I14.i11.p1.1">Cinder: The Cinder Project Team. (2024) Cinder [Software]. Available from <a class="ltx_ref ltx_url ltx_font_typewriter" href="https://libcinder.org/" title="">https://libcinder.org/</a></p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</li>
<li class="ltx_item" id="S1.I14.i12" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">12.</span>
<div class="ltx_para" id="S1.I14.i12.p1">
<p class="ltx_p" id="S1.I14.i12.p1.1">Dalmaijer, E.S., Mathôt, S., &amp; Van der Stigchel, S. (2014). PyGaze: an open-source, cross-platform toolbox for minimal-effort programming of eye tracking experiments. <span class="ltx_text ltx_font_italic" id="S1.I14.i12.p1.1.1">Behavior Research Methods</span>, 46, 913-921. <a class="ltx_ref ltx_href" href="https://doi.org/10.3758/s13428-013-0422-2" title="">doi:10.3758/s13428-013-0422-2</a>.</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</li>
<li class="ltx_item" id="S1.I14.i13" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">13.</span>
<div class="ltx_para" id="S1.I14.i13.p1">
<p class="ltx_p" id="S1.I14.i13.p1.1">Dressler, E. (2019). Understanding the Effect of Font Type on Reading Comprehension/Memory Under Time-Constrains. Omaha: University of Nebraska at Omaha.</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</li>
<li class="ltx_item" id="S1.I14.i14" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">14.</span>
<div class="ltx_para" id="S1.I14.i14.p1">
<p class="ltx_p" id="S1.I14.i14.p1.1">FontLab: FontLab Ltd. (2024) FontLab [Software]. Available from <a class="ltx_ref ltx_url ltx_font_typewriter" href="https://www.fontlab.com/" title="">https://www.fontlab.com/</a></p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</li>
<li class="ltx_item" id="S1.I14.i15" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">15.</span>
<div class="ltx_para" id="S1.I14.i15.p1">
<p class="ltx_p" id="S1.I14.i15.p1.1">French, M. M. J.; Blood, A.; Bright, N. D.; Futak, D.; Grohmann, M. J.; Hasthorpe, A.; Heritage, J.; Poland, R. L.; Reece, S.; &amp; Tabor, J. (2013). Changing fonts in education: How the benefits vary with ability and dyslexia. <span class="ltx_text ltx_font_italic" id="S1.I14.i15.p1.1.1">The Journal of Educational Research</span>, 106(4), 301-304. <a class="ltx_ref ltx_href" href="https://doi.org/10.1080/00220671.2012.736430" title="">doi: 10.1080/00220671.2012.736430</a>.</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</li>
<li class="ltx_item" id="S1.I14.i16" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">16.</span>
<div class="ltx_para" id="S1.I14.i16.p1">
<p class="ltx_p" id="S1.I14.i16.p1.1">Gasser, M.; Boeke, J.; Haffernan, M.; Tan, R. (2005). The influence of font type on information recall. <span class="ltx_text ltx_font_italic" id="S1.I14.i16.p1.1.1">North American Journal of Psychology</span>, 7(2), 181-188.</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</li>
<li class="ltx_item" id="S1.I14.i17" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">17.</span>
<div class="ltx_para" id="S1.I14.i17.p1">
<p class="ltx_p" id="S1.I14.i17.p1.1">Gasser, M., Haffeman, J. B. M., and Tan, R. (2005). The influence of font type on information recall. <span class="ltx_text ltx_font_italic" id="S1.I14.i17.p1.1.1">N. Am. J. Psychol.</span>, 7, 181–188.</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</li>
<li class="ltx_item" id="S1.I14.i18" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">18.</span>
<div class="ltx_para" id="S1.I14.i18.p1">
<p class="ltx_p" id="S1.I14.i18.p1.1">Glyphs: Schneider, G., &amp; Seifert, E. (2024) Glyphs [Software]. Available from <a class="ltx_ref ltx_url ltx_font_typewriter" href="https://glyphsapp.com/" title="">https://glyphsapp.com/</a></p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</li>
<li class="ltx_item" id="S1.I14.i19" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">19.</span>
<div class="ltx_para" id="S1.I14.i19.p1">
<p class="ltx_p" id="S1.I14.i19.p1.1">Haralambous, Yannis. (2007). Fonts &amp; Encodings. O’Reilly Press. ASIN: 0596102429.
</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</li>
<li class="ltx_item" id="S1.I14.i20" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">20.</span>
<div class="ltx_para" id="S1.I14.i20.p1">
<p class="ltx_p" id="S1.I14.i20.p1.1">Issak, A. A., Kakkar, S., Goetz, S., Brown, N. B., &amp; Harteveld, C. (2023, May). First TinyPapers track at The Eleventh International Conference on Learning Representations (ICLR). Kigali, Rwanda.</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</li>
<li class="ltx_item" id="S1.I14.i21" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">21.</span>
<div class="ltx_para" id="S1.I14.i21.p1">
<p class="ltx_p" id="S1.I14.i21.p1.1">Kanfer, R. &amp; Ackerman, P. L. (1989). Motivation and cognitive abilities: An integrative/aptitude-treatment interaction approach to skill acquisition. <span class="ltx_text ltx_font_italic" id="S1.I14.i21.p1.1.1">Journal of Applied Psychology</span>, 74, 657-690.</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</li>
<li class="ltx_item" id="S1.I14.i22" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">22.</span>
<div class="ltx_para" id="S1.I14.i22.p1">
<p class="ltx_p" id="S1.I14.i22.p1.1">Krafka K, Khosla A, Kellnhofer P, Kannan H, Bhandarkar S, Matusik W, &amp; Torralba A. (2016). Eye Tracking for Everyone. IEEE Conference on Computer Vision and Pattern Recognition (CVPR).</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</li>
<li class="ltx_item" id="S1.I14.i23" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">23.</span>
<div class="ltx_para" id="S1.I14.i23.p1">
<p class="ltx_p" id="S1.I14.i23.p1.1">Larson, K., and Picard, R. (2005). The Aesthetics of Reading. Available at: <a class="ltx_ref ltx_url ltx_font_typewriter" href="https://affect.media.mit.edu/pdfs/05.larson-picard.pdf" title="">https://affect.media.mit.edu/pdfs/05.larson-picard.pdf</a> (Accessed June 6, 2022).</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</li>
<li class="ltx_item" id="S1.I14.i24" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">24.</span>
<div class="ltx_para" id="S1.I14.i24.p1">
<p class="ltx_p" id="S1.I14.i24.p1.1">Larson, K., Hazlett, R. L., Chaparro, B. S., and Picard, R. W. (2006). Measuring the Aesthetics of Reading. Proceedings of HCI, People and Computers XX–Engage, 41–56.</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</li>
<li class="ltx_item" id="S1.I14.i25" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">25.</span>
<div class="ltx_para" id="S1.I14.i25.p1">
<p class="ltx_p" id="S1.I14.i25.p1.1">Lewis, C., and Walker, P. (1989). Typographic influences on reading. <span class="ltx_text ltx_font_italic" id="S1.I14.i25.p1.1.1">Br. J. Psychol.</span>, 80, 241–257. <a class="ltx_ref ltx_href" href="https://doi.org/10.1111/j.2044-8295.1989.tb02317.x" title="">doi: 10.1111/j.2044-8295.1989.tb02317.x</a></p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</li>
<li class="ltx_item" id="S1.I14.i26" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">26.</span>
<div class="ltx_para" id="S1.I14.i26.p1">
<p class="ltx_p" id="S1.I14.i26.p1.1">Magre, N., &amp; Brown, N. (2022, February). Typography-MNIST (TMNIST): An MNIST-Style Image Dataset to Categorize Glyphs and Font-Styles. arXiv. Available from <a class="ltx_ref ltx_url ltx_font_typewriter" href="http://arxiv.org/abs/2202.08112" title="">http://arxiv.org/abs/2202.08112</a></p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</li>
<li class="ltx_item" id="S1.I14.i27" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">27.</span>
<div class="ltx_para" id="S1.I14.i27.p1">
<p class="ltx_p" id="S1.I14.i27.p1.1">McLean, R. (1997). The Manual of Typography. London: Thames and Hudson.</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</li>
<li class="ltx_item" id="S1.I14.i28" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">28.</span>
<div class="ltx_para" id="S1.I14.i28.p1">
<p class="ltx_p" id="S1.I14.i28.p1.1">Metafont: Knuth, D. E. (2024) Metafont [Software]. Stanford University. Available from <a class="ltx_ref ltx_url ltx_font_typewriter" href="https://ctan.org/pkg/metafont?lang=en" title="">https://ctan.org/pkg/metafont?lang=en</a></p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</li>
<li class="ltx_item" id="S1.I14.i29" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">29.</span>
<div class="ltx_para" id="S1.I14.i29.p1">
<p class="ltx_p" id="S1.I14.i29.p1.1">Metaflop: Metaflop Project (2024) Metaflop [Software]. Available from <a class="ltx_ref ltx_url ltx_font_typewriter" href="http://www.metaflop.com/" title="">http://www.metaflop.com/</a></p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</li>
<li class="ltx_item" id="S1.I14.i30" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">30.</span>
<div class="ltx_para" id="S1.I14.i30.p1">
<p class="ltx_p" id="S1.I14.i30.p1.1">Metapolator: Metapolator Project. (2024) Metapolator [Software]. Available from <a class="ltx_ref ltx_url ltx_font_typewriter" href="http://metapolator.com/" title="">http://metapolator.com/</a></p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</li>
<li class="ltx_item" id="S1.I14.i31" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">31.</span>
<div class="ltx_para" id="S1.I14.i31.p1">
<p class="ltx_p" id="S1.I14.i31.p1.1">MetaPost: Hobby, J. D. (2024) MetaPost [Software]. Available from <a class="ltx_ref ltx_url ltx_font_typewriter" href="https://tug.org/metapost.html" title="">https://tug.org/metapost.html</a></p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</li>
<li class="ltx_item" id="S1.I14.i32" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">32.</span>
<div class="ltx_para" id="S1.I14.i32.p1">
<p class="ltx_p" id="S1.I14.i32.p1.1">NodeBox: Lieven van Velthoven and Frederik De Bleser. (2024) NodeBox [Software]. Available from <a class="ltx_ref ltx_url ltx_font_typewriter" href="https://www.nodebox.net/" title="">https://www.nodebox.net/</a></p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</li>
<li class="ltx_item" id="S1.I14.i33" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">33.</span>
<div class="ltx_para" id="S1.I14.i33.p1">
<p class="ltx_p" id="S1.I14.i33.p1.1">OpenFrameworks: The openFrameworks Team. (2024) openFrameworks [Software]. Available from <a class="ltx_ref ltx_url ltx_font_typewriter" href="https://openframeworks.cc/" title="">https://openframeworks.cc/</a></p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</li>
<li class="ltx_item" id="S1.I14.i34" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">34.</span>
<div class="ltx_para" id="S1.I14.i34.p1">
<p class="ltx_p" id="S1.I14.i34.p1.1">Oppenheimer, D. M., and Frank, M. C. (2008). A rose in any other font would not smell as sweet: effects of perceptual fluency on categorization. <span class="ltx_text ltx_font_italic" id="S1.I14.i34.p1.1.1">Cognition</span>, 106, 1178–1194. <a class="ltx_ref ltx_href" href="https://doi.org/10.1016/j.cognition.2007.05.010" title="">doi: 10.1016/j.cognition.2007.05.010</a></p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</li>
<li class="ltx_item" id="S1.I14.i35" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">35.</span>
<div class="ltx_para" id="S1.I14.i35.p1">
<p class="ltx_p" id="S1.I14.i35.p1.1">P5.js: McCarthy, L., et al. (2024) p5.js [Software]. Processing Foundation. Available from <a class="ltx_ref ltx_url ltx_font_typewriter" href="https://p5js.org/" title="">https://p5js.org/</a></p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</li>
<li class="ltx_item" id="S1.I14.i36" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">36.</span>
<div class="ltx_para" id="S1.I14.i36.p1">
<p class="ltx_p" id="S1.I14.i36.p1.1">Price, J., McElroy, K., and Martin, N. J. (2016). The role of font size and font style in younger and older adults predicted and actual recall performance. <span class="ltx_text ltx_font_italic" id="S1.I14.i36.p1.1.1">Aging Neuropsychol. Cogn.</span>, 23, 366–388. <a class="ltx_ref ltx_href" href="https://doi.org/10.1080/13825585.2015.1102194" title="">doi: 10.1080/13825585.2015.1102194</a></p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</li>
<li class="ltx_item" id="S1.I14.i37" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">37.</span>
<div class="ltx_para" id="S1.I14.i37.p1">
<p class="ltx_p" id="S1.I14.i37.p1.1">Processing: Reas, C., &amp; Fry, B. (2024) Processing [Software]. Processing Foundation. Available from <a class="ltx_ref ltx_url ltx_font_typewriter" href="https://processing.org/" title="">https://processing.org/</a></p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</li>
<li class="ltx_item" id="S1.I14.i38" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">38.</span>
<div class="ltx_para" id="S1.I14.i38.p1">
<p class="ltx_p" id="S1.I14.i38.p1.1">Pušnik, N., Podlesek, A., and Možina, K. (2016). Typeface comparison – does the x-height of lower-case letters increased to the size of upper-case letters speed up recognition? <span class="ltx_text ltx_font_italic" id="S1.I14.i38.p1.1.1">Int. J. Ind. Ergon.</span>, 54, 164–169.</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</li>
<li class="ltx_item" id="S1.I14.i39" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">39.</span>
<div class="ltx_para" id="S1.I14.i39.p1">
<p class="ltx_p" id="S1.I14.i39.p1.1">RoboFont: Van Rossum, F. (2024) RoboFont [Software]. UFO Tools. Available from <a class="ltx_ref ltx_url ltx_font_typewriter" href="https://robofont.com/" title="">https://robofont.com/</a></p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</li>
<li class="ltx_item" id="S1.I14.i40" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">40.</span>
<div class="ltx_para" id="S1.I14.i40.p1">
<p class="ltx_p" id="S1.I14.i40.p1.1">Tobii Pro (2017). Tobii Studio User’s Manual (Version 3.4.8). Stockholm: Tobii AB.</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</li>
<li class="ltx_item" id="S1.I14.i41" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">41.</span>
<div class="ltx_para" id="S1.I14.i41.p1">
<p class="ltx_p" id="S1.I14.i41.p1.1">Variable Fonts (as a technology): OpenType 1.8. (2024) Variable Fonts [Technology]. OpenType Specification. Available from <a class="ltx_ref ltx_url ltx_font_typewriter" href="https://learn.microsoft.com/en-us/typography/opentype/otspec180/" title="">https://learn.microsoft.com/en-us/typography/opentype/otspec180/</a></p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</li>
<li class="ltx_item" id="S1.I14.i42" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">42.</span>
<div class="ltx_para" id="S1.I14.i42.p1">
<p class="ltx_p" id="S1.I14.i42.p1.1">Wilkins, A., Cleave, R., Grayson, N., and Wilson, L. (2009). Typography for children may be inappropriately designed. <span class="ltx_text ltx_font_italic" id="S1.I14.i42.p1.1.1">J. Res. Read.</span>, 32, 402–412. <a class="ltx_ref ltx_href" href="https://doi.org/10.1111/j.1467-9817.2009.01402.x" title="">doi: 10.1111/j.1467-9817.2009.01402.x</a></p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</li>
<li class="ltx_item" id="S1.I14.i43" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">43.</span>
<div class="ltx_para" id="S1.I14.i43.p1">
<p class="ltx_p" id="S1.I14.i43.p1.1">Woods, R. J., Davis, K., and Scharff, L. F. V. (2005). Effects of typeface and font size on legibility for children. <span class="ltx_text ltx_font_italic" id="S1.I14.i43.p1.1.1">Am. J. Psychol. Res.</span>, 1, 86–102.</p><button class="sr-only button" style="display: none;">Report issue for preceding element</button>
</div>
</li>
</ol>
</div>
</section>
</section>
</article>
</div>

</div>
