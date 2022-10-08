## 1. Install Dependencies

`npm install`

## 2. Put recipient address

```javascript
  nonce: 4, // you will need to change this!
  gasLimit: '0x5208',
  maxPriorityFeePerGas: '0x3b9aca00',
  maxFeePerGas: '0x3b9acaff',
  to: '', // choose someone to send some ETH to! <- here !
  value: '0x5af3107a4000', // .0001 ether
  chainId: '0x05', // goerli chain id
  type: '0x02', // eip 1559
```

## 3. Run script

`node signTransaction.js`
