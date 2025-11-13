# Marketing
Marketing Web
"scripts": {
  "build": "next build"
},
"dependencies": {
  "next": "^14.0.0",
  "react": "^18.0.0",
  "react-dom": "^18.0.0"
}

{
  "scripts": {
    "build": "next build",
    "dev": "next dev",
    "start": "next start"
  }
}
  npm install next react react-dom
   npm ci
npm run build

/** @type {import('next').NextConfig} */
const nextConfig = {
  reactStrictMode: true,
  swcMinify: true,
  // Leave distDir as default ".next"
  // If you ever change it, update Netlify config accordingly
};

module.exports = nextConfig;
