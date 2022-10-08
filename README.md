# Spotify 
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)![Spotify](https://img.shields.io/badge/Spotify-1ED760?style=for-the-badge&logo=spotify&logoColor=white)![Next JS](https://img.shields.io/badge/Next-black?style=for-the-badge&logo=next.js&logoColor=white)![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)<img src="https://raw.githubusercontent.com/hiverkiya/Spotify/main/public/recoil.svg" alt="drawing" style="width:64px; height:-0px;"/>
<p align="center">Spotify is a digital music service that gives you access to millions of songs</p>


https://user-images.githubusercontent.com/34170205/194730013-11bf449b-beb4-4d6d-b074-4d2bda16bb5e.mp4



<p align="center">Spotify Developer Dashboard showing Client ID, Client Secret Key and Redirect URIs</p>

    
 <kbd>
 <img src="https://user-images.githubusercontent.com/34170205/194730052-5fbde638-b4b8-4b45-9df2-aeee0aa1f312.PNG"/>
 </kbd>
 
## Features

- Authentication is handled by Oauth JWT, Nextjs Middleware, and NextAuth to authorize the user and allocate sufficient privileges.
- Built-in router from Next.js handles the app routing
- You can remotely control the active Spotify device to play, pause, shuffle or skip songs with additional functionality to tweak the volume with a debounce of 200 ms
- RefreshToken ensures the longevity  of AccessToken by handshaking with the SpotifyWebAPI
- A global state management is handled by Recoil for the playlist and song
## Tech
- [React](https://reactjs.org/) - A JavaScript library for building user interfaces
- [Next.JS](https://nextjs.org/) - Production framework for React
- [Tailwind CSS](https://tailwindcss.com/) - A utility-first CSS framework packed with classes that can be composed in the markup
- [Recoil](https://recoiljs.org/) - A state management library for React
- [Node.js](https://nodejs.org/en/) - A Javascript runtime built on Chrome's V8 Javascript engine
## Installation

Install the dependencies in the **spotify** folder and run the development server

```sh
npm install
npm run dev
```

For production environments

```sh
NEXTAUTH_URL = < Absolute URL (E.g. http://localhost:3000) >
NEXT_PUBLIC_CLIENT_SECRET = < Spotify Client Secret >
NEXT_PUBLIC_CLIENT_ID = < Spotify Client ID >
JWT_SECRET = <any string value here>
```

[![MIT License](https://raw.githubusercontent.com/hiverkiya/Spotify/main/public/license.svg)](https://github.com/hiverkiya/Spotify/blob/main/LICENSE)
