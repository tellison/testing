Defined by https://nvlpubs.nist.gov/nistpubs/Legacy/IR/nistir7695.pdf

Example
`cpe:2.3:a:eclipse:temurin:17.0.8:*:*:*:*:*:*:*`

| Field | Value |
| ----- | ----- |
| URL | cpe:2.3 |
| Part | a |
| Vendor | eclipse |
| Product | temurin |
| Version | 17.0.8 |
| Update | * |
| Edition | * |
| Langauge | * |
| SW Edition | * |
| Target SW | * |
| Target HW | * |
| Other | * |

Example
`cpe:2.3:a:eclipse:temurin:1.8.0:u382:*:*:*:*:*:*`

| Field | Value |
| ----- | ----- |
| URL | cpe:2.3 |
| Part | a |
| Vendor | eclipse |
| Product | temurin |
| Version | 1.8.0 |
| Update | u382 |
| Edition | * |
| Langauge | * |
| SW Edition | * |
| Target SW | * |
| Target HW | * |
| Other | * |


Dictionary definitions defined by http://csrc.nist.gov/publications/nistir/ir7697/NISTIR-7697-CPE-Dictionary.pdf

```xml
  <cpe-item name="cpe:/a:eclipse:temurin:17.0.8">
    <title xml:lang="en-US">Eclipse Temurin 17.0.8+7</title>
    <references>
      <reference href="https://github.com/adoptium/temurin17-binaries/releases/tag/jdk-17.0.8%2B7">VERSION</reference>
      <reference href="https://www.adoptium.net/temurin">WEBSITE</reference>
      <reference href="https://www.eclipse.org/">VENDOR</reference>
    </references>
    <cpe-23:cpe23-item name="cpe:2.3:a:eclipse:temurin:17.0.8:*:*:*:*:*:*:*"/>
  </cpe-item>
```


Building code:

Version

OpenJDK version, e.g. "17.0.8.1+1"
```
curl -X 'GET' 'https://api.adoptium.net/v3/assets/latest/17/hotspotarchitecture=x64&image_type=jdk&os=linux&vendor=eclipse' -H 'accept: application/json' | jq '.[0].version.openjdk_version'
```


