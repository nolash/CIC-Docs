# Add new tokens to reserve

Author: Will Ruddick
Version: 0.0.1

## Rationale

## Before

We have a virtual token right now as the reserve. 

## After

We would need to be able to mint tokens and the reserve outside of the bonding curve.

the idea would be to keep the price 1:1 with reserve and increase both reserve and supply (off the curve)

## Implementation

* return ownership of the token to a person (not the converter)
* mint more tokens (off the curve)'
* give ownership back to the converter
* add more virtual reserve to the converter

## Testing

## Changelog

* 0.1: Created initial stub
