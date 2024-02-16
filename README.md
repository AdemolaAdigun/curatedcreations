# Curated Creations

## Introduction

Curated Creations is an innovative platform designed to empower artists and creators, enabling them to bring their artwork to life on a variety of merchandise such as Hoodies, T-shirts, Hats, Jackets, and more. Built on top of Next.js, and integrating seamlessly with Hasura and PostgreSQL, Curated Creations offers a comprehensive suite of tools for artists to manage their digital storefronts. From uploading artwork to setting up products and managing orders, our platform simplifies the e-commerce process, allowing creators to focus on what they do best: creating.

Our mission is to democratize art commerce by providing a direct channel between artists and their audience, removing traditional barriers to entry in the merchandise market. Curated Creations is not just a platform; it's a community where artists can showcase their work on a global stage, gain recognition, and earn from their creativity without worrying about the logistics of product manufacturing, order fulfillment, or customer service. We handle the heavy lifting so that our artists can concentrate on their passion.

Whether you're an artist looking to expand your reach or a customer seeking unique, artist-designed products, Curated Creations offers something for everyone. Welcome to the future of art commerce, where creativity knows no bounds.

## Features

Curated Creations is designed with both artists and customers in mind, offering a range of features that facilitate a seamless, engaging, and profitable online art marketplace experience.

- **Artist Dashboard**: A comprehensive dashboard allows artists to easily upload their artwork, choose the types of merchandise for their art to be featured on, and manage their personal bios. This centralized hub makes managing an online art business straightforward and efficient.

- **Customizable Storefronts**: Artists receive a customizable storefront where their artwork is dynamically rendered on selected products. This feature provides potential buyers with a realistic preview of how the art appears on various merchandise.

- **Product Variety**: Our platform supports a wide range of products, from apparel like T-shirts and hoodies to accessories like hats and jackets. Artists can select multiple product types to feature their artwork on, increasing their potential revenue streams.

- **Price Setting**: Artists have the freedom to set their own prices for their artwork on different products. The total price displayed to customers includes the artist's set price plus the base cost of the product, shipping, and handling.

- **Order Fulfillment**: Curated Creations takes responsibility for all order processing, fulfillment, and customer service, allowing artists to focus on their craft without worrying about the logistics of running an online store.

- **Real-time Earnings Tracking**: Artists can track their earnings in real time through the dashboard and request payouts once they reach a predefined threshold, ensuring a transparent and rewarding experience.

- **Customer Engagement**: Customers have the ability to browse through various artist storefronts, making it easier to find and purchase unique, artist-designed merchandise. The platform also includes features designed to enhance customer engagement and satisfaction, including product reviews and artist followings.

These features are designed to make Curated Creations the go-to platform for artists looking to monetize their art and for customers seeking unique, high-quality, artist-designed products.

## Getting Started

To begin using Curated Creations for your artistic and entrepreneurial journey, there are a few steps you need to follow to set up the platform. This guide will walk you through everything from checking prerequisites to getting the development server up and running on your local machine. Whether you're an artist looking to showcase your work or a developer interested in contributing to the project, following these steps will ensure you have everything you need to get started.

### Prerequisites

Before diving into the setup process, ensure you have the following prerequisites installed and properly configured on your system:

- **Node.js**: A JavaScript runtime built on Chrome's V8 JavaScript engine, necessary for running Next.js applications. Download and install the latest LTS version from [Node.js official website](https://nodejs.org/).

- **npm** or **Yarn**: Package managers for managing project dependencies. npm is installed automatically with Node.js. Yarn, an alternative to npm, can be installed separately from [Yarn's official site](https://yarnpkg.com/).

- **Git**: A distributed version control system for cloning the Curated Creations repository and managing your own version control. Download and install Git from [Git's official site](https://git-scm.com/).

- **PostgreSQL**: The primary database for storing all data related to Curated Creations. Install PostgreSQL by following the instructions on the [PostgreSQL official website](https://www.postgresql.org/download/).

- **Hasura CLI** (Optional): A command-line tool that assists in managing Hasura GraphQL engine instances, including migrations and metadata. While not strictly necessary for running the platform, it's useful for advanced database operations. Installation instructions can be found in [Hasura's documentation](https://hasura.io/docs/latest/graphql/core/hasura-cli/install-hasura-cli.html).

Making sure these tools are installed is crucial for a smooth setup and development experience with Curated Creations.

### Installation

#### Clone the Repository

To get started with Curated Creations, the first step is to clone the project repository from GitHub to your local machine. This will create a copy of the project's codebase on your computer, allowing you to begin setup and development. Open a terminal window and execute the following command:

```bash
git clone https://github.com/AdemolaAdigun/curatedcreations.git
cd curatedcreations
```

After cloning the Curated Creations repository, the next step is to install the project's dependencies. These dependencies include all the necessary libraries and packages that the project relies on to run correctly. To install these dependencies, navigate to the root directory of your cloned project in the terminal, and run one of the following commands depending on your package manager of choice:

For npm users:

```bash
npm install
npm run dev
``
