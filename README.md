# Web Sales Android 0.1.114-preview

Locally built preview of return/removal box cards. Installs as `ru.websales.helper.preview` alongside the production app; uses a separate preview signature, does not replace production or share its saved credentials. Configure sources in the preview app. Production update checks are disabled for this package.

Source commit: `81de46904f2b2999a3b0fd6a965a8964cf031848`. Source differences: preview package ID, app label, version suffix, preview signature and production update guard.

Android SDK 35, Gradle 8.11.1, JDK 17. Signature and packaged shared assets verified. No physical Android runtime test.
