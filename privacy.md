---
title: Privacy Policy
---

# PRIVACY POLICY

**Last updated September 16, 2026**

This Privacy Notice for unglazed ("**we**," "**us**," or "**our**") describes how and why we might access, collect, store, use, and/or share ("**process**") your information when you use our services ("**Services**"), including when you:

  * Download and use our mobile application (Fix My Korean), or any other application of ours that links to this Privacy Notice

  * Visit our website at [fixmykorean.com](https://fixmykorean.com), where the same checker runs in your browser

  * Engage with us in other related ways, including any support conversations

**Questions or concerns?** Reading this Privacy Notice will help you understand your privacy rights and choices. If you do not agree with our policies and practices, please do not use our Services. If you still have any questions or concerns, please contact us at [jjw3435@gmail.com](mailto:jjw3435@gmail.com).

## SUMMARY OF KEY POINTS

**What personal information do we process?** Almost none. Fix My Korean has no accounts and no sign-up. We do not collect your name, email address, phone number, contacts, location, or Apple's advertising identifier (IDFA).

**What happens to the text I check?** That depends on which checker you use. In the **iOS app**, the Korean text you entered goes over an encrypted connection straight to Google's Gemini API, and **we operate no server that stores it**. On the **website**, the request passes through a checking service we run (on Google Cloud, in the United States) before it reaches Gemini: that service never writes your text to its logs, but it does keep the *result* — the corrected sentence and the fragments it flagged — for 30 days, filed under a hash of what was submitted and linked to no person or device, so that repeating the same check is instant. In both cases Google processes the request under its own API terms ([Google APIs Terms of Service](https://developers.google.com/terms) and the [Gemini API Additional Terms](https://ai.google.dev/gemini-api/terms)). Do not enter passwords, financial details, or other sensitive personal information into the checker.

**What happens to photos I scan?** When you scan handwriting, the photo is sent over an encrypted connection to Google's Gemini API, which returns the text it reads so you can check it. We do not receive, log, or store the photo; Google processes it transiently to produce that text and, under the API terms linked above, does not use it to train its models. If the photo cannot be sent (for example when you are offline), the text is read on your device instead and the photo never leaves it.

**Where is my history stored?** In the app, your check history is stored only on your device. Deleting the app deletes it. It is never uploaded to us. The website keeps no history.

**Do you use cookies?** One, on the website: a first-party cookie named `__session` holding a random identifier, the moment it was created, your analytics choice, and — only if you accepted analytics — a copy of the Google Analytics session value. It is what lets us count returning devices without accounts, it expires 365 days after the last check you ran, and it is never used for advertising or shared with anyone.

**Do we use analytics, tracking, or ads?** We use Google Analytics to see how the checker is used — checks run, and which corrections people accept. In the app it records an app instance identifier, your device model, and an approximate country derived from a masked IP address. On the website we ask you first: Google Analytics is loaded only if you choose **Accept** on the banner, choosing **Decline** means the tag is never loaded and nothing is sent, and you can change your answer at any time through **Analytics settings** in the footer. Analytics never receives the text you check, your name, or Apple's advertising identifier (IDFA), and we do not track you across other apps or websites. There is no advertising in the app or on the site, and we never sell or share your information.

**Do we collect any information from third parties?** No.

## 1. WHAT INFORMATION DO WE PROCESS?

**Text you submit for checking.** The Korean sentences you type or paste are sent to Google's Gemini API solely to produce the grammar check result shown to you. From the **app**, the request goes from your device to Google and we neither receive, log, nor store the text. From the **website**, it passes through our checking service first, described under "Website data" below.

**Photos you scan.** When you use Scan, the photo of your handwriting (taken with the camera or chosen from your photo library) is sent to Google's Gemini API solely to transcribe it into text that appears in the editor for you to check. We do not receive, log, or store the photo on any server we operate. When the request cannot be made, the transcription runs on your device and the photo is not sent anywhere.

**Website data.** When you use the checker at fixmykorean.com, three things exist on our side and nowhere else:

  * **The `__session` cookie.** Our server sets it on the answer to a check. It holds a random identifier and the time it was first issued, your analytics choice, and — only while that choice is Accept — a copy of your Google Analytics session value, which lets a browser that has cleared its storage carry on as the same visitor instead of being counted as a new one. It carries no name, no email, and nothing you typed. It lasts 365 days, renewed each time you run a check, and declining analytics empties the Google Analytics part of it.

  * **Service logs.** One line per check: the random identifier from the cookie, how many days old it is, whether it was that device's first check, your analytics choice, the explanation language, how many paragraphs you submitted, a length band (for example "100-500 characters"), the politeness and context you selected, the verdict, how many issues were found, whether the answer came from the cache, and how long it took. **Your text and the corrections are not in it.** As on any web service, the underlying platform request log also records your IP address. Both are deleted after 30 days.

  * **The result cache.** To make a repeated check instant, the result — the corrected sentence and the flagged fragments, which for a fully rewritten sentence can amount to what you submitted — is stored for 30 days under a hash of the submitted content. It is filed by that hash alone, so it is tied to no person, device, or cookie, and it is deleted automatically when the 30 days are up.

**On-device data.** Your check history (the sentences you checked, verdicts, and corrections) is stored locally on your device so you can review past checks. It never leaves your device.

**Usage data.** On the website, and only after you press Accept on the analytics banner, Google Analytics collects the same events listed below, identified by the random identifier from the `__session` cookie rather than by anything about you. In the app, Google Analytics for Firebase collects app usage events on our behalf — app opens, checks run, corrections accepted or dismissed, source links opened, and errors shown — together with an app instance identifier that Google assigns to your installation, your device model and operating system version, your app version, and an approximate country derived from an IP address that Google masks. Events carry the length band of the text you checked (for example "100-500 characters"), never the text itself and never a correction. The app instance identifier is reset when you delete the app; it is not your Apple ID, not your name, and not Apple's advertising identifier (IDFA), which we never request.

We do not process any other personal information.

## 2. LEGAL BASES AND PURPOSE

We process the text you submit, and any photo you scan, only to provide the core function of the app and the website — checking Korean grammar — at your explicit request each time you press Check or Scan. We do not use them for any other purpose. The website's `__session` cookie and its service logs exist for the legitimate interest of running the service and knowing how many devices use it; the website's analytics run on your consent alone, which you may withdraw at any time.

## 3. WHEN AND WITH WHOM DO WE SHARE YOUR INFORMATION?

The only third party that receives your submitted text or scanned photos is **Google LLC** (Gemini API), strictly to generate the check result or the transcription. The same company, acting as our analytics provider, receives the usage events described in Section 1, and — as the cloud provider hosting the website's checking service, its logs and its result cache in the United States — stores them on our behalf under our instructions. We do not sell, rent, or trade any information. We have no advertising partners and no data brokers.

## 4. HOW LONG DO WE KEEP YOUR INFORMATION?

From the app we keep none of your content: we operate no server that stores it. On-device history is retained until you delete the app or remove the entries yourself. From the website we keep the service logs and the result cache described in Section 1 for **30 days**, and the `__session` cookie lives 365 days from the last check it accompanied. Usage events held in Google Analytics are retained for 14 months from your most recent activity, after which Google deletes them; aggregate reports built from them may remain. Google's transient processing of Gemini API requests — text and photos alike — is governed by Google's terms linked above.

## 5. HOW DO WE KEEP YOUR INFORMATION SAFE?

All network requests use encrypted connections (HTTPS/TLS). The app stores nothing on our servers at all. For the website, the only content we hold is the 30-day result cache described in Section 1, which is filed under a content hash with no identity attached to it.

## 6. WHAT ARE YOUR PRIVACY RIGHTS?

Depending on your region (for example the EEA, UK, or California), you may have rights such as access, correction, deletion, and portability. Because we hold so little, most requests can be satisfied by you alone: deleting the app removes everything stored on your device, and clearing site data for fixmykorean.com in your browser removes the `__session` cookie along with your saved settings, after which the identifier it held is gone. You can withdraw consent to analytics at any time through **Analytics settings** in the website footer, as easily as it was given. For anything else, contact us at [jjw3435@gmail.com](mailto:jjw3435@gmail.com) and we will respond within 30 days.

## 7. DO WE COLLECT INFORMATION FROM MINORS?

We do not knowingly collect data from or market to children under 18 years of age. Neither the app nor the website asks for an account, a name, or any contact details.

## 8. UPDATES TO THIS NOTICE

We may update this Privacy Notice from time to time. The updated version will be indicated by an updated "Last updated" date at the top of this page. If we make material changes, we will notify you within the app, on the website, or on this page.

## 9. HOW CAN YOU CONTACT US?

If you have questions or comments about this notice, email us at [jjw3435@gmail.com](mailto:jjw3435@gmail.com).
