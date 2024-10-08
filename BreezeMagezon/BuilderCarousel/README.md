# BreezeMagezon Builder Carousel

## Installation

```bash
composer require breeze-magezon/module-builder-carousel
bin/magento module:enable BreezeMagezon_BuilderCarousel
bin/magento setup:upgrade --safe-mode=1
bin/magento setup:di:compile
bin/magento setup:static-content:deploy -f
bin/magento c:f
```
