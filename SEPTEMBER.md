
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

*End of day*
- Most urgent tasks include
  - Writing the article about my bitcoin journey
  - Finalizing the engineering process document
  - Completing the draft PR https://github.com/BlueWallet/BlueWallet/pull/7991


