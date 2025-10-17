# Saturday 4 October 2025

*Highlight*
- Researched about `react-native-camera-kit` package and the issue is that it uses ML-Kit which is a proprietory software and cant be audited, FDroid doesnt allow projects using such packages to be listed

*Meta*
- Might have to create a native module to solve this issue
- Get camera feed using native module and send to js for decoding


# Sunday 5 October 2025

*Hightlight*
- Created PR https://github.com/BlueWallet/SilentPayments/pull/24 in SilentPayments to remove `Buffer`
- Created PR https://github.com/BlueWallet/BlueWallet/pull/8106 to fix issue of background color on seedwords and closed https://github.com/BlueWallet/BlueWallet/pull/8032

*Meta*
- Had indicated I could not remove all the Buffer because Uint8Array did not have `readUint32LE` but a contributor gave me the function so will use it and update my PR

*End of day*
- Reflect on grant proposal and see work on next
- Fix a few issues on BlueWallet as I brainstorm how to fix FDroid issue


# Monday 6 October

*Highlight*
- Reviewer requested for changes on my PR https://github.com/BlueWallet/BlueWallet/pull/8105 and I worked on all he requested
- Also comment on  https://github.com/BlueWallet/SilentPayments/pull/24 asking if the person who shared code for `readUint32` already as implementations for `readUint16LE`

# Tuesday 7 October

*Highlight*
- Worked on the request for review for https://github.com/BlueWallet/SilentPayments/pull/24 from a reviewer
- Looked at npm warnings and the packages causing everything

*Non highlight*
- Attended bi weekly standup meeting with the rest of Btrust grantees


# Wednesday 8 October 2025

*Highlight*
- Tested out paulmillr/qr package
- Worked well but coulf not decode eci qr codes (ECI (Extended Channel Interpretation))
- Want to test more before I open an issue
- Also checkout the jsQR package(https://github.com/cozmo/jsQR?tab=readme-ov-file)

*Non-highlight*
- Tried creating native module to get camera feed and send for decoding
- Was not succesful, will keep testing and trying out

*Meta*
- Most stressfull day, native module did not work out, been stuck trying different things whole day

*End of day*
- Keep trying the native module


# Thursday 9 October 2025

*Highlight*
- Got the native module to work at 5 fps
- Was able to scan some qr codes
- package doesnt scan ECI qr codes (need to test more)

*Meta*
- Finally got it to work
- Need to test alot
- Need to try integrating with BlueWallet


# Thursday 16 October
*Highlight*
- Noticed and issue and reported https://github.com/BlueWallet/BlueWallet/issues/8127
- Reviewed PR (https://github.com/BlueWallet/BlueWallet/pull/8118)
- Fixed issues raised by reviwer(https://github.com/BlueWallet/BlueWallet/pull/8124) and PR was merged

# Friday 17 October 2025

*Highlight*
- Found out cause of the error I reported (https://github.com/BlueWallet/BlueWallet/issues/8127), it is happening because I have the Github mobile app and the code is set to open  https://github.com/BlueWallet/BlueWallet/.
- Could be fixed by changing the link to anyother or just trimming it to https://github.com. I have tested both solutions

*Meta*
- Will add the comment under the issue and steps to produce and what is causing it

