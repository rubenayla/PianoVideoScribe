<!-- consult selectively — grep, never read in full -->
# Current Session Checklist

Items the user requested during this session that need to be done or verified.

## Code changes in progress
- [ ] Move detector zone offsets to config files (not hardcoded) — partially done, need to pass cfg through
- [ ] Visual debug output: show detector zones on keyboard image, tempo, config path as default output when running the tool. Let the user verify at a glance.
- [ ] Save a config file for each test video

## Before declaring "done"
- [ ] Run ALL tests (test1, test2, test3) and verify they pass
- [ ] Export PDFs and visually check them (don't just trust MIDI data)
- [ ] Check for pitch substitution errors (A→A# etc)
- [ ] Verify left hand has chords where expected
- [ ] Verify right hand is monophonic where expected
- [ ] Check key signature is correct (E major = 4 sharps for test3)

## User feedback to incorporate
- [ ] Don't open MuseScore — give the user the file path to click
- [ ] Always search before asking the user how something works
- [ ] Always verify rendered output before claiming a fix works
- [ ] Don't hardcode coordinates — use config files
- [ ] The code should show diagnostic info (detector zones, tempo, config) by default
