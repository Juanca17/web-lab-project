# Virtual House

A furniture e-commerce built with Go, that enables users to see 3D models of the selling items.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

What things you need to install the software and how to install them

Install Ponzu CMS
```
go get -u -v github.com/ponzu-cms/ponzu/...
```
* Make sure that you can execute `go get` scripts in your globally, by exporting **PATH=$GOPATH/bin** in your *~.bash_profile*

Install Hugo
```
brew install hugo
```


### Installing

Ponzu CMS
```
cd backend/
ponzu build
ponzu run --dev-https
```

Hugo
```
cd frontend/
hugo server
```


## Built With

* [Go](https://golang.org/) - The open source programming language
* [Ponzu](https://docs.ponzu-cms.org/) - The open source HTTP server framework and CMS.
* [Hugo](https://gohugo.io/) - The framework to build static websites


## Authors

* **Juan Carlos Sánchez**
* **Ekaterina Chumakova**
* **Germán Treviño**


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details
