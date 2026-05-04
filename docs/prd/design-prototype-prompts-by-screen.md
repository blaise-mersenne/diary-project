# 디자인 프로토타입 프롬프트 — 화면별 분리본

> **생성일:** 2025-07  
> **사용 방법:** 각 섹션의 프롬프트 전체를 복사하여 AI 툴에 붙여넣기

---

## 📌 Screen 1 — 감정 입력 화면 (Home / Emotion Input) `v2 — 한국어 + 게이미피케이션 반영`

```
Design a mobile wellness diary app called "Diary Project" (working title).
This is a low-friction emotional journaling app combined with a virtual garden growth system.
The core philosophy is absolute positive reinforcement — recording emotions makes good things happen, but NOT recording never causes anything negative.

---

## Core Design Direction

- Platform: Mobile app (iOS/Android), portrait orientation, 390px width reference
- Visual Style: Soft, organic, and deeply calming. Think a hand-illustrated botanical garden meets a gentle meditation app. Warm, muted tones with occasional luminous accents.
- Typography: Use a soft serif or rounded display font for headings. Avoid harsh, geometric sans-serifs. The tone should feel like a quiet journal, not a productivity tool.
- Color Palette: Base in warm off-whites and pale sage greens. Accent with soft corals, dusty roses, and golden ambers. No harsh blacks — use deep moss green or warm charcoal for text.
- Avoid: Dark mode, aggressive gradients, neon colors, sharp UI elements, any visual language that implies urgency or productivity.

---

## Language

- All UI text, labels, buttons, and copy must be displayed in Korean (한국어).
- Do not use any English text in the UI itself. English is used only in this prompt for instruction purposes.

---

## Screen 1 — Home / Emotion Input Screen

This is the first screen users see when opening the app.

Layout:
- Top: Soft Korean greeting text (e.g., "오늘 어떤 감정이 느껴지나요?") in a warm, handwritten-style or soft serif font
- Below greeting: A small gamification status bar showing the user's current plant stage and a gentle progress indicator (e.g., a tiny illustrated seedling icon + "3단계 성장 중" label). This reminds the user that their choices today will grow their plant.
- Middle: A grid or organic cluster of 10–15 emotion chips (pill-shaped tags) with Korean labels: 편안한, 상쾌한, 다행인, 설레는, 따뜻한, 뿌듯한, 고요한, 기쁜, 감사한, 포근한, 산뜻한, 홀가분한
- Chips should feel soft and tactile — rounded corners, subtle drop shadows, gentle fill colors
- Each chip has a small illustrated icon or floral accent that hints at which flower it will grow (e.g., 편안한 = tiny lavender sprig, 설레는 = small sunflower bud). This creates a collectible, gamified feel.
- Selected chips animate gently — a soft "pop" effect with a warm color fill and a subtle sparkle or glow, making selection feel rewarding like collecting items
- A small counter badge near the chips shows how many have been selected (e.g., "2개 선택됨 ✓") — minimum 2 required
- Bottom: A faint, optional memo input field ("오늘의 메모를 남겨보세요 (선택)") and a CTA button that reads "감정 기록하기" — the button should be visually inactive/greyed until 2+ chips are selected, then bloom into full color
- A small search icon labeled "직접 입력" in the corner for searching/creating custom emotion chips

Gamification Notes:
- The screen should feel like the start of a rewarding daily ritual, not a form to fill out
- The plant status bar at the top creates anticipation — the user can see their plant is waiting to grow
- Chip selection should feel like collecting or picking flowers — each tap is a small moment of delight
- The "Record" button activating (greying out → blooming into color) is itself a satisfying micro-reward

---

## Deliverable

Output as a high-fidelity mobile UI mockup, portrait orientation, warm and botanical aesthetic. Generate Screen 1 only.
```

---

## 📌 Screen 2 — 식물 성장 대기 화면 (Plant Growth & Waiting State)

```
Design a mobile wellness diary app called "Diary Project" (working title).
This is a low-friction emotional journaling app combined with a virtual garden growth system.
The core philosophy is absolute positive reinforcement — recording emotions makes good things happen, but NOT recording never causes anything negative.

---

## Core Design Direction

- Platform: Mobile app (iOS/Android), portrait orientation, 390px width reference
- Visual Style: Soft, organic, and deeply calming. Think a hand-illustrated botanical garden meets a gentle meditation app. Warm, muted tones with occasional luminous accents.
- Typography: Use a soft serif or rounded display font for headings. Avoid harsh, geometric sans-serifs. The tone should feel like a quiet journal, not a productivity tool.
- Color Palette: Base in warm off-whites and pale sage greens. Accent with soft corals, dusty roses, and golden ambers. No harsh blacks — use deep moss green or warm charcoal for text.
- Avoid: Dark mode, aggressive gradients, neon colors, sharp UI elements, any visual language that implies urgency or productivity.

---

## Screen 2 — Plant Growth & Waiting State

After recording emotions, the user's plant enters a "waiting/growing" state.

Layout:
- Full-screen soft background (pale sky, gentle gradient from warm white to light sage)
- Center: The user's plant in its current growth stage (show stage 3 or 4 as an example — a small seedling with a few leaves)
- Surrounding the plant: Subtle, looping particle animation — soft glowing light particles (like fireflies or tiny stars) gently floating and orbiting the plant. This represents the emotion being "absorbed" by the plant.
- A soft poetic text below the plant: e.g., "Your feelings are slowly taking root..."
- Time remaining shown softly — not as a harsh countdown timer, more like "a little while longer" in gentle typography
- Bottom: A soft, dismissible card — "Want to see your plant bloom a little sooner? Watch a short video 🌱" with a gentle CTA button

Growth Stages Reference (7+ stages, illustrated style):
1. Bare soil with a single seed
2. Seed cracking open, first root visible underground
3. Tiny sprout breaking through soil (1–2 leaves)
4. Small seedling with 3–4 leaves
5. Growing stem with visible bud
6. Bud swelling, about to bloom
7. First bloom open
8. Full bloom with multiple flowers
9. Mature plant with seeds ready to disperse — cycle complete

Each stage should feel like a hand-drawn botanical illustration, warm and organic.

---

## Deliverable

Output as a high-fidelity mobile UI mockup, portrait orientation, warm and botanical aesthetic. Generate Screen 2 only.
```

