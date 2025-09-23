
# Thursday 18 September 2025

*Hightlight*: Attended a meeting with Core maintainer for BlueWallet to discus pain points and focus areas
- He emphasized that BlueWallet was removed from FDroid becausing of licensing issue on one of the packages
- He suggested https://github.com/paulmillr/qr as a replacement
- I also took on a draft pr https://github.com/BlueWallet/BlueWallet/pull/7991 which was part of my proposal

  
*Non Highlight*: Attended an onboarding meeting with Kelvin
- Reminded us to complete engineering process document and to write the article about my story leading upto the grant
- Core maintainer requested my review on a PR we talked about during the Meeting
  
*Meta*
- Several other projects are facing a similar issue
- If I can fix it, it will not only benefit BlueWallet but also other projects
- I should create a draft and share by Monday 22 September

*End of day*
- I looked through the draft PR, most of the work was already done, should be easy for me to complete it
- This repo was very helpful https://github.com/sindresorhus/uint8array-extras

# Friday 19 September 2025

*Highlight*: Reviewed PR about removing `rn-nodeify` and other dependencies (https://github.com/BlueWallet/BlueWallet/pull/8086)
- The `rn-nodeify` package was removed and instead Metro is directly told how to resolve those Node APIs to React Native/browserify equivalents.
- `react-native-crypto` package required `rn-nodeify` so it was removed and substituted with `crypto-browserify` which is pure javascript and has no dependencies
- `path-browserify` package was removed as the package was not being used in the code. I commented about this in my review
- Links for some of the packages I read about
  - https://www.npmjs.com/package/rn-nodeify
  - https://www.npmjs.com/package/react-native-crypto
  - https://www.npmjs.com/package/crypto-browserify
  - https://www.npmjs.com/package/path-browserify
 
*Review*
- https://github.com/BlueWallet/BlueWallet/pull/8086#discussion_r2362749389
- https://github.com/BlueWallet/BlueWallet/pull/8086#pullrequestreview-3243132613

*Non highlights*
- Learnt the difference between shims and polyfills.

*End of day*
- Most urgent tasks include
  - Writing the article about my bitcoin journey
  - Finalizing the engineering process document
  - Submit form for monthly report
  - Completing the draft PR https://github.com/BlueWallet/BlueWallet/pull/7991 that is supposed to fix this https://github.com/BlueWallet/BlueWallet/issues/7662


# Saturday 20 September 2025

*Highlight*
- Looked at draft PR https://github.com/BlueWallet/BlueWallet/pull/7991 to understand work already written
- Asked a question whether all instances of Buffer should be replaced https://github.com/BlueWallet/BlueWallet/pull/7991#discussion_r2365636424
- Instances of buffer a being replaced with Uint8Array
- Read through the blog that talks about the migration https://sindresorhus.com/blog/goodbye-nodejs-buffer and the discussions https://github.com/sindresorhus/meta/discussions/22

*Non highlight*
- Created my task tracker on Notion https://www.notion.so/27478b86caaf80aa86bcc68af7554150?v=27478b86caaf80e39c67000ca71e6125


*Meta*
- I am getting most of the background knowledge and context, i need to read abit more and then start working on the code

# MOnday 22 September 2025

*Highlight*: COmpleted writing my article and also completed the engineering process document
- Started researching to work on comment from review https://github.com/BlueWallet/BlueWallet/pull/8032#issuecomment-3315991832
- 
