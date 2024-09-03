This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

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

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

# Top 20 Hacks Bootstrap

A web application built with *Next.js, **Prisma, and **shadcn/ui* that allows users to add and interact with a list of creative hacks. Users can submit new hacks, like or dislike existing ones, and view hacks across three dynamic categories: *Hot Hacks, **New Hacks, and **Top Hacks*.

## Features

- *New Hack Submission*: Users can add their hacks using the "New Hack" feature.
- *Like and Dislike*: Users can like or dislike other hacks.
- *Dynamic Categories*:
  - *Hot Hacks*: Displays the most liked hacks within the last 24 hours.
  - *New Hacks*: Shows recently added hacks.
  - *Top Hacks*: Lists the hacks with the most likes overall.

## Tech Stack

- *Next.js*: A React framework for server-side rendering and static site generation.
- *Prisma*: A modern ORM for managing the application's database.
- *shadcn/ui*: A component library for building a responsive and beautiful user interface.

## Installation

1. Clone the repository:

    bash
    git clone https://github.com/yourusername/top-20-hacks-bootstrap.git
    cd top-20-hacks-bootstrap
    

2. Install the dependencies:

    bash
    npm install
    

3. Set up the environment variables:

   Create a .env file in the root directory and add your database connection string and other required variables.

    bash
    DATABASE_URL="your-database-url"
    

4. Run the Prisma migrations to set up the database schema:

    bash
    npx prisma migrate dev
    

5. Start the development server:

    bash
    npm run dev
    

    The app will be available at [http://localhost:3000](http://localhost:3000).

## Usage

- *Add a New Hack*: Use the "New Hack" button to add a new hack.
- *Like or Dislike Hacks*: Interact with hacks by liking or disliking them.
- *Explore Hacks*: Navigate between the "Hot Hacks," "New Hacks," and "Top Hacks" sections to discover different types of hacks.

## Contributing

Contributions are welcome! Please fork the repository, make changes, and submit a pull request.

## License

This project is licensed under the MIT License.
