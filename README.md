# AI-CHAT-ASSISSTANCE
AI chat assistant for Windows: explains slang, fixes your English, and suggests natural replies in any chat app. Python + PySide6, works with Gemini, OpenAI, Claude or local models. You always review and send manually.

A Windows desktop chat assistant for people who want to reply naturally in
online conversations, especially if English slang, grammar, or replying quickly
feels hard. It works alongside any chat app.

## What it does
- **Understands messages:** explains what an incoming message means, including
  slang like "ngl", "lowkey", "no cap", "cooked", and "pull up", based on context.
- **Suggests replies:** gives three natural options (casual, playful, friendly),
  or pick a tone like gamer, polite, confident, or professional.
- **Fixes your English:** correct grammar, make it natural or casual, shorten it,
  improve vocabulary, or explain your mistakes. It keeps your meaning and tone.
- **Auto-reply on copy:** select a message in your chat app, press Ctrl+C, and
  replies appear in SayRight.
- **Live Watch (optional):** watch a chat area you choose and get replies when a
  new message appears (needs a vision-capable model).

## Privacy and safety
- SayRight never sends messages for you. You copy a reply and send it yourself.
- It doesn't log in to your chat accounts or touch the chat app's data.
- Text is sent to your chosen AI provider only when you click an action or
  turn on auto-reply or Live Watch, and the app tells you where it goes.
- API keys are stored locally, never hardcoded, shown, or logged.
- Pause or stop any time. Live Watch stops itself after repeated errors.

## Tech
Python 3.10+, PySide6, any OpenAI-compatible API (OpenAI, Gemini, OpenRouter,
Ollama, LM Studio) or Anthropic. Tested with pytest.
