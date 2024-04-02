This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.tsx`. The page auto-updates as you edit the file.

[API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:3000/api/hello](http://localhost:3000/api/hello). This endpoint can be edited in `pages/api/hello.ts`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.




// Import the functions you need from the SDKs you need
import { initializeApp } from "firebase/app";
import { getAnalytics } from "firebase/analytics";
// TODO: Add SDKs for Firebase products that you want to use
// https://firebase.google.com/docs/web/setup#available-libraries

// Your web app's Firebase configuration
// For Firebase JS SDK v7.20.0 and later, measurementId is optional
const firebaseConfig = {
  apiKey: "AIzaSyBnFRVFqFsW-4OAD-ut7jfHu99ET0uix9c",
  authDomain: "openskill-5b20d.firebaseapp.com",
  projectId: "openskill-5b20d",
  storageBucket: "openskill-5b20d.appspot.com",
  messagingSenderId: "1060347525039",
  appId: "1:1060347525039:web:21def06647102f5091615a",
  measurementId: "G-MFDSPY5RY3"
};

// Initialize Firebase
const app = initializeApp(firebaseConfig);
const analytics = getAnalytics(app);



firebase init
firebase deploy


















<Titulo>{props.titulo}</Titulo>

flex bg-gradient-to-r justify-center items-center h-screen from-orange-600 to-amber-800



apiKey: process.env.NEXT_PUBLIC_FIREBASE_API_KEY,

        authDomain: process.env.NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN,
      
        projectId: process.env.NEXT_PUBLIC_FIREBASE_PROJECT_ID,




        <Image
          src={usuario?.imagemUrl ?? "/images/avatar-padrao.jpg"}
          alt="Avatar do Usuário"
          width={64}
          height={64}
          className={`
            w-10 h-10 rounded-full cursor-pointer
            ${props.className || ""} // Usando props.className e tratando caso seja undefined
          `}
        />
    