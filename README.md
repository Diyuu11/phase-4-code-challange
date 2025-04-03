# Superheroes API

This is a Flask-based API that allows you to manage superheroes, their superpowers, and the relationships between them. The API allows you to perform various operations like retrieving heroes, powers, updating powers, and associating heroes with powers.

## Features

- List all superheroes.
- Retrieve a specific superhero by ID.
- List all superpowers.
- Retrieve a specific superpower by ID.
- Update a superpower's description.
- Associate a superhero with a power (create a hero-power relationship).

## Tech Stack

- **Flask**: The micro web framework for building the API.
- **SQLAlchemy**: ORM for database interactions.
- **Flask-Migrate**: Handles database migrations.
- **SQLite**: Lightweight database for storing hero and power data.

## Getting Started

Follow the steps below to set up the project locally.

### Prerequisites

You will need Python 3.6+ installed on your machine.

### 1. Clone the Repository

```bash
git clone <your-repository-url>
cd superheroes-api
