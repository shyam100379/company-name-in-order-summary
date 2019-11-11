# Company field in shipping information Magento 2 checkout order summary

Company field in checkout page

To bring the company name in shipping information section of Magento 2 checkout order summary, override


    vendor/magento/module-checkout/view/frontend/web/template/shipping-information/address-renderer/default.html

to

    /app/design/frontend/your-vendor-name/your-theme-name/Magento_Checkout/web/template/shipping-information/address-renderer/default.html
