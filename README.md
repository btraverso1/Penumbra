# Penumbra
**Everything I read, finally in one place.**

🔗 [btraverso1.github.io/penumbra](https://btraverso1.github.io/penumbra)

---

There is a moment every morning, before the day has an opinion about itself, that belongs entirely to me: Terrace. Coffee. News.

Half an hour, give or take. Not long enough, but long enough to matter.

The ritual has a problem. My notifications arrive like a press briefing with no agenda. Breaking news next to opinion pieces, Brussels next to Wall Street next to Madrid, the urgent buried under the interesting. I'd scroll, archive, tab-switch, lose the thread. By the time the coffee was cold I'd read two outlets and retained half of one.

What I actually wanted was simple: a broad picture of the world before the day began. Not depth (that comes later, on the stories worth pursuing). Just a clean read across everything I follow. EU policy, UK politics, Trade, Spain, Geopolitics. 

The apps that do this well cost money. The sources I trust most don't offer RSS. So I built my own.

Penumbra pulls live news by topic, tracks live legislation and consultations across the EU, UK, US and Spain and, when a story is worth going deeper, generates an AI analysis mapping the context, the stakeholders, the implications and the scenarios worth watching. The kind of questions I find myself asking anyway. Now they have answers before the second coffee.

Building this was genuinely fun. I use it every day, I tweak it constantly and there is always something to improve, a new source to add, a layout detail that bothers me, a feature that would make the morning read better. It is a living thing.

Yes, I could ask ChatGPT for a news summary every morning. I know (I do sometimes). But that was never the point. The point was to build something, to understand how things actually work under the hood and to see what people out there are really doing when they put these tools together. I tried APIs that turned out not to be free. I learned what CORS errors are. I exposed an API key to a public repository and had to delete the whole thing and start again. All of it was worth it.

What I find myself thinking about is what a proper system looks like. The professional platforms. The ones built for newsrooms, public affairs, government relations teams with real engineering behind them. Must be something else entirely. For now, this is mine. It works. And it makes the terrace, the coffee and the news just a little bit better.

---

**One thing to know:** the AI analysis needs an Anthropic API key to run. You can add yours in the banner at the top of the page if you have one. It stays in your browser, nothing stored anywhere else. No key, no problem. Everything else works perfectly.

---

**Stack:** HTML · CSS · JavaScript · RSS via rss2json · Anthropic Claude API · GitHub Pages

*Built by Begoña Traverso*
