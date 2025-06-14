# Next.js Application

This is a modern Next.js application built with TypeScript and Tailwind CSS.

## Features

- Modern UI components using shadcn/ui
- TypeScript support
- Tailwind CSS for styling
- Interactive motorcycle visualization
- Admin dashboard
- User requirements management
- App package download functionality

## Download App Package

You can download the complete application package through the admin interface:

1. Navigate to `/admin/download` in your browser
2. Click the "Download Package" button
3. Confirm the download in the dialog
4. The app will be downloaded as a ZIP file containing:
   - Source code (src/)
   - Public assets (public/)
   - Configuration files
   - Documentation

## Installation

After downloading the package:

1. Extract the ZIP file
2. Navigate to the extracted directory
3. Install dependencies:
   ```bash
   npm install
   ```
4. Start the development server:
   ```bash
   npm run dev
   ```
5. Open [http://localhost:3000](http://localhost:3000) in your browser

## Development

- Built with Next.js 14
- Uses TypeScript for type safety
- Styled with Tailwind CSS
- Components from shadcn/ui library
- File-based routing system

## Project Structure

```
├── src/
│   ├── app/              # Next.js app directory
│   ├── components/       # React components
│   ├── hooks/           # Custom React hooks
│   ├── lib/             # Utility functions
│   └── types/           # TypeScript type definitions
├── public/              # Static files
└── package.json         # Project dependencies
```

## License

This project is licensed under the MIT License.
