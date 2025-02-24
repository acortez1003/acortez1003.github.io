---
title: "eCommerce"
excerpt: "A full-stack eCommerce web application developed using .NET MAUI and C#. The application provides full shopping and inventory management functionality. To visit the GitHub repository, click [here](https://github.com/acortez1003/eCommerce_Su2024).<br/><img src='/images/ecommerce.PNG'>"
collection: portfolio
---

During my C# class, I developed a functional eCommerce web application that provides shopping and inventory management functionalities. This web application keeps up with MVVM architecture.

## Inventory Management

The `InventoryView` has all CRUD (Create, Read, Update, Delete) operations for products. We can change product details such as the name, the price and the amount.

![InventoryView](/images/inventory.PNG)

Clicking BOGO will turn it on/off for a specific object.

![Add Product](/images/add_product.PNG)

We can also add a product ...

![View new product](/images/new_product.PNG)

... and see it added to our inventory list!

## Shopping Functionalities

In the shopping area, the user can create a shopping cart, or use the default shopping cart. The inventory and shopping cart are dynamically linked, ensuring that any updates made to the inventory are reflected in the shopping area. This is achieved through data binding.

![Cart](/images/cart.PNG)

This `ShopView` is also where the tax rates are implemented and seen through the receipt. Here is also where the markdown value is applied, if a product has one.