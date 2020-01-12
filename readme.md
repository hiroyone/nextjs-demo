# NextJS
This repo is about successfully installing NextJS and creating a demo app.
Ref) https://nextjs.org/learn/basics/getting-started

# The benefits of NextJS
- An intuitive page-based routing system (with support for dynamic routes)
- Automatically statically optimizes page(s) when possible
- Server-side renders page(s) with blocking data requirements
- Automatic code splitting for faster page loads
- Client-side routing with optimized page prefetching
- Webpack-based dev environment which supports Hot Module Replacement (HMR)
- API routes to build your API with serverless functions, with the same simple router used for pages
- Customizable with community plugins and with your own Babel and Webpack configurations

# Installations
Let's say the name of your project is hello-next
```
mkdir hello-next
cd hello-next
npm init -y
npm install --save react react-dom next
mkdir pages
```
Then open the package.json file in the hello-next directory and replace scripts with the following:

"scripts": {
  "dev": "next",
  "build": "next build",
  "start": "next start"
}

Run the following command to start a dev server in Next.
```
npm run dev
```
`404 error page should appear at this point.`

# Create the first page
Create a file named pages/index.js and add the following content:

```
const Index = () => (
  <div>
    <p>Hello Next.js</p>
  </div>
);

export default Index;
```

Okay! So keep going!