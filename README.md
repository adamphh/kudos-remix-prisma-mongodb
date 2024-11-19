# This project is https://www.prisma.io/blog/fullstack-remix-prisma-mongodb-1-7D0BfTXBmB6r

# Tailwindcss
https://tailwindcss.com/docs/guides/remix

# Technologies we will use
Throughout this series you will be using the following tools to build this application:
- [MongoDB](https://www.mongodb.com/) as the database
- [Prisma](https://www.prisma.io/) as your Object Document Mapper (ODM)
- [Remix](https://remix.run/) as the React framework
- [TailwindCSS](https://tailwindcss.com/docs/guides/remix) for styling the application
- [AWS S3](https://aws.amazon.com/) for storing user-uploaded images
- [Vercel](https://vercel.com/) for deploying the application

# Reference resources
- https://blog.logrocket.com/building-full-stack-app-with-remix-prisma/
- https://dev.to/hackmamba/building-a-full-stack-app-with-remix-prisma-and-neon-3hf0?signin=true

# Welcome to Remix!

- 📖 [Remix docs](https://remix.run/docs)

## Development

Run the dev server:

```shellscript
npm run dev
```

## Deployment

First, build your app for production:

```sh
npm run build
```

Then run the app in production mode:

```sh
npm start
```

Now you'll need to pick a host to deploy it to.

### DIY

If you're familiar with deploying Node applications, the built-in Remix app server is production-ready.

Make sure to deploy the output of `npm run build`

- `build/server`
- `build/client`

## Styling

This template comes with [Tailwind CSS](https://tailwindcss.com/) already configured for a simple default starting experience. You can use whatever css framework you prefer. See the [Vite docs on css](https://vitejs.dev/guide/features.html#css) for more information.
