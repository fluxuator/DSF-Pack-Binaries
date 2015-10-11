#Dune HD System File packer/unpacker

## Installation

In case this package does not work on your system, try compile it from the source from `/src` directory

### Packagist

This package can be found on Packagist and installed with Composer.

Require the package with:

```
composer.phar require fluxuator/dsf-pack
```

The binary will then be located at:

`vendor/fluxuator/dsf_pack/bin/amd64/dsf_pack`

Also a symlink will be created in your configured bin/ folder, for example:

`vendor/bin/dsf_pack`


## Usage:

#### Decode DSF

```
$ bin/amd64/dsf_pack -d dune_service_test.dsf -o output_file.gz
```
#### Encode DSF

```
$ bin/amd64/dsf_pack -e your_packed_script.gz -o dune_service_test.dsf
```

#### Options
```
  -h          : display usage help (this output)
  -d filename : decode .dsf to outfile.gz
  -e filename : encode infile.gz to .dsf
  -o filename : specify different output filename
  -c filename : compare encode with file
  -v          : verbose it up!
```
