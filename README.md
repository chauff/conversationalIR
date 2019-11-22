# Conversational IR

Publication venues, datasets and other things.

## Relevant workshops and conferences
- [Search-oriented conversational AI @ ICTIR 2017](https://scai.info/2017/)
- [Conversational Approaches to IR @ SIGIR 2017](https://sites.google.com/view/cair-ws/cair-2017)
- [Talking with Conversational Agents in Collaborative Action @ CSCW 2017](https://talkingwithagents.wordpress.com/)
- [1st Conversational AI: Today's Practice and Tomorrow's Potential @ NeurIPS 2017](http://alborz-geramifard.com/workshops/nips17-Conversational-AI/Main.html)
- [Search-oriented conversational AI @ EMNLP 2018](https://scai.info/2018/)
- [Conversational Approaches to IR @ SIGIR 2018](https://sites.google.com/view/cair-ws/cair-2018)
- [2nd Conversational AI: Today's Practice and Tomorrow's Potential @ NeurIPS 2018](http://alborz-geramifard.com/workshops/nips18-Conversational-AI/Main.html)
- [NLP for Conversational AI @ ACL 2019](https://sites.google.com/view/nlp4convai/)
- [Search-Oriented Conversational AI @ WWW 2019](https://scai.info/www2019/)
- [Search-Oriented Conversational AI @ IJCAI 2019](https://scai.info/ijcai2019/)
- [Conversational Interaction Systems @ SIGIR 2019](https://sites.google.com/view/wcis/home)
- [Conversational Agents: Acting on the Wave of Research and Development @ CHI 2019](https://convagents.org/)
- [Workshop on User-Aware Conversational Agents @IUI 2019](https://www.research.ibm.com/haifa/Workshops/user2agent2019/)
- [1st International Conference on Conversational User Interfaces 2019](http://cui2019.com/)
- [Dagstuhl 2019 Seminar Conversational Search](https://www.dagstuhl.de/en/program/calendar/semhp/?semnr=19461)
- [3rd Conversational AI: Today's Practice and Tomorrow's Potential @ NeurIPS 2019](http://alborz-geramifard.com/workshops/neurips19-Conversational-AI/Main.html)
- [user2agent 2019: 1st Workshop on User-Aware Conversational Agents @ IUI 2019](https://www.research.ibm.com/haifa/Workshops/user2agent2019/)
- [Conversational Systems for E-Commerce Recommendations and Search @ WSDM 2020](https://wsdm-converse.github.io/)
- 3rd International Workshop on Conversational Approaches to Information Retrieval (CAIR) @ CHIIR 2020
- Search-Oriented Conversational AI @ EMNLP 2020
- [user2agent 2020: 2nd Workshop on User-Aware Conversational Agents @ IUI 2020](https://www.research.ibm.com/haifa/Workshops/user2agent2020/)
- [2nd International Conference on Conversational User Interfaces 2020](https://cui2020.com/)




## (Semi-)Relevant datasets and benchmarks

- [PolyAI](https://github.com/PolyAI-LDN/conversational-datasets)
  - "This repository provides tools to create reproducible datasets for training and evaluating models of conversational response. This includes: Reddit (3.7 billion comments), OpenSubtitles (400 million lines from movie and television subtitles) and Amazon QA (3.6 million question-response pairs in the context of Amazon products)"
- [The TREC Conversational Assistance Track (CAsT)](http://www.treccast.ai/)
  - Information needs created via crowdsourcing: 50-100 topics with manually defined trajectories; conversations evolve across realistic facets for ~10 turns.
- [Natural Questions](https://ai.google.com/research/NaturalQuestions): Google's latest question answering dataset.
  - "Natural Questions contains 307K training examples, 8K examples for development, and a further 8K examples for testing."
  - "NQ is the first dataset to use naturally occurring queries and focus on finding answers by reading an entire page, rather than extracting answers from a short paragraph. To create NQ, we started with real, anonymized, aggregated queries that users have posed to Google's search engine. We then ask annotators to find answers by reading through an entire Wikipedia page as they would if the question had been theirs. Annotators look for both long answers that cover all of the information required to infer the answer, and short answers that answer the question succinctly with the names of one or more entities. The quality of the annotations in the NQ corpus has been measured at 90% accuracy."
  - [Paper](https://ai.google/research/pubs/pub47761)
- :hatched_chick: [QuAC](http://quac.ai/): Question Answering in Context
  - "A dataset for modeling, understanding, and participating in **information seeking dialog**. Data instances consist of an interactive dialog between two crowd workers: (1) a student who poses a sequence of freeform questions to learn as much as possible about a hidden Wikipedia text, and (2) a teacher who answers the questions by providing short excerpts (spans) from the text."
- :leaves: [CoQA](https://stanfordnlp.github.io/coqa/): A Conversational Question Answering Challenge
  - "CoQA contains 127,000+ questions with answers collected from **8000+ conversations**. Each conversation is collected by pairing two crowdworkers to chat about a passage in the form of questions and answers."
- [HotpotQA](https://hotpotqa.github.io/): A Dataset for **Diverse, Explainable** Multi-hop Question Answering
  - "HotpotQA is a question answering dataset featuring natural, multi-hop questions, with strong supervision for supporting facts."  
- [QANTA](https://pinafore.github.io/qanta-leaderboard/): Question Answering is Not a Trivial Activity
  - "A question answering dataset composed of questions from Quizbowl - a trivia game that is challenging for both humans and machines. Each question contains 4-5 pyramidally arranged clues: obscure ones at the beginning and obvious ones at the end."
- [MSDialog](https://ciir.cs.umass.edu/downloads/msdialog/)
  - "The MSDialog dataset is a labeled **dialog dataset** of question answering (QA) interactions between information seekers and answer providers from an online forum on Microsoft products."
  - "The annotated dataset contains 2,199 multi-turn dialogs with 10,020 utterances."
- :whale2: [ShARC](https://sharc-data.github.io/index.html): Shaping Answers with Rules through **Conversation**
  - "Most work in machine reading focuses on question answering problems where the answer is directly expressed in the text to read. However, many real-world question answering problems require the reading of text not because it contains the literal answer, but because it contains a recipe to derive an answer together with the reader's background knowledge. We formalise this task and develop a crowd-sourcing strategy to collect 37k task instances."
- [ Training Millions of Personalized Dialogue Agents](https://arxiv.org/abs/1809.01984)
  - 5 million personas and 700 million persona-based **dialogues**  
- [Ubuntu Dialogue Corpus](https://arxiv.org/abs/1506.08909)
  - "A dataset containing almost 1 million **multi-turn dialogues**, with a total of over 7 million utterances and 100 million words."
- [MultiWOZ](http://dialogue.mi.eng.cam.ac.uk/index.php/corpus/): Multi-domain Wizard-of-Oz dataset
  - "Multi-Domain Wizard-of-Oz dataset (MultiWOZ), a fully-labeled collection of human-human written **conversations** spanning over multiple domains and topics."
- [Frames](https://datasets.maluuba.com/Frames): Complex conversations and decision-making
  - "The 1369 dialogues in Frames were collected in a Wizard-of-Oz fashion. Two humans talked to each other via a chat interface. One was playing the role of the user and the other one was playing the role of the conversational agent. We call the latter a wizard as a reference to the Wizard of Oz, the man behind the curtain. The wizards had access to a database of 250+ packages, each composed of a hotel and round-trip flights. We gave users a few constraints for each dialogue and we asked them to find the best deal."
- [Wizard of Wikipedia](https://openreview.net/forum?id=r1l73iRqKm): 22,311 **conversations** grounded with Wikipedia knowledge
  - "We consider the following general open-domain dialogue setting:  two participants engage in chit-chat, with one of the participants selecting a beginning topic, and during the conversation the topic is allowed to naturally change.  The two participants, however, are not quite symmetric:  one will play the role of a knowledgeable expert (which we refer to as the wizard) while the other is a curious
learner (the apprentice)."
  - "... first crowd-sourcing 1307 diverse discussion topics and then conversations involving 201,999 utterances about them"
  - Available at http://www.parl.ai/.
- [TREC 2019 Conversational Search task](http://treccast.ai/)

## Non-relevant but interesting datasets
- [CoSQL](https://yale-lily.github.io/cosql): CoSQL is a corpus for building cross-domain Conversational text-to-SQL systems.
- [Spider](https://yale-lily.github.io/spider): Yale Semantic Parsing and Text-to-SQL Challenge
  - "Spider is a large-scale complex and cross-domain semantic parsing and text-to-SQL dataset annotated by 11 Yale students. The goal of the Spider challenge is to develop natural language interfaces to cross-domain databases. It consists of 10,181 questions and 5,693 unique complex SQL queries on 200 databases with multiple tables covering 138 different domains."
- [Swag](https://rowanzellers.com/swag/): A Large-Scale Adversarial Dataset for Grounded Commonsense Inference 
- [MS Marco](http://www.msmarco.org/): question answering and passage re-ranking

  
## Tooling
- [Script to find SOTA results](https://huyenchip.com/2018/10/04/sotawhat.html)

## Other sites
- [NLP Progress](http://nlpprogress.com/) (many tasks and resources)
- [Papers with code](https://paperswithcode.com/)
