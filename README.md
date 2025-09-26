# 🪪 HxH Nen Simulator — Extended Final

This is the final extended version. **You only need to add music**; image & video endpoints are already wired.

## What you do
1) Add your MP3s at repo root (filenames must be exactly):
   - phase1.mp3
   - phase2.mp3
   - phase3.mp3
2) Push to GitHub → Import to Vercel → Deploy.
3) (Optional) Vercel → Settings → Environment Variables:
   - OPENAI_API_KEY → real image generation
   - DEMO_VIDEO_URL → demo video URL (optional)
4) Open your Vercel URL and run the exam.

## Features
- Phase 1: 12-question affinity quiz → full % spread
- Phase 2: Guided builder → auto-picks item/element/vows + confidence
- Phase 3: Auto stats + BIG pie chart + image/video preview
- Phase 4: Radar chart + role placement + origin story
- Phase 5: Arc assignment, bar chart vs risk, survival %, story beat
- Music fades across phases (uses phase1/2/3.mp3 names)

## API routes
- /api/generate-image → OpenAI Images if key set, else placeholder
- /api/generate-video → returns demo URL (swap to real provider later)
- /api/video-status → stub for queue polling

## Local Dev
npm i -g vercel
vercel dev

## License
MIT
