# Web Sales Android 0.1.124

Normal release: ru.websales.helper, versionCode 142, label Web Sales. Signed with the same release certificate as 0.1.122 and 0.1.123.

Certificate SHA-256: ee7ac6dcdb06a55003fd21b500780749bc589c3f10ed6b1e2cba586ae4f178a7

Includes cancellation of stale return searches, immediate removal of obsolete queued searches, protection against stale responses, six-card server batches (five visible plus one lookahead), and blocked Overview loading while the section is disabled. Pickup continues to load its complete list. Existing needs and return-card changes are retained.

Source: gross0509/web-sales, branch build/windows-0.1.72-android-0.1.124, commit 4e15ba3424550f1ba7cc30fd881309304297ab9c.

Verified: 116 automated tests; 2 JDBC cancellation JUnit tests; browser checks for Windows and Android; assembleRelease and lintVitalRelease; APK certificate/package, packaged shared assets, cancellation class and ZIP integrity. No physical-device installation or production-pooler cancellation test was performed.
