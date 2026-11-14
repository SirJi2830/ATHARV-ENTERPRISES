ATHARV ENTERPRISES - DELETE FIX UPDATE

Files:
- index.html: updated offline browser app source.

Fixes:
- Common delete handler for expense, payment, material and machinery records.
- Delete controls added to Materials and Machinery.
- Project deletion removes linked records from all supported sections.
- More robust handling of stored data arrays and storage write errors.

How to test:
1. Open index.html in the same browser/WebView profile used by the app.
2. Create a test project.
3. Add one expense, payment, material record and machinery log.
4. Delete each test record and confirm it disappears after the screen refreshes.
5. Reopen the app and verify the deleted records remain deleted.

Important:
This is an updated HTML source package, not a signed Android APK. The existing APK must be rebuilt/repackaged with this source for the fix to appear in the installed Android app. Export a JSON backup before replacing or reinstalling the app.
