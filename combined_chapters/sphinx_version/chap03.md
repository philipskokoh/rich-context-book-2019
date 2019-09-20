---# Chapter 3 - Digital Science Use CasesEnriching context and enhancing engagement around datasets==========================================================Christian Herzog^1,a^, Daniel W Hook^1,2,3,b^, Mark Hahnel^1,c^, StacyKonkiel^1,d^, and Duane E. Williams^1,e^^1^Digital Science, London, N1 9XW, UK^2^Department of Physics, Washington University in St Louis, St Louis,Missouri, USA^3^Centre for Complexity Science, Imperial College London, London, SW72AZ, UK(^a^[[https://orcid.org/0000-0002-9983-0033]{.underline}](https://orcid.org/0000-0002-9983-0033),^b^[[https://orcid.org/0000-0001-9746-1193]{.underline}](https://orcid.org/0000-0001-9746-1193),^c^[[https://orcid.org/0000-0003-4741-0309]{.underline}](https://orcid.org/0000-0003-4741-0309),^d^[<https://orcid.org/0000-0002-0546-8257>]{.underline}^e^[[https://orcid.org/0000-0002-2111-3413]{.underline}](https://orcid.org/0000-0002-2111-3413))Introduction------------The relationship between research, researchers and data is changing.Data has always played a critical role in scientific research, but inrecent years it has taken centre stage not only for the sciences butalso the social sciences, and it also now plays a significantlyincreased role in the humanities. This change is being driven by two keyfactors: First, the volume of research data that we have available isgrowing rapidly; and, second, our ability to process and analyse thesedata is growing as computers become faster and algorithms become morepowerful. While many researchers welcome having more data to work with,the challenges in this new data-rich research world are not trivial.The volumes of data that researchers have had to work with have beensteadily on the rise for many years. Big Science projects such as thoserun by CERN have led the way in creating international infrastructuresfor sharing, processing and analysing large datasets. In a very realsense, the Internet itself is the result of the need for a globalinfrastructure to support science. Grid computing is another piece ofinfrastructure that was developed to support large internationalcollaborations. Looking at the research world from a high enough vantagepoint and focusing on these large projects, however, misses thechallenges generated by a second wave of advances.While many researchers now have large volumes of data, the technologiesdeveloped to support the cutting-edge research projects of more than 20years ago have become commoditised and are available to many researchersat a fraction of their original cost: storage is cheap and data transferis fast. Technological issues are not, for the most part, at the centreof today's challenges for our increasingly data-centric research world.Rather it is infrastructure of a different sort that now needs to bedeveloped to support the research requirements of today.In this short article, we discuss the needs of today's research systemfor investment in two critical pieces of infrastructure that have notkept pace with their technological counterparts mentioned above. Thesemissing pieces are information infrastructure and culturalinfrastructure. Both of these challenges are addressed in DigitalScience's Rich Context project. Through this project, our aim is toprovide 'enriched' information infrastructure around datasets. Thisinformation includes details of the approach to data stewardship,context of usage, code applied to the dataset in its production, as wellas code applied to the data to derive further results or translate itfor practical uses. All these factors add critical elements to theresearch infrastructure. The cultural infrastructure involves creatingthe incentives, triggers and frameworks that encourage the datasetstewards, experts and users to contribute to these critical informationelements.Information Infrastructure--------------------------It is important to understand that any successful informationinfrastructure for research data will necessarily be deeply linked withthe culture of research. For clarity of presentation, we have decided topresent the challenges of the current information infrastructure andthose of our current cultural norms separately. However, at each stageit is clear that each influences the other.Information infrastructure can be defined as the collection of processesand artefacts that are foundational to today's scholarly communications.A simplified model of scholarly communications would have artefacts likejournals, journal articles, article metadata and citations. Theprocesses are peer review and scholarly search.The members of the Royal Society did not have today's world in mind whencreating *Philosophical Transactions*, the first ever scientificjournal, 350 years ago. The infrastructures that have built up aroundresearch publication since that time are powerful and persistent throughtheir ubiquity. Until very recently, we expected articles to be groupedinto journals, and published on a particular date. We expect there to bea version of record that is in some sense the definitive record of apiece of research.But heavy use of data in a research problem, or data sharedcollaboratively among colleagues across a research field, changes thedynamic around the research record. Fields that use data increasinglypublish those data as a distinct output from a research article. Datahas become a principal research output, but lacks the infrastructurethat we have built up around the journal article (some experiments like"data journals" have had only limited success, given that a static and"flat" article is not a natural fit for publishing most data).A dataset can change with time for many reasons: data may be added overtime, corrections may be issued, and so on. In these cases, it may beappropriate to "version" the dataset (by issuing a persistent identifierfor a point-in-time snapshot for the dataset, allowing subsequentchanges to receive their own "versions"). But changes to a dataset mayhave a knock-on effect on the interpretation of the data and mayfundamentally alter the research result that was originally reported.Moreover, in many fields "Big Data" is so central that it not only putspressure on the community to establish an acceptable model of datapublication, but also puts significant stress on how we read, interpret,and review research as a whole.Many datasets are now so vast that we lack the ability as humans toconsume them in an easy way. Visualisation technologies and other toolsthat allow us to interact with and sample data dynamically have receivedsignificant attention in recent years, and have helped with theinterpretation of data in online environments. But it is simplyimpossible to reduce some types of data to a single figure or printabletable, as would be the case for "traditional" journal publishing. Byattempting to do so, we miss the essence of the data and risk failing tocommunicate data-driven conclusions accurately. This limitation ofcurrent publication formats (e.g. static PDF files for articles) is anissue that relates to the reproducibility crisis of modern research.Peer review is another process that must change to account for data as a"first class" research object. Historically, peer reviewers have ensuredthat a piece of research is well-communicated and correct. This level ofpeer review is difficult to apply in the context of research data. Ifdata is being published as a primary output, then it may be possible toperform a kind of peer review by applying some statistical tests to asample of the data, or by using some other appropriate technique.However, it is no longer practical in most cases to set up a parallelexperiment to reproduce data, as had been the case in years past. Acrossall contexts there are good reasons for these challenges: the experimentmay be too costly to repeat, or the conditions of the original datacollection may not be replicable (for example, surveying stress levelsof the populace during a specific political event). In addition, ethicalconsiderations such as the anonymity of those being surveyed may makecertain types of data difficult to review. Thus, we must develop robustand accepted approaches to peer review, not only for data itself butalso for those publications that are heavily based on data.A number of publishing innovations have made journal articles morediscoverable and accessible in recent years, such as preprint servers,DOIs, centralized search engines like Google Scholar and Dimensions,etc., however, these do not translate directly across to research data.Part of the reason for this is that there is a standard structure for anacademic article (e.g. abstracts, keywords, etc), which is specificallydesigned around communication to humans. Solutions designed for data todate still have a long way to go in that regard. For example, the corefields required to create a valid DataCite record are identifier,creator, title, publisher, publication year and resource type[^1]. Allother data fields are optional (e.g. location, funder, subject,contributors) due to the fundamental uncertainty in what mightconstitute research data in the future. This flexibility limits how datacan be discovered. It has taken some years for Web of Science, Googleand others to introduce functionality to search for datasets in theirdiscovery systems.Clearly, technological infrastructure for data\--or lack thereof\--hashuge implications for the discovery, peer review, citation practices,interpretation, and availability of data. These challenges areinterconnected with challenges we face when thinking about the culturalinfrastructure for data, as well.Cultural Infrastructure-----------------------There are two main aspects to cultural infrastructure: incentives andcapability. Both of these aspects are strong drivers in how researchersengage with research data, and their behaviours relating to sharing itwith others and making it available to external scrutiny.Academics do not typically take up research careers for financial gain.Rather, they choose to dedicate their lives to understanding a specificproblem partially in the hopes of discovering something that will makethem "successful" by some measure. Success, of course, can be understoodby looking at incentives for researchers. Researchers in many fields arepromoted by publishing in specific high-impact journals, leading tofunding success. Once you have demonstrated capability in this respect,there is a virtuous cycle. More funding leads to a greater chance offurther publications in the "right" journals, which leads to morefunding.There are no such incentives here for sharing data. In this context,parting with the data that underpins your research gives rise to twoconcerns. Firstly, that someone may find an error in your work anddiscredit what you have done. Secondly, that someone else may not sharetheir own data but will gladly reuse yours if you make it available,especially in fields where success is based on having more data toanalyse. That may be the difference between having a career where youare well funded, promoted and have the ability to do research in the waythat you want, and having to leave the field.A further level of inequity exists in which data-related jobs are valuedby the Academy. If a researcher happens to be particularly talented inworking with data curation, data analysis or data processing, there isno track for recognising these talents. They are unlikely to be a firstauthor on a publication in a major journal due to their data wranglingtalents, and hence they have less of a chance of career progression thanresearchers who take a more traditional "publish or perish" path withtheir work as described above.This set of perverse incentives means that people with the capability tohandle data are often incentivised to leave research. Hence, not only dowe have a problem of incentives in sharing and communicating data, butwe also have a problem in retaining people who have the capability thatwe need to structure data so that it can be shared and built upon.Capability for sharing data is the second aspect of the culturalchallenge that academia continues to wrestle with. Making data availableto others is generally accepted as a key part of the researchcommunication process. However, there are certain established normsaround when the data should be shared, and to what depth it isshared[^2]; for example, in fields where human subjects research isprevalent, there is a much more conservative attitude towards open datathan in fields like astronomy where data sharing is widely practiced,given that data can be collected by only a handful of observatories andtelescopes worldwide.In fields that are more applied, ensuring that data generated as aresult of a commercial relationship is protected is crucial. In suchfields, academics often have a better understanding of copyright,intellectual property rights and licences[^3]. But outside of thiscontext, there is a general lack of understanding of these issues andhence data are often not shared over concerns for a perceived legalbarrier.Other concerns are ethical---for example, should these data be shared ifit might infringe the rights of the subjects of the research?Researchers are beginning to become aware that, through the use ofalgorithms, some data is not as well anonymised as it may firstappear[^4]. Anonymisation of data is a research field in and ofitself[^5].Other concerns are simply practical---how do I make my data available ina way that is meaningful to others? The work associated with making adataset generically machine-readable is challenging for manyresearchers, who tend not to be experts in data handling. The workassociated with making a dataset human-understandable, reproducible andfully contextualised is often significant. However, governments andfoundations have not necessarily prioritised these activities in theirgrant programs (though this is changing)[^6]^,^[^7].Enriching context-----------------While we at Digital Science cannot solve all the issues raised here, thepoints discussed do offer a blueprint for a generalised approach tohandling and thinking about research data and what it means to be aresearcher in the current research paradigm. We believe that asignificant step in changing the perception of data and those who handledata is to increase the contextuality of research data.There are two important pieces of infrastructure that need to beintroduced. Firstly, a version of CredIT for research data[^8], wherebyall contributors to a dataset's feeding and care over time arerecognized, valued, and encoded in machine-readable ways^.^ Such asystem would be crucial in providing incentives towards data sharing,both making it possible to recognize "data wranglers" who could advancetheir career in-turn, and also by making it much easier for universitiesto track and reward those who are contributing towards the kinds of openaccess that are often discussed in university mission statements andfaculty council decrees. The second piece of crucial infrastructureneeded is, a set of tools that allow research data to be discovered andcontextualised. In this section, we will focus on the latter challenge.When we built Dimensions, the ability to contextualise any piece ofresearch was a strong driver for our work[^9]. The idea that allresearch happens in a particular place at a particular time, carried outby a set of people, some of whom may be affiliated with a researchinstitution, gives a set of metadata that allows us the "weak context"of a piece of research. By "weak context" we mean that the context beingprovided gives no deep understanding of the context of an article to anon-expert and is essentially indistinguishable from standard metadata.But with modern data mining approaches, it is possible to add a "strongcontext".Strong contextualisation of research should provide a user with richinformation about the research including funding, other researchproduced as part of the larger project (e.g. related publications,clinical trials, etc), and details of the research that was built on topof it. This information should also fit into, trends and graphicalrepresentations that offer a more complete, more rapid understanding ofhow research fits into the larger field, related fields, or the contextof the publishing journal or supporting institution. For example, for aresearch article, we should be able to quickly understand how manyresearchers are in a related field, whether the field is growing, howold the field is, how much funding has been deployed in the field, whichcountries have provided that funding, whether the field has begun thetranslation to application through patents or clinical trials, orwhether it has been used as a basis for the formulation of policy.Context can also be offered in the data that we provide to understandthe reach and influence of research.Alternative metrics ("altmetrics") are data from the social web that runorthogonal to classic citation measures, which can be seen to addsignificant context to an article -- extending our understanding of howdifferent cohorts of potential users of the research are engaging withit. For example, we can use altmetrics to understand if an article isbeing mentioned in the news, in which geographical regions it is beingnoticed, whether it is being used as part of a teaching syllabus, andmany other kinds of public and non-traditional scholarly engagement.These data can then be visualized in creative ways to add instantadditional context to engagement with a research article (see Fig. 1).![](combined_images/chap03_image1.png){width="7.270833333333333in"height="2.5277777777777777in"}*Figure 1: Different types of context tracked by Altmetric.com for anyresearch output.  (Reproduced by permission of Altmetric.com)*How datasets are used in research more broadly is another importantpiece of context that many data search engines lack. This is where theRich Context project comes in. During the Rich Context project, weexplored using Dimensions' freely available public interface as adestination for researchers who seek context around datasets.Such context for research data and its impacts could be offered in theform of in-app badges and other "signposts" that connect data with itslarger context. Such a contextualizing badge could include not only thenumber of citations that the dataset has received, but also whether thedata has been versioned (through Figshare's repository metadata),discussed online (through Altmetric data), and what kind of tools andinsights have been built on top of the data (through rich mining offull-text and citation data available in the ReadCube referencemanagement corpus and in Dimensions).Correctly developed and accepted by the community, this type ofinformation can make a contribution to solving many of the problemshighlighted in this article. If the correct contextual facets can bedeveloped, then recognition would be easier to assign to those who havecontributed to the process of creating and maintaining datasets. Withgreater context around them, datasets become easier to locate,understand and value. This in turn could lead to a broader evaluativeenvironment and more engagement from academics.Engagement across academia, however, is not uniform. Mechanisms need tobe provided to engage data science-focused researchers from whom moredetails of their tools, scripts and codebooks could be drawn, addingfurther value to research data. At the same time, engagement tools needto allow data scientists to leverage this information so that it isvaluable to them when they are the consumers of search results. Theseare subtly different use cases from those of standard researchers. Bymining ever more open research systems wherein data is being analyzed(e.g. Gigantum, Github, etc), we can start to integrate these othercrucial engagement contexts as well.![https://lh5.googleusercontent.com/3OunhdD8OksXbG5n9dlxQZ4vHfq3ytZuYahLuNwnXG2oaJ7vSpCkCULgc\_8tpapwUqzFLsALR6Xcrhl2ZgyYtvxOhg2kfoXeAJ1MoibnK0liPl2w6xhvoMye-lGtyopkM0ja1xnB](combined_images/chap03_image2.png){width="4.543310367454068in"height="4.776042213473316in"}*Figure 2: Mock-up of a research data badge helping to contextualise aset of search results.*![https://lh5.googleusercontent.com/51fefhu7zEe3Y61OD1vbe-Bl9EiBI8IUUj1FOnP7NLLexSqDO7cJrzBeuzmwUR7eC84AQKmcMwDcTKW3trd7-vnNiyelvHvEOdM\_Da5OgEoTYh5lvrz8wfxWzTH2\_5DJjfgwe9Ed](combined_images/chap03_image3.png){width="4.163163823272091in"height="4.505208880139983in"}*Figure 3: Mock-up of a research data badge helping to contextualise aspecific dataset.*In Figures 2 and 3, we have mocked up some early thinking for how acontextualized research data badge could look. This visualisation isbased on insights from the Rich Context project and uses data that couldbe mined from articles that use a specific dataset. In particular, wehave suggested four initial facets of context that both datascience-focused researchers and others could find helpful when viewing adataset:-   **Experts** **who have made use of the data**, sourced from    references made to the dataset in a professional context such as an    industry whitepaper or policy document-   **Academics** that **cite the data**, mined from citation of the    dataset or ancillary data in the peer reviewed literature-   **End users of the data**, sourced from code book references    included in public code repositories-   **Enhancements of the data**, vis-à-vis annotations and comments    made on the data in public forums.In summary, we believe that, if deployed across the many environments inwhich researchers discover data (including and beyond Dimensions), thethinking behind the Rich Context project can overcome currentinfrastructural challenges to significantly extend the contextualisationof datasets. The number and variety of datasets in use in academia willcertainly expand in the future, and we can only see data becoming evenmore central to contemporary research efforts. As such, it is criticalto invest in robust infrastructures, not only to support the productionand sharing of these data, but also to change the culture and evaluativeenvironment around research data. It is only through initiatives such asthese that we will be able to solve the vast and complex sociotechnicalchallenges that face academia today.[^1]: Support.datacite.org. (2019). *DataCite Metadata Schema 4.0*.    \[online\] Available at: https://support.datacite.org/docs/schema-40    \[Accessed 1 Jul. 2019\].[^2]: Linek SB, Fecher B, Friesike S, Hebing M (2017) Data sharing as    social dilemma: Influence of the researcher's personality. PLOS ONE    12(8): e0183216. doi: 10.1371/journal.pone.0183216[^3]: Treadway, J., Hahnel, M., Leonelli, S., Penny, D., et al.    (2016) The State of Open Data Report. \[Online\]. Available from:    doi:10.6084/m9.figshare.4036398.v1 \[Accessed: 1 July 2019\].[^4]: Siddle, J. (2019). *I Know Where You Were Last Summer: London\'s    public bike data is telling everyone where you\'ve been*. \[online\]    Vartree.blogspot.com. Available at:    https://vartree.blogspot.com/2014/04/i-know-where-you-were-last-summer.html    \[Accessed 1 Jul. 2019\].[^5]: Li, N., Li, T. and Venkatasubramanian, S. (2007). t-Closeness:    Privacy Beyond k-Anonymity and l-Diversity. *2007 IEEE 23rd    International Conference on Data Engineering*.[^6]: Rdmtoolkit.jisc.ac.uk. (2019). *Research Data Management Toolkit    \| Jisc*. \[online\] Available at:    https://rdmtoolkit.jisc.ac.uk/plan-and-design/data-management-planning/    \[Accessed 1 Jul. 2019\].[^7]: Nnlm.gov. (2019). *Data Management Plan \| NNLM*. \[online\]    Available at: https://nnlm.gov/data/data-management-plan \[Accessed    1 Jul. 2019\].[^8]: Allen, L., Brand, A., Scott, J., Hlava, M., Altman, M., (2014)    Nature 508, 312--313. doi:10.1038/508312a.[^9]: Hook, D.W., Herzog, C. and Porter, S.j. (2018) Front. Res. Metr.    Anal. doi:10.3389/frma.2018.00023