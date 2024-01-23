# Bootstrap

```bash
npx ionic start
```

```bash
npm install @capacitor/cli
npm install @capacitor/ios
npm install @capacitor/android
```

```bash
ionic capacitor add ios
ionic capacitor add android
```

### Get some plugins 👉 [Plugins](https://capacitorjs.com/docs/apis)

```bash
npm install @ionic/pwa-elements

npm install @capacitor/toast
npm install @capacitor/device
npm install @capacitor/dialog
npm install @capacitor/preferences
npm install @capacitor/screen-orientation
```

### Build

Remove `/android` directory if you have one

Close `android studio` if already opened

```bash
ionic capacitor copy android
ionic capacitor copy android -l
```

```bash
ionic capacitor sync android
npx cap sync
npx cap update
npx cap open android
```

```bash
npm start
```
