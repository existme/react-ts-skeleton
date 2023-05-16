# README
This repository serves as a starter template for building React applications with TypeScript. It provides a solid foundation and essential configurations to kickstart your React projects using the TypeScript language and React.

### Install TypeScript
``` shell
npm install -g typescript
```

### React and typescript setup
```shell
npx create-react-app my-app --template typescript
```
### Install ESLint & Prettier
In order to ensure that your code follows the rules of the project or your team, and the style is consistent, it’s recommended you set up ESLint and Prettier. To get them to play nicely, follow these steps to set it up.


``` shell
yarn add eslint @typescript-eslint/parser @typescript-eslint/eslint-plugin eslint-plugin-react --dev

yarn add prettier eslint-config-prettier eslint-plugin-prettier --dev
```
ESLint will use -> .eslintrc.js

### Cleanup

Remove test and jest, and web-vital dependencies if you don't need them:
``` shell
npm uninstall @testing-library/react @testing-library/jest-dom @testing-library/user-event react-test-renderer web-vitals jest
```
also remove the following files
``` shell
\rm src/setupTests.ts src/reportWebVitals.ts src/App.test.tsx 
```

---
Reference: [React with Typescript: Best practices](https://www.sitepoint.com/react-with-typescript-best-practices/)