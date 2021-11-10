---
title: 'Digitizing Humanities in South Africa'
subtitle: 'Computational linguistic resources, training, and community building'
doi: '10.54590/pop.2020.007'
license: 'CC BY-SA 2.5 CA'
author: 
- name: 'Rooweither Mabuya'
  affil: 'South African Centre for Digital Language Resources (SADiLaR), Potchefstroom, South Africa'
  email: 'Roo.Mabuya@nwu.ac.za'
  orcid: '0000-0001-6658-975X'
  bio: '**Rooweither Mabuya** is a language researcher at the South African Centre for Digital Resources (SADiLaR). Her research interests lie in the systematic creation of relevant digital text, speech and multi-modal resources related to the development of isiZulu and to promote the use of digital humanities related methods and tools within the isiZulu research community. She wants to play a part in the development of isiZulu to be a language of administration, teaching and learning, research and innovation.'
- name: 'Dimakatso S. Mathe'
  affil: 'South African Centre for Digital Language Resources (SADiLaR), Potchefstroom, South Africa'
  email: 'Dimakatso.Mathe@nwu.ac.za'
  orcid: '0000-0001-9369-2672'
  bio: '**Dimakatso S. Mathe** is a researcher in Sesotho sa Leboa language at the South African Centre for Digital Language Resources. He holds an MA degree in African Languages, obtained at the University of Johannesburg. His research interests are in Sesotho sa Leboa morphology, syntax, language discription, and human language technologies, such as part of speech taggers and morphological parsers. '
- name: 'Mmasibidi Setaka'
  affil: 'South African Centre for Digital Language Resources (SADiLaR), Potchefstroom, South Africa'
  email: 'Mmasibidi.Setaka@nwu.ac.za'
  orcid: '0000-0002-2790-3344'
  bio: '**Mmasibidi Setaka** is a language researcher working on the Sesotho language at the South African Centre for Digital Language Resources (SADiLaR). Her interest lie in lexicography with the aim of promoting and helping preserve the language. Her responsibilities include but are not limited to conducting research for Sesotho and facilitating and providing training in digital humanities related trainings and workshops to the broader research community.'
- name: 'Menno van Zaanen'
  affil: 'South African Centre for Digital Language Resources (SADiLaR), Potchefstroom, South Africa'
  email: 'Menno.VanZaanen@nwu.ac.za'
  orcid: '0000-0003-1841-2444'
  bio: '**Menno van Zaanen** is a professor in digital humanities. He works at the South African Centre for Digital Language Resources (SADiLaR), where he is responsible for the digital humanities programme. Menno is particularly interested in incorporating the use of computational techniques in the field of humanities.'
date: 31-10-2020
deck: ''
abstract: 'South Africa has eleven official languages. However, not all have received similar amounts of attention. In particular, for many of the languages, only a limited number of digital language resources (data sets and computational tools) exist. This scarcity hinders (computational) research in the fields of humanities and social sciences for these languages. Additionally, using existing computational linguistics tools in a practical setting requires expert knowledge on the usage of these tools. In South Africa, only a small number of people currently have this expertise, further limiting the type of research that relies on computational linguistic tools.
The South African Centre for Digital Language Resources (SADiLaR) aims to enable and enhance research in the area of language technology by focusing on the development, management, and distribution of digital language resources for all South African languages. Additionally, it aims to build research capacity, specifically in the field of digital humanities. This requires several challenges to be resolved that we cluster under resources, training, and community building.
SADiLaR hosts a repository of existing digital language resources and supports the development of new resources. Additionally, it provides training on the use of these resources, specifically for (but not limited to) researchers in the fields of humanities and social sciences. Through this training, SADiLaR tries to build a community of practice to boost information sharing in the area of digital humanities.'
---


## Introduction

South Africa is a very interesting and diverse, although sometimes challenging, country from a linguistic point of view. It recognizes eleven official languages: Afrikaans, English, Sesotho (Southern Sotho), Sesotho sa Leboa (Northern Sotho, also known as Sepedi), Setswana (Tswana), Tshivenda (Venda), Xitsonga (Tsonga), isiNdebele (Ndebele), isiXhosa (Xhosa), isiZulu (Zulu), siSwati (Swati), with South African sign language currently being considered to become the twelfth official language in South Africa. Some of these official languages are also spoken in the neighbouring countries; for instance, Afrikaans is spoken in Namibia, isiNdebele in Zimbabwe, siSwati in eSwatini (former Swaziland), Setswana in Botswana, Sesotho in Lesotho, and lastly Xitsonga in Mozambique. Meanwhile, some of these languages have dialects which are fighting for official status. Additionally, several other languages are spoken, but are not recognized as official languages.

