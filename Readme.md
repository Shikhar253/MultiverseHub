# MultiverseHub: Where Dimensions Collide

Discover a new realm of online interaction with MultiverseHub! Seamlessly blending user management, video hosting, social engagement, and more, MultiverseHub invites you to navigate through a dynamic universe of content creation and community connection. From managing your profile to curating playlists, liking videos, and exploring channel statistics, MultiverseHub is your all-in-one destination for a diverse online experience. Embark on a journey through the multiverse of possibilities – register, upload, engage, and redefine your online presence with MultiverseHub!

# Celestial Platform: User & Content Universe

## Access and Identity

### 🚀 Onboarding to Infinity
- Journey through realms by registering for an account.
- Secure your presence with JWT-fueled login.
- Conclude your expedition with a logout ritual.
- Rediscover forgotten paths with a password reset feature.

### 🌌 Profile Cosmos
- Shape your cosmic presence in the Multiverse.
- Unveil avatars and cover images like cosmic artworks.
- Refine your essence with personalized details.

### 🕰️ Chronicles of Watching
- Unveil the cosmic tapestry with tracked watch histories.
- Each experience leaves an imprint in the celestial records.

## Cosmic Videoscape

### 🎥 Stellar Cinematics
- Channel your creativity by uploading and publishing videos.
- Control the visibility – unveil to the universe or keep it within your cosmic sanctuary.

### 🔍 Searching Nebulas
- Navigate the cosmic expanse by searching videos with diverse criteria.
- Sort and paginate through celestial video results.

### ✂️ Cosmic Editing and Annihilation
- Sculpt your videos with cosmic precision.
- The power to erase – gracefully delete videos from your cosmic tapestry.

## Cosmic Communications

### 🐦 Tweet Constellations
- Create and release cosmic tweets into the celestial atmosphere.
- Observe the cosmic whispers by exploring the tweets of fellow cosmic entities.

### 🔄 Tweet Alchemy
- Transform the cosmic energies by updating and deleting your cosmic tweets.

## Subspace Connections

### 🌌 Channel Subscription Nebula
- Align your cosmic energies by subscribing to celestial channels.
- Navigate through your cosmic subscriptions and subscribers' constellations.

## Playlist Universes

### 🎵 Playlist Creations and Transformations
- Weave cosmic melodies by creating, updating, and deleting playlists.
- Enhance your cosmic symphony by managing videos within playlists.

### 🌌 Playlist Revelations
- Gaze upon the celestial playlists crafted by fellow cosmic entities.

## Cosmic Likes

### ❤️ Likes in the Cosmos
- Infuse cosmic love by liking and unliking various cosmic entities.
- Reflect upon your cosmic adoration with a list of liked entities.

## Celestial Conversations

### 💬 Comment Universes
- Engage in cosmic dialogues by adding, updating, and deleting comments.
- Your cosmic voice resonates through the vastness of the universe.

## Cosmic Observatory

### 📊 Channel Celestial Statistics
- Peer into the cosmic statistics, revealing views, subscribers, videos, and likes.
- Swiftly access the cosmic archives – your uploaded videos in an instant.

## Astral Health Check

### 🌌 Verification of Celestial Integrity
- Ascertain the well-being of the cosmic backend with a dedicated health check.

## Celestial Technologies

### 🚀 Pillars of Celestial Construction
- Harness the powers of Node.js, Express.js, MongoDB, and the cosmic energies of Cloudinary (Account Required).



--- 
# Getting Started
```
$npm install -g nodemon

# or using yarn:
$yarn global add nodemon
```
- dotenv
```
$npm i dotenv
```
Run Locally
---
- check npm
```
$npm -v
```
- check nodemon
```
$nodemon -v
```
- install all the node_modules
```
$npm install
```
- create a .env file 
```

- create the [cloudinary](https://cloudinary.com/users/register_free) account(free version)
- get the cloudinary credential

```

in the .env file

```
PORT=8000
MONGODB_URI="Your mongodb URI string"
CORS_ORIGIN=*
ACCESS_TOKEN_SECRET="yours secret key"
ACCESS_TOKEN_EXPIRY="yours secret key"
REFRESH_TOKEN_SECRET="yours secret key"
REFRESH_TOKEN_EXPIRY="yours secret key"
CLOUDINARY_CLOUD_NAME="your cloud name"
CLOUDINARY_API_KEY=your-api-key
CLOUDINARY_API_SECRET=your-api-secret
```
- run the server
```
$npm run dev
```
