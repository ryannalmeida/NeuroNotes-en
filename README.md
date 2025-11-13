# NeuroNotes - AI-Powered Note Taking

A modern note-taking application with AI-powered features including automatic summarization, smart tagging, and semantic search.

## Features

- 📝 **Markdown Editor**: Rich text editing with markdown support
- 🤖 **AI Summarization**: Automatically generate concise summaries of your notes
- 🏷️ **Smart Tagging**: AI-powered tag suggestions to organize your notes
- ⭐ **Favorites**: Mark important notes as favorites
- 🔍 **Search**: Quickly find notes by title or content
- 🌓 **Dark Mode**: Beautiful dark and light themes
- 💾 **Cloud Sync**: All your notes are securely stored in the cloud

## Technologies

This project is built with:

- **Vite** - Fast build tool and dev server
- **TypeScript** - Type-safe JavaScript
- **React** - UI library
- **shadcn-ui** - Beautiful UI components
- **Tailwind CSS** - Utility-first CSS framework
- **Supabase** - Backend as a service (database, auth, edge functions)
- **React Router** - Client-side routing
- **Framer Motion** - Animation library

## Getting Started

### Prerequisites

- Node.js (v18 or higher) - [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating)
- npm or yarn package manager
- Supabase account and project

### Installation

1. Clone the repository:
```sh
git clone <YOUR_GIT_URL>
cd brain-bright-notes-main
```

2. Install dependencies:
```sh
npm install
```

3. Set up environment variables:
Create a `.env` file in the root directory:
```env
VITE_SUPABASE_URL=your_supabase_url
VITE_SUPABASE_PUBLISHABLE_KEY=your_supabase_anon_key
```

4. Set up Supabase Edge Functions environment variables:
In your Supabase project dashboard, configure the following secrets for edge functions:
- `AI_API_KEY`: Your AI API key (OpenAI, Anthropic, etc.)
- `AI_API_URL`: (Optional) Custom AI API endpoint URL (defaults to OpenAI)

5. Start the development server:
```sh
npm run dev
```

The application will be available at `http://localhost:8080`

## Building for Production

```sh
npm run build
```

The built files will be in the `dist` directory.

## Deployment

You can deploy this application to any static hosting service:

- **Vercel**: Connect your GitHub repository and deploy
- **Netlify**: Connect your repository and configure build settings
- **Supabase**: Use Supabase hosting for full-stack deployment

### Environment Variables for Production

Make sure to set the following environment variables in your hosting platform:
- `VITE_SUPABASE_URL`
- `VITE_SUPABASE_PUBLISHABLE_KEY`

## Project Structure

```
├── src/
│   ├── components/     # React components
│   ├── pages/          # Page components
│   ├── hooks/          # Custom React hooks
│   ├── integrations/   # External service integrations
│   └── lib/            # Utility functions
├── supabase/
│   ├── functions/      # Edge functions
│   └── migrations/     # Database migrations
└── public/             # Static assets
```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is open source and available under the MIT License.
# NeuroNotes-en
