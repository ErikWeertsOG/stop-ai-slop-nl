# Stop AI Slop (NL)

Een Claude-skill die Nederlandse tekst langs zes checks haalt voordat hij wordt opgeleverd. Zo klinkt het niet meer als AI.

## Het probleem

De meeste anti-AI-tools zijn op Engels gebouwd. Ze vangen "delve" en "tapestry", maar Nederlandse AI-tekst verraadt zich anders. Je ziet em dashes die geen Nederlander typt en zinnen die met een komma voor "en" aan elkaar geplakt zijn. Het ritme is zo gelijkmatig dat je na twee alinea's afhaakt.

Ik schrijf als Lead Content Marketeer elke dag met AI. Ik zag die patronen zo vaak terug dat ik ze in een lijstje heb gezet. Dat lijstje zit nu ín mijn schrijfskills, dus Claude loopt zijn eigen tekst na voordat ik hem zie. Ik heb geen los script of aparte tool nodig.

## De zes checks

1. Zinslengte varieert
2. Alinea's lijken niet op elkaar
3. Je zou het hardop zo zeggen
4. Nul em dashes
5. Elk punt staat er één keer
6. Geen komma voor "en" als lijm

De uitleg per check staat in [SKILL.md](SKILL.md). Voorbeelden van voor en na staan in [voorbeelden.md](voorbeelden.md).

## Installeren

Je hebt geen programmeerkennis nodig.

**In Claude (web, desktop of app)**
1. Download deze repo als zip via de groene knop **Code → Download ZIP**.
2. Upload de zip bij Skills in je Claude-instellingen.
3. Klaar. Vraag Claude om een tekst en zeg erbij: "check op AI-slop".

**In Claude Code**
Zet de map `stop-ai-slop-nl` in `~/.claude/skills/`.

## Zelf aanpassen

Mis je een patroon? Zet het erbij als check 7. Hoe korter de lijst, hoe beter hij werkt, dus schrap ook gerust iets.

Een pull request of een issue met een patroon dat jij steeds ziet is welkom.

---

Gemaakt door [Erik Weerts](https://github.com/ErikWeertsOG) · Lead Content Marketeer
