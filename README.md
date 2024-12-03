# **Magento 2 WhatsApp Share Extension**

In the age of instant messaging, sharing product details directly through WhatsApp is becoming increasingly popular among online shoppers. The **Magento 2 WhatsApp Share extension** is designed to seamlessly integrate with your Magento 2 store, allowing customers to share products with friends and family via WhatsApp. This simple yet powerful tool enhances social engagement and helps drive more traffic to your store, providing a direct marketing channel to potential customers.

## **How It Works**

The Magento 2 WhatsApp Share extension integrates with your product pages, adding a WhatsApp sharing button. When a user clicks on the button, a WhatsApp chat opens with a pre-filled message that includes the product details, such as the name, price and link to the product page. This makes it easier for customers to share your products with their contacts, potentially increasing visibility and driving traffic to your store.

## **Key Features**

* Enable WhatsApp sharing globally, or customize it for specific products or categories.  
* Utilize UTM tracking to monitor traffic from WhatsApp shares in Google Analytics.  
* Supports WhatsApp sharing via both the mobile app and web versions.

## **Seamless User Experience**

The WhatsApp Share button seamlessly appears on product pages, allowing customers to easily share product details with their contacts. Its clean, minimal design ensures it doesn’t distract from the product, maintaining focus on the item itself. Optimized for both mobile and desktop devices, the button ensures a smooth sharing experience across all platforms. When clicked, users are instantly redirected to the WhatsApp app with a pre-filled message that includes the product link, ready to be shared.

## **Customizable Button Placement and Design**

Admins can easily customize the placement of the WhatsApp share button on product pages, choosing its position—whether on the product image, below the description, or anywhere that fits the store's layout. The button’s size, color, and text can also be adjusted to match the store’s branding, ensuring it aligns with the overall design while maintaining optimal visibility.

## **No Third-Party Dependencies**

The extension does not require any third-party services or APIs, ensuring that the performance of your website remains unaffected. This makes it a reliable and secure solution for WhatsApp integration.

## **Boosts Social Engagement**

Encouraging customers to share their favorite products can create organic word-of-mouth marketing. With the WhatsApp Share extension, you are tapping into a fast-growing platform that’s widely used for both personal and business communication.

## **Extension Installation**

To install the **Magento 2 WhatsApp Share extension**, follow these simple steps:

### **Step 1** 

Extract the zip file and upload the extension to the root directory of your Magento 2 installation using FTP.

### **Step 2:**

### Login to your SSH and run below commands step by step:

* php bin/magento setup:upgrade  
* For Magento version 2.0.x to 2.1.x \- php bin/magento setup:static-content:deploy  
* For Magento version 2.2.x & above \- php bin/magento setup:static-content:deploy –f  
* php bin/magento cache:flush

## **How to Configure the Magento 2 WhatsApp Share Extension**

### **Step 1: Configure Settings**

To configure the extension, log in to your Magento 2 admin panel and navigate to **Stores \> Configuration \> WhatsApp Share**. Here, you’ll find several settings to customize the extension.

