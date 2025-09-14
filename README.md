# 👁️

View it: https://kumar303.github.io/llama-deal-with-it/

# 🎵

The music is [Computer Woman by Superior Elevation](https://www.youtube.com/watch?v=eklqLkyoJWA).

# 🔥

What is it? My kids and I vibe-coded a llama dance party using [`claude-4.1-opus`](https://www.anthropic.com/). We started with this prompt:

<details>
<summary>👩🏽‍💻 Expand</summary>

> Create a preact app using tailwind for css. Render a square centered in the viewport with slightly rounded corners. Add a diagnal dark purple to medium pink gradient to the background of the square. Add a pixelated llama in orange. Add a button, also in orange, underneath the llama that says Make the llama dance. When the button gets pressed, put "deal with it" sunglasses on the pixelated llama and make it dance up and down with crude css animation.

</details>

We prompted the rest one element at a time. The first take usually wouldn't work out well but it only took a few tries. For example, we'd say _add a hula hooping hippopotamus_ and it wouldn't get the hoop right or the arms wouldn't be connected. We'd have to ask for specific fixes like _make sure the right arm is connected at the shoulder_. The only one we gave up on was "add a [flossing](<https://en.wikipedia.org/wiki/Floss_(dance)>) lion." I don't know why that one was so hard.

This project took several hours of work but would have taken weeks to code by hand. Working through it made me think a lot about LLMs (AI) for coding...

# 🪐

I admit I didn't see potential in early LLMs. All I saw were useless things like _explain how to do short division as if you're a pirate_ or halluncinations that eroded trust. Coding was even worse. Early LLMs could create simple scripts but failed to modify complex codebases for simple tasks like _move this module and update all imports_.

# ✨

In mid 2025, the models started getting pretty good for coding. At work I'm seeing a 2x speedup (pure clock time) for coding tasks I could easily do by hand and a 30x speedup for those I couldn't, like when in a foreign codebase or with unfamiliar libraries. While waiting for code generation, I can catch up on Slack or start a new task.

# ☎️

Running prompts (in 2025) is slow and feels like the early days of dial-up Internet. In the 90s, the Internet had obvious potential and I get the same feeling about LLMs. They will get faster and consumers will pay, ignoring immense resource consumption behind the scenes (that's a topic for another day, though).

# 🌍

LLMs are a tool, not a personality. When the hype dies down, we'll be left with tools not chatbots. It's way _faster_ to talk to a tool and tell it what you want but I don't need it to pretend to like me. Some of the more scary, unethical directions AI is heading towards involve impersonating humans.

# 🧠

What if _anyone_ could build software at the speed of thought? This was always my dream as an engineer. Every skill I invested in--learning a more concise programming language ([Python](https://www.python.org/)), mastering a keyboard layout that favored my strongest fingers ([Kinesis Advantage](https://kinesis-ergo.com/shop/advantage2/)), learning an editor that required less keystrokes ([Vim](https://www.vim.org/) 😁)--were all marching toward the goal of creating software at the speed of thought. LLMs provide a **massive leap** toward this goal and might even get us there.

# 💃🏼

Everyone can build software now. I love hearing stories from designers and other non-coders who are writing code for the first time because they can explain to an LLM _how the software should behave_ as opposed to how to code it. With today's models, one still has to explain _how_ to build complex things but that will melt away as models and context techniques evolve.

# ✅

I'm not an expert in prompting or context techniques but in today's models I've had the most success when I tell an LLM how to check its work. If I give it a command to run (like a failing test) or a way to launch a browser (e.g. [Playwright](https://playwright.dev/)) and check for a specific element on the page, it's more likely to arrive at the correct answer on its own.

# 📣

For the first time ever, I've been talking to my computer 😂 It's faster to speak a prompt than to type it. I never bothered before since one cannot dictate computer code in a literal sense. My young kids find it more natural to speak commands at their ipads but I never really got into it until now.

# 🌴

"Are you worried about your job?" is usually what someone asks when I tell them I'm excited about AI for coding. I have 25 years experience writing code by hand, architecting and maintaining complex software, leading teams for collaboration, yadda yadda. I'm not worried. I might get paid less (lol) but I foresee software companies just **doing more** instead of reducing their workforces.

# 🐛

Hand written software takes a ridiculous amount of time. A small team often works for weeks or months on a feature. It has evolved a lot (publishing to the Web, [continuous delivery](https://en.wikipedia.org/wiki/Continuous_delivery)...) but it's still unbearably slow. If you've worked on software, has your team ever completed the _entire_ backlog of issues before moving on to another project? Probably not. LLMs will speed up software creation but there is _so much to do_ that I'm not worried about job loss.

# ✏️

Rapid prototyping is the key to building usable software. Today's models are very good at it. In fact, this might be the only thing they can do with any accuracy and precision. I've seen designers use LLMs to build completely interactive websites to demonstrate UI concepts. That's massive.

# 🔗

What will the new abstractions look like? I'm not sure. Software abstractions like [Django](https://www.djangoproject.com/), [Rails](https://rubyonrails.org/), [jQuery](https://jquery.com/), and [React](https://react.dev/) were all created to solve some kind of hand-written sofware problem, usually around security or the tedium of boilerplate code. In Armin Ronacher's experiments with hands-off LLM code generation, he found models [wrote the best code in Go](https://lucumr.pocoo.org/2025/6/12/agentic-coding/).

\~ Kumar McMillan, 2025-09-14
