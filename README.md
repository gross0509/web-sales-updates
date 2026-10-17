# Web Sales Windows 0.1.72

Portable x64 executable. Includes cancellation of stale return searches, immediate removal of obsolete queued searches, protection against stale responses, six-card server batches (five visible plus one lookahead), and blocked Overview loading while the section is disabled. Pickup continues to load its complete list. Existing needs and return-card changes are retained.

Source: gross0509/web-sales, branch build/windows-0.1.72-android-0.1.124, commit 4e15ba3424550f1ba7cc30fd881309304297ab9c.

Verified: 116 automated tests; 2 JDBC cancellation JUnit tests; browser checks for Windows and Android; packaged version and changed runtime modules; portable archive integrity. Native Windows execution and production-pooler cancellation were not tested in the Linux build environment.
