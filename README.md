# SayBoard

A free, offline AAC (augmentative and alternative communication) board that runs in any modern browser. Built by Audrey Pham, Communication Sciences and Disorders student at Cal State Fullerton.

**Live app:** https://audreypham2007-spec.github.io/sayboard/

## Why
Dedicated AAC devices and apps are expensive, and many families wait months for insurance approval. SayBoard runs on the tablets and Chromebooks schools already have, costs nothing, and keeps all data on the device.

## Features
- **About 640 words.** A fixed home board of 70 core words and 10 folders, plus 14 more folders (actions, describing, drinks, colors, numbers, time, weather, health, chat, home things, vehicles, church, holidays, questions). Buttons never move, so motor memory stays stable.
- **Classic AAC picture symbols on every button** from ARASAAC, the open AAC symbol library. Any button can use your own photo.
- **Word endings:** +s, +ing, +ed, +er, +est, with common irregular words (go becomes went).
- **Recent:** every spoken sentence is saved so it can be said again with one tap.
- **Phrases:** quick whole sentences like "I want more" and "play with me."
- **Hey! button:** a chime plus "excuse me" to get attention.
- **Switch scanning:** rows, then buttons, light up in turn. Select with a switch mapped to Space or Enter, or by tapping anywhere.
- **Modeling mode for adults:**
  - Type a word and numbered steps light up the path to it (Step 1: More folders, Step 2: Drinks, Step 3: juice).
  - Type a short sentence and press Show me: the app plays each word's path and says the sentence.
  - Partner taps: adult taps speak but stay out of the child's message.
  - "Try modeling next" suggestions expand the child's last word (more becomes "want more", "more juice").
  - A daily count of words modeled, a starred word of the week, and rotating caregiver tips.
- **Button color schemes:** Classic, Bright, Soft pastel, and Candy, plus dark and high contrast themes.
- **Color by word type.** People words, actions, describing words, things, social words, and questions each have a color band, plus text labels for colorblind users.
- **Sentence strip.** Tap words to build a sentence, tap the strip to speak it.
- **Two languages.** Add Spanish or Vietnamese labels on every button. Switch the spoken language with one tap. Mixing languages in one sentence is allowed.
- **Modeling mode.** Adults search for a word and the path to it lights up, so they can model while they talk.
- **Quick boards.** Help and pain (with body parts), a 1 to 5 feelings scale, and "fix it" phrases for repairing misunderstandings.
- **Typing board** with word prediction for spellers.
- **Edit mode behind a PIN** (default 1234). Change words, emoji, colors, add family photos, hide words without moving them, add new buttons to folders.
- **Touch support.** Optional hold-to-select for users who tap by accident. Large-button layouts.
- **Themes.** Light, dark, and high contrast. Plain, high-legibility system font.
- **Private word counts.** Optional, stored only on the device, downloadable as CSV for the SLP.
- **Backup and share** a board as a file. Print any board as a paper backup.
- **Works offline** after the first visit, and installs like an app (Add to Home Screen).

## Notes
- SayBoard is a communication tool, not therapy. Set it up with a speech-language pathologist.
- Symbols are your device's emoji, so they look slightly different on Apple, Android, and Windows.
- Spanish and Vietnamese labels are a starting point. Have a native speaker review them and edit any word in Edit mode.
- Voices come from the device. If a language has no voice, add one in the device's speech settings.

## Run locally
Open `index.html` through any local web server, for example `python -m http.server`, then visit http://localhost:8000.

## License
Code: MIT. See LICENSE.

Picture symbols (`symbols/a_*.png`): the pictographic symbols used are the property of the Government of Aragón and have been created by Sergio Palao for ARASAAC (https://arasaac.org), which distributes them under a Creative Commons license BY-NC-SA 4.0. Because of this license, SayBoard is free and non-commercial.

Files starting with `p_` in `symbols/` are original SayBoard pictograms (MIT). Files starting with `m_` are Mulberry Symbols by Steve Lee, CC BY-SA 4.0.

## New in version 7
- Dedicated-device look: dark frame, icon-over-label toolbar, black gaps between buttons.
- 1,461 buttons in 56 boards, with folders inside folders (Food > Fruit, Vegetables, Snacks, Meals, Kitchen, Restaurant).
- Home page sizes: Core 40 (beginner), Core 80, Core 120.
- Hold a word for its other forms: go, goes, going, went, gone, to go. Pronouns: I, me, my, mine, myself.
- Little words board for grammar: the, a, to, was, will, can't, didn't, and more.
- Tools: First / Then, visual timer, schedule, choice board, photo scenes with tap spots, big text display with partner flip.
- Show and Copy buttons on the message bar.
- Vocabulary builder hides words without moving any button.
- Button styles (filled, border, color band), label above or below, picture only or word only, word size.
- Voice pitch, volume, and clear-after-speaking.

## New in version 8
- TV and movies: 8 new boards with about 200 buttons. Toy Story, Disney friends, Princesses, Pixar movies, Kids shows, Heroes and movies, and Video games, plus words for watching (pause, again, louder, my favorite is). Open it from Play or from More.
- 12 more sections with about 270 buttons: Money, Jobs, Bugs, Sea animals, Pets, Tools, Party, Space, Chores, Travel, World food, and Pretend. Each opens from More and from its parent folder (Jobs is inside People, World food is inside Food).
- 1,964 buttons in 78 boards.
- Character buttons use a matching ARASAAC symbol where one fits (Rex has the dinosaur) and an emoji where none does. The real character pictures are copyrighted, so they are not included. Add your own picture to any button in Edit mode.
