# Reference
## Reference
<details><summary><code>client.reference.postV1ReferenceExchangeRatesSync(request) -> PostV1ReferenceExchangeRatesSyncResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.reference().postV1ReferenceExchangeRatesSync(
    PostV1ReferenceExchangeRatesSyncRequest
        .builder()
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**date:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.reference.postV1ReferenceExchangeRatesList(request) -> PostV1ReferenceExchangeRatesListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.reference().postV1ReferenceExchangeRatesList(
    PostV1ReferenceExchangeRatesListRequest
        .builder()
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `Optional<List<PostV1ReferenceExchangeRatesListRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<PostV1ReferenceExchangeRatesListRequestFilterItem>>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.reference.postV1ReferenceExchangeRatesSet(request) -> PostV1ReferenceExchangeRatesSetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.reference().postV1ReferenceExchangeRatesSet(
    PostV1ReferenceExchangeRatesSetRequest
        .builder()
        .currency("currency")
        .date("date")
        .rate("rate")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**currency:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**date:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**rate:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.reference.postV1ReferenceExchangeRatesOverridesList(request) -> PostV1ReferenceExchangeRatesOverridesListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.reference().postV1ReferenceExchangeRatesOverridesList(
    PostV1ReferenceExchangeRatesOverridesListRequest
        .builder()
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `Optional<List<PostV1ReferenceExchangeRatesOverridesListRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<PostV1ReferenceExchangeRatesOverridesListRequestFilterItem>>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.reference.postV1ReferenceExchangeRatesOverridesDelete(request) -> PostV1ReferenceExchangeRatesOverridesDeleteResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.reference().postV1ReferenceExchangeRatesOverridesDelete(
    PostV1ReferenceExchangeRatesOverridesDeleteRequest
        .builder()
        .currency("currency")
        .date("date")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**currency:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**date:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.reference.postV1ReferenceCountriesList(request) -> PostV1ReferenceCountriesListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.reference().postV1ReferenceCountriesList(
    PostV1ReferenceCountriesListRequest
        .builder()
        .build()
);
```
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.reference.postV1ReferenceBanksList(request) -> PostV1ReferenceBanksListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.reference().postV1ReferenceBanksList(
    PostV1ReferenceBanksListRequest
        .builder()
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `Optional<List<PostV1ReferenceBanksListRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<PostV1ReferenceBanksListRequestFilterItem>>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.reference.postV1ReferenceBanksUpsert(request) -> PostV1ReferenceBanksUpsertResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.reference().postV1ReferenceBanksUpsert(
    PostV1ReferenceBanksUpsertRequest
        .builder()
        .countryCode("countryCode")
        .name("name")
        .bic("bic")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**countryCode:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**name:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**bic:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**bankCode:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**isActive:** `Optional<Boolean>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.reference.postV1ReferenceLtRegionsList(request) -> PostV1ReferenceLtRegionsListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.reference().postV1ReferenceLtRegionsList(
    PostV1ReferenceLtRegionsListRequest
        .builder()
        .build()
);
```
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.reference.postV1ReferenceCurrenciesList(request) -> PostV1ReferenceCurrenciesListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.reference().postV1ReferenceCurrenciesList(
    PostV1ReferenceCurrenciesListRequest
        .builder()
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `Optional<List<PostV1ReferenceCurrenciesListRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<PostV1ReferenceCurrenciesListRequestFilterItem>>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.reference.postV1ReferenceVatClassifiersList(request) -> PostV1ReferenceVatClassifiersListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.reference().postV1ReferenceVatClassifiersList(
    PostV1ReferenceVatClassifiersListRequest
        .builder()
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `Optional<List<PostV1ReferenceVatClassifiersListRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<PostV1ReferenceVatClassifiersListRequestFilterItem>>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.reference.postV1ReferenceVatClassifiersUpsert(request) -> PostV1ReferenceVatClassifiersUpsertResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.reference().postV1ReferenceVatClassifiersUpsert(
    PostV1ReferenceVatClassifiersUpsertRequest
        .builder()
        .rows(
            Arrays.asList(
                PostV1ReferenceVatClassifiersUpsertRequestRowsItem
                    .builder()
                    .code("code")
                    .name("name")
                    .build()
            )
        )
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**rows:** `List<PostV1ReferenceVatClassifiersUpsertRequestRowsItem>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.reference.postV1ReferenceEuVatRatesList(request) -> PostV1ReferenceEuVatRatesListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.reference().postV1ReferenceEuVatRatesList(
    PostV1ReferenceEuVatRatesListRequest
        .builder()
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**countryCode:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**date:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.reference.postV1ReferenceVatResolve(request) -> PostV1ReferenceVatResolveResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.reference().postV1ReferenceVatResolve(
    PostV1ReferenceVatResolveRequest
        .builder()
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**partnerId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**customerCountryCode:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**customerIsBusiness:** `Optional<Boolean>` 
    
</dd>
</dl>

<dl>
<dd>

**supplyType:** `Optional<PostV1ReferenceVatResolveRequestSupplyType>` 
    
</dd>
</dl>

<dl>
<dd>

**date:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**belowDistanceSalesThreshold:** `Optional<Boolean>` 
    
</dd>
</dl>

<dl>
<dd>

**facilitatedByMarketplace:** `Optional<Boolean>` 
    
</dd>
</dl>

<dl>
<dd>

**actingAsMarketplace:** `Optional<Boolean>` 
    
</dd>
</dl>

<dl>
<dd>

**sellerEstablishedInEu:** `Optional<Boolean>` 
    
</dd>
</dl>

<dl>
<dd>

**importedConsignmentValueEur:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.reference.postV1ReferenceCnCodesList(request) -> PostV1ReferenceCnCodesListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.reference().postV1ReferenceCnCodesList(
    PostV1ReferenceCnCodesListRequest
        .builder()
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `Optional<List<PostV1ReferenceCnCodesListRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<PostV1ReferenceCnCodesListRequestFilterItem>>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.reference.postV1ReferenceCnCodesUpsert(request) -> PostV1ReferenceCnCodesUpsertResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.reference().postV1ReferenceCnCodesUpsert(
    PostV1ReferenceCnCodesUpsertRequest
        .builder()
        .rows(
            Arrays.asList(
                PostV1ReferenceCnCodesUpsertRequestRowsItem
                    .builder()
                    .code("code")
                    .name("name")
                    .build()
            )
        )
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**rows:** `List<PostV1ReferenceCnCodesUpsertRequestRowsItem>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.reference.postV1ReferenceComplianceVersionsList(request) -> PostV1ReferenceComplianceVersionsListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.reference().postV1ReferenceComplianceVersionsList(
    PostV1ReferenceComplianceVersionsListRequest
        .builder()
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**country:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.reference.postV1ReferenceIntrastatThresholdsList(request) -> PostV1ReferenceIntrastatThresholdsListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.reference().postV1ReferenceIntrastatThresholdsList(
    PostV1ReferenceIntrastatThresholdsListRequest
        .builder()
        .build()
);
```
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.reference.postV1ReferenceUnitsList(request) -> PostV1ReferenceUnitsListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.reference().postV1ReferenceUnitsList(
    PostV1ReferenceUnitsListRequest
        .builder()
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `Optional<List<PostV1ReferenceUnitsListRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<PostV1ReferenceUnitsListRequestFilterItem>>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.reference.postV1ReferenceSeriesCreate(request) -> PostV1ReferenceSeriesCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.reference().postV1ReferenceSeriesCreate(
    PostV1ReferenceSeriesCreateRequest
        .builder()
        .documentType("documentType")
        .year(1000000L)
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**documentType:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**prefix:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**year:** `Long` 
    
</dd>
</dl>

<dl>
<dd>

**startAt:** `Optional<Long>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.reference.postV1ReferenceSeriesList(request) -> PostV1ReferenceSeriesListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.reference().postV1ReferenceSeriesList(
    PostV1ReferenceSeriesListRequest
        .builder()
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `Optional<List<PostV1ReferenceSeriesListRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<PostV1ReferenceSeriesListRequestFilterItem>>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Partners
<details><summary><code>client.partners.postV1PartnersAddressesCreate(request) -> PostV1PartnersAddressesCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.partners().postV1PartnersAddressesCreate(
    PostV1PartnersAddressesCreateRequest
        .builder()
        .partnerId("partnerId")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**type:** `Optional<PostV1PartnersAddressesCreateRequestType>` 
    
</dd>
</dl>

<dl>
<dd>

**street:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**city:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**postalCode:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**countryCode:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**isDefault:** `Optional<Boolean>` 
    
</dd>
</dl>

<dl>
<dd>

**partnerId:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.partners.postV1PartnersAddressesUpdate(request) -> PostV1PartnersAddressesUpdateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.partners().postV1PartnersAddressesUpdate(
    PostV1PartnersAddressesUpdateRequest
        .builder()
        .id("id")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**type:** `Optional<PostV1PartnersAddressesUpdateRequestType>` 
    
</dd>
</dl>

<dl>
<dd>

**street:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**city:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**postalCode:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**countryCode:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**isDefault:** `Optional<Boolean>` 
    
</dd>
</dl>

<dl>
<dd>

**id:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.partners.postV1PartnersAddressesDelete(request) -> PostV1PartnersAddressesDeleteResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.partners().postV1PartnersAddressesDelete(
    PostV1PartnersAddressesDeleteRequest
        .builder()
        .id("id")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.partners.postV1PartnersAddressesList(request) -> PostV1PartnersAddressesListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.partners().postV1PartnersAddressesList(
    PostV1PartnersAddressesListRequest
        .builder()
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `Optional<List<PostV1PartnersAddressesListRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<PostV1PartnersAddressesListRequestFilterItem>>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.partners.postV1PartnersContactsCreate(request) -> PostV1PartnersContactsCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.partners().postV1PartnersContactsCreate(
    PostV1PartnersContactsCreateRequest
        .builder()
        .name("name")
        .partnerId("partnerId")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**name:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**role:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**email:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**phone:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**partnerId:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.partners.postV1PartnersContactsUpdate(request) -> PostV1PartnersContactsUpdateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.partners().postV1PartnersContactsUpdate(
    PostV1PartnersContactsUpdateRequest
        .builder()
        .id("id")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**name:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**role:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**email:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**phone:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**id:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.partners.postV1PartnersContactsDelete(request) -> PostV1PartnersContactsDeleteResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.partners().postV1PartnersContactsDelete(
    PostV1PartnersContactsDeleteRequest
        .builder()
        .id("id")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.partners.postV1PartnersContactsList(request) -> PostV1PartnersContactsListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.partners().postV1PartnersContactsList(
    PostV1PartnersContactsListRequest
        .builder()
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `Optional<List<PostV1PartnersContactsListRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<PostV1PartnersContactsListRequestFilterItem>>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.partners.postV1PartnersBankAccountsCreate(request) -> PostV1PartnersBankAccountsCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.partners().postV1PartnersBankAccountsCreate(
    PostV1PartnersBankAccountsCreateRequest
        .builder()
        .iban("iban")
        .partnerId("partnerId")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**iban:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**bankName:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**bic:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**currency:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**isDefault:** `Optional<Boolean>` 
    
</dd>
</dl>

<dl>
<dd>

**partnerId:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.partners.postV1PartnersBankAccountsUpdate(request) -> PostV1PartnersBankAccountsUpdateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.partners().postV1PartnersBankAccountsUpdate(
    PostV1PartnersBankAccountsUpdateRequest
        .builder()
        .id("id")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**iban:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**bankName:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**bic:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**currency:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**isDefault:** `Optional<Boolean>` 
    
</dd>
</dl>

<dl>
<dd>

**id:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.partners.postV1PartnersBankAccountsDelete(request) -> PostV1PartnersBankAccountsDeleteResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.partners().postV1PartnersBankAccountsDelete(
    PostV1PartnersBankAccountsDeleteRequest
        .builder()
        .id("id")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.partners.postV1PartnersBankAccountsList(request) -> PostV1PartnersBankAccountsListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.partners().postV1PartnersBankAccountsList(
    PostV1PartnersBankAccountsListRequest
        .builder()
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `Optional<List<PostV1PartnersBankAccountsListRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<PostV1PartnersBankAccountsListRequestFilterItem>>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.partners.postV1PartnersValidateVat(request) -> PostV1PartnersValidateVatResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.partners().postV1PartnersValidateVat(
    PostV1PartnersValidateVatRequest
        .builder()
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**vatCode:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**partnerId:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.partners.postV1PartnersCreate(request) -> PostV1PartnersCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.partners().postV1PartnersCreate(
    PostV1PartnersCreateRequest
        .builder()
        .name("name")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**type:** `Optional<PostV1PartnersCreateRequestType>` 
    
</dd>
</dl>

<dl>
<dd>

**name:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**code:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**vatCode:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**peppolId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**email:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**phone:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**selfEmploymentCertNo:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**birthDate:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**isCustomer:** `Optional<Boolean>` 
    
</dd>
</dl>

<dl>
<dd>

**isSupplier:** `Optional<Boolean>` 
    
</dd>
</dl>

<dl>
<dd>

**paymentTermDays:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**creditLimit:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**priceListId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**groupId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**statusId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**address:** `Optional<PostV1PartnersCreateRequestAddress>` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.partners.postV1PartnersFindOrCreate(request) -> PostV1PartnersFindOrCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.partners().postV1PartnersFindOrCreate(
    PostV1PartnersFindOrCreateRequest
        .builder()
        .name("name")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**type:** `Optional<PostV1PartnersFindOrCreateRequestType>` 
    
</dd>
</dl>

<dl>
<dd>

**name:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**code:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**vatCode:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**peppolId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**email:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**phone:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**selfEmploymentCertNo:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**birthDate:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**isCustomer:** `Optional<Boolean>` 
    
</dd>
</dl>

<dl>
<dd>

**isSupplier:** `Optional<Boolean>` 
    
</dd>
</dl>

<dl>
<dd>

**paymentTermDays:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**creditLimit:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**priceListId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**groupId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**statusId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**address:** `Optional<PostV1PartnersFindOrCreateRequestAddress>` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.partners.postV1PartnersGet(request) -> PostV1PartnersGetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.partners().postV1PartnersGet(
    PostV1PartnersGetRequest
        .builder()
        .id("id")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.partners.postV1PartnersUpdate(request) -> PostV1PartnersUpdateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.partners().postV1PartnersUpdate(
    PostV1PartnersUpdateRequest
        .builder()
        .id("id")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**type:** `Optional<PostV1PartnersUpdateRequestType>` 
    
</dd>
</dl>

<dl>
<dd>

**name:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**code:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**vatCode:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**peppolId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**email:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**phone:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**selfEmploymentCertNo:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**birthDate:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**isCustomer:** `Optional<Boolean>` 
    
</dd>
</dl>

<dl>
<dd>

**isSupplier:** `Optional<Boolean>` 
    
</dd>
</dl>

<dl>
<dd>

**paymentTermDays:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**creditLimit:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**priceListId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**groupId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**statusId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**address:** `Optional<PostV1PartnersUpdateRequestAddress>` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.partners.postV1PartnersDelete(request) -> PostV1PartnersDeleteResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.partners().postV1PartnersDelete(
    PostV1PartnersDeleteRequest
        .builder()
        .id("id")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.partners.postV1PartnersList(request) -> PostV1PartnersListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.partners().postV1PartnersList(
    PostV1PartnersListRequest
        .builder()
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `Optional<List<PostV1PartnersListRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<PostV1PartnersListRequestFilterItem>>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.partners.postV1PartnersGroupsCreate(request) -> PostV1PartnersGroupsCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.partners().postV1PartnersGroupsCreate(
    PostV1PartnersGroupsCreateRequest
        .builder()
        .code("code")
        .name("name")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**code:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**name:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.partners.postV1PartnersGroupsUpdate(request) -> PostV1PartnersGroupsUpdateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.partners().postV1PartnersGroupsUpdate(
    PostV1PartnersGroupsUpdateRequest
        .builder()
        .id("id")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**code:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**name:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.partners.postV1PartnersGroupsDelete(request) -> PostV1PartnersGroupsDeleteResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.partners().postV1PartnersGroupsDelete(
    PostV1PartnersGroupsDeleteRequest
        .builder()
        .id("id")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.partners.postV1PartnersGroupsList(request) -> PostV1PartnersGroupsListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.partners().postV1PartnersGroupsList(
    PostV1PartnersGroupsListRequest
        .builder()
        .build()
);
```
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.partners.postV1PartnersStatusesCreate(request) -> PostV1PartnersStatusesCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.partners().postV1PartnersStatusesCreate(
    PostV1PartnersStatusesCreateRequest
        .builder()
        .code("code")
        .name("name")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**code:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**name:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**sortOrder:** `Optional<Long>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.partners.postV1PartnersStatusesUpdate(request) -> PostV1PartnersStatusesUpdateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.partners().postV1PartnersStatusesUpdate(
    PostV1PartnersStatusesUpdateRequest
        .builder()
        .id("id")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**code:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**name:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**sortOrder:** `Optional<Long>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.partners.postV1PartnersStatusesDelete(request) -> PostV1PartnersStatusesDeleteResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.partners().postV1PartnersStatusesDelete(
    PostV1PartnersStatusesDeleteRequest
        .builder()
        .id("id")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.partners.postV1PartnersStatusesList(request) -> PostV1PartnersStatusesListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.partners().postV1PartnersStatusesList(
    PostV1PartnersStatusesListRequest
        .builder()
        .build()
);
```
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.partners.postV1PartnersInquiriesCreate(request) -> PostV1PartnersInquiriesCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.partners().postV1PartnersInquiriesCreate(
    PostV1PartnersInquiriesCreateRequest
        .builder()
        .subject("subject")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**partnerId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**contactName:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**contactEmail:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**contactPhone:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**subject:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**body:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**channel:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**assignedUserId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.partners.postV1PartnersInquiriesUpdate(request) -> PostV1PartnersInquiriesUpdateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.partners().postV1PartnersInquiriesUpdate(
    PostV1PartnersInquiriesUpdateRequest
        .builder()
        .id("id")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**partnerId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**subject:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**body:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**channel:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**status:** `Optional<PostV1PartnersInquiriesUpdateRequestStatus>` 
    
</dd>
</dl>

<dl>
<dd>

**assignedUserId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.partners.postV1PartnersInquiriesGet(request) -> PostV1PartnersInquiriesGetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.partners().postV1PartnersInquiriesGet(
    PostV1PartnersInquiriesGetRequest
        .builder()
        .id("id")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.partners.postV1PartnersInquiriesList(request) -> PostV1PartnersInquiriesListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.partners().postV1PartnersInquiriesList(
    PostV1PartnersInquiriesListRequest
        .builder()
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `Optional<List<PostV1PartnersInquiriesListRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<PostV1PartnersInquiriesListRequestFilterItem>>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.partners.postV1PartnersCreditCheck(request) -> PostV1PartnersCreditCheckResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.partners().postV1PartnersCreditCheck(
    PostV1PartnersCreditCheckRequest
        .builder()
        .partnerId("partnerId")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**partnerId:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**additionalAmount:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Catalog
<details><summary><code>client.catalog.postV1CatalogItemsCreate(request) -> PostV1CatalogItemsCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.catalog().postV1CatalogItemsCreate(
    PostV1CatalogItemsCreateRequest
        .builder()
        .name("name")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**type:** `Optional<PostV1CatalogItemsCreateRequestType>` 
    
</dd>
</dl>

<dl>
<dd>

**name:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**code:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**barcode:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**unit:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**vatClassifierCode:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**vatRatePercent:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**salePriceExclVat:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**purchasePriceExclVat:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**cnCode:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**originCountry:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**netMassKg:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**supplementaryUnit:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**supplementaryQtyPerUnit:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**description:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**groupId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**attributes:** `Optional<Map<String, String>>` 
    
</dd>
</dl>

<dl>
<dd>

**translations:** `Optional<Map<String, PostV1CatalogItemsCreateRequestTranslationsValue>>` 
    
</dd>
</dl>

<dl>
<dd>

**components:** `Optional<List<PostV1CatalogItemsCreateRequestComponentsItem>>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.catalog.postV1CatalogItemsGet(request) -> PostV1CatalogItemsGetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.catalog().postV1CatalogItemsGet(
    PostV1CatalogItemsGetRequest
        .builder()
        .id("id")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.catalog.postV1CatalogItemsUpdate(request) -> PostV1CatalogItemsUpdateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.catalog().postV1CatalogItemsUpdate(
    PostV1CatalogItemsUpdateRequest
        .builder()
        .id("id")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**type:** `Optional<PostV1CatalogItemsUpdateRequestType>` 
    
</dd>
</dl>

<dl>
<dd>

**name:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**code:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**barcode:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**unit:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**vatClassifierCode:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**vatRatePercent:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**salePriceExclVat:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**purchasePriceExclVat:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**cnCode:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**originCountry:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**netMassKg:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**supplementaryUnit:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**supplementaryQtyPerUnit:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**description:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**groupId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**attributes:** `Optional<Map<String, String>>` 
    
</dd>
</dl>

<dl>
<dd>

**translations:** `Optional<Map<String, PostV1CatalogItemsUpdateRequestTranslationsValue>>` 
    
</dd>
</dl>

<dl>
<dd>

**components:** `Optional<List<PostV1CatalogItemsUpdateRequestComponentsItem>>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.catalog.postV1CatalogItemsDelete(request) -> PostV1CatalogItemsDeleteResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.catalog().postV1CatalogItemsDelete(
    PostV1CatalogItemsDeleteRequest
        .builder()
        .id("id")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.catalog.postV1CatalogItemsList(request) -> PostV1CatalogItemsListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.catalog().postV1CatalogItemsList(
    PostV1CatalogItemsListRequest
        .builder()
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `Optional<List<PostV1CatalogItemsListRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<PostV1CatalogItemsListRequestFilterItem>>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.catalog.postV1CatalogItemGroupsCreate(request) -> PostV1CatalogItemGroupsCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.catalog().postV1CatalogItemGroupsCreate(
    PostV1CatalogItemGroupsCreateRequest
        .builder()
        .code("code")
        .name("name")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**code:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**name:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**parentId:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.catalog.postV1CatalogItemGroupsUpdate(request) -> PostV1CatalogItemGroupsUpdateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.catalog().postV1CatalogItemGroupsUpdate(
    PostV1CatalogItemGroupsUpdateRequest
        .builder()
        .id("id")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**code:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**name:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**parentId:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.catalog.postV1CatalogItemGroupsDelete(request) -> PostV1CatalogItemGroupsDeleteResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.catalog().postV1CatalogItemGroupsDelete(
    PostV1CatalogItemGroupsDeleteRequest
        .builder()
        .id("id")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.catalog.postV1CatalogItemGroupsList(request) -> PostV1CatalogItemGroupsListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.catalog().postV1CatalogItemGroupsList(
    PostV1CatalogItemGroupsListRequest
        .builder()
        .build()
);
```
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.catalog.postV1CatalogItemsSuppliersUpsert(request) -> PostV1CatalogItemsSuppliersUpsertResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.catalog().postV1CatalogItemsSuppliersUpsert(
    PostV1CatalogItemsSuppliersUpsertRequest
        .builder()
        .itemId("itemId")
        .partnerId("partnerId")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**itemId:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**partnerId:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**supplierCode:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**purchasePriceExclVat:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**currency:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.catalog.postV1CatalogItemsSuppliersList(request) -> PostV1CatalogItemsSuppliersListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.catalog().postV1CatalogItemsSuppliersList(
    PostV1CatalogItemsSuppliersListRequest
        .builder()
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**itemId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**partnerId:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.catalog.postV1CatalogItemsSuppliersDelete(request) -> PostV1CatalogItemsSuppliersDeleteResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.catalog().postV1CatalogItemsSuppliersDelete(
    PostV1CatalogItemsSuppliersDeleteRequest
        .builder()
        .id("id")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.catalog.postV1CatalogPriceListsCreate(request) -> PostV1CatalogPriceListsCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.catalog().postV1CatalogPriceListsCreate(
    PostV1CatalogPriceListsCreateRequest
        .builder()
        .code("code")
        .name("name")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**code:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**name:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**currency:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**isActive:** `Optional<Boolean>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.catalog.postV1CatalogPriceListsUpdate(request) -> PostV1CatalogPriceListsUpdateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.catalog().postV1CatalogPriceListsUpdate(
    PostV1CatalogPriceListsUpdateRequest
        .builder()
        .id("id")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**code:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**name:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**currency:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**isActive:** `Optional<Boolean>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.catalog.postV1CatalogPriceListsList(request) -> PostV1CatalogPriceListsListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.catalog().postV1CatalogPriceListsList(
    PostV1CatalogPriceListsListRequest
        .builder()
        .build()
);
```
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.catalog.postV1CatalogPriceListsItemsSet(request) -> PostV1CatalogPriceListsItemsSetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.catalog().postV1CatalogPriceListsItemsSet(
    PostV1CatalogPriceListsItemsSetRequest
        .builder()
        .priceListId("priceListId")
        .items(
            Arrays.asList(
                PostV1CatalogPriceListsItemsSetRequestItemsItem
                    .builder()
                    .itemId("itemId")
                    .unitPriceExclVat("unitPriceExclVat")
                    .build()
            )
        )
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**priceListId:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**items:** `List<PostV1CatalogPriceListsItemsSetRequestItemsItem>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.catalog.postV1CatalogPriceListsItemsList(request) -> PostV1CatalogPriceListsItemsListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.catalog().postV1CatalogPriceListsItemsList(
    PostV1CatalogPriceListsItemsListRequest
        .builder()
        .priceListId("priceListId")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**priceListId:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.catalog.postV1CatalogPriceListsItemsDelete(request) -> PostV1CatalogPriceListsItemsDeleteResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.catalog().postV1CatalogPriceListsItemsDelete(
    PostV1CatalogPriceListsItemsDeleteRequest
        .builder()
        .priceListId("priceListId")
        .itemId("itemId")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**priceListId:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**itemId:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Sales
<details><summary><code>client.sales.postV1SalesInvoicesCreate(request) -> PostV1SalesInvoicesCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.sales().postV1SalesInvoicesCreate(
    PostV1SalesInvoicesCreateRequest
        .builder()
        .partnerId("partnerId")
        .lines(
            Arrays.asList(
                PostV1SalesInvoicesCreateRequestLinesItem
                    .builder()
                    .build()
            )
        )
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**partnerId:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**type:** `Optional<PostV1SalesInvoicesCreateRequestType>` 
    
</dd>
</dl>

<dl>
<dd>

**currency:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**issueDate:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**dueDate:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**creditedInvoiceId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**vatScheme:** `Optional<PostV1SalesInvoicesCreateRequestVatScheme>` 
    
</dd>
</dl>

<dl>
<dd>

**vatCountryCode:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**deemedSupplier:** `Optional<Boolean>` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**lines:** `List<PostV1SalesInvoicesCreateRequestLinesItem>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.sales.postV1SalesInvoicesGet(request) -> PostV1SalesInvoicesGetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.sales().postV1SalesInvoicesGet(
    PostV1SalesInvoicesGetRequest
        .builder()
        .id("id")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.sales.postV1SalesInvoicesPdf(request) -> PostV1SalesInvoicesPdfResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.sales().postV1SalesInvoicesPdf(
    PostV1SalesInvoicesPdfRequest
        .builder()
        .id("id")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**locale:** `Optional<PostV1SalesInvoicesPdfRequestLocale>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.sales.postV1SalesInvoicesSend(request) -> PostV1SalesInvoicesSendResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.sales().postV1SalesInvoicesSend(
    PostV1SalesInvoicesSendRequest
        .builder()
        .id("id")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**to:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**locale:** `Optional<PostV1SalesInvoicesSendRequestLocale>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.sales.postV1SalesInvoicesPeppolXml(request) -> PostV1SalesInvoicesPeppolXmlResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.sales().postV1SalesInvoicesPeppolXml(
    PostV1SalesInvoicesPeppolXmlRequest
        .builder()
        .id("id")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.sales.postV1SalesInvoicesPeppolSend(request) -> PostV1SalesInvoicesPeppolSendResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.sales().postV1SalesInvoicesPeppolSend(
    PostV1SalesInvoicesPeppolSendRequest
        .builder()
        .id("id")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.sales.postV1SalesInvoicesUpdate(request) -> PostV1SalesInvoicesUpdateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.sales().postV1SalesInvoicesUpdate(
    PostV1SalesInvoicesUpdateRequest
        .builder()
        .id("id")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**partnerId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**currency:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**issueDate:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**dueDate:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**vatScheme:** `Optional<PostV1SalesInvoicesUpdateRequestVatScheme>` 
    
</dd>
</dl>

<dl>
<dd>

**vatCountryCode:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**deemedSupplier:** `Optional<Boolean>` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**lines:** `Optional<List<PostV1SalesInvoicesUpdateRequestLinesItem>>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.sales.postV1SalesInvoicesDelete(request) -> PostV1SalesInvoicesDeleteResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.sales().postV1SalesInvoicesDelete(
    PostV1SalesInvoicesDeleteRequest
        .builder()
        .id("id")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.sales.postV1SalesInvoicesIssue(request) -> PostV1SalesInvoicesIssueResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.sales().postV1SalesInvoicesIssue(
    PostV1SalesInvoicesIssueRequest
        .builder()
        .id("id")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**series:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**issueDate:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**warehouseId:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.sales.postV1SalesInvoicesApplyAdvance(request) -> PostV1SalesInvoicesApplyAdvanceResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.sales().postV1SalesInvoicesApplyAdvance(
    PostV1SalesInvoicesApplyAdvanceRequest
        .builder()
        .advanceId("advanceId")
        .invoiceId("invoiceId")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**advanceId:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**invoiceId:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**date:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.sales.postV1SalesInvoicesList(request) -> PostV1SalesInvoicesListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.sales().postV1SalesInvoicesList(
    PostV1SalesInvoicesListRequest
        .builder()
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `Optional<List<PostV1SalesInvoicesListRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<PostV1SalesInvoicesListRequestFilterItem>>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.sales.postV1SalesActsCreate(request) -> PostV1SalesActsCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.sales().postV1SalesActsCreate(
    PostV1SalesActsCreateRequest
        .builder()
        .partnerId("partnerId")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**partnerId:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**type:** `Optional<PostV1SalesActsCreateRequestType>` 
    
</dd>
</dl>

<dl>
<dd>

**documentDate:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**saleInvoiceId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**transferredByName:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**transferredByTitle:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**acceptedByName:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**acceptedByTitle:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**series:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**lines:** `Optional<List<PostV1SalesActsCreateRequestLinesItem>>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.sales.postV1SalesActsUpdate(request) -> PostV1SalesActsUpdateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.sales().postV1SalesActsUpdate(
    PostV1SalesActsUpdateRequest
        .builder()
        .id("id")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**partnerId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**type:** `Optional<PostV1SalesActsUpdateRequestType>` 
    
</dd>
</dl>

<dl>
<dd>

**documentDate:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**saleInvoiceId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**transferredByName:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**transferredByTitle:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**acceptedByName:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**acceptedByTitle:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**series:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**lines:** `Optional<List<PostV1SalesActsUpdateRequestLinesItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**id:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.sales.postV1SalesActsIssue(request) -> PostV1SalesActsIssueResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.sales().postV1SalesActsIssue(
    PostV1SalesActsIssueRequest
        .builder()
        .id("id")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.sales.postV1SalesActsCancel(request) -> PostV1SalesActsCancelResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.sales().postV1SalesActsCancel(
    PostV1SalesActsCancelRequest
        .builder()
        .id("id")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.sales.postV1SalesActsGet(request) -> PostV1SalesActsGetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.sales().postV1SalesActsGet(
    PostV1SalesActsGetRequest
        .builder()
        .id("id")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.sales.postV1SalesActsList(request) -> PostV1SalesActsListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.sales().postV1SalesActsList(
    PostV1SalesActsListRequest
        .builder()
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `Optional<List<PostV1SalesActsListRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<PostV1SalesActsListRequestFilterItem>>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.sales.postV1SalesActsPdf(request) -> PostV1SalesActsPdfResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.sales().postV1SalesActsPdf(
    PostV1SalesActsPdfRequest
        .builder()
        .id("id")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**locale:** `Optional<PostV1SalesActsPdfRequestLocale>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Purchases
<details><summary><code>client.purchases.postV1PurchasesInvoicesCreate(request) -> PostV1PurchasesInvoicesCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.purchases().postV1PurchasesInvoicesCreate(
    PostV1PurchasesInvoicesCreateRequest
        .builder()
        .partnerId("partnerId")
        .documentNumber("documentNumber")
        .documentDate("documentDate")
        .lines(
            Arrays.asList(
                PostV1PurchasesInvoicesCreateRequestLinesItem
                    .builder()
                    .build()
            )
        )
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**partnerId:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**type:** `Optional<PostV1PurchasesInvoicesCreateRequestType>` 
    
</dd>
</dl>

<dl>
<dd>

**documentNumber:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**documentDate:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**dueDate:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**currency:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**creditedInvoiceId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**lines:** `List<PostV1PurchasesInvoicesCreateRequestLinesItem>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.purchases.postV1PurchasesInvoicesGet(request) -> PostV1PurchasesInvoicesGetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.purchases().postV1PurchasesInvoicesGet(
    PostV1PurchasesInvoicesGetRequest
        .builder()
        .id("id")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.purchases.postV1PurchasesInvoicesUpdate(request) -> PostV1PurchasesInvoicesUpdateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.purchases().postV1PurchasesInvoicesUpdate(
    PostV1PurchasesInvoicesUpdateRequest
        .builder()
        .id("id")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**partnerId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**documentNumber:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**documentDate:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**dueDate:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**currency:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**lines:** `Optional<List<PostV1PurchasesInvoicesUpdateRequestLinesItem>>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.purchases.postV1PurchasesInvoicesDelete(request) -> PostV1PurchasesInvoicesDeleteResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.purchases().postV1PurchasesInvoicesDelete(
    PostV1PurchasesInvoicesDeleteRequest
        .builder()
        .id("id")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.purchases.postV1PurchasesInvoicesRegister(request) -> PostV1PurchasesInvoicesRegisterResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.purchases().postV1PurchasesInvoicesRegister(
    PostV1PurchasesInvoicesRegisterRequest
        .builder()
        .id("id")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**registrationDate:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**warehouseId:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.purchases.postV1PurchasesInvoicesList(request) -> PostV1PurchasesInvoicesListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.purchases().postV1PurchasesInvoicesList(
    PostV1PurchasesInvoicesListRequest
        .builder()
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `Optional<List<PostV1PurchasesInvoicesListRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<PostV1PurchasesInvoicesListRequestFilterItem>>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Declarations
<details><summary><code>client.declarations.postV1DeclarationsLtIntrastatCompute(request) -> PostV1DeclarationsLtIntrastatComputeResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().postV1DeclarationsLtIntrastatCompute(
    PostV1DeclarationsLtIntrastatComputeRequest
        .builder()
        .year(1000000L)
        .month(1000000L)
        .flow(PostV1DeclarationsLtIntrastatComputeRequestFlow.ARRIVALS)
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**year:** `Long` 
    
</dd>
</dl>

<dl>
<dd>

**month:** `Long` 
    
</dd>
</dl>

<dl>
<dd>

**flow:** `PostV1DeclarationsLtIntrastatComputeRequestFlow` 
    
</dd>
</dl>

<dl>
<dd>

**transactionNature:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**deliveryTerms:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**transportMode:** `Optional<PostV1DeclarationsLtIntrastatComputeRequestTransportMode>` 
    
</dd>
</dl>

<dl>
<dd>

**persist:** `Optional<Boolean>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.declarations.postV1DeclarationsLtIvazGenerate(request) -> PostV1DeclarationsLtIvazGenerateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().postV1DeclarationsLtIvazGenerate(
    PostV1DeclarationsLtIvazGenerateRequest
        .builder()
        .waybillIds(
            Arrays.asList("waybillIds")
        )
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**waybillIds:** `List<String>` 
    
</dd>
</dl>

<dl>
<dd>

**persist:** `Optional<Boolean>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.declarations.postV1DeclarationsLtIntrastatObligation(request) -> PostV1DeclarationsLtIntrastatObligationResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().postV1DeclarationsLtIntrastatObligation(
    PostV1DeclarationsLtIntrastatObligationRequest
        .builder()
        .year(1000000L)
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**year:** `Long` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.declarations.postV1DeclarationsLtIsafGenerate(request) -> PostV1DeclarationsLtIsafGenerateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().postV1DeclarationsLtIsafGenerate(
    PostV1DeclarationsLtIsafGenerateRequest
        .builder()
        .year(1000000L)
        .month(1000000L)
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**year:** `Long` 
    
</dd>
</dl>

<dl>
<dd>

**month:** `Long` 
    
</dd>
</dl>

<dl>
<dd>

**dataType:** `Optional<PostV1DeclarationsLtIsafGenerateRequestDataType>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.declarations.postV1DeclarationsLtFr0600Compute(request) -> PostV1DeclarationsLtFr0600ComputeResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().postV1DeclarationsLtFr0600Compute(
    PostV1DeclarationsLtFr0600ComputeRequest
        .builder()
        .year(1000000L)
        .month(1000000L)
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**year:** `Long` 
    
</dd>
</dl>

<dl>
<dd>

**month:** `Long` 
    
</dd>
</dl>

<dl>
<dd>

**months:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**deductionPercent:** `Optional<Long>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.declarations.postV1DeclarationsLtGpm313Compute(request) -> PostV1DeclarationsLtGpm313ComputeResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().postV1DeclarationsLtGpm313Compute(
    PostV1DeclarationsLtGpm313ComputeRequest
        .builder()
        .year(1000000L)
        .month(1000000L)
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**year:** `Long` 
    
</dd>
</dl>

<dl>
<dd>

**month:** `Long` 
    
</dd>
</dl>

<dl>
<dd>

**payoutTiming:** `Optional<PostV1DeclarationsLtGpm313ComputeRequestPayoutTiming>` 
    
</dd>
</dl>

<dl>
<dd>

**paymentDay:** `Optional<Long>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.declarations.postV1DeclarationsLtSamCompute(request) -> PostV1DeclarationsLtSamComputeResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().postV1DeclarationsLtSamCompute(
    PostV1DeclarationsLtSamComputeRequest
        .builder()
        .year(1000000L)
        .month(1000000L)
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**year:** `Long` 
    
</dd>
</dl>

<dl>
<dd>

**month:** `Long` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.declarations.postV1DeclarationsLtSdGenerate(request) -> PostV1DeclarationsLtSdGenerateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().postV1DeclarationsLtSdGenerate(
    PostV1DeclarationsLtSdGenerateRequest
        .builder()
        .type(PostV1DeclarationsLtSdGenerateRequestType.ONE_SD)
        .fromDate("fromDate")
        .toDate("toDate")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**type:** `PostV1DeclarationsLtSdGenerateRequestType` 
    
</dd>
</dl>

<dl>
<dd>

**fromDate:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**toDate:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.declarations.postV1DeclarationsLtSaftGenerate(request) -> PostV1DeclarationsLtSaftGenerateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().postV1DeclarationsLtSaftGenerate(
    PostV1DeclarationsLtSaftGenerateRequest
        .builder()
        .fromDate("fromDate")
        .toDate("toDate")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**fromDate:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**toDate:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**dataType:** `Optional<PostV1DeclarationsLtSaftGenerateRequestDataType>` 
    
</dd>
</dl>

<dl>
<dd>

**persist:** `Optional<Boolean>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.declarations.postV1DeclarationsEuOssCompute(request) -> PostV1DeclarationsEuOssComputeResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().postV1DeclarationsEuOssCompute(
    PostV1DeclarationsEuOssComputeRequest
        .builder()
        .year(1000000L)
        .quarter(1000000L)
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**year:** `Long` 
    
</dd>
</dl>

<dl>
<dd>

**quarter:** `Long` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.declarations.postV1DeclarationsEuIossCompute(request) -> PostV1DeclarationsEuIossComputeResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().postV1DeclarationsEuIossCompute(
    PostV1DeclarationsEuIossComputeRequest
        .builder()
        .year(1000000L)
        .month(1000000L)
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**year:** `Long` 
    
</dd>
</dl>

<dl>
<dd>

**month:** `Long` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.declarations.postV1DeclarationsConfigsList(request) -> PostV1DeclarationsConfigsListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().postV1DeclarationsConfigsList(
    PostV1DeclarationsConfigsListRequest
        .builder()
        .build()
);
```
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.declarations.postV1DeclarationsConfigsUpdate(request) -> PostV1DeclarationsConfigsUpdateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().postV1DeclarationsConfigsUpdate(
    PostV1DeclarationsConfigsUpdateRequest
        .builder()
        .system("system")
        .config(
            new HashMap<String, String>() {{
                put("key", "value");
            }}
        )
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**system:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**config:** `Map<String, String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.declarations.postV1DeclarationsSubmissionsCreate(request) -> PostV1DeclarationsSubmissionsCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().postV1DeclarationsSubmissionsCreate(
    PostV1DeclarationsSubmissionsCreateRequest
        .builder()
        .obligation(PostV1DeclarationsSubmissionsCreateRequestObligation.LT_ISAF)
        .year(1000000L)
        .month(1000000L)
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**obligation:** `PostV1DeclarationsSubmissionsCreateRequestObligation` 
    
</dd>
</dl>

<dl>
<dd>

**year:** `Long` 
    
</dd>
</dl>

<dl>
<dd>

**month:** `Long` 
    
</dd>
</dl>

<dl>
<dd>

**dataType:** `Optional<PostV1DeclarationsSubmissionsCreateRequestDataType>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.declarations.postV1DeclarationsSubmissionsMark(request) -> PostV1DeclarationsSubmissionsMarkResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().postV1DeclarationsSubmissionsMark(
    PostV1DeclarationsSubmissionsMarkRequest
        .builder()
        .id("id")
        .status(PostV1DeclarationsSubmissionsMarkRequestStatus.SUBMITTED)
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**status:** `PostV1DeclarationsSubmissionsMarkRequestStatus` 
    
</dd>
</dl>

<dl>
<dd>

**externalRef:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**message:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.declarations.postV1DeclarationsSubmissionsList(request) -> PostV1DeclarationsSubmissionsListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().postV1DeclarationsSubmissionsList(
    PostV1DeclarationsSubmissionsListRequest
        .builder()
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `Optional<List<PostV1DeclarationsSubmissionsListRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<PostV1DeclarationsSubmissionsListRequestFilterItem>>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Ledger
<details><summary><code>client.ledger.postV1LedgerAccountsList(request) -> PostV1LedgerAccountsListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.ledger().postV1LedgerAccountsList(
    PostV1LedgerAccountsListRequest
        .builder()
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `Optional<List<PostV1LedgerAccountsListRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<PostV1LedgerAccountsListRequestFilterItem>>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.ledger.postV1LedgerAccountsCreate(request) -> PostV1LedgerAccountsCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.ledger().postV1LedgerAccountsCreate(
    PostV1LedgerAccountsCreateRequest
        .builder()
        .code("code")
        .name("name")
        .type(PostV1LedgerAccountsCreateRequestType.ASSET)
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**code:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**name:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**type:** `PostV1LedgerAccountsCreateRequestType` 
    
</dd>
</dl>

<dl>
<dd>

**parentId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**isPostable:** `Optional<Boolean>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.ledger.postV1LedgerAccountsUpdate(request) -> PostV1LedgerAccountsUpdateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.ledger().postV1LedgerAccountsUpdate(
    PostV1LedgerAccountsUpdateRequest
        .builder()
        .id("id")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**name:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**parentId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**isPostable:** `Optional<Boolean>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.ledger.postV1LedgerAccountsApplyTemplate(request) -> PostV1LedgerAccountsApplyTemplateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.ledger().postV1LedgerAccountsApplyTemplate(
    PostV1LedgerAccountsApplyTemplateRequest
        .builder()
        .build()
);
```
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.ledger.postV1LedgerPeriodsList(request) -> PostV1LedgerPeriodsListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.ledger().postV1LedgerPeriodsList(
    PostV1LedgerPeriodsListRequest
        .builder()
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `Optional<List<PostV1LedgerPeriodsListRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<PostV1LedgerPeriodsListRequestFilterItem>>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.ledger.postV1LedgerPeriodsLock(request) -> PostV1LedgerPeriodsLockResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.ledger().postV1LedgerPeriodsLock(
    PostV1LedgerPeriodsLockRequest
        .builder()
        .year(1000000L)
        .month(1000000L)
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**year:** `Long` 
    
</dd>
</dl>

<dl>
<dd>

**month:** `Long` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.ledger.postV1LedgerPeriodsUnlock(request) -> PostV1LedgerPeriodsUnlockResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.ledger().postV1LedgerPeriodsUnlock(
    PostV1LedgerPeriodsUnlockRequest
        .builder()
        .year(1000000L)
        .month(1000000L)
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**year:** `Long` 
    
</dd>
</dl>

<dl>
<dd>

**month:** `Long` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.ledger.postV1LedgerJournalTransactionsList(request) -> PostV1LedgerJournalTransactionsListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.ledger().postV1LedgerJournalTransactionsList(
    PostV1LedgerJournalTransactionsListRequest
        .builder()
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `Optional<List<PostV1LedgerJournalTransactionsListRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<PostV1LedgerJournalTransactionsListRequestFilterItem>>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.ledger.postV1LedgerCostCentersCreate(request) -> PostV1LedgerCostCentersCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.ledger().postV1LedgerCostCentersCreate(
    PostV1LedgerCostCentersCreateRequest
        .builder()
        .code("code")
        .name("name")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**code:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**name:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**groupId:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.ledger.postV1LedgerCostCentersUpdate(request) -> PostV1LedgerCostCentersUpdateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.ledger().postV1LedgerCostCentersUpdate(
    PostV1LedgerCostCentersUpdateRequest
        .builder()
        .id("id")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**name:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**isActive:** `Optional<Boolean>` 
    
</dd>
</dl>

<dl>
<dd>

**groupId:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.ledger.postV1LedgerCostCentersList(request) -> PostV1LedgerCostCentersListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.ledger().postV1LedgerCostCentersList(
    PostV1LedgerCostCentersListRequest
        .builder()
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `Optional<List<PostV1LedgerCostCentersListRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<PostV1LedgerCostCentersListRequestFilterItem>>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.ledger.postV1LedgerCostCenterGroupsCreate(request) -> PostV1LedgerCostCenterGroupsCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.ledger().postV1LedgerCostCenterGroupsCreate(
    PostV1LedgerCostCenterGroupsCreateRequest
        .builder()
        .code("code")
        .name("name")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**code:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**name:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.ledger.postV1LedgerCostCenterGroupsUpdate(request) -> PostV1LedgerCostCenterGroupsUpdateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.ledger().postV1LedgerCostCenterGroupsUpdate(
    PostV1LedgerCostCenterGroupsUpdateRequest
        .builder()
        .id("id")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**code:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**name:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.ledger.postV1LedgerCostCenterGroupsDelete(request) -> PostV1LedgerCostCenterGroupsDeleteResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.ledger().postV1LedgerCostCenterGroupsDelete(
    PostV1LedgerCostCenterGroupsDeleteRequest
        .builder()
        .id("id")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.ledger.postV1LedgerCostCenterGroupsList(request) -> PostV1LedgerCostCenterGroupsListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.ledger().postV1LedgerCostCenterGroupsList(
    PostV1LedgerCostCenterGroupsListRequest
        .builder()
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `Optional<List<PostV1LedgerCostCenterGroupsListRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<PostV1LedgerCostCenterGroupsListRequestFilterItem>>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.ledger.postV1LedgerPostingRulesList(request) -> PostV1LedgerPostingRulesListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.ledger().postV1LedgerPostingRulesList(
    PostV1LedgerPostingRulesListRequest
        .builder()
        .build()
);
```
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.ledger.postV1LedgerPostingRulesUpdate(request) -> PostV1LedgerPostingRulesUpdateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.ledger().postV1LedgerPostingRulesUpdate(
    PostV1LedgerPostingRulesUpdateRequest
        .builder()
        .rules(
            Arrays.asList(
                PostV1LedgerPostingRulesUpdateRequestRulesItem
                    .builder()
                    .key(PostV1LedgerPostingRulesUpdateRequestRulesItemKey.SALES_RECEIVABLE)
                    .accountCode(
                        Nullable.ofNull()
                    )
                    .build()
            )
        )
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**rules:** `List<PostV1LedgerPostingRulesUpdateRequestRulesItem>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.ledger.postV1LedgerOwnersCreate(request) -> PostV1LedgerOwnersCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.ledger().postV1LedgerOwnersCreate(
    PostV1LedgerOwnersCreateRequest
        .builder()
        .name("name")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**name:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**code:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**equityAccountCode:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**sharesQuantity:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**sharesAmount:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**sharesType:** `Optional<PostV1LedgerOwnersCreateRequestSharesType>` 
    
</dd>
</dl>

<dl>
<dd>

**sharesAcquisitionDate:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**address:** `Optional<PostV1LedgerOwnersCreateRequestAddress>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.ledger.postV1LedgerOwnersUpdate(request) -> PostV1LedgerOwnersUpdateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.ledger().postV1LedgerOwnersUpdate(
    PostV1LedgerOwnersUpdateRequest
        .builder()
        .id("id")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**name:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**code:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**equityAccountCode:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**sharesQuantity:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**sharesAmount:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**sharesType:** `Optional<PostV1LedgerOwnersUpdateRequestSharesType>` 
    
</dd>
</dl>

<dl>
<dd>

**sharesAcquisitionDate:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**address:** `Optional<PostV1LedgerOwnersUpdateRequestAddress>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.ledger.postV1LedgerOwnersDelete(request) -> PostV1LedgerOwnersDeleteResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.ledger().postV1LedgerOwnersDelete(
    PostV1LedgerOwnersDeleteRequest
        .builder()
        .id("id")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.ledger.postV1LedgerOwnersList(request) -> PostV1LedgerOwnersListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.ledger().postV1LedgerOwnersList(
    PostV1LedgerOwnersListRequest
        .builder()
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `Optional<List<PostV1LedgerOwnersListRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<PostV1LedgerOwnersListRequestFilterItem>>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.ledger.postV1LedgerJournalTransactionsGet(request) -> PostV1LedgerJournalTransactionsGetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.ledger().postV1LedgerJournalTransactionsGet(
    PostV1LedgerJournalTransactionsGetRequest
        .builder()
        .id("id")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.ledger.postV1LedgerJournalTransactionsCreate(request) -> PostV1LedgerJournalTransactionsCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.ledger().postV1LedgerJournalTransactionsCreate(
    PostV1LedgerJournalTransactionsCreateRequest
        .builder()
        .date("date")
        .entries(
            Arrays.asList(
                PostV1LedgerJournalTransactionsCreateRequestEntriesItem
                    .builder()
                    .accountCode("accountCode")
                    .build()
            )
        )
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**date:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**description:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**entries:** `List<PostV1LedgerJournalTransactionsCreateRequestEntriesItem>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Assets
<details><summary><code>client.assets.postV1AssetsGroupsCreate(request) -> PostV1AssetsGroupsCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.assets().postV1AssetsGroupsCreate(
    PostV1AssetsGroupsCreateRequest
        .builder()
        .code("code")
        .name("name")
        .assetAccountCode("assetAccountCode")
        .depreciationAccountCode("depreciationAccountCode")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**code:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**name:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**defaultUsefulLifeMonths:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**assetAccountCode:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**depreciationAccountCode:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**expenseAccountCode:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.assets.postV1AssetsGroupsList(request) -> PostV1AssetsGroupsListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.assets().postV1AssetsGroupsList(
    PostV1AssetsGroupsListRequest
        .builder()
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `Optional<List<PostV1AssetsGroupsListRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<PostV1AssetsGroupsListRequestFilterItem>>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.assets.postV1AssetsAssetsCreate(request) -> PostV1AssetsAssetsCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.assets().postV1AssetsAssetsCreate(
    PostV1AssetsAssetsCreateRequest
        .builder()
        .groupId("groupId")
        .code("code")
        .name("name")
        .acquisitionDate("acquisitionDate")
        .acquisitionCost("acquisitionCost")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**groupId:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**code:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**name:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**acquisitionDate:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**depreciationStartDate:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**acquisitionCost:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**salvageValue:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**usefulLifeMonths:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.assets.postV1AssetsAssetsGet(request) -> PostV1AssetsAssetsGetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.assets().postV1AssetsAssetsGet(
    PostV1AssetsAssetsGetRequest
        .builder()
        .id("id")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.assets.postV1AssetsAssetsList(request) -> PostV1AssetsAssetsListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.assets().postV1AssetsAssetsList(
    PostV1AssetsAssetsListRequest
        .builder()
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `Optional<List<PostV1AssetsAssetsListRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<PostV1AssetsAssetsListRequestFilterItem>>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.assets.postV1AssetsAssetsModernize(request) -> PostV1AssetsAssetsModernizeResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.assets().postV1AssetsAssetsModernize(
    PostV1AssetsAssetsModernizeRequest
        .builder()
        .id("id")
        .date("date")
        .amount("amount")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**date:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**amount:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**addedLifeMonths:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.assets.postV1AssetsDepreciationPreview(request) -> PostV1AssetsDepreciationPreviewResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.assets().postV1AssetsDepreciationPreview(
    PostV1AssetsDepreciationPreviewRequest
        .builder()
        .year(1000000L)
        .month(1000000L)
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**year:** `Long` 
    
</dd>
</dl>

<dl>
<dd>

**month:** `Long` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.assets.postV1AssetsDepreciationPost(request) -> PostV1AssetsDepreciationPostResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.assets().postV1AssetsDepreciationPost(
    PostV1AssetsDepreciationPostRequest
        .builder()
        .year(1000000L)
        .month(1000000L)
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**year:** `Long` 
    
</dd>
</dl>

<dl>
<dd>

**month:** `Long` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Hr
<details><summary><code>client.hr.postV1HrPositionsCreate(request) -> PostV1HrPositionsCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.hr().postV1HrPositionsCreate(
    PostV1HrPositionsCreateRequest
        .builder()
        .name("name")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**code:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**name:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**translations:** `Optional<Map<String, PostV1HrPositionsCreateRequestTranslationsValue>>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.hr.postV1HrPositionsUpdate(request) -> PostV1HrPositionsUpdateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.hr().postV1HrPositionsUpdate(
    PostV1HrPositionsUpdateRequest
        .builder()
        .id("id")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**code:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**name:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**translations:** `Optional<Map<String, Optional<PostV1HrPositionsUpdateRequestTranslationsValue>>>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.hr.postV1HrPositionsList(request) -> PostV1HrPositionsListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.hr().postV1HrPositionsList(
    PostV1HrPositionsListRequest
        .builder()
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `Optional<List<PostV1HrPositionsListRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<PostV1HrPositionsListRequestFilterItem>>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.hr.postV1HrEmployeesCreate(request) -> PostV1HrEmployeesCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.hr().postV1HrEmployeesCreate(
    PostV1HrEmployeesCreateRequest
        .builder()
        .firstName("firstName")
        .lastName("lastName")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**code:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**firstName:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**lastName:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**personalCode:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**birthDate:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**email:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**phone:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**address:** `Optional<PostV1HrEmployeesCreateRequestAddress>` 
    
</dd>
</dl>

<dl>
<dd>

**iban:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**socialInsuranceNo:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**socialInsuranceStart:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**hireDate:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**applyNpd:** `Optional<Boolean>` 
    
</dd>
</dl>

<dl>
<dd>

**npdOverride:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**pensionAccumulation:** `Optional<Boolean>` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.hr.postV1HrEmployeesUpdate(request) -> PostV1HrEmployeesUpdateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.hr().postV1HrEmployeesUpdate(
    PostV1HrEmployeesUpdateRequest
        .builder()
        .id("id")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**code:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**firstName:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**lastName:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**personalCode:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**birthDate:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**email:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**phone:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**address:** `Optional<PostV1HrEmployeesUpdateRequestAddress>` 
    
</dd>
</dl>

<dl>
<dd>

**iban:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**socialInsuranceNo:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**socialInsuranceStart:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**hireDate:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**applyNpd:** `Optional<Boolean>` 
    
</dd>
</dl>

<dl>
<dd>

**npdOverride:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**pensionAccumulation:** `Optional<Boolean>` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**id:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**terminationDate:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**status:** `Optional<PostV1HrEmployeesUpdateRequestStatus>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.hr.postV1HrEmployeesGet(request) -> PostV1HrEmployeesGetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.hr().postV1HrEmployeesGet(
    PostV1HrEmployeesGetRequest
        .builder()
        .id("id")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.hr.postV1HrEmployeesList(request) -> PostV1HrEmployeesListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.hr().postV1HrEmployeesList(
    PostV1HrEmployeesListRequest
        .builder()
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `Optional<List<PostV1HrEmployeesListRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<PostV1HrEmployeesListRequestFilterItem>>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.hr.postV1HrContractsCreate(request) -> PostV1HrContractsCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.hr().postV1HrContractsCreate(
    PostV1HrContractsCreateRequest
        .builder()
        .employeeId("employeeId")
        .contractNo("contractNo")
        .startDate("startDate")
        .baseSalary("baseSalary")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**employeeId:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**positionId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**departmentId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**scheduleId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**contractNo:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**type:** `Optional<PostV1HrContractsCreateRequestType>` 
    
</dd>
</dl>

<dl>
<dd>

**startDate:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**endDate:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**baseSalary:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**salaryType:** `Optional<PostV1HrContractsCreateRequestSalaryType>` 
    
</dd>
</dl>

<dl>
<dd>

**workHoursPerWeek:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.hr.postV1HrContractsEnd(request) -> PostV1HrContractsEndResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.hr().postV1HrContractsEnd(
    PostV1HrContractsEndRequest
        .builder()
        .id("id")
        .endDate("endDate")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**endDate:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**endReason:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.hr.postV1HrContractsList(request) -> PostV1HrContractsListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.hr().postV1HrContractsList(
    PostV1HrContractsListRequest
        .builder()
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `Optional<List<PostV1HrContractsListRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<PostV1HrContractsListRequestFilterItem>>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.hr.postV1HrLeaveBalancesSet(request) -> PostV1HrLeaveBalancesSetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.hr().postV1HrLeaveBalancesSet(
    PostV1HrLeaveBalancesSetRequest
        .builder()
        .employeeId("employeeId")
        .year(1000000L)
        .entitledDays("entitledDays")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**employeeId:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**year:** `Long` 
    
</dd>
</dl>

<dl>
<dd>

**entitledDays:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**usedDays:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.hr.postV1HrLeaveBalancesList(request) -> PostV1HrLeaveBalancesListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.hr().postV1HrLeaveBalancesList(
    PostV1HrLeaveBalancesListRequest
        .builder()
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**employeeId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**year:** `Optional<Long>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.hr.postV1HrIncapacityCertificatesCreate(request) -> PostV1HrIncapacityCertificatesCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.hr().postV1HrIncapacityCertificatesCreate(
    PostV1HrIncapacityCertificatesCreateRequest
        .builder()
        .employeeId("employeeId")
        .number("number")
        .fromDate("fromDate")
        .toDate("toDate")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**employeeId:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**series:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**number:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**fromDate:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**toDate:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**reason:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.hr.postV1HrIncapacityCertificatesList(request) -> PostV1HrIncapacityCertificatesListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.hr().postV1HrIncapacityCertificatesList(
    PostV1HrIncapacityCertificatesListRequest
        .builder()
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `Optional<List<PostV1HrIncapacityCertificatesListRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<PostV1HrIncapacityCertificatesListRequestFilterItem>>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.hr.postV1HrEmployeesRecordsCreate(request) -> PostV1HrEmployeesRecordsCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.hr().postV1HrEmployeesRecordsCreate(
    PostV1HrEmployeesRecordsCreateRequest
        .builder()
        .employeeId("employeeId")
        .type(PostV1HrEmployeesRecordsCreateRequestType.EDUCATION)
        .title("title")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**employeeId:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**type:** `PostV1HrEmployeesRecordsCreateRequestType` 
    
</dd>
</dl>

<dl>
<dd>

**title:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**institution:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**issuedAt:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**validUntil:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**fileId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.hr.postV1HrEmployeesRecordsUpdate(request) -> PostV1HrEmployeesRecordsUpdateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.hr().postV1HrEmployeesRecordsUpdate(
    PostV1HrEmployeesRecordsUpdateRequest
        .builder()
        .id("id")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**type:** `Optional<PostV1HrEmployeesRecordsUpdateRequestType>` 
    
</dd>
</dl>

<dl>
<dd>

**title:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**institution:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**issuedAt:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**validUntil:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**fileId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.hr.postV1HrEmployeesRecordsDelete(request) -> PostV1HrEmployeesRecordsDeleteResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.hr().postV1HrEmployeesRecordsDelete(
    PostV1HrEmployeesRecordsDeleteRequest
        .builder()
        .id("id")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.hr.postV1HrEmployeesRecordsList(request) -> PostV1HrEmployeesRecordsListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.hr().postV1HrEmployeesRecordsList(
    PostV1HrEmployeesRecordsListRequest
        .builder()
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `Optional<List<PostV1HrEmployeesRecordsListRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<PostV1HrEmployeesRecordsListRequestFilterItem>>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.hr.postV1HrEmployeesAttachmentsList(request) -> PostV1HrEmployeesAttachmentsListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.hr().postV1HrEmployeesAttachmentsList(
    PostV1HrEmployeesAttachmentsListRequest
        .builder()
        .employeeId("employeeId")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**employeeId:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.hr.postV1HrTimesheetsGenerate(request) -> PostV1HrTimesheetsGenerateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.hr().postV1HrTimesheetsGenerate(
    PostV1HrTimesheetsGenerateRequest
        .builder()
        .year(1000000L)
        .month(1000000L)
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**year:** `Long` 
    
</dd>
</dl>

<dl>
<dd>

**month:** `Long` 
    
</dd>
</dl>

<dl>
<dd>

**employeeId:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.hr.postV1HrTimesheetsUpsert(request) -> PostV1HrTimesheetsUpsertResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.hr().postV1HrTimesheetsUpsert(
    PostV1HrTimesheetsUpsertRequest
        .builder()
        .employeeId("employeeId")
        .year(1000000L)
        .month(1000000L)
        .days(
            Arrays.asList(
                PostV1HrTimesheetsUpsertRequestDaysItem
                    .builder()
                    .day(1000000L)
                    .hours("hours")
                    .type(PostV1HrTimesheetsUpsertRequestDaysItemType.WORK)
                    .build()
            )
        )
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**employeeId:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**year:** `Long` 
    
</dd>
</dl>

<dl>
<dd>

**month:** `Long` 
    
</dd>
</dl>

<dl>
<dd>

**days:** `List<PostV1HrTimesheetsUpsertRequestDaysItem>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.hr.postV1HrTimesheetsGet(request) -> PostV1HrTimesheetsGetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.hr().postV1HrTimesheetsGet(
    PostV1HrTimesheetsGetRequest
        .builder()
        .employeeId("employeeId")
        .year(1000000L)
        .month(1000000L)
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**employeeId:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**year:** `Long` 
    
</dd>
</dl>

<dl>
<dd>

**month:** `Long` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.hr.postV1HrTimesheetsList(request) -> PostV1HrTimesheetsListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.hr().postV1HrTimesheetsList(
    PostV1HrTimesheetsListRequest
        .builder()
        .year(1000000L)
        .month(1000000L)
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**year:** `Long` 
    
</dd>
</dl>

<dl>
<dd>

**month:** `Long` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.hr.postV1HrTimesheetsDelete(request) -> PostV1HrTimesheetsDeleteResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.hr().postV1HrTimesheetsDelete(
    PostV1HrTimesheetsDeleteRequest
        .builder()
        .id("id")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Payroll
<details><summary><code>client.payroll.postV1PayrollDepartmentsCreate(request) -> PostV1PayrollDepartmentsCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.payroll().postV1PayrollDepartmentsCreate(
    PostV1PayrollDepartmentsCreateRequest
        .builder()
        .code("code")
        .name("name")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**code:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**name:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.payroll.postV1PayrollDepartmentsList(request) -> PostV1PayrollDepartmentsListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.payroll().postV1PayrollDepartmentsList(
    PostV1PayrollDepartmentsListRequest
        .builder()
        .build()
);
```
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.payroll.postV1PayrollSchedulesCreate(request) -> PostV1PayrollSchedulesCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.payroll().postV1PayrollSchedulesCreate(
    PostV1PayrollSchedulesCreateRequest
        .builder()
        .code("code")
        .name("name")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**code:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**name:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**hoursPerWeek:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.payroll.postV1PayrollSchedulesList(request) -> PostV1PayrollSchedulesListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.payroll().postV1PayrollSchedulesList(
    PostV1PayrollSchedulesListRequest
        .builder()
        .build()
);
```
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.payroll.postV1PayrollCalc(request) -> PostV1PayrollCalcResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.payroll().postV1PayrollCalc(
    PostV1PayrollCalcRequest
        .builder()
        .taxableBase("taxableBase")
        .date("date")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**taxableBase:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**date:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**applyNpd:** `Optional<Boolean>` 
    
</dd>
</dl>

<dl>
<dd>

**npdOverride:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**pensionAccumulation:** `Optional<Boolean>` 
    
</dd>
</dl>

<dl>
<dd>

**fixedTerm:** `Optional<Boolean>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.payroll.postV1PayrollRunsCreate(request) -> PostV1PayrollRunsCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.payroll().postV1PayrollRunsCreate(
    PostV1PayrollRunsCreateRequest
        .builder()
        .year(1000000L)
        .month(1000000L)
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**year:** `Long` 
    
</dd>
</dl>

<dl>
<dd>

**month:** `Long` 
    
</dd>
</dl>

<dl>
<dd>

**lines:** `Optional<List<PostV1PayrollRunsCreateRequestLinesItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.payroll.postV1PayrollRunsGet(request) -> PostV1PayrollRunsGetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.payroll().postV1PayrollRunsGet(
    PostV1PayrollRunsGetRequest
        .builder()
        .id("id")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.payroll.postV1PayrollRunsList(request) -> PostV1PayrollRunsListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.payroll().postV1PayrollRunsList(
    PostV1PayrollRunsListRequest
        .builder()
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `Optional<List<PostV1PayrollRunsListRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<PostV1PayrollRunsListRequestFilterItem>>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.payroll.postV1PayrollRunsApprove(request) -> PostV1PayrollRunsApproveResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.payroll().postV1PayrollRunsApprove(
    PostV1PayrollRunsApproveRequest
        .builder()
        .id("id")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**wageAccountCode:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**employerAccountCode:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**payableAccountCode:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**gpmAccountCode:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**sodraAccountCode:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**deductionAccountCode:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.payroll.postV1PayrollRunsCancel(request) -> PostV1PayrollRunsCancelResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.payroll().postV1PayrollRunsCancel(
    PostV1PayrollRunsCancelRequest
        .builder()
        .id("id")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.payroll.postV1PayrollPaymentsExport(request) -> PostV1PayrollPaymentsExportResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.payroll().postV1PayrollPaymentsExport(
    PostV1PayrollPaymentsExportRequest
        .builder()
        .runId("runId")
        .bankAccountId("bankAccountId")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**runId:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**bankAccountId:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**executionDate:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Agreements
<details><summary><code>client.agreements.postV1AgreementsTypesCreate(request) -> PostV1AgreementsTypesCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.agreements().postV1AgreementsTypesCreate(
    PostV1AgreementsTypesCreateRequest
        .builder()
        .code("code")
        .name("name")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**code:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**name:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.agreements.postV1AgreementsTypesList(request) -> PostV1AgreementsTypesListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.agreements().postV1AgreementsTypesList(
    PostV1AgreementsTypesListRequest
        .builder()
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `Optional<List<PostV1AgreementsTypesListRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<PostV1AgreementsTypesListRequestFilterItem>>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.agreements.postV1AgreementsAgreementsCreate(request) -> PostV1AgreementsAgreementsCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.agreements().postV1AgreementsAgreementsCreate(
    PostV1AgreementsAgreementsCreateRequest
        .builder()
        .partnerId("partnerId")
        .number("number")
        .startDate("startDate")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**typeId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**partnerId:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**number:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**name:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**startDate:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**endDate:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**autoRenew:** `Optional<Boolean>` 
    
</dd>
</dl>

<dl>
<dd>

**value:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**currency:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**status:** `Optional<PostV1AgreementsAgreementsCreateRequestStatus>` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**items:** `Optional<List<PostV1AgreementsAgreementsCreateRequestItemsItem>>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.agreements.postV1AgreementsAgreementsGet(request) -> PostV1AgreementsAgreementsGetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.agreements().postV1AgreementsAgreementsGet(
    PostV1AgreementsAgreementsGetRequest
        .builder()
        .id("id")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.agreements.postV1AgreementsAgreementsUpdate(request) -> PostV1AgreementsAgreementsUpdateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.agreements().postV1AgreementsAgreementsUpdate(
    PostV1AgreementsAgreementsUpdateRequest
        .builder()
        .id("id")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**typeId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**name:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**endDate:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**autoRenew:** `Optional<Boolean>` 
    
</dd>
</dl>

<dl>
<dd>

**value:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**status:** `Optional<PostV1AgreementsAgreementsUpdateRequestStatus>` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.agreements.postV1AgreementsAgreementsDelete(request) -> PostV1AgreementsAgreementsDeleteResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.agreements().postV1AgreementsAgreementsDelete(
    PostV1AgreementsAgreementsDeleteRequest
        .builder()
        .id("id")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.agreements.postV1AgreementsAgreementsList(request) -> PostV1AgreementsAgreementsListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.agreements().postV1AgreementsAgreementsList(
    PostV1AgreementsAgreementsListRequest
        .builder()
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `Optional<List<PostV1AgreementsAgreementsListRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<PostV1AgreementsAgreementsListRequestFilterItem>>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.agreements.postV1AgreementsInsurancePoliciesCreate(request) -> PostV1AgreementsInsurancePoliciesCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.agreements().postV1AgreementsInsurancePoliciesCreate(
    PostV1AgreementsInsurancePoliciesCreateRequest
        .builder()
        .policyNumber("policyNumber")
        .insuredObject("insuredObject")
        .fromDate("fromDate")
        .toDate("toDate")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**insurerPartnerId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**policyNumber:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**insuredObject:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**fromDate:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**toDate:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**premium:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**currency:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.agreements.postV1AgreementsInsurancePoliciesList(request) -> PostV1AgreementsInsurancePoliciesListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.agreements().postV1AgreementsInsurancePoliciesList(
    PostV1AgreementsInsurancePoliciesListRequest
        .builder()
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `Optional<List<PostV1AgreementsInsurancePoliciesListRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<PostV1AgreementsInsurancePoliciesListRequestFilterItem>>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.agreements.postV1AgreementsInsurancePoliciesDelete(request) -> PostV1AgreementsInsurancePoliciesDeleteResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.agreements().postV1AgreementsInsurancePoliciesDelete(
    PostV1AgreementsInsurancePoliciesDeleteRequest
        .builder()
        .id("id")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Inventory
<details><summary><code>client.inventory.postV1InventorySettingsGet(request) -> PostV1InventorySettingsGetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.inventory().postV1InventorySettingsGet(
    PostV1InventorySettingsGetRequest
        .builder()
        .build()
);
```
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.inventory.postV1InventorySettingsUpdate(request) -> PostV1InventorySettingsUpdateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.inventory().postV1InventorySettingsUpdate(
    PostV1InventorySettingsUpdateRequest
        .builder()
        .negativeStockPolicy(PostV1InventorySettingsUpdateRequestNegativeStockPolicy.REJECT)
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**negativeStockPolicy:** `PostV1InventorySettingsUpdateRequestNegativeStockPolicy` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.inventory.postV1InventoryWarehousesCreate(request) -> PostV1InventoryWarehousesCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.inventory().postV1InventoryWarehousesCreate(
    PostV1InventoryWarehousesCreateRequest
        .builder()
        .code("code")
        .name("name")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**code:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**name:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**isDefault:** `Optional<Boolean>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.inventory.postV1InventoryWarehousesList(request) -> PostV1InventoryWarehousesListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.inventory().postV1InventoryWarehousesList(
    PostV1InventoryWarehousesListRequest
        .builder()
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `Optional<List<PostV1InventoryWarehousesListRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<PostV1InventoryWarehousesListRequestFilterItem>>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.inventory.postV1InventoryStockReceive(request) -> PostV1InventoryStockReceiveResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.inventory().postV1InventoryStockReceive(
    PostV1InventoryStockReceiveRequest
        .builder()
        .warehouseId("warehouseId")
        .itemId("itemId")
        .date("date")
        .quantity("quantity")
        .unitCost("unitCost")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**warehouseId:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**itemId:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**date:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**quantity:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**unitCost:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.inventory.postV1InventoryStockWriteOff(request) -> PostV1InventoryStockWriteOffResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.inventory().postV1InventoryStockWriteOff(
    PostV1InventoryStockWriteOffRequest
        .builder()
        .warehouseId("warehouseId")
        .itemId("itemId")
        .date("date")
        .quantity("quantity")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**warehouseId:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**itemId:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**date:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**quantity:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**expenseAccountCode:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**inventoryAccountCode:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.inventory.postV1InventoryStockTransfer(request) -> PostV1InventoryStockTransferResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.inventory().postV1InventoryStockTransfer(
    PostV1InventoryStockTransferRequest
        .builder()
        .fromWarehouseId("fromWarehouseId")
        .toWarehouseId("toWarehouseId")
        .itemId("itemId")
        .date("date")
        .quantity("quantity")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**fromWarehouseId:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**toWarehouseId:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**itemId:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**date:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**quantity:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.inventory.postV1InventoryStockTake(request) -> PostV1InventoryStockTakeResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.inventory().postV1InventoryStockTake(
    PostV1InventoryStockTakeRequest
        .builder()
        .warehouseId("warehouseId")
        .date("date")
        .lines(
            Arrays.asList(
                PostV1InventoryStockTakeRequestLinesItem
                    .builder()
                    .countedQty("countedQty")
                    .build()
            )
        )
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**warehouseId:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**date:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**expenseAccountCode:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**inventoryAccountCode:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**lines:** `List<PostV1InventoryStockTakeRequestLinesItem>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.inventory.postV1InventoryStockLevels(request) -> PostV1InventoryStockLevelsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.inventory().postV1InventoryStockLevels(
    PostV1InventoryStockLevelsRequest
        .builder()
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**warehouseId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**itemId:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.inventory.postV1InventoryStockMovementsList(request) -> PostV1InventoryStockMovementsListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.inventory().postV1InventoryStockMovementsList(
    PostV1InventoryStockMovementsListRequest
        .builder()
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `Optional<List<PostV1InventoryStockMovementsListRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<PostV1InventoryStockMovementsListRequestFilterItem>>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Production
<details><summary><code>client.production.postV1ProductionBomsCreate(request) -> PostV1ProductionBomsCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.production().postV1ProductionBomsCreate(
    PostV1ProductionBomsCreateRequest
        .builder()
        .code("code")
        .name("name")
        .finishedItemId("finishedItemId")
        .lines(
            Arrays.asList(
                PostV1ProductionBomsCreateRequestLinesItem
                    .builder()
                    .componentItemId("componentItemId")
                    .quantity("quantity")
                    .build()
            )
        )
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**code:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**name:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**finishedItemId:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**outputQuantity:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**lines:** `List<PostV1ProductionBomsCreateRequestLinesItem>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.production.postV1ProductionBomsGet(request) -> PostV1ProductionBomsGetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.production().postV1ProductionBomsGet(
    PostV1ProductionBomsGetRequest
        .builder()
        .id("id")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.production.postV1ProductionBomsList(request) -> PostV1ProductionBomsListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.production().postV1ProductionBomsList(
    PostV1ProductionBomsListRequest
        .builder()
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `Optional<List<PostV1ProductionBomsListRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<PostV1ProductionBomsListRequestFilterItem>>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.production.postV1ProductionOrdersCreate(request) -> PostV1ProductionOrdersCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.production().postV1ProductionOrdersCreate(
    PostV1ProductionOrdersCreateRequest
        .builder()
        .bomId("bomId")
        .warehouseId("warehouseId")
        .quantity("quantity")
        .date("date")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**type:** `Optional<PostV1ProductionOrdersCreateRequestType>` 
    
</dd>
</dl>

<dl>
<dd>

**bomId:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**warehouseId:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**quantity:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**date:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.production.postV1ProductionOrdersComplete(request) -> PostV1ProductionOrdersCompleteResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.production().postV1ProductionOrdersComplete(
    PostV1ProductionOrdersCompleteRequest
        .builder()
        .id("id")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**componentsAccountCode:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**finishedAccountCode:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.production.postV1ProductionOrdersGet(request) -> PostV1ProductionOrdersGetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.production().postV1ProductionOrdersGet(
    PostV1ProductionOrdersGetRequest
        .builder()
        .id("id")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.production.postV1ProductionOrdersList(request) -> PostV1ProductionOrdersListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.production().postV1ProductionOrdersList(
    PostV1ProductionOrdersListRequest
        .builder()
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `Optional<List<PostV1ProductionOrdersListRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<PostV1ProductionOrdersListRequestFilterItem>>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Ecommerce
<details><summary><code>client.ecommerce.postV1EcommerceOrdersCreate(request) -> PostV1EcommerceOrdersCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.ecommerce().postV1EcommerceOrdersCreate(
    PostV1EcommerceOrdersCreateRequest
        .builder()
        .lines(
            Arrays.asList(
                PostV1EcommerceOrdersCreateRequestLinesItem
                    .builder()
                    .description("description")
                    .quantity("quantity")
                    .unitPriceExclVat("unitPriceExclVat")
                    .build()
            )
        )
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**channel:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**externalRef:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**partnerId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**partner:** `Optional<PostV1EcommerceOrdersCreateRequestPartner>` 
    
</dd>
</dl>

<dl>
<dd>

**warehouseId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**currency:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**shipToCountryCode:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**marketplace:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**lines:** `List<PostV1EcommerceOrdersCreateRequestLinesItem>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.ecommerce.postV1EcommerceOrdersGet(request) -> PostV1EcommerceOrdersGetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.ecommerce().postV1EcommerceOrdersGet(
    PostV1EcommerceOrdersGetRequest
        .builder()
        .id("id")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.ecommerce.postV1EcommerceOrdersList(request) -> PostV1EcommerceOrdersListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.ecommerce().postV1EcommerceOrdersList(
    PostV1EcommerceOrdersListRequest
        .builder()
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `Optional<List<PostV1EcommerceOrdersListRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<PostV1EcommerceOrdersListRequestFilterItem>>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.ecommerce.postV1EcommerceOrdersReserve(request) -> PostV1EcommerceOrdersReserveResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.ecommerce().postV1EcommerceOrdersReserve(
    PostV1EcommerceOrdersReserveRequest
        .builder()
        .id("id")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**warehouseId:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.ecommerce.postV1EcommerceOrdersFulfill(request) -> PostV1EcommerceOrdersFulfillResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.ecommerce().postV1EcommerceOrdersFulfill(
    PostV1EcommerceOrdersFulfillRequest
        .builder()
        .id("id")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**date:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**cogsAccountCode:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**inventoryAccountCode:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.ecommerce.postV1EcommerceOrdersCancel(request) -> PostV1EcommerceOrdersCancelResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.ecommerce().postV1EcommerceOrdersCancel(
    PostV1EcommerceOrdersCancelRequest
        .builder()
        .id("id")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.ecommerce.postV1EcommerceProductsList(request) -> PostV1EcommerceProductsListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.ecommerce().postV1EcommerceProductsList(
    PostV1EcommerceProductsListRequest
        .builder()
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**warehouseId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**priceListId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**updatedSince:** `Optional<OffsetDateTime>` 
    
</dd>
</dl>

<dl>
<dd>

**page:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `Optional<Long>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.ecommerce.postV1EcommerceStockList(request) -> PostV1EcommerceStockListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.ecommerce().postV1EcommerceStockList(
    PostV1EcommerceStockListRequest
        .builder()
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**warehouseId:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Cash
<details><summary><code>client.cash.postV1CashOrdersCreate(request) -> PostV1CashOrdersCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.cash().postV1CashOrdersCreate(
    PostV1CashOrdersCreateRequest
        .builder()
        .type(PostV1CashOrdersCreateRequestType.RECEIPT)
        .date("date")
        .amount("amount")
        .purpose("purpose")
        .counterAccountCode("counterAccountCode")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**type:** `PostV1CashOrdersCreateRequestType` 
    
</dd>
</dl>

<dl>
<dd>

**date:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**amount:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**purpose:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**counterAccountCode:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**cashAccountCode:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**series:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**partnerId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**employeeId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.cash.postV1CashOrdersGet(request) -> PostV1CashOrdersGetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.cash().postV1CashOrdersGet(
    PostV1CashOrdersGetRequest
        .builder()
        .id("id")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.cash.postV1CashOrdersList(request) -> PostV1CashOrdersListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.cash().postV1CashOrdersList(
    PostV1CashOrdersListRequest
        .builder()
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `Optional<List<PostV1CashOrdersListRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<PostV1CashOrdersListRequestFilterItem>>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.cash.postV1CashBalance(request) -> PostV1CashBalanceResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.cash().postV1CashBalance(
    PostV1CashBalanceRequest
        .builder()
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**cashAccountCode:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**asOf:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.cash.postV1CashAdvanceHoldersBalances(request) -> PostV1CashAdvanceHoldersBalancesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.cash().postV1CashAdvanceHoldersBalances(
    PostV1CashAdvanceHoldersBalancesRequest
        .builder()
        .build()
);
```
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Transport
<details><summary><code>client.transport.postV1TransportWaybillsCreate(request) -> PostV1TransportWaybillsCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.transport().postV1TransportWaybillsCreate(
    PostV1TransportWaybillsCreateRequest
        .builder()
        .consigneePartnerId("consigneePartnerId")
        .dispatchAt(OffsetDateTime.parse("2024-01-15T09:30:00Z"))
        .loadAddress("loadAddress")
        .unloadAddress("unloadAddress")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**consigneePartnerId:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**transporterPartnerId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**documentDate:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**dispatchAt:** `OffsetDateTime` 
    
</dd>
</dl>

<dl>
<dd>

**estimatedArrivalAt:** `Optional<OffsetDateTime>` 
    
</dd>
</dl>

<dl>
<dd>

**vehiclePlate:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**trailerPlate:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**driverName:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**driverSurname:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**loadWarehouseId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**loadAddress:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**unloadAddress:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**valueEur:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**saleInvoiceId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**series:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**lines:** `Optional<List<PostV1TransportWaybillsCreateRequestLinesItem>>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.transport.postV1TransportWaybillsUpdate(request) -> PostV1TransportWaybillsUpdateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.transport().postV1TransportWaybillsUpdate(
    PostV1TransportWaybillsUpdateRequest
        .builder()
        .id("id")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**consigneePartnerId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**transporterPartnerId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**documentDate:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**dispatchAt:** `Optional<OffsetDateTime>` 
    
</dd>
</dl>

<dl>
<dd>

**estimatedArrivalAt:** `Optional<OffsetDateTime>` 
    
</dd>
</dl>

<dl>
<dd>

**vehiclePlate:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**trailerPlate:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**driverName:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**driverSurname:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**loadWarehouseId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**loadAddress:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**unloadAddress:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**valueEur:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**saleInvoiceId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**series:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**lines:** `Optional<List<PostV1TransportWaybillsUpdateRequestLinesItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**id:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.transport.postV1TransportWaybillsIssue(request) -> PostV1TransportWaybillsIssueResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.transport().postV1TransportWaybillsIssue(
    PostV1TransportWaybillsIssueRequest
        .builder()
        .id("id")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.transport.postV1TransportWaybillsCancel(request) -> PostV1TransportWaybillsCancelResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.transport().postV1TransportWaybillsCancel(
    PostV1TransportWaybillsCancelRequest
        .builder()
        .id("id")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.transport.postV1TransportWaybillsGet(request) -> PostV1TransportWaybillsGetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.transport().postV1TransportWaybillsGet(
    PostV1TransportWaybillsGetRequest
        .builder()
        .id("id")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.transport.postV1TransportWaybillsList(request) -> PostV1TransportWaybillsListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.transport().postV1TransportWaybillsList(
    PostV1TransportWaybillsListRequest
        .builder()
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `Optional<List<PostV1TransportWaybillsListRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<PostV1TransportWaybillsListRequestFilterItem>>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Pos
<details><summary><code>client.pos.postV1PosDevicesCreate(request) -> PostV1PosDevicesCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.pos().postV1PosDevicesCreate(
    PostV1PosDevicesCreateRequest
        .builder()
        .name("name")
        .serialNumber("serialNumber")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**name:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**serialNumber:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**model:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**registrationNumber:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**address:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.pos.postV1PosDevicesUpdate(request) -> PostV1PosDevicesUpdateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.pos().postV1PosDevicesUpdate(
    PostV1PosDevicesUpdateRequest
        .builder()
        .id("id")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**isActive:** `Optional<Boolean>` 
    
</dd>
</dl>

<dl>
<dd>

**name:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**serialNumber:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**model:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**registrationNumber:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**address:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.pos.postV1PosDevicesList(request) -> PostV1PosDevicesListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.pos().postV1PosDevicesList(
    PostV1PosDevicesListRequest
        .builder()
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `Optional<List<PostV1PosDevicesListRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<PostV1PosDevicesListRequestFilterItem>>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.pos.postV1PosReportsCreate(request) -> PostV1PosReportsCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.pos().postV1PosReportsCreate(
    PostV1PosReportsCreateRequest
        .builder()
        .reportNumber("reportNumber")
        .date("date")
        .vatLines(
            Arrays.asList(
                PostV1PosReportsCreateRequestVatLinesItem
                    .builder()
                    .vatRatePercent("vatRatePercent")
                    .netAmount("netAmount")
                    .vatAmount("vatAmount")
                    .build()
            )
        )
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**reportNumber:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**date:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**deviceId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**warehouseId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**vatLines:** `List<PostV1PosReportsCreateRequestVatLinesItem>` 
    
</dd>
</dl>

<dl>
<dd>

**cashAmount:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**cardAmount:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**itemLines:** `Optional<List<PostV1PosReportsCreateRequestItemLinesItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**cashAccountCode:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**cardAccountCode:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**revenueAccountCode:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**vatAccountCode:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**cogsAccountCode:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**inventoryAccountCode:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.pos.postV1PosReportsGet(request) -> PostV1PosReportsGetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.pos().postV1PosReportsGet(
    PostV1PosReportsGetRequest
        .builder()
        .id("id")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.pos.postV1PosReportsList(request) -> PostV1PosReportsListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.pos().postV1PosReportsList(
    PostV1PosReportsListRequest
        .builder()
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `Optional<List<PostV1PosReportsListRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<PostV1PosReportsListRequestFilterItem>>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Audit
<details><summary><code>client.audit.postV1AuditList(request) -> PostV1AuditListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.audit().postV1AuditList(
    PostV1AuditListRequest
        .builder()
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `Optional<List<PostV1AuditListRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<PostV1AuditListRequestFilterItem>>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Webhooks
<details><summary><code>client.webhooks.postV1WebhooksSubscriptionsCreate(request) -> PostV1WebhooksSubscriptionsCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.webhooks().postV1WebhooksSubscriptionsCreate(
    PostV1WebhooksSubscriptionsCreateRequest
        .builder()
        .url("url")
        .events(
            Arrays.asList("events")
        )
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**url:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**events:** `List<String>` 
    
</dd>
</dl>

<dl>
<dd>

**secret:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.webhooks.postV1WebhooksSubscriptionsList(request) -> PostV1WebhooksSubscriptionsListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.webhooks().postV1WebhooksSubscriptionsList(
    PostV1WebhooksSubscriptionsListRequest
        .builder()
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `Optional<List<PostV1WebhooksSubscriptionsListRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<PostV1WebhooksSubscriptionsListRequestFilterItem>>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.webhooks.postV1WebhooksSubscriptionsUpdate(request) -> PostV1WebhooksSubscriptionsUpdateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.webhooks().postV1WebhooksSubscriptionsUpdate(
    PostV1WebhooksSubscriptionsUpdateRequest
        .builder()
        .id("id")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**url:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**events:** `Optional<List<String>>` 
    
</dd>
</dl>

<dl>
<dd>

**isActive:** `Optional<Boolean>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.webhooks.postV1WebhooksSubscriptionsDelete(request) -> PostV1WebhooksSubscriptionsDeleteResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.webhooks().postV1WebhooksSubscriptionsDelete(
    PostV1WebhooksSubscriptionsDeleteRequest
        .builder()
        .id("id")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.webhooks.postV1WebhooksDeliveriesList(request) -> PostV1WebhooksDeliveriesListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.webhooks().postV1WebhooksDeliveriesList(
    PostV1WebhooksDeliveriesListRequest
        .builder()
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `Optional<List<PostV1WebhooksDeliveriesListRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<PostV1WebhooksDeliveriesListRequestFilterItem>>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.webhooks.postV1WebhooksDeliveriesRedeliver(request) -> PostV1WebhooksDeliveriesRedeliverResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.webhooks().postV1WebhooksDeliveriesRedeliver(
    PostV1WebhooksDeliveriesRedeliverRequest
        .builder()
        .id("id")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Bank
<details><summary><code>client.bank.postV1BankAccountsCreate(request) -> PostV1BankAccountsCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.bank().postV1BankAccountsCreate(
    PostV1BankAccountsCreateRequest
        .builder()
        .name("name")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**name:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**iban:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**currency:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**accountCode:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.bank.postV1BankAccountsList(request) -> PostV1BankAccountsListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.bank().postV1BankAccountsList(
    PostV1BankAccountsListRequest
        .builder()
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `Optional<List<PostV1BankAccountsListRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<PostV1BankAccountsListRequestFilterItem>>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.bank.postV1BankAccountsUpdate(request) -> PostV1BankAccountsUpdateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.bank().postV1BankAccountsUpdate(
    PostV1BankAccountsUpdateRequest
        .builder()
        .id("id")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**name:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**iban:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**accountCode:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**isActive:** `Optional<Boolean>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.bank.postV1BankTransactionsImport(request) -> PostV1BankTransactionsImportResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.bank().postV1BankTransactionsImport(
    PostV1BankTransactionsImportRequest
        .builder()
        .bankAccountId("bankAccountId")
        .transactions(
            Arrays.asList(
                PostV1BankTransactionsImportRequestTransactionsItem
                    .builder()
                    .date("date")
                    .amount("amount")
                    .build()
            )
        )
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**bankAccountId:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**transactions:** `List<PostV1BankTransactionsImportRequestTransactionsItem>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.bank.postV1BankStatementsImport(request) -> PostV1BankStatementsImportResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.bank().postV1BankStatementsImport(
    PostV1BankStatementsImportRequest
        .builder()
        .bankAccountId("bankAccountId")
        .content("content")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**bankAccountId:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**format:** `Optional<PostV1BankStatementsImportRequestFormat>` 
    
</dd>
</dl>

<dl>
<dd>

**content:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.bank.postV1BankTransactionsList(request) -> PostV1BankTransactionsListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.bank().postV1BankTransactionsList(
    PostV1BankTransactionsListRequest
        .builder()
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `Optional<List<PostV1BankTransactionsListRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<PostV1BankTransactionsListRequestFilterItem>>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.bank.postV1BankTransactionsMatch(request) -> PostV1BankTransactionsMatchResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.bank().postV1BankTransactionsMatch(
    PostV1BankTransactionsMatchRequest
        .builder()
        .transactionId("transactionId")
        .documentType(PostV1BankTransactionsMatchRequestDocumentType.SALE_INVOICE)
        .documentId("documentId")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**transactionId:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**documentType:** `PostV1BankTransactionsMatchRequestDocumentType` 
    
</dd>
</dl>

<dl>
<dd>

**documentId:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.bank.postV1BankPaymentsExport(request) -> PostV1BankPaymentsExportResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.bank().postV1BankPaymentsExport(
    PostV1BankPaymentsExportRequest
        .builder()
        .bankAccountId("bankAccountId")
        .purchaseInvoiceIds(
            Arrays.asList("purchaseInvoiceIds")
        )
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**bankAccountId:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**purchaseInvoiceIds:** `List<String>` 
    
</dd>
</dl>

<dl>
<dd>

**executionDate:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.bank.postV1BankTransactionsSuggestMatches(request) -> PostV1BankTransactionsSuggestMatchesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.bank().postV1BankTransactionsSuggestMatches(
    PostV1BankTransactionsSuggestMatchesRequest
        .builder()
        .transactionId("transactionId")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**transactionId:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**limit:** `Optional<Long>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.bank.postV1BankSettlementsImport(request) -> PostV1BankSettlementsImportResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.bank().postV1BankSettlementsImport(
    PostV1BankSettlementsImportRequest
        .builder()
        .bankAccountId("bankAccountId")
        .content("content")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**bankAccountId:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**provider:** `Optional<PostV1BankSettlementsImportRequestProvider>` 
    
</dd>
</dl>

<dl>
<dd>

**content:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.bank.postV1BankSettlementsList(request) -> PostV1BankSettlementsListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.bank().postV1BankSettlementsList(
    PostV1BankSettlementsListRequest
        .builder()
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `Optional<List<PostV1BankSettlementsListRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<PostV1BankSettlementsListRequestFilterItem>>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.bank.postV1BankSettlementsGet(request) -> PostV1BankSettlementsGetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.bank().postV1BankSettlementsGet(
    PostV1BankSettlementsGetRequest
        .builder()
        .id("id")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.bank.postV1BankSettlementsMatch(request) -> PostV1BankSettlementsMatchResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.bank().postV1BankSettlementsMatch(
    PostV1BankSettlementsMatchRequest
        .builder()
        .lineId("lineId")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**lineId:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**invoiceId:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.bank.postV1BankSettlementsPost(request) -> PostV1BankSettlementsPostResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.bank().postV1BankSettlementsPost(
    PostV1BankSettlementsPostRequest
        .builder()
        .id("id")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**date:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**commissionPercent:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Files
<details><summary><code>client.files.postV1FilesUpload(request) -> PostV1FilesUploadResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.files().postV1FilesUpload(
    PostV1FilesUploadRequest
        .builder()
        .entity("entity")
        .entityId("entityId")
        .fileName("fileName")
        .mimeType("mimeType")
        .content("content")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**entity:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**entityId:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**fileName:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**mimeType:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**content:** `String` — Base64-encoded file content
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.files.postV1FilesGet(request) -> PostV1FilesGetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.files().postV1FilesGet(
    PostV1FilesGetRequest
        .builder()
        .id("id")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.files.postV1FilesList(request) -> PostV1FilesListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.files().postV1FilesList(
    PostV1FilesListRequest
        .builder()
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `Optional<List<PostV1FilesListRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<PostV1FilesListRequestFilterItem>>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.files.postV1FilesDelete(request) -> PostV1FilesDeleteResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.files().postV1FilesDelete(
    PostV1FilesDeleteRequest
        .builder()
        .id("id")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Reports
<details><summary><code>client.reports.postV1ReportsTrialBalance(request) -> PostV1ReportsTrialBalanceResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.reports().postV1ReportsTrialBalance(
    PostV1ReportsTrialBalanceRequest
        .builder()
        .fromDate("fromDate")
        .toDate("toDate")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**fromDate:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**toDate:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.reports.postV1ReportsSizeCategory(request) -> PostV1ReportsSizeCategoryResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.reports().postV1ReportsSizeCategory(
    PostV1ReportsSizeCategoryRequest
        .builder()
        .year(1000000L)
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**year:** `Long` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.reports.postV1ReportsFinancialStatements(request) -> PostV1ReportsFinancialStatementsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.reports().postV1ReportsFinancialStatements(
    PostV1ReportsFinancialStatementsRequest
        .builder()
        .fromDate("fromDate")
        .toDate("toDate")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**fromDate:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**toDate:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**category:** `Optional<PostV1ReportsFinancialStatementsRequestCategory>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.reports.postV1ReportsGeneralJournal(request) -> PostV1ReportsGeneralJournalResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.reports().postV1ReportsGeneralJournal(
    PostV1ReportsGeneralJournalRequest
        .builder()
        .fromDate("fromDate")
        .toDate("toDate")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**fromDate:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**toDate:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**page:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `Optional<Long>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.reports.postV1ReportsGlDetail(request) -> PostV1ReportsGlDetailResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.reports().postV1ReportsGlDetail(
    PostV1ReportsGlDetailRequest
        .builder()
        .accountCode("accountCode")
        .fromDate("fromDate")
        .toDate("toDate")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**accountCode:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**fromDate:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**toDate:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.reports.postV1ReportsPartnerBalances(request) -> PostV1ReportsPartnerBalancesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.reports().postV1ReportsPartnerBalances(
    PostV1ReportsPartnerBalancesRequest
        .builder()
        .build()
);
```
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.reports.postV1ReportsDebtAging(request) -> PostV1ReportsDebtAgingResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.reports().postV1ReportsDebtAging(
    PostV1ReportsDebtAgingRequest
        .builder()
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**side:** `Optional<PostV1ReportsDebtAgingRequestSide>` 
    
</dd>
</dl>

<dl>
<dd>

**asOf:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.reports.postV1ReportsMonthlySummary(request) -> PostV1ReportsMonthlySummaryResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.reports().postV1ReportsMonthlySummary(
    PostV1ReportsMonthlySummaryRequest
        .builder()
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**months:** `Optional<Long>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.reports.postV1ReportsStockBalance(request) -> PostV1ReportsStockBalanceResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.reports().postV1ReportsStockBalance(
    PostV1ReportsStockBalanceRequest
        .builder()
        .asOf("asOf")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**asOf:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**warehouseId:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.reports.postV1ReportsStockMovement(request) -> PostV1ReportsStockMovementResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.reports().postV1ReportsStockMovement(
    PostV1ReportsStockMovementRequest
        .builder()
        .fromDate("fromDate")
        .toDate("toDate")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**fromDate:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**toDate:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**warehouseId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**itemId:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.reports.postV1ReportsVatSummary(request) -> PostV1ReportsVatSummaryResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.reports().postV1ReportsVatSummary(
    PostV1ReportsVatSummaryRequest
        .builder()
        .fromDate("fromDate")
        .toDate("toDate")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**fromDate:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**toDate:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**side:** `Optional<PostV1ReportsVatSummaryRequestSide>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.reports.postV1ReportsCashFlow(request) -> PostV1ReportsCashFlowResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.reports().postV1ReportsCashFlow(
    PostV1ReportsCashFlowRequest
        .builder()
        .fromDate("fromDate")
        .toDate("toDate")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**fromDate:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**toDate:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.reports.postV1ReportsStockAging(request) -> PostV1ReportsStockAgingResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.reports().postV1ReportsStockAging(
    PostV1ReportsStockAgingRequest
        .builder()
        .asOf("asOf")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**asOf:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**warehouseId:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.reports.postV1ReportsStockShortage(request) -> PostV1ReportsStockShortageResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.reports().postV1ReportsStockShortage(
    PostV1ReportsStockShortageRequest
        .builder()
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**warehouseId:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.reports.postV1ReportsEuPurchases(request) -> PostV1ReportsEuPurchasesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.reports().postV1ReportsEuPurchases(
    PostV1ReportsEuPurchasesRequest
        .builder()
        .fromDate("fromDate")
        .toDate("toDate")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**fromDate:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**toDate:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.reports.postV1ReportsVatDetail(request) -> PostV1ReportsVatDetailResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.reports().postV1ReportsVatDetail(
    PostV1ReportsVatDetailRequest
        .builder()
        .fromDate("fromDate")
        .toDate("toDate")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**fromDate:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**toDate:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**side:** `Optional<PostV1ReportsVatDetailRequestSide>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.reports.postV1ReportsPosSales(request) -> PostV1ReportsPosSalesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.reports().postV1ReportsPosSales(
    PostV1ReportsPosSalesRequest
        .builder()
        .fromDate("fromDate")
        .toDate("toDate")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**fromDate:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**toDate:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.reports.postV1ReportsOnlineSales(request) -> PostV1ReportsOnlineSalesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.reports().postV1ReportsOnlineSales(
    PostV1ReportsOnlineSalesRequest
        .builder()
        .fromDate("fromDate")
        .toDate("toDate")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**fromDate:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**toDate:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.reports.postV1ReportsOss(request) -> PostV1ReportsOssResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.reports().postV1ReportsOss(
    PostV1ReportsOssRequest
        .builder()
        .fromDate("fromDate")
        .toDate("toDate")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**fromDate:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**toDate:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.reports.postV1ReportsAdvanceReconciliation(request) -> PostV1ReportsAdvanceReconciliationResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.reports().postV1ReportsAdvanceReconciliation(
    PostV1ReportsAdvanceReconciliationRequest
        .builder()
        .fromDate("fromDate")
        .toDate("toDate")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**fromDate:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**toDate:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.reports.postV1ReportsWriteOffActs(request) -> PostV1ReportsWriteOffActsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.reports().postV1ReportsWriteOffActs(
    PostV1ReportsWriteOffActsRequest
        .builder()
        .fromDate("fromDate")
        .toDate("toDate")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**fromDate:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**toDate:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**warehouseId:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.reports.postV1ReportsCostCenters(request) -> PostV1ReportsCostCentersResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.reports().postV1ReportsCostCenters(
    PostV1ReportsCostCentersRequest
        .builder()
        .fromDate("fromDate")
        .toDate("toDate")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**fromDate:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**toDate:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.reports.postV1ReportsCostCenterActivity(request) -> PostV1ReportsCostCenterActivityResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.reports().postV1ReportsCostCenterActivity(
    PostV1ReportsCostCenterActivityRequest
        .builder()
        .fromDate("fromDate")
        .toDate("toDate")
        .costCenterId("costCenterId")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**fromDate:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**toDate:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**costCenterId:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.reports.postV1ReportsCostCenterItems(request) -> PostV1ReportsCostCenterItemsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.reports().postV1ReportsCostCenterItems(
    PostV1ReportsCostCenterItemsRequest
        .builder()
        .fromDate("fromDate")
        .toDate("toDate")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**fromDate:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**toDate:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**costCenterId:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.reports.postV1ReportsJobsCreate(request) -> PostV1ReportsJobsCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.reports().postV1ReportsJobsCreate(
    PostV1ReportsJobsCreateRequest
        .builder()
        .reportType("reportType")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**reportType:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**params:** `Optional<Map<String, Object>>` 
    
</dd>
</dl>

<dl>
<dd>

**formats:** `Optional<List<PostV1ReportsJobsCreateRequestFormatsItem>>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.reports.postV1ReportsJobsGet(request) -> PostV1ReportsJobsGetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.reports().postV1ReportsJobsGet(
    PostV1ReportsJobsGetRequest
        .builder()
        .id("id")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.reports.postV1ReportsJobsList(request) -> PostV1ReportsJobsListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.reports().postV1ReportsJobsList(
    PostV1ReportsJobsListRequest
        .builder()
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**sort:** `Optional<List<PostV1ReportsJobsListRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<PostV1ReportsJobsListRequestFilterItem>>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Consolidation
<details><summary><code>client.consolidation.postV1ConsolidationGroupsCreate(request) -> PostV1ConsolidationGroupsCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.consolidation().postV1ConsolidationGroupsCreate(
    PostV1ConsolidationGroupsCreateRequest
        .builder()
        .name("name")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**name:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**presentationCurrency:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.consolidation.postV1ConsolidationGroupsList(request) -> PostV1ConsolidationGroupsListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.consolidation().postV1ConsolidationGroupsList(
    PostV1ConsolidationGroupsListRequest
        .builder()
        .build()
);
```
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.consolidation.postV1ConsolidationGroupsGet(request) -> PostV1ConsolidationGroupsGetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.consolidation().postV1ConsolidationGroupsGet(
    PostV1ConsolidationGroupsGetRequest
        .builder()
        .groupId("groupId")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**groupId:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.consolidation.postV1ConsolidationGroupsUpdate(request) -> PostV1ConsolidationGroupsUpdateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.consolidation().postV1ConsolidationGroupsUpdate(
    PostV1ConsolidationGroupsUpdateRequest
        .builder()
        .groupId("groupId")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**groupId:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**name:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**presentationCurrency:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.consolidation.postV1ConsolidationGroupsDelete(request) -> PostV1ConsolidationGroupsDeleteResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.consolidation().postV1ConsolidationGroupsDelete(
    PostV1ConsolidationGroupsDeleteRequest
        .builder()
        .groupId("groupId")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**groupId:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.consolidation.postV1ConsolidationMembersAdd(request) -> PostV1ConsolidationMembersAddResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.consolidation().postV1ConsolidationMembersAdd(
    PostV1ConsolidationMembersAddRequest
        .builder()
        .groupId("groupId")
        .memberCompanyId("memberCompanyId")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**groupId:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**memberCompanyId:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**ownershipPercent:** `Optional<Double>` 
    
</dd>
</dl>

<dl>
<dd>

**method:** `Optional<PostV1ConsolidationMembersAddRequestMethod>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.consolidation.postV1ConsolidationMembersRemove(request) -> PostV1ConsolidationMembersRemoveResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.consolidation().postV1ConsolidationMembersRemove(
    PostV1ConsolidationMembersRemoveRequest
        .builder()
        .groupId("groupId")
        .memberCompanyId("memberCompanyId")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**groupId:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**memberCompanyId:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.consolidation.postV1ConsolidationReport(request) -> PostV1ConsolidationReportResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.consolidation().postV1ConsolidationReport(
    PostV1ConsolidationReportRequest
        .builder()
        .groupId("groupId")
        .fromDate("fromDate")
        .toDate("toDate")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**groupId:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**fromDate:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**toDate:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**category:** `Optional<PostV1ConsolidationReportRequestCategory>` 
    
</dd>
</dl>

<dl>
<dd>

**eliminations:** `Optional<List<PostV1ConsolidationReportRequestEliminationsItem>>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Public
<details><summary><code>client.public_.postV1PublicIntegrationRequests(request) -> PostV1PublicIntegrationRequestsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.public_().postV1PublicIntegrationRequests(
    PostV1PublicIntegrationRequestsRequest
        .builder()
        .integration("integration")
        .name("name")
        .email("email")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**integration:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**name:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**company:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**email:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**details:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**website:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Account
<details><summary><code>client.account.postV1AccountLoginLinkRequest(request) -> PostV1AccountLoginLinkRequestResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.account().postV1AccountLoginLinkRequest(
    PostV1AccountLoginLinkRequestRequest
        .builder()
        .email("email")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**email:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**locale:** `Optional<PostV1AccountLoginLinkRequestRequestLocale>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.account.postV1AccountLoginLinkConsume(request) -> PostV1AccountLoginLinkConsumeResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.account().postV1AccountLoginLinkConsume(
    PostV1AccountLoginLinkConsumeRequest
        .builder()
        .token("token")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**token:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.account.postV1AccountLogout(request) -> PostV1AccountLogoutResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.account().postV1AccountLogout(
    PostV1AccountLogoutRequest
        .builder()
        .build()
);
```
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.account.postV1AccountMe(request) -> PostV1AccountMeResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.account().postV1AccountMe(
    PostV1AccountMeRequest
        .builder()
        .build()
);
```
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.account.postV1AccountMembersList(request) -> PostV1AccountMembersListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.account().postV1AccountMembersList(
    PostV1AccountMembersListRequest
        .builder()
        .build()
);
```
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.account.postV1AccountMembersSetRole(request) -> PostV1AccountMembersSetRoleResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.account().postV1AccountMembersSetRole(
    PostV1AccountMembersSetRoleRequest
        .builder()
        .userId("userId")
        .role(PostV1AccountMembersSetRoleRequestRole.ADMIN)
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**userId:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**role:** `PostV1AccountMembersSetRoleRequestRole` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.account.postV1AccountMembersRemove(request) -> PostV1AccountMembersRemoveResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.account().postV1AccountMembersRemove(
    PostV1AccountMembersRemoveRequest
        .builder()
        .userId("userId")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**userId:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.account.postV1AccountInvitesCreate(request) -> PostV1AccountInvitesCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.account().postV1AccountInvitesCreate(
    PostV1AccountInvitesCreateRequest
        .builder()
        .email("email")
        .role(PostV1AccountInvitesCreateRequestRole.ADMIN)
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**email:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**role:** `PostV1AccountInvitesCreateRequestRole` 
    
</dd>
</dl>

<dl>
<dd>

**locale:** `Optional<PostV1AccountInvitesCreateRequestLocale>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.account.postV1AccountInvitesList(request) -> PostV1AccountInvitesListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.account().postV1AccountInvitesList(
    PostV1AccountInvitesListRequest
        .builder()
        .build()
);
```
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.account.postV1AccountInvitesRevoke(request) -> PostV1AccountInvitesRevokeResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.account().postV1AccountInvitesRevoke(
    PostV1AccountInvitesRevokeRequest
        .builder()
        .id("id")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.account.postV1AccountInvitesGet(request) -> PostV1AccountInvitesGetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.account().postV1AccountInvitesGet(
    PostV1AccountInvitesGetRequest
        .builder()
        .token("token")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**token:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.account.postV1AccountInvitesAccept(request) -> PostV1AccountInvitesAcceptResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.account().postV1AccountInvitesAccept(
    PostV1AccountInvitesAcceptRequest
        .builder()
        .token("token")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**token:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**name:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**locale:** `Optional<PostV1AccountInvitesAcceptRequestLocale>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.account.postV1AccountLocaleSet(request) -> PostV1AccountLocaleSetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.account().postV1AccountLocaleSet(
    PostV1AccountLocaleSetRequest
        .builder()
        .locale(PostV1AccountLocaleSetRequestLocale.LT)
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**locale:** `PostV1AccountLocaleSetRequestLocale` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.account.postV1AccountCompaniesCreate(request) -> PostV1AccountCompaniesCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.account().postV1AccountCompaniesCreate(
    PostV1AccountCompaniesCreateRequest
        .builder()
        .name("name")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**name:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**code:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**vatCode:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**isVatPayer:** `Optional<Boolean>` 
    
</dd>
</dl>

<dl>
<dd>

**address:** `Optional<PostV1AccountCompaniesCreateRequestAddress>` 
    
</dd>
</dl>

<dl>
<dd>

**email:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**phone:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**iban:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**bankName:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**peppolId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**defaultInvoiceCurrency:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**countryCode:** `Optional<PostV1AccountCompaniesCreateRequestCountryCode>` — Jurisdiction the company is registered in (immutable after creation)
    
</dd>
</dl>

<dl>
<dd>

**isSandbox:** `Optional<Boolean>` — Sandbox companies hold test data and are purged immediately on delete (immutable after creation)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.account.postV1AccountCompaniesSelect(request) -> PostV1AccountCompaniesSelectResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.account().postV1AccountCompaniesSelect(
    PostV1AccountCompaniesSelectRequest
        .builder()
        .companyId("companyId")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**companyId:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.account.postV1AccountCompaniesProfile(request) -> PostV1AccountCompaniesProfileResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.account().postV1AccountCompaniesProfile(
    PostV1AccountCompaniesProfileRequest
        .builder()
        .build()
);
```
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.account.postV1AccountCompaniesUpdate(request) -> PostV1AccountCompaniesUpdateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.account().postV1AccountCompaniesUpdate(
    PostV1AccountCompaniesUpdateRequest
        .builder()
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**name:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**code:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**vatCode:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**isVatPayer:** `Optional<Boolean>` 
    
</dd>
</dl>

<dl>
<dd>

**address:** `Optional<PostV1AccountCompaniesUpdateRequestAddress>` 
    
</dd>
</dl>

<dl>
<dd>

**email:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**phone:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**iban:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**bankName:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**peppolId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**defaultInvoiceCurrency:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**logo:** `Optional<PostV1AccountCompaniesUpdateRequestLogo>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.account.postV1AccountCompaniesArchive(request) -> PostV1AccountCompaniesArchiveResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.account().postV1AccountCompaniesArchive(
    PostV1AccountCompaniesArchiveRequest
        .builder()
        .companyId("companyId")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**companyId:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.account.postV1AccountCompaniesDelete(request) -> PostV1AccountCompaniesDeleteResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.account().postV1AccountCompaniesDelete(
    PostV1AccountCompaniesDeleteRequest
        .builder()
        .companyId("companyId")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**companyId:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.account.postV1AccountCompaniesActivate(request) -> PostV1AccountCompaniesActivateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.account().postV1AccountCompaniesActivate(
    PostV1AccountCompaniesActivateRequest
        .builder()
        .companyId("companyId")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**companyId:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.account.postV1AccountApiKeysCreate(request) -> PostV1AccountApiKeysCreateResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.account().postV1AccountApiKeysCreate(
    PostV1AccountApiKeysCreateRequest
        .builder()
        .name("name")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**name:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**scopes:** `Optional<List<String>>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.account.postV1AccountApiKeysList(request) -> PostV1AccountApiKeysListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.account().postV1AccountApiKeysList(
    PostV1AccountApiKeysListRequest
        .builder()
        .build()
);
```
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.account.postV1AccountApiKeysRevoke(request) -> PostV1AccountApiKeysRevokeResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.account().postV1AccountApiKeysRevoke(
    PostV1AccountApiKeysRevokeRequest
        .builder()
        .id("id")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

