# ConvoCloud

ConvoCloud is a cloud-based communication platform designed for seamless team collaboration. Built with modern technologies like Next.js, TypeScript, Clerk (for authentication), and Stream (for video conferencing), ConvoCloud ensures efficient and secure communication for teams of all sizes.

### Live Project

Check out the deployed version of ConvoCloud here: [ConvoCloud Live](<https://convo-cloud-woad.vercel.app/>)


## Getting Started

To get started with the ConvoCloud project, follow these steps:

### Development Server

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to view the application.

You can start editing the pages by modifying the files in the `app/` directory. The changes will reflect instantly due to Next.js’s fast refresh feature.

### Environment Variables

Ensure you configure the required environment variables in your `.env.local` file. Below is an example of the variables you might need:

```env
NEXT_PUBLIC_CLERK_FRONTEND_API=<your_clerk_frontend_api>
CLERK_API_KEY=<your_clerk_api_key>
STREAM_API_KEY=<your_stream_api_key>
STREAM_API_SECRET=<your_stream_api_secret>
```

Refer to the respective documentation for setting up Clerk and Stream APIs.

### Features

- **Real-Time Collaboration:** Leverage Stream to enable real-time video conferencing and messaging.
- **Secure Authentication:** Powered by Clerk for seamless user authentication and management.
- **Scalability:** Built on Next.js, offering server-side rendering and static generation for optimized performance.

## Technologies Used

- **Next.js**: A React-based framework for building fast and scalable web applications.
- **TypeScript**: For type-safe code and better developer experience.
- **Clerk**: Provides authentication and user management.
- **Stream**: Enables real-time video conferencing and chat functionalities.

## Deployment

The easiest way to deploy your ConvoCloud app is via [Vercel](https://vercel.com), the creators of Next.js. Follow these steps for deployment:

1. Push your project to a GitHub repository.
2. Connect your GitHub repository to Vercel.
3. Add your environment variables in the Vercel project settings.
4. Deploy the project with a single click.

For more details, refer to [Next.js Deployment Documentation](https://nextjs.org/docs/app/building-your-application/deploying).



## Learn More

To learn more about the technologies used in this project, check out the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - Learn about Next.js features and API.
- [TypeScript Documentation](https://www.typescriptlang.org/docs/) - Learn about TypeScript and its benefits.
- [Clerk Documentation](https://clerk.dev/docs) - Guide to integrating authentication with Clerk.
- [Stream Documentation](https://getstream.io/docs/) - Explore how to use Stream for chat and video features.

## Feedback and Contributions

Contributions are welcome! If you encounter issues or have feature requests, please feel free to create an issue or submit a pull request in the [GitHub repository](https://github.com/abhijeet8080/ConvoCloud).

---

Built with ❤️ by the Abhijeet Kadam.

