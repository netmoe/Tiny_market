Under the tiny_market project instructions

The clarinet console session whitelist contract-call has a typo posted by codecademy.

error posted - (contract-call .tiny-market set-whitelisted .test-sip009 true)

correct entry should be - (contract-call .tiny-market set-whitelisted .sip009-nft true)

Althought the incorrect entry comes back with a (ok true), when the next entry to list
the NFT for sale is executed, the event emitted is err u2007 as defined in the tiny-market contract file
(define-constant err-asset-contract-not-whitelisted (err u2007))