South Africa has a wide range of cultures associated with the languages mentioned above, which is why the country is also called the Rainbow Nation. Generalizing, the Black population is typically divided into four groups: Nguni (containing isiNdebele, isiXhosa, isiZulu, and siSwati), Sotho (Sesotho, Sesotho sa Leboa, and Setswana), Venda (Tshivenda), and Xitsonga (Tsonga) (Prinsloo and de Schryver, 2002). The white population is mostly of Afrikaans origin, as well as from an English or European background. In addition, the coloured population consists of Khoisan and mixed backgrounds, though this division is not always clearly cut.

To better understand the current (and past) cultural situation, it is essential to investigate the different cultures found in South Africa. There are different ways of doing this, but here we focus on digital approaches to humanities research in South Africa. Digital humanities focuses on using digital or computational approaches to the field of humanities. The computational approach allows, among others, for the analysis of large amounts of information. For example, by analyzing power relations in books or plays in the different South African languages, one may get a better insight on how relationships in certain cultures are seen (van Zaanen et al., 2020). However, in order to do this, tools and resources that deal with the analysis of cultural and linguistic related aspects need to be made available. One of the first steps in this process is the development of computational linguistic tools, also called human language technology (HLT), for each of the South African languages.

We describe the current state of digital humanities in South Africa from the perspective of the South African Centre for Digital Language Resources (SADiLaR). SADiLaR is a centre, founded in 2016, that provides a research infrastructure for computational linguistic research. The infrastructure consists of a hub (located at North-West University in Potchefstroom) and a collection of nodes (at different universities and organizations throughout the country), each with their own expertise. It is funded by the Department of Science and Innovation of South Africa within the context of the South African Research Infrastructure Roadmap (SARIR). Such infrastructures aim to provide support for certain research areas.

The main focus of SADiLaR is to enable and support computational linguistic research in the areas of humanities and social sciences. As such, it provides a range of services that can be roughly divided into two main streams: digitization and digital humanities, which will be discussed in some detail in the sections below. Additionally, it provides training on a range of issues, including practical usage of computational linguistic and corpus analysis tools. At the moment, researchers in humanities and social sciences only make very limited use of such tools. The combination of activities should allow the development of the field of digital humanities, i.e. boosting the computational or digital research in the fields of humanities and social sciences in South Africa.

The rest of this article is structured as follows. Firstly, we describe the current state of available language resources in South Africa, showing that (additional) digital language resources will need to be developed and made available. SADiLaR provides an online framework for the creation and dissemination of these resources. Secondly, researchers require training on how to use the available resources. SADiLaR provides workshops and training in this area. The long-term effect of the training, however, is currently unclear as participants may not recall the full content of the training once that knowledge is required. This relates to the third challenge: there is no sense of community for researchers in the area of digital humanities, while we believe that the other two problems may (at least partially) be resolved through community building. When more researchers use the resources and see their benefits, the usage (and additional development) will increase. Also, with a vivid community, best practices and results are shared. This should encourage further development of research in the field of digital humanities in South Africa.

## Digital language resources in South Africa

With the wide range of languages in South Africa, one may expect that large amounts of linguistic material for all official languages would be available and accessible. Unfortunately, even though a limited amount of government documentation and educational material is available for all official languages, other types of linguistic data (such as books or spoken language collections) are either very difficult to find or simply not available at all. This is especially the case for languages such as Tshivenda, Xitsonga, and isiNdebele, which are spoken by only a limited number of people (Lehohla, 2012).

Considering the availability of computational linguistic tools for the different languages, we see that only a limited number of tools are available, most of which are low level such as spelling checkers, tokenizers, sentence splitters, or part-of speech taggers. For most languages, more complex and useful tools, such as speech recognition systems, are not available at all.[^1] These findings are made explicit in a recent audit (Moors et al., 2018; Wilken et al., 2018), which illustrates the limited availability of different tools for each of the languages.

