<h1 align=center>shop-ify Theme | NextJs + Shopify + Tailwind CSS + TypeScript Theme</h1>

<p align=center>A Next.js template powered by Tailwind CSS and TypeScript, specifically designed for Shopify. Utilizes the Shopify Storefront API through GraphQL and providing everything you need to jumpstart your Next project and save valuable time.</p>

<p align=center> This project has been cloned from <a target="_blank" href="https://github.com/zeon-studio/commerceplate">zeon-studio/commerceplate</a>, please give it a ⭐ to show your support. </p>

## 📌 Key Features

- 🌐 Dynamic Products from Shopify Storefront API
- 💸 Checkout and Payments with Shopify
- 🌞 Automatic Light/Dark Mode
- 🚀 Fetching and Caching Paradigms
- 🔗 Server Actions for Mutations
- 🔐 User Authentication
- 🧩 Similar Products Suggestions
- 🔍 Search, Sort, Different Views Functionality
- 🏷️ Tags & Categories & Vendors & Price Range & Product Variants Functionality
- 🖼️ Single Product Image Zoom, Hover Effect, Slider
- 🛒 Cart & Easy editing options for cart items
- 📝 Product Description on Multiple Tabs
- 🔗 Netlify Setting Pre-configured
- 📞 Support Contact Form
- 📱 Fully Responsive
- 🔄 Dynamic Home Banner Slider
- 📝 Write and Update Content in Markdown / MDX
- ⌛ Infinite Product Load on Scrolling

### 📄 10+ Pre-designed Pages

- 🏠 Homepage
- 👤 About
- 📞 Contact
- 🛍️ Products
- 📦 Product Single
- 💡 Terms of services
- 📄 Privacy Policy
- 🔐 Login
- 🔑 Register
- 🚫 Custom 404

## 🚀 Getting Started

### 📦 Dependencies

- shopify
- next 13.5.4+
- node v20.10+
- npm v10.2+
- tailwind v3.3+

<!-- get Shopify storefront API access token-->

## 🛒 Retrieve Shopify Token & Add Demo Products

- To get the tokens needed, create a Shopify partner account.

- Now go to 'stores' and select 'Add store.' Create a development store using the option 'Create development store'.

- Complete the process by creating your development store. This involves following the steps shown in the image.

- Click on import products.

- Locate the 'products_export_1' CSV file in the public folder of the repository and upload it for demo products.

- On the admin dashboard, click on ‘Settings’ at the bottom of the left sidebar.

- On the Settings page, click on ‘Apps and sales channels’ on the left sidebar.

- In the Apps and sales channels page that opens, click on ‘Develop apps’ on the top right.

- Now, on the App development page that opens, click on ‘Create an app’.

- A ‘Create an app’ popup opens. Fill in any name in the ‘App Name’ text box. In the App Developer text box, your name and email id is automatically fetched. Else type in the same email id you used while signing up for the Shopify store.

- Next, click on ‘Configure’ in the Storefront API integration section.

- In the Storefront API access scopes, select and check all the boxes and click on ‘Save’ and then ‘Install app’.

- Navigate to the 'API credentials' tab and locate three essential pieces of information. Subsequently, update your ``.env`` file by replacing the placeholder quotes("") in the ``.env.example`` file with your Shopify credentials.

- When adding your product, use the same alt title for images with the same color. This helps the first image appear as the color variant in the selector.

- We have the option to create additional collections for products.

### 👉 Install Dependencies

```bash
npm install
```
or using Yarn:

```bash
yarn
```

### 👉 Development Command

```bash
npm run dev
```
or using Yarn:

```bash
yarn dev
```

### 👉 Build Command

```bash
npm run build
```
or using Yarn:

```bash
yarn dev
```

