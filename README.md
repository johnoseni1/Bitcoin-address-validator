# bitcoin-address-validator

Functions for working with bitcoin address validation and other more functions that you need will be logged out

## install ##

```
npm install bitcoin-address
```

## API ##

### validate (address [, type]) ###

> returns true if the address (string) is a valid bitcoin address
> optionally, you can specify 'prod' or 'testnet' for the type to limit validation that that subset of addresses

### get_address_type (address) ###

> returns address type if valid base58 address, otherwise null