# QBRAG: QnA Boosted RAG with Vectara

Company's knoweldge bases often times don't answer the wide variety of questions a user could come up with.
A Customer Support system ideally could answer specific (but wide variety) questions about the company's systems and knowledge (example: "How can I enter Cash Flow in ThruThink?"). But sometimes the user asks geenric questions, such as "What is Cash Flow?" which could be sourced from the mind of a giant LLM model and / or the internet.

My idea is to help and boost the performance by leveraing Question and Answer geenration techniques normally used for fine tuning. The generated questions could support specific user queries potentially better matching than a "non focused" indexed generic knowedge base.

Steps taken:
1. I modified https://github.com/nestordemeure/question_extractor open source project to be able to run on AnyScale instead of OpenAI for QnA geenration. I toned it down to not hit rate limits as much. I also developed a capability for this project to continue a long running interrupted QnA generation session (it can take many hours with default rate limits on both OpenAI or AnyScale). See my open repository https://github.com/CsabaConsulting/question_extractor
2. I developed a script which can convert the OpenAI / AnyScale standard format fine tuning `jsonl` into a set of files for vectara indexing. The script breaks apart the `questions.jsonl` into the files beased on which file the questions originally sourced from. This will help Vectara indexing metadata. For the conversion see the https://github.com/CsabaConsulting/Vectara/blob/main/augment_prep.py script. This is somewhat analogous to augmenting extra data in AI/ML cases, since we generate the QnA from the knowledge base we already have.
3. Vectara upload scripts in a form of IPython Notebooks, see `Upload*.ipynb` files in this repository.
4. I leverage vectara's React based application to power and host the ThruThink Support Chat Agent. The software is capable of multi corpus filtering. See the details in the separate open source https://github.com/CsabaConsulting/vectara-answer repository
5. I host the application on Render: https://thruthink-support.onrender.com (fallback https://thruthink-vectara-first.onrender.com).

See all related scripts and materials are in this repository.
Future plan: evaluate RAG Fusion how that affects the project (answer quality, latency, ...).
