# Electric spark – POV vidéo (salon terracotta)

Prompt image-to-video prêt à l'emploi pour Veo, Kling, Runway Gen-4, Sora, Luma, etc.

- **Image de départ :** `start-frame-living-room.jpg` (1920×1080, 16:9) — vue large du salon : mur terracotta, meuble TV blanc avec cheminée, lampadaire noir à abat-jour damier.
- **Durée :** 5–5,5 s · **Format :** 16:9 · **Mouvement caméra :** faible / handheld · **FPS :** 24 ou 30

---

## 1. Prompt complet (Veo, Sora, Kling 2.x – ~2 400 caractères)

```
Use the start image as the exact environment, framing, perspective and lighting. Keep the terracotta paneled wall, white floating TV unit with linear fireplace, cream modular sofa with grey throw, white sculptural pendant, black floor lamp with checkered shade, round boucle pouf, glossy black coffee table, herringbone wood floor, LED ceiling lines and soft indoor daylight unchanged and stable.

Single continuous photorealistic first-person handheld POV shot from eye-level smart glasses, 5 seconds, raw real-life footage of an impossible event. Subtle head movement, slight body sway, breathing motion, natural motion blur. No cinematic push-in, no floating camera, no cuts.

A realistic right hand enters the lower frame: five fingers, correct joints, visible knuckles and tendons, natural skin texture.

0–1.5s: thin, sharp, irregular high-voltage arcs with bright white cores and faint cool-blue edges crackle around the hand and forearm, snapping between fingertips, crawling over knuckles and wrist, branching outward for a split second. They flicker rapidly, cast tiny reflections on the skin and briefly light the cream sofa and the glossy coffee table. Fingers twitch involuntarily.

1.5–2.2s: the LED ceiling lines flicker once. The white sculptural pendant crackles and a small, bright, unstable spark of electricity detaches and falls slowly. The hand rotates inward, fingers spread and tense.

2.5–3.5s: the hand catches the spark. The arcs connect to it with a sharp snap; a brief white flash reflects on the terracotta wall and herringbone floor. Fingers close slightly, the spark pulses irregularly in the palm.

3.5–5s: the spark collapses into the fingers and fades. Arcs weaken and vanish one by one. LED lines return to normal, fireplace flames keep moving naturally. The hand relaxes and lowers, the view drifts slightly as the person exhales. Final frame: the full living room, calm and intact.
```

## 2. Prompt court (Runway / Luma – < 1 000 caractères)

```
Handheld first-person POV from smart glasses in this exact living room, photorealistic raw footage, subtle head sway and breathing, no push-in. A realistic right hand (five fingers, visible knuckles and tendons) rises into frame. Thin jagged white-core high-voltage arcs with faint blue edges snap between the fingertips and crawl over the wrist, flickering light on the cream sofa and glossy coffee table; fingers twitch. The LED ceiling lines flicker once; a small unstable spark drops slowly from the white sculptural pendant. The hand catches it with a sharp snap and a brief white flash on the terracotta wall and wood floor; the spark pulses in the palm, then collapses into the fingers. Arcs fade one by one, lights return to normal, fireplace flames keep moving. The hand lowers, the view settles on the calm, intact room.
```

## 3. Negative prompt

```
glowing hand, aura, energy ball, fog, smoke, neon streaks, lens flare, magic particles, sparkles, cartoon, CGI look, extra fingers, missing fingers, fused fingers, six fingers, two right hands, deformed hand, distorted wrist, floating camera, dolly zoom, cinematic push-in, camera cut, scene change, changing furniture, warping walls, flickering background, text, watermark
```

## 4. Réglages conseillés

| Outil | Réglages |
|---|---|
| **Veo 3** | Image-to-video, 16:9, 8 s puis couper à 5,5 s ; audio : crépitements électriques secs, souffle léger, feu discret |
| **Kling 2.x** | Mode *Professional*, 5 s, *creativity/relevance* ≈ 0,5, coller le négatif dans *Negative prompt* |
| **Runway Gen-4** | 5 s, prompt court (§2), *camera motion* faible |
| **Sora** | 16:9, 5 s, prompt complet ; si la main dérive, ajouter « the hand stays in the lower third of the frame » |
| **Luma Ray** | Start frame = image ; end frame = même image (garantit la pièce intacte à la fin) |

**Astuce :** si l'outil accepte une *end frame*, utiliser la même image de départ comme image de fin : le dernier plan retombe exactement sur le salon calme et intact.

Autres angles fournis (non utilisés comme image de départ) : chambre ×2, salon vue alternative, couloir avec tableaux.
