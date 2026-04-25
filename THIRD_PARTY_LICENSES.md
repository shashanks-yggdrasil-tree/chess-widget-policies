# Third-Party Licenses and Attributions

This project includes third-party libraries and art assets.  
For commercial distribution, keep this file up to date.

## Runtime Dependencies

1. `androidx.core:core-ktx:1.15.0`  
   License: Apache-2.0  
   Source: https://developer.android.com/jetpack/androidx/releases/core

2. `com.google.android.material:material:1.12.0`  
   License: Apache-2.0  
   Source: https://github.com/material-components/material-components-android

3. `androidx.browser:browser:1.8.0`  
   License: Apache-2.0  
   Source: https://developer.android.com/jetpack/androidx/releases/browser

4. `androidx.security:security-crypto:1.1.0-alpha06`  
   License: Apache-2.0  
   Source: https://developer.android.com/jetpack/androidx/releases/security

5. `com.github.bhlangonijr:chesslib:1.3.6`  
   License: Apache-2.0  
   Source: https://github.com/bhlangonijr/chesslib

6. `com.android.billingclient:billing-ktx:7.1.1`  
   License: Android Software Development Kit License  
   Source: https://developer.android.com/google/play/billing

7. `androidx.navigation:navigation-fragment-ktx:2.7.7`  
   License: Apache-2.0  
   Source: https://developer.android.com/jetpack/androidx/releases/navigation

8. `androidx.navigation:navigation-ui-ktx:2.7.7`  
   License: Apache-2.0  
   Source: https://developer.android.com/jetpack/androidx/releases/navigation

## Chess Piece Assets

Piece drawables are generated from `lichess-org/lila` sources:
https://github.com/lichess-org/lila/blob/master/COPYING.md

1. In-app `Neo` piece set  
   Upstream set: `public/piece/chessnut`  
   License: Apache-2.0

2. In-app `Classic` piece set  
   Upstream set: `public/piece/rhosgfx`  
   License: CC0-1.0

Generation script:
`tools/generate_licensed_piece_vectors.py`

## Lichess Service Usage

This app consumes Lichess APIs and content. Commercial use depends on Lichess terms and API limits:

1. Terms: https://lichess.org/terms-of-service  
2. API tips and rate limits: https://lichess.org/page/api-tips

Operational notes based on current Lichess API docs:
1. Lichess API requests are rate-limited and HTTP 429 responses must be respected.
2. Puzzle endpoints must not be used for mass enumeration/download; use public database exports when needed.
3. OAuth scopes must be limited to the minimum required permissions.

Trademark notice:
Lichess is a third-party trademark/service. This app is independent and not affiliated with or endorsed by Lichess.

Important: Lichess may change limits, access rules, and service terms over time.

## Widget Preview Photo

1. `app/src/main/res/drawable-nodpi/widget_preview_photo.jpg`
   Title: Chess board with pieces
   Author: Aaaatu (Wikimedia Commons)
   Source: https://commons.wikimedia.org/wiki/File:Chess_board_with_pieces.jpg
   License: CC BY-SA 4.0
   License URL: https://creativecommons.org/licenses/by-sa/4.0/

## App Launcher Icon

1. Custom chess knight silhouette (original design)
   Files: `ic_launcher_foreground.xml`, `ic_launcher_monochrome.xml`
   License: Part of this project
