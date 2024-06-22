# SQL_Project_Music_Store_Analysis
SQL project to analyze online music store data

## Database and Tools
* mysql

Schema- Music Store Database  
![MusicDatabaseSchema](https://user-images.githubusercontent.com/112153548/213707717-bfc9f479-52d9-407b-99e1-e94db7ae10a3.png)

# Music Store Database

## Introduction
The Music Store Database is designed to manage and analyze sales data for a music store. This database includes tables for artists, albums, tracks, genres, media types, playlists, employees, customers, invoices, and invoice lines. The schema facilitates efficient querying for sales analysis, inventory management, and customer relationship management.

## Schema Overview
The database schema consists of the following tables and relationships:

- **Artist**: Contains information about artists.
- **Album**: Contains information about albums, each linked to an artist.
- **Track**: Contains information about tracks, each linked to an album, media type, and genre.
- **MediaType**: Contains different media types for tracks.
- **Genre**: Contains different genres for tracks.
- **Playlist**: Contains playlists of tracks.
- **PlaylistTrack**: A join table between playlists and tracks.
- **Employee**: Contains information about employees.
- **Customer**: Contains information about customers.
- **Invoice**: Contains information about invoices, each linked to a customer.
- **InvoiceLine**: Contains details of each invoice, linked to tracks.

## Setup Instructions
1. **Clone the Repository**
   - Clone the repository from GitHub to your local machine.
   
2. **Database Configuration**
   - Ensure you have a database management system like SQLite installed.
   - Use the provided SQL scripts to create the database schema and insert sample data.

## Example Queries
- **Total Sales by Genre**: Analyze total sales grouped by genre.
- **Top 10 Best-Selling Tracks**: Identify the top 10 tracks with the highest sales.
- **Total Sales by Artist**: Calculate total sales grouped by artist.
- **Monthly Sales Report**: Generate a report of sales totals by month.
- **Customer Purchase History**: Track purchase history for each customer.

## Usage
This database schema is designed for efficient data management and retrieval. It supports various queries to analyze sales performance, customer behavior, and inventory management.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.

## Contributions
Contributions are welcome! Please fork the repository and create a pull request with your changes.

## Contact
For any questions or inquiries, please contact Abrar Ahmed  at abbuabrar41524@gmail.com.


