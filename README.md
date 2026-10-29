# The NXT 10 Million — website

A responsive, motion-rich React/Vite campaign experience for Smile Foundation's internal strategy narrative.

## Run locally

Requirements: Node.js 18+.

```bash
npm install
npm run dev
```

Create a production build:

```bash
npm run build
npm run preview
```

## Deploy to Vercel

1. Create a GitHub repository and push this folder's contents.
2. In Vercel, choose **Add New → Project** and import the repository.
3. Framework preset: **Vite** (usually detected automatically).
4. Build command: `npm run build`
5. Output directory: `dist`
6. Deploy.

`vercel.json` includes a rewrite so client-side navigation paths resolve to the app.

## Content integrity

The site uses the source document's framing:
- Smile Foundation has reached 10M+ beneficiaries since 2002.
- The next 10 million is an ambition to prepare for by 2030, not a claim that this target has already been achieved.
- Strategic themes: technology and digital capabilities; R&D, evidence, data, feedback and MEL; cross-learning; climate-aware planning and community resilience; governance, accountability and responsible resource use.
- No CSR programme/vertical has been added.

No live progress figure, financial target, or unverified beneficiary metric is fabricated.

## Before publishing publicly

- Replace the typographic “Smile Foundation” treatment with the approved official logo asset if required.
- Confirm photo permissions and replace the remote supporting photography with approved Smile Foundation images where available.
- Review all copy with the relevant internal owner.
- Update contact details only if an approved public contact should be shown.

## Assets and motion

Photography is loaded from Unsplash's image CDN as illustrative supporting imagery. Framer Motion powers the reveals and transitions. The page respects `prefers-reduced-motion` by reducing motion in CSS and avoiding aggressive movement.