Using most of the computational linguistic tools often requires advanced computer skills (for instance, to convert linguistic data in a format that can be used as input to the tool or convert the output of the tool into a readable format) in addition to knowledge on how to interpret the output of the tools (for example, the meaning of part-of-speech tags or the tags that indicate named entities). As such, these can only be used by people who understand their purpose and know how to use them. This may not be an issue with end-user applications, such as spelling checkers, as their interface is directly incorporated in word processing software, but this is a problem for many of the other tools.

The HLT community (i.e. the people who know how to develop and use the computational linguistic tools) in South Africa is fairly small and consists mostly of researchers from some of the country’s higher education institutions. Additional organizations interested in these tools are national science councils, a handful of companies in the private sector, and the government who funds these projects (Grover et al., 2011a). It is a clear sign that the field of HLT in South Africa falls under the scarce skills bracket and the country “has not yet been able to maximise on its opportunities and create a thriving HLT industry” (Grover et al., 2011a, p. 1). It is for this reason that “\[t\]he South African Department of Arts and Culture (DAC) confirmed the need to advance HLT in the South African context by developing and establishing the national HLT strategy” (Grover et al., 2011b, p. 1). A limited number of HLT projects are undertaken at various institutions in the country, with a few universities offering modules in this field.

All official languages of South Africa are constitutionally guaranteed support from the government (Republic of South Africa, 1996, 2012). This implies the requirement that (at least) all the official languages should be catered to in terms of the development of HLT tools to enhance communication and strengthen the role of the languages within the economic, educational, and scientific spheres. However, currently there are large discrepancies in the support of languages (for instance, many of the government websites are only available in English and the distribution of financial support for each of the languages is unclear). As such, HLT for the South African languages has been regarded as a high priority in the country even though currently their development is still in its infancy stage (DAC, 2019).

Most of the research in and development of HLT is conducted at universities and government entities. Adegbola (2009) identifies seven universities that work within the field of HLT. In Table 1, we provide a brief overview of the focus areas of the different universities to provide an overview of the current landscape of HLT research in South Africa (which does vary over time). Note that CSIR is not a university, but a semi-government organization: Council for Scientific and Industrial Research. Also, CTexT is a research and development organization at the Potchefstroom campus of the North-West University.

<div class="bordertable" markdown="1">

| University 			| Area		| Topic |
-----------------------------------------------------------------------------------------------------|
| Cape Town				| Speech 	| Speaker recognition |
| Limpopo					| Speech 	| Speech synthesis (Sesotho sa Leboa, Setswana, Tshivenda, and Xitsonga) |
| Stellenbosch		| Speech 	| Speech to speech translation, tonal languages |
| CSIR						| Speech 	| Telephony-based information services |
| Witwatersrand		| Speech 	| Speech recognition, signal processing |
| Pretoria 				| Text  	| Corpora, software localization |
| South Africa (UNISA) 	| Text 		| Morphological analysis, Wordnet |
| North-West (CTexT)		| Text		| Machine translation systems, spelling checkers, POS taggers |
</div>


> *Table 1: Overview of universities and organizations researching HLT, including the area and example topics.*

This brief overview of some of the universities (and organizations) working in the area of HLT in South Africa shows that South Africa is taking HLT seriously and is making progress regardless of

the limited number of HLT practitioners found in the country. It may be clear that HLT is still a scarce skill and there is a need for additional experts in the field. Additionally, due to the somewhat scattered nature of the research and changes in research topics, it is likely that this brief overview is incomplete.

## Development of resources

Considering the first stream supported by SADiLaR, digitization, it is recognized that there are many reasons why linguistic data is important in the current research fields of linguistics, humanities, and social sciences. From a computational viewpoint, this data is essential when developing HLT applications. As a result, these tools allow for quantitative (not necessarily computational) as well as qualitative research approaches within the research fields.

In order to develop practical HLT applications, essentially two approaches can be taken. On the one hand, rule-based approaches are normally theory-driven and are mostly manual approaches to incorporate linguistic knowledge into the application. This requires language experts that describe linguistic properties, for example, in the form of grammars, which are then used to analyze, annotate, or generate linguistic data. On the other hand, data-driven approaches require large amounts of (annotated) language data, which are then used as training data for machine learning systems, to automatically find patterns within the annotations. The resulting trained systems can then be applied to new, unseen linguistic data.

