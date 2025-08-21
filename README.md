# Shayan Portfolio (Next.js + Tailwind + Framer Motion)

## Run locally
```bash
npm i
npm run dev
```

## Deploy
- Push to Git + connect to Netlify (Next.js build).
- Or build locally: `npm run build && npm run start`

## Replace content
- Portrait: place your image at `/public/portrait.jpg`.
- Case studies: edit `/content/case-studies.json`.
- Categories: `/content/categories.json`.
- Skill icons: replace SVGs in `/public/icons` or update `components/SkillsGrid.tsx`.

## Notes
- Thumbnails for YouTube use `https://img.youtube.com/vi/VIDEO_ID/maxresdefault.jpg`.
- The player is lazy and opens in a modal.
- Animations respect `prefers-reduced-motion`.
