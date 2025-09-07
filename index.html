# Create project folder
New-Item -ItemType Directory -Path facebook-landing
cd facebook-landing

# Create pages folder
New-Item -ItemType Directory -Path pages

# package.json
@"
{
  "name": "facebook-landing",
  "version": "1.0.0",
  "private": true,
  "scripts": {
    "dev": "next dev",
    "build": "next build",
    "start": "next start"
  },
  "dependencies": {
    "next": "13.5.4",
    "react": "18.2.0",
    "react-dom": "18.2.0"
  }
}
"@ | Out-File -FilePath package.json -Encoding utf8

# next.config.js
@"
const nextConfig = { reactStrictMode: true };
module.exports = nextConfig;
"@ | Out-File -FilePath next.config.js -Encoding utf8

# pages/index.js
@"
import Head from 'next/head';
export default function Home({ images }) {
  return (
    <>
      <Head>
        <title>4K Videos</title>
        <meta property='og:title' content='4K Videos'/>
        <meta property='og:description' content='लाला लाला जिंगाहू'/>
        <meta property='og:type' content='website'/>
        {images.map((img,i)=><meta key={i} property='og:image' content={img}/>)}
        <meta name='twitter:card' content='summary_large_image'/>
        <meta name='twitter:title' content='4K Videos'/>
        <meta name='twitter:description' content='लाला लाला जिंगाहू'/>
        <meta name='twitter:image' content={images[0]}/>
      </Head>
      <main style={{textAlign:'center',padding:'60px'}}>
        <h1 style={{fontSize:'3rem',color:'#222'}}>4K Videos</h1>
        <p style={{fontSize:'1.5rem',color:'#555'}}>लाला लाला जिंगाहू</p>
        <p style={{marginTop:'20px',fontSize:'1rem',color:'#999'}}>(VIP Landing Page – Facebook preview हर बार नया होगा 🎉)</p>
      </main>
    </>
  );
}
export async function getServerSideProps() {
  const baseImages = Array.from({length:30},(_,i)=>https://picsum.photos/1200/630?random=${i+1});
  const shuffled = baseImages.sort(()=>0.5-Math.random());
  const images = shuffled.map(img=>${img}&v=${Date.now()});
  return { props:{images} };
}
"@ | Out-File -FilePath pages\index.js -Encoding utf8
