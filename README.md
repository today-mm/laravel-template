# TODAY Laravel Dashboad Package
# Display Package Name Widgets

## Installation

You can install the package via composer:

```bash
composer require today/laravel-dash-package-name
```

In the config file, you must add this configuration in the tiles key.

```php
    'package-name' => [
        'config1' => 'config1',
        'config2' => 'config2,
        'config3' => 'config3',
    ]
```

You can publish and run the migrations with:

```
php artisan vendor:publish --tag=":laravel-dash-package-name"
php artisan migrate
```

Usage

```


{{$laravelDashPackageName->site->block->nav()}}
{{$laravelDashPackageName->site->block->welcome()}}
{{$laravelDashPackageName->site->block->about()}}
{{$laravelDashPackageName->site->block->posts()}}
{{$laravelDashPackageName->site->block->faqs()}}
{{$laravelDashPackageName->site->block->registerOfInterest()}}
{{$laravelDashPackageName->site->block->emailSubscribe()}}
{{$laravelDashPackageName->site->block->contact()}}
{{$laravelDashPackageName->site->block->sectionTitle()}}
{{$laravelDashPackageName->site->block->footer()}}


{{$laravelDashPackageName->site->components->posts()}}
{{$laravelDashPackageName->site->components->post()}}
{{$laravelDashPackageName->site->components->faqs()}}
{{$laravelDashPackageName->site->components->faq()}}


{{$laravelDashPackageName->site->section->nav()}}
{{$laravelDashPackageName->site->section->welcome()}}
{{$laravelDashPackageName->site->section->about()}}
{{$laravelDashPackageName->site->section->post()}}
{{$laravelDashPackageName->site->section->registerOfInterest()}}
{{$laravelDashPackageName->site->section->emailSubscribe()}}
{{$laravelDashPackageName->site->section->contact()}}
{{$laravelDashPackageName->site->section->footer()}}



{{$laravelDashPackageName->dash->widget->localization()}}
{{$laravelDashPackageName->dash->widget->posts()}}
{{$laravelDashPackageName->dash->widget->image()}}
{{$laravelDashPackageName->dash->widget->menu()}}


```


## Testing

``` bash
composer test
```

## Changelog

Please see [CHANGELOG](CHANGELOG.md) for more information on what has changed recently.

## Contributing

Please see [CONTRIBUTING](CONTRIBUTING.md) for details.

## Security

If you discover any security related issues, please email info@todaydev.com.mm instead of using the issue tracker.

## Credits
- Sayar Gyi

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.
