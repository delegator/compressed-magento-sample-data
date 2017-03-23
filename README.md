# Compressed Magento Sample Data

Inspired by https://github.com/Vinai/compressed-magento-sample-data

## Available variations


### 1.9.2.4

- 38M [compressed-no-mp3-magento-sample-data-1.9.2.4.tar.gz][1]

```
commands:
  N98\Magento\Command\Installer\InstallCommand:
    demo-data-packages:
    - name: compressed-sample-data-1.9.2.4
      version: 1.9.2.4
      dist:
        url: https://raw.githubusercontent.com/delegator/compressed-magento-sample-data/master/compressed-no-mp3-magento-sample-data-1.9.2.4.tar.gz
        type: tar
        shasum: d4efd5f50fa0bcee4a33242c6b8c33cfe5543b4a
```

- 31M [compressed-no-mp3-magento-sample-data-1.9.2.4.tar.bz2][2]

```
commands:
  N98\Magento\Command\Installer\InstallCommand:
    demo-data-packages:
      - name: compressed-sample-data-1.9.2.4
        version: 1.9.2.4
        dist:
          url: https://raw.githubusercontent.com/delegator/compressed-magento-sample-data/master/compressed-no-mp3-magento-sample-data-1.9.2.4.tar.bz2
          type: tar
          shasum: d2c0fb98fe3e2fbe4ee6d6015e955973fe327c27
```

[1]: https://raw.githubusercontent.com/delegator/compressed-magento-sample-data/master/compressed-no-mp3-magento-sample-data-1.9.2.4.tar.gz
[2]: https://raw.githubusercontent.com/delegator/compressed-magento-sample-data/master/compressed-no-mp3-magento-sample-data-1.9.2.4.tar.bz2
