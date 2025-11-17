# HycreD React Template (Web/Android)

## Includes
- React
- Vite
- Tailwind
- ShadCN
- Capacitor

## Usage:
1. Clone the repository:
```sh-session
git clone https://github.com/hycred/react-template-android
```

2. Replace all instances of `hycred-template` or `hycred-app` with app name. To find out:
```sh-session
grep -RI 'hycred*'
```

3. Install dependencies and sync capacitor
```sh-session
npm i
npm run build
npx cap add android
npx cap sync
```

4. Build, test and run
```sh-session
npm run dev # For web
npx cap open android # For android
```

5. Change remote and push
```
git remote set-url origin <new-origin>
git pusb -u origin master
```