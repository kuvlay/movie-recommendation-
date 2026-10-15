# Movie App · Expo Routing Prototype

An early mobile application exploring navigation with Expo Router. The current implementation provides a welcome screen, an onboarding screen, and a dynamic movie-detail route.

**Expo 52 · React Native · TypeScript · Expo Router · NativeWind**

[Portfolio](https://github.com/kuvlay)

## Implemented screens

| Route | Current behavior |
| --- | --- |
| `/` | Displays a welcome message and navigation links |
| `/onboarding` | Displays the onboarding placeholder |
| `/movie/[id]` | Reads the route parameter and displays the selected ID |

The repository name reflects the planned direction. A recommendation algorithm, movie catalog, search service, authentication, and external movie API are not implemented in the reviewed source.

## Run locally

Requirements: Node.js/npm and an Expo-compatible development environment. Use an emulator, development build, or Expo client compatible with the project's SDK version.

```bash
git clone https://github.com/kuvlay/movie-recommendation-.git
cd movie-recommendation-
npm ci
npm start
```

Additional launch scripts:

```bash
npm run android
npm run ios
npm run web
```

No application API keys or environment variables are required by the current screens.

## Structure

`app/_layout.tsx` configures the navigation stack. `app/index.tsx`, `app/onboarding.tsx`, and `app/movie/[id].tsx` define the screens. Styles use NativeWind/Tailwind configuration and `app/global.css`.

## Status

This is a navigation prototype. The inherited reset command references a missing script, and the Jest command does not have a corresponding installed Jest dependency or verified suite. No fresh mobile, web, or build validation was performed during this documentation update.

<details>
<summary>Credits and project history</summary>

Source lineage: [aarish-io/movie-recommendation-](https://github.com/aarish-io/movie-recommendation-). The original Expo starter lineage and contributor history are retained. No standalone license was present in the reviewed source.

</details>
