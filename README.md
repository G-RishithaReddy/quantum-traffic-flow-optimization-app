# Quantum Traffic Flow Optimization

A smart traffic control system simulation with quantum optimization algorithms, built with React and TypeScript.

## 🌐 Live Demo

- **Production Site**: https://thriving-pony-2db6e3.netlify.app
- **GitHub Repository**: https://github.com/G-RishithaReddy/quantum-traffic-flow-optimization-app
- **AI Studio**: https://ai.studio/apps/drive/1dCHegDQGiA3lR5Ks7O74piv3Th-cDQU2

## 🚀 Run Locally

**Prerequisites:** Node.js

1. Install dependencies:
   ```bash
   npm install
   ```

2. (Optional) Set the `GEMINI_API_KEY` in `.env.local` to your Gemini API key for AI-powered quantum optimization explanations:
   ```
   GEMINI_API_KEY=your_api_key_here
   ```
   Note: The app works without the API key using mock data.

3. Run the development server:
   ```bash
   npm run dev
   ```

4. Open your browser and navigate to `http://localhost:3000`

## 📦 Build for Production

```bash
npm run build
```

The production build will be in the `dist` directory.

## 🚢 Deployment

This project is configured for deployment on:
- **Netlify**: Already deployed and configured with `netlify.toml`
- **Vercel**: Configured with `vercel.json`

### Deploy to Netlify
```bash
netlify deploy --prod
```

### Deploy to Vercel
```bash
vercel --prod
```
