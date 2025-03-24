# Tasks

1- Ticket #1: Project Initialization & Environment Setup
Outcome: 
- A working Rails project with proper environment management and gem dependencies
What to do:
- Create a new project/Initialize a new Ruby on Rails project 

Ticket #2: Database Schema & Models for Flight Deals
Tasks:

Outcome: 
- A solid data layer that supports storing flight data and tracking deals.

What to do:

- Create a Flight model to store flight information (origin, destination, dates, prices, etc.).

- Create a Deal model if we want to log which deals have been processed or sent.

- Create a User model if we plan to allow subscriptions or personalized notifications.

- Write migrations to build the schema.

- Set up model validations and basic associations.

Ticket #3: External API Integration for Flight Data
Tasks:

Outcome: 
- A reusable service that fetches and processes flight data from external sources.

What to do:

- Research and choose one or more flight data APIs (e.g., Skyscanner, Kiwi, or another affordable API).

- Build a service class (e.g., FlightDealFetcher) to query the API for flight deals?

- Parse the API response and map the data to your Flight model.

- Ensure error handling and logging for API call failures.