The data-driven machine learning approaches are currently popular in the field of computational linguistics. Their performance is typically good and their development is not very time and expertise-intensive. However, they do require large amounts of (sometimes annotated) data, which means that if this data is not available, data-driven approaches either cannot be used or will only yield systems with low performance.

Another reason for wanting access to linguistic data is that it allows for corpus-driven or data-driven research. In contrast to armchair theorizing (which corresponds to a careful analysis of existing scholarship, or, for instance, careful consideration of syntactic correctness when evaluating linguistic theory), corpus or data-driven methodologies (which identify properties based on large linguistic data collections) require observations. By collecting large amounts of language use and identifying patterns or regularities in the examples of language use, one may come up with novel theories on the language, such as linguistic structures, grammar, etc., or on the content of the linguistic data collection (i.e. a content-based analysis). This data analysis approach may require quantitative (e.g., counting) or qualitative (e.g., in-depth analysis of specific constructs) methods. For both, ample linguistic data is required. The actual content of the data may be different depending on the research question under consideration. For instance, to investigate changes in music culture, texts that describe these cultures over time may be analyzed (computationally) and high-level patterns may be identified.

Unfortunately, for most official South African languages, hardly any linguistic data is available in digital form for research purposes. For English, large amounts of data are available (linguistically annotated as well as unannotated), however, this data is often not South African English, which means that specific linguistic constructs typical for South African English cannot be researched. For Afrikaans, some linguistic data is available,[^2] but for the other languages, hardly any digital linguistic data can be found. This severely limits the data-driven analyses of these languages.

SADiLaR provides funding in the form of open calls (with funding up to R500,000 per project) to work towards the aims of SADiLaR, which include the development of computational linguistic resources (both data sets and tools). Additionally, SADiLaR’s nodes can apply for funding to develop resources related to their expertise. This has led to and currently results in the development and improvement of several tools, including machine translation for the official languages, automatic speech recognition, and the development of practical tools, such as writing development aids.

With respect to digitization, depending on the source of the data, several processes may be required. For instance, if texts are scanned, an OCR (Optical Character Recognition) tool will need to be applied to the scans to convert the images in texts that can be handled for further analysis. These OCR tools typically contain a language model (that needs to be redeveloped for each language) that checks for the likelihood of correctness of words being proposed from the character by character analysis in the image. When applying such a tool to texts from a specific language, the correct language model needs to be selected. For English, language models are available (with South African English being only a minor variation in this sense). Afrikaans is quite similar to European languages for which language models exist, such as Dutch. However, other South African languages, more specifically the African Indigenous languages, are quite different, hence they require their own language models.

To illustrate the difficulties of dealing with the different indigenous South African languages, we would like to show that they are also structurally different. Regarding orthography, they can be separated into two distinct writing systems, conjunctive or disjunctive. The conjunctive orthographies combine morphemes to form words while the disjunctive languages separate them. For example, Nguni languages (consisting of isiNdebele, isiXhosa, isiZulu, and siSwati) use a conjunctive system, whereas the Sotho languages (Sesotho sa Leboa, Sesotho, and Setswana) including Tshivenda, and Xitsonga are written disjunctively (Van Wyk, 1995). This can be seen in the following examples from isiZulu (Example 1) and Sesotho sa Leboa (Example 2), which have similar morphological configuration, but show conjunctive (combine morphological units into one word) and disjunctive (each morphological unit is a separate word) orthographic writing systems respectively.

IsiZulu example:

	(1) Ngiyabazi

		Ngi- 	ya- 	ba- 	zi
		I  		[pres]	them 	know
		‘I know them’

Sesotho sa Leboa example:

	(2) Ke a ba tseba

		Ke 	a 		ba 		tseba
		I 	[pres]	them 	know
		‘I know them’

These orthographic issues also affect HLT processes, because these writing systems need to be catered for separately. This notion is reiterated by Taljard and Bosch (2006, p. 428) when they mention that “not only different approaches are needed for word class tagging, but also that the sequencing of tasks is to a large extent determined by the difference in writing systems.” This shows that essentially for each tool built for the South African indigenous languages, their respective writing systems needs to be taken into account.

