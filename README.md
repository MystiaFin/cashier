# Dynoboo Server-side

## Development

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn
- PostgreSQL (or your preferred database supported by Prisma)

### Setup

1. **Clone the repository**

   ```bash
   git clone https://github.com/yourusername/kasir.git
   cd kasirdevelopement:
   ```

2. **Install dependencies**

   ```bash
   npm install
   ```

3. **Setup the environent variables**

4. **Database Setup**

   ```bash
   # Generate Prisma client
   npx prisma generate

   # Run migrations
   npx prisma migrate dev
   ```

5. **Run**
   ```bash
   npm run dev
   ```
