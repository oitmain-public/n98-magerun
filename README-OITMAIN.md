## How to compile
 
`build.sh` will compile the stable branch by default. add `--changes` option to compile the source

````bash
# Install the composer development packages
composer update --dev

# Build
./build.sh --changes && chmod +x n98-magerun.phar 
````