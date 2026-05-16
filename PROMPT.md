# Pure Nature – E-Commerce Website Project Specification

## 1. Project Overview
Create a modern, elegant, and fully responsive e-commerce website for **"Pure Nature"** – a brand that sells organic, handmade products including skincare, herbal oils, natural soaps, organic foods, and herbal teas.

* **Visual Identity:** Warm, natural, premium feel with earth tones.
* **Responsiveness:** 100% mobile responsive, working perfectly across all devices (phones, tablets, desktops).

---

## 2. Branding & Visual Identity

### 🎨 Color Palette
* **Primary Brand Color:** Sage Green (`#6B7C5B`)
* **Secondary Background:** Soft Cream (`#F5F3F0`)
* **Accent Color:** Golden Yellow (for buttons and highlights)
* **Text Color:** Dark gray for readability, white on dark backgrounds

### 🔤 Typography (Google Fonts)
* **Headings:** *Playfair Display* (serif, elegant)
* **Body Text:** *Inter* (sans-serif, clean)
* **Brand Name Special Font:** *Pacifico* (for visual identity if needed)

---

## 3. Page Sections (In Order)

### 📌 1. Navigation Bar (Sticky)
* **Left:** Logo image file (`logo.png`) instead of text.
* **Center/Right:** Navigation links: *Home*, *About*, *Products*, *Contact* (smooth scroll to sections).
* **Right:** WhatsApp button (green/sage, with WhatsApp icon).
* **Hover Effects:** Underline animation on links, subtle scale on button.

### 🌅 2. Hero Section
* **Background:** Full-screen background image (`hero.jpg`) with a dark overlay for text readability.
* **Headline:** "Pure Nature" with "Organic Living" highlighted in yellow.
* **Subheadline:** Short description about organic handmade products.
* **CTA Button:** Large "Shop Organic Products" button (yellow, with hover scale effect).

### 📖 3. About Our Story Section
* **Layout:** Two columns (left text, right image).
* **Left Column:** Heading "Our Story of Natural Wellness", two paragraphs of brand story, and a "100% Natural Promise" icon + text.
* **Right Column:** Image file `Our Story of Natural Wellness.jpg` (rounded corners, hover zoom effect).

### ✨ 4. Why Choose Pure Nature Section
* **Layout:** 4 cards in a row on desktop, stacked on mobile.
* **Card Content:** An icon (leaf, heart, shield, clock), heading, and short description.
* **Hover Effect:** Lift up with shadow.

### 📦 5. Product Categories Section
* **Categories:** 5 category cards: *Organic Skincare*, *Herbal Oils*, *Natural Soaps*, *Organic Foods*, *Herbal Teas*.
* **Images Used:**
  * `Organic Skincare.jpg`
  * `Herbal Oils.jpg`
  * `Natural Soaps.jpg`
  * `Organic Foods.jpg`
  * `Herbal Teas.jpg`
* **Interactivity:** Clicking any category filters the product grid below to show only that category.

### 🛒 6. Premium Collection (Products Grid)
* **Top Filters:** All Products, Skincare, Herbal Oils, Natural Soaps, Organic Foods, Herbal Teas.
* **Layout:** 3 columns on desktop, 2 on tablet, 1 on mobile.
* **Card Content:**
  * Square product image (1:1 aspect ratio)
  * Star rating (filled yellow stars)
  * Number of reviews
  * Product name (bold, serif font)
  * Short description (2 lines max)
  * Price in PKR
  * Yellow "Buy Now" button
* **Hover Effect:** Card lifts up, image scales slightly.
* **Interactivity:** Clicking anywhere on the card OR the "Buy Now" button opens the *Product Detail Modal*.

### 🔥 7. Best Sellers Section
* **Layout:** 3 premium product cards featuring *Rose Face Cream*, *Raw Honey*, and *Lavender Oil*.
* **Card Content:**
  * "Best Seller" badge (yellow rounded)
  * 5-star rating
  * Product name, description, price
  * "View Details" button
* **Images Used:** * `Rose Face Cream best seller.jpg`
  * `Raw Honey best seller.jpg`
  * `Lavender Oil Best seller.jpg`

### 🛡️ 8. Our Promise Section
* **Layout:** Two columns (left text with icons, right image).
* **Left Side:** Two promise items with shield and heart icons.
* **Right Side:** Image file `Our Promise to You.jpg`.

### 👣 9. Footer
* **Content:** Logo, brand description, WhatsApp contact button, quick links (Home, About, Products), copyright text, and social media icons (Facebook, Instagram, WhatsApp).

---

## 4. Product Data (All Products)
Every product requires a detailed description (2-3 sentences), a key ingredients list, and the following exact details:

