# seat-billing
A billing system for mining/PvE costs for corps/alliances


## Quick Installation:

In your seat directory (By default:  /var/www/seat), type the following:

```
php artisan down

composer require denngarr/seat-billing
php artisan vendor:publish --force
php artisan migrate

php artisan up
```

And now, when you log into 'Seat', you should see a 'Seat IRS' link on the left.


You should schedule a job to run Monthly called 'billing:update'.  This will calculate the bills for the corps each month.


Good luck, and Happy Hunting!!  o7

