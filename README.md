# Web Sales Android 0.1.125

Normal release: ru.websales.helper, versionCode 143, label Web Sales. Same release certificate as 0.1.122–0.1.124.

Certificate SHA-256: ee7ac6dcdb06a55003fd21b500780749bc589c3f10ed6b1e2cba586ae4f178a7

A lost return SELECT response is retried once on a fresh connection, discarding partial rows. Cancelled searches, SQL errors, SQL timeouts and TLS failures are not retried. The loading journal now includes the submitted search text. Existing queue cancellation, card batch size and disabled Overview behavior are retained. Server queries, filters, SSL and ports were not changed.

Source: gross0509/web-sales, branch fix/android-return-read-retry, commit f7c761811dca7a33e3c187db2c6a755cb5caa5f5.

Verified: 116 automated tests; 8 real-driver JDBC recovery/cancellation tests on a local PostgreSQL wire peer; browser checks on both platforms; assembleRelease/lintVitalRelease; package, signature, shared assets and ZIP integrity. This does not establish the cause of the phone/network interruption. No physical-device installation test was performed.
