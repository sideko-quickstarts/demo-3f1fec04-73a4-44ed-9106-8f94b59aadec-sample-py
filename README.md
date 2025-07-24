
# Swagger Petstore - OpenAPI 3.0 Python SDK

## Overview
This is a sample Pet Store Server based on the OpenAPI 3.0 specification.  You can find out more about
Swagger at [https://swagger.io](https://swagger.io). In the third iteration of the pet store, we've switched to the design first approach!
You can now help us improve the API whether it's by making changes to the definition itself or to the code.
That way, with time, we can improve the API in general, and expose some of the new features in OAS3.

Some useful links:
- [The Pet Store repository](https://github.com/swagger-api/swagger-petstore)
- [The source API definition for the Pet Store](https://github.com/swagger-api/swagger-petstore/blob/master/src/main/resources/openapi.yaml)

#### Synchronous Client

```python
from os import getenv
from sample_py import Client

client = Client(api_key=getenv("API_KEY"))
```

#### Asynchronous Client

```python
from os import getenv
from sample_py import AsyncClient

client = AsyncClient(api_key=getenv("API_KEY"))
```

## Module Documentation and Snippets

### [pet](sample_py/resources/pet/README.md)

* [create](sample_py/resources/pet/README.md#create) - Add a new pet to the store.
* [delete](sample_py/resources/pet/README.md#delete) - Deletes a pet.
* [find_by_status](sample_py/resources/pet/README.md#find_by_status) - Finds Pets by status.
* [get](sample_py/resources/pet/README.md#get) - Find pet by ID.
* [update](sample_py/resources/pet/README.md#update) - Update an existing pet.
* [upload_image](sample_py/resources/pet/README.md#upload_image) - Uploads an image.

### [store.order](sample_py/resources/store/order/README.md)

* [create](sample_py/resources/store/order/README.md#create) - Place an order for a pet.
* [delete](sample_py/resources/store/order/README.md#delete) - Delete purchase order by identifier.
* [get](sample_py/resources/store/order/README.md#get) - Find purchase order by ID.

<!-- MODULE DOCS END -->
