<div dir="rtl" lang="he">

# הסקילים של mrdaniel.co.il

עשרה סקילים לסוכני AI, בפורמט הפתוח [Agent Skills](https://agentskills.io) (תיקייה עם `SKILL.md`), שנכתבו ב-[mrdaniel.co.il](https://mrdaniel.co.il) מתוך העבודה היומית של האתר והסטודיו שלו: הרילים של הבוקר, הקרוסלות, סוכן החדשות, החוברות החינמיות והבאגים בעברית שתוקנו באתר עצמו. כולם בעברית, כולם ברישיון MIT.

**מחבר:** דניאל בן ברוך · [mrdaniel.co.il](https://mrdaniel.co.il) · עמוד הסקילים באתר: [mrdaniel.co.il/skills](https://mrdaniel.co.il/skills)

## הסקילים

| סקיל | למי | שם | מה הוא עושה |
|---|---|---|---|
| [`hebrew-reel-script`](hebrew-reel-script/) | יוצרים | תסריט לריל בעברית | קריינות לריל טיפ של עד דקה: פתיח קצר, טיפ אחד, צעדים שמחזיקים על המסך וסיום שמזמין לשמור. |
| [`hebrew-caption-writer`](hebrew-caption-writer/) | יוצרים | כיתוב לריל ולפוסט | כיתוב שלא חוזר על הקריינות: מה הצופה חוסך, למה לשמור, ואיך מסיימים בקריאה אמיתית לפעולה. |
| [`hebrew-carousel-deck`](hebrew-carousel-deck/) | יוצרים | קרוסלת ידע בעברית | מכתבה, פוסט או הסבר לקרוסלה של שקופיות: כותרת בשקף הראשון, רעיון אחד בכל שקף, וסגירה שמסכמת. |
| [`ai-news-brief-he`](ai-news-brief-he/) | יוצרים | תקציר חדשות AI ללומדים | מכתבה באנגלית או בעברית לתקציר קצר: שלוש נקודות שונות, מה זה מלמד, ובלי מספר שלא במקור. |
| [`ai-learning-path-he`](ai-learning-path-he/) | לומדים | מסלול לומדים AI | העוזר נהיה מורה פרטי שמלווה אתכם במסלול של האתר, צעד אחד בכל פעם. |
| [`prompt-brief-he`](prompt-brief-he/) | לומדים | בקשה שעובדת מהניסיון הראשון | שישה מרכיבים לכל בקשה: תפקיד, משימה, רקע, גבולות, צורת התשובה ודוגמה. ומה עושים כשהתשובה לא נכונה. |
| [`code-assistant-first-steps-he`](code-assistant-first-steps-he/) | לומדים | Claude Code מאפס | מההתקנה ועד המשימה הראשונה: עוזר שקורא את הקבצים שלכם, מציע שינוי ומבקש אישור. |
| [`agent-brief-he`](agent-brief-he/) | בונים | אפיון סוכן AI במילים פשוטות | שיחה קצרה שמסתיימת במסמך אפיון: מה הסוכן עושה, ממה הוא מתחיל, מה הוא מחזיר ואיפה הוא עוצר לאישור. |
| [`agent-automation-map-he`](agent-automation-map-he/) | בונים | מיפוי משימה לפני אוטומציה | מפרקים משימה שחוזרת לחמישה חלקים, נותנים לה ציון, ומחליטים מה הופכים לסוכן קודם. |
| [`hebrew-site-bidi-check`](hebrew-site-bidi-check/) | בונים | בדיקת עברית ודו־כיווניות באתר | מספרים הפוכים, שעות שמתהפכות, נקודה שקופצת לצד הלא נכון: רשימת הבדיקה והתיקונים. |

## התקנה

- **Claude Code:** מעתיקים את תיקיית הסקיל אל `~/.claude/skills/` (לכל הפרויקטים) או אל `.claude/skills/` בתוך הפרויקט. בסשן הבא העוזר כבר מכיר אותו.
- **Claude.ai ו-Claude Desktop:** מורידים את ה-ZIP של הסקיל מ[עמוד הסקילים](https://mrdaniel.co.il/skills) ומעלים אותו בהגדרות (Customize ← Skills ← Upload a skill).
- **סוכנים אחרים** (Cursor, Codex, Gemini CLI, Copilot ועוד): כל סוכן שקורא `SKILL.md` לפי המפרט הפתוח טוען את התיקייה כמו שהיא.

## מה יש בכל תיקייה

- `SKILL.md`: ההוראות עצמן, בעברית, עם ה-frontmatter של המפרט (שם, תיאור, רישיון, גרסה ותאריך).
- `SKILL_HE.md`: אותו תוכן, בשם שספריות דו-לשוניות מחפשות.
- `metadata.json`: שם, תיאור ותגיות בעברית ובאנגלית, הקטגוריה והסוכנים הנתמכים.

הסקילים הם טקסט בלבד: בלי סקריפטים, בלי גישה לרשת, בלי מפתחות. עובדה שסקיל מבקש מהעוזר להשתמש בה מגיעה מהמשתמש או מעמוד רשמי, אף פעם לא מהסקיל עצמו.

## גרסאות

כל שינוי בסקיל מעלה את `metadata.version` ואת `metadata.updated` ב-`SKILL.md` שלו, ומקבל release חתום (תג `v*`). ראו [CHANGELOG.md](CHANGELOG.md).

## רישיון

MIT, ראו [LICENSE](LICENSE). אפשר להעתיק, לשנות ולהתאים לקול שלכם; הקרדיט נשאר.

</div>

---

# mrdaniel.co.il skills

Ten skills for AI agents in the open [Agent Skills](https://agentskills.io) format (a folder with a `SKILL.md`), written at [mrdaniel.co.il](https://mrdaniel.co.il) out of the site's and its studio's daily work: the morning reels, the carousels, the news agent, the free booklets, and the Hebrew bugs fixed on the site itself. All of them are in Hebrew, all of them MIT.

**Author:** Daniel Ben Baruch · [mrdaniel.co.il](https://mrdaniel.co.il) · the skills page: [mrdaniel.co.il/skills](https://mrdaniel.co.il/skills)

## The skills

| Skill | For | Name | What it does |
|---|---|---|---|
| [`hebrew-reel-script`](hebrew-reel-script/) | creators | Hebrew Reel Script | Narration, on-screen cards and caption for a short Hebrew tip reel (up to 60 seconds): a three-second hook, one tip, readable pacing, step cards with real links and a spoken call to action. |
| [`hebrew-caption-writer`](hebrew-caption-writer/) | creators | Hebrew Caption Writer | Instagram, TikTok or LinkedIn captions for a Hebrew reel or post that never repeat the narration: the added value in other words, a real call to action, up to five hashtags and two expanded versions. |
| [`hebrew-carousel-deck`](hebrew-carousel-deck/) | creators | Hebrew Carousel Deck | Turns an article, a post or a short explanation into the text and structure of a Hebrew Instagram or LinkedIn carousel: a headline-only cover, one idea per slide, a closing summary and a caption that carries the link. |
| [`ai-news-brief-he`](ai-news-brief-he/) | creators | AI News Brief for Learners (Hebrew) | Turns an AI news article into a short Hebrew brief for people learning AI: the full article, three distinct points, what it teaches a learner, and no number that is not in the source. |
| [`ai-learning-path-he`](ai-learning-path-he/) | learners | AI Learning Path Tutor (Hebrew) | Turns the assistant into a patient Hebrew tutor that walks a beginner along a five-step AI learning path, one step and one exercise at a time. |
| [`prompt-brief-he`](prompt-brief-he/) | learners | Prompt Brief (Hebrew) | Helps a Hebrew speaker write a request that works on the first try: role, task, background, limits, answer shape and one example, plus how to spot a made-up answer. |
| [`code-assistant-first-steps-he`](code-assistant-first-steps-he/) | learners | Claude Code First Steps (Hebrew) | Walks a Hebrew speaker from zero to a first working Claude Code session: what to prepare, the install from the official page, the first session, CLAUDE.md and five working habits. |
| [`agent-brief-he`](agent-brief-he/) | builders | AI Agent Brief Interview (Hebrew) | A short Hebrew interview that ends in a written brief for an AI agent or automation: the task, the trigger, inputs, outputs, what it may never do alone and where it stops for approval. |
| [`agent-automation-map-he`](agent-automation-map-he/) | builders | Automation Task Map (Hebrew) | Maps a repeating task before automating it: trigger, inputs, decision points, actions and output, a score, which layer to automate first, and a human kept in the loop. |
| [`hebrew-site-bidi-check`](hebrew-site-bidi-check/) | builders | Hebrew Site Bidi Check | Finds and fixes the right-to-left and bidirectional text bugs that break real Hebrew websites: reversed numbers and times, units glued to digits, punctuation on the wrong end, with a fix order and a test to keep. |

## Install

- **Claude Code:** copy the skill's folder into `~/.claude/skills/` (every project) or `.claude/skills/` inside a project.
- **Claude.ai and Claude Desktop:** download the skill's ZIP from [the skills page](https://mrdaniel.co.il/skills) and upload it under Customize → Skills → Upload a skill.
- **Other agents** (Cursor, Codex, Gemini CLI, Copilot and more): any agent that reads `SKILL.md` per the open spec loads the folder as it is.

## What each folder holds

- `SKILL.md`: the instructions, in Hebrew, with the spec's frontmatter (name, description, license, version and date).
- `SKILL_HE.md`: the same content under the name bilingual directories look for.
- `metadata.json`: name, description and tags in Hebrew and English, the category and the supported agents.

The skills are text only: no scripts, no network access, no keys. A fact a skill asks the assistant to use comes from the user or from an official page, never from the skill itself.

## Versions

Every change to a skill bumps `metadata.version` and `metadata.updated` in its `SKILL.md` and gets a signed release (a `v*` tag). See [CHANGELOG.md](CHANGELOG.md).

## License

MIT, see [LICENSE](LICENSE). Copy, change and adapt to your own voice; the credit stays.