| Product Name | Price (PKR) | Rating | Reviews | Category | Image File |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Rose Face Cream** | 2,500 | 5 | 24 | skincare | `Rose Face Cream.jpg` |
| **Aloe Vera Gel** | 1,800 | 4 | 18 | skincare | `Aloe Vera Gel.jpg` |
| **Neem Toner** | 1,500 | 4 | 22 | skincare | `Neem Toner.jpg` |
| **Coconut Moisturizer** | 2,200 | 5 | 27 | skincare | `Coconut Moisturizer.jpg` |
| **Lavender Oil** | 2,800 | 5 | 35 | oils | `Lavender Oil Best seller.jpg` |
| **Tea Tree Oil** | 3,500 | 4 | 19 | oils | `Eucalyptus Oil.jpg` |
| **Eucalyptus Oil** | 2,600 | 5 | 28 | oils | `Eucalyptus Oil.jpg` |
| **Rosemary Oil** | 3,000 | 4 | 23 | oils | `Rosemary Oil.jpg` |
| **Jojoba Oil** | 4,200 | 5 | 41 | oils | `Jojoba Oil.jpg` |
| **Oatmeal Soap** | 800 | 5 | 33 | soaps | `Oatmeal Soap.jpg` |
| **Charcoal Soap** | 950 | 4 | 26 | soaps | `Charcoal Soap.jpg` |
| **Honey Soap** | 1,100 | 5 | 38 | soaps | `Honey Soap.jpg` |
| **Raw Honey** | 1,800 | 5 | 45 | foods | `Raw Honey.jpg` |
| **Chia Seeds** | 2,200 | 4 | 32 | foods | `Chia Seeds.jpg` |
| **Chamomile Tea** | 1,500 | 5 | 39 | teas | `Chamomile Tea.jpg` |

---

## 5. Interactive Features (Modals)
> ⚠️ **Important:** The product detail modal and checkout modal must be **SEPARATE** screens. First click product → see details → click "Proceed to Checkout" → see checkout form.

### 🔍 Product Detail Modal
*Opens when clicking any product card or "Buy Now" button.*
* Shows larger product image.
* Product name, full description, star rating.
* Key ingredients section.
* Price and Quantity selector (`+` / `-` buttons).
* **CTA Button:** "Proceed to Checkout" button (yellow).

### 💳 Checkout Modal
*Opens after clicking "Proceed to Checkout".*
* **Order Summary:** Displays product name, price × quantity, and total.
* **Required Form Fields:** Full Name, Phone Number, Delivery Address.
* **CTA Button:** "Send Order via WhatsApp" button (green).
* **Action:** When submitted, opens WhatsApp with a pre-filled order message containing all customer details and product information.
* **WhatsApp Number Placeholder:** `923001234567`

---

## 6. Animations & Interactions
* **Fade-in on scroll:** All sections should fade in as they appear on screen.
* **Hover effects:** Cards lift up, buttons scale slightly, images zoom gently.
* **Smooth scrolling:** Navigation links scroll smoothly to sections.
* **Active filter state:** Category filter buttons change color when active.
* **WhatsApp button pulse:** Subtle pulsing animation on the WhatsApp button.

---

## 7. Image Files Required
All images must be local files placed in the same folder as the HTML file (no readdy.ai or external URLs):
* `logo.png`
* `hero.jpg`
* `Our Story of Natural Wellness.jpg`
* `Our Promise to You.jpg`
* `Organic Skincare.jpg`
* `Herbal Oils.jpg`
* `Natural Soaps.jpg`
* `Organic Foods.jpg`
* `Herbal Teas.jpg`
* `Rose Face Cream.jpg`
* `Rose Face Cream best seller.jpg`
* `Aloe Vera Gel.jpg`
* `Neem Toner.jpg`
* `Coconut Moisturizer.jpg`
* `Lavender Oil Best seller.jpg`
* `Eucalyptus Oil.jpg`
* `Rosemary Oil.jpg`
* `Jojoba Oil.jpg`
* `Oatmeal Soap.jpg`
* `Charcoal Soap.jpg`
* `Honey Soap.jpg`
* `Raw Honey.jpg`
* `Raw Honey best seller.jpg`
* `Chia Seeds.jpg`
* `Chamomile Tea.jpg`

---

## 8. Technical Requirements & Layout Rules

### 🛠️ Technical Specifications
* Styling via **Tailwind CSS** (included via CDN).
* Icons via **Remix Icon** (included via CDN).
* Fonts via **Google Fonts** (*Playfair Display*, *Inter*, and *Pacifico*).
* Fully functional with pure HTML/CSS/JavaScript (No backend required – WhatsApp handles orders).

### 📐 Layout Rules
* **Product Grid:** 3 columns on desktop, 2 on tablet, 1 on mobile.
* **Cards:** Centered with reasonable max-width, consistent sizing (not full width).
* **Spacing:** Generous padding between sections (typically `py-20`).
* **Rounded Corners:** Consistent use of `rounded-xl` and `rounded-2xl` for cards and buttons.
* **Container:** Centered content with max-width on most sections except the product grid which can be slightly wider.

---

### 🎯 The Goal
Build a beautiful, trustworthy, nature-inspired e-commerce website that makes customers feel confident buying organic products. The site should feel premium, clean, and easy to navigate. Every product click leads to a detailed view, and every purchase goes through WhatsApp for simple order management.
