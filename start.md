Next.js is a fullstack React framework - an extension of React.  
Simplifies building fullstack apps with React.  
Vanilla React is a client-side JS library which runs in the browser.  
Downside - SEO sees limited page content.  
Next.js shows all page content in source code.
Next.js runs on both client and server.  

Install Node.js.  
cd to root. Following command creates project dir.  
`npx create-next-app@latest`  
`npm run build`  
`npm run start`

# Create routes and pages
`mkdir app/route`  
`echo > app/route/page.tsx`  
`mkdir app/meals/[meal]`  
`echo > app/meals/[meal]/page.tsx`

```
export default function Home() {
  return (
    <main>
      <h1>Home</h1>
    </main>
  );
}
```

# Reserved file names
`page.tsx`  
`layout.tsx`  
`not-found.tsx`  
`error.tsx`  
`loading.tsx`  
`route.tsx`  
