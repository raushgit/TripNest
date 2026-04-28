⚙️ Getting Started
1. Clone the repository
Bash
git clone [https://github.com/your-username/tripnest.git](https://github.com/your-username/tripnest.git)
cd tripnest
2. Install dependencies
Bash
npm install
3. Environment Variables
Create a .env file in the root directory and add the following:

Code snippet
DATABASE_URL="postgresql://user:password@localhost:5432/tripnest"
NEXTAUTH_SECRET="your_generated_secret"
NEXTAUTH_URL="http://localhost:3000"
CLOUDINARY_URL="your_cloudinary_url"
4. Database Setup
Bash
npx prisma generate
npx prisma db push
npx prisma db seed
5. Run the Project
Bash
npm run dev
📊 Business & Technical Edge
Unlike standard planners, TripNest solves "App Fatigue" by combining the features of Wanderlog, Splitwise, and Google Photos into a single, high-performance dashboard. The system utilizes a Debt Simplification Algorithm to minimize total transactions and WebSockets for zero-latency group collaboration.

👤 Author
Raushan Kumar Computer Science Student | Backend Developer

GitHub | LinkedIn

