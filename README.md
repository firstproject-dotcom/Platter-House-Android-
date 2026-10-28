# Platter House — Android MVP

**Brand:** luxury black, white and gold, with blue and green accents  
**Slogan:** “Taste the Difference.”  
**Currency:** South African Rand (ZAR / R)

## Included in this project
- Native Android app using Kotlin and Jetpack Compose
- Home screen with featured dishes and menu call-to-action
- Menu browsing by category
- Add-to-cart, quantity controls, remove items and subtotal
- Checkout form with collection or delivery selection and required-field checks
- Demo order confirmation and in-session order history
- Profile contact fields
- Branded dark theme and bottom navigation

## Important limitations
This is a functional **front-end MVP/demo**, not a production ordering service. Cart, profile and order data are kept in app memory and reset when the app process restarts. Checkout creates a local demo order only: there is no payment gateway, live restaurant backend, delivery integration, staff/manager dashboard, authentication, push notifications, or real order transmission. Do not treat a demo order as a real restaurant order.

## Build an APK in Android Studio
1. Extract this ZIP.
2. Open the extracted `platterhouse_project` folder in Android Studio.
3. Allow Gradle to sync and install the Android SDK components it requests (compile SDK 35).
4. Choose **Build → Build Bundle(s) / APK(s) → Build APK(s)**.
5. The debug APK is normally created at `app/build/outputs/apk/debug/app-debug.apk`.

The original uploaded project was incomplete: navigation referenced screen/view-model/domain classes that were not included, the repository contained placeholder `...` bodies, and the manifest referenced a missing theme resource. This MVP replaces those broken references with a self-contained app flow. A successful APK build still needs to be confirmed in an Android SDK/Gradle environment.
