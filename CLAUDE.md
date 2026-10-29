# Henrik Slater: Claude Code Instructions

Henrik Slater is a 1970s-styled AI influencer. "Earl" was his working name, so some older assets are still labeled "Earl"; it is the same character. The trained Soul was renamed to "Henrik Slater" on Oct 29, 2026.

The full locked design, every asset ID, and lessons learned are in `claude/earl-reference.md` (a copy of the reference file in the "Henrik Slater" claude.ai Project). Read it before starting any task. If it and this file ever disagree, the reference file wins; ask J if unsure.

## Roles
- J and the claude.ai chat (Henrik Slater Project) are in the driver's seat. They decide creative direction, approve looks, and approve anything that spends money or publishes.
- Claude Code executes: generate, check, organize, and report back. Do not make creative calls that change the character, and do not publish or post anything.
- When something is ambiguous, stop and ask J rather than guessing.

## Who Henrik is (short version)
- Light-skinned Black man, freckles, hazel eyes
- Large round reddish-brown afro
- Light brown tinted aviator glasses
- Reddish-brown U-shaped horseshoe mustache, ends down both sides of the mouth, not connected under the chin, no sideburns
- Signature: long, slightly exaggerated neck. Subtle, never stretched or distorted.
- Signature outfit: bright orange shawl-collar dinner jacket, sky blue ruffled tuxedo shirt, black velvet bow tie, light blue pocket square, dark green rose-print bell-bottoms, black dress shoes

## How to generate him
- Higgsfield workspace ID: d27b220d-bf6a-4aa8-8379-8e371bdf6b74
- Trained Soul V2: soul_id `cf90649c-188a-40c2-916e-0defb2d4a90f` (named "Henrik Slater" in Higgsfield)
- The Soul only works with models `soul_2` and `soul_cinematic`. Pass `soul_id` as a top-level param.
- Still describe his key features and outfit in every prompt; the Soul carries the face, the prompt carries the rest.
- Master close-up face anchor (for non-Soul models): media_id `0e0b3dd6-cc18-4ed2-b962-fa39ba11261c`
- Approved Soul test shots (Oct 29, 2026): 28a9a2c4-cf15-4e1f-b0c7-3aa72f6cb806 (diner), f1ac5a7a-7b61-4b93-89cc-b363be786fc5 (street), 944aee9a-3bef-464c-975d-bdb67d44c1f1 (record store)

## Quality check on every image (actually look at it)
1. Face matches the master close-up: glasses, mustache shape, freckles, afro color and shape
2. Neck is long but natural; reject both a normal-length neck and a stretched one
3. Outfit correct (unless the brief says otherwise)
4. No garbled text or signage in focus; no extra limbs or warped hands
5. Report honestly what failed. Never describe an image you have not viewed.

## Rules
- Never fabricate results or claim something worked without checking it
- Never use em dashes in any writing (captions included); use commas, colons, periods, or parentheses
- Get J's OK before spending more than 10 credits in one task, training a new Soul, buying anything, or posting/publishing anywhere
- Do not change Henrik's locked design or the Soul without J's approval

## Reporting back
At the end of each task, add a short report to `claude/henrik-reports.md` (newest on top): what was made, job IDs, credits spent, which images passed the check, which failed and why, and any open questions for J. Claude Code cannot write to the claude.ai Project directly, so the report lives in this repo for J or the chat to copy over.

## Current assignment
None yet. J sets it in the chat.
