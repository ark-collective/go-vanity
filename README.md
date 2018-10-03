## Go Vanity Script

<p align="center">
    <img src="https://github.com/ark-collective/go-vanity/blob/master/banner.png" />
</p>

### Install dep

Follow the instructions [here](https://github.com/golang/dep#installation)

### Install Dependencies

```
dep ensure
```

### Run Vanity Script

```
go run vanity.go -prefix ALEX -entropy 128 -address-format 23 -threads 100 -wif 170 -c 1 -case-insensitive
go run vanity.go -p ALEX -e 128 -a 23 -t 100 -w 170 -c 1 -i
```