If we now consider the second SADiLaR stream, digital humanities (often abbreviated as DH), which relies heavily on the practical use of the HLT tools in the fields of humanities and social sciences, we see that this research field is rather new in South Africa. For instance, the Digital Humanities Association of Southern Africa was only established in April 2016 as a way to enhance the understanding and participation in digital humanities in Southern Africa. Some of the aims of this organization are to: foreground the national and international benefits of developing digital humanities scholarship as a priority in the humanities and social sciences, and promote the understanding and practice of digital approaches to humanities scholarship across the southern African region, amongst others.[^3]

There are a few projects that are run by different institutions in South Africa within the domain of digital humanities, such as the Digital Innovation South Africa, which is a centre of excellence, focuses on digital imaging techniques in the context of library and archival studies[^4] and the Jonathan Edwards Centre Africa, which concentrates on research on the work of Jonathan Edwards.[^5] Some more examples can be found on the DHASA website.[^6] These projects are generally multi-disciplinary in nature. Several projects are funded by SADiLaR (within the digitization and digital humanities programmes as explained above). One of the external projects currently underway and funded by SADiLaR, African Wordnet (AFWN),[^7] creates wordnets for nine of the official languages of South Africa with the exclusion of Afrikaans and English. The wordnet as an electronic database of synonyms clustered together as synsets on the basis of conceptual-semantic and lexical relations is essential for, among others, study into lexical structure, lexicalization patterns, and cross-linguistic comparison (Bosch and Griesel, 2017; Griesel and Bosch, 2020). Other projects are typically small, run by individual researchers as can be seen, for example, by looking at the program of the second international conference of the Digital Humanities Association of Southern Africa (DHASA).[^8]

## Training

The limited availability of people with HLT skills, and similarly with digital humanities skills, is a cause for concern. It goes against the government’s idea realized a few years back related to the role of HLT in the country: “The field of human language technology (HLT) can play a vital role in bridging the digital divide and thus has been recognized as a priority area by the South African government” (Grover et al., 2011b, p. 1). Skills needed include, but are not limited to: computational linguists, human language technology specialists, research and development engineers, linguists, terminographers, lexicographers, etc.

To resolve the problem of limited availability of experts, SADiLaR is playing a major role in training and development in the areas of HLT and digital humanities. This training program exposes language researchers to different HLT tools and methodologies, which help to equip them to be the next generation with skills in the fields of HLT and digital humanities. It provides training for the researchers to use the tools in their own respective research areas, boosting the computational or digital methodologies in different humanities and social sciences research areas.

As such, SADiLaR also has to fulfill the national mandate of creating awareness and offering training opportunities to various scholars in South Africa. Initially, the training of researchers working at SADiLaR consists of them attending local and international workshops (or tutorials). During these training events, the SADiLaR researchers receive training in the different tools themselves; in fact, they are required to be experts in at least two tools. As these training sessions are conducted by subject specialists, the SADiLaR researchers receive the right level of training in order to share this information later. For example, one of the SADiLaR researchers attended a Sketch engine (a corpus manager and text analysis tool) workshop held in Mikulov, Czech Republic, conducted by developers of the tool and an editor of Macmillan Dictionaries and several SADiLaR researchers have participated in the Knowledge Creation in the 21st Century: Approaches to Open, Digital Scholarship workshop organized by the Canadian-Australian Partnership for Open Scholarship (CAPOS), combined with the DH Downunder summer school in Newcastle, Australia.

The centre also has a national mandate of transferring skills to the broader community and this is done by SADiLaR researchers providing training to other researchers. Training workshops can be requested and, based on the request, specialized workshops will be developed. These workshops, which can take place across the country (typically at one of the 26 universities or seven universities of technology), normally take one or two days and are typically taught by SADiLaR researchers, but SADiLaR also partners with the Carpentries.[^9] During the workshops, researchers who have been trained in the use of different tools that allow for data handling in a humanities or social sciences context—such as Voyant tools, CATMA, Atlas.ti, Autshumato, etc.—explain these tools in practical sessions. All SADiLaR researchers help as instructors during these workshops, which helps build the HLT and digital humanities community within the country (and beyond in some instances).

