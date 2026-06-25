# Chapterization And Transition Grammar

Use this when a prompt is dense or naturally multi-part. It decides whether to
split into chapters, what each chapter does, and how to move between them.
Easing anchors (see `motion-taste.md` → "Easing Anchors") are supporting tools
here, not the transition itself.

## When To Chapter

Split into chapters when the prompt carries more than one idea: long text,
multiple claims, feature list, multiple stats, timeline, before/after,
problem/solution, quote+proof, setup/payoff, product walkthrough, recap/social
story, or multi-language / repeating content variations. One readable idea per
chapter.

## When Not To Chapter

Keep one beat for a single logo lockup, one CTA, one icon animation, one simple
stat card, one UI microinteraction, a legal/read-critical block, or a calm hero
moment whose final settle is the payoff. Let it land and settle.

## Chapter Roles

Give each chapter one readable job: hook, setup, claim, proof, contrast, detail,
payoff, CTA / final lockup, or loop bridge.

## Split By Meaning, Not Length

Rewrite long text into short authored beats or reveal it progressively. Never
place a paragraph at once, and do not just chop it into smaller paragraph blocks.
Each chapter carries one idea.

## Structure Modes

- Repeated armature: same layout and motion path, content changes. Best for
  lists, stats, languages, recaps, supercuts.
- Evolving story layout: objects/text carry into new positions and the
  composition changes across chapters. Best for product walkthroughs, explainers,
  process, setup/payoff, and narrative motion.

## Readable Window

Each chapter's main message gets a coast, hold, or stable moment before the seam.
Fast transitions are fine, but never at the cost of the read.

## Transition Grammar (pick one per seam)

- hard cut on action: cut while the focal motion is still moving.
- jump cut: hard cut with matched direction/velocity across the seam.
- motion-masked swap: outgoing motion becomes the next beat's reveal/mask.
- continuous carry: an object/text travels into its next location across chapters.
- occlusion wipe: a large shape covers frame, then reveals the next chapter.
- hold/settle cut: only when the beat must land clearly first.
- loop reset: when the cadence intentionally repeats.

## Choosing Transitions (message + tone)

- Energetic list/supercut/recap → repeated armature + hard cut / jump cut on motion.
- Narrative / product walkthrough → continuous carry or motion-masked swap.
- Contrast or palette/world change → occlusion wipe or hard cut.
- Premium / stat / proof → restrained mask or hold/settle cut.
- Read-critical → hold longer; never cut before it is understood.
- Every seam needs a reason — preserve continuity, create contrast, reset rhythm,
  or land a point. Do not vary transition types randomly.

## Jump Cut And Cut-On-Action Mechanics

- A hard cut reads smooth only when the eye is already moving: cut at high
  velocity with travel direction continuous across the seam. Content and position
  may jump if momentum does not — this is cutting on action.
- Per beat, the motion runs snap-in → readable coast (message registers) →
  exit-accel, with the cut placed in the exit-accel so the move's natural end
  sits past the cut and it never settles on screen.
- It is rhythmic, not local: it only reads as intentional across a repeated
  armature of about three to four or more beats (anthology/supercut, often
  looping), where rhythm and momentum carry the cuts and the cadence never
  resolves. One isolated interrupted move just looks broken.

## Easing-Anchor Support

Anchors are tools, not the transition. A transition is chapter role + timing +
direction + cut point + masking + easing.

- `travel-cut` / `exit-accelerate`: cut-on-motion exits.
- `travel-balanced`: continuous carry.
- `settle-soft`: chapter landings and read-critical holds.
- `entrance-sharp`: mask-wipes and strong reveals.

## Guardrails

- Jump/hard cuts need repeated rhythm or a clear editorial reason; one isolated
  interrupted move can look broken.
- Cut-on-motion should usually match direction/velocity across the cut.
- Avoid high-energy chapter cuts for calm luxury/institutional tone, final logo
  lockups, legal text, or anything that must settle to be understood.
