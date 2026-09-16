# StoreMERN

A simple product store built with MERN stack!!

[Click here to view the website](https://store-mern-u8k1.onrender.com)

> [!NOTE]
> It might take some time to wake up as it is hosted on a free plan.

## Run locally

If you want to run the website locally, you will need:

- Node.js and npm
- A MongoDB connection string

Create `backend/.env` with:

```env
MONGO_URI=your_mongodb_connection_string
PORT=5001
```

From the repository root, install dependencies:

```bash
npm install
npm install --prefix frontend
```

Start the backend in one terminal instance:

```bash
npm run dev
```

Start the frontend in another terminal instance:

```bash
npm run dev --prefix frontend
```

Open <http://localhost:5173> in a browser.

## API endpoints

### Products

- `GET /api/products` — fetch all products
- `POST /api/products` — create a new product
- `PUT /api/products/:id` — update a product by id
- `DELETE /api/products/:id` — delete a product by id

## Project structure

```bash
store-mern/
├── backend/
│   ├── config/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   └── server.js
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── store/
│   │   ├── App.jsx
│   │   └── main.jsx
│   ├── public/
│   ├── index.html
│   ├── package.json
│   ├── vite.config.js
│   └── README.md
├── package.json
├── README.md
└── .gitignore
```
