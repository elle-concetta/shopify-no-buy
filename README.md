# shopify-no-buy
A universal template for a Shopify product page that doesn't let customers purchase the product. It hides the pricing, and informs customers or visitors that the product is coming soon, or it's not available for purchase yet.

INSTRUCTIONS TO MANUALLY INSTALL TEMPLATE:
Keep in mind that the name of your 'Templates' and 'Sections' files for product template might be labeled a bit differently, so you may need to change the file names and some of the coding to correspond with your shopify theme.

Go to the 'Online Store' option on the left hand sidebar. Click on 'Actions' and then the 'Edit Code' option.

You will see all of the files to your shopify theme. First look at your 'Templates,' and click on the product.liquid file.

You will then click on 'Add a New Template.' A small option form will pop-up for the new template. Create a new template for: 'product'. Template type: 'liquid'. File name: product.nobuy.liquid (you will just want to type in 'nobuy').

After the 'product.nobuy.liquid' file is created, copy and paste in the code from the 'product.nobuy.liquid' file in this repository. Then hit 'Save'.

You will then scroll down to 'Sections' and analyze the name of the file for your 'Product Template'. Some themes name their files differently, so you want to keep this is mind. The 'Section' filename I will use as an example is 'template--product'. So then in turn you will want to name your new 'Section' file 'template--product-nobuy'

Click on 'Add a new section'. Create a new section called: template--product-nobuy Then click on 'Create section'.

Copy and paste the code listed in the Sections file. Again, you may need to edit some things to coincide with your shopify theme.
