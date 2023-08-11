# Xentral API Specifications

This repository contains the specification of the [Xentral API](https://developer.xentral.com/reference/intro).

## OpenAPI 3.0 Spec

The file `xentral-api/xentral-api.openapi-3.0.0.json` contains an [OpenAPI 3.0](https://spec.openapis.org/oas/v3.0.0.html) collection of the Xentral API.

## Postman Collection

The file `xentral-api/xentral-api.postman_collecion.json` contains a [Postman 2.1 collection](https://www.postman.com/collection/) of the Xentral API.

## Standard API Postman Collection

The file `xentral-api/standard-xentral-api.postman_collection.json contains a Postman 2.1 collection of the Standard Xentral API.n.json` contains a [Postman 2.1 collection](https://www.postman.com/collection/) of the Standard Xentral API.

## New API

## Documentation for API Endpoints

All URIs are relative to _https://.xentral.biz_, but will link to the `.http` file that contains the endpoint definition

| Method                                   | HTTP request                                                                       | Description                                               |
| ---------------------------------------- | ---------------------------------------------------------------------------------- | --------------------------------------------------------- |
| [**CreditNoteBalance**]                  | **Get** /api/creditNotes/{id}/balance                                              | View Credit Note Balance                                  |
| [**CreditNoteCreate**]                   | **Post** /api/creditNotes                                                          | Create credit note                                        |
| [**CreditNoteCreatePositions**]          | **Post** /api/creditNotes/{id}/positions                                           | [ALPHA] Create Positions for Credit note                  |
| [**CreditNoteDelete**]                   | **Delete** /api/creditNotes/{id}                                                   | [ALPHA] Delete single credit note                         |
| [**CreditNoteDeletePosition**]           | **Delete** /api/creditNotes/{id}/positions/{positionId}                            | [ALPHA] Delete Position from Credit Note                  |
| [**CreditNoteDocumentsView**]            | **Get** /api/creditNotes/{id}/documents                                            | [BETA] View related documents for credit note             |
| [**CreditNoteList**]                     | **Get** /api/creditNotes                                                           | List credit notes                                         |
| [**CreditNoteUpdate**]                   | **Patch** /api/creditNotes/{id}                                                    | [BETA] Update single credit note                          |
| [**CreditNoteUpdatePositions**]          | **Patch** /api/creditNotes/{id}/positions                                          | [ALPHA] Update Positions for Credit Note                  |
| [**CreditNoteView**]                     | **Get** /api/creditNotes/{id}                                                      | [ALPHA] View credit note                                  |
| [**CreditNoteTagList**]                  | **Get** /api/creditNotesTags                                                       | List Credit Notes tags                                    |
| [**CustomerCreate**]                     | **Post** /api/customers                                                            | Create customer                                           |
| [**CustomerDelete**]                     | **Delete** /api/customers/{id}                                                     | Delete customer                                           |
| [**CustomerList**]                       | **Get** /api/customers                                                             | List customer                                             |
| [**CustomerUpdate**]                     | **Patch** /api/customers/{id}                                                      | Update single Customer                                    |
| [**CustomerUpdateMultiple**]             | **Patch** /api/customers                                                           | Update multiple Customers                                 |
| [**CustomerView**]                       | **Get** /api/customers/{id}                                                        | View customer                                             |
| [**CustomerTagList**]                    | **Get** /api/customersTags                                                         | List customers tags                                       |
| [**DeliveryNoteList**]                   | **Get** /api/deliveryNotes                                                         | [BETA] Delivery note list                                 |
| [**DeliveryTermsList**]                  | **Get** /api/deliveryTerms                                                         | List Delivery Terms                                       |
| [**EmployeeList**]                       | **Get** /api/employees                                                             | List employees                                            |
| [**ExternalReferenceCreate**]            | **Post** /api/products/{id}/externalReferences                                     | [BETA] Create new external references for a given Product |
| [**ExternalReferenceDeleteMultiple**]    | **Delete** /api/products/{id}/externalReferences                                   | [BETA] Delete external references of a given Product      |
| [**ExternalReferenceList**]              | **Get** /api/products/{id}/externalReferences                                      | [BETA] List external references for given Product         |
| [**ExternalReferenceUpdateMultiple**]    | **Patch** /api/products/{id}/externalReferences                                    | [BETA] Update external references for a given Product     |
| [**ExternalReferenceTargetList**]        | **Get** /api/externalReferenceTargets                                              | [BETA] List External Reference Targets                    |
| [**InvoiceBalance**]                     | **Get** /api/invoices/{id}/balance                                                 | View Invoice Balance                                      |
| [**InvoiceCreate**]                      | **Post** /api/invoices                                                             | Create invoice                                            |
| [**InvoiceCreatePositions**]             | **Post** /api/invoices/{id}/positions                                              | [ALPHA] Create Positions for Invoice                      |
| [**InvoiceDelete**]                      | **Delete** /api/invoices/{id}                                                      | [ALPHA] Delete single invoice                             |
| [**InvoiceDeletePosition**]              | **Delete** /api/invoices/{id}/positions/{positionId}                               | [ALPHA] Delete Position from Invoice                      |
| [**InvoiceDocumentsView**]               | **Get** /api/invoices/{id}/documents                                               | [BETA] View related documents for invoice                 |
| [**InvoiceList**]                        | **Get** /api/invoices                                                              | List invoices                                             |
| [**InvoiceSend**]                        | **Patch** /api/invoices/{id}/send                                                  | [BETA] Send invoice                                       |
| [**InvoiceStatus**]                      | **Patch** /api/invoices/{id}/status                                                | [BETA] Update status for single invoice                   |
| [**InvoiceUpdate**]                      | **Patch** /api/invoices/{id}                                                       | [BETA] Update single invoice                              |
| [**InvoiceView**]                        | **Get** /api/invoices/{id}                                                         | View invoice                                              |
| [**InvoiceTagList**]                     | **Get** /api/invoicesTags                                                          | List Invoice tags                                         |
| [**LiabilityList**]                      | **Get** /api/liabilities                                                           | List Liability                                            |
| [**LiabilityView**]                      | **Get** /api/liabilities/{id}                                                      | [ALPHA] View liability                                    |
| [**PaymentMethodList**]                  | **Get** /api/paymentMethods                                                        | [BETA] Payment method list                                |
| [**CashCountAdd**]                       | **Post** /api/posCashCount/actions/add                                             | [BETA] Add cash count entry                               |
| [**CashRegisterBalance**]                | **Get** /api/cashRegisters/{id}/balance                                            | [BETA] Cash Register balance                              |
| [**CashierList**]                        | **Get** /api/cashiers                                                              | [BETA] Cashier list                                       |
| [**CashierPinCheck**]                    | **Post** /api/cashiers/{id}/pinCheck                                               | [BETA] Cashier PIN check                                  |
| [**JournalAdd**]                         | **Post** /api/posJournals/actions/add                                              | [BETA] Add journal entry                                  |
| [**ProductCreate**]                      | **Post** /api/products                                                             | Create new product                                        |
| [**ProductCreateParts**]                 | **Post** /api/products/{id}/parts                                                  | Create new parts for product                              |
| [**ProductDelete**]                      | **Delete** /api/products/{id}                                                      | Delete product                                            |
| [**ProductDeleteMultiple**]              | **Delete** /api/products                                                           | Delete multiple products                                  |
| [**ProductDeleteParts**]                 | **Delete** /api/products/{id}/parts                                                | Deletes parts of a product                                |
| [**ProductList**]                        | **Get** /api/products                                                              | List products                                             |
| [**ProductListMedia**]                   | **Get** /api/products/{id}/media                                                   | [ALPHA] View media                                        |
| [**ProductListParts**]                   | **Get** /api/products/{id}/parts                                                   | View parts                                                |
| [**ProductListProductionsPositions**]    | **Get** /api/products/{id}/productionsPositions                                    | View productions positions                                |
| [**ProductListProperties**]              | **Get** /api/products/{id}/properties                                              | View properties                                           |
| [**ProductListPurchaseOrdersPositions**] | **Get** /api/products/{id}/purchaseOrdersPositions                                 | View purchase orders positions                            |
| [**ProductListPurchasePrices**]          | **Get** /api/products/{id}/purchasePrices                                          | View purchase prices                                      |
| [**ProductListReservations**]            | **Get** /api/products/{id}/reservations                                            | View reservations                                         |
| [**ProductListSalesOrdersPositions**]    | **Get** /api/products/{id}/salesOrdersPositions                                    | View sales orders positions                               |
| [**ProductListSalesPrices**]             | **Get** /api/products/{id}/salesPrices                                             | View sales prices                                         |
| [**ProductStorageLocations**]            | **Get** /api/products/{id}/storageLocations                                        | View storage locations                                    |
| [**ProductUpdate**]                      | **Patch** /api/products/{id}                                                       | Update product                                            |
| [**ProductUpdateMultiple**]              | **Patch** /api/products                                                            | Update multiple products                                  |
| [**ProductUpdateParts**]                 | **Patch** /api/products/{id}/parts                                                 | Update parts of a product                                 |
| [**ProductUpdateProperties**]            | **Patch** /api/products/{id}/properties                                            | Update properties                                         |
| [**ProductView**]                        | **Get** /api/products/{id}                                                         | View Product                                              |
| [**ProductCategoryList**]                | **Get** /api/productsCategories                                                    | List products categories                                  |
| [**ProductMediaCreate**]                 | **Post** /api/productMedia                                                         | [BETA] Create product media                               |
| [**ProductMediaCreateVersion**]          | **Post** /api/productMedia/{id}/versions                                           | [BETA] Create product media version                       |
| [**ProductMediaDeleteMultiple**]         | **Delete** /api/productMedia                                                       | [BETA] Delete multiple product media                      |
| [**ProductMediaDeleteVersion**]          | **Delete** /api/productMedia/{id}/versions/{version}                               | [BETA] Delete product media version                       |
| [**ProductMediaList**]                   | **Get** /api/productMedia                                                          | [BETA] List product media                                 |
| [**ProductMediaUpdateMultiple**]         | **Patch** /api/productMedia                                                        | [BETA] Update multiple product media                      |
| [**ProductMediaUpdateVersion**]          | **Patch** /api/productMedia/{id}/versions/{version}                                | [ALPHA] Updates product media version                     |
| [**ProductMediaView**]                   | **Get** /api/productMedia/{id}                                                     | [BETA] View product media                                 |
| [**ProductMediaViewVersion**]            | **Get** /api/productMedia/{id}/versions/{version}                                  | [BETA] View product media version                         |
| [**ProductPropertyCreate**]              | **Post** /api/productsProperties                                                   | Create products properties                                |
| [**ProductPropertyDeleteMultiple**]      | **Delete** /api/productsProperties                                                 | Delete multiple products properties                       |
| [**ProductPropertyList**]                | **Get** /api/productsProperties                                                    | List products properties                                  |
| [**ProductPropertyUpdateMultiple**]      | **Patch** /api/productsProperties                                                  | Update multiple products properties                       |
| [**ProductTagList**]                     | **Get** /api/productsTags                                                          | List products tags                                        |
| [**PurchasePriceCreate**]                | **Post** /api/purchasePrices                                                       | Create purchase price                                     |
| [**PurchasePriceDelete**]                | **Delete** /api/purchasePrices/{id}                                                | Delete purchase price                                     |
| [**PurchasePriceList**]                  | **Get** /api/purchasePrices                                                        | List purchase prices                                      |
| [**PurchasePriceUpdateMultiple**]        | **Patch** /api/purchasePrices                                                      | Update multiple purchase prices                           |
| [**PurchasePriceView**]                  | **Get** /api/purchasePrices/{id}                                                   | View purchase price                                       |
| [**ReturnCreate**]                       | **Post** /api/returns                                                              | [BETA] Create a return                                    |
| [**ReturnList**]                         | **Get** /api/returns                                                               | [BETA] List returns                                       |
| [**ReturnView**]                         | **Get** /api/returns/{id}                                                          | [BETA] View return                                        |
| [**ReturnReasonList**]                   | **Get** /api/returnReasons                                                         | [BETA] List of return reasons                             |
| [**SalesOrderActionsDispatch**]          | **Post** /api/salesOrders/{id}/actions/dispatch                                    | [BETA] Dispatch a released sales order                    |
| [**SalesOrderImport**]                   | **Post** /api/salesOrders/actions/import                                           | [BETA] Import sales order                                 |
| [**SalesOrderList**]                     | **Get** /api/salesOrders                                                           | [BETA] List sales orders                                  |
| [**SalesOrderView**]                     | **Get** /api/salesOrders/{id}                                                      | [BETA] View sale order                                    |
| [**SalesPriceCreate**]                   | **Post** /api/salesPrices                                                          | Create sales price                                        |
| [**SalesPriceDelete**]                   | **Delete** /api/salesPrices/{id}                                                   | Delete sales price                                        |
| [**SalesPriceList**]                     | **Get** /api/salesPrices                                                           | List sales prices                                         |
| [**SalesPriceUpdateMultiple**]           | **Patch** /api/salesPrices                                                         | Update multiple sales prices                              |
| [**SalesPriceView**]                     | **Get** /api/salesPrices/{id}                                                      | View sales price                                          |
| [**ShippingMethodList**]                 | **Get** /api/shippingMethods                                                       | List shipping methods                                     |
| [**SupplierDelete**]                     | **Delete** /api/suppliers/{id}                                                     | Delete supplier                                           |
| [**SupplierList**]                       | **Get** /api/suppliers                                                             | List suppliers                                            |
| [**SupplierUpdate**]                     | **Patch** /api/suppliers/{id}                                                      | Update single Supplier                                    |
| [**SupplierUpdateMultiple**]             | **Patch** /api/suppliers                                                           | Update multiple suppliers                                 |
| [**SupplierView**]                       | **Get** /api/suppliers/{id}                                                        | View supplier                                             |
| [**SupplierTagList**]                    | **Get** /api/suppliersTags                                                         | List suppliers tags                                       |
| [**UserCreate**]                         | **Post** /api/users                                                                | Create user                                               |
| [**UserDelete**]                         | **Delete** /api/users/{id}                                                         | Delete single user                                        |
| [**UserList**]                           | **Get** /api/users                                                                 | List users                                                |
| [**UserPermissionView**]                 | **Get** /api/users/{id}/permissions                                                | View user&#39;s permissions                               |
| [**UserUpdate**]                         | **Patch** /api/users/{id}                                                          | Update user                                               |
| [**UserView**]                           | **Get** /api/users/{id}                                                            | View user                                                 |
| [**WarehouseList**]                      | **Get** /api/warehouses/{warehouseId}/storageLocations/{storageLocationId}/items   | [BETA] Storage item list                                  |
| [**WarehouseRetrieveItem**]              | **Patch** /api/warehouses/{warehouseId}/storageLocations/{storageLocationId}/items | Retrieves item from Storage Location                      |
| [**WarehouseStockItem**]                 | **Post** /api/warehouses/{warehouseId}/storageLocations/{storageLocationId}/items  | Add item to Storage Location                              |

## Contact

For questions or remarks about the API documentation or this repository send an email to <api@xentral.com>
