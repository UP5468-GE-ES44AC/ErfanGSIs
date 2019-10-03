##Modified for wayne,do not use this tool to port for other device!##

## Requirements
    Linux or Mac

## How to use

### Download tools
```
git clone --recurse-submodules https://github.com/UP5468-GE-ES44AC/ErfanGSIs.git
cd ErfanGSIs
```

### For setting up requirements
    bash setup.sh

### Generating GSI from stock firmware URL
Example: for making Pixel of Pixel2XL firmware, you can use this command
```
./url2GSI.sh https://dl.google.com/dl/android/aosp/taimen-ota-qp1a.190711.020-4757f073.zip Pixel
```
check url2GSI.sh for more info

*Note:Larger RAM machine will increase success rate of output GSIs.
