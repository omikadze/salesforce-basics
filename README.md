# Salesforce Basics

**Table of context:**
- [Salesforce User Basics](#salesforce-user-basics)
  - [Salesforce User Basics](#welcome-to-salesforce)
  - [Who sees what](#Who-sees-what)
  - [Collaboration using Salesforce](#collaboration-using-salesforce) 
  - [What Is CRM?](#What-is-crm)
  - [How Salesforce Organizes Your Data](##how-salesforce-organizes-your-data)
  - [Salesforce Standard Objects](#salesforce-standard-objects)
- [Get Started with Commerce Cloud](#get-started-with-commerce-cloud)
  - [What Is Commerce Cloud?](#what-is-commerce-cloud)
  - [What Are the Commerce Cloud Products and Capabilities?](#what-are-the-commerce-cloud-products-and-capabilities)
  - [Why Does Commerce Cloud Need Different Products for B2B and B2C Commerce?](#why-does-commerce-cloud-need-different-products-for-b2b-and-b2c-commerce)
  - [The Key Categories of B2C Commerce](#the-key-categories-of-b2c-commerce)
  - [Einstein for Commerce](#einstein-for-commerce)
  - [Learn About Commerce Cloud Order Management](#learn-about-commerce-cloud-order-management)
  - [Learn About B2B Commerce](#learn-about-b2b-commerce)
- [Salesforce B2C Commerce (Explore how B2C Commerce transforms the online shopping experience)](#salesforce-b2c-commerce-explore-how-b2c-commerce-transforms-the-online-shopping-experience)
  - [B2C Commerce Shopping Experience](#b2c-commerce-shopping-experience)
  - [B2C Commerce Features](#b2c-commerce-features)
- Salesforce B2C Commerce for Merchandisers(Configure product listings, make them easy to find, and give shoppers discounts they love.)[#salesforce-b2c-commerce-for-merchandisers--configure-product-listings-make-them-easy-to-find-and-give-shoppers-discounts-they-love-]
  - [B2C Commerce Product Data](#b2c-commerce-product-data)
  - [B2C Commerce Search](#b2c-commerce-search)
  - [B2C Commerce Campaigns and Promotions](#b2c-commerce-campaigns-and-promotions)
- [B2C Commerce Campaigns and Promotions (Plan and configure campaigns and promotions for your B2C Commerce storefront)](#b2c-commerce-campaigns-and-promotions-plan-and-configure-campaigns-and-promotions-for-your-b2c-commerce-storefront)
  - [Explore Campaigns and Experience Types](#explore-campaigns-and-experience-types)
  - [Create Qualifiers](#create-qualifiers)
  - [Discount Types and Promotion Controls](#discount-types-and-promotion-controls)
  - [Create Promotions](#create-promotions)
  - [Create Campaigns](#create-campaigns)
- [Salesforce B2C Commerce for Developers (Learn about the B2C Commerce developer tools you can use to create storefront application projects)](#salesforce-b2c-commerce-for-developers-learn-about-the-b2c-commerce-developer-tools-you-can-use-to-create-storefront-application-projects)
  - [Commerce Cloud Business Manager](#commerce-cloud-business-manager)
  - [B2C Commerce Development Environment](#b2c-commerce-development-environment)
  - [Commerce Cloud Storefront Reference Architecture](#commerce-cloud-storefront-reference-architecture)
  - [B2C Commerce Business Objects](#b2c-commerce-business-objects)
- [Architecture of Salesforce B2C Commerce](#architecture-of-salesforce-b2c-commerce)
  - [Get Started Configuring Your B2C Commerce Sites](#get-started-configuring-your-b2c-commerce-sites)
  - [Learn About Importing and Exporting Data](#learn-about-importing-and-exporting-data)
  - [Learn About B2C Commerce Replication](#learn-about-b2c-commerce-replication)
- [Tools & Resources for Salesforce B2C Commerce Developers](#tools--resources-for-salesforce-b2c-commerce-developers)
  - [Explore the Developer Resources](#explore-the-developer-resources)
  - [Install and Configure UX Studio](#install-and-configure-ux-studio)
  - [Access the GitHub Repositories]()
  - [Install and Configure SFRA]()
  

## Salesforce User Basics

### Welcome to Salesforce

Salesforce is your customer success platform, designed to help you sell, service, market, analyze, and connect with your customers. Using standard products and features, you can manage relationships with prospects and customers, collaborate and engage with employees and partners, and store your data securely in the cloud. 

So what does that really mean? Well, before Salesforce, your contacts, emails, follow-up tasks, and prospective deals might have been organized something like this:

![GitHub Logo](/photo1.png)

It’s hard to get the full picture of your prospective customer. And you certainly can’t access the data from anywhere, anytime, nor can your manager or executives see your progress on deals in flight.

Salesforce takes all of that important data and organizes it into a simple user interface. It’s one place for you to:

* Manage all your contacts
* Work with your prospective customers
* Organize tasks and to-do items
* Focus on the right deals
* Collaborate with your team
* Showcase your big wins
* Close more business

And because it’s stored on our secure cloud, you can access your data anytime, anywhere, whether you’re on desktop or mobile.
![GitHub Logo](/photo2.png)

### Who sees what

Access determines your ability to open and interact with data stored in Salesforce. The data you can create, view, edit, and delete is determined by settings your admin maintains. Access can be simple or multilayered, depending the complexity of your company’s needs. The important thing you need to know is that Salesforce has options for who can see and edit data, and your admin helps to set these up and maintain them.
With the right security enabled, your whole company can be on Salesforce, and one of the best reasons to do that is to harness the power of collaboration.

### Collaboration using Salesforce

In addition to technology for managing your sales process, Salesforce includes a platform for collaboration. You can create groups, follow people and topics, ask questions, post informal polls, share files and links, and mention colleagues with whom you’d like to connect. You can also ask questions and get answers, crowdsourcing expertise from across your company. You can find experts who can help you with overcoming objections as they come up. You can search for competitive information to help you through the negotiation stage. You can get help from your leaders and teammates as you work on steps to close.

But perhaps the best part about collaborating in Salesforce is that it’s all stored for future reference. Rather than having key insights and answers to important questions living in individual email inboxes or in hallway conversations, collaboration in Salesforce is accessible and searchable. 

And because it’s in Salesforce, this is collaboration that can happen in context, right on individual deals, tasks, support issues, and more. This is the power of collaboration combined with CRM.

### What Is CRM?

CRM stands for Customer Relationship Management. This technology allows you to manage relationships with your customers and prospects and track data related to all of your interactions. It also helps teams collaborate, both internally and externally, gather insights from social media, track important metrics, and communicate via email, phone, social, and other channels.

In Salesforce, all of this information is stored securely in the cloud.

### How Salesforce Organizes Your Data

Salesforce organizes your data into objects and records. You can think of objects like a tab on a spreadsheet, and a record like a single row of data.

![GitHub Logo](/photo3.png)

In Salesforce, objects are accessed via the navigation menu. Select any record to drill into a specific account, contact, opportunity, or any other record in Salesforce.

So, that’s objects, records, and more, and now you have some insight into how your data is organized in Salesforce using our spreadsheet example. But unlike an actual spreadsheet, your Salesforce data is stored in our trusted, secure cloud and has an easy-to-use interface, which you can access both from the desktop and your mobile device. So it’s similar to a spreadsheet, but in Salesforce, your data is all tracked, shared, and has apps connected to it. Salesforce comes with a set of standard objects already set up and ready for use.

### Salesforce Standard Objects
Here are some of the core standard objects you’ll be using with Salesforce, and a description of how each one is used.

* Accounts are the companies you’re doing business with. You can also do business with individual people (like solo contractors) using something called Person Accounts.
* Contacts are the people who work at an Account.
* Leads are potential prospects. You haven’t yet qualified that they are ready to buy or what product they need. You don’t have to use Leads, but they can be helpful if you have team selling, or if you have different sales processes for prospects and qualified buyers.
* Opportunities are qualified leads that you’ve converted. When you convert the Lead, you create an Account and Contact along with the Opportunity.

Salesforce CRM allows you to manage and access your data in sophisticated ways that you could never do with a simple spreadsheet. Your records can be linked together to show how your data is related, so you can see the whole picture.

## Get Started with Commerce Cloud

### What Is Commerce Cloud?

Commerce Cloud is a key part of the Salesforce Customer Success Platform and offers ecommerce solutions for B2C (business to consumer) and B2B (business to business) customers. That means that organizations purchase Commerce Cloud to provide the best ecommerce websites to their customers who are shopping online—whether they are consumers buying the latest fashion or businesses making a large wholesale purchase.

Commerce Cloud was created in July 2016, when Salesforce acquired Demandware, an industry leader in ecommerce sites and solutions designed with the shopper in mind. The Demandware technology has grown and evolved to become the Salesforce B2C Commerce product.

In 2018, Commerce Cloud expanded beyond B2C ecommerce with the acquisition of CloudCraze, a leader in ecommerce designed for organizations selling to business customers. What was CloudCraze is now the Salesforce B2B Commerce product.

Now Commerce Cloud spans across B2C and B2B to offer leading ecommerce solutions for all types of companies looking to sell products and services online.

### What Are the Commerce Cloud Products and Capabilities?

Commerce Cloud features two core capabilities: B2B Commerce and B2C Commerce.

#### B2B Commerce
Consumers aren’t the only ones buying online. Businesses need to make purchases too. For example, a wholesaler can place an order of merchandise to stock multiple stores for an entire season, or a factory can purchase replacement parts for a specific type of machine. B2B Commerce powers sites for many of the world’s largest companies that span manufacturing, consumer goods, technology, healthcare, and more.

These sites are designed for extremely large carts and purchases consisting of hundreds or thousands of items. They include B2B-specific functionality such as:

* Authenticated sites, including logins for each visitor
* Shopping carts that can accommodate hundreds of items per order
* Two-click reorders to make large, frequent orders fast and easy
* Custom storefront themes for a unique look and feel for each account
* Specific product catalogs by account for a selected subset of products
* Negotiated/contract pricing by account or by customer segment
* Complex shipping functionality allowing for multiple delivery dates and locations
* Multiple payment types like credit card, purchase order, and ACH

#### B2C Commerce

B2C Commerce lets brands create and coordinate shoppers’ online experiences and transactions across digital channels and devices. Web and mobile sites are a huge part of the online experience. Brands can launch and manage responsive ecommerce sites—for web and mobile—that have rich online storefronts, shopping cart and checkout functionalities, and full customization capabilities.

For many retailers, one site isn’t enough. When retailers have more than one brand, or when they sell in multiple countries, they typically need different sites for each brand and geography. Commerce Cloud lets retailers launch sites for multiple brands and geographies and then manage them all in a single place.

But shoppers don’t just visit web and mobile sites, they also interact with brands through email, social media, and in stores. By integrating their ecommerce sites with their marketing and service solutions, brands can make every email and social media interaction more personalized and relevant to shoppers. And by bringing ecommerce into the store through kiosks or store associate application they can provide shoppers with improved service and access to more inventory than what is available in store, often helping to “save the sale!”

##### Einstein for B2C Commerce
Einstein for B2C Commerce features are directly embedded into B2C Commerce to empower marketers and merchandisers to use AI without having to hire a data scientist. Using the wealth of their commerce data, they now have the power to make smarter decisions and supercharge personalization across commerce journeys.

Einstein intelligence powers five key B2C Commerce capabilities: Einstein Product Recommendations, Einstein Predictive Sort, Einstein Commerce Insights, Einstein Search Dictionaries, and Einstein Search Recommendations.
  
##### Order Management for B2C Commerce
Order Management for B2C Commerce gives brands full visibility into orders and inventory data. Self-service tools for shoppers, and smart up-sell and cross-sell opportunities for service agents inspire shopper loyalty and drive revenue for companies.

With Order Management, merchants can leverage the extensibility of the Salesforce Platform to design complex processes with flow, and connect effortlessly to logistics partners via the AppExchange and MuleSoft. This gives companies the flexibility to ship from anywhere, creating efficiencies that save time and money.

##### Endless Aisle for B2C Commerce
Endless Aisle for B2C Commerce provides brands with physical stores the ability to offer shoppers limitless product choice and eliminate lost sales by extending digital commerce into the store. Brands can offer to sell and ship any product to their customers, regardless of its location—helping to deliver product faster and more cost effectively. And brands can also empower store associates with real-time access to digital inventory.


### Why Does Commerce Cloud Need Different Products for B2B and B2C Commerce?

Commerce sites built for business users (B2B) are designed for a smaller set of known customers who often make large or frequent purchases. For example, a chemical manufacturer can sell to 1,000 factories that reorder each month. B2B sites need to make it easy for customers to make large orders, and then reorder the right products quickly.

Commerce sites built for the consumer (B2C)—the kind that all of us use for regular online shopping—are designed to attract a large number of guest shoppers to the site. Once a shopper is on the site, companies want to show them the most relevant products, let them quickly add a few (or several!) products to their cart, and then pay and finish the transaction quickly. It’s important for B2C sites to scale for big sales or holidays when millions of shoppers can be on the site at the same time.

### The Key Categories of B2C Commerce

B2C Commerce is broken down into these categories:

* Commerce Storefront
* Merchandising and Marketing
* Multi Site Management and Localization
* B2C Commerce Extensions

#### B2C Commerce Storefront

The B2C Commerce storefront is essentially an ecommerce site. But it’s so much more than just a website with an online cart. Brands can differentiate, manage, and customize shoppers’ ecommerce experience.

Capabilities include the Storefront Reference Architecture (SFRA), a robust reference architecture that helps brands build and launch sites quickly and easily using mobile-first best practices. While each site has its own feature-rich storefront, retailers can use the reference architecture to create it. It sits outside the platform API layer and is fully customizable. It lets you create storefronts that support multiple languages and currencies. It provides a modern shopping cart and checkout that features Save for Later (to save an item to a wishlist for a logged in user), optimized user flows, Apple Pay, and other wallet options to make the checkout process as fast and seamless as possible.

Capabilities also include prebuilt integrations to extend site functionality, and open APIs so that your site can connect to any third-party data or applications like user reviews.

#### Merchandising and Marketing

Merchandising and Marketing capabilities in B2C Commerce draw on the power and insights of AI, giving retailers limitless opportunities for personalized engagement with their customers. These capabilities help brands fuel ecommerce growth with features that empower:

* Product, pricing, and catalog management, so that marketers and merchandisers can sync products and pricing across categories, catalogs, currencies, and sites
* Merchandising and promotion management, to quickly launch campaigns and promotions
* Site search and guided navigation that help online shoppers zero in on the perfect product
* Faster AI-powered personalization that uses machine learning to deliver personalized offers and product recommendations

#### Multi Site Management and Localization

Global retail brands need unique, localized sites for each market. B2C Commerce is a leader in internationalization and helps customers easily create and manage additional, geo-specific sites that encompass different customs, cultures, currencies, and languages. For example, a retailer focusing on the United States, France, and Germany is most likely to have a unique website dedicated to each country. Brands can target their content, offers, and products by language, country, region, state, or city.

Multi Site Management also empowers regional marketing teams with a global reference storefront that lets them build and launch sites quickly with multi-lingual, multi-currency logic. Plus, user interfaces are available in English, Chinese, Japanese, French, Italian, Korean, and Portuguese

#### B2C Commerce APIs

B2C Commerce APIs take brands beyond the website to use digital capabilities across social, mobile, and even in-store channels. These include:

* APIs to connect with third-party applications
* Social media extensions, to extend commerce into social channels and online communities, such as Instagram and Facebook
* In-store endless aisle and “clienteling,” to help in-store shoppers find the item they need, even if it’s not available at that specific store location. (This is a reference app that uses B2C Commerce customer, product, and inventory data to enable store associates to access this information to complete sales in the store.)

### Einstein for Commerce

Einstein for Commerce features are directly embedded into Salesforce B2C Commerce to delight shoppers, make merchants more productive, and most importantly—grow revenue. This is all achieved through AI and machine learning, using their own wealth of commerce data.

#### Einstein Product Recommendations

Product Recommendations uses machine learning to make suggestions personalized to a consumer’s shopping experience. Whether a shopper is a guest or known—that is, signed in to an account—these recommendations suggest the most relevant products throughout a consumer’s shopping journey to keep them engaged on the web site, and help them browse more efficiently.

Merchants can choose from multiple recommendation types. They can use traditional recommendations that show like-for-like products, for example, where a shopper sees blue shoes recommended on a product detail page for another pair of blue shoes.
Einstein Product Recommendations present customers with the right products at the right time. They encourage more purchases and maximize a brand’s revenue. But they do something else that’s just as important, if less quantifiable. They offer each customer a delightful shopping experience through personalized—perhaps even thoughtful—attention to their interests, based on the items they themselves have shown interest in.  And happy shoppers are good for business.

#### Einstein Predictive Sort

With Einstein Predictive Sort, brands can automatically personalize the order of products shown on each search results or category page. This means products most relevant to a shopper show up first based on their past browsing and buying behavior. Predictive Sort makes the web experience more enjoyable since shoppers don’t have to scroll through as many products and pages to find items of interest.

It’s even more impactful for shoppers using a mobile device. Mobile screens typically show fewer products per page, and shoppers don’t like to click and scroll through several pages to find what they’re looking for. Einstein Predictive Sort is a simple way to make the mobile shopping experience faster and more seamless.

#### Einstein Search Recommendations

Einstein Search Recommendations powers personalized type ahead search guidance for each individual shopper on site. This Google-ifys the brand’s site search so that shoppers are automatically guided to the best search terms for them.

For example, if one shopper starts to type the letter s, she might see the word sandals autocomplete for her. This is based on her past shopping and browsing history. If another shopper types the letter s, he might see the word sneakers autocomplete based on his history.

#### Einstein Commerce Insights

Einstein Commerce Insights empowers merchandisers to interpret purchasing behavior using a powerful shopping basket analysis dashboard. Merchandisers can choose key items in their inventory and learn which products shoppers most commonly purchase along with them. Merchandisers can drill into data on specific products based on date range, and gain insight into metrics such as product-specific sales and top “co-purchase” categories.

#### Einstein Search Dictionaries

Einstein Search Dictionaries consumes all the site searches and surface terms that are used in searches, but not yet in the retailer’s keyword list. It then makes recommendations to merchandisers, for example, synonyms that can be added to the list. Before, if retailers wanted to find missing search terms and pick the synonyms list to add them to, they had to sift through a long spreadsheet and guess which one they wanted.

Einstein Search Dictionaries analyzes data across B2C Commerce to find relationships between search terms, and then recommends the synonym list to add them to. For example, a shopper searching for “mauve sweater” might not get any results. But Einstein Search Dictionaries, seeing a potential relationship—mauve being sort of pink—will recommend adding “mauve” to the synonym list for “pink” and “purple.” Now, a shopper looking for a "mauve sweater" might see exactly what they want. The benefits for shoppers and retailers are clear. Shoppers aren’t disappointed, coming away empty-handed when they can’t find the stuff they want. Retailers benefit in multiple ways: by not losing a sale to a customer who can’t find what's actually in stock, and by reducing some of their workload so they can focus on other important site merchandising tasks.

### Learn About Commerce Cloud Order Management

Order Management for B2C Commerce gives retailers an all-inclusive view of customers, orders, returns and exchanges, inventory, products, and promotions across physical and digital channels. This feature helps retailers process orders and optimize their inventory—and so much more.

If you’ve bought anything online, you probably relied on an order management system when you checked on your order or even looked up previous orders. But Order Management also drives more complex, “cross-channel” transactions. Have you ever bought something online and then picked it up in the store? Or returned to a store an item you bought online? You were engaging in a cross-channel transaction, a shopping experience that is becoming more and more popular with consumers.

Order Management, an add-on to B2C Commerce, shares order data in real time with B2C Commerce. That's why it's "for B2C Commerce!"


#### Capabilities of Commerce Cloud Order Management for B2C Commerce

* Enterprise Inventory

At the core of every successful shopping experience is an accurate view of the inventory that’s available for sale. Enterprise Inventory makes all available inventory visible—whether it's in stores or in distribution centers—in a single, authoritative available-to-sell record. So all selling and service channels have an accurate representation of sellable inventory no matter where it sits. This makes more units of inventory available to shoppers, rather than just the units sitting in an individual area or store. It also prevents over sells, which can frustrate consumers and retailers alike.

* Distributed Order Management

The Order Management engine, sometimes called Distributed Order Management, encompasses all of the sophisticated logic that it takes to allocate items, fulfill an order and manage the entire order life cycle. This baked-in intelligence means retailers can accept orders and returns from multiple selling channels—online, mobile, in-store. Retailers can process invoices, payments, and sales tax. And it lets retailers set allocation rules for backorders, preorders, split orders, and drop-ship orders to ensure each and every one is fulfilled cost-effectively and efficiently.

* Store Fulfillment

Mobile optimized, real-time tools for retailers let store associates quickly and easily handle fulfillment requests that are ready for shipment. The Store Fulfillment feature also enables retailers to have products at the ready for a customer who wants to pick items up in-store.

* Customer Service

The customer service features of Order Management enable universal order intervention. From any channel—phone, web, store, even customer self-serve—customer service reps have a complete view of shoppers, the product catalog, inventory, and orders. So reps and associates can provide the best possible service when they handle order inquiries or modifications.

* Complete Order Data

With Order Management, retailers have access to order information at all stages of the process, from where and how the order was generated to where and how it is being delivered. This gives retailers more control and visibility into each individual unit of merchandise from the moment of purchase to the moment of delivery.

### Learn About B2B Commerce

While Salesforce B2C Commerce focuses on online retail shoppers, there’s another whole area of ecommerce with its own demands and capabilities—B2B—business to business.

Salesforce B2B Commerce enables organizations to create ecommerce storefronts that are specifically designed for businesses making large volume purchases from other businesses online. B2B commerce customers need easy online access to suppliers so they can buy products to run their businesses.

 
## Salesforce B2C Commerce (Explore how B2C Commerce transforms the online shopping experience)

### B2C Commerce Shopping Experience

In this module, you’ll learn what ecommerce is and how B2C Commerce helps you delight the customers who buy your products online. After you earn this badge, you’ll better understand what your stakeholders—partners, admins, developers, and merchandisers—are talking about when they talk about B2C Commerce.

We build B2C Commerce storefront applications with the shopper in mind. We want shoppers to get what they want, return again and again, and tell their friends and family what a great experience they had. Providing an online shopping experience that’s fun, fast, and easy makes everyone happy.

#### The Shopper’s View

Let’s say you’re treating yourself to a tropical vacation next month. You’ve done a little surfing on other vacation trips, and you’re curious about riding the waves in a new location. Maybe you’ll discover when you get there that the waves are a tad out of your league. Maybe you’ll go to nice quiet reef instead and play with the tropical fish and the green sea turtles.

Whatever you do, you’re going to have a great time, and you need some fabulous gear!

You take a deep breath, log in to your smartphone or computer, and open a cool site called BeachCloud that sells beach products.

You click the Apparel tab, then the tile that says Bathing Suits. There are other tabs, such as Accessories, but you ignore those for now.

Like many B2C Commerce storefronts, the BeachCloud site organizes products by category, and each category has a tab. When you click a tab to see products in that category, you’re navigating the site.

You don't see what you want, so you enter stripd bathing suit into the search field. Woops, typo!

But then you see a page that asks if you really meant “striped bathing suit.” And there’s a link.

This is called searching.

You click the link and a pink striped bathing suit displays on the very first page. It’s just what you’re looking for.

You hover your mouse over the image and it zooms in, showing more details. You’re viewing product content.

You click a video link and see a model wearing the suit and moving so you can see it from different angles. The video is also content.

The suit looks just right. You select your size and click Buy.

Now you’re on a roll. You click the Accessories tab and see tiles for footwear, towels, and sunglasses. You click the Towels tile and select a big, thirsty-looking towel with bright stripes, then click Buy.

You spy a panel at the top of the page that says, “All Surfboards Half Off.”

This is a promotion with a fabulous discount.

It’s your lucky day. You click the panel to open a page showing a whole lot of surfboards. You pick one with red and pink stripes and click Buy.

You go back to your cart and view your new list, which now includes the flip-flops.

You didn't know it when you made your original choices, but the bathing suit comes with a free bag. There’s a link to choose the bag you want beneath the bathing suit line item. You click the link, pick the yellow bag, and click Choose. Your bag is now listed beneath the bathing suit in the cart.

Checkout is fast and easy.

You enter your name and address, click Same as Billing, enter your credit card information, and select a shipping method. Because you’re in no rush, BeachCloud waives the shipping fee. Your order looks great, and you have free shipping. You’re happy. You click Place Order.

You’re back at the front page and you spy a pair of goggles. It’s too late to add to your order now, but maybe you’ll add the goggles to your wish list. You wonder if you should create a BeachCloud account so you get more cool deals that help you save up for your next vacation.

People who create accounts at an ecommerce site can log in whenever they shop there. Logged-in shoppers have special privileges like wish lists and saved payment information that save them time and make them feel special.

Now, all you have to do is start packing for your trip.

### B2C Commerce Features

Lots of retail companies sell their products online—in fact most do. But finding the right tools and services to make ecommerce dreams come true can be daunting. That’s where B2C Commerce comes in. What is B2C Commerce, and how can you relate it to what you already know about online shopping?

![Photo](./photo4.png)

B2C Commerce is a set of tools, services, and processes that you use to configure ecommerce sites. Whether your customers are browsing on their desktop or a mobile device, we’ve got you covered. It’s about product details that help shoppers make decisions, targeted discounts, speedy checkout, and underlying tools that track behavior and data. Lots of features come standard, and the B2C Commerce open development environment lets you customize or extend it further.

In B2C Commerce, a site is the application and associated code that runs a storefront, where shoppers go to buy things online. You can sell your products internationally if you want, because B2C Commerce data and storefronts are localizable. B2C Commerce supports both language- and country-specific locales.

If you create or maintain B2C Commerce sites, you’re probably a merchandiser, administrator, or developer. Merchandisers create marketing campaigns and work with site data such as product details, images, and search. Administrators configure sites and make sure they run properly. Developers develop the sites. This module is designed mainly for merchandisers, but if you’re an admin or a developer, you’ll find information here that’s helpful for you, too.

Let’s start by learning about the B2C Commerce standard features: search, navigation, product, content, discounts, logged-in users, and checkout. You configure these features in Business Manager, an online B2C Commerce tool for anyone who creates and maintains B2C Commerce sites.

![Photo](./photo5.png)

#### How Shoppers Find Your Stuff and Navigate Your Storefront

Good ecommerce search and navigation help shoppers find what they want fast. You want shoppers to find what they’re looking for, buy it, and keep coming back.

Here are some key terms you should know.

* Keyword Search—The shopper types a word in the search field.
* Search Suggestion (aka search-as-you-type)—After the shopper types the first few letters of a word, B2C Commerce displays a list of clickable suggestions.
* Search Results—The site displays clickable product tiles or a list of products that fit the search criteria.
* Navigation—The shopper clicks tabs or breadcrumbs to get closer to the products they want.
* Storefront Sorting—The shopper selects from a menu to change which products appear first in the search results.
* Search Refinement—The shopper selects price range, color, and size to narrow the search.
* No Results Found—This page opens when there are no results.

![Photo](./photo6.png)

#### How You Showcase Your Products

While search is where a shopper types text into a search field to find something, navigation is when they click on category tabs or select subcategories to navigate the site. In the BeachCloud storefront we talked about in the previous unit, our imaginary shopper clicked the Accessories (category) tab and then the Footwear (sub-category) tile.

![Photo](./photo7.png)

B2C Commerce organizes sites using categories. A catalog is a container for categories, and a category is a container for products. Each product is identified by an SKU or part number. Other information about the product includes size, color, specifications, brand, price, graphics, and videos. Videos are typically supported outside B2C Commerce, such as with a content delivery network (CDN).

You can configure products as masters and variants. For example, each variant of the master product can specify a unique size and color, with corresponding graphics.

![Photo](./photo8.png)

Product sets are where your shoppers can buy a group (set) of products or individual products in the set. For example, they can order a wardrobe—pants, shirt, and hat—all together or separately. Product bundles are multiple products that are orderable only as a unit, such as a gaming bundle that includes a video game console and several games.

#### How Shoppers Compare Your Products

After searching for an item, shoppers see a search results page where they can click a tile or an item in a list.

![Photo](./photo9.png)

To make it easy for shoppers to compare products, the product details are consistent. Graphics and video are in the same place, the list of product information has the same format and information types, and pictures display in standard sizes. Consistency improves your shoppers' experience because they can focus on the differences between products, not the difference between page elements.

#### How You Give Shoppers a Discount

Getting a discount feels awesome! You use Business Manager to create all kinds of discounts for your customers. Start by creating qualifiers, then promotions, and then campaigns.

A qualifier is a condition that shoppers must meet to be eligible for a discount. These are qualifiers.

* Coupons support direct marketing efforts. You can create single-use coupons and coupons that shoppers can use more than once.
* Customer groups can be a list of specific customers or customers that meet certain criteria such as age and geographic location.
* Source codes are available via a link on an affiliate website. Shoppers search on one site, click a link, and are directed to another site. A qualifier code in the cookie provides the discount at the second site.

In Business Manager, you can create three types of promotions.

* Product—Give shoppers a free or discounted product.
* Order—Give shoppers a discount on their order.
* Shipping—Give shoppers a discount or an upgrade on shipping.

A B2C Commerce campaign contains one or more experiences that shoppers have in your storefront. In this module, we focus on the promotion experience. You can create a spring campaign, for example, that offers 10% off on pants, 20% off orders over a specified amount, and free shipping. You configure each discount in a promotion, then configure each promotion as an experience within a campaign.

#### How You Reward Logged-In Users

Shoppers who create an account on your ecommerce site and log in when they shop are loyal buyers. You can reward their loyalty by giving them special discounts or providing services such as wish lists, gift registries, detailed order history, and delivery tracking. You can also store credit card data and addresses so logged-in shoppers can check out and pay faster.

#### How Your Shoppers Check Out

After shoppers select the items they want to buy, they check out and pay for their purchases. This process should be easy and fast.

![Photo](./photo10.png)

Helping your shoppers check out fast means collecting key information from them as painlessly as possible. B2C Commerce lets you do that by minimizing the number of pages in your checkout flow and the number of buttons or links a shopper has to click—anything that can detract from the buying experience and prevent a sale.

#### Third Party Integrations

B2C Commerce comes with all the standard features we’ve looked at so far in this module. Through the Salesforce B2C Commerce LINK Technology Program, B2C Commerce also integrates with third-party applications that handle processes such as tax calculation, shipping carriers, and payment providers.

## Salesforce B2C Commerce for Merchandisers ( Configure product listings, make them easy to find, and give shoppers discounts they love. )

### B2C Commerce Product Data

In this unit, we discuss how catalogs, categories, products, content, and libraries work in your organization’s B2C Commerce storefront.

A quick word about organizations, sites, and storefronts. Your organization contains your sites, and each of your sites can contain one or more storefronts. Your organization can have:

* One site with one storefront
* One site with multiple storefronts
* Multiple sites and multiple storefronts

#### Catalogs

A catalog is a collection of categories, products, and images. Your company can have one or many catalogs. You can only assign one catalog—the storefront catalog—to your site.

![catalog](./photo11.png)

When we talk about sites in B2C Commerce, we mean the application and associated code and configurations that represent one or more storefront URLs. Storefront is the term we use for a B2C Commerce website, but we also use the term to describe any online ecommerce experience, such as a native application on a mobile device. A storefront is the place shoppers go to buy stuff!

In the storefront catalog, the category structure you create determines storefront navigation: the categories that group products, the products available in each category, and the product attributes displayed to the shopper.

Product attributes are the information types you define for each product. For example, product attributes for shoes include size, color, heel height, width, and brand. When you define attributes for the Shoes category, all products in that category have those attributes.

If you want to manage your products in a catalog with the same structure as an external system or system of record, you create a standard catalog, which you don’t assign to a site. A standard catalog owns the products (that means you edit products in the standard catalog) and mirrors the organization of your inventory, fulfillment, or product management systems.

![catalog](./photo12.png)

Catalog A is the standard catalog, while Catalog B is the storefront catalog. They both contain the same product IDs, but they have different categories. Catalog A categories are from the system of record. Catalog B categories display on the storefront.

You don’t have to create your data in Business Manager. You can import data such as product details, inventory, prices, content, images, and video from another system.

#### Categories

Categories define the catalog structure. We call the top-level category in a catalog the root category, though it doesn’t actually have a name. All the categories you create are a child of the root category.

#### Products

A product is owned by one catalog. You can only edit the product in the catalog that owns it. However, you can include the product in any combination of catalogs and categories in your sites. When you edit a product in the catalog that owns it, your edits are reflected automatically in the other catalogs the product are included in.

To display in a storefront, a product must be:

* Assigned to a storefront category
* Searchable
* Online
* Available

You use Business Manager to configure these settings. The Online setting means the product can display on the site.

In Business Manager, you can create the following types of products.

* Standard — A product that you sell and display by itself. They don’t have variations, such as different sizes or colors.
* Master — A representation of all the variations of a product. For example, the Cloud Kicks shoe company makes a shoe called the Mesospheric that comes in several sizes and colors. Mesospheric is a variation master. Your shoppers can’t buy it directly.
* Variation Group—A group of products that share an attribute, such as color or size. The variation group belongs to a master product. For example, the Mesopheric shoe comes in several colors and sizes. All sizes of Mesopheric shoes that come in blue are a variation group.
* Variation — A specific variation of a master product. For example, if the Mesospheric is the variation master, then a variation product is a pair of size 10, blue Mesospheric shoes.
* Set — Multiple products that you display together, which shoppers can buy either together or separately. For example, an accessories kit that includes a hairbrush, comb, and mirror is a product set if shoppers can also buy the individual products separately.
* Bundle—Multiple products that you sell only as a group. For example, a gaming bundle that includes a video game console and several games is a product bundle if shoppers can’t buy the console or games separately.
* Option — Optional accessories, upgrades, or the like that come with a product, yet have a separate price and display name, and no thumbnail image. They are not separately orderable or searchable. An example is warranties for different time periods.

#### Inventory

B2C Commerce provides built-in inventory capability that you can use with your storefront via inventory lists. They list product IDs that map to inventory details such as allocation amounts, preorder and backorder handling, and in-stock dates.

The inventory list you assign to a site represents the online inventory of that site. You can assign an inventory list to one or more sites, but a site can only have one inventory list. You can assign an inventory list to multiple sites to share product availability data.

B2C Commerce isn’t the system of record for inventory data. Its job is to track inventory levels and integrate with back-end inventory systems in near real time. This means that shoppers see availability info that’s based on current stock-level information. Product availability automatically adjusts as shoppers place orders.

#### Price Books

You define B2C Commerce storefront product prices in price books, which contain the price details for products based on a currency. You define prices for varying quantities of a product in a price table. You can create multiple price tables for each product, but you can only activate one price table at a time. For example, in one price table, a box of soap sells for US$12.00. In another price table, a box of the same soap sells for US$11.00, and two to three boxes each sell for US$10.00.

Though you define price books for your entire organization rather than for a specific storefront site, you can assign a price book to one or more storefronts in the organization.

You have to assign a price book to a site before you can use it in the storefront. You can assign one or more price books to a storefront, and multiple price books can be active at a time.

#### Content Assets

In your B2C Commerce storefront, your content helps you sell products and inform shoppers. B2C Commerce supports a wide variety of content assets, including HTML text, graphics, and video, serving shoppers content such as customer support pages, special sales, size charts, gardening tips, or videos of models walking in boots. You can create new text content in Business Manager and import other content from another source. You store your content assets in libraries and folders for quick access.

You can use Business Manager or external systems to manage all or some of your content. We support a B2C Commerce managed or an external content delivery network (CDN), for example, for super-fast performance.

In Business Manager, you can create a matrix of images associated with products. You can specify images by color, fabric, and size range, with large, medium, and small images, and color swatches for product color selection. Though you can manage images and text in B2C Commerce, you must add video through a third-party application.

In B2C Commerce, content assets are organized in libraries. You can use the private library that was created when the site was created, or libraries that are shared by multiple sites.

### B2C Commerce Search

Online shoppers want to find stuff fast! Salesforce B2C Commerce comes with lots of search capabilities to help your shoppers find the things they’re looking for. In this unit, we cover search redirects, the search index, searchable attributes, and search configuration settings in Business Manager. We also look at the B2C Commerce search engine optimization (SEO) capabilities, for when the search comes from a search engine like Google.

#### Search Features

##### Type-Ahead Search

B2C Commerce starts processing a storefront search as soon as shoppers type a few characters into the search field. As they type, B2C Commerce is already checking for things like spelling and word completion. It also gives suggestions, such as a category.

Keyword search field, search suggestions, and sorting search results


##### Search Redirects

After the shopper enters a search term, B2C Commerce can process a search redirect. In a search redirect, a predefined term, like wedding dress, sends the shopper to a specific page or URL instead of to a search results page. The Wedding Dress page (or site) might have a unique look and feel, special content, access to a bridal registry, wedding guide information, and pricing. By going directly to the site, the shopper’s enhanced buying experience increases the likelihood that they buy something.

#### Search Index

B2C Commerce passes the information that the shopper types to the search index. The search index is a collection of data about the site’s products and content that shoppers can search for. And this is key! Data isn’t searchable by default. You have to configure product and content data as searchable in Business Manager.

You configure product details and attributes—data such as brand, ID, name, and description—as searchable. For example, when you include product names and descriptions in your search index, and a shopper enters beaded wedding dress in the search field, the search results page displays any product names and descriptions that include the phrase beaded wedding dress, or any combination of the three words, depending on your configuration.

Don’t go overboard when you mark data as searchable. The more data you configure as searchable, the bigger the index, and the slower the search speed.

The B2C Commerce search index combines several indexes that handle spelling, content, synonyms, suggestions, and product availability. In Business Manager, you can define all kinds of information.

* Synonyms—Terms that mean the same thing.
* Hypernyms—Term for a group of products. For example, the term top is a hypernym that contains the hyponyms tunic, shirt, and blouse. When a shopper searches for top, B2C Commerce returns products that contain top, tunic, shirt, and blouse.
* Hyponyms—Term for an item in the group of products that a hypernym describes. For example, blouse is a hyponym of the hypernym top. When the shopper searches for blouse, B2C Commerce only returns products that contain blouse.

Let’s look at an example of synonyms. Suppose you configure a synonym list for the terms bag, purse, pocketbook, and tote. When shoppers search for bag, B2C Commerce looks for bag OR purse OR pocketbook OR tote, and returns:

* bag and bags
* purse and purses
* pocketbook and pocketbooks
* tote and totes
* White purse

The search index derives search terms from these types of product data.

* Stop words—Define words that the search engine ignores, such as an or the.
* Compound words—Define words that the search engine splits into separate terms. For example, if you configure foot-* as a compound word, a search for footstool returns results for foot and stool.
* Common phrases—Define word combinations that the search engine finds as a unit, such as pencil case.
* Word stems—Define the common root of one or more words. For example, boot is the stem of boots and booties.
* Special characters—Configure the search engine to remove these special characters: ! ( ) : [ ] { } + ~ ^ ? ' .
* Product numbers—Configure the search engine to split product IDs into their parts. For example, a product ID shirt-1234 can be split into shirt and 1234.
* Short terms—Specify short words (fewer than three characters) that the search engine evaluates. Search suggestions and the Did You Mean features ignore short terms unless you specify them.

You want site data that's as fresh as possible, but rebuilding the index after every update isn't always practical. Indexing everything can take hours, depending on the amount of data and the complexity of the search configuration.

There are other ways, however, to keep the search index up to date. Turn on Incremental Indexing to update the index whenever someone changes search configurations or product details in Business Manager.

#### Einstein Search Dictionaries

Einstein Search Dictionaries uses artificial intelligence to make your site search even smarter, by collecting data from all site searches and settings to find search terms that aren’t in your dictionaries. Then it detects relationships between search terms and recommends which synonym lists to assign terms to.

#### Search Preference Settings

Business Manager search preferences give you tons of control over storefront search. Use preferences to hide products that aren’t available or move those with limited availability to the bottom of search results.

#### SEO
If you can get the attention of external search engines like Google, you can drive sales. Optimize your site for search engines with a few basic settings in Business Manager.

* Get more search engine attention—Streamline URLs and eliminate irrelevant keywords, multiple directory layers, and parameters. Dynamically create HTML page metatags and heading tags, embedded information to get hits.
* Focus attention on the sites to be searched—Configure robot.txt files, which web crawlers and other web robots check to see if site indexing is allowed.
* Don’t miss a sale—Configure hostname aliases for alternate URL names.
* Retain loyal shoppers—Send shoppers from an old URL to a new one via URL redirects.
* Populate search engine indexes—Configure sitemaps with website contents for crawler consumption and indexing. Sitemaps are XML files that provide search engines with information like a list of available URLs, when a page was last updated, frequency of updates, and page relevance. Search engines use this information to construct links to the site and control the ranking of links within search results.
* Avoid dead-ends—Configure alternative paths to avoid 404s, or file not found errors.
* Preserve search rankings for pages that seem like duplicates—Configure within your page headers which of multiple similar URLs is the preferred or canonical one.

#### After the Search

After the search results display, shoppers sometimes need more guidance. For example, you can help them sort or refine their results. You can also sort results to highlight top sellers or showcase your latest products. You can also let shoppers customize search results by sales, product availability, or personalized details.

You can use Business Manager to configure B2C Commerce sorting rules to change the order of search results, or to let your shoppers change the order themselves. Shoppers direct their own sorting through storefront sorting options. The options appear in a dropdown list on a search results page. Shoppers click an option such as Low to High to sort by price.

### B2C Commerce Campaigns and Promotions

Everyone loves getting a discount. With Business Manager, you can create serious discounts that drive sales and make shoppers happy.

In Business Manager, you configure discounts as promotions, and group multiple promotions into campaigns. For example, create a campaign to push new spring apparel, such as flowered dresses, lightweight pants, and raincoats. Here are some of the promotions you offer.

* Free shipping to shoppers who spend more than a certain amount on selected apparel.
* Buy one, get one free for all flowered dresses via an emailed coupon.
* Buy one pair of khaki pants and get 50% off on the next pair.
* Buy three raincoats and get 20% off the entire order.

#### Campaigns

A campaign is a collection of scheduled experiences that your shoppers can have in your storefront. You can create three types of experiences within a campaign.

* Promotion—Promotions are discounts. We talk more about them in a minute.
* Slot configuration—Slots are specific places in a storefront that display content and perform some action. For example, a banner shows a child wearing a red hat and text that says, “50% off on all kids’ hats.” When the shopper clicks the banner, the search results show a list of children’s hats.
* Sorting rule—We introduced sorting rules in the previous unit. Sorting rules let you or your shoppers reorder the search results in a certain way, by lowest price first, for example.

You can schedule campaigns with specific start and end dates, or you can run them continually. Enable or disable campaigns with one setting. You can give promotions the same schedule as the campaign or an independent schedule within the campaign period. For example, you can schedule a series of promotions that kick off one after the other during your campaign.

You control promotions by assigning qualifiers and rank. Qualifiers determine who gets a discount, while rank controls precedence when multiple promotions apply at the same time. We talk more about how to control promotions later.

#### Promotions

In B2C Commerce, you create a promotion to define the rules that govern your discount. You ask three basic questions.

1. What is the promotion class?
2. What is the discount type?
3. What is the discount?

##### Promotion Classes

There are three promotion classes.

* Product—discounted individual products
* Order—discount on the entire order
* Shipping—discounted shipping costs

##### Discount Types

Product promotions are the most complex, offering a matrix of discount type choices. These are the product promotion discount types in Business Manager.

When you set up order promotion rules, you specify an amount the shopper must spend or the number or combination of products the shopper must buy to qualify for a discount. You can configure order promotion rules for percent off, amount off, bonus products, or choice of bonus products (list or rule) discounts.

You base shipping promotion rules on the order or on individual products or product combinations within the order. You can give qualifying shoppers free or discounted shipping costs.

##### Discounts

Available discounts vary by discount type. Here’s a list of discounts you can give.

* Percent off
* Amount off
* Fixed price
* Price from a certain price book
* Percent off product options
* Bonus products
* Choice of bonus products
* Fixed price shipping
* Free shipping

##### Qualifiers

You create qualifiers to control which customers get a discount. In B2C Commerce, qualifiers are coupons, customer groups, and source codes.

* Coupons	A coupon entitles the holder to a discount. In B2C Commerce, you configure coupons for a single use or multiple uses. You can create a multiuse coupon that’s good “while supplies last.” You can also create system-generated coupons that create coupon codes for you.

* Customer Groups	Create discounts that are available to all customers who belong to a particular group. B2C Commerce comes standard with three predefined customer groups: Everyone, Registered customers, and Unregistered customers. You can create new groups to meet your own requirements, such as a list of customers or a group based on visit data, order value, or address.

* Source Codes	Use a source code to direct customers to a specialized landing page, featured product detail page, category list, or other URL. You can provide a source code to shoppers in your print catalog; shoppers manually enter the code in your storefront. Or provide the code via a redirect link on an affiliate website.

##### Other Ways to Control Promotions


You don’t want give products away by applying multiple discounts when shoppers qualify for them. With B2C Commerce, you control which discounts apply, in what order, and how many times. You can exclude certain products from discounts or offer volume discounts.

###### Tiered Discounts
You can tier discounts so that the discount amount increases as the shopper buys more products or spends more money

###### Rank and Exclusivity
If a shopper qualifies for multiple discounts, you can use the rank and exclusivity attributes to limit which discounts apply. Setting these attributes prevents stacking, or the excessive application of multiple discounts. Rank is a number you can assign—the smaller the number, the higher the rank. Discounts with a higher rank apply before lower-ranked discounts.

You can set the exclusivity of discounts to NO, CLASS, or GLOBAL. Setting exclusivity to NO allows for combining discounts, CLASS disallows combining discounts in the same class, and GLOBAL prevents all combining. If the shopper qualifies for a global exclusive promotion, for example, no other promotions apply.

Say there’s a 10% product promotion for everyone, and a special 20% product promotion for registered customers. Registered customers should only get the 20% discount. Right? Maybe so. But you might want multiple promotions applied to an order. A shopper gets a 10% discount on a winter coat, free shipping because the order’s over a set amount, and a free scarf to go with the coat in the same order.

You can exclude a product from specific promotions or exclude it from all promotions (to prevent discounts on low-margin products, for example).

You can define both the qualifying products—which products a shopper must buy and in what quantity to be eligible for a discount—and the discounted products—which products are eligible for the discount.

###### What Happens When?
If a shopper qualifies for multiple promotions in a cart, B2C Commerce applies them in a well-defined order to prevent double dipping or unpredictable results. For example, product promotions are applied before order promotions, because order promotions depend on the resulting total after the product discounts.

This is the order that B2C Commerce applies discounts:

* Class—The promotion types in the sequence of product, order, and shipping.
* Exclusivity Type—Whether promotions are mutually exclusive, in general or relative to a promotion's class.
* Rank—Which promotions take precedence (with 10 = highest and 100 = lowest).
* Discount Type and Value—Discounts in order (for example, Fixed Price, Total Fixed Price, and Free).
* Maximum Application—Limits the times a discount can apply in an order. (Only certain discounts have this capability.)

## B2C Commerce Campaigns and Promotions (Plan and configure campaigns and promotions for your B2C Commerce storefront)

### Explore Campaigns and Experience Types

#### What’s a B2C Commerce Campaign?

A B2C Commerce campaign contains scheduled experiences that are targeted at a specific set of shoppers. Experiences can be promotions, content slots, sorting rules, and keyword search sorting rules (you’ll learn more about each of these shortly). Shoppers must qualify for an experience. Experiences must run within the campaign’s overall schedule.

#### Experience Types
Campaigns can contain multiple experiences. When Brandon ties multiple promotion experiences to one campaign, he gets a single view of all the experiences running at any given time.


![GitHub Logo](/photo13.png)

#### Content Slots

A content slot is a preconfigured location on the storefront where you can showcase products, categories, content assets, static HTML, or product recommendations. A content asset can be a flash graphic, product carousel, or marketing graphic. This is where he makes his products shine.

For instance, you want to show exciting new content about the spring sports apparel on the homepage banner content slot and on category landing page banner content slots.

#### Sorting Rules and Keyword Search Sorting Rules

Sorting rules let you control the order in which products display on the storefront after a search or when viewing a category listing page.

You can bring certain products to the shopper’s attention by having them appear at the top, for example. You can configure a sorting rule or a keyword search sorting rule. The sorting rule experience requires a category, while the keyword search experience does not use categories. An experience can only have one keyword search sorting rule.

You can sort the search results with a single attribute or a weighted blend of multiple attributes.

#### Promotions
A B2C Commerce promotion is a set of rules that define how and when a shopper gets a discount, and the details of that discount. Here are the three promotion types (or classes): product promotion (1), order promotion (2), and shipping promotion (3).

![GitHub Logo](/photo13.png)

#### What's a Qualifier?

Qualifiers trigger a promotion and can be coupons, customer groups, or source codes.

Shoppers can get a coupon code in an email, for example, or they can be part of a customer group based on their demographics or membership, or they can receive a discount because they navigated from an affiliate group such as Google. A source code embedded in a cookie triggers the discount.

![GitHub Logo](/photo14.png)

You can set multiple qualifiers for a promotion. For example, Brandon wants to offer 20% off Brand-X SuperSpeed running shoes. To qualify, the shopper must be a Loyalty Program member and enter a coupon code that they received in an email.

#### Build the Playbook
Yours campaign is more than a configuration. It’s a complete program that you design and implement. You must consider graphics, timelines, products, categories, marketing sources, and storefront page locations. And where exactly do you place your campaign assets?

You create a playbook. Here’s an example of the campaign so far.

![GitHub Logo](/photo15.png)
![GitHub Logo](/photo16.png)
![GitHub Logo](/photo17.png)

#### What's the Process?
YOu start by creating the campaign. But then you have to stop and create the qualifiers, and then stop again to create the promotions.

Because you’re already planned a detailed approach, here’s a more efficient way.

* Create the qualifiers.
* Create the experiences.
* Create the campaign.


### Create Qualifiers

Brandon Wilson, the Cloud Kicks merchandiser, wants to offer exciting promotions in his Spring campaign. He wants to target Loyalty Program members and shoppers who haven’t purchased for a while. It’s great that he’s identified his audience. Now he must figure out how they can qualify for discounts.

That’s where qualifiers come in. As a reminder, these are the qualifier types.

* Coupons: Multiple or single-use codes that shoppers can use to get a discount.
* Customer groups: A list of specific customers or customers who meet criteria such as geographic location.
* Source codes: A code on a browser cookie that results from the shopper clicking a link on an affiliate website. They automatically navigate to the storefront.
Brandon wants to configure multiple qualifiers for some of his promotion experiences. He does that using qualifier settings for each promotion experience within a campaign. He configures campaigns in a later unit.

Let’s follow along with Brandon as he learns how to configure his qualifiers.

* Merchant-defined single code coupon
* Static customer group
* Dynamic customer group
* Source code

#### Coupons

Brandon can create coupons in Salesforce B2C Commerce or import them from an external system. They can also exist outside of a campaign or a promotion. When you configure a coupon as a promotion qualifier, when the promotion expires, the coupon expires, too.

You can assign a coupon to one or more promotions and associate an individual promotion with multiple coupons. When you associate a coupon with a campaign, all promotions in that campaign automatically inherit the coupon. You can also disinherit a coupon within a promotion.

##### Coupon Types

Here are the types of coupons you can create in Business Manager.

![GitHub Logo](/photo18.png)

Brandon uses the redemption limit to limit how many times each shopper can use the coupon in a transaction.

##### Create Coupons

In this module, we assume that you are a B2C Commerce merchandiser with the proper permissions to perform these tasks. If you’re not a B2C Commerce merchandiser, that’s OK. Read along to learn how your merchandiser would take these steps in Business Manager. 

Brandon starts with a merchant-defined single code coupon. Here’s what he does.

![GitHub Logo](/photo19.png)

Brandon can assign the coupon to a campaign in the Coupon module. But remember, he wants to create all the qualifiers and promotions first, and then add them to the campaign.

#### Customer Groups

Brandon uses customer groups to show content slots, promotions, and sorting rules to specific customers, providing them with an awesome experience.

##### Customer Group Types

Here are the types of customer groups he can configure.

* System: Pre-existing groups already available in Business Manager. They are Everyone, Registered, and Unregistered. You cannot change them.
* Static: Add shoppers to the group manually one by one, or upload a list of shoppers from your customer relationship management (CRM) system.
* Dynamic: Create a membership rule to place customers in a particular group. The rules are based on customer data attributes, for example, a customer’s birthday in 30 days.

He wants to configure these customer groups.

* Static: Logged-in Loyalty Program member
* Dynamic: Lapsed shoppers.

Lapsed shoppers have created a profile but haven't shopped for a while.

##### Create Customer Groups

Here’s how he creates the Loyalty Program customer group.

![GitHub Logo](/photo20.png)

Here’s how he creates the lapsed-shoppers customer group.

![GitHub Logo](/photo21.png)

#### Source Codes

When shoppers type coupon codes in a storefront to qualify for a promotion, the source codes can trigger different actions behind the scenes. They can:

* Direct customers to specialized landing pages, featured product detail pages, category lists, and URLs.
* Redirect them to other sites.
* Activate price books.
* Enable promotions.

What makes source codes special is that they can do different things. A source code can activate a price book, or you can use one as a qualifier in a campaign to activate promotions, sorting rules, or content slots.

Brandon wants to use a source code to activate a promotion when a shopper clicks a newsletter email. From a link in the email, the shopper navigates to the Cloud Kicks storefront, which stores the source code in a cookie on the shopper’s machine. Lucky them—they get free shipping on orders over $100.

Brandon learns that he can create a source code group to contain one or more literal codes or patterns that match multiple codes. He uses SPORT[1..10] as the code, which means that shoppers can enter SPORT1 but not sport1.

He can map multiple codes to the same set of rules (price books, promotions, and redirects). He does this by defining them as part of a source code group, while still tracking results on a per source code basis. He can assign one or more source codes to a campaign, so that all the promotions within that campaign use those source codes.

Here’s how he creates a source code.

![GitHub Logo](/photo22.png)

### Discount Types and Promotion Controls

Brandon Wilson, the Cloud Kicks merchandiser, has his qualifiers and now wants to create promotions. But before he begins, he wants to learn more about what Salesforce B2C Commerce promotions are and how they work.

B2C Commerce promotions specify discounts or offers. They run within a campaign or an A/B test. A/B test is a B2C Commerce feature that lets you test multiple experiences against each other to see how shoppers respond.

Promotion configurations contain rules that define the promotion type, conditions, and discounts. You can extend a promotion with custom attributes to meet specific business requirements. Promotions can be time-sensitive and targeted at specific customer groups. They can be perpetual, such as offering free shipping to build shopper loyalty. You can assign the same promotion to multiple campaigns.

For example, Brandon wants to offer 20% off Brand-X SuperSpeed running shoes to Loyalty Program members. Shoppers qualify for this discount by entering a coupon code after they log in to the storefront.

For each promotion Brandon wants to create, he asks himself:

* Who gets the deal? (Loyalty Program members)
* What’s the discount? (20% off)
* How do shoppers get the deal? (Buy Brand-X SuperSpeed running shoes)
* Are there exclusions? (No)

He needs to answer these questions for all his promotions. He already answered the first question by creating qualifiers in the previous unit. Let’s move on to explore discount types and the many ways he can control how shoppers get the deals.


#### Discount Types

Each of the three promotion types is further defined by discount type and available discounts.

Here’s a sampling of them.

![GitHub Logo](/photo23.png)

Here are the promotions he wants to create.

![GitHub Logo](/photo24.png)

Before Brandon creates the promotions, he wants to learn more about how to control them.

#### Control Those Promotions

Brandon wants to offer great discounts, but within reason. He doesn’t want a shopper to qualify for multiple discounts and get products for free. Even double-dipping is not OK. That’s when a shopper gets a double discount.

Here are the ways he can control who gets a discount.

![GitHub Logo](/photo25.png)

##### Tiered Discounts 

With tiered discounts, the discount amount increases as the shopper buys more products or spends more money. For example, a shopper gets 10% off a $50 purchase of Brand-X apparel, 15% on $100, and 20% on $150 or more. They must buy a certain brand and spend a certain amount to qualify. The more they spend, the bigger the discount.

##### Compatibility Rules

Compatibility rules let you configure which discounts apply and in what order, so that all promotions for which a shopper is eligible are not automatically applied. Exclusivity and rank settings let you do this.

With the exclusivity setting, Brandon can define if promotion types are mutually exclusive or relative to another promotion type. Here are the settings.

* NO	Can be combined with any promotion (default).
* CLASS	Cannot be combined with a promotion of the same class.
* GLOBAL	Cannot be combined with any promotion.

For example, if all shoppers get 10% off and registered shoppers get 20% off, the registered shoppers should only get a 20% discount. Brandon might, however, want shoppers to get a 10% product discount, free shipping based on the order value, and a free bonus product in the same order. In this case, exclusivity should be set to Cannot be combined with a promotion of the same class.

The rank setting lets Brandon decide which promotions come first (10 is highest and 100 is lowest, for example). Promotions are applied in the order of their rank (highest rank first).

##### Maximum Application

You can control how many times a shopper can use a specific promotion in a single order. For example, Brandon wants to offer a bonus baseball with a purchase of a pair of Brand-X baseball shoes. He can limit the number of baseballs that a shopper receives in an order, regardless of how many pairs of shoes they buy in that order.

##### Globally Excluded Products

You can exclude certain products from a promotion within each promotion individually. You can also exclude specific products from all promotions globally. Brandon can prevent discounts on low margin products, for example, without having to configure a setting for each promotion.

##### Qualifying and Discounted Products

You can configure a specific set of products that qualify for a promotion and the same or a different set of products that qualify for a discount. For example, Brandon is considering this discount.

Buy a buy Brand-Y T-shirt and get half off the matching shorts.

A shopper qualifies for the promotion by buying the T-shirt, while the shorts are discounted.

Brandon wants to understand how discounts are prioritized when a shopper qualifies for more than one of them at checkout. If only one discount can apply, how does B2C Commerce figure out which one it is?

B2C Commerce uses priority rules to determine this. You can customize some of the rules, such as exclusivity and rank, but most of them are fixed. For example, B2C Commerce processes product, order, and shipping promotions in an exact order based on cart calculations. Here are the steps B2C Commerce takes to process discounts by class.

* Calculate product promotions.
* Calculate order promotions on the basis of the merchandise total.
* Prorate order-level discounts across all products within the order.
* Calculate shipping promotions.

Promotion class is only one of the many promotion calculations. When multiple promotions apply, B2C Commerce processes promotions in this order.

1. External API-generated promotions
2. Class (product, order, shipping)
3. Exclusivity (customizable )
4. Rank (customizable)
5. Discount type and value (Promotions that provide the best value to the shoppers are evaluated first.)
  a. Fixed price
  b. Total fixed price
  c. Free
  d. Price book price
  e. Amount-off
  f. Percent-off
  g. Bonus-product
  h. Choice of bonus products
  i. Free product-shipping
  j. Fixed price product-shipping
6. Maximum application

Promotion processing is complex, but it happens fast. As shoppers add items to the cart, the numbers change in a flash.

### Create Promotions

Brandon Wilson is ready to create promotions for his Spring sports campaign. With so many options available in Salesforce B2C Commerce, right now he just wants to focus on promotions that meet his immediate needs. Later, he can explore other possibilities, building on the experience he gains here.

Brandon has a lot of confidence in his plan. Here’s what he has in mind.

![GitHub Logo](/photo26.png)

#### Product Promotions

Here are the product promotions he wants to create.

* 20% off Brand-X SuperSpeed running shoes
* Free baseball with a pair of baseball shoes
* Buy one, get one half off Brand-Y Xcel athletic shorts and t-shirts

He assigns the CLASS exclusivity setting to all of them, because he doesn’t want shoppers to get more than one discount. The CLASS exclusivity means that a shopper can’t use a promotion with another promotion in the same class.

Brandon selects qualifying and discounted products carefully. For example, he doesn’t select master products because they are not orderable. They don’t have a stock keeping unit (SKU). He can select from these product types.

* Standard product
* Variation product
* Product set
* Product bundle

##### Create Promotion: 20% Off Brand-X SuperSpeed Running Shoes

![GitHub Logo](/photo27.png)
![GitHub Logo](/photo28.png)

##### Create Promotion: Free Baseball with a Pair of Baseball Shoes

![GitHub Logo](/photo29.png)

##### Create Promotion: Buy One Get One Half Off Brand-Y Xcel Athletic Shorts and T-Shirts

![GitHub Logo](/photo30.png)
![GitHub Logo](/photo31.png)

#### Order Promotions

Brandon wants to offer an order promotion where orders over $50 get 15% off. He also wants to alert the shopper when their order value approaches this discount by $10. He first works with a developer to add code for the alert on approaching functionality. His developer refers to documentation in the Infocenter. Once the developer has completed the code, Brandon takes these steps.

![GitHub Logo](/photo32.png)

#### Shipping Promotions

Brandon wants to create a promotion with free shipping on orders over $100. He also wants to alert the shopper when their order value approaches this discount by $10. He first works with a developer to add code for the alert on approaching functionality. His developer refers to documentation in the Infocenter. Once the developer has completed the code, Brandon takes these steps.

![GitHub Logo](/photo33.png)

### Create Campaigns

Brandon Wilson is ready to build his Spring campaign with the qualifiers and promotions he just created.

randon learns that a campaign start date and time and end date and time are optional. If there’s no start date, Salesforce B2C Commerce enables the campaign immediately. If there’s no end date, the campaign runs indefinitely. He wants to run his Spring campaign from January 15 to April 15.

And now he’s ready to create it!

##### Create a Campaign with Qualifiers and Promotions

Brandon is thrilled with his company’s fabulous new products and wants lots of people to wear them this spring.

Here’s how he creates his campaign.

![GitHub Logo](/photo34.png)
![GitHub Logo](/photo35.png)
![GitHub Logo](/photo36.png)
![GitHub Logo](/photo37.png)

## Salesforce B2C Commerce for Developers (Learn about the B2C Commerce developer tools you can use to create storefront application projects)

### Commerce Cloud Business Manager

  Business Manager is the Salesforce B2C Commerce online tool for configuring and managing B2C Commerce storefronts. This important tool is the command center for your B2C Commerce merchandising, administration, and site development capabilities. To use Business Manager, you must have access to a B2C Commerce instance. 

#### Get Started with the Business Manager User Interface

  When you open Business Manager, you must first select a site. You can have a few sites or many, depending on the size of your company and how many sites you support. Once you select a site, you can access the data, code, and permissions that are configured for it
  In B2C Commerce, a site and its associated code combine to create a storefront. A storefront is the user's online experience. A site can have multiple storefronts. (When referring to a merchant's website, we use the term storefront.)
  
  Click Storefront to open the site you’ve selected in another window. The site shown here is a sample site that demonstrates the architecture of B2C Commerce.
  
  ![GitHub Logo](/photo38.png)
  
  Typically, you want to see your own site.

  You might also see icons for the Storefront Toolkit, a development tool that helps developers troubleshoot.
  
  ![GitHub Logo](/photo39.png)
  
  This toolkit is automatically linked to the Business Manager site that you just came from. How convenient!

 #### Personas
 
 People in three types of job roles are most likely to use Business Manager. We call these job roles personas.

 ![GitHub Logo](/photo40.png)
 
  With large merchants, each persona can have a distinct function that’s held by multiple people. Large merchants often work with partners, who have a team of developers. Small and medium merchants often blur personas, so that multiple job responsibilities are handled by a few people.

#### Where Personas Work in Business Manager

Two tabs in Business Manager—Merchant Tools and Administration—contain the functionality used by all three personas. Let’s explore the tab used by our first persona, merchandisers.

##### Merchant Tools Tab

  The Merchant Tools area is where merchandisers manage site-specific configuration settings, and storefront data such as products, catalogs, content, search, campaigns, and promotions.
  
  ![GitHub Logo](/photo41.png)
  
  This is also where they configure functionality that helps bring shoppers to the site; namely, search URLs and the robots.txt file. Webmasters create this file to instruct web robots (typically search engine robots) how to crawl pages on their website.

  Merchandisers can also review customer data, though it’s typically stored in an external database. The same is true for order details, which can come directly from shoppers on a storefront or through add-on systems like Order Management for B2C Commerce and Customer Service Center. These products are part of the Commerce Cloud product suite.

##### Cross-Functional Tools

  Some functionality within Merchant Tools crosses persona boundaries. This includes site analytics and content slots.

  Business Manager Analytics reflects site data that’s captured on production storefronts, aggregated by B2C Commerce, and reported in Business Manager. Data such as carts to orders—the percentage of carts that were ordered from the total cart count—is extremely useful to merchandisers. Other data, however, such as pipeline performance summary data and object churn trends, is more useful to developers.

  A content slot can be embedded in any part of your storefront to show products, categories, content assets, or static HTML based on a schedule. You can personalize what it contains based on a customer group. A content asset can be a flash graphic, product carousel, product search result set, or marketing graphic.
  
  ![GitHub Logo](/photo42.png)
  
  Content slots require both developer and merchandiser involvement. First, a developer adds code to HTML pages, creates rendering templates, and uploads the code to the server. Then the merchandiser uses Business Manager to create and schedule the slot configuration.

##### Administration Tab

  The second tab, used by our administrator and developer personas, is called Administration. In this tab, the administrator:

* Imports and exports site data
* Moves data and code to and from site instances
* Manages customer lists and content libraries
  
  If you’re an administrator, you configure global settings that apply to all the sites in an organization. An organization contains all the sites that are configured for a merchant. Global settings, also called preferences, include:

* Locales and regional settings to support multiple languages
* Password restrictions and login lockout policies for Business Manager users
* Time zones
* Order and customer sequence numbers

##### The Developer Persona

Finally, we can talk about the developer persona. These are the people who develop storefront applications using a variety of software development tools (in this case, Business Manager).

A developer typically opens three windows with:

* The Integrated Development Environment (IDE), where they write and test the application
* Business Manager, which is used to open the storefront site
* The storefront application, where they see the real-time results of any code or data changes

Let’s focus on Business Manager, where developers can do the following:

* Create new sites
* Troubleshoot problems.
* Navigate to XChange, the Commerce Cloud Community portal, where they can download the latest version of UX Studio.
* Configure code versions
* Register cartridges (containing code or data) with the server
* Manage page cache settings
* Set the site to online
* Manage site taxation
* Create custom error and maintenance pages to steer the shopper to what they want to buy

Business Manager operational tasks are also done by developers. This includes configuring credentials and security and tracking quota status. Quotas are internal limits that keep the systems running nicely.

##### Permissions

  Access to Business Manager areas or modules is based on job tasks, also called roles. The most important role is the administrator (admin), who manages users and permissions. The admin starts by defining the organization and all its storefronts, and setting default languages. They then create additional roles.
  
  ![GitHub Logo](/photo43.png)

##### Localization  

  Business Manager supports multiple languages in both its user interface and in the underlying data that’s created, edited, and shown within it—to be used on the storefront. You can configure locales separately for viewing the application and for managing the data. For example, a shopper could view English products and content using a Japanese-language Business Manager.

  The admin user selects the preferred locale for the Business Manager display language, and when creating or editing a user profile. A Business Manager user can then select a different display language in their user profile.
  
##### Customize Business Manager
  
  You can customize the following parts of the Business Manager user interface to make it your own:

* Menu items
* Menu actions
* Dialog actions
* Forms
  
  The out-of-the-box Business Manager menus use menu item actions to access functionality. So changes to those areas integrate really well with the standard user interface actions. In other words, it’s easy to customize certain parts of the user interface!  
  
### B2C Commerce Development Environment

  Whether you’re a new or an experienced B2C Commerce storefront application developer, you know the landscape. You start by looking at the tools.

  The three key B2C Commerce software development tools are Business Manager, UX Studio, and the Commerce Cloud Storefront Reference Architecture (SFRA). Other tools include the following:

* Templates
* Form definitions
* Resource bundles
* Scripts
* Controllers

  We’ll get into more details in a minute, but first, let’s talk about the architecture.
  
#### The MVC Architecture
  
  We use the Model–View–Controller (MVC) architecture, which divides an application into three parts.

* The model is the business logic, data, and rules underlying the application. Traditionally, models store the data that’s used to populate the view. In B2C Commerce, data is represented by APIs, which provide helper classes instead of storing data.
* The view is what the shopper sees on the storefront. It’s the landing page, the product details page, QuickView, or the cart page.
* The controller takes shopper input from entry fields, button clicks, and the like, and converts them into actions or data that’s consumed by the model or view.  
  
  ![GitHub Logo](/photo44.png)

While this architecture provides a map of how the elements work together, the code still needs a deployment mechanism. That’s where the cartridge comes in.

#### B2C Commerce Cartridges

  A cartridge is how B2C Commerce packages and deploys program code and data. It delivers generic or application-specific functionality. For example, a merchant sells multiple brands, each with its own site. Because they sell apparel, all sites have similar processes. But the look and feel of the sites differ by brand. Generic cartridges contain standard processes, while application-specific cartridges contain brand-specific code and data.

#### Let's Start With What We're Building

  Let’s start by talking about what we’re building, from the top down.

  Storefront pages display on the client, whether it’s a desktop or a mobile device. These are some standard storefront pages:

* Home
* Category
* Product details
* Search results

  These pages are in proprietary ISML, which is based on HTML and uses CSS for formatting—industry standard stuff. Shoppers interact on these pages by clicking buttons and tabs and entering text into fields. The development tools used here are called templates and form definitions.

  With these tools you can:

* Validate shopper input
* Prompt shoppers for confirmation
* Show error or informational boxes
* Conditionalize HTML

  There’s an application processing component on both client and server. This is the code that takes the clicks and data entry from the pages and does something with it. The development tools used here are scripts and controllers.
  
  With these tools you can:

* Add calculations and logic to business processes
* Call web services
* Integrate back-end systems
* Share information across users
  
  Now let’s talk about the processing part.

#### Coding Storefront Pages

  The storefront pages are the visuals—the nifty products, flashy advertisements, and crafty discounts. For these you need templates, form definitions, and resource bundles—client-based only.

##### Templates

  Templates define how data and page information is transformed into HTML-based web pages. These pages are rendered on the browser using CSS for page layout and styling and the B2C Commerce form definitions for data display and verification. Templates are coded in the Internet Store Markup Language (ISML) that dynamically generates HTML. It provides a number of predefined tags (for example, <isif>/<isloop>) and uses script blocks and expressions.

  With ISML, you can use a single template to show thousands of products. For example, the search results page shows a list of products in rows and columns of tiles as defined by a template.
  
##### Form Definitions

  Form definitions let you control how customer-entered values are validated and rendered on the browser. With forms, for example, you can specify that ZIP codes must be entered as a precise series of integers; while name and address information must be entered as strings. Like with ISML, B2C Commerce form definitions use a distinct language and are proprietary.

  ![GitHub Logo](/photo45.png)

  Form definitions are stored in the forms folder of a cartridge (cartridge/forms/default). A form schema file identifies allowed elements and attributes. Form definitions interact with both the display and the processing parts of storefront applications.

##### Resource Bundles

  You want to avoid hard-coding text strings in storefront code that are visible to the shopper. Do this by storing titles, labels, messages, button and field names in resource bundles (also called .properties files). Keeping this text separate from display layout makes it easy to change the text for different purposes, especially when supporting different locales.
  
#### Process the Storefront Application

  The processing part of the application displays, sends, calculates, or retrieves the right details from arrival to checkout—all at the shopper’s initiative. To do this, the application uses scripts and controllers.

  To upload code, you must either use UX Studio or an upload utility, such as webdav, a standard protocol. Upload utilities are available from the B2C Commerce community repositories in GitHub. You can also use standard JavaScript tools, including linters and static code analysis tools.
  
##### Scripts 

  You develop your application locally in UX Studio, but run it on the server. A JavaScript interpreter runs on the application server to process each JavaScript class or method. To the JavaScript interpreter, the source of the script call is irrelevant. This gives you flexibility in the tools that you can choose.

  B2C Commerce has some serious application program interfaces (APIs) with the B2C Commerce Script APIs and the Open Commerce APIs (OCAPI). OCAPI is a RESTful API, which receives HTTP requests and returns responses. The request construction and response consumption is up to you.

  Use the B2C Commerce API to build all parts of a storefront’s user experience. Use OCAPI to integrate third party systems and to unify customer journeys that go beyond the Commerce Cloud hosted experience.
  
  The B2C Commerce Script API supports industry standards:
  
* Rhino JavaScript (including ECMAScript 5, Mozilla extensions up to JavaScript 1.8 and E4X)
* Optional type specification support from JavaScript 2.0/ECMA 4th edition proposal and ActionScript
* ECMAScript 5 compatibility fix for the global parseInt(String) functions

##### Controllers

  Controllers are server-side scripts that handle storefront requests. Controllers orchestrate your storefront’s back-end processing and create instances of models and views to process each storefront request and generate an appropriate response. For example, clicking a category menu item or entering a search term triggers a controller that renders a page.

  Controllers are written in JavaScript and B2C Commerce script. The file extension of a controller can be either .ds or .js. Controllers must be located in the controllers folder at the top level of the cartridge.

  You can use any IDE with a JavaScript editor to develop controllers.
  
#### LINK Partners

  The LINK marketplace is where developers go to extend their sites with third party software.

  Third-party software providers join the Salesforce B2C Commerce LINK Technology Partner Program to certify their cartridges against the latest Commerce Cloud technology. Use LINK cartridges to implement the most groundbreaking and innovative ecommerce technologies available.

  These cartridges take significantly less time to implement because they’re ready to go. There are lots of solutions, many in the following categories:

* Payment providers
* Rating and reviews
* Tax address verification
* Social personalization

### Commerce Cloud Storefront Reference Architecture

  What better way to show what an online storefront site looks like than to build one that you can view and use as a code base? That’s exactly what we did with SFRA. But this architecture is more than just a code base: It provides the blueprint for site design.

  Using a reference architecture is all about speedy innovation! Build sites faster with a full library of core site capabilities developed with industry best practices. Hundreds of out-of-the-box features include cart, checkout, homepage, product detail pages, and more. Also, quickly adopt technologies like Apple Pay–giving your shoppers an awesome experience.

  The SFRA customization model makes it easy for you to build, maintain, and update your storefront. It sits outside of the platform API layer and uses a conventional Model-View-Controller (MVC) architecture. We talked about APIs and the MVC architecture in the Salesforce B2C Commerce Development Environment unit.

  Developers are free to customize and extend the SFRA code base. Brands are empowered to design pixel perfect sites and meticulously build unique web experiences. Developers bring in new code, integrate with third-party providers, and iterate on their site designs. As a result, merchants completely own their storefront and the underlying code base.


#### Mobile First Design

  Historically, most web designers focused on the desktop first, with mobile second. Even with responsive design, the focus started with the desktop, with additional code for mobile.

  Responsive design adapts what’s on the screen based on the screen size.

  Mobile isn’t a trend. It’s the present. More and more people use mobile devices to do all kinds of things, especially shop online. Holding a computer in your hand is a powerful thing.

  Mobile-first designs for the smallest screen, and then works its way up. It’s one of the best strategies to create either a responsive or adaptive design.

  Adaptive design detects the device and other features, and then provides the appropriate feature and layout based on a predefined set of viewport sizes and other characteristics.


#### Let's Talk Architecture

  A reference architecture serves as a starting point for online storefront design, and combines best practices in site design and storefront architecture. It gives you a blueprint for building and customizing your ecommerce storefronts.
 
 ![GitHub Logo](/photo46.png)
 
 The Commerce Cloud Storefront Reference Architecture (SFRA) uses JavaScript controllers. In B2C Commerce, controllers are server-side scripts that handle storefront requests. They manage the flow of control in the application, and create instances of models and views to process each storefront request and generate an appropriate response. For example, the shopper clicks a category menu item or enters a search term, which triggers a controller that renders a page.

  The SFRA makes it easy to segment B2C Commerce delivered code, merchant customizations, and third-party integration code into discrete cartridges—making it easier to maintain and update the contents of each cartridge.

  In B2C Commerce, a cartridge contains code or data. This means that developers can build new components, for example, features such as wishlist, Apple Pay, and payment integrations, and independently plug them into the storefront. This architecture allows for a lightweight and cleaner codebase for continuous, iterative, and evolutionary site design. The core code is not available for edit, while developers are free to develop functionality on top of it.


*Best Practices UI Development
The SFRA uses the popular Bootstrap front-end component UI library. Bootstrap is an open source toolkit for developing with HTML, CSS, and JS. It lets you quickly prototype your ideas or build your entire app with its Sass variables and mixins, responsive grid system, extensive prebuilt components, and powerful plugins built on jQuery.
  
#### LINK Partners
  The B2C Commerce LINK Technology Partner Program provides a world-class ecosystem of rich, robust capabilities that merchants use to deliver best-in-class ecommerce solutions. LINK Partners work hard to integrate their technologies with B2C Commerce. Once integrated, the technologies are delivered to global B2C Commerce customers through the LINK Marketplace.

  The most-used LINK cartridges—Paypal, CyberSource, Bazaarvoice (Ratings & Reviews), Avalara (Tax), Adyen, Experian QAS (AVS)—are available in the SFRA. When evaluating new site designs or redesigns, merchants and SI implementers should consider the LINK ecosystem to extend the commerce experience.
  
### B2C Commerce Business Objects

  B2C Commerce is an object-oriented system, so it’s important to understand some basic principles, starting with objects. An object is a self-contained entity that contains data. A single object is organized so that the data describes the object. For example, a Dress object looks like this:

Dress

* Size
* Color
* Fabric
* Occasion
* Sleeves
* Neckline
* Length

  The Dress object only contains data that describes the dress. It doesn’t contain data that describes something else, such as a bracelet, for example.

  The data, such as Color in this example, is stored in fields that are also known as attributes. Attributes are used to describe an aspect of the object. In this case, if you told a friend you were going to describe something and then said, “Size, Color, Fabric, Occasion, Sleeves, Neckline, and Length,” they would likely say that you were talking about a dress (or maybe a blouse). Dress is the object, while Color is the object’s attribute.
  
  Business objects define the structure of B2C Commerce storefront data. Business objects can be system objects that come with the system, or custom objects that you can use to add additional capability to your application. Custom objects require custom code.

#### System Objects

  B2C Commerce provides 63 system object types, from Appeasement to TrackingRef. Some are marked as read-only in your version of Business Manager. You can’t customize the internal B2C Commerce system by creating new system objects, but you can create new custom system objects to meet your business needs. This is an important distinction! System object types define the attributes that are contained in system objects. They act like a map.

  The Commerce Cloud Storefront Reference Architecture (SFRA) uses system objects to describe parts of its site. This makes it useful as a starting point for storefront application development, because it was developed to interact with system objects—eliminating the need for custom code.

  To ensure that your implementation fully uses the available system objects, you should get familiar with them. In Business Manager, B2C Commerce’s online tool for configuring, administering, and developing your storefront application, you can: 
  
* View system objects
* View the attributes of each system object
* Edit the attributes, including creating new attribute values
* View attribute groups
* Create new attribute groups

  B2C Commerce’s rich library of system objects already addresses most of the data you need in your storefront application, such as product details, content, orders, and promotions. Using these objects greatly speeds implementation, because you can take advantage of code that’s developed for these objects.

 ![GitHub Logo](/photo47.png)

#### Extend System Objects

  You can extend system objects to collect more information from your shopper, tailor your storefront site to show additional information, and help you process orders more efficiently, depending on your back-office needs.
  
  For example, you can add an addToEmailList attribute to the basket object, which would display a Please Add Me To Your Email List checkmark box on the shopping cart page. You would also need to add the code to display and process this data.

#### Group Objects to Collect More Data

  Business Manager is where you manage storefront data, such as product and content details. Though system objects come with a standard set of attributes, you can always add attributes if you want to add more data. For example, you can give your shoppers the ability to pick up items in your brick-and-mortar store by adding an attribute. We’ve already added this attribute, because it’s a great feature, by creating an attribute group called InStorePickup.

  On the storefront, this feature shows up at checkout. But in Business Manager, it shows up on the product details page where you manage your product data. You can set specific products to be available for in-store pick-up.

  Of course, you also have to write the underlying application code that handles this on your storefront, but we’re just talking about business objects.

  To show a system attribute within Business Manager, the attribute must belong to a group. Otherwise, it won’t appear on a Business Manager page. That’s not the same as appearing in the storefront
  
   ![GitHub Logo](/photo48.png)

#### Custom Objects

  You can use custom objects to extend the B2C Commerce model to suit your business needs. In Business Manager, you first create custom object types and define the attributes they contain. Then you create the custom objects based on those attributes.

  Custom object types are available to be used in all the storefronts sites that are defined for the organization. However, you can choose, when creating a custom object, if it’s site-specific or organization-wide. We talked about organizations in the Business Manager unit in this module.

   ![GitHub Logo](/photo49.png)

#### Best Practices

  Use system objects instead of custom objects whenever possible to make it easier to upgrade to the latest reference architecture and eliminate unnecessary customization.

  Use system attributes instead of custom attributes whenever possible.

  
## Architecture of Salesforce B2C Commerce
Learn the architecture and tools you use to develop for Salesforce B2C Commerce.

### Get Started Configuring Your B2C Commerce Sites

Salesforce B2C Commerce includes the resources and processes you need to run your ecommerce storefronts. You don’t interact directly with the cloud; it’s the foundation that supports your site. This unit explains how it all works: realms, PIGs, SIGs, and the types of instances that run on them.

When a site is created, or provisioned, it is structured into what is called a realm, which includes two groups: the primary instance group (PIG) and the secondary instance group (SIG). Realms are merchant-specific. Both groups include tools that you can use to configure your ecommerce site.

![GitHub Logo](/photo50.png)

#### Realms

Merchants typically have a single realm that’s just for them. A realm contains instances on which to develop, test, and deploy a storefront application. A B2C Commerce instance is an application infrastructure that includes the following components:

* Web servers
* Application servers
* Database servers

Typically, a merchant receives nine instances per realm. This includes three instances for staging, testing, and deployment on the PIG, five sandbox instances for code development on the SIG, and one demo instance. For scalability, customers can have up to 47 sandboxes per realm.

Within Business Manager, the B2C Commerce tool for site configuration and management, you use the PIG instances as follows.

* Staging—For site configuration, data enrichment, and data import
* Development—For testing the site before deployment
* Production—For hosting the live site that's visited by shoppers

#### Single and Multiple Realm Configurations

Typically, a merchant has a single realm in which to develop, stage, and deploy multiple sites with different branding or locales. The people managing the storefront site don’t need to be in the same location. Sites can share product catalogs or have different catalogs. They can even share some site admin settings.

Merchants with multiple lines of business or global teams that each have their own processes or business policies often use multiple realms. Separate realms are also useful for merchants with distinct organizations that have separate back-end integrations, schedules, or other concerns that are better managed independently.

![GitHub Logo](/photo51.png)

While sites in the same realm can share the same master catalog for product data, sites in different realms can’t share data through the catalog structure. They can, however, share data by importing it into different realms.

Say you have two sites with separate brands: one in Europe and the other in the Pacific Rim. You can have a realm for the team managing the Pacific Rim site and another realm for the team managing the European site.

#### Sites and Organizations

In Business Manager, you can configure one or more sites within each instance. The multiple sites on a particular instance are considered an organization. When you configure settings, for example, you can configure them as site-specific (one site) or across all the sites (the organization).

#### Instances

A B2C Commerce instance contains the tools and resources for customizing storefronts. View an instance by typing its URL in a browser or open it in Business Manager. The four types of instances—sandbox, staging, development, and production—have different considerations:

![GitHub Logo](/photo52.png)

#### Instance Type Users
Depending on the size of the team, a person can play multiple roles. These are some general responsibilities.

![GitHub Logo](/photo53.png)

### Learn About Importing and Exporting Data

Most merchants have back-end systems, which are their systems of record. The Salesforce B2C Commerce application environment has its own databases and servers designed to support storefronts. The B2C Commerce import/export functionality bridges the gap.

Think of the flow of data: From a system of record to B2C Commerce and from B2C Commerce capture to system of record. Product details such as SKU numbers, product descriptions, sizes, images, prices, and video are developed in a system of record and then imported into B2C Commerce. Shoppers create orders that are exported to external system for processing. While coupon codes can be imported into B2C Commerce, the act of redeeming a coupon by a shopper creates data that is exported.

Import uses data from an external file to populate the B2C Commerce database. Export lets you extract data from the B2C Commerce database and create XML files that can be used as feeds for external systems. A feed is a specific import or export process.

![GitHub Logo](/photo54.png)

Data is exported from production.

These are not storefront data import/export processes.

* Data replication is when you copy code and data from one instance to another. We talk about data replication in the next unit.
* The Business Manager catalog feed feature processes third-party files (such as for Certona).
* Site import/export moves site-specific configuration and setting information from one instance to another.

#### Schemas

Schema files specify the file structure expected by B2C Commerce import and export. B2C Commerce only accepts XML import files formatted by these schemas. The schemas also document the required data attributes. Imported data must match the schema, or it won’t import.

B2C Commerce exports in XML format, except for coupon codes, which export to CSV format. We recommend you use a third-party program to process .csv files into the required XML format. It’s a lot faster and more efficient to transform a file using a pure .NET or a Java platform with a large amount of memory allocated to the processing.

So what are these schema files? It turns out there are a lot of them. Here are some examples:

* sort.xsd
* coupon.xsd
* couponredemption.xsd
* order.xsd
* Promotion.xsd

#### Modes

You specify an import mode to define how B2C Commerce interprets the data within an import feed. The mode applies to all objects within a feed and to all import files defined by the schemas.

![GitHub Logo](/photo55.png)

These are the import modes.

![GitHub Logo](/photo56.png)

Be careful when you delete objects in an import. Delete mode deletes objects that are in the feed. Likewise, replace mode deletes and then re-creates objects that are in the feed. Performing a replace import just to change one object deletes the entire object set.

Some schemas support an attribute mode at the import element level. In this case, the only supported mode is delete, where the import mode for the process can be overwritten for a particular element. This is useful with changed information, where a single import process creates, updates, and deletes objects.

##### Production Feeds

We recommend that production feeds only contain changes from the previous feed. These are called delta feeds. They are smaller to archive, faster to import, and easier to troubleshoot. However, some schemas have elements that override the global import mode and always use the replace mode. These elements can't be included in delta feeds, because they require the full set of objects to be included in each import.

##### List-Type Elements

The standard behavior for list-type elements in the XML files is to replace the entire list, regardless of import mode. If the list element isn’t contained in the import file:

* In merge mode, the list remains.
* In replace mode, the list is deleted.

#### The Import/Export Process

This is a typical import process.

1. Use WebDAV, SFTP, or HTTPS to transfer the XML file from your back-end system to a B2C Commerce instance.
2. For staging or production instances, set up a secure connection for the file transfer. Sandboxes don’t require it.
3. Import the XML file into the instance using Business Manager, or create a custom controller. B2C Commerce provides import pipelets for most standard imports that can deal with large data sets, are fast and reliable, and use system resources efficiently. We recommend using them when business objects must be loaded into B2C Commerce instead of using custom logic with B2C Commerce script or pipelets.


This is a typical export process.

1. Export the database objects to an XML file using the schemas. Do this manually through Business Manager or by creating a custom controller. You can use B2C Commerce export pipelets for most exports. In some cases, they’re more granular with the objects than Business Manager. You must create a controller to automate data exports.
2. Transfer files from the instance to the merchant back-end system.
3. Configure a secure connection if you need to meet PCI-DSS (security) requirements for transferring the data or for back-end system requirements.


#### Instance-Specific Details

You’ll use B2C Commerce import/export in different ways, based on the instance type. We explore each instance type separately.

##### Sandbox

When developing your site, each developer uses a separate sandbox. You can create an initial sandbox that’s used as a template for additional sandboxes, so that site configuration is only done once.

You first transfer data files from your local machine to the instance. Then you import the data into the instance database using Business Manager. When your first sandbox has the configuration and data you want for your development team, use Site Export to export the site contents and configuration, and then download them to your developer machines.

During development, you can import new product and price feeds directly into each sandbox. Each sandbox uses the same import files, but must independently import them. You can also create custom controllers to automate data import, a step that’s usually done to support automatic data import for staging and production systems. Another sandbox can then use Site Import to get the configuration and contents.

##### Staging and Production

The primary instance group (PIG) contains the development, staging, and production instances. Use a custom controller to move data via a secure connection from a back-end system to one of these instance types. For infrequent feeds, import them only into staging and then replicate them to production. This protects your production instance from problems with imported data.

Some feeds might require additional enhancement in Business Manager; for example, if you want to manually add web-only descriptions or other information. Feeds that require enhancement are updated in staging and then the data is replicated to production.

It’s not practical to stage and replicate data that must be changed frequently, so frequent feeds are imported directly into production. Frequent feeds are imported into staging and production at the same time, so the instances remain synchronized. Remember, your staging instance should always reflect production.

Use controllers for added import/export flexibility. Add business logic to your controller to add values to your import file, update search indexes automatically, or archive the import file. When you export data from production, you can add business logic to your controller to change the format of the export file, add values, or do other processing.

##### Development

A development instance is the testing environment for your production instance. You can do an initial site import/export from a staging to development instance to set it up. After that, use data replication to update data and code on that instance.


### Learn About B2C Commerce Replication
  
Replication is a Salesforce B2C Commerce process that pushes data and code from a staging instance to a development or production instance in a controlled manner, minimizing the risk of errors. Replication only happens on instances in the primary instance group (PIG), and not on the secondary instance group (SIG) or sandboxes.

![GitHub Logo](/photo57.png)

#### Source and Target

During replication, changes are pushed from a replication source to a replication target. The replication source is always the staging instance; while the replication target can be a development or production instance. While the main goal of replication is to push changes from staging to production, a preliminary step is to push the same changes to development. This lets you verify that replication was successful.

#### Replication Control

Start by creating a replication process in Business Manager, the B2C Commerce tool for site configuration and management. A replication process is a collection of replication tasks that specify the changes since the last replication. The changes can be data (such as product data, content, and image files) or code.

You can define multiple replication processes and specify which replication tasks to include in each. This lets you control the level of granularity that’s pushed each time. You can push an entire site or a selected subset; for example, just the site's custom objects. You have a similar flexibility with organization-level changes.

Schedule start and end dates during times of low traffic, so it doesn't impact your site's performance, or adversely affect the shopper experience.

##### Two-Step Publishing

You can replicate data via two-step publishing, which helps you avoid running the entire process only to have it fail. This process helps if you’re just starting your replication and transfer processes, and need more control over the results.

1. Transfer—Create a new replication, configure it for your site, and select Transfer as the replication type. If the transfer fails, figure out what went wrong. Once you've fixed it, try again.
2. Publish—Create a second task called Data Publish to publish the data. For data replication, the data in the transfer and publish tasks must match. For example, you can’t transfer catalog, index, and promotion data, and then only publish catalog data.

#### Data Replication

Because data replication is intended to push the latest version of a storefront into production, it’s a replace operation, and not a merge. Data replication first creates a copy of the data from the source instance at a new location in the target instance, without replacing the original data. When the process completes, you switch from the existing data to the new data in the target system, effectively replacing the data. It’s seamless and instantaneous.

The first time you replicate data, all the data is included. For subsequent replications, you can replicate on a granular level. For example, you can replicate individual sites and their associated catalogs: all catalogs, one catalog, or the standard catalog.

##### Choosing Data to Replicate

B2C Commerce data can have an organization or site scope. At the organization level, data is shared by all sites. At the site level, data is only used by an individual site. Within each scope, you can select different sets of data to replicate, such as all of the organization's catalogs or a specific storefront's promotions and coupons. This is the lowest level of data replication granularity supported. This capability is useful when some data is ready to replicate and some isn’t. For example, new content assets might be ready for production, while new catalog definitions aren’t.

There are some limitations. You can’t select a single product in a catalog or a promotion from within a data set to replicate. Data replication doesn’t copy these from staging:

* Orders
* Inventory lists
* Business Manager user profiles and login credentials

##### Schedule Data Replication

You can schedule a replication process four ways.

* Automatic—At a specified date and time, by default, or immediately after you’ve defined the replication process
* Manual—Ready to be started in Business Manager by a user with the proper permissions
* Recurring—On a daily, weekly, or monthly schedule
* Job Step—When triggered by a job

Be careful when you replicate. If a recurring data replication fails, subsequent repetitions of the job won’t run. Replication usually clears the page cache, which can have a dramatic impact on storefront performance.

##### Best Practices
Here are some data replication best practices.

* Test the replication process from staging to development first.
* Test the resulting configuration on development to ensure it works as expected.
* Always run transfer, followed by publish so you can verify the transfer process.
* Identify dependencies between different data replication groups.
* Always replicate the search indexes with catalogs.
* Perform the transfer to production step when storefront activity is at a minimum.
* Disable incremental and scheduled indexing and stop other jobs while replicating data. Though incremental indexing doesn’t need to be disabled for the transfer, it must be disabled before you publish. You can either replicate the search index or manually build it on the target instance.
* Avoid major data replications during the B2C Commerce standard maintenance windows.
* Use Business Manager permissions to limit who can perform data replication.

#### Code Replication

With Business Manager code replication, you replicate a code version between a source and a target instance. A code version is a folder that contains custom cartridges. An instance can have multiple code versions, but only uses the active code version.

When you’ve finished developing in your sandbox, use UX Studio to create a new server connection and upload your code to staging. The server connection should be secure.

![GitHub Logo](/photo58.png)

On the production instance, a new version is automatically created, named a combination of the original version name with a timestamp. You can copy the code to production without activating it, or copy it while making it active. If you need to revert to a previous code version, B2C Commerce knows which version was previously active and reactivates it. We suggest you do the following on a production instance.

1. Deploy the code version on staging.
2. Replicate the code (and data) to development to test the process.
3. Replicate the code to production.


##### Replication Types

Configure the target system to create code replication processes with a manual, automatic, or job step start. These are the replication types.

![GitHub Logo](/photo59.png)


##### Email Notification

You can configure email notifications for code replications using a comma-delimited list of recipients. An email is sent after the process finishes or fails. If the process hangs, no email is sent.


#### Replication Groups

Replication groups (or tasks) let you organize your data and processes in a manageable way. You can also replicate data at the site level, organizational level, or both. Custom objects, for example, can be replicated at both the organizational and site level.

Business Manager groups multiple objects that are replicated together. Spend time reviewing the relationships among the objects to understand their complexity.

#### Data/Code Replication Versus Import/Export

* Replication moves data from one instance to another, once the data is already in a B2C Commerce database.
* Import and export moves data to and from external systems, from and to a B2C Commerce Database.


## Tools & Resources for Salesforce B2C Commerce Developers

### Explore the Developer Resources 

Vijay Lahiri is a senior developer at Cloud Kicks, a company that specializes in high-end custom sneakers. He wants to develop a new B2C Commerce storefront. But before he gets started, he wants to make sure that he has access to the latest and greatest information about B2C Commerce. He also wants to check out the resources that Salesforce provides especially for developers like him.

![GitHub Logo](/photo60.png)

So, how does he get plugged into all that good stuff? In this unit, we follow along as he learns about XChange, the Commerce Cloud Community Portal, and the Infocenter, the B2C Commerce official documentation portal.

In XChange, he can ask a question or sign up for a class. He can also find information about releases and events, and become part of the B2C Commerce community of developers. In the Infocenter, he can explore product details and learn how B2C Commerce features and technology works.

#### Get Started with XChange

Vijay needs credentials to sign in to XChange. He contacts the B2C Commerce account manager for Cloud Kicks, who sends him an email with information on how to get a username and password. If he still needs help accessing XChange, he works with the account manager directly. Once he has his credentials, he logs in and the XChange home page opens. There are lots of great resources to help him get started with XChange. He clicks XChange Help at the top of the XChange home page to go to the Getting Started in XChange page.

![GitHub Logo](/photo61.png)

This page has links to a Getting Started Video, FAQs, and other information about XChange features. Vijay watches the Getting Started Video and pays close attention to the information about the Developer Forum and how to sign up for training classes.

![GitHub Logo](/photo62.png)

Next, he checks out some other resources on the Getting Started page, including the How to Use XChange links.

#### Join the B2C Commerce Developer Community

Vijay wants to know where can he go for help when he’s stuck. Is there a way he can discuss his issues with other developers and share solutions? Working with other developers is a big part of how he gets his work done. Luckily, that’s what the Developer Community on XChange is all about.

Vijay clicks Developers on the XChange home page to access the Developer Community page.

![GitHub Logo](/photo63.png)

The Developer Community page is the go-to place for B2C Commerce developer information, with links to conferences, best practices, and a code library.

![GitHub Logo](/photo64.png)

He clicks Discussion Forums to access the B2C Commerce developer discussion board. On the discussion board, he can search the forum, ask a question, or post or respond to a poll.

![GitHub Logo](/photo65.png)

#### Join the Partner Community

Although Vijay works for Cloud Kicks, many B2C Commerce developers work for partner organizations. Resources for partners are available though the Salesforce Partner Community, a trusted environment where partners can get answers, share ideas, collaborate, and learn best practices.

Another great resource is the B2C Commerce Chatter group. Partners use this to communicate with the global Salesforce LINK Technology Partner Team and other partners. There's also a Chatter group within the Partner Community called Official: LINK Tech Partner Program for LINK partners.

#### Find Release Information

Vijay is definitely going to want to keep up with new features and bug fixes in B2C Commerce releases. The easiest way to do that is to click Product Release Information on the Welcome To XChange page.

![GitHub Logo](/photo66.png)

This page has links to release notes and webinars that explain what’s new in each release. Plus, Vijay can access discussion forums to give Salesforce his feedback about the new features.

![GitHub Logo](/photo67.png)

From XChange, he can also access the B2C Commerce release notes. The release notes live on the Salesforce Help and Training Portal, but he can conveniently access them from both places.

#### Search the Documentation

Vijay has lots of questions. What’s the procedure for connecting to the server? What does this option on the screen mean? Sometimes he just wants to look up something in the documentation.

The Salesforce B2C Commerce Infocenter is where he can access all the B2C Commerce documentation. He quickly locates the developer documentation, information about using Business Manager, B2C Commerce APIs, admin tasks, and more.

![GitHub Logo](/photo68.png)

When he wants to find something specific, he searches for it in the Infocenter.

![GitHub Logo](/photo69.png)
![GitHub Logo](/photo70.png)

### Install and Configure UX Studio

Now that Vijay has identified the Salesforce B2C Commerce resources for developers, he’s ready to take the first steps in developing the new storefront. In this unit, we follow along as he gets his local computer ready for the job by downloading the necessary software and configuring the right settings.

Here are the installation and configuration tasks ahead.

* Install Eclipse as the integrated development environment (IDE).
* Install Java and configure a workspace.
* Install the UX Studio plug-in.
* Connect the local system to the B2C Commerce sandbox instance.
* Get Commerce Cloud Storefront Reference Architecture (SFRA) repositories from GitHub.
* Install and configure SFRA.

In this unit, we show you steps 1 through 4. We show you steps 5 and 6 in the next units.

#### What's UX Studio?

As with any software development project, Vijay needs to use an integrated development environment (IDE). For this project, Vijay uses UX Studio, a special plug-in that we designed for the Eclipse IDE, just for Salesforce B2C Commerce developers. You can use UX Studio to develop new storefronts, create business processes, and integrate with external applications.

But wait… what if you have a favorite IDE or JavaScript editor that you want to use instead of UX Studio in Eclipse? That’s OK. As long as you’re developing for a newer storefront that uses controllers instead of pipelines, you can use other tools (for instance Propher Debugger for VS Code). Some B2C Commerce developers use Visual Studio Code, Sublime Text, or WebStorm. But keep in mind that if your storefront uses pipelines, you have to use UX Studio.

#### Install Eclipse and Java

Vijay starts by looking at requirements. What versions of Eclipse and Java does he need?

UX Studio requires these versions of the Eclipse IDE for Java EE Developers.

Eclipse 4.5 (Mars)
Eclipse 4.6 (Neon)
Vijay doesn’t have Eclipse, so he downloads and installs it from this location: http://www.eclipse.org.

Eclipse is similar to other IDEs Vijay has used. And there’s lots of great documentation to help him get started. You can check it out here: https://www.eclipse.org/documentation

He also needs Java SE Development Kit (JDK) Version 8 on his local computer, so he downloads and install it from this location: http://www.oracle.com.

#### Set Up a Workspace

When Vijay starts Eclipse, he must specify a workspace. He chooses a location on his local system that has plenty of space.

![GitHub Logo](/photo71.png)

#### Install the UX Studio Plug-In

Now that Vijay has installed Eclipse and Java and specified a workspace on his local system, he’s ready to install the B2C Commerce UX Studio plug-in. But first, he needs to determine the version of Eclipse he uses so he can upload the correct version of the plug-in using its URL.

This table shows all the options that Vijay can enter in the Location field when he specifies the Eclipse version. We recommend that you always work in a sandbox instance when developing your storefront application. (We talk about working in sandboxes in the next topic.)

![GitHub Logo](/photo72.png)

Now that he’s figured out which plug-in URL to use, here’s how he installs it.

![GitHub Logo](/photo73.png)
![GitHub Logo](/photo74.png)

Now Vijay opens the Digital Development perspective. This is the perspective you work in to develop your storefront. Here’s how he does it.

![GitHub Logo](/photo75.png)


#### Connect to Your Sandbox
 
To use UX Studio to develop a storefront, Vijay must create a connection between UX Studio and a B2C Commerce sandbox instance.

In this module, we assume you are a B2C Commerce developer with the proper permissions to perform these tasks. If you’re not a B2C Commerce developer, that’s OK. Read along to learn how your developer would take these steps in a sandbox instance. Don't try to follow our steps in your Trailhead Playground. B2C Commerce isn't available in the Trailhead Playground.

If you have a sandbox instance of B2C Commerce, you can try out these steps in your sandbox. If you don't have a sandbox and you're a customer or partner developer, ask your manager if there is a sandbox that you can use.

Let’s see how Vijay connects UX Studio on his local machine to his B2C Commerce sandbox instance.

![GitHub Logo](/photo76.png)
