# Xentral API Specifications

This repository contains the specification of the [Xentral API](https://developer.xentral.com/reference/intro). 

## OpenAPI 3.1 Spec
The file `xentral-api/xentral-api.openapi-3.1.0.json` contains an [OpenAPI 3.1](https://spec.openapis.org/oas/latest.html) collection of the Xentral API.

## Postman Collection
The file `xentral-api/xentral-api.postman_collecion.json` contains a [Postman 2.1 collection](https://www.postman.com/collection/) of the Xentral API.

## Standard API Postman Collection
The file `xentral-api/standard-xentral-api.postman_collection.json contains a Postman 2.1 collection of the Standard Xentral API.n.json` contains a [Postman 2.1 collection](https://www.postman.com/collection/) of the Standard Xentral API.

## New API

## Documentation for API Endpoints

All URIs are relative to *https://.xentral.biz*, but will link to the `.http` file that contains the endpoint definition

Class | HTTP request | Description
------------ | ------------- | -------------
*CreditNoteApi* | **GET** /api/creditNotes/{id}/balance | View Credit Note Balance
*CreditNoteApi* | **POST** /api/creditNotes | Create credit note
*CreditNoteApi* | **POST** /api/creditNotes/{id}/positions | [ALPHA] Create Positions for Credit note
*CreditNoteApi* | **DELETE** /api/creditNotes/{id} | [ALPHA] Delete single credit note
*CreditNoteApi* | **DELETE** /api/creditNotes/{id}/positions/{positionId} | [ALPHA] Delete Position from Credit Note
*CreditNoteApi* | **GET** /api/creditNotes/{id}/documents | [BETA] View related documents for credit note
*CreditNoteApi* | **GET** /api/creditNotes | List credit notes
*CreditNoteApi* | **PATCH** /api/creditNotes/{id} | [ALPHA] Update single credit note
*CreditNoteApi* | **PATCH** /api/creditNotes/{id}/positions | [ALPHA] Update Positions for Credit Note
*CreditNoteApi* | **GET** /api/creditNotes/{id} | [ALPHA] View credit note
*CreditNoteTagApi* | **GET** /api/creditNotesTags | List Credit Notes tags
*CustomerApi* | **POST** /api/customers | Create customer
*CustomerApi* | **DELETE** /api/customers/{id} | Delete customer
*CustomerApi* | **GET** /api/customers | List customer
*CustomerApi* | **PATCH** /api/customers/{id} | Update single Customer
*CustomerApi* | **PATCH** /api/customers | Update multiple Customers
*CustomerApi* | **GET** /api/customers/{id} | View customer
*CustomerTagApi* | **GET** /api/customersTags | List customers tags
*DeliveryNoteApi* | **GET** /api/deliveryNotes | [BETA] Delivery note list
*EmployeeApi* | **GET** /api/employees | List employees
*ExternalReferenceApi* | **POST** /api/products/{id}/externalReferences | [BETA] Create new external references for a given Product
*ExternalReferenceApi* | **DELETE** /api/products/{id}/externalReferences | [BETA] Delete external references of a given Product
*ExternalReferenceApi* | **GET** /api/products/{id}/externalReferences | [BETA] List external references for given Product
*ExternalReferenceApi* | **PATCH** /api/products/{id}/externalReferences | [BETA] Update external references for a given Product
*ExternalReferenceTargetApi* | **GET** /api/externalReferenceTargets | [BETA] List External Reference Targets
*InvoiceApi* | **GET** /api/invoices/{id}/balance | View Invoice Balance
*InvoiceApi* | **POST** /api/invoices | Create invoice
*InvoiceApi* | **POST** /api/invoices/{id}/positions | [ALPHA] Create Positions for Invoice
*InvoiceApi* | **DELETE** /api/invoices/{id} | [ALPHA] Delete single invoice
*InvoiceApi* | **DELETE** /api/invoices/{id}/positions/{positionId} | [ALPHA] Delete Position from Invoice
*InvoiceApi* | **GET** /api/invoices/{id}/documents | [BETA] View related documents for invoice
*InvoiceApi* | **GET** /api/invoices | List invoices
*InvoiceApi* | **PATCH** /api/invoices/{id}/send | [BETA] Send invoice
*InvoiceApi* | **PATCH** /api/invoices/{id}/status | [BETA] Update status for single invoice
*InvoiceApi* | **PATCH** /api/invoices/{id} | [ALPHA] Update single invoice
*InvoiceApi* | **GET** /api/invoices/{id} | View invoice
*InvoiceTagApi* | **GET** /api/invoicesTags | List Invoice tags
*LiabilityApi* | **GET** /api/liabilities | List Liability
*LiabilityApi* | **GET** /api/liabilities/{id} | [ALPHA] View liability
*POSApi* | **POST** /api/cashiers/{id}/pinCheck | [POST] Cashier PIN check
*ProductApi* | **POST** /api/products | Create new product
*ProductApi* | **DELETE** /api/products/{id} | Delete product
*ProductApi* | **GET** /api/products | List products
*ProductApi* | **GET** /api/products/{id}/media | [ALPHA] View media
*ProductApi* | **GET** /api/products/{id}/parts | View parts
*ProductApi* | **GET** /api/products/{id}/productionsPositions | View productions positions
*ProductApi* | **GET** /api/products/{id}/properties | View properties
*ProductApi* | **GET** /api/products/{id}/purchaseOrdersPositions | View purchase orders positions
*ProductApi* | **GET** /api/products/{id}/purchasePrices | View purchase prices
*ProductApi* | **GET** /api/products/{id}/reservations | View reservations
*ProductApi* | **GET** /api/products/{id}/salesOrdersPositions | View sales orders positions
*ProductApi* | **GET** /api/products/{id}/salesPrices | View sales prices
*ProductApi* | **GET** /api/products/{id}/storageLocations | View storage locations
*ProductApi* | **PATCH** /api/products/{id} | Update product
*ProductApi* | **PATCH** /api/products | Update multiple products
*ProductApi* | **PATCH** /api/products/{id}/properties | Update properties
*ProductApi* | **GET** /api/products/{id} | View Product
*ProductCategoryApi* | **GET** /api/productsCategories | List products categories
*ProductMediaApi* | **POST** /api/productMedia | [ALPHA] Create product media
*ProductMediaApi* | **POST** /api/productMedia/{id}/versions | [ALPHA] Create product media version
*ProductMediaApi* | **DELETE** /api/productMedia/{id} | [ALPHA] Delete product media
*ProductMediaApi* | **DELETE** /api/productMedia/{id}/versions/{versionId} | [ALPHA] Delete product media version
*ProductMediaApi* | **GET** /api/productMedia | [ALPHA] List product media
*ProductMediaApi* | **PATCH** /api/productMedia/{id} | [ALPHA] Update product media
*ProductMediaApi* | **GET** /api/productMedia/{id} | [ALPHA] View product media
*ProductPropertyApi* | **POST** /api/productsProperties | Create products properties
*ProductPropertyApi* | **DELETE** /api/productsProperties | Delete multiple products properties
*ProductPropertyApi* | **GET** /api/productsProperties | List products properties
*ProductPropertyApi* | **PATCH** /api/productsProperties | Update multiple products properties
*ProductTagApi* | **GET** /api/productsTags | List products tags
*PurchasePriceApi* | **POST** /api/purchasePrices | Create purchase price
*PurchasePriceApi* | **DELETE** /api/purchasePrices/{id} | Delete purchase price
*PurchasePriceApi* | **GET** /api/purchasePrices | List purchase prices
*PurchasePriceApi* | **PATCH** /api/purchasePrices | Update multiple purchase prices
*PurchasePriceApi* | **GET** /api/purchasePrices/{id} | View purchase price
*SalesOrderApi* | **POST** /api/salesOrders/importOrder | Import sales order
*SalesOrderApi* | **GET** /api/salesOrders | List sales orders
*SalesOrderApi* | **GET** /api/salesOrders/{id} | View sale order
*SalesPriceApi* | **POST** /api/salesPrices | Create sales price
*SalesPriceApi* | **DELETE** /api/salesPrices/{id} | Delete sales price
*SalesPriceApi* | **GET** /api/salesPrices | List sales prices
*SalesPriceApi* | **PATCH** /api/salesPrices | Update multiple sales prices
*SalesPriceApi* | **GET** /api/salesPrices/{id} | View sales price
*SupplierApi* | **DELETE** /api/suppliers/{id} | Delete supplier
*SupplierApi* | **GET** /api/suppliers | List suppliers
*SupplierApi* | **PATCH** /api/suppliers/{id} | Update single Supplier
*SupplierApi* | **PATCH** /api/suppliers | Update multiple suppliers
*SupplierApi* | **GET** /api/suppliers/{id} | View supplier
*SupplierTagApi* | **GET** /api/suppliersTags | List suppliers tags
*UserApi* | **POST** /api/users | Create user
*UserApi* | **DELETE** /api/users/{id} | Delete single user
*UserApi* | **GET** /api/users | List users
*UserApi* | **GET** /api/users/{id}/permissions | View user's permissions
*UserApi* | **PATCH** /api/users/{id} | Update user
*UserApi* | **GET** /api/users/{id} | View user
*WarehouseApi* | **GET** /api/warehouses/{warehouseId}/storageLocations/{storageLocationId}/items | [BETA] Storage item list
*WarehouseApi* | **PATCH** /api/warehouses/{warehouseId}/storageLocations/{storageLocationId}/items | Retrieves item from Storage Location
*WarehouseApi* | **POST** /api/warehouses/{warehouseId}/storageLocations/{storageLocationId}/items | Add item to Storage Location


## Contact
For questions or remarks about the API documentation or this repository send an email to <api@xentral.com>