---

## 📌 Screen 3 — 이달의 정원 뷰 (Monthly Garden View)

```
Design a mobile wellness diary app called "Diary Project" (working title).
This is a low-friction emotional journaling app combined with a virtual garden growth system.
The core philosophy is absolute positive reinforcement — recording emotions makes good things happen, but NOT recording never causes anything negative.

---

## Core Design Direction

- Platform: Mobile app (iOS/Android), portrait orientation, 390px width reference
- Visual Style: Soft, organic, and deeply calming. Think a hand-illustrated botanical garden meets a gentle meditation app. Warm, muted tones with occasional luminous accents.
- Typography: Use a soft serif or rounded display font for headings. Avoid harsh, geometric sans-serifs. The tone should feel like a quiet journal, not a productivity tool.
- Color Palette: Base in warm off-whites and pale sage greens. Accent with soft corals, dusty roses, and golden ambers. No harsh blacks — use deep moss green or warm charcoal for text.
- Avoid: Dark mode, aggressive gradients, neon colors, sharp UI elements, any visual language that implies urgency or productivity.

---

## Screen 3 — Monthly Garden View ("This Month's Garden")

The archive screen showing one month of emotional records as a full illustrated garden.

Layout:
- Full-screen garden illustration
- Multiple plants/flowers arranged naturally across the screen (not in a grid — organic placement)
- Show a mid-month example with approximately 15 days recorded
- Each flower represents a recorded day; more recordings = more flowers, more variety
- Each flower's species and color is determined by the emotion words recorded that day:
  - Calm/peaceful emotions (고요한, 편안한) → soft lavender or white flowers (e.g., cosmos, baby's breath)
  - Joyful/excited emotions (설레는, 기쁜) → bright warm flowers (e.g., sunflowers, marigolds) in golden/amber
  - Relieved/grateful emotions (다행인, 감사한) → soft pink or blush flowers (e.g., cherry blossoms, peonies)
  - Refreshed/energized emotions (상쾌한, 활기찬) → cool green or mint tones with white flowers (e.g., lily of the valley)
  - Proud/accomplished emotions (뿌듯한) → rich deep roses or dahlias in coral/deep pink
- Days with no recording: Empty soil patch with a tiny stone or fallen petal — never wilted plants, never sad imagery
- A soft header showing the month name in elegant typography
- A gentle navigation element to move between months

Emotional Tone:
- Opening this screen should feel like opening a memory box — warm, nostalgic, peaceful
- The garden should feel MORE beautiful as more emotions are recorded (positive reinforcement through aesthetics)

---

## Deliverable

Output as a high-fidelity mobile UI mockup, portrait orientation, warm and botanical aesthetic. Generate Screen 3 only.
```

---

## 📌 Screen 4 — 수익화 터치포인트 (Monetization Touch Points)

```
Design a mobile wellness diary app called "Diary Project" (working title).
This is a low-friction emotional journaling app combined with a virtual garden growth system.
The core philosophy is absolute positive reinforcement — recording emotions makes good things happen, but NOT recording never causes anything negative.

---

## Core Design Direction

- Platform: Mobile app (iOS/Android), portrait orientation, 390px width reference
- Visual Style: Soft, organic, and deeply calming. Think a hand-illustrated botanical garden meets a gentle meditation app. Warm, muted tones with occasional luminous accents.
- Typography: Use a soft serif or rounded display font for headings. Avoid harsh, geometric sans-serifs. The tone should feel like a quiet journal, not a productivity tool.
- Color Palette: Base in warm off-whites and pale sage greens. Accent with soft corals, dusty roses, and golden ambers. No harsh blacks — use deep moss green or warm charcoal for text.
- Avoid: Dark mode, aggressive gradients, neon colors, sharp UI elements, any visual language that implies urgency or productivity.

---

## Screen 4 — Monetization Touch Points (Non-intrusive)

These UI elements should feel like gentle invitations, never aggressive upsells.

Rewarded Ad Prompt:
- A soft, dismissible bottom card overlaid on the plant waiting screen
- Text: "Want to see your plant bloom a little sooner? Watch a short video 🌱"
- Design: Rounded card, warm cream background, small illustrated plant icon, gentle CTA button
- Must feel optional and warm — never a full-screen interstitial, never urgent

Garden Shop Screen:
- A cozy, botanical shop layout — feels like browsing a quiet flower market, not a game store
- Navigation entry: A small watering can or basket icon in the bottom nav
- Shop sections:
  1. Premium Seeds — rare and beautiful flower varieties not available for free
  2. Garden Decorations — small objects to place in the garden (lanterns, stones, benches)
  3. Special Weather Effects — aurora, starlight, golden hour light overlays
- Each item shown as a soft illustrated card with a gentle price tag
- Overall tone: Cozy, unhurried, collectible — like a stationery shop

---

## Deliverable

Output as high-fidelity mobile UI mockups, portrait orientation, warm and botanical aesthetic. Generate Screen 4 only — show both the rewarded ad card variant and the Garden Shop screen.
```
