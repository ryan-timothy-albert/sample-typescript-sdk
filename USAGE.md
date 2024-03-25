<!-- Start SDK Example Usage [usage] -->
```typescript
import { PetSDK } from "petsdk";

async function run() {
    const sdk = new PetSDK();

    const limit = 21453;

    const result = await sdk.pets.listPets(limit);

    // Handle the result
    console.log(result);
}

run();

```
<!-- End SDK Example Usage [usage] -->