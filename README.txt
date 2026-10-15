BEAST WARS ENGLISH - HUMAN TEST BUILD v0.31

For Kettou Beast Wars - Beast Senshi Saikyou Ketteisen (Japan), Game Boy / Game Boy Color.
Unofficial, noncommercial, AI-assisted English fan translation. Human language review and a complete human playthrough are pending. This remains a partial draft release; automated coverage is not a whole-game completion percentage.

PATCHING
Apply ONE patch to a clean, matching Japanese ROM. IPS and xdelta produce the same 2 MiB result. Do not patch an older translated ROM or apply both patches. Begin from a fresh boot. Earlier emulator states can retain old artwork or text.
Source SHA-256: 73621246600e5c1cd4b18f55855b7d78f567e4dd6f621154dbbf37690b05276e
Source SHA-1: db690f46d37e0273c69f24badbb44588a363a84f
Source MD5: adfb8d9dc0d5633b1c385be79f3b425f
Source CRC32: 72895639
Source size: 1048576 bytes
Target SHA-256: see SHA256.json in this archive.

EARLIER v0.30 BATTLE AND SCENERY FIXES
- Scuba Dance 99: the late Japanese speech after the ellipsis now reads NO GOOD! The native ellipsis, balloon outline, sprite placement and timing are retained.
- Cheetus: the two timed ultimate callouts now read TAKE / THIS!!, with their original staggered sprite arrangement and outlines.
- Megatron: tighter spacing keeps IT'S OVER further inside the existing round-win balloon.
- Star Upper arena: crowd signs now read FIGHT!! and STAR UPPER, retaining the native purple/white colors, scenery, and repeating tile layout.
- Five additional source-linked workbook entries; all existing wording, human overrides and review cells were preserved.

v0.31 LANGUAGE POLISH
- Applied10 source-checked editorial recommendations across14 existing occurrences.
- Intro consistently describes the single Energon Crystal and uses a more natural sentence order.
- Special-move and Piyopiyo instructions read as grammatical commands, with original button order.
- Cheetus/Convoy profiles retain their original three-line paragraph height and describe mysterious planet Energoa naturally.
- Improved Artemis, Moon, Megatron, Galvatron and Cheetus dialogue for conversational flow and character voice.
- No optional terminology, menu-label, title-art or gameplay changes.

TRANSLATION AND PRESENTATION
- 1663 source-linked occurrences in the editable project workbook, with stable IDs and ROM locations. Existing source, wording, human override and review cells are preserved.
- Menus, options, character profiles and move explanations for the ten fighters; numbered and hidden tutorials; story/intro narration, endings, epilogues, staff text, password messages and minigame instructions/results.
- English title design with the approved gold/white dithered logo, two-line subtitle and continuously visible original white/red menu markers.
- Crystal intro preserves the swaying crystals and sparkles behind blank text pixels.
- Original menu colors, button icons and character artwork retained. Longer text uses proportional graphics through the native rendering paths; this is not a universal runtime VWF.
- This version fixes the separate CONFIRM/EXIT graphic atlas shared by the Run, Beast! and Fight, Beast! character-selection screens. Punch and both Guard selections retain their existing translated atlas.
- No gameplay or difficulty modifications are part of this patch. Original passwords and optional Soft Dip settings still work.

VERIFICATION
Fresh v0.31 build passes original-source change audit and all pixel-width limits. Original Japanese font remains byte-identical. Exact v0.30 comparison confines changes to English scripts/intro and generated fonts or their references; gameplay, title and ultimate/stage artwork remain byte-identical.
Changed profile/tutorial rows are checked on-screen in independent mGBA in CGB/DMG and both text settings. Native checks exercise full affected tutorial topics, all hidden-opponent intro literals, the Hard newsletter and all100 Guard result paths. Intro crystal motion/visibility and title/menu/selection markers are rechecked on the final build. Regenerated shared-font credit/result references are included in static audit and scoped regression checks. These are automated checks, not a complete human playthrough.
One legacy Run/Fight result-entry test does not reach its result in either the untouched v0.30 baseline or v0.31. No fresh runtime pass is claimed for that harness; its existing wording is unchanged, and current compiled mappings are checked separately.

Earlier project verification (not a fresh replay of every route in v0.31):
Independent mGBA coverage includes ten profile paths, eleven tutorial paths and ten ending-replay paths in CGB/DMG and both text settings. Scrolling epilogues and credits are checked through native replay states; earlier controller-only battle-clear routes remain separate evidence. Complete English row/heading pixels are compared, rather than relying only on successful menu entry.
One-player Team Mode wins/losses were exercised for both factions in both display modes; independent idle-loss and rematch checks also pass.
Hidden passwords, the combined unlock sequence, Ikard/Scylla/D-J minigame variants and held-Left Soft Dip entry were checked. The guide explains the button sequences and the blank password key.
The mapped 2054-candidate narrative inventory has no unhandled live prose candidates. Its 84 button/direction rows are preserved exactly, and 196 unmapped-source-glyph rows are bypassed by checked English redirects. This does not prove that arbitrary undiscovered graphics contain no text.
Fresh workbook build, checksum checks, declared-change audit and independent IPS/xdelta roundtrips are required for this package. Prior releases are retained separately.

HUMAN CHECKS STILL NEEDED
Read the included testing checklist. Review natural English, character voice, timing, usability, every mode and unusual outcomes during actual play. Linked multiplayer and a physical Game Boy Printer have not been verified. The guide includes crystal reward thresholds and tested passwords. Other encounter conditions reported by older guides are not all independently established.

CREDITS AND RIGHTS
AI assistance was used for extraction, programming, translation drafting, documentation and automated verification, with Japanese-source comparison and visual checks. Human review remains necessary.
Distributed free for noncommercial fan use. No ROM is included. Original game, artwork, names and Transformers characters remain the property of their respective rights holders. This project is unofficial and not endorsed by those owners. A noncommercial notice does not transfer ownership of the original materials or grant rights the contributors do not own.

The included player guide cites the older GameFAQs references used for cross-checking. Their prose and translations are not copied into the guide.

HIDDEN ULTIMATE INPUT
In the default game rules, use low health and a full BP gauge, then Down, back, Down, forward and A. The separate Up+A+B Hyper power-up blocks this command while active. This behavior was checked in the original ROM and is not changed by the patch.
