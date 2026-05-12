# salu-victoria

My submission for the Git assignment — a calculator app using Expo.

I haven't used React Native much before so this was a good learning experience. I followed the project structure from the `create-expo-app` template and then modified the components and theme to build out the calculator.

---

**To run it locally:**

```
npm install
npx expo start
```

---

The calculator handles basic maths operations. I picked a green colour theme because I like how clean it looks against white backgrounds. Dark mode also works — it switches to a brighter lime shade so it stays visible.

The trickiest part was getting the floating-point results to not show lots of decimal places (like when you do 1/3). I fixed this by rounding to 8 significant figures.
