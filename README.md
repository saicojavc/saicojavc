<div align="center">

### Jorge Adrián Valdés Camacho

**Android engineer · Miami, FL** — Kotlin, Jetpack Compose, Clean Architecture.

Three years shipping native Android. Authorized to work in the US — no sponsorship needed.

[Portfolio](https://jorge-android-dev.web.app) · [CV](https://jorge-android-dev.web.app/cv) · [LinkedIn](https://www.linkedin.com/in/jorge-adrián-valdés-camacho-21b371221/) · [Email](mailto:jorgito.avc03@gmail.com)

</div>

---

## Building

**[Mi mercado](https://github.com/saicojavc/Mi-mercado)** — a grocery list a whole family shares. Product catalogue from the USDA FoodData Central API, barcode scanning for physical products, custom items when the catalogue has nothing, households joined by invite code, and every item records who added it.

`Kotlin` · `Compose` · `Firebase` · `CameraX` — in internal testing on Google Play.

## Shipped

**FitLog** — offline-first fitness tracker. GPS session engine, MET-based calorie estimation living in the domain layer with unit tests, foreground services for step counting, PDF export.

`Kotlin 2.1` · `Compose` · `Room` · `Firebase` — [live on Google Play](https://play.google.com/store/apps/details?id=com.saico.fitlog) · [case study](https://jorge-android-dev.web.app/projects/fitlog)

**Ticket** — Android client for a national reservations platform. Seventeen Gradle modules with a `build-logic` convention plugin; a feature module can't import another feature, everything goes through the domain. Client work, no public repo — [case study](https://jorge-android-dev.web.app/projects/ticket)

## In progress

**ADA** — a task app that decides what to put in front of you. Five independent analysers combined into one score, with a recency penalty so the same task doesn't win every session. Runs entirely on device, no backend.

`Kotlin` · `Compose` · `Room` · `Hilt`

## How I work

- The rule that decides what the user sees lives in the domain layer, not in the ViewModel.
- A feature module is a closed box: if two of them need to talk, that's a missing contract, not an import.
- A screen isn't finished until I know what it does with no network, at 60 fps, on a mid-range phone.

## Stack

`Kotlin` · `Coroutines / Flow` · `Jetpack Compose` · `Hilt` · `Room` · `Retrofit` · `Firebase` · `Gradle KTS` · `GitHub Actions` · learning Kotlin Multiplatform

