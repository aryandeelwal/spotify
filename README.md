## Spotify Clone 

[spotify-aryandeelwal.vercel.app](spotify-aryandeelwal.vercel.app)


### Tech Stack
```
Next.js
Tailwind
Supabase
PostgreSQL
Stripe
```

Key Features:

- Song and image upload using Supabase storage
- Stripe integration. For subscription use, [Stripe Testing Cards](https://stripe.com/docs/testing)
- Tailwind design for sleek UI
- Tailwind animations and transition effects
- Full responsiveness for all devices
- Credential authentication with Supabase
- Github and Google authentication integration
- Client form validation and handling using react-hook-form
- Server error handling with react-toast
- Play song audio
- Favorites system
- Playlists / Liked songs system
- Advanced Player component
- Stripe recurring payment integration
- How to write POST, GET, and DELETE routes in route handlers (app/api)
- How to fetch data in server React components by directly accessing the database (WITHOUT API! like Magic! all because of Supabase)
- Handling relations between Server and Child components in a real-time environment
- Cancelling Stripe subscriptions

### Cloning the repository

```shell
git clone https://github.com/aryandeelwal/spotify.git
```
### Install packages

```shell
npm i
```
### Setup .env file

```js
NEXT_PUBLIC_SUPABASE_URL=
NEXT_PUBLIC_SUPABASE_ANON_KEY=
SUPABASE_SERVICE_ROLE_KEY=

NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY=
STRIPE_SECRET_KEY=
STRIPE_WEBHOOK_SECRET=
```

### Start the app

```shell
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.


