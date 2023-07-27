# Spryker Feature: Availability Notification

Allows users to subscribe to product availability notifications to receive emails when a product that was out of stock, is back in stock again.

[Learn more](https://docs.spryker.com/docs/pbc/all/warehouse-management-system/202307.0/base-shop/availability-notification-feature-overview.html)

## Installation

```
composer require spryker-feature/availability-notification
```

## Recommended feature dependencies
- [spryker-feature/inventory-management](https://github.com/spryker-feature/inventory-management)
- [spryker-feature/mailing-notifications](https://github.com/spryker-feature/mailing-notifications)
- [spryker-feature/product](https://github.com/spryker-feature/product)

If you don't include the feature dependencies, make sure you use the respective modules instead.

## Optional modules
- [AvailabilityNotificationsRestApi ^1.2.0](https://github.com/spryker/availability-notifications-rest-api) (Legacy Glue)
