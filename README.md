# medusaEcommerce
Leading open source e-commerce platform for javascript developers. An API-first composable commerce engine that lets you build custom and flexible

## Docs

- https://www.sitepoint.com/medusa-shopify-alternative/

- https://medusajs.com/blog/beginner-guide-to-node-js-ecommerce-platform-understanding-the-medusa-server/

- https://blog.openreplay.com/create-an-ecommerce-platform-with-medusa-and-docker/


## Medusa Architecture Overview

**Three main components of a Medusa** project
Medusa’s complete architecture consists of three main components: 

- Headless Node.js Ecommerce Server,
- Admin Dashboard
- Storefront. 


![Headless E-commerce](https://github.com/sanogotech/medusaEcommerce/blob/main/HeadlessArchi.png)


The modular and headless architecture makes all three components completely separated and deployable to different environments without any restriction.

To understand more what each component is:

**Medusa Server (Headless)**

This is the core component and is the brain of your online store. It is a Node.js Ecommerce Server. Being a headless server, it is accessed via REST APIs. Both the storefront and admin dashboard are presentation layers to interact with the server.
Everything you configure in the admin dashboard or actions performed by consumers on the storefront are handled underneath by the Medusa server.


**Admin Dashboard**

Only authorized personnel can access the admin dashboard. This is where you manage your online store’s data and settings such as adding products, setting price/currencies, and managing orders.
Medusa provides an intuitive admin built with Gatsby, but you can also create your own from scratch using the REST APIs.


**Storefront**

A storefront is where consumers arrive, search for products and buy them. An example of a storefront is the Amazon website. You can either have one cross-platform storefront (e.g., web application), or multiple storefronts (e.g., web, iOS, and Android native applications).
Medusa provides two starter storefronts, one built using Next.js and one using Gatsby. You can also build your own storefront by interacting with the REST APIs.

## Medusa’s headless architecture

**Medusa's architecture**


![Medusa Headless E-commerce Architecture](
https://github.com/sanogotech/medusaEcommerce/blob/main/medusaEcommerceArchi.jpg)


Headless is the concept of decoupling the frontend from the backend. For the backend, this means that it’s free from the shackles of any presentation layer. 

The backend is only responsible for handling the data and logic of the system.

The backend exposes a set of APIs that allows any frontend or presentation layer to interact with it.

This decoupling gives developers the freedom to choose which language or framework to use for the frontend. Developers can use Jamstack frameworks like Gatsby and Next.js. They can also integrate different types of channels such as mobile apps or marketplaces.

Medusa is composed of three components: the headless server, the storefront, and the admin panel. Although Medusa provides two starter storefronts — one built with Next.js and another with Gatsby, and an intuitively-designed admin panel — developers have the full freedom to build these components with any other frameworks from scratch. All they need to do is interact with the REST APIs.

This allows the developers working on the frontend to focus their efforts on providing a unique and good user experience without the storefront being tightly knit to the backend.

**An open-source Shopify alternative**
