# TODO: Fix index.html issues

## Plan Implementation Steps:
1. ✅ Persist admin mode with localStorage and auto-enable admin UI on load.
2. ✅ Add street name fetching via Nominatim API on position update, store in Firebase /street.
3. ✅ Update user card HTML to show street next to username: `${id} @${street}`.
4. ✅ Force list refresh after admin login to show buttons immediately.
5. ✅ Improve mic button text/logic: "MUTE" if active, "UNMUTE" if not.
6. ✅ Enhance deleteUser with success feedback.
7. ✅ Fix mute bug: sound continues after mute.
8. ✅ Persist audio across browser close/reopen.
9. ✅ Real-time street updates on every move.
10. ✅ Battery indicator per user.
11. [ ] attempt_completion

**Status:** Street updates live (every GPS tick), battery % + charging icon + street timestamp. UI enhanced with multi-info row. Complete!
