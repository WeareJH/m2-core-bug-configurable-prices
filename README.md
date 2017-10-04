# Jh_CoreBugConfigurablePrices
Fixes the MAGETWO-60098 issue where the min/max price is minus for configurable products with special offered associated products

See: https://github.com/magento/magento2/issues/7367

# Install

Using composer...

```
composer require wearejh/m2-core-bug-configurable-prices
```

Enable the module

```
bin/magento module:enable Jh_CoreBugConfigurablePrices
```