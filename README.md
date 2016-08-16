# our-partner-client
The Andremyid Our Partner Client package.

## Installation

* Add the following to your `Composer JSON` file
```
"andremyid/our-partner-client": "0.0.x-dev"
```
* Run Composer
```
$ composer update
```
* Add the following to 'Andremyid/Framework-Core' => 'ServiceProvider'
```
Andremyid\OurPartnerClient\OurPartnerClientServiceProvider
```
* Run the migration

Copy from database migrate manually.
```
// first, optional
$ composer dump-autoload
// and then
$ php andre migrate
```
## Usage

### Extending
