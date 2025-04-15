cat << 'EOF' > README.md
# MatchFlow.AI

Welcome to **MatchFlow**, a project built out of passion for rugby, AI, and storytelling.

This is the start of something that could turn into a real product. The idea is simple but powerful: transform structured game stats into full narrative recaps in the style of a coach’s email — and eventually go from **audio → stats → recap**. With my rugby coach’s blessing and his connections, there’s huge potential here. Right now, I’m focused on building the first piece.

## What this project does

- Input: Structured rugby match data (team, scorers, big moments)
- Output: A natural language game recap (like Coach Tony’s incredible post-match emails)

Eventually, the goal is to:
- Transcribe audio from coaches into structured game data
- Parse it, extract the relevant info
- Generate a personalized, emotional, and fact-based recap

## Why I'm doing this

Besides being my final project for my Topics in AI class, this is something I really believe in. I want to use this opportunity to build something real — something that could support athletes, coaches, and fans in a way that blends data and emotion.

If it never takes off, cool. I'll still learn a ton. But if it does... well, I’m all in.

## Current Status

- [x] Collected 27 coach recap emails for training
- [ ] Parse structured input and recap text from email files
- [ ] Fine-tune a T5 model using Hugging Face
- [ ] Generate recaps from structured input
- [ ] Build MVP flow from text input → recap output

## Technologies

- Python
- Hugging Face Transformers
- Google Colab / VSCode
- Pandas / Regex / spaCy (for parsing)

## Next Milestones

1. Clean and structure training data
2. Build training-ready dataset
3. Fine-tune a model on recap style
4. Build a prototype interface (Streamlit or Flask)

## Acknowledgements

Big thanks to Coach Tony for allowing me to use his emails, sharing game data, and pitching a business vision I never expected. Appreciate the belief.

EOF
