This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).
Dockerizing your Next.js application offers several compelling benefits that can streamline development, improve scalability, and simplify deployment. Some benefits include:

### Consistent Environment: 
Docker ensures your app runs the same across all stages of development and deployment.

### Dependency Management: 
It packages all dependencies, avoiding conflicts with other applications.

### Effortless Deployment: 
Docker makes deploying your app to any environment straightforward and consistent.

### Scalability: 
Easily scale your app with multiple container instances to handle increased traffic.

### CI/CD Integration: 
Automate builds, tests, and deployments seamlessly in your pipeline.
Resource Efficiency: Containers are lightweight, start quickly, and use fewer resources than virtual machines.

### Version-Controlled Infrastructure: 
Dockerfiles track your environment changes alongside your code.

### Microservices Compatibility: 
Easily run and manage microservices in isolated containers.

### Enhanced Security: 
Containers isolate apps, reducing risks of vulnerabilities spreading.

### Simplified Collaboration: 
Share and set up your app environment effortlessly with a single file.

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

## Runnung Dockerfile

Run the following docker command

```bash
docker build -t {name} {dockerfile path}
# or
docker build -t {name} . (current directory)

```

## Deploy on Render

The easiest and cheapest way to deploy your dockerized Next.js app is to use the [Render Platform](https://render.com/). Create a new WEB SERVICE and choose docker as your platform of choice.

