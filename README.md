# Discord Web: React, Next.js 13, Tailwind, Socket.io, MySQL, Prisma

Key Features:


- Member management (Kick, Role change Guest / Moderator)
- Unique invite link generation & full working invite system
- Infinite loading for messages in batches of 10 (tanstack/query)
- Delete & Edit messages in real time for all users
- Light / Dark mode
- Websocket fallback: Polling with alerts
- ORM using Prisma
- MySQL database using Planetscale
- Authentication with Clerk
- Beautiful UI using TailwindCSS and ShadcnUI
- Full responsivity and mobile UI
- Server creation and customization
- Create Text, Audio and Video call Channels
- 1:1 conversation between members
- Real-time messaging using Socket.io
- Send attachments as messages using UploadThing
- 1:1 video calls between members
### Setup .env file


```js

DATABASE_URL=
UPLOADTHING_SECRET=
UPLOADTHING_APP_ID=
LIVEKIT_API_KEY=
LIVEKIT_API_SECRET=
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=
NEXT_PUBLIC_LIVEKIT_URL=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=
NEXT_PUBLIC_CLERK_SIGN_UP_URL=
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=


```