SCHEDULER - iPhone app project
==============================

STEP 1 - Build the .ipa (no Mac needed)
1. Create a free account at github.com and make a new repository.
2. Upload everything from this folder to it (keep the ".github" folder).
3. Open the repository's "Actions" tab > "Build IPA" > "Run workflow".
4. When it finishes (about 3-5 minutes), open the run and download
   "Scheduler-ipa". Unzip it to get Scheduler.ipa.

STEP 2 - Install with 3uTools
1. Connect the iPhone by USB, tap Trust, and open 3uTools.
2. The .ipa is unsigned, so sign it with your Apple ID first
   (3uTools: Toolbox > IPA Signature, or the Sideload option), then install
   the signed .ipa. Menu names can differ between 3uTools versions.
3. On the iPhone: Settings > General > VPN & Device Management >
   trust your Apple ID.

NOTES
- A free Apple ID signature lasts 7 days; sign and install again to renew.
  Your saved records stay on the phone if you install over the same app.
- If you have a Mac: install XcodeGen (brew install xcodegen), run
  "xcodegen generate", and open Scheduler.xcodeproj in Xcode.
- The app screen is Scheduler/index.html. To change the app, edit that file.