Additionally, at least two people are trained before the actual workshop, who then become helpers on the day of the workshop. This way, the helpers are able to sharpen their skills in a specific tool taught while also helping people new to the tool at the same time. This can be seen as a “train the trainer” approach.

To structure the training sessions, SADiLaR aims to provide a more organized set of workshops by separating the current workshops into three levels: beginner, intermediate, and expert. This allows for more targeted and on-going training. An additional advantage is that, because it allows for tracking participants over time, it will be easier to measure the impact of these workshops, as the attendees will be moving from one level to the next.

In general, digitizing humanities in South Africa can only be achieved using a range of different channels to get the message across. SADiLaR has therefore decided on having webinars, blogs, and vlogs, in addition to the training sessions that are already organized, to help the wider community in learning and understanding the challenges, solutions, and tools that can be used in the area of digital humanities, as well as what SADiLaR is trying to achieve in the general sense. These forms of communication will give a brief and general overview, an introduction, and sometimes a step by step guide of using digital tools and methods for research purposes. In particular, webinars are quite interactive and are typically in the form of question and answer sessions. According to Wang and Hsu (2008, p. 175) “webinar tools facilitate real-time communication and enrich the interactivity in an online learning environment.” As such, webinars have a near live experience, but are also recorded and made available for future reference.

SADiLaR has recently started blogging, where researchers write short blog posts about their experiences. This can be anything relating to the growth of the South African languages, but also about the different HLT tools, conference attendances, practical experiences, etc. The hope is that this type of blog (as well as vlogs) will not only increase awareness, but will also provide information on how to use specific tools, which are already widely available for people across different disciplines. By providing, for instance, step by step guides, users will receive information on how to use the tools.

## Community building

Even though the workshops have received positive feedback from participants in the different fields, the actual impact of the workshops is yet to be established. Similarly, measuring the impact of the webinars, blogs, and vlogs is difficult. There are several difficulties. Firstly, digital humanities is still an emerging field in the country, which means that it is difficult to identify explicit digital humanities researchers. Secondly, it is hard to measure the consistency of usage of the tools after they have been introduced during workshops. Thirdly, even though the participants in webinars and views of the recorded webinar, blogs, and vlogs can be counted, it is unclear what impact this has.

SADiLaR is currently working on developing strategies to build an HLT and digital humanities community of practice, which is quite popular in the field of education (Renninger et al., 2002). The aim of the training events (described in the previous section) is not only to train one researcher, but to see these events as “training the trainer” events (Pancucci, 2007). These events train researchers who can distribute the learned knowledge to a larger number of researchers. This has a variety of benefits. Firstly, people who have followed the workshops can help with other researchers using the same tools. This will also allow the working knowledge of these tools to be active. Secondly, a sense of community will emphasize the importance of the research field. Thirdly, a strong community of practice allows for answering (practical) questions by people in similar fields, but also lead to new research projects or collaborations.

## Conclusion

Computational linguistic resources are important for the digital and economic growth of South Africa. Hence, it has been identified as a priority area by the government. Also, it is recognized that building a strong community of specialists in this field is essential. Furthermore, having a good basis of HLT tools and experience, for all official South African languages (to start with), is a prerequisite to digitize humanities research in the country.

Two main directions are currently taken: the development of new computational linguistic resources (tools and data sets) through the digitization program of SADiLaR, and training for interested (humanities, social sciences, and other) researchers into the fields of HLT to boost the research in the area of digital humanities.

At the moment, the important work in this direction is the skilling and re-skilling of researchers, such as language specialists and humanities researchers. Additionally, grooming current university students by showing the possibilities of HLT tools and digital humanities is essential, so they can become the next generation of experts in HLT and digital humanities.

SADiLaR currently aims at extending awareness and offering assistance in training interested researchers and students through workshops. This approach is extended with the goal of building a community of practice consisting of interested researchers who also share their knowledge and skills. This should lead to an environment where new researchers feel welcomed and that allows for easy skills transfer, boosting the fields of HLT and DH.

<div class="refs" markdown="1">

## References

Adegbola, T. (2009). Building capacities in human language technology for African languages. In *Proceedings of the First Workshop on Language Technologies for African Languages*, pp. 53-58. Association for Computational Linguistics.

Bosch, S. E. and M. Griesel (2017). Strategies for building wordnets for under-resourced languages: The case of African languages. *Literator (Potchefstroom.* *Online) 38*, 1-12.

