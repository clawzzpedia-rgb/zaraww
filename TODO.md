# TODO: Fix index.html issues

## Plan Implementation Steps:
1. ✅ Persist admin mode with localStorage and auto-enable admin UI on load.
2. ✅ Add street name fetching via Nominatim API on position update, store in Firebase /street.
3. ✅ Update user card HTML to show street next to username: `${id} @${street}`.
4. ✅ Force list refresh after admin login to show buttons immediately.
5. ✅ Improve mic button text/logic: "MUTE" if active, "UNMUTE" if not.
6. ✅ Enhance deleteUser with success feedback.
7. ✅ Fix mute bug: sound continues after mute.
8. [ ] attempt_completion

**Status:** Mute now immediately stops new PeerJS calls + local state sync on toggle/snapshot. Test: Admin mute → no more audio transmission.
