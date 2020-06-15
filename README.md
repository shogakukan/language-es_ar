# Mugar Language-es_AR for Magento2

Magento2 Spanish (Argentina) language pack.

## Installation

Use [composer](https://getcomposer.org/) to install Mugar Language-es_AR.

```
composer require mugar/language-es_arf
```

Then you'll need to pack the translations.

```
bin/magento i18n:pack --mode=replace -d vendor/mugar/language-es_ar/es_ar.csv . es_AR
bin/magento setup:static-content:deploy es_AR
```

## Support

You can request to be added to [Slack](https://mugar.slack.com/).

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

### How to create a PR

1. Fork it
2. Create your feature branch (git checkout -b my-new-feature)
3. Commit your changes (git commit -am 'Add some feature')
4. Push to the branch (git push origin my-new-feature)
5. Create new Pull Request

## License

[MIT](https://choosealicense.com/licenses/mit/)
