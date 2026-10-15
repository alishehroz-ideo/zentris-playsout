# ZENTRIS · Playsout pilot (Phase A)

Guest WebGL build for the Playsout pilot: opens straight into play, no login, shows the result and restarts.
No GameBull or other network calls; no Playsout SDK yet (that is Phase B).

- Unity 6000.4.3f1 · source `g-b-store/zentris-gamebull`, branch `playsout-pilot`, commit `54870bf`
- Brotli with decompression fallback (works on hosts that send no `Content-Encoding: br`, such as GitHub Pages)
- Output folder 14.75 MB
