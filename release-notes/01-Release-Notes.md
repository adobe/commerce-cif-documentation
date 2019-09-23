
# Commerce Integration Framework GitHub Release Overview

#### Release Date: September, 2019

|GitHub| Version| Detailed Release Notes|
|:-------|:-----:|---------------------:|
|CIF Connector | 0.5.0|[Release Notes](https://github.com/adobe/commerce-cif-connector/releases)|
|CIF Core Components |0.4.0|[Release Notes](https://github.com/adobe/aem-core-cif-components/releases)|
|CIF Archetype |0.4.0|[Release Notes](https://github.com/adobe/aem-cif-project-archetype/releases)|


### What's new

**Features**
* Multi-template feature to allow authors to enrich specific product detail page or product list page. Authors can easily create a custom product detail page or product list page and use the product or category picker to assign the custom page to a specific product(s) or category(s).

* Multi-catalog binding to allow authors to bind multiple catalogs in the AEM product console. Authors can also edit and view the catalog binding properties after creating the binding.


**Components**
* React-based client-side Checkout and Mini Cart using GraphQL to support a complete basic shopping journey.

* Checkout component includes address forms, payment selection, and shipping method selection.


### What's improved
* Product Teaser and Product Carousel components support product variants.

***


#### Release Date: August, 2019

|GitHub| Version| Detailed Release Notes|
|:-------|:-----:|---------------------:|
|CIF Connector | 0.4.0|[Release Notes](https://github.com/adobe/commerce-cif-connector/releases)|
|CIF Core Components |0.3.0|[Release Notes](https://github.com/adobe/aem-core-cif-components/releases)|
|CIF Archetype |0.3.0|[Release Notes](https://github.com/adobe/aem-cif-project-archetype/releases)|

### What's new

**Features**
* Embedding CIF Connector in CIF Archetype made optional to provide developers more flexibility.  

* CIF Components decoupled from "Venia" specific CSS styling to allow developers to apply CSS styling of their choice.

* Multi-store/site feature to allow use of CIF Core Components on multiple AEM site structures and enabling the underlying GraphQL client implementation to connect to different Magento store/store views.

* GraphQL caching enabled for certain GraphQL queries via HTTP GET to reduce response time.

* Product description view enabled in AEM Products console.


**Components**
* Commerce Teaser extends WCM Teaser component to allow authors to also add CTA fields to a product detail page or a product list page.

* Button to allow authors to place on an AEM page and link to either an AEM page, product detail page, product list page, or an external link.


### What's improved
* Magento store configuration moved from OSGi to AEM Product console to make the integration setup more author-friendly.

***

#### Release Date: July, 2019

|GitHub| Version| Detailed Release Notes|
|:-------|:-----:|---------------------:|
|CIF Connector | 0.3.0|[Release Notes](https://github.com/adobe/commerce-cif-connector/releases)|
|CIF Core Components |0.2.0|[Release Notes](https://github.com/adobe/aem-core-cif-components/releases)|
|CIF Archetype |0.2.0|[Release Notes](https://github.com/adobe/aem-cif-project-archetype/releases)|

### What's new

#### Features
* First CIF Archetype to provide developers with several deployment options: 1.Deploy AEM Venia storefront 2. Deploy scaffolding for a new project 3. Use CIF elements in an existing project

* Multi-level catalog navigation to support navigation through categories and sub-categories.

* Pagination on category pages for better UX.

* Client-side rendering of price attribute in Product Detail and Product List components to support rendering of dynamic attributes. 


#### Components
* Server-side Product Carousel to display list of featured products in a carousel style.

* Server-side Featured Category List to display list of categories on an AEM page.



### What's improved
* Support for Magento 2.3.2 and bug fixes related to product properties display in the product console.

***

#### Release Date: June, 2019

|GitHub| Version| Detailed Release Notes|
|:-------|:-----:|---------------------:|
|CIF Connector | 0.2.0|[Release Notes](https://github.com/adobe/commerce-cif-connector/releases)|
|CIF Core Components |0.1.0|[Release Notes](https://github.com/adobe/aem-core-cif-components/releases)|


### What's new

#### Features
*  AEM B2C storefront with mobile-first Venia CSS styling, landing page, dynamic catalog navigation via product and category pages, product search page, and shopping cart capabilities to kickstart and accelerate commerce projects.

* CIF Connector and authoring tools (Product Console, Product Picker, and Category Picker) to enable authors to create experiences in AEM with commerce content.


#### Components
*  First version of CIF Core Components compatible with Magento 2.3.1:
    * Product Detail
    * Product List
    * Product Teaser
    * Navigation
    * Product Search
    * Shopping Cart (REST)