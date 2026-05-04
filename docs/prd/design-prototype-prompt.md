# 디자인 프로토타입 프롬프트 (Design Prototype Prompt)

> **생성일:** 2025-07  
> **기반 문서:** PRD v1.0  
> **용도:** Figma Make, Claude, v0 등 AI 디자인/프로토타이핑 툴에 붙여넣기용

---

## 사용 방법

1. 아래 **[FULL PROMPT]** 섹션 전체를 복사
2. AI 툴의 프롬프트 입력창에 붙여넣기
3. 결과물을 보며 수정이 필요한 부분은 Claude와 논의 후 프롬프트 업데이트

---

## [FULL PROMPT]

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

## Screen 1 — Home / Emotion Input Screen

This is the first screen users see when opening the app.

Layout:
- Top: Soft greeting text (e.g., "How are you feeling right now?") in a warm, handwritten-style or soft serif font
- Middle: A grid or organic cluster of 10–15 emotion chips (pill-shaped tags). Example words: 편안한 (comfortable), 상쾌한 (refreshing), 다행인 (relieved), 설레는 (excited), 따뜻한 (warm), 뿌듯한 (proud), 고요한 (peaceful)
- Chips should feel soft and tactile — rounded corners, subtle drop shadows, gentle fill colors
- Selected chips should have a distinct but gentle highlighted state (e.g., soft glow, color fill)
- Bottom: A faint, optional memo input field ("Add a note... (optional)") and a "Record" CTA button
- A small search icon in the corner for searching/creating custom emotion chips

Interaction Notes:
- Minimum 2 chips must be selected before the Record button activates
- The overall feeling should be like picking flowers, not filling out a form

---

## Screen 2 — Plant Growth & Waiting State

After recording, the user's plant enters a "waiting/growing" state.

Layout:
- Full-screen soft background (pale sky, gentle gradient from warm white to light sage)
- Center: The user's plant in its current growth stage (see Growth Stages below)
- Surrounding the plant: Subtle, looping particle animation — soft glowing light particles (like fireflies or tiny stars) gently floating and orbiting the plant. This represents the emotion being "absorbed" by the plant.
- A soft progress indicator or poetic text below the plant: e.g., "Your feelings are slowly taking root..." 
- Time remaining shown softly (not as a countdown timer — more like "a little while longer")

Growth Stages (7+ stages, illustrated style):
1. Bare soil with a single seed
2. Seed cracking open, first root visible underground
3. Tiny sprout breaking through soil (1–2 leaves)
4. Small seedling with 3–4 leaves
5. Growing stem with visible bud
6. Bud swelling, about to bloom
7. First bloom open
8. Full bloom with multiple flowers
9. (Optional) Mature plant with seeds ready to disperse — cycle complete

Each stage should feel like a hand-drawn botanical illustration, warm and organic.

---

## Screen 3 — Monthly Garden View ("This Month's Garden")

The archive screen showing one month of emotional records as a full illustrated garden.

Layout:
- Full-screen garden illustration
- Multiple plants/flowers arranged naturally across the screen (not in a grid — organic placement)
- Each flower represents a recorded day; more recordings = more flowers, more variety
- Each flower's species and color is determined by the emotion words recorded that day:
  - Calm/peaceful emotions (고요한, 편안한) → soft lavender or white flowers (e.g., cosmos, baby's breath)
  - Joyful/excited emotions (설레는, 기쁜) → bright warm flowers (e.g., sunflowers, marigolds) in golden/amber
  - Relieved/grateful emotions (다행인, 감사한) → soft pink or blush flowers (e.g., cherry blossoms, peonies)
  - Refreshed/energized emotions (상쾌한, 활기찬) → cool green or mint tones with white flowers (e.g., lily of the valley)
  - Proud/accomplished emotions (뿌듯한) → rich deep roses or dahlias in coral/deep pink
- Days with no recording: Empty soil patch with a tiny stone or fallen petal — never wilted plants, never sad imagery
- A soft header showing the month name in elegant typography
- A gentle scrollable or swipeable interface to navigate between months

Emotional Tone:
- Opening this screen should feel like opening a memory box — warm, nostalgic, peaceful
- The garden should feel MORE beautiful as more emotions are recorded (positive reinforcement through aesthetics)

---

## Screen 4 — Monetization Touch Points (Non-intrusive)

These UI elements should feel like gentle invitations, never aggressive upsells.

Rewarded Ad Prompt (during waiting state):
- A soft, dismissible card at the bottom of Screen 2
- Text example: "Want to see your plant bloom a little sooner? Watch a short video 🌱"
- Design: Rounded card, warm background, small plant icon, gentle CTA button — never a full-screen interstitial

In-App Purchase Entry Points:
- A "Garden Shop" icon in the navigation — a small basket or watering can icon
- Shop contents: Premium seed varieties, garden decoration items, special weather effects (aurora, starlight, golden hour)
- Design language: Like browsing a cozy botanical shop, not a game store

---

## Overall UX Principles to Reflect in Design

1. Zero guilt design: Nothing ever looks sad, wilted, neglected, or broken
2. Breathing room: Generous whitespace, no cluttered screens
3. Tactile softness: Every interactive element should look and feel soft to touch
4. Poetic language: All UI copy uses gentle, metaphorical language (not system/utility language)
5. Reward through beauty: The longer you use the app, the more beautiful your garden becomes

---

## Deliverable

Please generate the following screens:
1. Home / Emotion Input Screen
2. Plant in Waiting/Growing State
3. Monthly Garden View (mid-month example with ~15 days recorded)
4. One monetization touch point (rewarded ad card variant)

Output as high-fidelity mobile UI mockups, portrait orientation, warm and botanical aesthetic.
```

---

## 결정된 디자인 스펙 요약 (PRD 반영 사항)

| 항목 | 결정 내용 | 관련 Epic |
|------|-----------|-----------|
| 이달의 정원 뷰 컨셉 | 정원 일러스트형 | Epic 03 |
| 식물 성장 단계 | 7단계 이상 (씨앗 → 만개 → 씨앗 산포) | Epic 04 |
| 대기 중 시각 연출 | 은은한 빛 입자(반딧불/별빛) 반짝임 애니메이션 | Epic 04 |
| 감정 단어 ↔ 꽃/색상 매핑 | 감정 카테고리별 꽃 종류 + 색상 연결 | Epic 01, 03 |
