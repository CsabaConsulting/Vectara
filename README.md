# QBRAG: QnA Boosted RAG with [Vectara](https://vectara.com/)

A company's knowledge bases often don't answer the wide variety of questions a user could come up with.
A Customer Support system ideally could answer specific (but wide variety) questions about the company's systems and knowledge (example: *"How can I enter Cash Flow in ThruThink?"*). But sometimes the user asks generic questions, such as *"What is Cash Flow?"* which could be sourced from the mind of a giant LLM model and / or the internet.

My idea is to help and boost the performance by leveraging Question and Answer generation techniques - normally used for fine tuning but in this case - for knowledge base augmentation / indexing enrichment. The generated questions could support specific user queries potentially better matching than a "non focused" indexed generic knowledge base.

Notable achievements:
1. I modified https://github.com/nestordemeure/question_extractor open source project to be able to run on [AnyScale](https://www.anyscale.com/) instead of OpenAI for QnA generation. I toned it down to not hit rate limits as much. I also developed a capability for this project to continue a long running interrupted QnA generation session (it can take many hours with default rate limits on both OpenAI or AnyScale). See my open repository https://github.com/CsabaConsulting/question_extractor
2. I developed a script which can convert the OpenAI / [AnyScale](https://www.anyscale.com/) standard format fine tuning `jsonl` into a set of files for Vectara indexing. The script breaks apart the `questions.jsonl` into the files based on which file the questions originally sourced from. This will help Vectara indexing metadata. For the conversion see the https://github.com/CsabaConsulting/Vectara/blob/main/augment_prep.py script. This is somewhat analogous to augmenting extra data in AI/ML cases, since we generate the QnA from the knowledge base we already have.
3. Vectara upload scripts in a form of IPython Notebooks, see `Upload*.ipynb` files in this repository.
4. I leverage Vectara's React based application to power and host the ThruThink Support Chat Agent. The software is capable of multi corpus filtering. See the details in the separate open source https://github.com/CsabaConsulting/vectara-answer repository
5. I host the application on [Render](https://render.com/): https://thruthink-support.onrender.com (fallback https://thruthink-vectara-first.onrender.com).

See all related scripts and materials in this repository.
Future plan: evaluate [RAG Fusion](https://towardsdatascience.com/forget-rag-the-future-is-rag-fusion-1147298d8ad1) how that affects the project (answer quality, latency, ...).
The final application will be integrated into ThruThink which uses ASP.NET MVC / C# / Azure technology stack, but not open source. In that final deployment I'll be able to open up referred help topics using the meta-data I get back as part of the query results document references.

In the end the hackathon had an arc of a story which became full circle. I thought I may need RAG Fusion, but helping the indexing with extra documents and *"QnA boosting"* resulted in satisfiable outcome with the deployed instance in Render. (Earlier queries can be seen in the https://github.com/CsabaConsulting/Vectara/blob/main/QueryCorpus.ipynb and the https://github.com/CsabaConsulting/Vectara/blob/main/QueryCorpusWQnA.ipynb notebooks).
