# Web Sales Android 0.1.128

Normal release: ru.websales.helper, versionCode146, label Web Sales. Same release certificate as 0.1.122–0.1.127.

Certificate SHA-256: ee7ac6dcdb06a55003fd21b500780749bc589c3f10ed6b1e2cba586ae4f178a7

Tab/search cancellation now aborts the request-owned physical socket using the pinned driver's Android-compatible API, rather than sending a detached CancelRequest and waiting for Statement.close(). Late aborts cannot close the next connection. The loading worker and query limits remain bounded.

The pickup badge reconciles with each complete unfiltered response. Production verification found 13 removal boxes plus one customer return; no nine-card backend limit. Filtering retains the total. No SQL, rights or filters changed.

Source: gross0509/web-sales, branch fix/android-return-tab-cancellation, commit 7921b47abbadd5342ed373a028bc888967acf675.

Verified: 116 automated checks; 11 real-driver JDBC tests; blocked-read cancellation regression fails on former code and passes on the new code; browser tab/count regression on both platforms; assembleRelease/lintVitalRelease; package/signature/assets/ZIP integrity. Physical phone behavior still requires confirmation. Pending cosmetic changes are not included.
