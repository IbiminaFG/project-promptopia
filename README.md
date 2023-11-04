# Promptopia

Promptopia is an open-source web application that leverages AI to generate, share, and discover creative prompts. Whether you're a writer, artist, or anyone seeking inspiration, Promptopia provides a platform to spark your imagination. This README provides an overview of the project, its features, and how to get started.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)

## Features

- **User Profiles:** Create and manage your user profile.
- **My Profile:** Personalized profile page to view, edit, and delete your prompts.
- **Community Feed:** View prompts shared by other users.
- **Update Prompts:** Edit and update prompts you've created.
- **Responsive Design:** A mobile-friendly interface for a seamless user experience.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/IbiminaFG/project-promptopia.git
   ```

1. Install the required dependencies:

   ```bash
   cd promptopia
   yarn install
   ```

1. Set up environment variables:

   Create a .env.local file in the root directory with the following variables:

   ```bash
   MONGODB_URI=your_mongodb_connection_uri
   GOOGLE_ID=your_google_client_id
   GOOGLE_CLIENT_SECRET=your_google_client_secret
   NEXTAUTH_URL=the_url_to_run_this_app_from
   NEXtAUTH_URL_INTERNAL=the_url_to_run_this_app_from
   NEXTAUTH_SECRET=from_next
   ```

1. Start the development server:

   ```bash
   yarn run dev
   ```

## Usage

1. Register or sign in using your Google account to start using Promptopia.
2. Explore the community feed to discover creative prompts.
3. Create, edit, and share your own prompts.
4. Visit "My Profile" to manage your personalized profile and prompts.
