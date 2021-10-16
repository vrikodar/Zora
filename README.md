# Zora

<p align="center">
  <img src="https://github.com/SxNade/Zora/blob/main/zora.png" />
</p>


Zora is a python program that searches for GeoLocation info for given CIDR networks , with options to search with API or without API


## Installing and Running Zora

```bash
$ git clone https://github.com/SxNade/Zora
$ cd Zora
$ chmod +x zora

$ ./zora --help
```

## Zora Options

**Listing Help**
```bash
$ ./zora --help
```

### Specifying File containing Networks in CIDR
```bash
$ ./zora --file /path/to/file.txt
```

### with API or Without API

**with API, `Note that this will look for API key in api.txt File in current Directory`**

[Get Your API Key](https://ipgeolocation.io/signup.html)


```bash
$ ./zora --file --api=1
