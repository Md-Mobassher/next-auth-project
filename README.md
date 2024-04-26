# Next.js Authentication Project

This project is a Next.js application that implements custom registration and login functionality, along with social login integration for Google and GitHub.

## Features

- Custom registration and login system
- Social login integration for Google and GitHub
- Secure authentication process
- Client-side interface for user interaction

## Deployment

- Client-side: [Next.js Authentication Client](https://nextjs-authentication-client-vakuzidwr.vercel.app/)
- Server-side: [Next.js Custom Auth Server](https://nextjs-custom-auth-server-fyt5ijo69.vercel.app/)

## Technologies Used

- Next.js
- React.js
- Node.js
- Express.js
- Passport.js
- Google OAuth
- GitHub OAuth

## Getting Started

To run the project locally, follow these steps:

1. Clone this repository:

```
git clone <repository-url>
```

2. Navigate to the project directory:

```
cd next-authentication-project
```

3. Install dependencies:

```
npm install
```

4. Start the development server:

```
npm run dev
```

5. Open your browser and visit [http://localhost:3000](http://localhost:3000/) to view the application.

## Configuration

Before running the application, ensure that you have configured the following environment variables:

- `GOOGLE_CLIENT_ID`: Client ID obtained from Google Developer Console for Google OAuth integration.
- `GOOGLE_CLIENT_SECRET`: Client secret obtained from Google Developer Console for Google OAuth integration.
- `GITHUB_CLIENT_ID`: Client ID obtained from GitHub Developer Settings for GitHub OAuth integration.
- `GITHUB_CLIENT_SECRET`: Client secret obtained from GitHub Developer Settings for GitHub OAuth integration.

Ensure that these environment variables are set in both the client-side and server-side environments.

## Contributing

Contributions are welcome! Feel free to open issues or pull requests for any improvements or additional features you'd like to see in the project.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
