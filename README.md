# EP-1: The mempool search JSON RPC call to ethnode

## Overview

### Usecases

### Context

### Technical analysis
Includes EP-0 bugfixes.

### DOD

### Estimated time

### How to test

### How to deploy

## Usage

## Notes

> [!IMPORTANT]
> Copy the next files to ethnode sourcecode and build ```geth``` as usual:
> - ```./core/txpool/blobpool/blobpool.go```
> - ```./core/txpool/legacypool/legacypool.go```
> - ```./core/txpool/legacypool/list.go```
> - ```./core/txpool/subpool.go```
> - ```./core/txpool/txpool.go```
> - ```./eth/api_backend.go```
> - ```./internal/ethapi/api.go```
> - ```./internal/ethapi/backend.go```
> - ```./internal/web3ext/web3ext.go```
> - ```./les/api_backend.go```
> - ```./light/txpool.go```

> [!IMPORTANT]
> Compare files! Only EP-1 and EP-0 rows are needed!

> [!NOTE]
> See ```// EP-0``` and ```// EP-1``` lines in the sourcecode.

> [!NOTE]
> Based on ethnode release Mawinor (v1.12.2) (https://github.com/ethereum/go-ethereum/releases/tag/v1.12.2) commit bed8460.

> [!NOTE]
> Version EP-1b is available for BSC node: https://github.com/olegasivakov/ep-1b
