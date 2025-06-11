# 🚀 Realtime Express.js API with Socket.IO

This is a Node.js backend project using **Express.js** and **Socket.IO** to build a fast, scalable REST API with real-time capabilities.

---

## 📚 Table of Contents

- [📦 Tech Stack](#tech-stack)
- [🗂️ Project Structure](#project-structure)
- [⚙️ Getting Started](#getting-started)
- [▶️ Run the Server](#run-the-server)

---

## 📦 Tech Stack <a name="tech-stack"></a>

- Node.js
- Express.js
- Socket.IO
- dotenv
- nodemon
- morgan

---

## 🗂️ Project Structure <a name="project-structure"></a>
```plaintext
Medical-Be
├── app.js
├── associations
│   ├── package-item.association.js
│   └── user-role.association.js
├── bin
│   └── www
├── config
│   ├── database.js
│   ├── db_connect.js
│   ├── passport.js
│   └── sync.js
├── controllers
│   ├── address.controller.js
│   ├── appointment.controller.js
│   ├── auth.controller.js
│   ├── brand.controller.js
│   ├── cart.controller.js
│   ├── category.controller.js
│   ├── country.controller.js
│   ├── doctor.controller.js
│   ├── doctor_assignment.controller.js
│   ├── indication.controller.js
│   ├── ingredient.controller.js
│   ├── ingredient_description.controller.js
│   ├── medical_object.controller.js
│   ├── medical_record.controller.js
│   ├── message.controller.js
│   ├── order.controller.js
│   ├── origin.controller.js
│   ├── package_booking.controller.js
│   ├── package_item.controller.js
│   ├── payment_method.controller.js
│   ├── product.controller.js
│   ├── product_detail.controller.js
│   ├── product_image.controller.js
│   ├── product_option.controller.js
│   ├── product_section.controller.js
│   ├── review.controller.js
│   ├── schedule.controller.js
│   ├── service_category.controller.js
│   ├── service_item.controller.js
│   ├── service_pkg.controller.js
│   ├── statisticsController.js
│   └── user.controller.js
├── jods
│   └── orderCancelJob.js
├── len
├── middlewares
│   ├── auth.middleware.js
│   ├── role.middleware.js
│   ├── schedule.middleware.js
│   ├── upload.middleware.js
│   ├── validateProduct.middleware.js
│   ├── validateProductOption.middleware.js
│   └── validateRequest.middleware.js
├── models
│   ├── address.model.js
│   ├── appointment.model.js
│   ├── brand.model.js
│   ├── cart.model.js
│   ├── cart_items.model.js
│   ├── category.model.js
│   ├── country.model.js
│   ├── department.model.js
│   ├── doctor-assignment.model.js
│   ├── doctor.model.js
│   ├── index.js
│   ├── indication.model.js
│   ├── medical-record.model.js
│   ├── medical_object.model.js
│   ├── message.model.js
│   ├── message_item.model.js
│   ├── order.model.js
│   ├── order_item.model.js
│   ├── order_status_history.model.js
│   ├── origin.model.js
│   ├── package-booking-request.model.js
│   ├── package-item.model.js
│   ├── payment_method.model.js
│   ├── product.model.js
│   ├── product_detail.model.js
│   ├── product_detail_section.model.js
│   ├── product_image.model.js
│   ├── product_option.model.js
│   ├── refresh.model.js
│   ├── review_replies.model.js
│   ├── reviews.model.js
│   ├── role.model.js
│   ├── schedule.model.js
│   ├── section_ingredient_descriptions.model.js
│   ├── section_ingredients.model.js
│   ├── service-category.model.js
│   ├── service-item.model.js
│   ├── service-pkg.model.js
│   ├── user-role.model.js
│   └── user.model.js
├── package-lock.json
├── package.json
├── public
│   └── stylesheets
│       └── style.css
├── routes
│   ├── address.routes.js
│   ├── appointment.routes.js
│   ├── auth.routes.js
│   ├── brand.routes.js
│   ├── cart.routes.js
│   ├── category.routes.js
│   ├── country.routes.js
│   ├── department.routes.js
│   ├── detail_section.routes.js
│   ├── doctor.routes.js
│   ├── doctor_assignment.routes.js
│   ├── index.js
│   ├── indication.routes.js
│   ├── ingredient.routes.js
│   ├── ingredient_description.routes.js
│   ├── medical_object.routes.js
│   ├── medical_record.routes.js
│   ├── message.routes.js
│   ├── order.routes.js
│   ├── origin.routes.js
│   ├── package_booking_request.routes.js
│   ├── package_item.routes.js
│   ├── payment.routes.js
│   ├── product.routes.js
│   ├── product_detail.routes.js
│   ├── product_image.routes.js
│   ├── product_option.routes.js
│   ├── reviews.routes.js
│   ├── schedule.routes.js
│   ├── service_category.routes.js
│   ├── service_item.routes.js
│   ├── service_pkg.routes.js
│   ├── statistics.routes.js
│   └── user.routes.js
├── services
│   └── booking_service.service.js
├── utils
│   ├── cloudinary.js
│   ├── mailService.js
│   ├── productFileds.js
│   ├── productInclude.js
│   ├── sortObjectPayment.js
│   └── vnpay.js
└── views
    ├── error.ejs
    └── index.ejs
```

## ⚙️ Getting Started <a name="getting-started"></a>
### 1. Clone the repository
```bash
git clone https://github.com/your-username/your-express-repo.git
```
```bash
cd Medical-Be
```

### 2. Install dependencies
```bash
npm install
```
### 3. Configure environment variables
Example:
```bash
PORT=3000
```

## ▶️ Run the Server <a name="run-the-server"></a>
```bash
npm start
```
The server will run at: http://localhost:3000




