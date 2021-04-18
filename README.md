This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.js`. The page auto-updates as you edit the file.

[API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:3000/api/hello](http://localhost:3000/api/hello). This endpoint can be edited in `pages/api/hello.js`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.

## Dokumentasi
1. Extrak file setup-next.js kemudian lakukan npm i 
2. Selanjutnya kita akan membuat file yang telah di ekstrak berjalan sebagaimana mestinya.

### Buat halaman pertama
3. Tambah file index.js didalam folder pages, kemudian kita dapat menjalankan <h5> npm run dev. </h5>. untuk nama file index.js adalah nama spesial yang digunakan dalam akses pertama ke aplikasi. 
    - index.js
    ```js
    export default function HomePage() {
        return (
            <div>
                <h1>The HomePage</h1>
            </div>
        )
    }
    ```

4. Selanjutnya, kita bisa membuat file lagi dalam folder pages, dengan nama profile.js, dan contact.js
    - profile.js
    ```js
    export default function profile() {
    return (
        <div>
            <h3>Halaman profile</h3>
        </div>
      )
    }
    ```
    - contact.js
    ```js
    export default function contact() {
        return (
            <div>
                <h3>Halaman Kontak</h3>
            </div>
        )
    }
    ```