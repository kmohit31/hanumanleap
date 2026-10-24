# Hanuman's Leap

A browser arcade game based on the Sundara Kanda of the Ramayana: Hanuman's journey across the ocean from Mahendra mountain to Lanka, to find Sita Maa in the Ashok Vatika.

Everything is in a single `index.html`: canvas art, Web Audio sound, and plain JavaScript, with no image or audio files.

## Status

- [x] 1. The Great Leap
- [ ] 2. Mainaka Mountain
- [ ] 3. Surasa
- [ ] 4. Simhika
- [ ] 5. Lankini at the Gate
- [ ] 6. Lanka by Night
- [ ] 7. Ashok Vatika

## Run locally

```bash
python3 -m http.server 8765
```

Then open http://localhost:8765. Add `?cgmock=1` to simulate the CrazyGames SDK (ads, gameplay events); `?cgmock=error` and `?cgmock=adblock` test the error and adblock paths.

## Controls

- Space / Up: fly (hold to rise, release to glide)
- Left / Right: slow down / speed up
- Z: shrink · X or hold Shift: grow
- C: golden glow when the devotion meter is full
- Esc: pause
- Touch: on-screen buttons · Mouse: click and hold to fly