DAC (2019). Annual performance plan 2018-2019. Technical report, DAC.

Griesel, M. and S. Bosch (2020, May). Navigating challenges of multilingual resource development for under-resourced languages: The case of the African wordnet project. In R. Mabuya, P. Ramukhadi, M. Setaka, V. Wagner, and M. van Zaanen (Eds.), *Proceedings of the first workshop on Resources for* *African Indigenous Languages*, Marseille, France, pp. 45-50. European Language Resources Association (ELRA).

Grover, A. S., G. B. van Huyssteen, and M. W. Pretorius (2011a). The South African human language technology audit. *Language resources and evaluation* 45(3), 271-288.

Grover, A. S., G. B. van Huyssteen, and M. W. Pretorius (2011b). A technology audit: The state of human language technologies (HLT) R&D in South Africa. In *Proceedings of PICMET’11: Technology Management in the Energy Smart World (PICMET)*, pp. 1-14. IEEE.

Lehohla, P. (2012). Census 2011 census in brief. Technical Report 03-01-41, Statistics South Africa.

Moors, C., I. Wilken, K. Calteaux, and T. Gumede (2018, September). Human language technology audit 2018: analysing the development trends in resource availability in all South African languages. In *Proceedings of the Annual Conference of the South African Institute of Computer Scientists and Information Technologists*, New York, NY, pp. 296-304. Association for Computing Machinery.

Pancucci, S. (2007). Train the trainer: The bricks in the learning community scaffold of professional development. *International Journal of Social Sciences* 2(1), 14-21.

Prinsloo, D. and G.-M. de Schryver (2002). Towards an 11 x 11 array for the degree of conjunctivism/disjunctivism of the South African languages. *Nordic Journal of African Studies* 11(2), 249-265.

Renninger, K., W. Shumar, and R. Pea (2002). *Building Virtual Communities: Learning and Change in Cyberspace. Learning in Doing: Social, Cognitive and Computational Perspectives. Cambridge University Press.*

Republic of South Africa (1996). Constitution of the Republic of South Africa. Act 26.

Republic of South Africa (2012). Use of official languages act. Act 12.

Taljard, E. and S. E. Bosch (2006). A comparison of approaches to word class tagging: Disjunctively vs. conjunctively written Bantu languages. *Nordic journal of African studies* 15(4), 428-442.

Van Wyk, E. B. (1995). Linguistic assumptions and lexicographical traditions in the African languages. *Lexikos* 5, 82-96.

van Zaanen, M., B. Trollip, P. M. Ramukhadi, and R. Mlambo (2020). Identifying relations between characters in Afrikaans, Tshivenda, and Xitsonga books. In *DH2020 Book of abstracts*.

Wang, S.-K. and H.-Y. Hsu (2008). Use of the webinar tool (elluminate) to support training: The effects of webinar-learning implementation from student-trainers’ perspective. *Journal of interactive online learning* 7(3), 175-194.

Wilken, I., T. Gumede, C. Moors, and K. Calteaux (2018). Human language technology audit 2018: Design considerations and methodology. In *International Conference on Intelligent and Innovative Computing Applications (ICONIC)*, pp. 1-7. IEEE.

</div>


[^1]: Note that most of the computational linguistic tools are highly language dependent, meaning that they need to be (re)developed for each language.

[^2]: The SADiLaR catalog contains a list of data collections for the different languages, [https://repo.sadilar.org/handle/20.500.12185/7](https://repo.sadilar.org/handle/20.500.12185/7).

[^3]: [https://digitalhumanities.org.za](https://digitalhumanities.org.za)

[^4]: [https://disa.ukzn.ac.za](https://disa.ukzn.ac.za)

[^5]: [https://edwardseducationblog.wordpress.com](https://edwardseducationblog.wordpress.com)

[^6]: [https://digitalhumanities.org.za/index.php/activities](https://digitalhumanities.org.za/index.php/activities)

[^7]: [https://africanwordnet.wordpress.com](https://africanwordnet.wordpress.com)

[^8]: [https://dh2019.digitalhumanities.org.za/schedule](https://dh2019.digitalhumanities.org.za/schedule)

[^9]: [https://carpentries.org](https://carpentries.org)