![Configure Settings](https://github.com/user-attachments/assets/69000db2-7836-4670-b79c-bea1eb4ec1f7)

* **WhatsApp Share**: Enable or disable the WhatsApp Share extension.  
* **Enable WhatsApp Share**: Choose whether to enable the extension globally, for specific categories, or for individual products.  
* **Show WhatsApp Share Button on Category Page**: Set to "Yes" to display the WhatsApp share button on category pages in addition to product pages.

### **Step 2: Check Sharing Options**

The sharing settings allow you to configure how users can share your store's products through WhatsApp.

![Check Sharing Options](https://github.com/user-attachments/assets/abc88510-2049-4003-b2c9-0aa66b4cea8d)

* **WhatsApp Share Button Type**: Select the preferred type of WhatsApp Share button.  
* **Custom Sharing Message**: Add a personalized message to be shared along with the product details.  
* **Product Name**: Enable this option to share the product name on WhatsApp.  
* **Product Description**: Enable this option to include the product description in the WhatsApp share message.  
* **Product Price**: Enable this option to share the product price via WhatsApp.  
* **Deal On**: Select a deal to share from the dropdown list. You can choose between "Special Price" or "Discount." If you select "Special Price," ensure you have set special prices for your products. If you select "Discount," configure the catalog or shopping cart price rule in the backend and provide a custom message to share the discount deal via WhatsApp.  
* **Special Price Message**: Enter a custom message to share the special price deal with WhatsApp contacts.

### **Step 3: Check UTM Tracking Settings**

UTM tracking helps analyze visits and conversions in Google Analytics by appending a tracking code to the shared URL. You can configure the UTM Tracking Settings as follows:

![Check UTM Tracking Settings](https://github.com/user-attachments/assets/45828572-1465-4389-8f17-4355211be161)

* **UTM Tracking**: Enable UTM Tracking for WhatsApp sharing here.  
* **Campaign Source**: Set the source for tracking in Analytics.  
* **Campaign Medium**: Define the medium for tracking in Analytics.  
* **Campaign Name**: Assign a name for tracking in Analytics.

### **Step 4: Check Bitly Short URL Settings**

Short URLs are easier to manage, and this extension allows you to use the Bitly URL shortener when sharing product URLs on WhatsApp. Here’s how to configure the Bitly Short URL settings:

![BitlyURL](https://github.com/user-attachments/assets/5fab4bcd-c2a0-4473-bf78-ce9720774a1c)

* **Bitly Short URL**: Enable the Bitly URL shortener to share shortened product URLs.  
* **API Key**: Enter your Bitly API key to enable short URLs for sharing on WhatsApp.  
  * To obtain your Bitly API key, register and log in to your Bitly account. Then, go to **Profile Settings** and click on **Generate Access Token**.

### **Step 5: Generate Access Token**

![Generate Access Token](https://github.com/user-attachments/assets/8c36f7c1-851b-4cb0-a1f4-49079789712d)

![Check Bitly Short URL Settings](https://github.com/user-attachments/assets/4549743d-f0bb-4f4b-b88c-063c6522ee70)

Re-enter your Bitly password and click on **Generate Token**.

### **Step 6: Category-Specific WhatsApp Share**

Navigate to **Catalog \> Categories**, select the category for which you want to enable WhatsApp sharing, and set the option to **YES**.

![Category-Specific WhatsApp Share](https://github.com/user-attachments/assets/7f64a85f-b8e9-4700-a1f6-5031bbadcd85)

* **WhatsApp Share**: Enable WhatsApp sharing for this specific category

### **Step 7: Product-Specific WhatsApp Share**

Navigate to **Catalog \> Products**, select the product for which you want to enable WhatsApp sharing, and set the option to **YES**.

![Product-Specific WhatsApp Share](https://github.com/user-attachments/assets/c83f2cb4-eb24-4881-bf29-a57a81518338)

* **WhatsApp Share**: Enable WhatsApp sharing for this specific product.

### **Step 8: Check WhatsApp Share on the Frontend**

After successfully configuring the extension, the WhatsApp Share button will be enabled on both the Category and Product Pages, along with features like UTM Tracking and more, as shown below.

![Check WhatsApp Share on the Frontend](https://github.com/user-attachments/assets/afda59ff-6873-4812-a79e-7c24557a00b9)

* **WhatsApp Share on Category Page**  
  If you’ve enabled the share button on the category page, it will appear here.

![WhatsApp Share on Category Page](https://github.com/user-attachments/assets/8691f2d7-e808-47af-b6fa-3d9c0e4d0db4)

* **WhatsApp Share on Product Page**

![WhatsApp Share on Product Page](https://github.com/user-attachments/assets/35e3c17a-4d8d-4dfb-ac45-173fd1591152)

* **Contact Selection in WhatsApp**  
  When users click the WhatsApp share button, they are redirected to the web or app version of WhatsApp, depending on whether they are using a desktop or mobile device. In the app, they will be prompted to choose a contact to share the product details with.

![Contact Selection in WhatsApp](https://github.com/user-attachments/assets/1d2b638b-c390-4216-b5f0-2ec29c678e26)

* **Sharing in WhatsApp**

![Sharing in WhatsApp](https://github.com/user-attachments/assets/13a978b1-dd6f-4b9d-9236-bfadc2f7fbbd)

* **UTM Tracking Enabled in Shared URL**

## Download our [Magento 2 WhatsApp Share](https://meetanshi.com/magento-2-whatsapp-share.html) Extension
