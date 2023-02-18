# 🔴 ISSUE README

Simply clone the repository and run:

```
npm install
npm run dev -- --open
```

You will see an `500 Error`, with the `DevTools` console showing the following:

<img width="320" alt="image" src="https://user-images.githubusercontent.com/20924663/219874310-25479066-68bf-4144-aab9-26240a3cc861.png">

🛠️ FIX!

Simply comment the two lines under the `FIXME:` on the `src/routes/+page.svelte` file, and save the file and reload the `npm run dev` browser link.
The error should be gone and all working correctly.