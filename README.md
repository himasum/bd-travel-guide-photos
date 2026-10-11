# BD Travel Guide photos

Real place photos for the BD Travel Guide app. The app loads them through jsDelivr:

```
https://cdn.jsdelivr.net/gh/himasum/bd-travel-guide-photos@main/<file>.webp        (about 960 px, detail pages)
https://cdn.jsdelivr.net/gh/himasum/bd-travel-guide-photos@main/thumb/<file>.webp  (about 400 px, lists)
```

## Adding a photo

1. Make two WebP files with the same name: about 960 px wide (quality 70) in the root, and about 400 px wide (quality 65) in `thumb/`. Keep each under 100 KB and 30 KB.
2. Add a line to `CREDITS.md` with the photographer and licence.
3. Push to `main`. In the app, set the spot's `photo: { file, credit }` in `src/data/spots.ts`.

Only use photos you took yourself or ones whose licence allows reuse (for example CC BY or CC BY-SA from Wikimedia Commons).
