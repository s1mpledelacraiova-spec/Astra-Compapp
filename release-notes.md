Astra Companion 0.2.3 — sign-in recovery

Discord browser failures now offer a direct retry that keeps the current sign-in
attempt. Connection messages distinguish timeout, DNS, secure-connection, service
HTTP and unreadable-response failures with useful next steps.

Pairing, approved account controls and protected credentials are unchanged.
Install over the public 0.2.2 app; the release signing certificate is the same.
The universal APK supports Android 7.0+ on ARMv7, ARM64 and x86_64.

Verified with 177 automated tests, clean Flutter analysis, two synthetic live
sign-in checks, APK signature and 16 KB alignment checks. The original phone's
failure cause and this repair on that physical phone remain unverified.
