# Buon Appetito

This is my solution for the challenge Buon APPetito: https://bit.ly/3DdS5HY, which is part of the challenge series de Rviewer.

**User notes**

This app is a **PWA**: https://web.dev/i18n/es/progressive-web-apps/ made with **Next.js**: https://nextjs.org/ and it's deployed on **Vercel**: https://vercel.com/. You can visit it here: http://bit.ly/3EEaeiS.

**Technical notes**

This app doesn't have a database. There is a `data.json` file instead in the `db` directory, with the information of every pizza of the menu. And the image of every pizza is stored in the `public` directory. If anyone needs to add, remove or modify the menu, must edit that `data.json` file.

I didn't use any pre or post css processor or UI components. It's not fully responsive. It's customized to mobile phones in portrait mode. Maybe not so ok in old mobiles. It seems ok in tablets too. In PC screens it doesn't look bad, but feels too narrow.

I used Next.js' static-site generation: https://nextjs.org/docs/basic-features/data-fetching/get-static-props which helps to improve speed and to obtain a smoother experience.

I tested with **Jest**: https://jestjs.io/ and **React Testing Library**: https://testing-library.com/. I started testing components from the cart. There are components that are still not tested.

**To do**

- Make it fully responsive.
- Finish testing.
- Go for the extra points.

**Removed references to the QR code**

* In the first paragraph, the phrase "for the best experience I strongly recommend you to scan this QR with your mobile and even install it to use as any other app" has been removed.
* The QR code image has been removed.
