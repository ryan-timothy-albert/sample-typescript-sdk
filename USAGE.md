<!-- Start SDK Example Usage [usage] -->
```typescript
import { PetSDK } from "petsdk";

const petSDK = new PetSDK();

async function run() {
    const result = await petSDK.pets.listPets(21453);

    // Handle the result
    console.log(result);
}

run();

```
<!-- End SDK Example Usage [usage] -->