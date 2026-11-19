# Tech Stack & Hosting Strategy

## Defined Tech Stack

- `React + TypeScript`: Used to build the front-end dashboard where satellite operators can view orbit information, collision alerts, and suggested path adjustments.

- `Python + FastAPI`: Used for the backend to process satellite and debris data, check for potential orbit intersections, and generate suggested path adjustments.

- `Supabase`: Used as the cloud database to store satellite information, debris records, orbit data, and collision alerts.

## Hosting & Deployment Strategy

The LEON application will use Vercel to host the front-end website and Render to host the Python backend. Supabase will provide the hosted database for storing and accessing satellite and debris information. This setup will allow users to access LEON through a web browser while keeping the website, backend, and database connected.
