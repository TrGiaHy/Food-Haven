# Food-Haven



Food Haven is a full-featured e-commerce web application built with ASP.NET Core Razor Pages (.NET 8, C# 12). The platform connects food lovers, sellers, and administrators, providing a seamless experience for online food shopping, store management, and community engagement.

---

**🎯 Project Purpose**

Food Haven aims to:

•	Enable users to discover, purchase, and review a wide variety of food products.

•	Empower sellers to manage their stores, products, orders, and customer interactions.

•	Provide administrators with tools to oversee platform activity, handle complaints, and ensure quality.

---

**🧑‍💻 Key Features**

For Customers

•	Account Management: Register, log in, update profile, and manage security.

•	Product Browsing: Search, filter, and view detailed product information.

•	Shopping Cart \& Orders: Add products to cart, apply vouchers, place orders, and track order status.

•	Wishlist: Save favorite products for later.

•	Recipe Community: Browse, create, review, and favorite recipes; view ingredient tags and cooking types.

•	Chat: Real-time chat with sellers and support via SignalR.

•	Complaint System: File complaints about orders, request refunds, or escalate to admin.



For Sellers

•	Store Management: Register and update store details, including images and descriptions.

•	Product Management: Create, update, and manage products, categories, types, and images.

•	Order Handling: View, process, and update order statuses; manage sales history.

•	Voucher Management: Create and manage promotional vouchers for customers.

•	Complaint Resolution: Respond to customer complaints and escalate issues to admin if needed.

•	Feedback: View and reply to customer reviews and feedback.

•	Statistics Dashboard: Access sales, product, and customer analytics.



For Administrators

•	User \& Seller Management: Approve seller registrations, manage user accounts, and handle bans.

•	Store Oversight: Approve or reject store registrations, manage store reports, and monitor store activity.

•	Complaint \& Report Handling: Oversee complaints escalated by users or sellers, provide admin responses.

•	Content Moderation: Manage categories, recipes, ingredient tags, and vouchers.

•	Platform Analytics: View platform-wide statistics and reports.

---

**🏗️ Technical Stack**

•	Frontend: ASP.NET Core Razor Pages, Bootstrap 5, jQuery, Grid.js, SweetAlert2, Notify.js

•	Backend: ASP.NET Core (.NET 8), Entity Framework Core, ASP.NET Core Identity

•	Database: SQL Server

•	Real-time Communication: SignalR (for chat and notifications)

•	Authentication: Role-based (User, Seller, Admin)

•	Other: CKEditor (rich text editing), Dropzone (image uploads), Flatpickr (date pickers)

---

**🗂️ Project Structure**

•	Models/DBContext/: Entity models and EF Core context

•	Repository/ViewModels/: View models for data transfer between layers

•	Food\_Haven.Web/Controllers/: Razor Pages controllers for Users, Sellers, and Admins

•	Food\_Haven.Web/Views/: Razor Pages and shared layouts for all roles

•	wwwroot/: Static assets (CSS, JS, images)

---

**📦 Main Database Entities**

•	AppUser: User accounts (customers, sellers, admins)

•	StoreDetails: Store information and owner relationship

•	Product, ProductTypes, ProductImages: Product catalog and variants

•	Order, OrderDetail, Cart, Wishlist: Shopping and order management

•	Voucher: Discount and promotional codes

•	Complaint, ComplaintImage: Order complaints and evidence

•	Recipe, RecipeReview, FavoriteRecipe, IngredientTag, TypeOfDish: Recipe community features

•	Message, MessageImage: Real-time chat system

•	BalanceChange: User wallet and transaction history

---

