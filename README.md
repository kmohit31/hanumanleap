# Hanuman's Leap

A browser arcade game based on the Sundara Kanda of the Ramayana: Hanuman's journey across the ocean from Mahendra mountain to Lanka, to find Sita Maa in the Ashok Vatika.

Everything is in a single `index.html`: canvas art, Web Audio sound, and plain JavaScript, with no image or audio files.

## Status

- [x] 1. The Great Leap: fly over the ocean, collect lotus and orbs
- [x] 2. Mainaka Mountain: land on golden ledges to refill energy, but don't linger
- [x] 3. Surasa: grow to match her mouth, then shrink tiny and dart in and out
- [x] 4. Simhika: keep your shadow from her grasp, hide in clouds, dive to strike
- [x] 5. Lankini at the Gate: dodge her attacks, then land one mighty blow or slip between her feet
- [x] 6. Lanka by Night: stealth at cat size across rooftops, avoiding lantern light and guards
- [x] 7. Ashok Vatika: hide in the shimshapa tree until the guards sleep, then present Rama's ring to Sita Maa

## Run locally

```bash
python3 -m http.server 8765
```

Then open http://localhost:8765. Add `?cgmock=1` to simulate the CrazyGames SDK (ads, gameplay events); `?cgmock=error` and `?cgmock=adblock` test the error and adblock paths.

## Controls

- Space / Up: fly (hold to rise, release to glide); in Lanka by Night, jump (hold to float)
- Left / Right: slow down / speed up
- Z: shrink · X or hold Shift: grow (in Surasa's trial, hold to grow or shrink smoothly)
- Down: dive
- C: golden glow when the devotion meter is full
- Esc: pause
- Touch: on-screen buttons · Mouse: click and hold to fly
