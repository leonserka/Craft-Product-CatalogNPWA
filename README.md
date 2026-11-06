# Craft Product Catalog

Seminar project for NPWA 2026: a web application for browsing one selected category of craft products, such as beer, wine, chocolate, or pizza.

## Project Status

This folder currently contains the assignment specification (`NPWA_2026_projekt.pdf`). Application development has not started, and the product category has not yet been selected. The features below describe the required scope, not completed functionality.

## Required Technology Stack

- **Frontend:** React
- **Backend:** Express.js
- **Database:** MongoDB
- **Authentication:** JSON Web Tokens (JWT)

## Core Requirements

### Products and Manufacturers

- Create product and manufacturer models, with every product linked to a manufacturer.
- Store product characteristics appropriate to the selected category, such as price, alcohol/cocoa/milk percentage, color, and type.
- Store manufacturer information such as founding year, country, a short description, and a logo URL.
- Show a product list with basic information on the home page, grouped or sorted alphabetically by manufacturer.
- Provide product details, a manufacturer list, and manufacturer details.
- Provide forms for adding, editing, and deleting products and manufacturers.
- Prevent deletion of a manufacturer while products are still linked to it.

### Authentication and Authorization

- Implement registration, login, and logout in the frontend, with corresponding backend endpoints.
- Require a valid JWT for server-side routes that return product data.
- Allow regular users to browse existing products and manufacturers.
- Restrict product and manufacturer creation, editing, and deletion to administrators. Enforce permissions on the server as well as in the interface.
- Respect user roles when authorizing user management operations.
- Show login or logout controls according to the current authentication state.
- Redirect users to login after registration, logout, or rejection of an invalid token.
- Redirect users to the home page after successful login.

## Additional Requirements

- Add and remove products from a shopping cart.
- Add and remove products from a favorites list.
- Clear the shopping cart when the user selects checkout.

## Running the Project

No application source code, dependency manifests, or startup commands are available yet. Installation instructions, environment configuration, and development commands should be added when the application is implemented.

## Current Files

| File                      | Description                                   |
| ------------------------- | --------------------------------------------- |
| `NPWA_2026_projekt.pdf` | Original assignment specification in Croatian |
| `README.md`             | English project overview and requirements     |

## Assessment

The seminar includes a practical assessment on a computer and an oral presentation. Passing the practical assessment is a prerequisite for the oral presentation. An excellent overall grade requires completion of both the core and additional requirements.

## Source

This overview is based on the assignment in [NPWA_2026_projekt.pdf](NPWA_2026_projekt.pdf). Refer to that document for the original requirements.
