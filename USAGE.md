<!-- Start SDK Example Usage [usage] -->
```typescript
import { PetSDK } from "petsdk";

const petSDK = new PetSDK();

async function run() {
    const limit = 21453;

    const result = await petSDK.pets.listPets(limit);

    // Handle the result
    console.log(result);
}

run();

```
<!-- End SDK Example Usage [usage] -->