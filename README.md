This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

## Struktur Project

Folder utama aplikasi berada di `src/`:

| Folder | Tanggung jawab |
| --- | --- |
| `src/app` | Routing, halaman, layout, dan konfigurasi global Next.js App Router. |
| `src/components/custom-ui` | Komponen UI khusus yang memiliki perilaku atau tampilan spesifik aplikasi. |
| `src/components/layouts` | Komponen layout reusable seperti header, sidebar, dan footer. |
| `src/components/ui` | Komponen UI reusable dasar seperti button, modal, dan input. |
| `src/config` | Konfigurasi aplikasi seperti environment, endpoint, dan pengaturan global. |
| `src/features` | Modul fitur beserta komponen dan hooks yang hanya digunakan oleh fitur tersebut. |
| `src/features/dashboard/components` | Komponen khusus halaman dashboard. |
| `src/features/dashboard/hooks` | Hooks khusus untuk fitur dashboard. |
| `src/hooks` | Hooks reusable yang digunakan lintas fitur. |
| `src/lib` | Integrasi dan helper library pihak ketiga atau infrastruktur aplikasi. |
| `src/services` | Service untuk komunikasi dengan API atau sumber data eksternal. |
| `src/shared/constants` | Nilai konstan yang digunakan lintas fitur. |
| `src/shared/service` | Shared service atau logika data yang digunakan lintas fitur. |
| `src/shared/state` | State global atau store bersama. |
| `src/shared/utils` | Utility reusable yang digunakan lintas fitur. |
| `src/types` | Tipe dan interface global TypeScript. |
| `src/utils` | Fungsi utilitas umum aplikasi. |

Folder yang saat ini masih kosong menggunakan `.gitkeep` agar struktur tetap tercatat oleh Git.

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

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.
