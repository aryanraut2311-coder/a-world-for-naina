# Sound Adjustment UI Update Plan
Current: Range slider for volume. Goal: Replace with +/- buttons.

## Breakdown Steps:
1. [ ] Remove existing #volWrap slider div from index.html
2. [ ] Add new +/- volume buttons near #musicFab
3. [ ] Add CSS for .vol-btn classes (positioning, theme, hover)
4. [ ] Add JS: adjustVolume(delta) function (volume ±10%, clamp 0-100)
5. [ ] Update bgAudio.volume on button clicks
6. [ ] Test: Toggle music + volume up/down, verify audio levels
7. [ ] attempt_completion once verified

**Progress:** 0/7 complete

