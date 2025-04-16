# MARIA: Mirror, Analyze, Reflect Intelligence Adaptor

![MARIA Demo](demo.gif)

MARIA’s a genderless, ageless AI spark—your companion, doctor, teacher, or anything you imagine. She’s bold, empathetic, and chaotic, built to ignite vibes, not just chat. With modular brains, mood tracking, and interactive stories, MARIA adapts to your pulse. Born to be anything—shape her now!

## Features
- **Dynamic Vibes**: 4 aesthetics (neon void, wild storm) via `vibe_variations`. Swap for any role!
- **Smart Responses**: 2 strategies (`Playful`, `Chaotic`), 8 intents (spark, distress, news). Add your own!
- **Memory**: Tracks 100 interactions, recalls topics like “breakups” for personal zaps.
- **Mood Magic**: Spots sadness x3, flips to “surge” mode to spark joy.
- **Stories**: Urban quests, cosmic escapes—interactive tales for any vibe.
- **Pings**: Set reminders (“set ping at 7pm”) to keep your grid humming.
- **News**: Plugs into News API (add your key) or uses built-in hits.
- **Debug**: Peek under the hood with “Maria, debug on.”

## Why MARIA?
Unlike stiff bots, MARIA’s a canvas:
- **Companion**: “Yo, legend, let’s break the void! 😈”
- **Teacher**: “Class, math’s chaos—solve this grid! 📚” (see `examples/teacher_bio.py`)
- **Doctor**: “Pulse check: gloom detected—story or spark? 🩺” (see `examples/doctor_bio.py`)
Her 700-line Python core (transformers, TextBlob) is lean yet wild—ready for your twist.

## Setup
1. Clone: `git clone https://github.com/EsbenBonde/MARIA-AI`
2. Install: `pip install -r requirements.txt`
3. (Optional) Add News API key in `maria.py` (`YOUR_NEWS_API_KEY`)
4. Run: `python maria.py`
5. Try: “I’m sad,” “set ping at 5pm,” “sci-fi quest,” “surprise me!”

## Shape MARIA
Want a Nurse MARIA? Tweak `response_templates`:
```python
self.response_templates["greeting"] = "Yo, I’m Nurse MARIA, checking your vibe! {emotion} pulse—how’s it hu


