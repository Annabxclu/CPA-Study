# CPA Study Hub

A single-page study app for the CPA exam, organized by section — **AUD, FAR, REG** (core) and **BAR, ISC, TCP** (discipline). Each section keeps its own cards, questions, review schedule and progress.

## Study strategies
- **Spaced review**: Leitner-style scheduling (Again / Hard / Good / Easy)
- **Flashcards**: flip and sort into "got it" / "still learning"
- **Multiple choice**: instant feedback and explanations; flashcards can be turned into MC questions
- **Exam simulation**: timed testlet with flagging and a review grid
- **Active recall**: type the answer before revealing it
- **Match**: timed term–definition pairing game
- **Weak spots**: drills only what you've missed
- **Teach it back**: Feynman-style explanation with a self-check list

Also: **questions from a page** (screenshot up to 3 textbook pages and Claude writes MC questions or flashcards from them; claude.ai version only), **fill from screenshot** (snap a question or card and the form fills itself in), create/edit flashcards and MC questions, import from Quizlet (tab-separated export), copy cards out as text, per-topic accuracy, streaks, and a Pomodoro focus timer.

## Running it
Open `index.html` in a browser, or enable GitHub Pages for this repo. Opened this way, progress is saved in your browser's local storage. On GitHub Pages, "Fill from screenshot" reads the text with on-device OCR (Tesseract.js) and you pick the correct answer; on claude.ai, Claude reads the image and also detects or works out the answer. The "Generate with Claude", "Explain this more" and teach-back feedback features, plus saving to your account, only work in the hosted claude.ai version.
