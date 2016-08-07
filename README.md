# build
This repository is exists the files for building and testing for docker.  
To build a disposable environment that middleware is included in the cloud and on-premises environment you can run the test. This repository and [DockerHub repository](https://hub.docker.com/u/rankforce/) is in cooperation "Automated Build".

## Usage for build
```shell
$> sudo docker build -t rankforce/ruby-alpine .
```

or

```shell
$> sudo docker pull rankforce/ruby-alpine .
```

## Usage for run
```shell
$> sudo docker run rankforce/ruby-alpine rspec
```
## Dockerfile URL
* [Dockerfile](https://github.com/rankforce/build/blob/master/ruby/Dockerfile)

## License
Licensed under the MIT
http://www.opensource.org/licenses/mit-license.php
