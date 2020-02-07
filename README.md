# exchange-tokenization-android

This SDK enables you to tokenize card data natively from your Android application to our PCI-certified servers.

## Usage

- See [![](https://jitpack.io/v/allsecure-pay/exchange-tokenization-android.svg)](https://jitpack.io/#allsecure-pay/exchange-tokenization-android)
- Javadoc [![](https://javadoc.jitpack.io/v/allsecure-pay/exchange-tokenization-android.svg)](https://javadoc.jitpack.io/#allsecure-pay/exchange-tokenization-android)


## Examples

### Tokenization API
- See Android invocation of [TokenizationApi.java](exchange-tokenization-api/src/main/java/com/exchange/api/tokenization/TokenizationApi.java) in [MainActivity.java](exchange-tokenization-demoapp/src/main/java/com/exchange/tokenizationdemo/MainActivity.java)
- See minimal example in [TestMain.java](exchange-tokenization-api/src/test/java/com/exchange/api/tokenization/TestMain.java)


### DemoApp
- Set appropriate credentials in [secrets.xml](exchange-tokenization-demoapp/src/main/res/values/secrets.xml)
- Start the demo application

## Development

### Requirements
- Java 8 or higher

### Dependencies
- [org.json](https://github.com/stleary/JSON-java) (built-in Android)
- [OkHttp 3.x](http://square.github.io/okhttp/) (built-in Android 4.4 or higher)

### Executing the tests
```
./gradlew test -Dgateway=<TEST_GATEWAY_HOST> -Dtokenization=<TEST_TOKENIZATION_HOST> -Dkey=<TEST_PUBLIC_INTEGRATION_KEY>
```

## License

[LICENSE](LICENSE)

## Changelog

[CHANGELOG.md](CHANGELOG.md)
