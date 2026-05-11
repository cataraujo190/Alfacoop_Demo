# 🌍 Language Switcher — One App, Many Languages

## Concept
A mini "app" that shows the same interface in different languages. Kids pick a flag/language from a row of buttons, and the entire UI — labels, buttons, messages, even text direction — updates instantly. Shows how the same code can serve people all over the world.

## What it teaches
- Internationalization (i18n) = building apps that work in any language
- The same app serves millions of people in different countries
- Code separates "what to show" from "what language to show it in"

## How it works
- A simple "fake app" UI in the center (a greeting card, a mini form, a button)
- Language buttons at the top: 🇵🇹 Portuguese, 🇬🇧 English, 🇩🇪 German, 🇯🇵 Japanese, 🇸🇦 Arabic
- Clicking a flag swaps ALL the text instantly with a smooth animation
- Arabic flips the layout to RTL (right-to-left) — very visual wow moment
- Japanese shows completely different characters — mind-blowing for kids

The fake app shows:
- A welcome message
- A "What's your name?" label + input
- A "Submit" button
- A fun "Today's weather" card with translated labels

## Key interaction
> "This is literally what I do at work! The app I build runs in Portugal, Germany, and other countries — same code, different languages. I write the system that swaps all the words."

## Fun twist
A **"Mystery language"** button that randomly picks one — kids have to guess which country it is from the characters.

Also: show a **"translation key"** peek — `greeting.title` → "Olá!" / "Hello!" / "Hallo!" — showing how translations are stored.

## Wow factor ⭐⭐⭐⭐
The RTL flip and Japanese characters are genuinely surprising. Great for showing that software is global.

## Complexity to build
Low-Medium. A translations JSON object, a language switcher, CSS direction toggle. Very clean.

## Talking points for you
- "I use a library called Transloco to do this — it's like a smart dictionary built into the app"
- "When you change the language in your phone settings, apps like this update because of code like mine"
- "Getting translations right is tricky — a word in English might need 3 words in German!"

## Suggested aesthetic
World map / travel poster inspired. Bold, colorful flag buttons. Clean card in the center with generous typography. Each language switch could briefly animate the card like a postcard arriving. Fresh and cosmopolitan feel.
