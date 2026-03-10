# The Thin Line

**Where submarine cables meet silicon photonics. Where the field meets the lab. Where Grace lives.**

An interactive AI-powered portfolio experience for **Grace Wanjiru Irungu** — R&D engineer, submarine fiber veteran, poet, builder. Not a resume. Not a chatbot. A *conversation* with someone who deployed $102M of optical infrastructure across four countries and is now asking: *what's next?*

---

### What Is This?

A living, breathing portfolio that *responds* to you. Ask Grace about her work. Ask about fear. Ask about Lake Tanganyika at 1,400 meters. Ask about sonoluminescence. Watch the canvas shift as the conversation moves through her story.

**10 dynamic scenes** painted in real-time on HTML5 Canvas — each one a chapter of Grace's journey. The background listens to the conversation and *becomes* the story.

| Scene | Palette | Trigger |
|-------|---------|---------|
| Red Earth | Warm ochre, Kenyan soil | Origin, heritage, Kikuyu roots |
| Abyss | Deep ocean blue | Lake Tanganyika, submarine cables |
| Wound | Blood red, amber | Struggle, vulnerability, the poet |
| Crossroads | Teal to gold | HyperLight moment, transitions |
| Nano | Electric violet | Photonics, devices, the new frontier |
| Build | Steel, concrete tones | GlitchWitch, PANDERMA, making things |
| Faith | Warm gold | God, family, Lawrence Kansas |
| Fear | Dark shifting grays | Honest moments, the room between rooms |
| Vision | Aurora spectrum | The future, sonoluminescence, what's next |
| Chaos | All colors at once | The chrysalis. Everything converging |

### The Stack

```
Frontend    HTML5 Canvas + vanilla JS (single file, no framework)
Backend     Express.js streaming proxy
AI          Claude API (streaming SSE, conversation memory)
Fallback    Pattern-matching knowledge base (works offline)
Resume      Print-optimized HTML (downloadable)
```

### Easter Eggs

There are a few. You'll have to find them. One involves a poet named Rugano. Another involves Ngai and Kirinyaga. A third shows you what the thin line actually looks like.

### Run It Locally

```bash
git clone https://github.com/irungugraceig-sudo/the-thin-line.git
cd the-thin-line
npm install
```

Create a `.env` file:
```
ANTHROPIC_API_KEY=your-key-here
PORT=3000
```

```bash
npm start
```

Open `http://localhost:3000`. Start talking.

### The Story Behind It

Grace spent 7 years deploying submarine fiber optic cables across East Africa. She led Africa's first deep-lake bathymetric survey at Lake Tanganyika, 1,400 meters deep, where no playbook existed. She secured $102M in international financing. She knows what happens when a cable fails at 2am in the Indian Ocean.

Now she's at Northeastern University, building toward photonic devices, underwater optical communication, and the infrastructure layer that makes AI, VR, and next-generation networks physically possible.

This portfolio exists because a resume can't hold the contradiction: confident AND scared, visionary AND practical, poet AND engineer. The thin line between who you were and who you're becoming.

*"I am battered, beaten, defeated. I am bruised, hurt, disheartened. But hey if you ask me, love, how have you been? I will smile generously."*
— Rugano

---

Built with fire and a laptop at 2am.
