# Netflix-clone

## Getting Started

### Run the Development Server

To start your development environment, run:

```bash
npm run dev
# or
yarn dev
```

Visit http://localhost:3000 in your browser to view the application.

## Live Editing
To modify the homepage, edit the file at pages/index.js. Changes you make will be reflected immediately in your browser.

## API Routes
The API endpoint at http://localhost:3000/api/hello can be modified in the pages/api/hello.js file. This setup maps the pages/api directory to handle requests at /api/*, treating them as API routes rather than React pages.

## Setup Local Environment
Required API Keys
To fully setup your local environment, you'll need to obtain several API keys:

**Magic Server and Publishable Key**

**Hasura Admin URL and JWT Secret**

**YouTube API Key**

Create a .env.local file in your project root with the following content (replace placeholders with actual values from the respective service documentation):

```bash
NEXT_PUBLIC_HASURA_ADMIN_URL=<REPLACE THIS>
JWT_SECRET=<REPLACE THIS>
NEXT_PUBLIC_HASURA_ADMIN_SECRET=<REPLACE THIS>
MAGIC_SERVER_KEY=<REPLACE THIS>
NEXT_PUBLIC_MAGIC_PUBLISHABLE_API_KEY=<REPLACE THIS>
YOUTUBE_API_KEY=<REPLACE THIS>
```

Refer to the linked documentation of each service to retrieve the necessary values and update your .env.local file accordingly.
