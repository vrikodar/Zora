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

### Specifying File containing Networks in CIDR or Single IP addresses
```bash
$ ./zora --file /path/to/file.txt
```

Note: The File must contain only one network at each line

### with API or Without API

**with API, `Note that this will look for API key in api.txt File in current Directory, reads only the very First line!`**

[Get Your API Key](https://ipgeolocation.io/signup.html)
```bash
$ ./zora --file cidr_networks.txt --api=1
```
**without API**

Note: The Info Found without using API might not be accurate and detailed as the API ones
```bash
$ ./zora --file cidr_networks.txt --api=0
```

## Local Storage of Data

**Note**: Only the Data Found using API is stored locally in the Data Directory in `JSON` Format

*whenever you rerun the program, it also checks for the presence of corresponding json in the data directory and if its found the results are displayed from the local storage*

## Demo

![](https://github.com/SxNade/Zora/blob/main/data/zora.gif)

# Future Updates 🕒

**Note:** A Major update of utilizing online APIs for free / without any key etc.. will be added soon
