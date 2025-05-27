# Modern React Clothing Store 

StyleHub is a **fully responsive eCommerce clothing store** built with **React, Tailwind CSS, and modern web technologies**. It features a sleek UI, product filtering, cart functionality, and seamless checkout.  

## Key Features

✅ **Fully Responsive** – Mobile, tablet & desktop optimized  
✅ **Product Showcase** – Featured, trending, and new arrivals  
✅ **Advanced Filtering** – Sort by category, price, size, and color  
✅ **Shopping Cart** – Add/remove items, quantity adjustment  
✅ **User Authentication** – Login/Register with Firebase  
✅ **Checkout Process** – Stripe integration for payments  
✅ **Wishlist & Favorites** – Save items for later  
✅ **Dark/Light Mode** – Toggleable theme  
✅ **SEO Optimized** – Next.js for better performance  



## Tech Stack  

- **Frontend**: React.js, Next.js  
- **Styling**: Tailwind CSS  
- **State Management**: Redux Toolkit  
- **Authentication**: Firebase  
- **Payments**: Stripe API  
- **Backend**: Node.js + Express (optional)  
- **Database**: Firebase Firestore / MongoDB  


2. **Install dependencies**  

   npm install
   # or
   yarn install


3. **Set up environment variables**  
   Create a `.env` file and add:  
   NEXT_PUBLIC_FIREBASE_API_KEY=your_firebase_key
   NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY=your_stripe_key
   
4. **Run the app**  

   npm run dev
   # or
   yarn dev


5. **Open in browser**  
   Visit `http://localhost:3000`  



## Project Structure**  

stylehub-react/
├── components/       # Reusable UI components
├── pages/            # Next.js pages (home, product, cart, etc.)
├── redux/            # Redux store & slices
├── public/           # Static assets (images, logos)
├── styles/           # Global Tailwind/CSS
├── utils/            # Helper functions
├── firebase.js       # Firebase config
├── next.config.js    # Next.js settings
└── package.json      # Dependencies


## Customization

- **Change branding**: Modify colors in `tailwind.config.js`  
- **Add products**: Update `redux/productsSlice.js`  
- **Modify Stripe keys**: Update `.env` file  
- **Deploy**: Vercel, Netlify, or Firebase Hosting  
