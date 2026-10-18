# Web Sales Android 0.1.127

Normal release: ru.websales.helper, versionCode145, label Web Sales. Same release certificate as 0.1.122–0.1.126.

Certificate SHA-256: ee7ac6dcdb06a55003fd21b500780749bc589c3f10ed6b1e2cba586ae4f178a7

Return cards and counter now use the parameterized extended PostgreSQL protocol, as the desktop does, with prepareThreshold=0 and unnamed statements/portals for transaction pooling. Query text, filters, pagination, one-time bounded recovery, cancellation, SSL and ports are preserved. The journal identifies the mode and the timeout message no longer attributes a connection read failure to database execution.

This is a candidate correction for a confirmed client transport difference. The production timeout has not been reproduced locally or proven resolved on the phone.

Source: gross0509/web-sales, branch fix/android-return-extended-protocol, commit ff7559101c107e05cd061f0338ffec660be6d203.

Verified: 116 automated checks, 9 real-driver JDBC tests including a large fragmented Unicode response, complete ReturnsProtocolProbe, assembleRelease/lintVitalRelease, signature/package/DEX/shared assets/ZIP integrity. No physical-device installation test.
