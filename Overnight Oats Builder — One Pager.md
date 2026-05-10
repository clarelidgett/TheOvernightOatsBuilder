# The Overnight Oats Builder
*An overnight oats jar that adapts to who you are.*

---

## Taglines (pick one)

- **Build it once. Eat well all week.**
- **An overnight oats builder that actually knows you.**
- **Profile-aware oats. From Sunday prep to Sunday again.**

---

## Short blurb (sharing copy)

Most overnight oats apps hand you generic recipes. This one starts with you.

Pick a profile — Regular, Menopausal, Athletic, Pregnant, or Blood-sugar focused — and flag any allergies. The Builder filters out anything unsafe, stars what's actually optimal for you, and warns when flavours clash. Save favourites, rate them Loved / Fine / Skip, and let it generate a 7-day menu with an aggregated shopping list.

Single HTML file. Light or dark. No login, no tracking, no cloud — your data stays on your device.

---

## What it does

A self-contained breakfast tool that handles three jobs:

| | What it does |
|---|---|
| **Personalises** | Filters and recommends ingredients based on your profile, allergies, and dietary stance. Banned ingredients show struck through with the reason; recommended ones get a star |
| **Builds** | Click ingredients to assemble a jar. Live macro bar updates with calories, protein, fat, carbs and fibre. Generates a printable recipe card with method, macros and "why this works for you" rationale per ingredient |
| **Plans** | Saves your favourites with ratings and notes. Generates a 7-day menu using your top-rated combos first, falling back to profile-recommended fresh combos. Aggregates the shopping list by category |

---

## Customisation, layer by layer

| Layer | Options |
|---|---|
| **Profile** | Regular · Menopausal · Athletic · Pregnant · Blood-sugar focused |
| **Plant-based toggle** | Auto-bans dairy, honey, bee pollen, collagen; swaps milk and yogurt selectors to plant-only |
| **Allergies** | Tree nut · Peanut · Sesame · Soy · Gluten-free — independent toggles |
| **Base** | ½ cup rolled oats (fixed) + choice of 6 milks (full-fat dairy, skimmed, almond, oat, soy, coconut — or none) + 6 yogurts (Greek full-fat, Greek 0%, cottage cheese, skyr, coconut, soy — or none) |
| **Toppings** | 56 ingredients across 8 categories: Fruit · Nuts · Seeds · Protein & dairy · Butters & fats · Sweeteners · Extras & superfoods · Spices & powders |
| **Modes** | Freestyle (pick anything) or Best Combo (auto-disables flavour clashes, hearts signature pairings) |
| **Helpers** | 🎲 Surprise me (random profile-aware combo) · Reset toppings · Live macro bar with profile-aware protein and fibre targets · Servings adjuster (1× – 4×) |
| **Per recipe** | Save with name · Rate Loved/Fine/Skip · Free-text notes · Soft warning if you rebuild a Skip-rated combo · Sort and filter library by date / rating / profile / name |
| **Weekly Menu** | One-tap 7-day plan from your rated recipes; gaps filled with profile-recommended fresh combos; honest banner showing the mix; tap any day to open in Builder |
| **Shopping list** | Aggregated by category; base scaled to weekly quantities (e.g. "3.5 cups oats"); toppings shown as "Banana × 4 days" — no unreliable fraction maths |
| **Recipe card** | Ingredients, method (smart stir-in vs. morning topping logic), 5-tile macro estimate, "Why this works for you" rationale per ingredient, copy-as-text, print |
| **Theme** | Light / dark toggle, remembered across sessions |
| **Privacy** | All data lives in your browser's localStorage. No login, no analytics, no cloud sync |

---

## How it learns

Day one, the Weekly Menu runs entirely from your profile's recommendations. As you start saving and rating combos, your favourites become the backbone of the week — the system fills any remaining days with fresh combos drawn from your profile's recommended ingredients. By the time you've rated five or six recipes, your weekly menu is almost entirely *your* food.

---

## How to share

- **OneDrive share link** → recipient taps, opens in their browser. Cleanest path.
- **HTML file as attachment** → works, but iOS sometimes shows it in Quick Look (script-limited preview); recipient may need to "Open in Safari".

Each recipient starts with a clean slate — your saved recipes and ratings don't travel.

---

## What it's not

- Not a calorie tracker — it estimates per-meal macros, not daily intake
- Not a medical tool — pregnancy bans cover insufficient-data adaptogens (bee pollen, spirulina, maca, goji), but profile recommendations are general nutrition guidance, not individualised advice
- Not cloud-based — by design. Privacy-first. Trade-off: ratings and saves don't sync across devices unless you re-import the file
