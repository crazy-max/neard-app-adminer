This a sub-repo of [Neard project](https://github.com/crazy-max/neard) involving Adminer app bundles.

## Installation

* Download and install [Neard](https://github.com/crazy-max/neard).
* If you already have installed Neard, stop it.
* Download [an Adminer bundle](#download).
* Extract archive in `neard\apps\adminer\`. Directory structure example :

```
[-] neard
 | [-] apps
 |  | [-] adminer 
 |  |  | [-] adminer4.1.0
 |  |     | neard.conf
 |  |  | [-] adminer4.2.4
 |  |     | neard.conf
 ```

* Edit the `neard.conf` file and replace the key `adminerVersion` with the correct version.
* Edit the `alias/adminer.conf` file and replace the lines with the correct version. 
* Start Neard.

## Download

![](https://raw.github.com/crazy-max/neard-app-adminer/master/img/star-20160403.png) : Default bundle on Neard.

|                     | Adminer release date | Neard release | Download |
| --------------------|:--------------------:|:-------------:|:--------:|
| **Adminer 4.1.0**   | 2014/04/18 | [r1](https://github.com/crazy-max/neard-app-adminer/releases/tag/r1) | [neard-adminer-4.1.0-r1.zip](https://github.com/crazy-max/neard-app-adminer/releases/download/r1/neard-adminer-4.1.0-r1.zip) |
| **Adminer 4.2.4** ![](https://raw.github.com/crazy-max/neard-app-adminer/master/img/star-20160403.png) | 2016/02/06 | [r1](https://github.com/crazy-max/neard-app-adminer/releases/tag/r1) | [neard-adminer-4.2.4-r1.zip](https://github.com/crazy-max/neard-app-adminer/releases/download/r1/neard-adminer-4.2.4-r1.zip) |

## Sources

* https://www.adminer.org/
* https://sourceforge.net/projects/adminer/files/Adminer/
* https://github.com/vrana/adminer

## Contribute

If you want to contribute to this bundle and create new bundles, you have to download [neard-dev](https://github.com/crazy-max/neard-dev) in the parent folder of the bundle.
Directory structure example :

```
[-] neard-dev
 | [-] build
 |  |  | build-commons.xml 
[-] neard-app-adminer
 |  | build.xml
```

To create a new bundle :
* Do not forget to increment the `build.release` in the `build.properties` file.
* If you want you can change the `build.path` (default `C:\neard-build`).
* Open a command prompt in your bundle folder and call the Ant target `release` : `ant release`.
* Upload your release on a file hosting system like [Sendspace](https://www.sendspace.com/).
* Create an [issue on Neard repository](https://github.com/crazy-max/neard/issues) to integrate your release.

## Issues

Issues must be reported on [Neard repository](https://github.com/crazy-max/neard/issues).<br />
Please read [Found a bug?](https://github.com/crazy-max/neard#found-a-bug) section before reporting an issue.
