# 📹

Watch it: https://kumar303.github.io/llama-deal-with-it/

# 🎵

The music is [Computer Woman by Superior Elevation](https://www.youtube.com/watch?v=eklqLkyoJWA).

# 🔥

What is it? My kids and I vibe-coded a llama dance party using [`claude-4.1-opus`](https://www.anthropic.com/). We started with this prompt:

<details>
<summary>👩🏽‍💻 Expand</summary>

> Create a preact app using tailwind for css. Render a square centered in the viewport with slightly rounded corners. Add a diagonal dark purple to medium pink gradient to the background of the square. Add a pixelated llama in orange. Add a button, also in orange, underneath the llama that says Make the llama dance. When the button gets pressed, put "deal with it" sunglasses on the pixelated llama and make it dance up and down with crude css animation.

</details>

We prompted the rest one element at a time. The first take usually wouldn't work out well but it only took a few tries. For example, we'd say _add a hula hooping hippopotamus_ and it wouldn't get the hoop right or the arms wouldn't be connected. We'd have to ask for specific fixes like _make sure the right arm is connected at the shoulder_ or maybe we'd ask to change the look. The only one we gave up on was "add a [flossing](<https://en.wikipedia.org/wiki/Floss_(dance)>) lion." I don't know why that one was so hard.

This project took several hours of work but would have taken weeks to code by hand. Getting immediate results was highly motivating. It was fun. It made me think a lot about LLMs (AI) for coding...

# 🪐

I admit I didn't see potential in early LLMs. All I saw were useless things like _explain how to do long division as if you're a pirate_ or halluncinations that eroded trust. Coding was even worse. Early LLMs could create simple scripts but failed to modify complex codebases for basic tasks like _move this module and update all imports_.

# 🌍

In mid 2025, the models started getting pretty good for coding. At work I'm now seeing a 2x speedup (time to completion) for coding tasks I could easily do by hand and a 30x speedup for those I couldn't, like when in a foreign codebase or using unfamiliar libraries. While waiting for code generation, I get extra time to review other PRs or start new tasks.

# ☎️

Running prompts (in 2025) is slow and feels like the early days of dial-up Internet. In the 90s, the Internet had obvious potential and I get that same feeling about LLMs. They will get faster and the per token cost will be worth it. All of this will consume immense energy but that's a topic for another time.

# ⛏️

AI is a tool, not a personality. When the hype dies down, I hope we'll be left with more tools and less chatbots. It's way faster to explain in natural language what needs doing but I don't need pampering like _you're absolutely right!_ Some of the more scary, unethical uses of AI involve impersonating humans.

# 🧠

What if _anyone_ could build software at the **speed of thought**? This was always my dream as an engineer. Every skill I invested in--learning a more concise programming language ([Python](https://www.python.org/) 🌶️), mastering a keyboard layout that favored my stronger fingers ([Kinesis Advantage](https://kinesis-ergo.com/shop/advantage2/) 🌶️🌶️), learning an editor that required less keystrokes ([Vim](https://www.vim.org/) 🌶️🌶️🌶️🌶️)--were all marching toward the goal of creating software at the speed of thought. LLMs are a **massive leap** toward this goal and might even get us there.

# 💃🏼

Everyone can build software now. I love hearing stories from designers and other non-coders who are writing code for the first time because they can explain to an LLM _how the software should behave_. With today's models, one still has to explain _how_ to build complex things but that could melt away as models and context techniques evolve.

# ✅

I'm not an expert in prompting but in 2025 I've had the most success when telling an LLM how to check its work. If I give it a command to run (like a failing test) or tell it to launch a browser (e.g. with [Playwright](https://playwright.dev/)) and check for a specific element on the page, it's more likely to arrive at the correct answer on its own.

# 📣

For the first time ever, I've been talking to my computer 😂 It's faster to speak a prompt than to type it. I hadn't ever bothered with dictation as I wasn't aware of a way to dictate actual computer code that will compile. My young kids find it more natural to speak commands at their ipads but I never really got into that either.

# 🌴

"Are you worried about your job?" is usually what someone asks when I tell them I'm excited about AI for coding. I have 25 years experience writing code by hand, architecting complex software, setting up teams for collaboration, yadda yadda. I'm not worried. I might get paid less (that's fair!) but I foresee software companies just **doing more** instead of reducing their workforces.

# 🐛

Hand written software takes a ridiculous amount of time to get right. Teams work for weeks or months on a feature. The process has evolved a lot (publishing to the Web, [continuous delivery](https://en.wikipedia.org/wiki/Continuous_delivery), [user stories](https://en.wikipedia.org/wiki/User_story)...) but it's still unbearably slow. Has your software team ever completed the _entire_ backlog of issues before moving on to another project? Probably not. LLMs will speed up software creation but there is _so much to do_ that I'm not worried about job loss.

# ✏️

Rapid prototyping has always been the key to building useful, delightful software. Today's models are very good at prototyping. In fact, this might be the only thing they can do with high accuracy. I've seen designers use LLMs to build fully interactive websites to demonstrate UI concepts. That's massive. Most software companies fail by simply building the wrong thing for their customers.

# 🏛️

Will we still build cathedrals of code? Probably not. I admit I've built more than one software system where I'd become proud of its elegant, poetic architecture. The art of coding by hand is also really fun. I would often enter a [flow state](<https://en.wikipedia.org/wiki/Flow_(psychology)>), energized by intense focus. I would often walk away from a coding session with a much deeper understanding of the system, of all its inputs and outputs and limitations.

# 🕊️

I will mourn the loss of this. Some of us may reminisce about it like lore. However, with AI generated code we'll likely be less emotionally attached to the code and less prone to [sunk cost fallacies](https://thedecisionlab.com/biases/the-sunk-cost-fallacy). I've found that _most_ successful hand coded systems end up an inelegant mess anyway.

# 🔗

What will future abstractions look like? I'm not sure. Software abstractions like [Django](https://www.djangoproject.com/), [Rails](https://rubyonrails.org/), [jQuery](https://jquery.com/), and [React](https://react.dev/) were all created to solve some kind of hand-written software problem, usually around security mistakes or the tedium of boilerplate code. In Armin Ronacher's experiments with hands-off LLM code generation, he found models [wrote the best code in Go](https://lucumr.pocoo.org/2025/6/12/agentic-coding/).

# ⚠️

Don't get me wrong, the AI hype right now is out of control. I find services like [Suno](https://suno.com/) that generate a song from a prompt devoid of creativity. That's not a tool, it's a rubber stamp. If it were to let me describe or, even better, _express_ a perfectly timed yet nuanced drum rhythm without having to spend 10 years mastering the drums and then doing the same with bass guitar, keys, vocals--letting me build _my own song_--then that would make it a tool.

# 📖

Sal Khan [mentioned](https://www.theverge.com/decoder-podcast-with-nilay-patel/766082/khan-academy-ceo-sal-khan-ai-education-schoolhouse-hank-green-interview) how teachers protested when text books were first introduced into classrooms, fearing they'd get replaced by the text books. Teachers never went away and it's hard to imagine going to school without a physical or digital text book. When the dust settles and we're left clutching an LLM toolbox, we might look back on AI more like those text books.

<hr />

\~ Kumar McMillan, 2025-09-14
