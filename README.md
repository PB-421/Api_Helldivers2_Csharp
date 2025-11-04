# Helldivers 2 - API in C# .NET 8.0

**Helldivers 2 API** is a personal project created using C# and .NET 8.0. This API provides information about the Freedom's enemies and the Stratagems used to defend it in *Helldivers 2*. The API is simple, with GET endpoints that allow you to retrieve information about various aspects of the game, such as enemies and Stratagems.

## API Endpoints

The API exposes several GET endpoints to fetch data about the game's enemies and Stratagems:

### 1. **SuperEarth**
   - **Description**: Information about SuperEarth stratagems, the resources that the Helldivers use.
   - **Endpoint**:  
     [GET /api/superearth](https://helldivers2-api.onrender.com/api/superearth)
   
### 2. **Terminids**
   - **Description**: Information about the *Terminids*, one of the enemy factions players must face in the game.
   - **Endpoint**:  
     [GET /api/terminids](https://helldivers2-api.onrender.com/api/terminids)

### 3. **Automatons**
   - **Description**: Information about the *Automatons*, one of the enemy factions in *Helldivers 2*.
   - **Endpoint**:  
     [GET /api/automatons](https://helldivers2-api.onrender.com/api/automatons)

### 4. **Illuminates**
   - **Description**: Information about the *Illuminate*, one of the enemy factions in *Helldivers 2*.
   - **Endpoint**:  
     [GET /api/illuminate](https://helldivers2-api.onrender.com/api/illuminate)

## Features

- **Simple Endpoints**: The API is designed to provide data via simple GET requests.
- **Built with C# and .NET 8.0**: Utilizes the latest technologies in C# and .NET for optimal performance and easy integration.
- **Personal Project**: This project was created as an additional resource for the *Helldivers 2* web interface, part of a fan-made initiative.

## Usage

  **Querying the API**: You can access any of the provided endpoints to retrieve information about the enemies or Stratagems.

## Local installation

  1. **Clone repository**
     ```bash
      git clone https://github.com/your-username/helldivers2-api.git

  2. **Install dependencies**
     ```bash
      dotnet restore

  3. **Run the project**
     ```bash
      dotnet run

## Licence

  This project is a personal, fan-made initiative and is not intended for commercial use. It is a tribute to the Helldivers 2 game and its community. You are free to use it for    educational and exploration purposes, but not for commercial applications.
