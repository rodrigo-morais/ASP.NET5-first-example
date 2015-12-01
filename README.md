# First example of ASP.NET 5

## Installation

To install ASP.NET 5 in Mac OS X:

First step is to install the DNVM:

```sh
$ curl -sSL https://raw.githubusercontent.com/aspnet/Home/dev/dnvminstall.sh | DNX_BRANCH=dev sh && source ~/.dnx/dnvm/dnvm.sh
```

Second step is to install DNX for .NET Core:

```sh
$ dnvm upgrade -r coreclr
```

## Run

To run the example is necessary to restore the dependencies:

```sh
$ dnu restore
```

After all dependencies are updated, is possible to execute the application:

```sh
$ dnx run
```