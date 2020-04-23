# ChainerCorp application

Application for testing network load with logging.

## Getting Started

Download latest version from 
https://chainercorp.com/app/latest

or using command line 
```
 sudo apt update
 sudo apt upgrade -y
 sudo apt install chappce
 ```
### Prerequisites

You need to have installed __Python3__

```
sudo apt update
sudo apt install software-properties-common
sudo add-apt-repository ppa:deadsnakes/ppa
sudo apt install python3.7
```
You can check version with
```
python3.7 --version
```
### Installing

After installation you need to configure app settings


```
sudo chappce --config
```
if you need detailed help try

```
chappce man
```
for complete manual and help




## Running the tests

Load application and use log directory for accessing logs
To see real time statistics use
```
chappce -f monitor
```

### Troubleshooting

If you face any difficulties you can refer to our [documentation](https://chainercorp.com/app/docs/)

And check our [__forums__](https://chainercorp.com/forums)

## Deployment

To deploy this app in Azure AWS GCC or as Docker image refer to [deploy page](https://chainercorp.com/app/deploy)


## Built With

* [Python3.7](https://www.python.org/downloads/release/python-370/) - Coding language used
* [Maven](https://maven.apache.org/) - Dependency Management
* [ROME](https://rometools.github.io/rome/) - Used to generate RSS Feeds

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [GIT](https://git-scm.com/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Authors

* **Konstantin Bezruchenkov** - *Initial work* - [chainerenator](https://github.com/chainerenator)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Last words

* This is alpha version
* No rights reserved

