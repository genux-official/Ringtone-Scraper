# Ringtone-Scraper
Free Ringtones - Download for Android &amp; iPhone - MeloBoom

## Installation

To use this module, you need to have Node.js and npm installed on your machine. You can install the required dependencies by running:

```bash
npm install @genuxofficial/ringtone
```

## Usage

First, require the module in your project:

```javascript
const { meloboom } = require('@genuxofficial/ringtone');
```

Then, you can use the meloboom function to search for audio tracks:

```javascript
async function run() {
    const sample = await meloboom('kgf');
    console.log(sample);
}
run();
```

## Example Response

The function returns an object with the following structure:

```javascript
{
  status: true,
  creator: 'Genux Official',
  result: [
    {
      title: 'KGF Maa theme',
      source: 'https://meloboom.com//en/r-mV7kkzN_V',
      audio: 'https://btones.b-cdn.net/fetch/e5/e57032b71eb71fa19fbeecba7c22dbb9.mp3'
    },
    {
      title: 'KGF Mothers love dj ',
      source: 'https://meloboom.com//en/r-Av23J7zc5',
      audio: 'https://btones.b-cdn.net/fetch/06/0695e1bae445adf4015deace5085acbd.mp3'
    },
    {
      title: 'KGF BGM',
      source: 'https://meloboom.com//en/r-oMHePTjXl',
      audio: 'https://btones.b-cdn.net/fetch/53/5312e5a67d58f2851c285641dc96daa7.mp3'
    },
    {
      title: 'Kgf Theme',
      source: 'https://meloboom.com//en/r-l42cdJ2RT',
      audio: 'https://btones.b-cdn.net/fetch/4e/4e691711bfa0d6f4b5bb0a3dc27f14b5.mp3'
    },
    {
      title: 'KGF Mother Remix',
      source: 'https://meloboom.com//en/r-mI4pft9xM',
      audio: 'https://btones.b-cdn.net/fetch/39/3966d6e0f8ce55e5e858af25adc65ffb.mp3'
    }
  ]
}
```