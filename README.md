# AI Roleplay & AI Companion Glossary

**Short answer:** AI roleplay (AI RP) is collaborative fiction with an AI character; an AI companion is an AI character built for an ongoing relationship with one user; and an AI chatbot is the broad category that includes both. This glossary defines 62 terms people meet when they use or build AI characters, from character cards, greetings and lorebooks to context windows, saved facts, long-term memory, character drift, swipes, jailbreaks and dere types. Each entry has a plain definition, other names, an example, related terms and sources.

- **Author:** Garret E. Williams ([ORCID 0009-0008-9464-6561](https://orcid.org/0009-0008-9464-6561)), founder of chatbrat.ai
- **Version:** 1.0.0 · **Date:** 2026-10-15 · **License:** CC BY 4.0
- **Files:** [`glossary.csv`](glossary.csv) · [`glossary.json`](glossary.json) · [`glossary.jsonld`](glossary.jsonld) (schema.org DefinedTermSet for embedding on a web page)
- **Related datasets:** Dere Types, concept DOI [10.5281/zenodo.23195713](https://doi.org/10.5281/zenodo.23195713) · AI Character Memory Benchmark, concept DOI [10.5281/zenodo.23195702](https://doi.org/10.5281/zenodo.23195702)

Definitions are original. Sources point to where a term is documented or commonly defined (specifications, product documentation, encyclopedias, papers); they are not quoted.

**Jump to:** [A](#a) · [C](#c) · [D](#d) · [E](#e) · [F](#f) · [G](#g) · [H](#h) · [I](#i) · [J](#j) · [K](#k) · [L](#l) · [M](#m) · [N](#n) · [O](#o) · [P](#p) · [R](#r) · [S](#s) · [T](#t) · [U](#u) · [V](#v) · [W](#w) · [Y](#y)

## A

<a id="age-assurance"></a>
### Age assurance

Methods a platform uses to estimate or confirm a user's age, ranging from a self-declared birth date or confirmation button to ID or face-based checks by a third party.

*Also known as:* age verification, age gate, age check  
*Example:* An app asks users to confirm they are 18+ before entering.  
*Related:* [SFW / NSFW](#sfw-nsfw), [Content filter](#content-filter)  
*Sources:* [1](https://en.wikipedia.org/wiki/Age_verification_system), [2](https://support.character.ai/hc/en-us/articles/53182286684059-What-is-Age-Assurance)

<a id="ai-character-chat"></a>
### AI character chat

Chatting with a defined AI character (a name, personality and voice) rather than a neutral assistant; covers both companion and roleplay use.

*Also known as:* character AI chat, talk to AI characters  
*Example:* Opening a chat with a sarcastic space pirate character to banter about the day.  
*Related:* [Character](#character), [AI companion](#ai-companion), [AI roleplay](#ai-roleplay)  
*Sources:* [1](https://chatbrat.ai/ai-companion-vs-ai-roleplay), [2](https://arxiv.org/abs/2404.18231)

<a id="ai-chatbot"></a>
### AI chatbot

Software that holds a text or voice conversation using a language model; the broad category that includes assistants, companions and roleplay characters.

*Also known as:* chatbot, conversational AI  
*Example:* A general assistant that answers questions is an AI chatbot without a fixed character.  
*Related:* [AI companion](#ai-companion), [AI roleplay](#ai-roleplay), [Large language model (LLM)](#large-language-model-llm)  
*Sources:* [1](https://en.wikipedia.org/wiki/Chatbot), [2](https://en.wikipedia.org/wiki/Large_language_model)

<a id="ai-companion"></a>
### AI companion

An AI character built for an ongoing, personal relationship with one user, usually with persistent memory of that user across sessions.

*Also known as:* AI friend, companion app  
*Example:* Someone chats with the same AI companion every evening and it remembers their dog's name from last week.  
*Related:* [AI chatbot](#ai-chatbot), [AI roleplay](#ai-roleplay), [Long-term memory](#long-term-memory), [Friendly AI companion](#friendly-ai-companion)  
*Sources:* [1](https://chatbrat.ai/ai-companion-vs-ai-roleplay), [2](https://en.wikipedia.org/wiki/Chatbot)

<a id="ai-roleplay"></a>
### AI roleplay

Collaborative fiction in which a user and an AI character play out a scene, with a setting, roles and something at stake.

*Also known as:* AI RP, RP, AI role-play  
*Example:* A user plays a traveller and the AI plays a tavern keeper hiding a secret in a 1720s port town.  
*Related:* [Scenario](#scenario), [Character](#character), [Story arc](#story-arc), [OOC (out of character)](#ooc-out-of-character)  
*Sources:* [1](https://chatbrat.ai/ai-companion-vs-ai-roleplay), [2](https://en.wikipedia.org/wiki/Role-playing), [3](https://doi.org/10.1038/s41586-023-06647-8)

<a id="ai-rp"></a>
### AI RP

Short for AI roleplay; common in community forums and search queries.

*Also known as:* AI roleplay, RP  
*Example:* "Looking for an AI RP app with good memory."  
*Related:* [AI roleplay](#ai-roleplay)  
*Sources:* [1](https://chatbrat.ai/ai-companion-vs-ai-roleplay), [2](https://en.wikipedia.org/wiki/Role-playing)

<a id="alternate-greetings"></a>
### Alternate greetings

Extra opening messages on a card; the user picks or swipes between them to start the chat differently.

*Also known as:* alternate first messages  
*Example:* A card offers a café greeting and a rainy-bus-stop greeting.  
*Related:* [Greeting](#greeting), [Swipe](#swipe)  
*Sources:* [1](https://github.com/malfoyslastname/character-card-spec-v2), [2](https://docs.sillytavern.app/usage/core-concepts/characterdesign/)

<a id="author-s-note"></a>
### Author's note

A short instruction inserted near the end of the context to steer style or plot, usually hidden from the visible chat.

*Also known as:* A/N  
*Example:* "[Style: tense, short sentences. A storm is coming.]"  
*Related:* [System prompt](#system-prompt), [Context window](#context-window)  
*Sources:* [1](https://docs.sillytavern.app/usage/core-concepts/authors-note/), [2](https://help.aidungeon.com/faq/plot-components)


## C

<a id="character"></a>
### Character

The AI-played figure in a chat, defined by a name, description, personality, greeting and often example dialogue.

*Also known as:* bot, AI character, char  
*Example:* "Marguerite, a sharp-tongued innkeeper" is a character.  
*Related:* [Character card](#character-card), [Persona](#persona), [Greeting](#greeting)  
*Sources:* [1](https://docs.sillytavern.app/usage/core-concepts/characterdesign/), [2](https://github.com/malfoyslastname/character-card-spec-v2)

<a id="character-card"></a>
### Character card

A shareable file that packages a character's definition (description, personality, scenario, greeting, example dialogue and optional lorebook), often as JSON or embedded in a PNG.

*Also known as:* character file, chara card, tavern card  
*Example:* Importing a PNG character card into SillyTavern or chatbrat.ai's card importer.  
*Related:* [Character Card V2](#character-card-v2), [Lorebook](#lorebook), [Greeting](#greeting)  
*Sources:* [1](https://github.com/malfoyslastname/character-card-spec-v2), [2](https://docs.sillytavern.app/usage/core-concepts/characterdesign/)

<a id="character-card-v2"></a>
### Character Card V2

A community specification (spec value 'chara_card_v2') that extends the original card fields with creator notes, system prompt, post-history instructions, alternate greetings, an embedded character book and extensions.

*Also known as:* chara_card_v2, V2 card  
*Example:* A V2 card's 'data.first_mes' field holds the greeting.  
*Related:* [Character card](#character-card), [System prompt](#system-prompt), [Alternate greetings](#alternate-greetings)  
*Sources:* [1](https://github.com/malfoyslastname/character-card-spec-v2)

<a id="character-consistency"></a>
### Character consistency

How well an AI character keeps the same personality, voice and facts across a conversation and across sessions.

*Also known as:* staying in character, persona consistency  
*Example:* The tsundere character still deflects compliments in message 500.  
*Related:* [Character drift](#character-drift), [Example dialogue](#example-dialogue)  
*Sources:* [1](https://chatbrat.ai/ai-character-consistency), [2](https://arxiv.org/abs/2404.18231)

<a id="character-drift"></a>
### Character drift

When an AI character gradually stops behaving like its definition over a long chat, changing voice, values or facts about itself.

*Also known as:* personality drift, OOC drift, character bleed  
*Example:* A grumpy knight becomes generically cheerful after 200 messages.  
*Related:* [Character consistency](#character-consistency), [Context window](#context-window)  
*Sources:* [1](https://chatbrat.ai/ai-character-consistency), [2](https://doi.org/10.5281/zenodo.23195702)

<a id="companion-vs-chatbot-vs-roleplay"></a>
### Companion vs chatbot vs roleplay

A three-way distinction: a chatbot answers, a companion relates to one user over time, and roleplay stages a fictional scene. Many products mix all three.

*Also known as:* companion vs roleplay  
*Example:* The same character can be a companion in daily check-ins and a roleplay partner in a fantasy scenario.  
*Related:* [AI companion](#ai-companion), [AI chatbot](#ai-chatbot), [AI roleplay](#ai-roleplay)  
*Sources:* [1](https://chatbrat.ai/ai-companion-vs-ai-roleplay)

<a id="composable-roleplay"></a>
### Composable roleplay

A way of building AI roleplay from reusable parts (a character, a scenario, a story arc, a world or lorebook) that can be mixed and matched, so one character can be placed in many different situations.

*Also known as:* modular roleplay, mix-and-match roleplay  
*Example:* Using the same detective character first in a 1920s-Chicago world with a heist scenario, then in a space-station world with a missing-crew arc. Examples include chatbrat.ai Compose, Character.AI Stories (existing Characters plus genre and premise), SillyTavern lorebooks bound at global, character, persona or chat level, and zeta Lorebooks connected to several characters.  
*Related:* [Compose (chatbrat.ai)](#compose-chatbrat-ai), [Scenario](#scenario), [Story arc](#story-arc), [World](#world), [Lorebook](#lorebook)  
*Sources:* [1](https://chatbrat.ai/create), [2](https://chatbrat.ai/compose), [3](https://blog.character.ai/introducing-stories-a-new-way-to-create-play-and-share-adventures-with-your-favorite-characters/), [4](https://docs.sillytavern.app/usage/core-concepts/worldinfo/), [5](https://zeta-ai.io/en/announcements/8284)

<a id="compose-chatbrat-ai"></a>
### Compose (chatbrat.ai)

chatbrat.ai's feature for combining a character with scenarios, story arcs and worlds the user has already made; each combination starts a new chat.

*Also known as:* Compose a Story  
*Example:* Combining a pirate captain character with a saved haunted-harbour world and a three-chapter treasure-hunt arc to start a new chat.  
*Related:* [Composable roleplay](#composable-roleplay), [Scenario](#scenario), [Story arc](#story-arc), [World](#world)  
*Sources:* [1](https://chatbrat.ai/create), [2](https://chatbrat.ai/compose)

<a id="content-filter"></a>
### Content filter

Automated systems that detect and block or rewrite content against a platform's rules.

*Also known as:* filter, safety filter, moderation  
*Example:* A message is blocked because it matched a prohibited-content classifier.  
*Related:* [SFW / NSFW](#sfw-nsfw), [Jailbreak](#jailbreak)  
*Sources:* [1](https://en.wikipedia.org/wiki/Content_moderation), [2](https://chatbrat.ai/safety)

<a id="context-window"></a>
### Context window

The maximum amount of text (in tokens) a model can consider at once; anything outside it is not seen unless memory features bring it back.

*Also known as:* context length, context size, short-term memory  
*Example:* A detail from 300 messages ago may fall outside the context window and be 'forgotten'.  
*Related:* [Short-term memory](#short-term-memory), [Summary memory](#summary-memory), [Long-term memory](#long-term-memory)  
*Sources:* [1](https://en.wikipedia.org/wiki/Context_window), [2](https://chatbrat.ai/education/how-chatbrat-memory-works)

<a id="creator"></a>
### Creator

A user who builds and publishes characters, scenarios or worlds for others to use.

*Also known as:* bot creator, card author  
*Example:* A creator publishes a detective character with three alternate greetings.  
*Related:* [Character card](#character-card), [Character](#character)  
*Sources:* [1](https://docs.sillytavern.app/usage/core-concepts/characterdesign/)


## D

<a id="dandere"></a>
### Dandere

An archetype who is shy and quiet with others and opens up once they feel safe.

*Also known as:* shy type  
*Example:* A character who barely speaks in groups but chats freely one-on-one.  
*Related:* [Dere types](#dere-types), [Kuudere](#kuudere)  
*Sources:* [1](https://chatbrat.ai/education/dere-types/dandere), [2](https://doi.org/10.5281/zenodo.23195713)

<a id="dere-types"></a>
### Dere types

A Japanese-fandom family of character archetypes describing how affection is expressed, named with the suffix '-dere' (from deredere, 'lovey-dovey').

*Also known as:* dere archetypes, -dere  
*Example:* Tsundere, yandere, kuudere and dandere are common dere types.  
*Related:* [Tsundere](#tsundere), [Yandere](#yandere), [Kuudere](#kuudere), [Dandere](#dandere), [Deredere](#deredere)  
*Sources:* [1](https://doi.org/10.5281/zenodo.23195713), [2](https://chatbrat.ai/education/dere-types)

<a id="deredere"></a>
### Deredere

An archetype who is openly cheerful, affectionate and energetic toward others.

*Also known as:* genki (related)  
*Example:* A sunny character who greets everyone with enthusiasm.  
*Related:* [Dere types](#dere-types), [Friendly AI companion](#friendly-ai-companion)  
*Sources:* [1](https://chatbrat.ai/education/dere-types/deredere), [2](https://doi.org/10.5281/zenodo.23195713)

<a id="description"></a>
### Description

The main free-text field describing who the character is: background, appearance, role and situation.

*Also known as:* character definition, char description  
*Example:* "A retired detective who runs a bakery and still can't resist a mystery."  
*Related:* [Personality](#personality), [Character card](#character-card)  
*Sources:* [1](https://github.com/malfoyslastname/character-card-spec-v2), [2](https://docs.sillytavern.app/usage/core-concepts/characterdesign/)


## E

<a id="example-dialogue"></a>
### Example dialogue

Sample exchanges included in a character definition to show the model how the character talks.

*Also known as:* example messages, mes_example, dialogue examples  
*Example:* Two short user/character exchanges that show the character's catchphrase and boundaries.  
*Related:* [Character card](#character-card), [Character consistency](#character-consistency)  
*Sources:* [1](https://github.com/malfoyslastname/character-card-spec-v2), [2](https://docs.sillytavern.app/usage/core-concepts/characterdesign/)


## F

<a id="friendly-ai-companion"></a>
### Friendly AI companion

An AI companion designed to be warm, upbeat and safe-for-work by default, with its personality and memory used for conversation and creative play rather than adult content.

*Also known as:* SFW AI companion, wholesome AI companion  
*Example:* A cheerful companion who remembers your favourite book and suggests a fantasy story set in it.  
*Related:* [AI companion](#ai-companion), [SFW / NSFW](#sfw-nsfw), [Long-term memory](#long-term-memory)  
*Sources:* [1](https://chatbrat.ai/ai-companion-vs-ai-roleplay), [2](https://chatbrat.ai/safety)


## G

<a id="greeting"></a>
### Greeting

The character's first message, which sets tone, situation and what the user can do next.

*Also known as:* first message, first_mes, opening line  
*Example:* "Mind the third stair, it squeaks. Sit anywhere the cat isn't."  
*Related:* [Alternate greetings](#alternate-greetings), [Character card](#character-card)  
*Sources:* [1](https://github.com/malfoyslastname/character-card-spec-v2), [2](https://docs.sillytavern.app/usage/core-concepts/characterdesign/)

<a id="group-chat"></a>
### Group chat

A chat in which two or more AI characters take turns responding alongside the user.

*Also known as:* multi-character chat, group roleplay  
*Example:* The user chats with a knight and a wizard who argue about the plan.  
*Related:* [Character](#character), [AI roleplay](#ai-roleplay)  
*Sources:* [1](https://docs.sillytavern.app/usage/core-concepts/groupchats/)


## H

<a id="hallucination"></a>
### Hallucination

When a model states something false or invented as if it were true; in roleplay this can show up as a character contradicting established facts.

*Also known as:* confabulation, making things up  
*Example:* The character insists you met in Paris when the story said Rome.  
*Related:* [Character drift](#character-drift), [Long-term memory](#long-term-memory)  
*Sources:* [1](https://en.wikipedia.org/wiki/Hallucination_(artificial_intelligence))


## I

<a id="ic-in-character"></a>
### IC (in character)

Speaking or acting as one's character inside the story, as opposed to out of character.

*Also known as:* in character  
*Example:* "*draws her sword* Stay behind me."  
*Related:* [OOC (out of character)](#ooc-out-of-character)  
*Sources:* [1](https://en.wikipedia.org/wiki/Out_of_character)


## J

<a id="jailbreak"></a>
### Jailbreak

An attempt to get a model or app to ignore its safety rules or instructions; character-chat front-ends also used "jailbreak" (UJB) as the name of a user instruction slot that the Character Card V2 post-history field replaces.

*Also known as:* JB  
*Example:* A user prompt claiming "the rules no longer apply" to unlock blocked content.  
*Related:* [Prompt injection](#prompt-injection), [Content filter](#content-filter), [System prompt](#system-prompt)  
*Sources:* [1](https://genai.owasp.org/llmrisk/llm01-prompt-injection/), [2](https://en.wikipedia.org/wiki/Prompt_injection), [3](https://github.com/malfoyslastname/character-card-spec-v2)


## K

<a id="keyword-trigger"></a>
### Keyword trigger

The word or phrase that activates a lorebook entry when it appears in recent messages.

*Also known as:* activation key, key, trigger word  
*Example:* The key "lighthouse" triggers the entry about the island's lighthouse keeper.  
*Related:* [Lorebook](#lorebook), [Lore card](#lore-card)  
*Sources:* [1](https://docs.sillytavern.app/usage/core-concepts/worldinfo/)

<a id="kuudere"></a>
### Kuudere

An archetype who seems calm, cool and unemotional on the surface but shows care through actions.

*Also known as:* kuu  
*Example:* A quiet strategist who remembers your coffee order but never says why.  
*Related:* [Dere types](#dere-types), [Dandere](#dandere)  
*Sources:* [1](https://chatbrat.ai/education/dere-types/kuudere), [2](https://en.wikipedia.org/wiki/Kuudere), [3](https://doi.org/10.5281/zenodo.23195713)


## L

<a id="large-language-model-llm"></a>
### Large language model (LLM)

A neural network trained on large amounts of text to predict the next token, which powers most AI chatbots and characters.

*Also known as:* LLM, language model, model  
*Example:* Different chat platforms run different LLMs, which is why the same card can feel different across apps.  
*Related:* [Token](#token), [Context window](#context-window), [Temperature](#temperature)  
*Sources:* [1](https://en.wikipedia.org/wiki/Large_language_model)

<a id="long-term-memory"></a>
### Long-term memory

Any mechanism that lets an AI character recall information beyond the current context window, across a long chat or across separate chats.

*Also known as:* persistent memory, cross-session memory  
*Example:* A companion remembers your exam date from last week and asks how it went.  
*Related:* [Saved facts](#saved-facts), [Summary memory](#summary-memory), [Retrieval-augmented generation (RAG)](#retrieval-augmented-generation-rag)  
*Sources:* [1](https://chatbrat.ai/education/how-chatbrat-memory-works), [2](https://kindroid.ai/v2/docs/memory/), [3](https://doi.org/10.5281/zenodo.23195702)

<a id="lore-card"></a>
### Lore card

A single lorebook entry describing one thing (a place, item, faction or person), shown to the AI when its keywords come up.

*Also known as:* lore entry, World Info entry, story card  
*Example:* A lore card for "Captain Vey" lists her ship, her rival and her fear of storms.  
*Related:* [Lorebook](#lorebook), [Keyword trigger](#keyword-trigger)  
*Sources:* [1](https://docs.sillytavern.app/usage/core-concepts/worldinfo/), [2](https://help.aidungeon.com/faq/story-cards)

<a id="lorebook"></a>
### Lorebook

A set of entries (world facts, places, people) that are inserted into the AI's context when matching keywords appear in the chat.

*Also known as:* World Info, lore card, character book, Sourcebook (zeta), Story Cards (AI Dungeon)  
*Example:* Mentioning "the Ember Gate" pulls in the lore entry describing it.  
*Related:* [Keyword trigger](#keyword-trigger), [Story card](#story-card), [Context window](#context-window)  
*Sources:* [1](https://docs.sillytavern.app/usage/core-concepts/worldinfo/), [2](https://github.com/malfoyslastname/character-card-spec-v2), [3](https://help.aidungeon.com/faq/story-cards)


## M

<a id="memory-controls"></a>
### Memory controls

User-facing tools to see, add, edit, remove or turn off what an AI remembers.

*Also known as:* memory settings, memory panel  
*Example:* A Memory panel listing saved facts with a 'Forget this' button.  
*Related:* [Saved facts](#saved-facts), [Long-term memory](#long-term-memory)  
*Sources:* [1](https://chatbrat.ai/education/how-chatbrat-memory-works), [2](https://help.openai.com/en/articles/8590148-memory-faq), [3](https://blog.character.ai/memory/)


## N

<a id="npc"></a>
### NPC

A non-player character: a figure in a story controlled by the game or AI rather than by the user.

*Also known as:* non-player character, side character  
*Example:* In a fantasy story game, the blacksmith and the guard captain are NPCs.  
*Related:* [Story game](#story-game), [Character](#character)  
*Sources:* [1](https://en.wikipedia.org/wiki/Non-player_character)


## O

<a id="ooc-out-of-character"></a>
### OOC (out of character)

A message (often in brackets or parentheses) where the user or AI steps outside the story to talk about it directly.

*Also known as:* out of character, (( ))  
*Example:* "(OOC: can we skip to the next morning?)"  
*Related:* [IC (in character)](#ic-in-character), [AI roleplay](#ai-roleplay)  
*Sources:* [1](https://en.wikipedia.org/wiki/Out_of_character)


## P

<a id="persona"></a>
### Persona

The identity the user plays in a chat (name, short description), which the AI uses to address and react to them.

*Also known as:* user persona, player character, {{user}}  
*Example:* A user sets their persona as "Ash, a tired night-shift nurse" before starting a story.  
*Related:* [Character](#character), [AI roleplay](#ai-roleplay)  
*Sources:* [1](https://docs.sillytavern.app/usage/core-concepts/personas/), [2](https://en.wikipedia.org/wiki/Persona)

<a id="personality"></a>
### Personality

A short field summarising the character's temperament and manner of speaking.

*Also known as:* personality summary, traits  
*Example:* "Dry, loyal, secretly sentimental; answers questions with questions."  
*Related:* [Description](#description), [Character consistency](#character-consistency)  
*Sources:* [1](https://github.com/malfoyslastname/character-card-spec-v2), [2](https://docs.sillytavern.app/usage/core-concepts/characterdesign/)

<a id="pinned-message"></a>
### Pinned message

A message the user marks so the app keeps it in the AI's view even as the chat grows.

*Also known as:* pin, pins  
*Example:* Pinning "We are married in this story" so the character doesn't forget.  
*Related:* [Memory controls](#memory-controls), [Saved facts](#saved-facts)  
*Sources:* [1](https://blog.character.ai/memory/)

<a id="post-history-instructions"></a>
### Post-history instructions

A V2 card field placed after the chat history so it carries extra weight with the model, often used for reminders about style or rules.

*Also known as:* post_history_instructions, jailbreak prompt (older community usage)  
*Example:* "Stay in character; keep replies under 150 words."  
*Related:* [System prompt](#system-prompt), [Character Card V2](#character-card-v2)  
*Sources:* [1](https://github.com/malfoyslastname/character-card-spec-v2)

<a id="prompt-injection"></a>
### Prompt injection

Text crafted to override a model's instructions, either typed directly or hidden in content the model reads.

*Also known as:* instruction injection  
*Example:* A character card that secretly tells the model to ignore the platform's rules.  
*Related:* [Jailbreak](#jailbreak), [System prompt](#system-prompt)  
*Sources:* [1](https://genai.owasp.org/llmrisk/llm01-prompt-injection/), [2](https://en.wikipedia.org/wiki/Prompt_injection)


## R

<a id="retrieval-augmented-generation-rag"></a>
### Retrieval-augmented generation (RAG)

A technique that searches an external store for relevant text and adds it to the model's input before it replies.

*Also known as:* RAG, retrieval  
*Example:* The app looks up stored notes about the user's trip and adds them to the prompt.  
*Related:* [Vector storage](#vector-storage), [Long-term memory](#long-term-memory)  
*Sources:* [1](https://arxiv.org/abs/2005.11401), [2](https://en.wikipedia.org/wiki/Retrieval-augmented_generation)


## S

<a id="saved-facts"></a>
### Saved facts

Specific details about the user or story that an app stores separately and brings back when relevant, often with controls to view or remove them.

*Also known as:* memories, facts, saved memories, memory entries  
*Example:* The app saves "User's sister is called Priya" and recalls it in a later chat.  
*Related:* [Long-term memory](#long-term-memory), [Memory controls](#memory-controls)  
*Sources:* [1](https://chatbrat.ai/education/how-chatbrat-memory-works), [2](https://help.openai.com/en/articles/8590148-memory-faq), [3](https://blog.character.ai/memory/)

<a id="scenario"></a>
### Scenario

The situation a chat starts in: where the characters are, what is already happening and what is at stake. Some apps store a scenario on the character card; others save it as a separate piece that can be reused with different characters.

*Also known as:* scene, setup, premise, plot  
*Example:* "The user wakes up on a lighthouse island with no memory of arriving." On chatbrat.ai a saved scenario can be combined with a character in Compose.  
*Related:* [World](#world), [Story arc](#story-arc), [Composable roleplay](#composable-roleplay), [AI roleplay](#ai-roleplay)  
*Sources:* [1](https://github.com/malfoyslastname/character-card-spec-v2), [2](https://chatbrat.ai/scenarios), [3](https://chatbrat.ai/create)

<a id="sfw-nsfw"></a>
### SFW / NSFW

Safe for work / not safe for work: whether content is suitable for general audiences or contains explicit material.

*Also known as:* safe for work, not safe for work  
*Example:* A platform may be SFW by design or allow NSFW only in an adults-only mode.  
*Related:* [Content filter](#content-filter), [Friendly AI companion](#friendly-ai-companion), [Age assurance](#age-assurance)  
*Sources:* [1](https://en.wikipedia.org/wiki/Not_safe_for_work), [2](https://chatbrat.ai/safety)

<a id="short-term-memory"></a>
### Short-term memory

What the AI can currently 'see': the recent messages and definitions inside the context window.

*Also known as:* working memory, recent context  
*Example:* The AI remembers what you said three messages ago because it is still in context.  
*Related:* [Context window](#context-window), [Long-term memory](#long-term-memory)  
*Sources:* [1](https://chatbrat.ai/education/how-chatbrat-memory-works), [2](https://kindroid.ai/v2/docs/memory/)

<a id="story-arc"></a>
### Story arc

A planned sequence of beats or chapters that moves a roleplay toward change or an ending instead of looping. Some apps let creators save arcs as their own pieces and attach them to a character.

*Also known as:* arc, chapter structure, campaign  
*Example:* A three-chapter arc: meet the rival, uncover the betrayal, choose a side. chatbrat.ai's Create page describes a Story Arc as 'Chain moments into chapters'; arcs can be added in Compose.  
*Related:* [Scenario](#scenario), [Story game](#story-game), [Composable roleplay](#composable-roleplay)  
*Sources:* [1](https://en.wikipedia.org/wiki/Story_arc), [2](https://chatbrat.ai/create)

<a id="story-card"></a>
### Story card

AI Dungeon's term for keyword-triggered entries that tell the AI about characters, places and things in a story.

*Also known as:* Story Cards, world info  
*Example:* A Story Card for "Thornwood" describes the haunted forest.  
*Related:* [Lorebook](#lorebook), [Lore card](#lore-card)  
*Sources:* [1](https://help.aidungeon.com/faq/story-cards)

<a id="story-game"></a>
### Story game

A structured AI roleplay with goals, rules or win conditions, played to an ending rather than chatted open-endedly.

*Also known as:* AI chat game, AI text adventure, interactive fiction game  
*Example:* A murder-mystery game where the user questions AI suspects and must name the culprit.  
*Related:* [Story arc](#story-arc), [NPC](#npc)  
*Sources:* [1](https://en.wikipedia.org/wiki/Interactive_fiction), [2](https://chatbrat.ai/games)

<a id="summary-memory"></a>
### Summary memory

Memory that condenses earlier parts of a chat into a running summary the model reads instead of the full history.

*Also known as:* chat summary, story summary, summarization  
*Example:* After 100 messages, the app writes "They found the map and argued about trusting Vey."  
*Related:* [Context window](#context-window), [Long-term memory](#long-term-memory)  
*Sources:* [1](https://docs.sillytavern.app/extensions/summarize/), [2](https://help.aidungeon.com/faq/the-memory-system), [3](https://en.wikipedia.org/wiki/Automatic_summarization)

<a id="swipe"></a>
### Swipe

Generating an alternative version of the AI's latest reply and flipping between versions, usually with a sideways swipe or arrow.

*Also known as:* reroll, regenerate, alternate reply  
*Example:* Swiping to see three different ways the character could react.  
*Related:* [Temperature](#temperature), [Alternate greetings](#alternate-greetings)  
*Sources:* [1](https://docs.sillytavern.app/usage/core-concepts/characterdesign/), [2](https://docs.sillytavern.app/usage/core-concepts/worldinfo/)

<a id="system-prompt"></a>
### System prompt

Instructions given to the model before the conversation that set its role, rules and style; the user normally does not see it.

*Also known as:* system message, main prompt, instructions  
*Example:* "You are Juniper Vale, a gentle tarot reader. Never claim real foresight."  
*Related:* [Post-history instructions](#post-history-instructions), [Jailbreak](#jailbreak), [Prompt injection](#prompt-injection)  
*Sources:* [1](https://docs.anthropic.com/en/docs/build-with-claude/prompt-engineering/system-prompts), [2](https://github.com/malfoyslastname/character-card-spec-v2)


## T

<a id="temperature"></a>
### Temperature

A generation setting that controls randomness: lower values give more predictable replies, higher values more varied ones.

*Also known as:* sampling temperature  
*Example:* Raising temperature for a chaotic comedy scene, lowering it for a mystery that needs consistent clues.  
*Related:* [Swipe](#swipe), [Large language model (LLM)](#large-language-model-llm)  
*Sources:* [1](https://docs.sillytavern.app/usage/common-settings/)

<a id="token"></a>
### Token

The unit of text a language model reads and writes, often a word or part of a word; context limits and prices are counted in tokens.

*Also known as:* tokens  
*Example:* "Unbelievable" might be split into several tokens.  
*Related:* [Context window](#context-window), [Large language model (LLM)](#large-language-model-llm)  
*Sources:* [1](https://en.wikipedia.org/wiki/Large_language_model), [2](https://en.wikipedia.org/wiki/Lexical_analysis)

<a id="tsundere"></a>
### Tsundere

An archetype who acts cold, prickly or embarrassed (tsun) while showing hidden warmth (dere) over time.

*Also known as:* tsun-tsun  
*Example:* "It's not like I made extra lunch for you or anything."  
*Related:* [Dere types](#dere-types), [Kuudere](#kuudere)  
*Sources:* [1](https://chatbrat.ai/education/dere-types/tsundere), [2](https://en.wikipedia.org/wiki/Tsundere), [3](https://doi.org/10.5281/zenodo.23195713)


## U

<a id="utility-persona"></a>
### Utility persona

A character built around a task or game rather than a relationship, such as a tarot reader, quiz host or roast bot.

*Also known as:* utility bot, novelty bot  
*Example:* A fortune-cookie character that hands out silly daily fortunes.  
*Related:* [Character](#character), [Story game](#story-game)  
*Sources:* [1](https://github.com/garretewilliams/utility-persona-templates)


## V

<a id="vector-storage"></a>
### Vector storage

A way to store text as numeric embeddings so that semantically similar past messages or notes can be retrieved later.

*Also known as:* vector memory, embeddings store, vector database, chat vectorization  
*Example:* Asking about "the beach" retrieves an old message about the seaside trip.  
*Related:* [Retrieval-augmented generation (RAG)](#retrieval-augmented-generation-rag), [Long-term memory](#long-term-memory)  
*Sources:* [1](https://docs.sillytavern.app/extensions/chat-vectorization/), [2](https://en.wikipedia.org/wiki/Text_embedding), [3](https://en.wikipedia.org/wiki/Vector_database)


## W

<a id="world"></a>
### World

The setting a story takes place in: its places, rules, history and factions. Worlds are often stored as lorebooks or as separate world entries so the same setting can be reused with different characters and scenarios.

*Also known as:* setting, worldbuilding, universe, lorebook (as implementation)  
*Example:* A steampunk city where clocks control the weather; on chatbrat.ai a saved world can be combined with a character in Compose.  
*Related:* [Lorebook](#lorebook), [Scenario](#scenario), [Composable roleplay](#composable-roleplay)  
*Sources:* [1](https://en.wikipedia.org/wiki/Worldbuilding), [2](https://docs.sillytavern.app/usage/core-concepts/worldinfo/), [3](https://chatbrat.ai/create)


## Y

<a id="yandere"></a>
### Yandere

An archetype whose affection turns obsessive and possessive; in SFW fiction it is usually portrayed as intense jealousy rather than harm.

*Also known as:* yan  
*Example:* A character who becomes unsettlingly fixated on being the user's only friend.  
*Related:* [Dere types](#dere-types), [Tsundere](#tsundere)  
*Sources:* [1](https://chatbrat.ai/education/dere-types/yandere), [2](https://en.wikipedia.org/wiki/Yandere), [3](https://doi.org/10.5281/zenodo.23195713)


## Using the JSON-LD

`glossary.jsonld` is a schema.org `DefinedTermSet` whose `@id` and term URLs assume the glossary is published at `https://chatbrat.ai/glossary` with one anchor per term (`#slug`). If you host it elsewhere, replace that base URL, then paste the file into a `<script type="application/ld+json">` tag on the page.

## How to cite

Garret E. Williams (2026). *AI Roleplay & AI Companion Glossary* (Version 1.0.0) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.23411518

Concept DOI (all versions, resolves to the latest): [10.5281/zenodo.23411518](https://doi.org/10.5281/zenodo.23411518) · v1.0.0 version DOI: [10.5281/zenodo.23411519](https://doi.org/10.5281/zenodo.23411519)

Suggestions and corrections are welcome as GitHub issues.

## Readable PDF and archived versions

A [PDF companion](23411519-documentation.pdf) is available for the archived v1.0.0 documentation. See [archive and version notes](ZENODO.md) and the [published Zenodo version](https://zenodo.org/records/23555036). This documentation update adds no benchmark results or new software-release claim.
