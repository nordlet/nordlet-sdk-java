# Reference
## reference
<details><summary><code>client.reference.exchangeRatesSync(request) -> ExchangeRatesSyncReferenceResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.reference().exchangeRatesSync(
    ExchangeRatesSyncReferenceRequest
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

<details><summary><code>client.reference.exchangeRatesList(request) -> ExchangeRatesListReferenceResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.reference().exchangeRatesList(
    ExchangeRatesListReferenceRequest
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

**sort:** `Optional<List<ExchangeRatesListReferenceRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<ExchangeRatesListReferenceRequestFilterItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `Optional<List<String>>` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.reference.exchangeRatesSet(request) -> ExchangeRatesSetReferenceResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.reference().exchangeRatesSet(
    ExchangeRatesSetReferenceRequest
        .builder()
        .currency("currency")
        .date("2026-07-01")
        .rate("121.00000000")
        .build()
);
```
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

<details><summary><code>client.reference.exchangeRatesOverridesList(request) -> ExchangeRatesOverridesListReferenceResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.reference().exchangeRatesOverridesList(
    ExchangeRatesOverridesListReferenceRequest
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

**sort:** `Optional<List<ExchangeRatesOverridesListReferenceRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<ExchangeRatesOverridesListReferenceRequestFilterItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `Optional<List<String>>` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.reference.exchangeRatesOverridesDelete(request) -> ExchangeRatesOverridesDeleteReferenceResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.reference().exchangeRatesOverridesDelete(
    ExchangeRatesOverridesDeleteReferenceRequest
        .builder()
        .currency("currency")
        .date("2026-07-01")
        .build()
);
```
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

<details><summary><code>client.reference.countriesList(request) -> CountriesListReferenceResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.reference().countriesList(
    CountriesListReferenceRequest
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

<details><summary><code>client.reference.ltCountiesList(request) -> LtCountiesListReferenceResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.reference().ltCountiesList(
    LtCountiesListReferenceRequest
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

<details><summary><code>client.reference.ltMunicipalitiesList(request) -> LtMunicipalitiesListReferenceResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.reference().ltMunicipalitiesList(
    LtMunicipalitiesListReferenceRequest
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

**countyCode:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.reference.ltCitiesList(request) -> LtCitiesListReferenceResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.reference().ltCitiesList(
    LtCitiesListReferenceRequest
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

**municipalityCode:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**q:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.reference.banksList(request) -> BanksListReferenceResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.reference().banksList(
    BanksListReferenceRequest
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

**sort:** `Optional<List<BanksListReferenceRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<BanksListReferenceRequestFilterItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `Optional<List<String>>` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.reference.banksUpsert(request) -> BanksUpsertReferenceResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.reference().banksUpsert(
    BanksUpsertReferenceRequest
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

<details><summary><code>client.reference.ltRegionsList(request) -> LtRegionsListReferenceResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.reference().ltRegionsList(
    LtRegionsListReferenceRequest
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

<details><summary><code>client.reference.currenciesList(request) -> CurrenciesListReferenceResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.reference().currenciesList(
    CurrenciesListReferenceRequest
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

**sort:** `Optional<List<CurrenciesListReferenceRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<CurrenciesListReferenceRequestFilterItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `Optional<List<String>>` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.reference.vatClassifiersList(request) -> VatClassifiersListReferenceResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.reference().vatClassifiersList(
    VatClassifiersListReferenceRequest
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

**sort:** `Optional<List<VatClassifiersListReferenceRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<VatClassifiersListReferenceRequestFilterItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `Optional<List<String>>` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.reference.vatClassifiersUpsert(request) -> VatClassifiersUpsertReferenceResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.reference().vatClassifiersUpsert(
    VatClassifiersUpsertReferenceRequest
        .builder()
        .rows(
            Arrays.asList(
                VatClassifiersUpsertReferenceRequestRowsItem
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

**rows:** `List<VatClassifiersUpsertReferenceRequestRowsItem>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.reference.euVatRatesList(request) -> EuVatRatesListReferenceResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Effective EU VAT rate mapping for this company: EC TEDB defaults, replaced per country by any company overrides. Verify the mapping fits the goods and services you sell before relying on it.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.reference().euVatRatesList(
    EuVatRatesListReferenceRequest
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

<details><summary><code>client.reference.euVatRatesSetOverrides(request) -> EuVatRatesSetOverridesReferenceResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Replace the VAT rate mapping this company uses for one EU country. Pass an empty rates array to drop the overrides and return to the TEDB defaults. Overrides feed rate suggestions (vat/resolve) and OSS/IOSS return rate classification.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.reference().euVatRatesSetOverrides(
    EuVatRatesSetOverridesReferenceRequest
        .builder()
        .countryCode("countryCode")
        .rates(
            Arrays.asList(
                EuVatRatesSetOverridesReferenceRequestRatesItem
                    .builder()
                    .category(EuVatRatesSetOverridesReferenceRequestRatesItemCategory.STANDARD)
                    .ratePercent("121.00")
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

**countryCode:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**rates:** `List<EuVatRatesSetOverridesReferenceRequestRatesItem>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.reference.vatResolve(request) -> VatResolveReferenceResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.reference().vatResolve(
    VatResolveReferenceRequest
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

**supplyType:** `Optional<VatResolveReferenceRequestSupplyType>` 
    
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

<details><summary><code>client.reference.cnCodesList(request) -> CnCodesListReferenceResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.reference().cnCodesList(
    CnCodesListReferenceRequest
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

**sort:** `Optional<List<CnCodesListReferenceRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<CnCodesListReferenceRequestFilterItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `Optional<List<String>>` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.reference.cnCodesUpsert(request) -> CnCodesUpsertReferenceResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.reference().cnCodesUpsert(
    CnCodesUpsertReferenceRequest
        .builder()
        .rows(
            Arrays.asList(
                CnCodesUpsertReferenceRequestRowsItem
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

**rows:** `List<CnCodesUpsertReferenceRequestRowsItem>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.reference.complianceVersionsList(request) -> ComplianceVersionsListReferenceResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.reference().complianceVersionsList(
    ComplianceVersionsListReferenceRequest
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

<details><summary><code>client.reference.intrastatThresholdsList(request) -> IntrastatThresholdsListReferenceResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.reference().intrastatThresholdsList(
    IntrastatThresholdsListReferenceRequest
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

<details><summary><code>client.reference.unitsList(request) -> UnitsListReferenceResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.reference().unitsList(
    UnitsListReferenceRequest
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

**sort:** `Optional<List<UnitsListReferenceRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<UnitsListReferenceRequestFilterItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `Optional<List<String>>` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.reference.seriesCreate(request) -> SeriesCreateReferenceResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.reference().seriesCreate(
    SeriesCreateReferenceRequest
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

<details><summary><code>client.reference.seriesList(request) -> SeriesListReferenceResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.reference().seriesList(
    SeriesListReferenceRequest
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

**sort:** `Optional<List<SeriesListReferenceRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<SeriesListReferenceRequestFilterItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `Optional<List<String>>` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## partners
<details><summary><code>client.partners.addressesCreate(request) -> AddressesCreatePartnersResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.partners().addressesCreate(
    AddressesCreatePartnersRequest
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

**type:** `Optional<AddressesCreatePartnersRequestType>` 
    
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

<details><summary><code>client.partners.addressesUpdate(request) -> AddressesUpdatePartnersResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.partners().addressesUpdate(
    AddressesUpdatePartnersRequest
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

**type:** `Optional<AddressesUpdatePartnersRequestType>` 
    
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

<details><summary><code>client.partners.addressesDelete(request) -> AddressesDeletePartnersResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.partners().addressesDelete(
    AddressesDeletePartnersRequest
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

<details><summary><code>client.partners.addressesList(request) -> AddressesListPartnersResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.partners().addressesList(
    AddressesListPartnersRequest
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

**sort:** `Optional<List<AddressesListPartnersRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<AddressesListPartnersRequestFilterItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `Optional<List<String>>` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.partners.contactsCreate(request) -> ContactsCreatePartnersResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.partners().contactsCreate(
    ContactsCreatePartnersRequest
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

<details><summary><code>client.partners.contactsUpdate(request) -> ContactsUpdatePartnersResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.partners().contactsUpdate(
    ContactsUpdatePartnersRequest
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

<details><summary><code>client.partners.contactsDelete(request) -> ContactsDeletePartnersResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.partners().contactsDelete(
    ContactsDeletePartnersRequest
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

<details><summary><code>client.partners.contactsList(request) -> ContactsListPartnersResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.partners().contactsList(
    ContactsListPartnersRequest
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

**sort:** `Optional<List<ContactsListPartnersRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<ContactsListPartnersRequestFilterItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `Optional<List<String>>` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.partners.bankAccountsCreate(request) -> BankAccountsCreatePartnersResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.partners().bankAccountsCreate(
    BankAccountsCreatePartnersRequest
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

<details><summary><code>client.partners.bankAccountsUpdate(request) -> BankAccountsUpdatePartnersResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.partners().bankAccountsUpdate(
    BankAccountsUpdatePartnersRequest
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

<details><summary><code>client.partners.bankAccountsDelete(request) -> BankAccountsDeletePartnersResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.partners().bankAccountsDelete(
    BankAccountsDeletePartnersRequest
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

<details><summary><code>client.partners.bankAccountsList(request) -> BankAccountsListPartnersResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.partners().bankAccountsList(
    BankAccountsListPartnersRequest
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

**sort:** `Optional<List<BankAccountsListPartnersRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<BankAccountsListPartnersRequestFilterItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `Optional<List<String>>` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.partners.filesList(request) -> FilesListPartnersResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.partners().filesList(
    FilesListPartnersRequest
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
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.partners.debtRemindersPreview(request) -> DebtRemindersPreviewPartnersResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.partners().debtRemindersPreview(
    DebtRemindersPreviewPartnersRequest
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

<details><summary><code>client.partners.debtRemindersList(request) -> DebtRemindersListPartnersResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.partners().debtRemindersList(
    DebtRemindersListPartnersRequest
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

**sort:** `Optional<List<DebtRemindersListPartnersRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<DebtRemindersListPartnersRequestFilterItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `Optional<List<String>>` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.partners.validateVat(request) -> ValidateVatPartnersResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.partners().validateVat(
    ValidateVatPartnersRequest
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

<details><summary><code>client.partners.vatReviewsList(request) -> VatReviewsListPartnersResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.partners().vatReviewsList(
    VatReviewsListPartnersRequest
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

**sort:** `Optional<List<VatReviewsListPartnersRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<VatReviewsListPartnersRequestFilterItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `Optional<List<String>>` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.partners.vatReviewsResolve(request) -> VatReviewsResolvePartnersResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.partners().vatReviewsResolve(
    VatReviewsResolvePartnersRequest
        .builder()
        .id("id")
        .resolution(VatReviewsResolvePartnersRequestResolution.CONFIRMED_VALID)
        .build()
);
```
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

**resolution:** `VatReviewsResolvePartnersRequestResolution` 
    
</dd>
</dl>

<dl>
<dd>

**note:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.partners.create(request) -> CreatePartnersResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.partners().create(
    CreatePartnersRequest
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

**type:** `Optional<CreatePartnersRequestType>` 
    
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

**address:** `Optional<CreatePartnersRequestAddress>` 
    
</dd>
</dl>

<dl>
<dd>

**correspondenceAddress:** `Optional<CreatePartnersRequestCorrespondenceAddress>` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**documentRef:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**shortName:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**website:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**fax:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**eoriCode:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**otherCode:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**foreignTaxNumber:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**autoDebtReminder:** `Optional<Boolean>` 
    
</dd>
</dl>

<dl>
<dd>

**lateInterestPercent:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**firstCallDate:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**lastCallDate:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**nextCallDate:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**rating:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**isEmployee:** `Optional<Boolean>` 
    
</dd>
</dl>

<dl>
<dd>

**isGroupMember:** `Optional<Boolean>` 
    
</dd>
</dl>

<dl>
<dd>

**isActive:** `Optional<Boolean>` 
    
</dd>
</dl>

<dl>
<dd>

**legalCountryClass:** `Optional<CreatePartnersRequestLegalCountryClass>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.partners.findOrCreate(request) -> FindOrCreatePartnersResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.partners().findOrCreate(
    FindOrCreatePartnersRequest
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

**type:** `Optional<FindOrCreatePartnersRequestType>` 
    
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

**address:** `Optional<FindOrCreatePartnersRequestAddress>` 
    
</dd>
</dl>

<dl>
<dd>

**correspondenceAddress:** `Optional<FindOrCreatePartnersRequestCorrespondenceAddress>` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**documentRef:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**shortName:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**website:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**fax:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**eoriCode:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**otherCode:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**foreignTaxNumber:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**autoDebtReminder:** `Optional<Boolean>` 
    
</dd>
</dl>

<dl>
<dd>

**lateInterestPercent:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**firstCallDate:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**lastCallDate:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**nextCallDate:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**rating:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**isEmployee:** `Optional<Boolean>` 
    
</dd>
</dl>

<dl>
<dd>

**isGroupMember:** `Optional<Boolean>` 
    
</dd>
</dl>

<dl>
<dd>

**isActive:** `Optional<Boolean>` 
    
</dd>
</dl>

<dl>
<dd>

**legalCountryClass:** `Optional<FindOrCreatePartnersRequestLegalCountryClass>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.partners.get(request) -> GetPartnersResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.partners().get(
    GetPartnersRequest
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

<details><summary><code>client.partners.update(request) -> UpdatePartnersResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.partners().update(
    UpdatePartnersRequest
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

**type:** `Optional<UpdatePartnersRequestType>` 
    
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

**address:** `Optional<UpdatePartnersRequestAddress>` 
    
</dd>
</dl>

<dl>
<dd>

**correspondenceAddress:** `Optional<UpdatePartnersRequestCorrespondenceAddress>` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**documentRef:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**shortName:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**website:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**fax:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**eoriCode:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**otherCode:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**foreignTaxNumber:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**autoDebtReminder:** `Optional<Boolean>` 
    
</dd>
</dl>

<dl>
<dd>

**lateInterestPercent:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**firstCallDate:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**lastCallDate:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**nextCallDate:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**rating:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**isEmployee:** `Optional<Boolean>` 
    
</dd>
</dl>

<dl>
<dd>

**isGroupMember:** `Optional<Boolean>` 
    
</dd>
</dl>

<dl>
<dd>

**isActive:** `Optional<Boolean>` 
    
</dd>
</dl>

<dl>
<dd>

**legalCountryClass:** `Optional<UpdatePartnersRequestLegalCountryClass>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.partners.delete(request) -> DeletePartnersResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.partners().delete(
    DeletePartnersRequest
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

<details><summary><code>client.partners.anonymize(request) -> AnonymizePartnersResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Removes birth date, self-employment certificate number, email, phone, address, notes, contacts, addresses and bank accounts, then hides the partner. The name, code and VAT number stay because issued invoices must keep identifying the counterparty for the statutory retention period.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.partners().anonymize(
    AnonymizePartnersRequest
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

<details><summary><code>client.partners.list(request) -> ListPartnersResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.partners().list(
    ListPartnersRequest
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

**sort:** `Optional<List<ListPartnersRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<ListPartnersRequestFilterItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `Optional<List<String>>` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.partners.groupsCreate(request) -> GroupsCreatePartnersResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.partners().groupsCreate(
    GroupsCreatePartnersRequest
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

<details><summary><code>client.partners.groupsUpdate(request) -> GroupsUpdatePartnersResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.partners().groupsUpdate(
    GroupsUpdatePartnersRequest
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

<details><summary><code>client.partners.groupsDelete(request) -> GroupsDeletePartnersResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.partners().groupsDelete(
    GroupsDeletePartnersRequest
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

<details><summary><code>client.partners.groupsList(request) -> GroupsListPartnersResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.partners().groupsList(
    GroupsListPartnersRequest
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

<details><summary><code>client.partners.statusesCreate(request) -> StatusesCreatePartnersResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.partners().statusesCreate(
    StatusesCreatePartnersRequest
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

<details><summary><code>client.partners.statusesUpdate(request) -> StatusesUpdatePartnersResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.partners().statusesUpdate(
    StatusesUpdatePartnersRequest
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

<details><summary><code>client.partners.statusesDelete(request) -> StatusesDeletePartnersResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.partners().statusesDelete(
    StatusesDeletePartnersRequest
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

<details><summary><code>client.partners.statusesList(request) -> StatusesListPartnersResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.partners().statusesList(
    StatusesListPartnersRequest
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

<details><summary><code>client.partners.inquiriesCreate(request) -> InquiriesCreatePartnersResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.partners().inquiriesCreate(
    InquiriesCreatePartnersRequest
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

<details><summary><code>client.partners.inquiriesUpdate(request) -> InquiriesUpdatePartnersResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.partners().inquiriesUpdate(
    InquiriesUpdatePartnersRequest
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

**status:** `Optional<InquiriesUpdatePartnersRequestStatus>` 
    
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

<details><summary><code>client.partners.inquiriesGet(request) -> InquiriesGetPartnersResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.partners().inquiriesGet(
    InquiriesGetPartnersRequest
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

<details><summary><code>client.partners.inquiriesList(request) -> InquiriesListPartnersResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.partners().inquiriesList(
    InquiriesListPartnersRequest
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

**sort:** `Optional<List<InquiriesListPartnersRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<InquiriesListPartnersRequestFilterItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `Optional<List<String>>` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.partners.creditCheck(request) -> CreditCheckPartnersResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.partners().creditCheck(
    CreditCheckPartnersRequest
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

## Leads
<details><summary><code>client.leads.create(request) -> CreateLeadsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.leads().create(
    CreateLeadsRequest
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

**contactName:** `Optional<String>` 
    
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

**website:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**countryCode:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**sourceId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**status:** `Optional<CreateLeadsRequestStatus>` 
    
</dd>
</dl>

<dl>
<dd>

**estimatedValue:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**currency:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**description:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**assignedUserId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**documents:** `Optional<List<CreateLeadsRequestDocumentsItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `Optional<List<String>>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.leads.get(request) -> GetLeadsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.leads().get(
    GetLeadsRequest
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

<details><summary><code>client.leads.update(request) -> UpdateLeadsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.leads().update(
    UpdateLeadsRequest
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

**contactName:** `Optional<String>` 
    
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

**website:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**countryCode:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**sourceId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**status:** `Optional<UpdateLeadsRequestStatus>` 
    
</dd>
</dl>

<dl>
<dd>

**estimatedValue:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**currency:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**description:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**assignedUserId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**documents:** `Optional<List<UpdateLeadsRequestDocumentsItem>>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.leads.delete(request) -> DeleteLeadsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.leads().delete(
    DeleteLeadsRequest
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

<details><summary><code>client.leads.list(request) -> ListLeadsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.leads().list(
    ListLeadsRequest
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

**sort:** `Optional<List<ListLeadsRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<ListLeadsRequestFilterItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `Optional<List<String>>` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.leads.notesCreate(request) -> NotesCreateLeadsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.leads().notesCreate(
    NotesCreateLeadsRequest
        .builder()
        .leadId("leadId")
        .body("body")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**leadId:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**body:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.leads.notesDelete(request) -> NotesDeleteLeadsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.leads().notesDelete(
    NotesDeleteLeadsRequest
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

<details><summary><code>client.leads.notesList(request) -> NotesListLeadsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.leads().notesList(
    NotesListLeadsRequest
        .builder()
        .leadId("leadId")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**leadId:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.leads.filesList(request) -> FilesListLeadsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.leads().filesList(
    FilesListLeadsRequest
        .builder()
        .leadId("leadId")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**leadId:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.leads.sourcesCreate(request) -> SourcesCreateLeadsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.leads().sourcesCreate(
    SourcesCreateLeadsRequest
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

**isActive:** `Optional<Boolean>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.leads.sourcesUpdate(request) -> SourcesUpdateLeadsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.leads().sourcesUpdate(
    SourcesUpdateLeadsRequest
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
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.leads.sourcesDelete(request) -> SourcesDeleteLeadsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.leads().sourcesDelete(
    SourcesDeleteLeadsRequest
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

<details><summary><code>client.leads.sourcesList(request) -> SourcesListLeadsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.leads().sourcesList(
    SourcesListLeadsRequest
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

<details><summary><code>client.leads.sourcesOptions(request) -> SourcesOptionsLeadsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.leads().sourcesOptions(
    SourcesOptionsLeadsRequest
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

<details><summary><code>client.leads.convert(request) -> ConvertLeadsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Create a customer partner from the lead, move the lead files to the partner, copy the lead notes into the partner notes and mark the lead as converted.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.leads().convert(
    ConvertLeadsRequest
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

**partnerType:** `Optional<ConvertLeadsRequestPartnerType>` 
    
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
</dd>
</dl>


</dd>
</dl>
</details>

## catalog
<details><summary><code>client.catalog.itemsCreate(request) -> ItemsCreateCatalogResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.catalog().itemsCreate(
    ItemsCreateCatalogRequest
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

**type:** `Optional<ItemsCreateCatalogRequestType>` 
    
</dd>
</dl>

<dl>
<dd>

**tracking:** `Optional<ItemsCreateCatalogRequestTracking>` 
    
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

**documentRef:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**translations:** `Optional<Map<String, ItemsCreateCatalogRequestTranslationsValue>>` 
    
</dd>
</dl>

<dl>
<dd>

**components:** `Optional<List<ItemsCreateCatalogRequestComponentsItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**kindId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**saleAccountCode:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**purchaseAccountCode:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**expenseAccountCode:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**manufacturer:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**grossMassKg:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**minQuantity:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**costPrice:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**isFreePrice:** `Optional<Boolean>` 
    
</dd>
</dl>

<dl>
<dd>

**externalId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**isReturnable:** `Optional<Boolean>` 
    
</dd>
</dl>

<dl>
<dd>

**commentRequired:** `Optional<Boolean>` 
    
</dd>
</dl>

<dl>
<dd>

**priceFrom:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**priceTo:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**minPrice:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**discountPercent:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**maxDiscountPercent:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**loyaltyPoints:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**department:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**ageRestriction:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**packageQuantity:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**taraCode:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**certificateNumber:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**certificateDate:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**validFrom:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**validTo:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**posFlags:** `Optional<Map<String, Boolean>>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.catalog.itemsGet(request) -> ItemsGetCatalogResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.catalog().itemsGet(
    ItemsGetCatalogRequest
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

<details><summary><code>client.catalog.itemsUpdate(request) -> ItemsUpdateCatalogResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.catalog().itemsUpdate(
    ItemsUpdateCatalogRequest
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

**type:** `Optional<ItemsUpdateCatalogRequestType>` 
    
</dd>
</dl>

<dl>
<dd>

**tracking:** `Optional<ItemsUpdateCatalogRequestTracking>` 
    
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

**attributes:** `Optional<Map<String, Optional<String>>>` 
    
</dd>
</dl>

<dl>
<dd>

**documentRef:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**translations:** `Optional<Map<String, Optional<ItemsUpdateCatalogRequestTranslationsValue>>>` 
    
</dd>
</dl>

<dl>
<dd>

**components:** `Optional<List<ItemsUpdateCatalogRequestComponentsItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**kindId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**saleAccountCode:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**purchaseAccountCode:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**expenseAccountCode:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**manufacturer:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**grossMassKg:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**minQuantity:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**costPrice:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**isFreePrice:** `Optional<Boolean>` 
    
</dd>
</dl>

<dl>
<dd>

**externalId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**isReturnable:** `Optional<Boolean>` 
    
</dd>
</dl>

<dl>
<dd>

**commentRequired:** `Optional<Boolean>` 
    
</dd>
</dl>

<dl>
<dd>

**priceFrom:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**priceTo:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**minPrice:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**discountPercent:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**maxDiscountPercent:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**loyaltyPoints:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**department:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**ageRestriction:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**packageQuantity:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**taraCode:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**certificateNumber:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**certificateDate:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**validFrom:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**validTo:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**posFlags:** `Optional<Map<String, Optional<Boolean>>>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.catalog.itemsDelete(request) -> ItemsDeleteCatalogResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.catalog().itemsDelete(
    ItemsDeleteCatalogRequest
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

<details><summary><code>client.catalog.itemsList(request) -> ItemsListCatalogResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.catalog().itemsList(
    ItemsListCatalogRequest
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

**sort:** `Optional<List<ItemsListCatalogRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<ItemsListCatalogRequestFilterItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `Optional<List<String>>` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.catalog.itemsFilesList(request) -> ItemsFilesListCatalogResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.catalog().itemsFilesList(
    ItemsFilesListCatalogRequest
        .builder()
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

**itemId:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.catalog.itemsKindsCreate(request) -> ItemsKindsCreateCatalogResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.catalog().itemsKindsCreate(
    ItemsKindsCreateCatalogRequest
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

**saftType:** `Optional<ItemsKindsCreateCatalogRequestSaftType>` 
    
</dd>
</dl>

<dl>
<dd>

**quantityAccounting:** `Optional<Boolean>` 
    
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

<details><summary><code>client.catalog.itemsKindsUpdate(request) -> ItemsKindsUpdateCatalogResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.catalog().itemsKindsUpdate(
    ItemsKindsUpdateCatalogRequest
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

**saftType:** `Optional<ItemsKindsUpdateCatalogRequestSaftType>` 
    
</dd>
</dl>

<dl>
<dd>

**quantityAccounting:** `Optional<Boolean>` 
    
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

<details><summary><code>client.catalog.itemsKindsDelete(request) -> ItemsKindsDeleteCatalogResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.catalog().itemsKindsDelete(
    ItemsKindsDeleteCatalogRequest
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

<details><summary><code>client.catalog.itemsKindsList(request) -> ItemsKindsListCatalogResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.catalog().itemsKindsList(
    ItemsKindsListCatalogRequest
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

<details><summary><code>client.catalog.unitsCreate(request) -> UnitsCreateCatalogResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.catalog().unitsCreate(
    UnitsCreateCatalogRequest
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

**isActive:** `Optional<Boolean>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.catalog.unitsUpdate(request) -> UnitsUpdateCatalogResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.catalog().unitsUpdate(
    UnitsUpdateCatalogRequest
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

**isActive:** `Optional<Boolean>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.catalog.unitsDelete(request) -> UnitsDeleteCatalogResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.catalog().unitsDelete(
    UnitsDeleteCatalogRequest
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

<details><summary><code>client.catalog.unitsList(request) -> UnitsListCatalogResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.catalog().unitsList(
    UnitsListCatalogRequest
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

<details><summary><code>client.catalog.unitsOptions(request) -> UnitsOptionsCatalogResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.catalog().unitsOptions(
    UnitsOptionsCatalogRequest
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

**locale:** `Optional<UnitsOptionsCatalogRequestLocale>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.catalog.itemGroupsCreate(request) -> ItemGroupsCreateCatalogResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.catalog().itemGroupsCreate(
    ItemGroupsCreateCatalogRequest
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

<details><summary><code>client.catalog.itemGroupsUpdate(request) -> ItemGroupsUpdateCatalogResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.catalog().itemGroupsUpdate(
    ItemGroupsUpdateCatalogRequest
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

<details><summary><code>client.catalog.itemGroupsDelete(request) -> ItemGroupsDeleteCatalogResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.catalog().itemGroupsDelete(
    ItemGroupsDeleteCatalogRequest
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

<details><summary><code>client.catalog.itemGroupsList(request) -> ItemGroupsListCatalogResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.catalog().itemGroupsList(
    ItemGroupsListCatalogRequest
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

<details><summary><code>client.catalog.itemsSuppliersUpsert(request) -> ItemsSuppliersUpsertCatalogResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.catalog().itemsSuppliersUpsert(
    ItemsSuppliersUpsertCatalogRequest
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

<details><summary><code>client.catalog.itemsSuppliersList(request) -> ItemsSuppliersListCatalogResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.catalog().itemsSuppliersList(
    ItemsSuppliersListCatalogRequest
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

<details><summary><code>client.catalog.itemsSuppliersDelete(request) -> ItemsSuppliersDeleteCatalogResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.catalog().itemsSuppliersDelete(
    ItemsSuppliersDeleteCatalogRequest
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

<details><summary><code>client.catalog.priceListsCreate(request) -> PriceListsCreateCatalogResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.catalog().priceListsCreate(
    PriceListsCreateCatalogRequest
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

<details><summary><code>client.catalog.priceListsUpdate(request) -> PriceListsUpdateCatalogResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.catalog().priceListsUpdate(
    PriceListsUpdateCatalogRequest
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

<details><summary><code>client.catalog.priceListsList(request) -> PriceListsListCatalogResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.catalog().priceListsList(
    PriceListsListCatalogRequest
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

<details><summary><code>client.catalog.priceListsItemsSet(request) -> PriceListsItemsSetCatalogResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.catalog().priceListsItemsSet(
    PriceListsItemsSetCatalogRequest
        .builder()
        .priceListId("priceListId")
        .items(
            Arrays.asList(
                PriceListsItemsSetCatalogRequestItemsItem
                    .builder()
                    .itemId("itemId")
                    .unitPriceExclVat("121.0000")
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

**items:** `List<PriceListsItemsSetCatalogRequestItemsItem>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.catalog.priceListsItemsList(request) -> PriceListsItemsListCatalogResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.catalog().priceListsItemsList(
    PriceListsItemsListCatalogRequest
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

<details><summary><code>client.catalog.priceListsItemsDelete(request) -> PriceListsItemsDeleteCatalogResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.catalog().priceListsItemsDelete(
    PriceListsItemsDeleteCatalogRequest
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

## sales
<details><summary><code>client.sales.invoicesCreate(request) -> InvoicesCreateSalesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.sales().invoicesCreate(
    InvoicesCreateSalesRequest
        .builder()
        .partnerId("partnerId")
        .lines(
            Arrays.asList(
                InvoicesCreateSalesRequestLinesItem
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

**type:** `Optional<InvoicesCreateSalesRequestType>` 
    
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

**creditedInvoiceReference:** `Optional<String>` — Number of an original invoice issued outside Nordlet; give it with creditedInvoiceDate
    
</dd>
</dl>

<dl>
<dd>

**creditedInvoiceDate:** `Optional<String>` — Issue date of the original invoice issued outside Nordlet
    
</dd>
</dl>

<dl>
<dd>

**agreementId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**vatScheme:** `Optional<InvoicesCreateSalesRequestVatScheme>` 
    
</dd>
</dl>

<dl>
<dd>

**intrastatTransportMode:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**intrastatDeliveryTerms:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**intrastatRegion:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**intrastatNatureOfTransaction:** `Optional<String>` 
    
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

**documentRef:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**operationTypeId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**documentSeriesId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**seriesLabel:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**orderNumber:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**issuedByName:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**issuedByTitle:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**receivedByName:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**receivedByTitle:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**discountPercent:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**lines:** `List<InvoicesCreateSalesRequestLinesItem>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.sales.invoicesGet(request) -> InvoicesGetSalesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.sales().invoicesGet(
    InvoicesGetSalesRequest
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

<details><summary><code>client.sales.invoicesPdf(request) -> InvoicesPdfSalesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.sales().invoicesPdf(
    InvoicesPdfSalesRequest
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

**locale:** `Optional<InvoicesPdfSalesRequestLocale>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.sales.invoicesSend(request) -> InvoicesSendSalesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.sales().invoicesSend(
    InvoicesSendSalesRequest
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

**locale:** `Optional<InvoicesSendSalesRequestLocale>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.sales.invoicesPeppolXml(request) -> InvoicesPeppolXmlSalesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.sales().invoicesPeppolXml(
    InvoicesPeppolXmlSalesRequest
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

<details><summary><code>client.sales.invoicesPeppolSend(request) -> InvoicesPeppolSendSalesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.sales().invoicesPeppolSend(
    InvoicesPeppolSendSalesRequest
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

<details><summary><code>client.sales.invoicesEinvoiceXml(request) -> InvoicesEinvoiceXmlSalesResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Render an issued invoice as the national e-invoicing payload for the company country: FatturaPA (IT), KSeF FA(3) (PL) or UBL CIUS-RO (RO). Review the warnings - data the invoice does not carry is flagged, never invented.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.sales().invoicesEinvoiceXml(
    InvoicesEinvoiceXmlSalesRequest
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

<details><summary><code>client.sales.invoicesEinvoiceSend(request) -> InvoicesEinvoiceSendSalesResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Build the national e-invoicing payload and deliver it over the transport configured for the country gateway in compliance settings. With transport=direct the request talks to the tax authority itself - SdICoop over 2-way TLS for Italy, a KSeF session for Poland, ANAF SPV OAuth for Romania - and returns the national number as soon as the channel assigns one. With transport=bridge the payload goes to the configured bridge endpoint (an accredited intermediary or connector) instead.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.sales().invoicesEinvoiceSend(
    InvoicesEinvoiceSendSalesRequest
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

<details><summary><code>client.sales.invoicesEinvoiceStatus(request) -> InvoicesEinvoiceStatusSalesResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Ask the national e-invoicing channel what happened to an invoice that was already sent, and store the answer. Italy, Poland and Romania return the outcome only on request - none of them calls back - so this is the way the national number and any rejection reason reach the invoice.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.sales().invoicesEinvoiceStatus(
    InvoicesEinvoiceStatusSalesRequest
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

<details><summary><code>client.sales.invoicesUpdate(request) -> InvoicesUpdateSalesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.sales().invoicesUpdate(
    InvoicesUpdateSalesRequest
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

**agreementId:** `Optional<String>` 
    
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

**vatScheme:** `Optional<InvoicesUpdateSalesRequestVatScheme>` 
    
</dd>
</dl>

<dl>
<dd>

**intrastatTransportMode:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**intrastatDeliveryTerms:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**intrastatRegion:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**intrastatNatureOfTransaction:** `Optional<String>` 
    
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

**operationTypeId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**documentSeriesId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**seriesLabel:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**discountPercent:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**orderNumber:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**issuedByName:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**issuedByTitle:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**receivedByName:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**receivedByTitle:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**lines:** `Optional<List<InvoicesUpdateSalesRequestLinesItem>>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.sales.invoicesDelete(request) -> InvoicesDeleteSalesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.sales().invoicesDelete(
    InvoicesDeleteSalesRequest
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

<details><summary><code>client.sales.invoicesIssue(request) -> InvoicesIssueSalesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.sales().invoicesIssue(
    InvoicesIssueSalesRequest
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

<details><summary><code>client.sales.invoicesLock(request) -> InvoicesLockSalesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.sales().invoicesLock(
    InvoicesLockSalesRequest
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

<details><summary><code>client.sales.invoicesUnlock(request) -> InvoicesUnlockSalesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.sales().invoicesUnlock(
    InvoicesUnlockSalesRequest
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

<details><summary><code>client.sales.invoicesPaymentLink(request) -> InvoicesPaymentLinkSalesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.sales().invoicesPaymentLink(
    InvoicesPaymentLinkSalesRequest
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

<details><summary><code>client.sales.invoicesPaymentSettingsGet(request) -> InvoicesPaymentSettingsGetSalesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.sales().invoicesPaymentSettingsGet(
    InvoicesPaymentSettingsGetSalesRequest
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

<details><summary><code>client.sales.invoicesPaymentSettingsUpdate(request) -> InvoicesPaymentSettingsUpdateSalesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.sales().invoicesPaymentSettingsUpdate(
    InvoicesPaymentSettingsUpdateSalesRequest
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

**paymentLinkTemplate:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.sales.recognitionSchedulesList(request) -> RecognitionSchedulesListSalesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.sales().recognitionSchedulesList(
    RecognitionSchedulesListSalesRequest
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

**sort:** `Optional<List<RecognitionSchedulesListSalesRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<RecognitionSchedulesListSalesRequestFilterItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `Optional<List<String>>` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.sales.invoicesApplyAdvance(request) -> InvoicesApplyAdvanceSalesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.sales().invoicesApplyAdvance(
    InvoicesApplyAdvanceSalesRequest
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

<details><summary><code>client.sales.invoicesList(request) -> InvoicesListSalesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.sales().invoicesList(
    InvoicesListSalesRequest
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

**sort:** `Optional<List<InvoicesListSalesRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<InvoicesListSalesRequestFilterItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `Optional<List<String>>` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.sales.actsCreate(request) -> ActsCreateSalesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.sales().actsCreate(
    ActsCreateSalesRequest
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

**type:** `Optional<ActsCreateSalesRequestType>` 
    
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

**lines:** `Optional<List<ActsCreateSalesRequestLinesItem>>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.sales.actsUpdate(request) -> ActsUpdateSalesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.sales().actsUpdate(
    ActsUpdateSalesRequest
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

**type:** `Optional<ActsUpdateSalesRequestType>` 
    
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

**lines:** `Optional<List<ActsUpdateSalesRequestLinesItem>>` 
    
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

<details><summary><code>client.sales.actsIssue(request) -> ActsIssueSalesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.sales().actsIssue(
    ActsIssueSalesRequest
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

<details><summary><code>client.sales.actsCancel(request) -> ActsCancelSalesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.sales().actsCancel(
    ActsCancelSalesRequest
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

<details><summary><code>client.sales.actsGet(request) -> ActsGetSalesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.sales().actsGet(
    ActsGetSalesRequest
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

<details><summary><code>client.sales.actsList(request) -> ActsListSalesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.sales().actsList(
    ActsListSalesRequest
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

**sort:** `Optional<List<ActsListSalesRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<ActsListSalesRequestFilterItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `Optional<List<String>>` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.sales.actsPdf(request) -> ActsPdfSalesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.sales().actsPdf(
    ActsPdfSalesRequest
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

**locale:** `Optional<ActsPdfSalesRequestLocale>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.sales.recognitionCompute(request) -> RecognitionComputeSalesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.sales().recognitionCompute(
    RecognitionComputeSalesRequest
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

**asOfDate:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.sales.recognitionRun(request) -> RecognitionRunSalesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.sales().recognitionRun(
    RecognitionRunSalesRequest
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

**asOfDate:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**postingDate:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**scheduleIds:** `Optional<List<String>>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.sales.recognitionProgress(request) -> RecognitionProgressSalesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.sales().recognitionProgress(
    RecognitionProgressSalesRequest
        .builder()
        .invoiceLineId("invoiceLineId")
        .percentComplete("121.00")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**invoiceLineId:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**percentComplete:** `String` 
    
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

<details><summary><code>client.sales.recognitionModify(request) -> RecognitionModifySalesResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Apply an IFRS 15 contract modification to a deferred invoice line. Prospective: cancel the pending schedule and respread the unrecognized remainder over the new terms. Cumulative catch-up (ratable only): recompute revenue as if the new terms applied from the start and post the difference immediately.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.sales().recognitionModify(
    RecognitionModifySalesRequest
        .builder()
        .invoiceLineId("invoiceLineId")
        .approach(RecognitionModifySalesRequestApproach.PROSPECTIVE)
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**invoiceLineId:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**approach:** `RecognitionModifySalesRequestApproach` 
    
</dd>
</dl>

<dl>
<dd>

**date:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**newEndDate:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**newMilestones:** `Optional<List<RecognitionModifySalesRequestNewMilestonesItem>>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.sales.recognitionRunsList(request) -> RecognitionRunsListSalesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.sales().recognitionRunsList(
    RecognitionRunsListSalesRequest
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

**sort:** `Optional<List<RecognitionRunsListSalesRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<RecognitionRunsListSalesRequestFilterItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `Optional<List<String>>` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.sales.recognitionSummary(request) -> RecognitionSummarySalesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.sales().recognitionSummary(
    RecognitionSummarySalesRequest
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

**invoiceId:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.sales.refundLiabilityList(request) -> RefundLiabilityListSalesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.sales().refundLiabilityList(
    RefundLiabilityListSalesRequest
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

**sort:** `Optional<List<RefundLiabilityListSalesRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<RefundLiabilityListSalesRequestFilterItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `Optional<List<String>>` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.sales.refundLiabilityTrueUp(request) -> RefundLiabilityTrueUpSalesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.sales().refundLiabilityTrueUp(
    RefundLiabilityTrueUpSalesRequest
        .builder()
        .invoiceId("invoiceId")
        .estimatedTotal("121.0000")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**invoiceId:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**estimatedTotal:** `String` 
    
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

## OperationTypes
<details><summary><code>client.operationTypes.create(request) -> CreateOperationTypesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.operationTypes().create(
    CreateOperationTypesRequest
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

**invoiceType:** `Optional<CreateOperationTypesRequestInvoiceType>` 
    
</dd>
</dl>

<dl>
<dd>

**payerPartnerId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**debitAccountCode:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**creditAccountCode:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**vatAccountCode:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**expenseAccountCode:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**advanceAccountCode:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**incomeAccountCode:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**isPurchase:** `Optional<Boolean>` 
    
</dd>
</dl>

<dl>
<dd>

**isSale:** `Optional<Boolean>` 
    
</dd>
</dl>

<dl>
<dd>

**isWriteOff:** `Optional<Boolean>` 
    
</dd>
</dl>

<dl>
<dd>

**isInternalMovement:** `Optional<Boolean>` 
    
</dd>
</dl>

<dl>
<dd>

**isPurchaseReturn:** `Optional<Boolean>` 
    
</dd>
</dl>

<dl>
<dd>

**isSalesReturn:** `Optional<Boolean>` 
    
</dd>
</dl>

<dl>
<dd>

**isConsignment:** `Optional<Boolean>` 
    
</dd>
</dl>

<dl>
<dd>

**isProduction:** `Optional<Boolean>` 
    
</dd>
</dl>

<dl>
<dd>

**isAssetIn:** `Optional<Boolean>` 
    
</dd>
</dl>

<dl>
<dd>

**isAssetOut:** `Optional<Boolean>` 
    
</dd>
</dl>

<dl>
<dd>

**isCashRegisterSale:** `Optional<Boolean>` 
    
</dd>
</dl>

<dl>
<dd>

**includeInVatRegister:** `Optional<Boolean>` 
    
</dd>
</dl>

<dl>
<dd>

**includeInSaft:** `Optional<Boolean>` 
    
</dd>
</dl>

<dl>
<dd>

**isActive:** `Optional<Boolean>` 
    
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

<details><summary><code>client.operationTypes.update(request) -> UpdateOperationTypesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.operationTypes().update(
    UpdateOperationTypesRequest
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

**invoiceType:** `Optional<UpdateOperationTypesRequestInvoiceType>` 
    
</dd>
</dl>

<dl>
<dd>

**payerPartnerId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**debitAccountCode:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**creditAccountCode:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**vatAccountCode:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**expenseAccountCode:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**advanceAccountCode:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**incomeAccountCode:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**isPurchase:** `Optional<Boolean>` 
    
</dd>
</dl>

<dl>
<dd>

**isSale:** `Optional<Boolean>` 
    
</dd>
</dl>

<dl>
<dd>

**isWriteOff:** `Optional<Boolean>` 
    
</dd>
</dl>

<dl>
<dd>

**isInternalMovement:** `Optional<Boolean>` 
    
</dd>
</dl>

<dl>
<dd>

**isPurchaseReturn:** `Optional<Boolean>` 
    
</dd>
</dl>

<dl>
<dd>

**isSalesReturn:** `Optional<Boolean>` 
    
</dd>
</dl>

<dl>
<dd>

**isConsignment:** `Optional<Boolean>` 
    
</dd>
</dl>

<dl>
<dd>

**isProduction:** `Optional<Boolean>` 
    
</dd>
</dl>

<dl>
<dd>

**isAssetIn:** `Optional<Boolean>` 
    
</dd>
</dl>

<dl>
<dd>

**isAssetOut:** `Optional<Boolean>` 
    
</dd>
</dl>

<dl>
<dd>

**isCashRegisterSale:** `Optional<Boolean>` 
    
</dd>
</dl>

<dl>
<dd>

**includeInVatRegister:** `Optional<Boolean>` 
    
</dd>
</dl>

<dl>
<dd>

**includeInSaft:** `Optional<Boolean>` 
    
</dd>
</dl>

<dl>
<dd>

**isActive:** `Optional<Boolean>` 
    
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

<details><summary><code>client.operationTypes.get(request) -> GetOperationTypesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.operationTypes().get(
    GetOperationTypesRequest
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

<details><summary><code>client.operationTypes.delete(request) -> DeleteOperationTypesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.operationTypes().delete(
    DeleteOperationTypesRequest
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

<details><summary><code>client.operationTypes.list(request) -> ListOperationTypesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.operationTypes().list(
    ListOperationTypesRequest
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

**sort:** `Optional<List<ListOperationTypesRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<ListOperationTypesRequestFilterItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `Optional<List<String>>` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## DocumentSeries
<details><summary><code>client.documentSeries.create(request) -> CreateDocumentSeriesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.documentSeries().create(
    CreateDocumentSeriesRequest
        .builder()
        .prefix("prefix")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**documentType:** `Optional<CreateDocumentSeriesRequestDocumentType>` 
    
</dd>
</dl>

<dl>
<dd>

**prefix:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**name:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**label:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**operationTypeId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**numberLength:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**nextNumber:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**allocatedFrom:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**allocatedTo:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**warehouseId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**printSeries:** `Optional<Boolean>` 
    
</dd>
</dl>

<dl>
<dd>

**isDefault:** `Optional<Boolean>` 
    
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

<details><summary><code>client.documentSeries.update(request) -> UpdateDocumentSeriesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.documentSeries().update(
    UpdateDocumentSeriesRequest
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

**documentType:** `Optional<UpdateDocumentSeriesRequestDocumentType>` 
    
</dd>
</dl>

<dl>
<dd>

**prefix:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**name:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**label:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**operationTypeId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**numberLength:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**nextNumber:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**allocatedFrom:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**allocatedTo:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**warehouseId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**printSeries:** `Optional<Boolean>` 
    
</dd>
</dl>

<dl>
<dd>

**isDefault:** `Optional<Boolean>` 
    
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

<details><summary><code>client.documentSeries.get(request) -> GetDocumentSeriesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.documentSeries().get(
    GetDocumentSeriesRequest
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

<details><summary><code>client.documentSeries.delete(request) -> DeleteDocumentSeriesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.documentSeries().delete(
    DeleteDocumentSeriesRequest
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

<details><summary><code>client.documentSeries.list(request) -> ListDocumentSeriesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.documentSeries().list(
    ListDocumentSeriesRequest
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

**sort:** `Optional<List<ListDocumentSeriesRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<ListDocumentSeriesRequestFilterItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `Optional<List<String>>` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## purchases
<details><summary><code>client.purchases.invoicesCreate(request) -> InvoicesCreatePurchasesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.purchases().invoicesCreate(
    InvoicesCreatePurchasesRequest
        .builder()
        .partnerId("partnerId")
        .documentNumber("documentNumber")
        .documentDate("2026-07-01")
        .lines(
            Arrays.asList(
                InvoicesCreatePurchasesRequestLinesItem
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

**type:** `Optional<InvoicesCreatePurchasesRequestType>` 
    
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

**purchaseOrderId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**operationTypeId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**intrastatTransportMode:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**intrastatDeliveryTerms:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**intrastatRegion:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**intrastatNatureOfTransaction:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**einvoiceNumber:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**documentRef:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**lines:** `List<InvoicesCreatePurchasesRequestLinesItem>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.purchases.invoicesGet(request) -> InvoicesGetPurchasesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.purchases().invoicesGet(
    InvoicesGetPurchasesRequest
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

<details><summary><code>client.purchases.invoicesUpdate(request) -> InvoicesUpdatePurchasesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.purchases().invoicesUpdate(
    InvoicesUpdatePurchasesRequest
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

**purchaseOrderId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**operationTypeId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**intrastatTransportMode:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**intrastatDeliveryTerms:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**intrastatRegion:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**intrastatNatureOfTransaction:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**einvoiceNumber:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**lines:** `Optional<List<InvoicesUpdatePurchasesRequestLinesItem>>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.purchases.invoicesDelete(request) -> InvoicesDeletePurchasesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.purchases().invoicesDelete(
    InvoicesDeletePurchasesRequest
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

<details><summary><code>client.purchases.invoicesRegister(request) -> InvoicesRegisterPurchasesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.purchases().invoicesRegister(
    InvoicesRegisterPurchasesRequest
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

<details><summary><code>client.purchases.invoicesList(request) -> InvoicesListPurchasesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.purchases().invoicesList(
    InvoicesListPurchasesRequest
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

**sort:** `Optional<List<InvoicesListPurchasesRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<InvoicesListPurchasesRequestFilterItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `Optional<List<String>>` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.purchases.ordersCreate(request) -> OrdersCreatePurchasesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.purchases().ordersCreate(
    OrdersCreatePurchasesRequest
        .builder()
        .partnerId("partnerId")
        .orderDate("2026-07-01")
        .lines(
            Arrays.asList(
                OrdersCreatePurchasesRequestLinesItem
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

**orderNumber:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**orderDate:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**expectedDate:** `Optional<String>` 
    
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

**notes:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**documentRef:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**lines:** `List<OrdersCreatePurchasesRequestLinesItem>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.purchases.ordersUpdate(request) -> OrdersUpdatePurchasesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.purchases().ordersUpdate(
    OrdersUpdatePurchasesRequest
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

**orderDate:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**expectedDate:** `Optional<String>` 
    
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

**notes:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**lines:** `Optional<List<OrdersUpdatePurchasesRequestLinesItem>>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.purchases.ordersGet(request) -> OrdersGetPurchasesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.purchases().ordersGet(
    OrdersGetPurchasesRequest
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

<details><summary><code>client.purchases.ordersList(request) -> OrdersListPurchasesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.purchases().ordersList(
    OrdersListPurchasesRequest
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

**sort:** `Optional<List<OrdersListPurchasesRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<OrdersListPurchasesRequestFilterItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `Optional<List<String>>` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.purchases.ordersSubmit(request) -> OrdersSubmitPurchasesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.purchases().ordersSubmit(
    OrdersSubmitPurchasesRequest
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

**reason:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.purchases.ordersApprove(request) -> OrdersApprovePurchasesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.purchases().ordersApprove(
    OrdersApprovePurchasesRequest
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

**reason:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.purchases.ordersReject(request) -> OrdersRejectPurchasesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.purchases().ordersReject(
    OrdersRejectPurchasesRequest
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

**reason:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.purchases.ordersCancel(request) -> OrdersCancelPurchasesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.purchases().ordersCancel(
    OrdersCancelPurchasesRequest
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

**reason:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.purchases.ordersClose(request) -> OrdersClosePurchasesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.purchases().ordersClose(
    OrdersClosePurchasesRequest
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

**reason:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.purchases.ordersDelete(request) -> OrdersDeletePurchasesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.purchases().ordersDelete(
    OrdersDeletePurchasesRequest
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

<details><summary><code>client.purchases.receiptsCreate(request) -> ReceiptsCreatePurchasesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.purchases().receiptsCreate(
    ReceiptsCreatePurchasesRequest
        .builder()
        .orderId("orderId")
        .receiptDate("2026-07-01")
        .lines(
            Arrays.asList(
                ReceiptsCreatePurchasesRequestLinesItem
                    .builder()
                    .orderLineId("orderLineId")
                    .quantity("121.0000")
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

**orderId:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**receiptDate:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**warehouseId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**lines:** `List<ReceiptsCreatePurchasesRequestLinesItem>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.purchases.receiptsGet(request) -> ReceiptsGetPurchasesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.purchases().receiptsGet(
    ReceiptsGetPurchasesRequest
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

<details><summary><code>client.purchases.receiptsList(request) -> ReceiptsListPurchasesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.purchases().receiptsList(
    ReceiptsListPurchasesRequest
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

**sort:** `Optional<List<ReceiptsListPurchasesRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<ReceiptsListPurchasesRequestFilterItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `Optional<List<String>>` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.purchases.invoicesMatch(request) -> InvoicesMatchPurchasesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.purchases().invoicesMatch(
    InvoicesMatchPurchasesRequest
        .builder()
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

**invoiceId:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**priceTolerancePercent:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## capture
<details><summary><code>client.capture.settingsGet(request) -> SettingsGetCaptureResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.capture().settingsGet(
    SettingsGetCaptureRequest
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

<details><summary><code>client.capture.settingsUpdate(request) -> SettingsUpdateCaptureResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.capture().settingsUpdate(
    SettingsUpdateCaptureRequest
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

**intakeEnabled:** `Optional<Boolean>` 
    
</dd>
</dl>

<dl>
<dd>

**captureAutoExtract:** `Optional<Boolean>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.capture.settingsRegenerateIntake(request) -> SettingsRegenerateIntakeCaptureResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.capture().settingsRegenerateIntake(
    SettingsRegenerateIntakeCaptureRequest
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

<details><summary><code>client.capture.inboundEmail(request) -> InboundEmailCaptureResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.capture().inboundEmail(
    InboundEmailCaptureRequest
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

**postmarkTo:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**toFull:** `Optional<List<InboundEmailCaptureRequestToFullItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**postmarkFrom:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**postmarkSubject:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**postmarkAttachments:** `Optional<List<InboundEmailCaptureRequestAttachmentsItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**to:** `Optional<InboundEmailCaptureRequestTo>` 
    
</dd>
</dl>

<dl>
<dd>

**from:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**subject:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**attachments:** `Optional<List<InboundEmailCaptureRequestAttachmentsItem>>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.capture.documentsUpload(request) -> DocumentsUploadCaptureResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.capture().documentsUpload(
    DocumentsUploadCaptureRequest
        .builder()
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

**content:** `String` — Base64-encoded scan, photo or PDF of the supplier document
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.capture.documentsExtract(request) -> DocumentsExtractCaptureResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.capture().documentsExtract(
    DocumentsExtractCaptureRequest
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

<details><summary><code>client.capture.documentsGet(request) -> DocumentsGetCaptureResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.capture().documentsGet(
    DocumentsGetCaptureRequest
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

<details><summary><code>client.capture.documentsList(request) -> DocumentsListCaptureResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.capture().documentsList(
    DocumentsListCaptureRequest
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

**sort:** `Optional<List<DocumentsListCaptureRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<DocumentsListCaptureRequestFilterItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `Optional<List<String>>` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.capture.documentsDelete(request) -> DocumentsDeleteCaptureResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.capture().documentsDelete(
    DocumentsDeleteCaptureRequest
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

<details><summary><code>client.capture.documentsConfirm(request) -> DocumentsConfirmCaptureResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.capture().documentsConfirm(
    DocumentsConfirmCaptureRequest
        .builder()
        .id("id")
        .documentNumber("documentNumber")
        .documentDate("2026-07-01")
        .lines(
            Arrays.asList(
                DocumentsConfirmCaptureRequestLinesItem
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

**newSupplier:** `Optional<DocumentsConfirmCaptureRequestNewSupplier>` 
    
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

**notes:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**lines:** `List<DocumentsConfirmCaptureRequestLinesItem>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## declarations
<details><summary><code>client.declarations.ltIntrastatCompute(request) -> LtIntrastatComputeDeclarationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().ltIntrastatCompute(
    LtIntrastatComputeDeclarationsRequest
        .builder()
        .year(1000000L)
        .month(1000000L)
        .flow(LtIntrastatComputeDeclarationsRequestFlow.ARRIVALS)
        .build()
);
```
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

**flow:** `LtIntrastatComputeDeclarationsRequestFlow` 
    
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

**transportMode:** `Optional<LtIntrastatComputeDeclarationsRequestTransportMode>` 
    
</dd>
</dl>

<dl>
<dd>

**regionCode:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**statisticalValueRequired:** `Optional<Boolean>` 
    
</dd>
</dl>

<dl>
<dd>

**preparationTimeHours:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**preparationTimeMinutes:** `Optional<Long>` 
    
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

<details><summary><code>client.declarations.ltIvazGenerate(request) -> LtIvazGenerateDeclarationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().ltIvazGenerate(
    LtIvazGenerateDeclarationsRequest
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

<details><summary><code>client.declarations.ltIntrastatObligation(request) -> LtIntrastatObligationDeclarationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().ltIntrastatObligation(
    LtIntrastatObligationDeclarationsRequest
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

<details><summary><code>client.declarations.ltIsafGenerate(request) -> LtIsafGenerateDeclarationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().ltIsafGenerate(
    LtIsafGenerateDeclarationsRequest
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

**dataType:** `Optional<LtIsafGenerateDeclarationsRequestDataType>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.declarations.ltFr0600Compute(request) -> LtFr0600ComputeDeclarationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().ltFr0600Compute(
    LtFr0600ComputeDeclarationsRequest
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

<details><summary><code>client.declarations.ltGpm313Compute(request) -> LtGpm313ComputeDeclarationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().ltGpm313Compute(
    LtGpm313ComputeDeclarationsRequest
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

**payoutTiming:** `Optional<LtGpm313ComputeDeclarationsRequestPayoutTiming>` 
    
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

<details><summary><code>client.declarations.ltSamCompute(request) -> LtSamComputeDeclarationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().ltSamCompute(
    LtSamComputeDeclarationsRequest
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

<details><summary><code>client.declarations.ltSdGenerate(request) -> LtSdGenerateDeclarationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().ltSdGenerate(
    LtSdGenerateDeclarationsRequest
        .builder()
        .type(LtSdGenerateDeclarationsRequestType.ONE_SD)
        .fromDate("2026-07-01")
        .toDate("2026-07-01")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**type:** `LtSdGenerateDeclarationsRequestType` 
    
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

<details><summary><code>client.declarations.ltSaftGenerate(request) -> LtSaftGenerateDeclarationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().ltSaftGenerate(
    LtSaftGenerateDeclarationsRequest
        .builder()
        .fromDate("2026-07-01")
        .toDate("2026-07-01")
        .build()
);
```
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

**dataType:** `Optional<LtSaftGenerateDeclarationsRequestDataType>` 
    
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

<details><summary><code>client.declarations.ltIvazAmend(request) -> LtIvazAmendDeclarationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().ltIvazAmend(
    LtIvazAmendDeclarationsRequest
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

<details><summary><code>client.declarations.ltIvazCancel(request) -> LtIvazCancelDeclarationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().ltIvazCancel(
    LtIvazCancelDeclarationsRequest
        .builder()
        .entries(
            Arrays.asList(
                LtIvazCancelDeclarationsRequestEntriesItem
                    .builder()
                    .waybillId("waybillId")
                    .reason(LtIvazCancelDeclarationsRequestEntriesItemReason.ONE)
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

**entries:** `List<LtIvazCancelDeclarationsRequestEntriesItem>` 
    
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

<details><summary><code>client.declarations.ltFr0564Compute(request) -> LtFr0564ComputeDeclarationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().ltFr0564Compute(
    LtFr0564ComputeDeclarationsRequest
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

<details><summary><code>client.declarations.ltGpm312Compute(request) -> LtGpm312ComputeDeclarationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().ltGpm312Compute(
    LtGpm312ComputeDeclarationsRequest
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

<dl>
<dd>

**payoutTiming:** `Optional<LtGpm312ComputeDeclarationsRequestPayoutTiming>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.declarations.ltPln204Compute(request) -> LtPln204ComputeDeclarationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().ltPln204Compute(
    LtPln204ComputeDeclarationsRequest
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

<details><summary><code>client.declarations.euOssCompute(request) -> EuOssComputeDeclarationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().euOssCompute(
    EuOssComputeDeclarationsRequest
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

<details><summary><code>client.declarations.euIossCompute(request) -> EuIossComputeDeclarationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().euIossCompute(
    EuIossComputeDeclarationsRequest
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

<details><summary><code>client.declarations.euDistanceSalesThresholdGet(request) -> EuDistanceSalesThresholdGetDeclarationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().euDistanceSalesThresholdGet(
    EuDistanceSalesThresholdGetDeclarationsRequest
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

<details><summary><code>client.declarations.euUnionTurnoverGet(request) -> EuUnionTurnoverGetDeclarationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().euUnionTurnoverGet(
    EuUnionTurnoverGetDeclarationsRequest
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

<details><summary><code>client.declarations.euSmeCrossBorderReportCompute(request) -> EuSmeCrossBorderReportComputeDeclarationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().euSmeCrossBorderReportCompute(
    EuSmeCrossBorderReportComputeDeclarationsRequest
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

<details><summary><code>client.declarations.euSmeThresholdsList(request) -> EuSmeThresholdsListDeclarationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().euSmeThresholdsList(
    EuSmeThresholdsListDeclarationsRequest
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

<details><summary><code>client.declarations.euSmeThresholdGet(request) -> EuSmeThresholdGetDeclarationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().euSmeThresholdGet(
    EuSmeThresholdGetDeclarationsRequest
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

<details><summary><code>client.declarations.euVatReturnPacksList(request) -> EuVatReturnPacksListDeclarationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().euVatReturnPacksList(
    EuVatReturnPacksListDeclarationsRequest
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

<details><summary><code>client.declarations.euVatReturnCompute(request) -> EuVatReturnComputeDeclarationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().euVatReturnCompute(
    EuVatReturnComputeDeclarationsRequest
        .builder()
        .countryCode("countryCode")
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

**countryCode:** `String` 
    
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

**months:** `Optional<Long>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.declarations.plJpkV7MGenerate(request) -> PlJpkV7MGenerateDeclarationsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Generate the Polish JPK_V7M(3) file (VAT declaration with evidence) for a month, per the MF schema in force since February 2026. Amounts must already be in PLN; rows are marked BFK until a KSeF integration supplies invoice numbers. Review the warnings before submitting via e-dokumenty.mf.gov.pl.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().plJpkV7MGenerate(
    PlJpkV7MGenerateDeclarationsRequest
        .builder()
        .year(1000000L)
        .month(1000000L)
        .kodUrzedu("kodUrzedu")
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

**kodUrzedu:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**email:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**celZlozenia:** `Optional<Long>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.declarations.plVatUeGenerate(request) -> PlVatUeGenerateDeclarationsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Build the rows of the Polish recapitulative statement VAT-UE for a month: section C intra-Community supplies of goods, section D intra-Community acquisitions, section E services taxed where the customer is established. Amounts are full złoty per counterparty. The VAT-UE(5) file itself goes out from the EU sales list deadline in the calendar.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().plVatUeGenerate(
    PlVatUeGenerateDeclarationsRequest
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

<details><summary><code>client.declarations.plIntrastatGenerate(request) -> PlIntrastatGenerateDeclarationsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Build the rows of the Polish INTRASTAT declaration for a month, arrivals or dispatches, grouped by CN code, partner country, country of origin, partner VAT number, nature of transaction, transport and delivery terms. Values are whole złoty converted at the invoice rate; credit notes with goods lines are returns (code 21). Goods without a CN code are left out and named in the warnings. The IST message itself goes out from the Intrastat deadline in the calendar.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().plIntrastatGenerate(
    PlIntrastatGenerateDeclarationsRequest
        .builder()
        .year(1000000L)
        .month(1000000L)
        .flow(PlIntrastatGenerateDeclarationsRequestFlow.ARRIVALS)
        .build()
);
```
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

**flow:** `PlIntrastatGenerateDeclarationsRequestFlow` 
    
</dd>
</dl>

<dl>
<dd>

**transactionNature:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.declarations.plKsefReceivedList(request) -> PlKsefReceivedListDeclarationsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

List the invoices KSeF holds for this company as the buyer, for a window of acquisition timestamps. Each row carries the KSeF number and, when the document number matches a registered purchase invoice, the invoice it belongs to.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().plKsefReceivedList(
    PlKsefReceivedListDeclarationsRequest
        .builder()
        .from(OffsetDateTime.parse("2024-01-15T09:30:00Z"))
        .to(OffsetDateTime.parse("2024-01-15T09:30:00Z"))
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**from:** `OffsetDateTime` 
    
</dd>
</dl>

<dl>
<dd>

**to:** `OffsetDateTime` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**pageOffset:** `Optional<Long>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.declarations.plKsefReceivedFetch(request) -> PlKsefReceivedFetchDeclarationsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Read one invoice out of KSeF by its national number. With a purchase invoice given, the KSeF number is written onto that invoice, which is what makes the purchase row of JPK_V7M carry NrKSeF instead of the BFK marker.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().plKsefReceivedFetch(
    PlKsefReceivedFetchDeclarationsRequest
        .builder()
        .ksefNumber("ksefNumber")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**ksefNumber:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**purchaseInvoiceId:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.declarations.plKsefReceipt(request) -> PlKsefReceiptDeclarationsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

The UPO for a KSeF session. KSeF issues one receipt per session rather than per invoice, so the session reference number from the send is what identifies it.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().plKsefReceipt(
    PlKsefReceiptDeclarationsRequest
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

**sessionReferenceNumber:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.declarations.taxAdjustmentsList(request) -> TaxAdjustmentsListDeclarationsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

The differences between the accounting result and the taxable profit: non-deductible expenses, income added to or left out of the tax base, extra deductible expenses, donations, losses carried forward, reliefs and tax credits. The annual corporate income tax return is built from them.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().taxAdjustmentsList(
    TaxAdjustmentsListDeclarationsRequest
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

<details><summary><code>client.declarations.taxAdjustmentsCreate(request) -> TaxAdjustmentsCreateDeclarationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().taxAdjustmentsCreate(
    TaxAdjustmentsCreateDeclarationsRequest
        .builder()
        .year(1000000L)
        .kind(TaxAdjustmentsCreateDeclarationsRequestKind.NON_DEDUCTIBLE)
        .amount("121.00")
        .description("description")
        .build()
);
```
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

**kind:** `TaxAdjustmentsCreateDeclarationsRequestKind` 
    
</dd>
</dl>

<dl>
<dd>

**code:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**amount:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**description:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.declarations.taxAdjustmentsUpdate(request) -> TaxAdjustmentsUpdateDeclarationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().taxAdjustmentsUpdate(
    TaxAdjustmentsUpdateDeclarationsRequest
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

**kind:** `Optional<TaxAdjustmentsUpdateDeclarationsRequestKind>` 
    
</dd>
</dl>

<dl>
<dd>

**code:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**amount:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**description:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.declarations.taxAdjustmentsDelete(request) -> TaxAdjustmentsDeleteDeclarationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().taxAdjustmentsDelete(
    TaxAdjustmentsDeleteDeclarationsRequest
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

<details><summary><code>client.declarations.taxPaymentsList(request) -> TaxPaymentsListDeclarationsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

What the company has paid the administration towards a tax before the return is filed: payments on account, tax withheld at source by others, a final settlement, and a refund received. Returns report these on their own lines, so the amount they ask for is the balance.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().taxPaymentsList(
    TaxPaymentsListDeclarationsRequest
        .builder()
        .tax(TaxPaymentsListDeclarationsRequestTax.CORPORATE_INCOME_TAX)
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

**tax:** `TaxPaymentsListDeclarationsRequestTax` 
    
</dd>
</dl>

<dl>
<dd>

**year:** `Long` 
    
</dd>
</dl>

<dl>
<dd>

**month:** `Optional<Long>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.declarations.taxPaymentsCreate(request) -> TaxPaymentsCreateDeclarationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().taxPaymentsCreate(
    TaxPaymentsCreateDeclarationsRequest
        .builder()
        .tax(TaxPaymentsCreateDeclarationsRequestTax.CORPORATE_INCOME_TAX)
        .year(1000000L)
        .kind(TaxPaymentsCreateDeclarationsRequestKind.ADVANCE)
        .amount("121.00")
        .paidOn("2026-07-01")
        .description("description")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**tax:** `TaxPaymentsCreateDeclarationsRequestTax` 
    
</dd>
</dl>

<dl>
<dd>

**year:** `Long` 
    
</dd>
</dl>

<dl>
<dd>

**month:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**kind:** `TaxPaymentsCreateDeclarationsRequestKind` 
    
</dd>
</dl>

<dl>
<dd>

**amount:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**paidOn:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**reference:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**description:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.declarations.taxPaymentsUpdate(request) -> TaxPaymentsUpdateDeclarationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().taxPaymentsUpdate(
    TaxPaymentsUpdateDeclarationsRequest
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

**kind:** `Optional<TaxPaymentsUpdateDeclarationsRequestKind>` 
    
</dd>
</dl>

<dl>
<dd>

**amount:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**paidOn:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**reference:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**description:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.declarations.taxPaymentsDelete(request) -> TaxPaymentsDeleteDeclarationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().taxPaymentsDelete(
    TaxPaymentsDeleteDeclarationsRequest
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

<details><summary><code>client.declarations.annualAccountsGet(request) -> AnnualAccountsGetDeclarationsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Whether the general meeting adopted the annual accounts and on which date, the date the accounts were prepared, and which directors signed them. The annual accounts filed with the trade register are built from these facts.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().annualAccountsGet(
    AnnualAccountsGetDeclarationsRequest
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

<details><summary><code>client.declarations.annualAccountsSet(request) -> AnnualAccountsSetDeclarationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().annualAccountsSet(
    AnnualAccountsSetDeclarationsRequest
        .builder()
        .year(1000000L)
        .adopted(true)
        .dateOfPreparation("2026-07-01")
        .build()
);
```
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

**adopted:** `Boolean` 
    
</dd>
</dl>

<dl>
<dd>

**adoptionDate:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**dateOfPreparation:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**audited:** `Optional<Boolean>` 
    
</dd>
</dl>

<dl>
<dd>

**auditReportQualified:** `Optional<Boolean>` 
    
</dd>
</dl>

<dl>
<dd>

**auditorNotElected:** `Optional<Boolean>` 
    
</dd>
</dl>

<dl>
<dd>

**notesText:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**managementReportText:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**auditorReportText:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**auditorReportDate:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**resultToReserves:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**resultToLossCompensation:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**resultToRemainder:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.declarations.annualAccountsSignaturesCreate(request) -> AnnualAccountsSignaturesCreateDeclarationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().annualAccountsSignaturesCreate(
    AnnualAccountsSignaturesCreateDeclarationsRequest
        .builder()
        .year(1000000L)
        .directorName("directorName")
        .directorType(AnnualAccountsSignaturesCreateDeclarationsRequestDirectorType.MANAGING_CURRENT)
        .signed(true)
        .build()
);
```
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

**directorName:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**directorType:** `AnnualAccountsSignaturesCreateDeclarationsRequestDirectorType` 
    
</dd>
</dl>

<dl>
<dd>

**signed:** `Boolean` 
    
</dd>
</dl>

<dl>
<dd>

**signedOn:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**signedAt:** `Optional<OffsetDateTime>` 
    
</dd>
</dl>

<dl>
<dd>

**reasonNotSigned:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.declarations.annualAccountsSignaturesUpdate(request) -> AnnualAccountsSignaturesUpdateDeclarationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().annualAccountsSignaturesUpdate(
    AnnualAccountsSignaturesUpdateDeclarationsRequest
        .builder()
        .id("id")
        .directorName("directorName")
        .directorType(AnnualAccountsSignaturesUpdateDeclarationsRequestDirectorType.MANAGING_CURRENT)
        .signed(true)
        .build()
);
```
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

**directorName:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**directorType:** `AnnualAccountsSignaturesUpdateDeclarationsRequestDirectorType` 
    
</dd>
</dl>

<dl>
<dd>

**signed:** `Boolean` 
    
</dd>
</dl>

<dl>
<dd>

**signedOn:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**signedAt:** `Optional<OffsetDateTime>` 
    
</dd>
</dl>

<dl>
<dd>

**reasonNotSigned:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.declarations.annualAccountsSignaturesDelete(request) -> AnnualAccountsSignaturesDeleteDeclarationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().annualAccountsSignaturesDelete(
    AnnualAccountsSignaturesDeleteDeclarationsRequest
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

<details><summary><code>client.declarations.annualAccountsDistributionsCreate(request) -> AnnualAccountsDistributionsCreateDeclarationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().annualAccountsDistributionsCreate(
    AnnualAccountsDistributionsCreateDeclarationsRequest
        .builder()
        .year(1000000L)
        .decidedOn("2026-07-01")
        .kind(AnnualAccountsDistributionsCreateDeclarationsRequestKind.DIVIDEND)
        .amount("121.00")
        .build()
);
```
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

**decidedOn:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**kind:** `AnnualAccountsDistributionsCreateDeclarationsRequestKind` 
    
</dd>
</dl>

<dl>
<dd>

**amount:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**description:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.declarations.annualAccountsDistributionsUpdate(request) -> AnnualAccountsDistributionsUpdateDeclarationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().annualAccountsDistributionsUpdate(
    AnnualAccountsDistributionsUpdateDeclarationsRequest
        .builder()
        .id("id")
        .decidedOn("2026-07-01")
        .kind(AnnualAccountsDistributionsUpdateDeclarationsRequestKind.DIVIDEND)
        .amount("121.00")
        .build()
);
```
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

**decidedOn:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**kind:** `AnnualAccountsDistributionsUpdateDeclarationsRequestKind` 
    
</dd>
</dl>

<dl>
<dd>

**amount:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**description:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.declarations.annualAccountsDistributionsDelete(request) -> AnnualAccountsDistributionsDeleteDeclarationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().annualAccountsDistributionsDelete(
    AnnualAccountsDistributionsDeleteDeclarationsRequest
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

<details><summary><code>client.declarations.annualAccountsAttachmentsAdd(request) -> AnnualAccountsAttachmentsAddDeclarationsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Links a file uploaded through files/upload (its storageKey) to the annual accounts of the year as the notes, the management report, the auditor statement, the profit appropriation resolution, the approval certificate, the general data sheet, the full report as a pdf, or another document. Deposits that must carry these documents take them from here.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().annualAccountsAttachmentsAdd(
    AnnualAccountsAttachmentsAddDeclarationsRequest
        .builder()
        .year(1000000L)
        .kind(AnnualAccountsAttachmentsAddDeclarationsRequestKind.FULL_REPORT)
        .ref("ref")
        .build()
);
```
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

**kind:** `AnnualAccountsAttachmentsAddDeclarationsRequestKind` 
    
</dd>
</dl>

<dl>
<dd>

**name:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**ref:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.declarations.annualAccountsAttachmentsDelete(request) -> AnnualAccountsAttachmentsDeleteDeclarationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().annualAccountsAttachmentsDelete(
    AnnualAccountsAttachmentsDeleteDeclarationsRequest
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

<details><summary><code>client.declarations.cyTd4Generate(request) -> CyTd4GenerateDeclarationsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Compute the company income tax return TD4 of a tax year from the ledger and the recorded tax adjustments: the accounting profit, the add-backs, deductions, capital allowances and losses brought forward, the chargeable income, the corporation tax at the rate of the year and the double tax relief, as the fields the company keys into TAXISnet or Tax For All. The Tax Department publishes no upload layout for the TD4; the XML is a working file.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().cyTd4Generate(
    CyTd4GenerateDeclarationsRequest
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

<details><summary><code>client.declarations.cyHe32Generate(request) -> CyHe32GenerateDeclarationsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Build the annual return HE32 of a year: the figures the Registrar’s e-filing screens ask for (company number, registered office, made-up-to date, share capital, register of members, directors and secretary, annual general meeting date, the accounts summary), the working file, and the printed form HE32(I) filled in as a PDF for signing and for keying into the Registrar’s system, which takes the return only through its own screens.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().cyHe32Generate(
    CyHe32GenerateDeclarationsRequest
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

<details><summary><code>client.declarations.deReturnsGenerate(request) -> DeReturnsGenerateDeclarationsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Build one of the German returns that ELSTER accepts only through a licensed ERiC transmission (E-Bilanz, Körperschaftsteuer, Gewerbesteuer with its Zerlegungserklärung, annual VAT return, Lohnsteuer-Anmeldung, Lohnsteuerbescheinigung) for the company to send through its own ELSTER-capable program. The period is the year, or YYYY-MM for the monthly Lohnsteuer-Anmeldung.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().deReturnsGenerate(
    DeReturnsGenerateDeclarationsRequest
        .builder()
        .ruleKey(DeReturnsGenerateDeclarationsRequestRuleKey.DE_E_BILANZ)
        .period("period")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**ruleKey:** `DeReturnsGenerateDeclarationsRequestRuleKey` 
    
</dd>
</dl>

<dl>
<dd>

**period:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.declarations.deReturnFactsGet(request) -> DeReturnFactsGetDeclarationsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

The facts of one year that the German annual returns (Körperschaftsteuer, Gewerbesteuer, Umsatzsteuererklärung) need and the ledger does not hold: changes of shareholders, contracts with shareholders, the tax contribution account, loss carry-back, the donation carry-forward, the business premises with the municipalities for the apportionment of the trade tax, the land values or property tax and the participations for the trade tax additions and reductions, the foreign income per country for the Anlage AESt, the date of leaving the small-business scheme and the Anlage UN answers of a company seated abroad. A key that is absent has not been answered.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().deReturnFactsGet(
    DeReturnFactsGetDeclarationsRequest
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

<details><summary><code>client.declarations.deReturnFactsSet(request) -> DeReturnFactsSetDeclarationsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Replace the facts of one year for the German annual returns. The returns built afterwards read them; a key left out stays unanswered.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().deReturnFactsSet(
    DeReturnFactsSetDeclarationsRequest
        .builder()
        .year(1000000L)
        .facts(
            DeReturnFactsSetDeclarationsRequestFacts
                .builder()
                .build()
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

**year:** `Long` 
    
</dd>
</dl>

<dl>
<dd>

**facts:** `DeReturnFactsSetDeclarationsRequestFacts` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.declarations.deDeuevGenerate(request) -> DeDeuevGenerateDeclarationsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Build the DEÜV notifications of a month (Anmeldung for every start, Abmeldung for every leaving, in December the Jahresmeldung for everyone employed on 31 December) as DSME records with the DBME, DBNA, DBGB and DBAN blocks of Anlage 4 in force from 2026, from the approved payroll runs and the employee record, for the company's own transmission channel.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().deDeuevGenerate(
    DeDeuevGenerateDeclarationsRequest
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

<details><summary><code>client.declarations.deBeitragsnachweisGenerate(request) -> DeBeitragsnachweisGenerateDeclarationsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Build the monthly contribution statement to the health insurers (Beitragsnachweis) from the payroll run: one fixed-length record BW02 per insurer, in the record layout in force from 2026, ready for the company's own transmission channel.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().deBeitragsnachweisGenerate(
    DeBeitragsnachweisGenerateDeclarationsRequest
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

<details><summary><code>client.declarations.dkSelskabsskatGenerate(request) -> DkSelskabsskatGenerateDeclarationsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Compute the oplysningsskema for selskaber (selskabsselvangivelsen) of an income year from the ledger and the recorded tax adjustments: accounting result before tax, tax adjustments, losses carried forward, taxable income, the 22 % corporation tax, reliefs and the balance, as the rubrikker the company keys into TastSelv Selskabsskat (DIAS). Skatteforvaltningen publishes no file format for the return; the XML is a working file.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().dkSelskabsskatGenerate(
    DkSelskabsskatGenerateDeclarationsRequest
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

<details><summary><code>client.declarations.eeEmploymentRegisterSend(request) -> EeEmploymentRegisterSendDeclarationsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Send one employment register (töötamise register) entry for an employment contract to e-MTA over X-tee: the start of work, or its end with the reason recorded on the contract.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().eeEmploymentRegisterSend(
    EeEmploymentRegisterSendDeclarationsRequest
        .builder()
        .contractId("contractId")
        .event(EeEmploymentRegisterSendDeclarationsRequestEvent.START)
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**contractId:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**event:** `EeEmploymentRegisterSendDeclarationsRequestEvent` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.declarations.esVerifactuDeclaracionResponsable(request) -> EsVerifactuDeclaracionResponsableDeclarationsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Nordlet's declaración responsable for its VERI*FACTU invoicing system (Orden HAC/1177/2024, art. 15), as a PDF and as plain text.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().esVerifactuDeclaracionResponsable(
    EsVerifactuDeclaracionResponsableDeclarationsRequest
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

<details><summary><code>client.declarations.ieCt1Generate(request) -> IeCt1GenerateDeclarationsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Build the Form CT1 of an accounting year as the ROS version 26 XML and the accompanying financial statements as inline XBRL on the FRS 102 Irish Extension 2026 taxonomy Revenue accepts, both from the ledger, the recorded tax adjustments, the annual accounts record and the officers, for upload through the company’s own ROS account. Says whether the company is above the iXBRL deferral limits (balance sheet total €4.4 million, turnover €8.8 million, 50 employees).
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().ieCt1Generate(
    IeCt1GenerateDeclarationsRequest
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

<details><summary><code>client.declarations.ieB1Generate(request) -> IeB1GenerateDeclarationsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Build the working paper for the Form B1 annual return of a financial year — company details, registered office, directors and secretary from Settings → Officers, the members from Settings → Shareholders, the issued share capital and the figures of the financial statements — in the order the CORE screens ask for them. The CRO publishes no file format for the B1, so it is keyed into CORE.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().ieB1Generate(
    IeB1GenerateDeclarationsRequest
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

<details><summary><code>client.declarations.itSdiPurchaseSend(request) -> ItSdiPurchaseSendDeclarationsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Build the TD16-TD19 integration document for a registered purchase invoice and send it to the Sistema di Interscambio. Since July 2022 a purchase from a supplier established abroad is reported this way instead of the esterometro. The Italian VAT rate to self-assess is a judgement about the supply: pass vatRatePercent unless the purchase lines already carry it, otherwise the request is refused rather than guessed.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().itSdiPurchaseSend(
    ItSdiPurchaseSendDeclarationsRequest
        .builder()
        .purchaseInvoiceId("purchaseInvoiceId")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**purchaseInvoiceId:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**vatRatePercent:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**tipoDocumento:** `Optional<ItSdiPurchaseSendDeclarationsRequestTipoDocumento>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.declarations.itSdiPurchasePreview(request) -> ItSdiPurchasePreviewDeclarationsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Render the TD16-TD19 integration document for a registered purchase invoice without sending it, so the rate and the document type can be checked first.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().itSdiPurchasePreview(
    ItSdiPurchasePreviewDeclarationsRequest
        .builder()
        .purchaseInvoiceId("purchaseInvoiceId")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**purchaseInvoiceId:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**vatRatePercent:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**tipoDocumento:** `Optional<ItSdiPurchasePreviewDeclarationsRequestTipoDocumento>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.declarations.ltSaftSend(request) -> LtSaftSendDeclarationsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Upload the SAF-T file to i.SAF-T over the iSAFTUploaderService web service and start its processing. The file, the case reference and the status are kept as a declaration submission (submissionId), whose outcome Nordlet then checks with i.SAF-T. The submission itself is confirmed separately, because after confirmation the file can no longer be corrected. A range and data type already sent is sent again only with amend: true.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().ltSaftSend(
    LtSaftSendDeclarationsRequest
        .builder()
        .fromDate("2026-07-01")
        .toDate("2026-07-01")
        .build()
);
```
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

**dataType:** `Optional<LtSaftSendDeclarationsRequestDataType>` 
    
</dd>
</dl>

<dl>
<dd>

**confirm:** `Optional<Boolean>` 
    
</dd>
</dl>

<dl>
<dd>

**amend:** `Optional<Boolean>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.declarations.ltSdFfdata(request) -> LtSdFfdataDeclarationsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Render the Sodra 1-SD or 2-SD notice for the contracts starting or ending in the range as an .ffdata document for EDAS.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().ltSdFfdata(
    LtSdFfdataDeclarationsRequest
        .builder()
        .type(LtSdFfdataDeclarationsRequestType.ONE_SD)
        .fromDate("2026-07-01")
        .toDate("2026-07-01")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**type:** `LtSdFfdataDeclarationsRequestType` 
    
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

**managerFullName:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**preparatorDetails:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.declarations.ltPln204Ffdata(request) -> LtPln204FfdataDeclarationsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Render the annual corporate income tax return PLN204 as an .ffdata document, including the PLN204S and PLN204Z annexes, from the ledger and the tax adjustments recorded for that year.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().ltPln204Ffdata(
    LtPln204FfdataDeclarationsRequest
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

<details><summary><code>client.declarations.mtCompanyTaxGenerate(request) -> MtCompanyTaxGenerateDeclarationsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Compute the company income tax return and self-assessment of a year of assessment from the ledger and the recorded tax adjustments: the accounting profit before tax, the add-backs and deductions, the approved donations, capital allowances and losses carried forward, the chargeable income, the 35 % charge, the relief against the tax and the allocation of the distributable profit to the five tax accounts. The Malta Tax and Customs Administration issues the return as a personalised spreadsheet to the registered tax practitioner and publishes no layout, so the XML is a working file and the figures are keyed into that spreadsheet.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().mtCompanyTaxGenerate(
    MtCompanyTaxGenerateDeclarationsRequest
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

<details><summary><code>client.declarations.mtAnnualReturnGenerate(request) -> MtAnnualReturnGenerateDeclarationsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Build the annual return of a year: the company number, registered office and made-up-to date, the share capital, the register of members, the directors and the company secretary and the accounts summary, as the figures the Malta Business Registry asks for on its own screens, plus the printed Annual Return Form of the Seventh Schedule filled in as a PDF for signing.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().mtAnnualReturnGenerate(
    MtAnnualReturnGenerateDeclarationsRequest
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

<details><summary><code>client.declarations.plJpkFaGenerate(request) -> PlJpkFaGenerateDeclarationsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Generate JPK_FA(4), the on-demand structure with every sales invoice issued in a period, its VAT bases per rate and one row per invoice line. Filed only when the tax office asks for it.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().plJpkFaGenerate(
    PlJpkFaGenerateDeclarationsRequest
        .builder()
        .dateFrom("2026-07-01")
        .dateTo("2026-07-01")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**dateFrom:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**dateTo:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.declarations.plJpkKrGenerate(request) -> PlJpkKrGenerateDeclarationsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Generate JPK_KR(1), the on-demand structure with the chart of accounts and its opening balances and turnover, the journal and the double entries behind it. Filed only when the tax office asks for it.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().plJpkKrGenerate(
    PlJpkKrGenerateDeclarationsRequest
        .builder()
        .dateFrom("2026-07-01")
        .dateTo("2026-07-01")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**dateFrom:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**dateTo:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.declarations.plJpkMagGenerate(request) -> PlJpkMagGenerateDeclarationsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Generate JPK_MAG(2), the on-demand structure with the warehouse documents of one warehouse: goods received from outside (PZ) or internally (PW) and issued to a customer (WZ) or internally (RW). Filed only when the tax office asks for it.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().plJpkMagGenerate(
    PlJpkMagGenerateDeclarationsRequest
        .builder()
        .dateFrom("2026-07-01")
        .dateTo("2026-07-01")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**dateFrom:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**dateTo:** `String` 
    
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

<details><summary><code>client.declarations.plPit11Generate(request) -> PlPit11GenerateDeclarationsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Generate PIT-11(29) for every person on the payroll of one year: the pay, the deductible costs, the advance withheld and the social and health contributions taken off it. One document per person, because that is how the form is filed.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().plPit11Generate(
    PlPit11GenerateDeclarationsRequest
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

<details><summary><code>client.declarations.plCit8Generate(request) -> PlCit8GenerateDeclarationsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Generate CIT-8(34), the annual corporate income tax return, from the ledger of the year and the recorded tax adjustments. The tax office code and the small-taxpayer setting come from the e-Deklaracje compliance settings, the seat address from the JPK gateway settings. Names the annexes the figures would need, which are not produced.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().plCit8Generate(
    PlCit8GenerateDeclarationsRequest
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

<details><summary><code>client.declarations.plZusDraCompute(request) -> PlZusDraComputeDeclarationsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Compute the monthly ZUS DRA settlement from the payroll run of one month: the pension, disability, sickness, accident and health insurance contributions and the Labour Fund, Solidarity Fund and guaranteed benefits fund charges, each split between the insured person and the payer. The amounts are carried into Płatnik or ePłatnik by hand.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().plZusDraCompute(
    PlZusDraComputeDeclarationsRequest
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

<details><summary><code>client.declarations.plZusDraKedu(request) -> PlZusDraKeduDeclarationsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Build the KEDU file for one month: the ZUS DRA settlement and one ZUS RCA report per person on the payroll, in the schema kedu_5_4 that Płatnik and ePłatnik import. The payer REGON, short name and declaration deadline code come from the ZUS compliance settings; the insurance title code and working time of each person from the employee record.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().plZusDraKedu(
    PlZusDraKeduDeclarationsRequest
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

<details><summary><code>client.declarations.plZusDraPdf(request) -> PlZusDraPdfDeclarationsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Fill the published ZUS DRA form for one month and return it as a PDF. The amounts, the payer identity and the deadline code are the same ones the KEDU file carries; blocks the payroll does not hold (paid benefits, bridging pensions, income declaration of a self-paying person) stay empty.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().plZusDraPdf(
    PlZusDraPdfDeclarationsRequest
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

<details><summary><code>client.declarations.roEtransportBuild(request) -> RoEtransportBuildDeclarationsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Build the RO e-Transport declaration for an issued waybill: goods with their tariff codes and masses, the commercial partner, the route and the vehicle. The XML follows the ANAF eTransport v2 schema and is kept as a file on the waybill. Anything listed in blockers has to be filled in before /etransport/send will accept it.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().roEtransportBuild(
    RoEtransportBuildDeclarationsRequest
        .builder()
        .waybillId("waybillId")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**waybillId:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.declarations.roEtransportSubmit(request) -> RoEtransportSubmitDeclarationsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Hand the RO e-Transport declaration for an issued waybill to ANAF under the SPV OAuth token in compliance settings, and return the upload index the UIT is read back with. Answers 422 while any field the ANAF validator requires is still missing.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().roEtransportSubmit(
    RoEtransportSubmitDeclarationsRequest
        .builder()
        .waybillId("waybillId")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**waybillId:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.declarations.roEtransportStatus(request) -> RoEtransportStatusDeclarationsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Read the outcome of an e-Transport declaration from ANAF by its upload index, under the SPV OAuth token in compliance settings. Returns the UIT code once the declaration validates.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().roEtransportStatus(
    RoEtransportStatusDeclarationsRequest
        .builder()
        .reference("reference")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**reference:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.declarations.liLohndeklarationGenerate(request) -> LiLohndeklarationGenerateDeclarationsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Build the annual wage declaration (Lohndeklaration) to the AHV-IV-FAK from the approved payroll runs of the year as the CSV that AHVeasy imports under Lohndeklaration → CSV-Import der Lohndaten: one row per employee with the 18 columns of the AHVeasy template, the AHV-liable wage and the ALV wage.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().liLohndeklarationGenerate(
    LiLohndeklarationGenerateDeclarationsRequest
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

<details><summary><code>client.declarations.liLohnlistenGenerate(request) -> LiLohnlistenGenerateDeclarationsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Build the annual wage list (Lohnliste) of a Liechtenstein employer from the approved payroll runs of the year as the XLSX file the tax administration's eLohnausweis / eLohnlisten application imports: one row per employee with PEID, name, birth date, address, gross wage, wage tax withheld and the settlement period.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().liLohnlistenGenerate(
    LiLohnlistenGenerateDeclarationsRequest
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

<details><summary><code>client.declarations.configsList(request) -> ConfigsListDeclarationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().configsList(
    ConfigsListDeclarationsRequest
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

<details><summary><code>client.declarations.configsUpdate(request) -> ConfigsUpdateDeclarationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().configsUpdate(
    ConfigsUpdateDeclarationsRequest
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

<details><summary><code>client.declarations.certificatesUpload(request) -> CertificatesUploadDeclarationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().certificatesUpload(
    CertificatesUploadDeclarationsRequest
        .builder()
        .system("system")
        .fileName("fileName")
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

**system:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**fileName:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**content:** `String` — Base64-encoded PEM or PKCS#12 file
    
</dd>
</dl>

<dl>
<dd>

**passphrase:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.declarations.certificatesList(request) -> CertificatesListDeclarationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().certificatesList(
    CertificatesListDeclarationsRequest
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

<details><summary><code>client.declarations.certificatesDelete(request) -> CertificatesDeleteDeclarationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().certificatesDelete(
    CertificatesDeleteDeclarationsRequest
        .builder()
        .system("system")
        .fieldKey(CertificatesDeleteDeclarationsRequestFieldKey.CERTIFICATE)
        .build()
);
```
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

**fieldKey:** `CertificatesDeleteDeclarationsRequestFieldKey` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.declarations.automationList(request) -> AutomationListDeclarationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().automationList(
    AutomationListDeclarationsRequest
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

<details><summary><code>client.declarations.automationUpdate(request) -> AutomationUpdateDeclarationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().automationUpdate(
    AutomationUpdateDeclarationsRequest
        .builder()
        .ruleKey("ruleKey")
        .enabled(true)
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**ruleKey:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**enabled:** `Boolean` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.declarations.submissionsRetry(request) -> SubmissionsRetryDeclarationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().submissionsRetry(
    SubmissionsRetryDeclarationsRequest
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

<details><summary><code>client.declarations.submissionsCreate(request) -> SubmissionsCreateDeclarationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().submissionsCreate(
    SubmissionsCreateDeclarationsRequest
        .builder()
        .obligation(SubmissionsCreateDeclarationsRequestObligation.LT_ISAF)
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

**obligation:** `SubmissionsCreateDeclarationsRequestObligation` 
    
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

**dataType:** `Optional<SubmissionsCreateDeclarationsRequestDataType>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.declarations.submissionsMark(request) -> SubmissionsMarkDeclarationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().submissionsMark(
    SubmissionsMarkDeclarationsRequest
        .builder()
        .id("id")
        .status(SubmissionsMarkDeclarationsRequestStatus.SUBMITTED)
        .build()
);
```
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

**status:** `SubmissionsMarkDeclarationsRequestStatus` 
    
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

<details><summary><code>client.declarations.submissionsList(request) -> SubmissionsListDeclarationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.declarations().submissionsList(
    SubmissionsListDeclarationsRequest
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

**sort:** `Optional<List<SubmissionsListDeclarationsRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<SubmissionsListDeclarationsRequestFilterItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `Optional<List<String>>` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## ledger
<details><summary><code>client.ledger.accountsList(request) -> AccountsListLedgerResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.ledger().accountsList(
    AccountsListLedgerRequest
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

**sort:** `Optional<List<AccountsListLedgerRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<AccountsListLedgerRequestFilterItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `Optional<List<String>>` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.ledger.accountsCreate(request) -> AccountsCreateLedgerResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.ledger().accountsCreate(
    AccountsCreateLedgerRequest
        .builder()
        .code("code")
        .name("name")
        .type(AccountsCreateLedgerRequestType.ASSET)
        .build()
);
```
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

**translations:** `Optional<Map<String, AccountsCreateLedgerRequestTranslationsValue>>` 
    
</dd>
</dl>

<dl>
<dd>

**type:** `AccountsCreateLedgerRequestType` 
    
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

<details><summary><code>client.ledger.accountsUpdate(request) -> AccountsUpdateLedgerResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.ledger().accountsUpdate(
    AccountsUpdateLedgerRequest
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

**translations:** `Optional<Map<String, Optional<AccountsUpdateLedgerRequestTranslationsValue>>>` 
    
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

<details><summary><code>client.ledger.accountsApplyTemplate(request) -> AccountsApplyTemplateLedgerResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.ledger().accountsApplyTemplate(
    AccountsApplyTemplateLedgerRequest
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

<details><summary><code>client.ledger.accountsSwitchChart(request) -> AccountsSwitchChartLedgerResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Replaces the seeded chart with the chart template of the company country (the Romanian general chart for a company registered in Romania, the Lithuanian standard chart otherwise) and switches the posting defaults with it. Answers 409 when the company already uses that chart, has journal entries, holds accounts created by hand, or has settings that name an account the new chart does not have.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.ledger().accountsSwitchChart(
    AccountsSwitchChartLedgerRequest
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

<details><summary><code>client.ledger.periodsList(request) -> PeriodsListLedgerResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.ledger().periodsList(
    PeriodsListLedgerRequest
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

**sort:** `Optional<List<PeriodsListLedgerRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<PeriodsListLedgerRequestFilterItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `Optional<List<String>>` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.ledger.periodsLock(request) -> PeriodsLockLedgerResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.ledger().periodsLock(
    PeriodsLockLedgerRequest
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

<details><summary><code>client.ledger.periodsUnlock(request) -> PeriodsUnlockLedgerResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.ledger().periodsUnlock(
    PeriodsUnlockLedgerRequest
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

<details><summary><code>client.ledger.journalTransactionsList(request) -> JournalTransactionsListLedgerResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.ledger().journalTransactionsList(
    JournalTransactionsListLedgerRequest
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

**sort:** `Optional<List<JournalTransactionsListLedgerRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<JournalTransactionsListLedgerRequestFilterItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `Optional<List<String>>` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.ledger.costCentersCreate(request) -> CostCentersCreateLedgerResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.ledger().costCentersCreate(
    CostCentersCreateLedgerRequest
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

<details><summary><code>client.ledger.costCentersUpdate(request) -> CostCentersUpdateLedgerResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.ledger().costCentersUpdate(
    CostCentersUpdateLedgerRequest
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

<details><summary><code>client.ledger.costCentersList(request) -> CostCentersListLedgerResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.ledger().costCentersList(
    CostCentersListLedgerRequest
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

**sort:** `Optional<List<CostCentersListLedgerRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<CostCentersListLedgerRequestFilterItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `Optional<List<String>>` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.ledger.costCenterGroupsCreate(request) -> CostCenterGroupsCreateLedgerResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.ledger().costCenterGroupsCreate(
    CostCenterGroupsCreateLedgerRequest
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

<details><summary><code>client.ledger.costCenterGroupsUpdate(request) -> CostCenterGroupsUpdateLedgerResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.ledger().costCenterGroupsUpdate(
    CostCenterGroupsUpdateLedgerRequest
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

<details><summary><code>client.ledger.costCenterGroupsDelete(request) -> CostCenterGroupsDeleteLedgerResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.ledger().costCenterGroupsDelete(
    CostCenterGroupsDeleteLedgerRequest
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

<details><summary><code>client.ledger.costCenterGroupsList(request) -> CostCenterGroupsListLedgerResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.ledger().costCenterGroupsList(
    CostCenterGroupsListLedgerRequest
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

**sort:** `Optional<List<CostCenterGroupsListLedgerRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<CostCenterGroupsListLedgerRequestFilterItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `Optional<List<String>>` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.ledger.postingRulesList(request) -> PostingRulesListLedgerResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.ledger().postingRulesList(
    PostingRulesListLedgerRequest
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

<details><summary><code>client.ledger.postingRulesUpdate(request) -> PostingRulesUpdateLedgerResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.ledger().postingRulesUpdate(
    PostingRulesUpdateLedgerRequest
        .builder()
        .rules(
            Arrays.asList(
                PostingRulesUpdateLedgerRequestRulesItem
                    .builder()
                    .key(PostingRulesUpdateLedgerRequestRulesItemKey.SALES_RECEIVABLE)
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

**rules:** `List<PostingRulesUpdateLedgerRequestRulesItem>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.ledger.ownersCreate(request) -> OwnersCreateLedgerResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.ledger().ownersCreate(
    OwnersCreateLedgerRequest
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

**sharesType:** `Optional<OwnersCreateLedgerRequestSharesType>` 
    
</dd>
</dl>

<dl>
<dd>

**sharesAcquisitionDate:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**withholdingTaxPercent:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**partnerLiability:** `Optional<OwnersCreateLedgerRequestPartnerLiability>` 
    
</dd>
</dl>

<dl>
<dd>

**specialBalanceRequired:** `Optional<Boolean>` 
    
</dd>
</dl>

<dl>
<dd>

**supplementaryBalanceRequired:** `Optional<Boolean>` 
    
</dd>
</dl>

<dl>
<dd>

**address:** `Optional<OwnersCreateLedgerRequestAddress>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.ledger.ownersUpdate(request) -> OwnersUpdateLedgerResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.ledger().ownersUpdate(
    OwnersUpdateLedgerRequest
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

**sharesType:** `Optional<OwnersUpdateLedgerRequestSharesType>` 
    
</dd>
</dl>

<dl>
<dd>

**sharesAcquisitionDate:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**withholdingTaxPercent:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**partnerLiability:** `Optional<OwnersUpdateLedgerRequestPartnerLiability>` 
    
</dd>
</dl>

<dl>
<dd>

**specialBalanceRequired:** `Optional<Boolean>` 
    
</dd>
</dl>

<dl>
<dd>

**supplementaryBalanceRequired:** `Optional<Boolean>` 
    
</dd>
</dl>

<dl>
<dd>

**address:** `Optional<OwnersUpdateLedgerRequestAddress>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.ledger.ownersDelete(request) -> OwnersDeleteLedgerResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.ledger().ownersDelete(
    OwnersDeleteLedgerRequest
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

<details><summary><code>client.ledger.ownersList(request) -> OwnersListLedgerResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.ledger().ownersList(
    OwnersListLedgerRequest
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

**sort:** `Optional<List<OwnersListLedgerRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<OwnersListLedgerRequestFilterItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `Optional<List<String>>` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.ledger.journalTransactionsGet(request) -> JournalTransactionsGetLedgerResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.ledger().journalTransactionsGet(
    JournalTransactionsGetLedgerRequest
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

<details><summary><code>client.ledger.journalTransactionsCreate(request) -> JournalTransactionsCreateLedgerResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.ledger().journalTransactionsCreate(
    JournalTransactionsCreateLedgerRequest
        .builder()
        .date("2026-07-01")
        .entries(
            Arrays.asList(
                JournalTransactionsCreateLedgerRequestEntriesItem
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

**entries:** `List<JournalTransactionsCreateLedgerRequestEntriesItem>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.ledger.statementRowsSchemes(request) -> StatementRowsSchemesLedgerResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

The rows or codes of each return or registry deposit of the company country that are filled from account balances. Accounts fall into a row by the layout defaults for the standard chart of accounts unless mapped under Settings → Statement rows.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.ledger().statementRowsSchemes(
    StatementRowsSchemesLedgerRequest
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

<details><summary><code>client.ledger.statementRowsList(request) -> StatementRowsListLedgerResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.ledger().statementRowsList(
    StatementRowsListLedgerRequest
        .builder()
        .scheme("scheme")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**scheme:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**fromDate:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**toDate:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.ledger.statementRowsSet(request) -> StatementRowsSetLedgerResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

A mapping on a code prefix covers every account whose code starts with it; the longest matching prefix wins. An empty rowCode removes the mapping so the layout default applies again.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.ledger().statementRowsSet(
    StatementRowsSetLedgerRequest
        .builder()
        .scheme("scheme")
        .accountCode("accountCode")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**scheme:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**accountCode:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**rowCode:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Officers
<details><summary><code>client.officers.list(request) -> ListOfficersResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Directors, board members, the company secretary, representatives and liquidators, with their personal identifier, appointment and resignation dates and whether they sign the annual accounts. Annual returns and registry deposits are built from this register.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.officers().list(
    ListOfficersRequest
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

<details><summary><code>client.officers.create(request) -> CreateOfficersResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.officers().create(
    CreateOfficersRequest
        .builder()
        .name("name")
        .role(CreateOfficersRequestRole.DIRECTOR)
        .build()
);
```
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

**role:** `CreateOfficersRequestRole` 
    
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

**appointedOn:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**powerNotary:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**resignedOn:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**signsAccounts:** `Optional<Boolean>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.officers.update(request) -> UpdateOfficersResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.officers().update(
    UpdateOfficersRequest
        .builder()
        .id("id")
        .name("name")
        .role(UpdateOfficersRequestRole.DIRECTOR)
        .build()
);
```
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

**name:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**role:** `UpdateOfficersRequestRole` 
    
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

**appointedOn:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**powerNotary:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**resignedOn:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**signsAccounts:** `Optional<Boolean>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.officers.delete(request) -> DeleteOfficersResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.officers().delete(
    DeleteOfficersRequest
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

## migration
<details><summary><code>client.migration.booksValidate(request) -> BooksValidateMigrationResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Runs every check the import runs (accounts, partners, balances, open invoices, assets, stock) and returns the same summary and warnings, then rolls everything back. Nothing is stored.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.migration().booksValidate(
    BooksValidateMigrationRequest
        .builder()
        .cutoverDate("2026-07-01")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**cutoverDate:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**source:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**accounts:** `Optional<List<BooksValidateMigrationRequestAccountsItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**partners:** `Optional<List<BooksValidateMigrationRequestPartnersItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**items:** `Optional<List<BooksValidateMigrationRequestItemsItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**openingBalances:** `Optional<BooksValidateMigrationRequestOpeningBalances>` 
    
</dd>
</dl>

<dl>
<dd>

**journal:** `Optional<List<BooksValidateMigrationRequestJournalItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**openReceivables:** `Optional<List<BooksValidateMigrationRequestOpenReceivablesItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**openPayables:** `Optional<List<BooksValidateMigrationRequestOpenPayablesItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**assetGroups:** `Optional<List<BooksValidateMigrationRequestAssetGroupsItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**fixedAssets:** `Optional<List<BooksValidateMigrationRequestFixedAssetsItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**stock:** `Optional<List<BooksValidateMigrationRequestStockItem>>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.migration.booksImport(request) -> BooksImportMigrationResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Brings a company over from another system in one call: chart of accounts, partners, items, opening balances (or the full journal history), open customer and supplier invoices, fixed assets with their accumulated depreciation, and stock on hand. The whole package is written in one database transaction — if any row fails, nothing is stored.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.migration().booksImport(
    BooksImportMigrationRequest
        .builder()
        .cutoverDate("2026-07-01")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**cutoverDate:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**source:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**accounts:** `Optional<List<BooksImportMigrationRequestAccountsItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**partners:** `Optional<List<BooksImportMigrationRequestPartnersItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**items:** `Optional<List<BooksImportMigrationRequestItemsItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**openingBalances:** `Optional<BooksImportMigrationRequestOpeningBalances>` 
    
</dd>
</dl>

<dl>
<dd>

**journal:** `Optional<List<BooksImportMigrationRequestJournalItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**openReceivables:** `Optional<List<BooksImportMigrationRequestOpenReceivablesItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**openPayables:** `Optional<List<BooksImportMigrationRequestOpenPayablesItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**assetGroups:** `Optional<List<BooksImportMigrationRequestAssetGroupsItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**fixedAssets:** `Optional<List<BooksImportMigrationRequestFixedAssetsItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**stock:** `Optional<List<BooksImportMigrationRequestStockItem>>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## assets
<details><summary><code>client.assets.groupsCreate(request) -> GroupsCreateAssetsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.assets().groupsCreate(
    GroupsCreateAssetsRequest
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

<details><summary><code>client.assets.groupsList(request) -> GroupsListAssetsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.assets().groupsList(
    GroupsListAssetsRequest
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

**sort:** `Optional<List<GroupsListAssetsRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<GroupsListAssetsRequestFilterItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `Optional<List<String>>` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.assets.assetsCreate(request) -> AssetsCreateAssetsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.assets().assetsCreate(
    AssetsCreateAssetsRequest
        .builder()
        .groupId("groupId")
        .code("code")
        .name("name")
        .acquisitionDate("2026-07-01")
        .acquisitionCost("121.0000")
        .build()
);
```
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

<dl>
<dd>

**documents:** `Optional<List<AssetsCreateAssetsRequestDocumentsItem>>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.assets.assetsUpdate(request) -> AssetsUpdateAssetsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.assets().assetsUpdate(
    AssetsUpdateAssetsRequest
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

**groupId:** `Optional<String>` 
    
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

**acquisitionDate:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**depreciationStartDate:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**acquisitionCost:** `Optional<String>` 
    
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

<dl>
<dd>

**documents:** `Optional<List<AssetsUpdateAssetsRequestDocumentsItem>>` 
    
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

<details><summary><code>client.assets.assetsInputVat(request) -> AssetsInputVatAssetsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Record the input VAT facts of a capital good that the annual VAT return needs for the adjustment of the deduction over the adjustment period (Article 187 of the VAT Directive, § 15a UStG): the input VAT on the acquisition, the date of first use, the share of use for deductible turnover at first use, whether it is land or a building (ten-year period instead of five), and every later year in which the share changed or the good was sold or withdrawn. Allowed also after depreciation has been posted.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.assets().assetsInputVat(
    AssetsInputVatAssetsRequest
        .builder()
        .id("id")
        .inputVatRealEstate(true)
        .inputVatUseChanges(
            Arrays.asList(
                AssetsInputVatAssetsRequestInputVatUseChangesItem
                    .builder()
                    .year(1000000L)
                    .percent("121.00")
                    .reason(AssetsInputVatAssetsRequestInputVatUseChangesItemReason.USE_CHANGE)
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

**id:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**inputVatAmount:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**inputVatFirstUseDate:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**inputVatDeductiblePercent:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**inputVatRealEstate:** `Boolean` 
    
</dd>
</dl>

<dl>
<dd>

**inputVatUseChanges:** `List<AssetsInputVatAssetsRequestInputVatUseChangesItem>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.assets.assetsGet(request) -> AssetsGetAssetsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.assets().assetsGet(
    AssetsGetAssetsRequest
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

<details><summary><code>client.assets.assetsList(request) -> AssetsListAssetsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.assets().assetsList(
    AssetsListAssetsRequest
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

**sort:** `Optional<List<AssetsListAssetsRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<AssetsListAssetsRequestFilterItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `Optional<List<String>>` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.assets.assetsModernize(request) -> AssetsModernizeAssetsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.assets().assetsModernize(
    AssetsModernizeAssetsRequest
        .builder()
        .id("id")
        .date("2026-07-01")
        .amount("121.0000")
        .build()
);
```
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

<details><summary><code>client.assets.assetsDispose(request) -> AssetsDisposeAssetsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Dispose of a fixed asset (sold, scrapped or written off). Removes its cost and accumulated depreciation, books the net book value as a disposal loss and the proceeds as a disposal gain (posting rules assets.disposalLoss, assets.disposalGain, assets.disposalProceeds), and stops its depreciation. Depreciation must be posted for every month before the disposal month.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.assets().assetsDispose(
    AssetsDisposeAssetsRequest
        .builder()
        .id("id")
        .date("2026-07-01")
        .reason(AssetsDisposeAssetsRequestReason.SOLD)
        .build()
);
```
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

**reason:** `AssetsDisposeAssetsRequestReason` 
    
</dd>
</dl>

<dl>
<dd>

**proceeds:** `Optional<String>` — Sale price excluding VAT; 0 when scrapped or written off
    
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

<details><summary><code>client.assets.depreciationPreview(request) -> DepreciationPreviewAssetsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.assets().depreciationPreview(
    DepreciationPreviewAssetsRequest
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

<details><summary><code>client.assets.depreciationPost(request) -> DepreciationPostAssetsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.assets().depreciationPost(
    DepreciationPostAssetsRequest
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

## hr
<details><summary><code>client.hr.positionsCreate(request) -> PositionsCreateHrResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.hr().positionsCreate(
    PositionsCreateHrRequest
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

**translations:** `Optional<Map<String, PositionsCreateHrRequestTranslationsValue>>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.hr.positionsUpdate(request) -> PositionsUpdateHrResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.hr().positionsUpdate(
    PositionsUpdateHrRequest
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

**translations:** `Optional<Map<String, Optional<PositionsUpdateHrRequestTranslationsValue>>>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.hr.positionsList(request) -> PositionsListHrResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.hr().positionsList(
    PositionsListHrRequest
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

**sort:** `Optional<List<PositionsListHrRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<PositionsListHrRequestFilterItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `Optional<List<String>>` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.hr.employeesCreate(request) -> EmployeesCreateHrResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.hr().employeesCreate(
    EmployeesCreateHrRequest
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

**address:** `Optional<EmployeesCreateHrRequestAddress>` 
    
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

**applyAllowance:** `Optional<Boolean>` 
    
</dd>
</dl>

<dl>
<dd>

**allowanceOverride:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**pensionAccumulation:** `Optional<Boolean>` 
    
</dd>
</dl>

<dl>
<dd>

**payrollOptions:** `Optional<Map<String, String>>` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**attributes:** `Optional<List<EmployeesCreateHrRequestAttributesItem>>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.hr.employeesUpdate(request) -> EmployeesUpdateHrResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.hr().employeesUpdate(
    EmployeesUpdateHrRequest
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

**address:** `Optional<EmployeesUpdateHrRequestAddress>` 
    
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

**applyAllowance:** `Optional<Boolean>` 
    
</dd>
</dl>

<dl>
<dd>

**allowanceOverride:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**pensionAccumulation:** `Optional<Boolean>` 
    
</dd>
</dl>

<dl>
<dd>

**payrollOptions:** `Optional<Map<String, String>>` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**attributes:** `Optional<List<EmployeesUpdateHrRequestAttributesItem>>` 
    
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

**status:** `Optional<EmployeesUpdateHrRequestStatus>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.hr.employeesGet(request) -> EmployeesGetHrResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.hr().employeesGet(
    EmployeesGetHrRequest
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

<details><summary><code>client.hr.employeesFields(request) -> EmployeesFieldsHrResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Attributes a filing of the company country needs about a person that the shared employee record does not carry, such as the sex and place of birth an Italian income certificate asks for. Their values are kept in the payrollOptions of the employee.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.hr().employeesFields(
    EmployeesFieldsHrRequest
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

<details><summary><code>client.hr.employeesList(request) -> EmployeesListHrResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.hr().employeesList(
    EmployeesListHrRequest
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

**sort:** `Optional<List<EmployeesListHrRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<EmployeesListHrRequestFilterItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `Optional<List<String>>` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.hr.employeesDelete(request) -> EmployeesDeleteHrResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.hr().employeesDelete(
    EmployeesDeleteHrRequest
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

<details><summary><code>client.hr.employeesAnonymize(request) -> EmployeesAnonymizeHrResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Replaces the name with a placeholder and removes personal code, birth date, contact details, address, bank account, social-insurance number, notes and sick-leave reasons. Payroll and contract rows stay linked to the record for the statutory retention period.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.hr().employeesAnonymize(
    EmployeesAnonymizeHrRequest
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

<details><summary><code>client.hr.contractsCreate(request) -> ContractsCreateHrResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.hr().contractsCreate(
    ContractsCreateHrRequest
        .builder()
        .employeeId("employeeId")
        .startDate("2026-07-01")
        .baseSalary("121.0000")
        .build()
);
```
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

**agreementId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**contractNo:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**type:** `Optional<ContractsCreateHrRequestType>` 
    
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

**salaryType:** `Optional<ContractsCreateHrRequestSalaryType>` 
    
</dd>
</dl>

<dl>
<dd>

**workHours:** `Optional<String>` 
    
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

<details><summary><code>client.hr.contractsEnd(request) -> ContractsEndHrResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.hr().contractsEnd(
    ContractsEndHrRequest
        .builder()
        .id("id")
        .endDate("2026-07-01")
        .build()
);
```
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

<details><summary><code>client.hr.contractsList(request) -> ContractsListHrResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.hr().contractsList(
    ContractsListHrRequest
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

**sort:** `Optional<List<ContractsListHrRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<ContractsListHrRequestFilterItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `Optional<List<String>>` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.hr.leaveBalancesSet(request) -> LeaveBalancesSetHrResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.hr().leaveBalancesSet(
    LeaveBalancesSetHrRequest
        .builder()
        .employeeId("employeeId")
        .year(1000000L)
        .entitledDays("121.00")
        .build()
);
```
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

<details><summary><code>client.hr.leaveBalancesList(request) -> LeaveBalancesListHrResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.hr().leaveBalancesList(
    LeaveBalancesListHrRequest
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

<details><summary><code>client.hr.incapacityCertificatesCreate(request) -> IncapacityCertificatesCreateHrResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.hr().incapacityCertificatesCreate(
    IncapacityCertificatesCreateHrRequest
        .builder()
        .employeeId("employeeId")
        .number("number")
        .fromDate("2026-07-01")
        .toDate("2026-07-01")
        .build()
);
```
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

<details><summary><code>client.hr.incapacityCertificatesList(request) -> IncapacityCertificatesListHrResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.hr().incapacityCertificatesList(
    IncapacityCertificatesListHrRequest
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

**sort:** `Optional<List<IncapacityCertificatesListHrRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<IncapacityCertificatesListHrRequestFilterItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `Optional<List<String>>` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.hr.employeesRecordsCreate(request) -> EmployeesRecordsCreateHrResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.hr().employeesRecordsCreate(
    EmployeesRecordsCreateHrRequest
        .builder()
        .employeeId("employeeId")
        .type(EmployeesRecordsCreateHrRequestType.EDUCATION)
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

**type:** `EmployeesRecordsCreateHrRequestType` 
    
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

<details><summary><code>client.hr.employeesRecordsUpdate(request) -> EmployeesRecordsUpdateHrResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.hr().employeesRecordsUpdate(
    EmployeesRecordsUpdateHrRequest
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

**type:** `Optional<EmployeesRecordsUpdateHrRequestType>` 
    
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

<details><summary><code>client.hr.employeesRecordsDelete(request) -> EmployeesRecordsDeleteHrResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.hr().employeesRecordsDelete(
    EmployeesRecordsDeleteHrRequest
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

<details><summary><code>client.hr.employeesRecordsList(request) -> EmployeesRecordsListHrResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.hr().employeesRecordsList(
    EmployeesRecordsListHrRequest
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

**sort:** `Optional<List<EmployeesRecordsListHrRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<EmployeesRecordsListHrRequestFilterItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `Optional<List<String>>` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.hr.employeesAttachmentsList(request) -> EmployeesAttachmentsListHrResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.hr().employeesAttachmentsList(
    EmployeesAttachmentsListHrRequest
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

<details><summary><code>client.hr.timesheetsGenerate(request) -> TimesheetsGenerateHrResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.hr().timesheetsGenerate(
    TimesheetsGenerateHrRequest
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

<details><summary><code>client.hr.timesheetsUpsert(request) -> TimesheetsUpsertHrResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.hr().timesheetsUpsert(
    TimesheetsUpsertHrRequest
        .builder()
        .employeeId("employeeId")
        .year(1000000L)
        .month(1000000L)
        .days(
            Arrays.asList(
                TimesheetsUpsertHrRequestDaysItem
                    .builder()
                    .day(1000000L)
                    .hours("121.00")
                    .type(TimesheetsUpsertHrRequestDaysItemType.WORK)
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

**days:** `List<TimesheetsUpsertHrRequestDaysItem>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.hr.timesheetsGet(request) -> TimesheetsGetHrResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.hr().timesheetsGet(
    TimesheetsGetHrRequest
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

<details><summary><code>client.hr.timesheetsList(request) -> TimesheetsListHrResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.hr().timesheetsList(
    TimesheetsListHrRequest
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

<details><summary><code>client.hr.timesheetsDelete(request) -> TimesheetsDeleteHrResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.hr().timesheetsDelete(
    TimesheetsDeleteHrRequest
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

## fleet
<details><summary><code>client.fleet.vehiclesCreate(request) -> VehiclesCreateFleetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.fleet().vehiclesCreate(
    VehiclesCreateFleetRequest
        .builder()
        .plateNumber("plateNumber")
        .make("make")
        .model("model")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**plateNumber:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**make:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**model:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**year:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**vin:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**fuelType:** `Optional<VehiclesCreateFleetRequestFuelType>` 
    
</dd>
</dl>

<dl>
<dd>

**acquisitionDate:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**marketValue:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**fixedAssetId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**technicalInspectionDue:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**insuranceDue:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**documents:** `Optional<List<VehiclesCreateFleetRequestDocumentsItem>>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.fleet.vehiclesUpdate(request) -> VehiclesUpdateFleetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.fleet().vehiclesUpdate(
    VehiclesUpdateFleetRequest
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

**plateNumber:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**make:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**model:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**year:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**vin:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**fuelType:** `Optional<VehiclesUpdateFleetRequestFuelType>` 
    
</dd>
</dl>

<dl>
<dd>

**acquisitionDate:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**marketValue:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**fixedAssetId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**technicalInspectionDue:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**insuranceDue:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**status:** `Optional<VehiclesUpdateFleetRequestStatus>` 
    
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

<details><summary><code>client.fleet.vehiclesGet(request) -> VehiclesGetFleetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.fleet().vehiclesGet(
    VehiclesGetFleetRequest
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

<details><summary><code>client.fleet.vehiclesList(request) -> VehiclesListFleetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.fleet().vehiclesList(
    VehiclesListFleetRequest
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

**sort:** `Optional<List<VehiclesListFleetRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<VehiclesListFleetRequestFilterItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `Optional<List<String>>` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.fleet.assignmentsCreate(request) -> AssignmentsCreateFleetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.fleet().assignmentsCreate(
    AssignmentsCreateFleetRequest
        .builder()
        .vehicleId("vehicleId")
        .employeeId("employeeId")
        .fromDate("2026-07-01")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**vehicleId:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**employeeId:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**fromDate:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**toDate:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**privateUse:** `Optional<Boolean>` 
    
</dd>
</dl>

<dl>
<dd>

**employerPaysFuel:** `Optional<Boolean>` 
    
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

<details><summary><code>client.fleet.assignmentsEnd(request) -> AssignmentsEndFleetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.fleet().assignmentsEnd(
    AssignmentsEndFleetRequest
        .builder()
        .id("id")
        .toDate("2026-07-01")
        .build()
);
```
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

**toDate:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.fleet.assignmentsList(request) -> AssignmentsListFleetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.fleet().assignmentsList(
    AssignmentsListFleetRequest
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

**sort:** `Optional<List<AssignmentsListFleetRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<AssignmentsListFleetRequestFilterItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `Optional<List<String>>` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.fleet.naturaPreview(request) -> NaturaPreviewFleetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.fleet().naturaPreview(
    NaturaPreviewFleetRequest
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

## payroll
<details><summary><code>client.payroll.departmentsCreate(request) -> DepartmentsCreatePayrollResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.payroll().departmentsCreate(
    DepartmentsCreatePayrollRequest
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

<details><summary><code>client.payroll.departmentsList(request) -> DepartmentsListPayrollResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.payroll().departmentsList(
    DepartmentsListPayrollRequest
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

<details><summary><code>client.payroll.schedulesCreate(request) -> SchedulesCreatePayrollResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.payroll().schedulesCreate(
    SchedulesCreatePayrollRequest
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

<details><summary><code>client.payroll.schedulesList(request) -> SchedulesListPayrollResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.payroll().schedulesList(
    SchedulesListPayrollRequest
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

<details><summary><code>client.payroll.calc(request) -> CalcPayrollResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.payroll().calc(
    CalcPayrollRequest
        .builder()
        .taxableBase("121.00")
        .date("2026-07-01")
        .build()
);
```
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

**applyAllowance:** `Optional<Boolean>` 
    
</dd>
</dl>

<dl>
<dd>

**allowanceOverride:** `Optional<String>` 
    
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

<dl>
<dd>

**benefitInKind:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**options:** `Optional<Map<String, String>>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.payroll.runsCreate(request) -> RunsCreatePayrollResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.payroll().runsCreate(
    RunsCreatePayrollRequest
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

**includeNatura:** `Optional<Boolean>` 
    
</dd>
</dl>

<dl>
<dd>

**grossOverrides:** `Optional<List<RunsCreatePayrollRequestGrossOverridesItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**lines:** `Optional<List<RunsCreatePayrollRequestLinesItem>>` 
    
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

<details><summary><code>client.payroll.runsGet(request) -> RunsGetPayrollResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.payroll().runsGet(
    RunsGetPayrollRequest
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

<details><summary><code>client.payroll.runsList(request) -> RunsListPayrollResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.payroll().runsList(
    RunsListPayrollRequest
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

**sort:** `Optional<List<RunsListPayrollRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<RunsListPayrollRequestFilterItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `Optional<List<String>>` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.payroll.linesAttendance(request) -> LinesAttendancePayrollResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

The days and hours worked, the days on the register and the average hourly earnings that some countries report per employment. The Czech monthly employer report asks for all four. They can be set while the run is a draft.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.payroll().linesAttendance(
    LinesAttendancePayrollRequest
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

**daysWorked:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**hoursWorked:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**registeredDays:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**averageHourlyEarnings:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.payroll.runsApprove(request) -> RunsApprovePayrollResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.payroll().runsApprove(
    RunsApprovePayrollRequest
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

**employerSocialAccountCode:** `Optional<String>` 
    
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

<details><summary><code>client.payroll.runsCancel(request) -> RunsCancelPayrollResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.payroll().runsCancel(
    RunsCancelPayrollRequest
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

<details><summary><code>client.payroll.paymentsExport(request) -> PaymentsExportPayrollResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.payroll().paymentsExport(
    PaymentsExportPayrollRequest
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

<dl>
<dd>

**locale:** `Optional<PaymentsExportPayrollRequestLocale>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## agreements
<details><summary><code>client.agreements.typesCreate(request) -> TypesCreateAgreementsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.agreements().typesCreate(
    TypesCreateAgreementsRequest
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

<details><summary><code>client.agreements.typesList(request) -> TypesListAgreementsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.agreements().typesList(
    TypesListAgreementsRequest
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

**sort:** `Optional<List<TypesListAgreementsRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<TypesListAgreementsRequestFilterItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `Optional<List<String>>` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.agreements.agreementsCreate(request) -> AgreementsCreateAgreementsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.agreements().agreementsCreate(
    AgreementsCreateAgreementsRequest
        .builder()
        .number("number")
        .startDate("2026-07-01")
        .build()
);
```
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

**kind:** `Optional<AgreementsCreateAgreementsRequestKind>` 
    
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

**bankAccountId:** `Optional<String>` 
    
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

**billingPeriod:** `Optional<AgreementsCreateAgreementsRequestBillingPeriod>` 
    
</dd>
</dl>

<dl>
<dd>

**currency:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**status:** `Optional<AgreementsCreateAgreementsRequestStatus>` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**documentRef:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**items:** `Optional<List<AgreementsCreateAgreementsRequestItemsItem>>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.agreements.agreementsGet(request) -> AgreementsGetAgreementsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.agreements().agreementsGet(
    AgreementsGetAgreementsRequest
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

<details><summary><code>client.agreements.agreementsUpdate(request) -> AgreementsUpdateAgreementsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.agreements().agreementsUpdate(
    AgreementsUpdateAgreementsRequest
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

**kind:** `Optional<AgreementsUpdateAgreementsRequestKind>` 
    
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

**billingPeriod:** `Optional<AgreementsUpdateAgreementsRequestBillingPeriod>` 
    
</dd>
</dl>

<dl>
<dd>

**status:** `Optional<AgreementsUpdateAgreementsRequestStatus>` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**documentRef:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.agreements.agreementsDelete(request) -> AgreementsDeleteAgreementsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.agreements().agreementsDelete(
    AgreementsDeleteAgreementsRequest
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

<details><summary><code>client.agreements.agreementsList(request) -> AgreementsListAgreementsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.agreements().agreementsList(
    AgreementsListAgreementsRequest
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

**sort:** `Optional<List<AgreementsListAgreementsRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<AgreementsListAgreementsRequestFilterItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `Optional<List<String>>` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.agreements.agreementsGenerateInvoice(request) -> AgreementsGenerateInvoiceAgreementsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.agreements().agreementsGenerateInvoice(
    AgreementsGenerateInvoiceAgreementsRequest
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

**asOfDate:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.agreements.agreementsBillingRun(request) -> AgreementsBillingRunAgreementsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.agreements().agreementsBillingRun(
    AgreementsBillingRunAgreementsRequest
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

**asOfDate:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.agreements.insurancePoliciesCreate(request) -> InsurancePoliciesCreateAgreementsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.agreements().insurancePoliciesCreate(
    InsurancePoliciesCreateAgreementsRequest
        .builder()
        .policyNumber("policyNumber")
        .insuredObject("insuredObject")
        .fromDate("2026-07-01")
        .toDate("2026-07-01")
        .build()
);
```
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

<details><summary><code>client.agreements.insurancePoliciesList(request) -> InsurancePoliciesListAgreementsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.agreements().insurancePoliciesList(
    InsurancePoliciesListAgreementsRequest
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

**sort:** `Optional<List<InsurancePoliciesListAgreementsRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<InsurancePoliciesListAgreementsRequestFilterItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `Optional<List<String>>` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.agreements.insurancePoliciesDelete(request) -> InsurancePoliciesDeleteAgreementsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.agreements().insurancePoliciesDelete(
    InsurancePoliciesDeleteAgreementsRequest
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

## inventory
<details><summary><code>client.inventory.settingsGet(request) -> SettingsGetInventoryResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.inventory().settingsGet(
    SettingsGetInventoryRequest
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

<details><summary><code>client.inventory.settingsUpdate(request) -> SettingsUpdateInventoryResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.inventory().settingsUpdate(
    SettingsUpdateInventoryRequest
        .builder()
        .negativeStockPolicy(SettingsUpdateInventoryRequestNegativeStockPolicy.REJECT)
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**negativeStockPolicy:** `SettingsUpdateInventoryRequestNegativeStockPolicy` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.inventory.warehousesCreate(request) -> WarehousesCreateInventoryResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.inventory().warehousesCreate(
    WarehousesCreateInventoryRequest
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

<details><summary><code>client.inventory.warehousesList(request) -> WarehousesListInventoryResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.inventory().warehousesList(
    WarehousesListInventoryRequest
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

**sort:** `Optional<List<WarehousesListInventoryRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<WarehousesListInventoryRequestFilterItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `Optional<List<String>>` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.inventory.stockReceive(request) -> StockReceiveInventoryResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.inventory().stockReceive(
    StockReceiveInventoryRequest
        .builder()
        .warehouseId("warehouseId")
        .itemId("itemId")
        .date("2026-07-01")
        .quantity("121.0000")
        .unitCost("121.000000")
        .build()
);
```
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

**lotNumber:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**expiryDate:** `Optional<String>` 
    
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

<details><summary><code>client.inventory.stockWriteOff(request) -> StockWriteOffInventoryResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.inventory().stockWriteOff(
    StockWriteOffInventoryRequest
        .builder()
        .warehouseId("warehouseId")
        .itemId("itemId")
        .date("2026-07-01")
        .quantity("121.0000")
        .build()
);
```
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

**lotNumber:** `Optional<String>` 
    
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

<details><summary><code>client.inventory.stockTransfer(request) -> StockTransferInventoryResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.inventory().stockTransfer(
    StockTransferInventoryRequest
        .builder()
        .fromWarehouseId("fromWarehouseId")
        .toWarehouseId("toWarehouseId")
        .itemId("itemId")
        .date("2026-07-01")
        .quantity("121.0000")
        .build()
);
```
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

**lotNumber:** `Optional<String>` 
    
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

<details><summary><code>client.inventory.stockTake(request) -> StockTakeInventoryResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.inventory().stockTake(
    StockTakeInventoryRequest
        .builder()
        .warehouseId("warehouseId")
        .date("2026-07-01")
        .lines(
            Arrays.asList(
                StockTakeInventoryRequestLinesItem
                    .builder()
                    .countedQty("121.0000")
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

**lines:** `List<StockTakeInventoryRequestLinesItem>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.inventory.stockLevels(request) -> StockLevelsInventoryResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.inventory().stockLevels(
    StockLevelsInventoryRequest
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

<details><summary><code>client.inventory.stockMovementsList(request) -> StockMovementsListInventoryResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.inventory().stockMovementsList(
    StockMovementsListInventoryRequest
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

**sort:** `Optional<List<StockMovementsListInventoryRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<StockMovementsListInventoryRequestFilterItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `Optional<List<String>>` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.inventory.lotsList(request) -> LotsListInventoryResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.inventory().lotsList(
    LotsListInventoryRequest
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

**sort:** `Optional<List<LotsListInventoryRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<LotsListInventoryRequestFilterItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `Optional<List<String>>` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.inventory.lotsGet(request) -> LotsGetInventoryResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.inventory().lotsGet(
    LotsGetInventoryRequest
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

<details><summary><code>client.inventory.lotsUpdate(request) -> LotsUpdateInventoryResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.inventory().lotsUpdate(
    LotsUpdateInventoryRequest
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

**expiryDate:** `Optional<String>` 
    
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

<details><summary><code>client.inventory.landedCostsCreate(request) -> LandedCostsCreateInventoryResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.inventory().landedCostsCreate(
    LandedCostsCreateInventoryRequest
        .builder()
        .date("2026-07-01")
        .amount("121.000000")
        .build()
);
```
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

**amount:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**method:** `Optional<LandedCostsCreateInventoryRequestMethod>` 
    
</dd>
</dl>

<dl>
<dd>

**goodsReceiptId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**movementIds:** `Optional<List<String>>` 
    
</dd>
</dl>

<dl>
<dd>

**sourceInvoiceId:** `Optional<String>` 
    
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

<details><summary><code>client.inventory.landedCostsGet(request) -> LandedCostsGetInventoryResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.inventory().landedCostsGet(
    LandedCostsGetInventoryRequest
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

<details><summary><code>client.inventory.landedCostsList(request) -> LandedCostsListInventoryResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.inventory().landedCostsList(
    LandedCostsListInventoryRequest
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

**sort:** `Optional<List<LandedCostsListInventoryRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<LandedCostsListInventoryRequestFilterItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `Optional<List<String>>` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.inventory.reorderRulesCreate(request) -> ReorderRulesCreateInventoryResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.inventory().reorderRulesCreate(
    ReorderRulesCreateInventoryRequest
        .builder()
        .itemId("itemId")
        .minQty("121.0000")
        .build()
);
```
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

**warehouseId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**minQty:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**reorderQty:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**isActive:** `Optional<Boolean>` 
    
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

<details><summary><code>client.inventory.reorderRulesUpdate(request) -> ReorderRulesUpdateInventoryResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.inventory().reorderRulesUpdate(
    ReorderRulesUpdateInventoryRequest
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

**minQty:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**reorderQty:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**isActive:** `Optional<Boolean>` 
    
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

<details><summary><code>client.inventory.reorderRulesDelete(request) -> ReorderRulesDeleteInventoryResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.inventory().reorderRulesDelete(
    ReorderRulesDeleteInventoryRequest
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

<details><summary><code>client.inventory.reorderRulesList(request) -> ReorderRulesListInventoryResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.inventory().reorderRulesList(
    ReorderRulesListInventoryRequest
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

**sort:** `Optional<List<ReorderRulesListInventoryRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<ReorderRulesListInventoryRequestFilterItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `Optional<List<String>>` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.inventory.reorderRulesCheck(request) -> ReorderRulesCheckInventoryResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.inventory().reorderRulesCheck(
    ReorderRulesCheckInventoryRequest
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

## production
<details><summary><code>client.production.workCentersCreate(request) -> WorkCentersCreateProductionResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.production().workCentersCreate(
    WorkCentersCreateProductionRequest
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

**costPerHour:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**costAccountCode:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**maintenanceIntervalDays:** `Optional<Long>` 
    
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

<details><summary><code>client.production.workCentersUpdate(request) -> WorkCentersUpdateProductionResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.production().workCentersUpdate(
    WorkCentersUpdateProductionRequest
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

**costPerHour:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**costAccountCode:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**maintenanceIntervalDays:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**isActive:** `Optional<Boolean>` 
    
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

<details><summary><code>client.production.workCentersList(request) -> WorkCentersListProductionResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.production().workCentersList(
    WorkCentersListProductionRequest
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

**sort:** `Optional<List<WorkCentersListProductionRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<WorkCentersListProductionRequestFilterItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `Optional<List<String>>` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.production.routingsCreate(request) -> RoutingsCreateProductionResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.production().routingsCreate(
    RoutingsCreateProductionRequest
        .builder()
        .code("code")
        .name("name")
        .operations(
            Arrays.asList(
                RoutingsCreateProductionRequestOperationsItem
                    .builder()
                    .sequence(1000000L)
                    .name("name")
                    .workCenterId("workCenterId")
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

**notes:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**operations:** `List<RoutingsCreateProductionRequestOperationsItem>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.production.routingsGet(request) -> RoutingsGetProductionResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.production().routingsGet(
    RoutingsGetProductionRequest
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

<details><summary><code>client.production.routingsList(request) -> RoutingsListProductionResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.production().routingsList(
    RoutingsListProductionRequest
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

**sort:** `Optional<List<RoutingsListProductionRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<RoutingsListProductionRequestFilterItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `Optional<List<String>>` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.production.maintenanceCreate(request) -> MaintenanceCreateProductionResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.production().maintenanceCreate(
    MaintenanceCreateProductionRequest
        .builder()
        .workCenterId("workCenterId")
        .type(MaintenanceCreateProductionRequestType.PREVENTIVE)
        .plannedDate("2026-07-01")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**workCenterId:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**type:** `MaintenanceCreateProductionRequestType` 
    
</dd>
</dl>

<dl>
<dd>

**plannedDate:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**description:** `Optional<String>` 
    
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

<details><summary><code>client.production.maintenanceComplete(request) -> MaintenanceCompleteProductionResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.production().maintenanceComplete(
    MaintenanceCompleteProductionRequest
        .builder()
        .id("id")
        .completedDate("2026-07-01")
        .build()
);
```
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

**completedDate:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**downtimeHours:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**cost:** `Optional<String>` 
    
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

<details><summary><code>client.production.maintenanceCancel(request) -> MaintenanceCancelProductionResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.production().maintenanceCancel(
    MaintenanceCancelProductionRequest
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

<details><summary><code>client.production.maintenanceList(request) -> MaintenanceListProductionResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.production().maintenanceList(
    MaintenanceListProductionRequest
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

**sort:** `Optional<List<MaintenanceListProductionRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<MaintenanceListProductionRequestFilterItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `Optional<List<String>>` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.production.bomsCreate(request) -> BomsCreateProductionResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.production().bomsCreate(
    BomsCreateProductionRequest
        .builder()
        .code("code")
        .name("name")
        .finishedItemId("finishedItemId")
        .lines(
            Arrays.asList(
                BomsCreateProductionRequestLinesItem
                    .builder()
                    .componentItemId("componentItemId")
                    .quantity("121.0000")
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

**routingId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**lines:** `List<BomsCreateProductionRequestLinesItem>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.production.bomsGet(request) -> BomsGetProductionResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.production().bomsGet(
    BomsGetProductionRequest
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

<details><summary><code>client.production.bomsList(request) -> BomsListProductionResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.production().bomsList(
    BomsListProductionRequest
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

**sort:** `Optional<List<BomsListProductionRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<BomsListProductionRequestFilterItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `Optional<List<String>>` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.production.ordersCreate(request) -> OrdersCreateProductionResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.production().ordersCreate(
    OrdersCreateProductionRequest
        .builder()
        .bomId("bomId")
        .warehouseId("warehouseId")
        .quantity("121.0000")
        .date("2026-07-01")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**type:** `Optional<OrdersCreateProductionRequestType>` 
    
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

**routingId:** `Optional<String>` 
    
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

<details><summary><code>client.production.ordersRecordOperation(request) -> OrdersRecordOperationProductionResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.production().ordersRecordOperation(
    OrdersRecordOperationProductionRequest
        .builder()
        .id("id")
        .actualMinutes("121.00")
        .build()
);
```
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

**actualMinutes:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.production.qualityChecksAdd(request) -> QualityChecksAddProductionResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.production().qualityChecksAdd(
    QualityChecksAddProductionRequest
        .builder()
        .orderId("orderId")
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

**orderId:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**name:** `String` 
    
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

<details><summary><code>client.production.qualityChecksRecord(request) -> QualityChecksRecordProductionResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.production().qualityChecksRecord(
    QualityChecksRecordProductionRequest
        .builder()
        .id("id")
        .result(QualityChecksRecordProductionRequestResult.PASSED)
        .build()
);
```
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

**result:** `QualityChecksRecordProductionRequestResult` 
    
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

<details><summary><code>client.production.qualityChecksList(request) -> QualityChecksListProductionResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.production().qualityChecksList(
    QualityChecksListProductionRequest
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

**sort:** `Optional<List<QualityChecksListProductionRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<QualityChecksListProductionRequestFilterItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `Optional<List<String>>` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.production.ordersComplete(request) -> OrdersCompleteProductionResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.production().ordersComplete(
    OrdersCompleteProductionRequest
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

**scrappedQuantity:** `Optional<String>` 
    
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

<details><summary><code>client.production.ordersGet(request) -> OrdersGetProductionResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.production().ordersGet(
    OrdersGetProductionRequest
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

<details><summary><code>client.production.ordersList(request) -> OrdersListProductionResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.production().ordersList(
    OrdersListProductionRequest
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

**sort:** `Optional<List<OrdersListProductionRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<OrdersListProductionRequestFilterItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `Optional<List<String>>` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## ecommerce
<details><summary><code>client.ecommerce.ordersCreate(request) -> OrdersCreateEcommerceResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.ecommerce().ordersCreate(
    OrdersCreateEcommerceRequest
        .builder()
        .lines(
            Arrays.asList(
                OrdersCreateEcommerceRequestLinesItem
                    .builder()
                    .description("description")
                    .quantity("121.0000")
                    .unitPriceExclVat("121.0000")
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

**partner:** `Optional<OrdersCreateEcommerceRequestPartner>` 
    
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

**lines:** `List<OrdersCreateEcommerceRequestLinesItem>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.ecommerce.ordersGet(request) -> OrdersGetEcommerceResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.ecommerce().ordersGet(
    OrdersGetEcommerceRequest
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

<details><summary><code>client.ecommerce.ordersList(request) -> OrdersListEcommerceResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.ecommerce().ordersList(
    OrdersListEcommerceRequest
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

**sort:** `Optional<List<OrdersListEcommerceRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<OrdersListEcommerceRequestFilterItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `Optional<List<String>>` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.ecommerce.ordersReserve(request) -> OrdersReserveEcommerceResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.ecommerce().ordersReserve(
    OrdersReserveEcommerceRequest
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

<details><summary><code>client.ecommerce.ordersFulfill(request) -> OrdersFulfillEcommerceResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.ecommerce().ordersFulfill(
    OrdersFulfillEcommerceRequest
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

<details><summary><code>client.ecommerce.ordersCancel(request) -> OrdersCancelEcommerceResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.ecommerce().ordersCancel(
    OrdersCancelEcommerceRequest
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

<details><summary><code>client.ecommerce.productsList(request) -> ProductsListEcommerceResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.ecommerce().productsList(
    ProductsListEcommerceRequest
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

<details><summary><code>client.ecommerce.stockList(request) -> StockListEcommerceResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.ecommerce().stockList(
    StockListEcommerceRequest
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

## cash
<details><summary><code>client.cash.ordersCreate(request) -> OrdersCreateCashResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.cash().ordersCreate(
    OrdersCreateCashRequest
        .builder()
        .type(OrdersCreateCashRequestType.RECEIPT)
        .date("2026-07-01")
        .amount("121.0000")
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

**type:** `OrdersCreateCashRequestType` 
    
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

<details><summary><code>client.cash.ordersGet(request) -> OrdersGetCashResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.cash().ordersGet(
    OrdersGetCashRequest
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

<details><summary><code>client.cash.ordersList(request) -> OrdersListCashResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.cash().ordersList(
    OrdersListCashRequest
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

**sort:** `Optional<List<OrdersListCashRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<OrdersListCashRequestFilterItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `Optional<List<String>>` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.cash.balance(request) -> BalanceCashResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.cash().balance(
    BalanceCashRequest
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

<details><summary><code>client.cash.advanceHoldersBalances(request) -> AdvanceHoldersBalancesCashResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.cash().advanceHoldersBalances(
    AdvanceHoldersBalancesCashRequest
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

## projects
<details><summary><code>client.projects.create(request) -> CreateProjectsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.projects().create(
    CreateProjectsRequest
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

**partnerId:** `Optional<String>` 
    
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

<details><summary><code>client.projects.update(request) -> UpdateProjectsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.projects().update(
    UpdateProjectsRequest
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

**partnerId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**status:** `Optional<UpdateProjectsRequestStatus>` 
    
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

<details><summary><code>client.projects.get(request) -> GetProjectsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.projects().get(
    GetProjectsRequest
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

<details><summary><code>client.projects.list(request) -> ListProjectsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.projects().list(
    ListProjectsRequest
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

**sort:** `Optional<List<ListProjectsRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<ListProjectsRequestFilterItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `Optional<List<String>>` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.projects.timeEntriesCreate(request) -> TimeEntriesCreateProjectsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.projects().timeEntriesCreate(
    TimeEntriesCreateProjectsRequest
        .builder()
        .projectId("projectId")
        .date("2026-07-01")
        .hours("121.00")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**projectId:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**employeeId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**date:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**hours:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**description:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**billable:** `Optional<Boolean>` 
    
</dd>
</dl>

<dl>
<dd>

**hourlyRate:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.projects.timeEntriesUpdate(request) -> TimeEntriesUpdateProjectsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.projects().timeEntriesUpdate(
    TimeEntriesUpdateProjectsRequest
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

**hours:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**description:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**billable:** `Optional<Boolean>` 
    
</dd>
</dl>

<dl>
<dd>

**hourlyRate:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.projects.timeEntriesDelete(request) -> TimeEntriesDeleteProjectsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.projects().timeEntriesDelete(
    TimeEntriesDeleteProjectsRequest
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

<details><summary><code>client.projects.timeEntriesList(request) -> TimeEntriesListProjectsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.projects().timeEntriesList(
    TimeEntriesListProjectsRequest
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

**sort:** `Optional<List<TimeEntriesListProjectsRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<TimeEntriesListProjectsRequestFilterItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `Optional<List<String>>` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.projects.timeEntriesBill(request) -> TimeEntriesBillProjectsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.projects().timeEntriesBill(
    TimeEntriesBillProjectsRequest
        .builder()
        .projectId("projectId")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**projectId:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**partnerId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**dateFrom:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**dateTo:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**itemId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**hourlyRate:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**vatRatePercent:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**vatClassifierCode:** `Optional<String>` 
    
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

**groupBy:** `Optional<TimeEntriesBillProjectsRequestGroupBy>` 
    
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

<details><summary><code>client.projects.report(request) -> ReportProjectsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.projects().report(
    ReportProjectsRequest
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

**projectId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**dateFrom:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**dateTo:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## transport
<details><summary><code>client.transport.waybillsCreate(request) -> WaybillsCreateTransportResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.transport().waybillsCreate(
    WaybillsCreateTransportRequest
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

**lines:** `Optional<List<WaybillsCreateTransportRequestLinesItem>>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.transport.waybillsUpdate(request) -> WaybillsUpdateTransportResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.transport().waybillsUpdate(
    WaybillsUpdateTransportRequest
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

**lines:** `Optional<List<WaybillsUpdateTransportRequestLinesItem>>` 
    
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

<details><summary><code>client.transport.waybillsIssue(request) -> WaybillsIssueTransportResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.transport().waybillsIssue(
    WaybillsIssueTransportRequest
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

<details><summary><code>client.transport.waybillsCancel(request) -> WaybillsCancelTransportResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.transport().waybillsCancel(
    WaybillsCancelTransportRequest
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

<details><summary><code>client.transport.waybillsGet(request) -> WaybillsGetTransportResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.transport().waybillsGet(
    WaybillsGetTransportRequest
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

<details><summary><code>client.transport.waybillsList(request) -> WaybillsListTransportResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.transport().waybillsList(
    WaybillsListTransportRequest
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

**sort:** `Optional<List<WaybillsListTransportRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<WaybillsListTransportRequestFilterItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `Optional<List<String>>` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## pos
<details><summary><code>client.pos.devicesCreate(request) -> DevicesCreatePosResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.pos().devicesCreate(
    DevicesCreatePosRequest
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

<details><summary><code>client.pos.devicesUpdate(request) -> DevicesUpdatePosResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.pos().devicesUpdate(
    DevicesUpdatePosRequest
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

<details><summary><code>client.pos.devicesList(request) -> DevicesListPosResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.pos().devicesList(
    DevicesListPosRequest
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

**sort:** `Optional<List<DevicesListPosRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<DevicesListPosRequestFilterItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `Optional<List<String>>` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.pos.reportsCreate(request) -> ReportsCreatePosResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.pos().reportsCreate(
    ReportsCreatePosRequest
        .builder()
        .reportNumber("reportNumber")
        .date("2026-07-01")
        .vatLines(
            Arrays.asList(
                ReportsCreatePosRequestVatLinesItem
                    .builder()
                    .vatRatePercent("121.00")
                    .netAmount("121.0000")
                    .vatAmount("121.0000")
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

**vatLines:** `List<ReportsCreatePosRequestVatLinesItem>` 
    
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

**itemLines:** `Optional<List<ReportsCreatePosRequestItemLinesItem>>` 
    
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

<details><summary><code>client.pos.reportsGet(request) -> ReportsGetPosResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.pos().reportsGet(
    ReportsGetPosRequest
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

<details><summary><code>client.pos.reportsList(request) -> ReportsListPosResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.pos().reportsList(
    ReportsListPosRequest
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

**sort:** `Optional<List<ReportsListPosRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<ReportsListPosRequestFilterItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `Optional<List<String>>` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## calendar
<details><summary><code>client.calendar.list(request) -> ListCalendarResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.calendar().list(
    ListCalendarRequest
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

**from:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**to:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**includeDone:** `Optional<Boolean>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.calendar.get(request) -> GetCalendarResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.calendar().get(
    GetCalendarRequest
        .builder()
        .key("key")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**key:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.calendar.submit(request) -> SubmitCalendarResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

With amend: true the return is filed again as a correction of the one already submitted or accepted for the period; only returns whose format has a correction mark accept it.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.calendar().submit(
    SubmitCalendarRequest
        .builder()
        .key("key")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**key:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**amend:** `Optional<Boolean>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.calendar.download(request) -> DownloadCalendarResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Builds the file of a deadline whose format Nordlet produces but whose administration takes it only through the company's own account or program. Nothing is sent and no filing is recorded.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.calendar().download(
    DownloadCalendarRequest
        .builder()
        .key("key")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**key:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.calendar.create(request) -> CreateCalendarResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.calendar().create(
    CreateCalendarRequest
        .builder()
        .title("title")
        .dueDate("2026-07-01")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**title:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**dueDate:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**done:** `Optional<Boolean>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.calendar.update(request) -> UpdateCalendarResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.calendar().update(
    UpdateCalendarRequest
        .builder()
        .key("key")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**key:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**title:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**dueDate:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**notes:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**done:** `Optional<Boolean>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.calendar.delete(request) -> DeleteCalendarResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.calendar().delete(
    DeleteCalendarRequest
        .builder()
        .key("key")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**key:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## audit
<details><summary><code>client.audit.list(request) -> ListAuditResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.audit().list(
    ListAuditRequest
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

**sort:** `Optional<List<ListAuditRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<ListAuditRequestFilterItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `Optional<List<String>>` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## webhooks
<details><summary><code>client.webhooks.subscriptionsCreate(request) -> SubscriptionsCreateWebhooksResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.webhooks().subscriptionsCreate(
    SubscriptionsCreateWebhooksRequest
        .builder()
        .url("url")
        .events(
            Arrays.asList(SubscriptionsCreateWebhooksRequestEventsItem.AGREEMENT_INVOICE_GENERATED)
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

**events:** `List<SubscriptionsCreateWebhooksRequestEventsItem>` 
    
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

<details><summary><code>client.webhooks.subscriptionsList(request) -> SubscriptionsListWebhooksResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.webhooks().subscriptionsList(
    SubscriptionsListWebhooksRequest
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

**sort:** `Optional<List<SubscriptionsListWebhooksRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<SubscriptionsListWebhooksRequestFilterItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `Optional<List<String>>` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.webhooks.subscriptionsUpdate(request) -> SubscriptionsUpdateWebhooksResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.webhooks().subscriptionsUpdate(
    SubscriptionsUpdateWebhooksRequest
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

**events:** `Optional<List<SubscriptionsUpdateWebhooksRequestEventsItem>>` 
    
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

<details><summary><code>client.webhooks.subscriptionsDelete(request) -> SubscriptionsDeleteWebhooksResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.webhooks().subscriptionsDelete(
    SubscriptionsDeleteWebhooksRequest
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

<details><summary><code>client.webhooks.deliveriesList(request) -> DeliveriesListWebhooksResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.webhooks().deliveriesList(
    DeliveriesListWebhooksRequest
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

**sort:** `Optional<List<DeliveriesListWebhooksRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<DeliveriesListWebhooksRequestFilterItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `Optional<List<String>>` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.webhooks.deliveriesRedeliver(request) -> DeliveriesRedeliverWebhooksResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.webhooks().deliveriesRedeliver(
    DeliveriesRedeliverWebhooksRequest
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

## bank
<details><summary><code>client.bank.accountsCreate(request) -> AccountsCreateBankResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.bank().accountsCreate(
    AccountsCreateBankRequest
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

<dl>
<dd>

**documentRef:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.bank.accountsList(request) -> AccountsListBankResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.bank().accountsList(
    AccountsListBankRequest
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

**sort:** `Optional<List<AccountsListBankRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<AccountsListBankRequestFilterItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `Optional<List<String>>` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.bank.accountsUpdate(request) -> AccountsUpdateBankResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.bank().accountsUpdate(
    AccountsUpdateBankRequest
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

<details><summary><code>client.bank.transactionsImport(request) -> TransactionsImportBankResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.bank().transactionsImport(
    TransactionsImportBankRequest
        .builder()
        .bankAccountId("bankAccountId")
        .transactions(
            Arrays.asList(
                TransactionsImportBankRequestTransactionsItem
                    .builder()
                    .date("2026-07-01")
                    .amount("-121.0000")
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

**transactions:** `List<TransactionsImportBankRequestTransactionsItem>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.bank.statementsImport(request) -> StatementsImportBankResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.bank().statementsImport(
    StatementsImportBankRequest
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

**templateId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**format:** `Optional<StatementsImportBankRequestFormat>` 
    
</dd>
</dl>

<dl>
<dd>

**content:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**transfersCsv:** `Optional<String>` — Stripe transfers export (plain CSV or base64) used to post lender payouts and commissions
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.bank.transactionsList(request) -> TransactionsListBankResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.bank().transactionsList(
    TransactionsListBankRequest
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

**sort:** `Optional<List<TransactionsListBankRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<TransactionsListBankRequestFilterItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `Optional<List<String>>` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.bank.transactionsMatch(request) -> TransactionsMatchBankResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.bank().transactionsMatch(
    TransactionsMatchBankRequest
        .builder()
        .transactionId("transactionId")
        .documentType(TransactionsMatchBankRequestDocumentType.SALE_INVOICE)
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

**documentType:** `TransactionsMatchBankRequestDocumentType` 
    
</dd>
</dl>

<dl>
<dd>

**documentId:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**invoiceAmount:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.bank.transactionsUnmatch(request) -> TransactionsUnmatchBankResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Undo a match. A payment matched to an invoice, or a line posted by an import template, gets a reversing journal transaction dated date (default: today) and the invoice paid amount and payment status are restored; a line linked to a payment-provider settlement is only unlinked. The line returns to status new.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.bank().transactionsUnmatch(
    TransactionsUnmatchBankRequest
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

**date:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.bank.transactionsRecord(request) -> TransactionsRecordBankResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.bank().transactionsRecord(
    TransactionsRecordBankRequest
        .builder()
        .bankAccountId("bankAccountId")
        .date("2026-07-01")
        .amount("121.0000")
        .documentType(TransactionsRecordBankRequestDocumentType.SALE_INVOICE)
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

**bankAccountId:** `String` 
    
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

**description:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**documentType:** `TransactionsRecordBankRequestDocumentType` 
    
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

<details><summary><code>client.bank.paymentsExport(request) -> PaymentsExportBankResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.bank().paymentsExport(
    PaymentsExportBankRequest
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

<details><summary><code>client.bank.importTemplatesCreate(request) -> ImportTemplatesCreateBankResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.bank().importTemplatesCreate(
    ImportTemplatesCreateBankRequest
        .builder()
        .name("name")
        .type(ImportTemplatesCreateBankRequestType.STRIPE)
        .build()
);
```
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

**type:** `ImportTemplatesCreateBankRequestType` 
    
</dd>
</dl>

<dl>
<dd>

**fields:** `Optional<List<ImportTemplatesCreateBankRequestFieldsItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**metaFields:** `Optional<List<String>>` 
    
</dd>
</dl>

<dl>
<dd>

**invoiceMetaField:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**invoiceVatRatePercent:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**companyMetaField:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**invoiceItemId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**advanceInvoices:** `Optional<Boolean>` 
    
</dd>
</dl>

<dl>
<dd>

**authorizationOperationTypeId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**payoutOperationTypeId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**commissionOperationTypeId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**lenderMetaField:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**partialRefundLabel:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**fullRefundLabel:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.bank.importTemplatesUpdate(request) -> ImportTemplatesUpdateBankResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.bank().importTemplatesUpdate(
    ImportTemplatesUpdateBankRequest
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

**type:** `Optional<ImportTemplatesUpdateBankRequestType>` 
    
</dd>
</dl>

<dl>
<dd>

**fields:** `Optional<List<ImportTemplatesUpdateBankRequestFieldsItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**metaFields:** `Optional<List<String>>` 
    
</dd>
</dl>

<dl>
<dd>

**invoiceMetaField:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**invoiceVatRatePercent:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**companyMetaField:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**invoiceItemId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**advanceInvoices:** `Optional<Boolean>` 
    
</dd>
</dl>

<dl>
<dd>

**authorizationOperationTypeId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**payoutOperationTypeId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**commissionOperationTypeId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**lenderMetaField:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**partialRefundLabel:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**fullRefundLabel:** `Optional<String>` 
    
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

<details><summary><code>client.bank.importTemplatesDelete(request) -> ImportTemplatesDeleteBankResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.bank().importTemplatesDelete(
    ImportTemplatesDeleteBankRequest
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

<details><summary><code>client.bank.importTemplatesGet(request) -> ImportTemplatesGetBankResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.bank().importTemplatesGet(
    ImportTemplatesGetBankRequest
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

<details><summary><code>client.bank.importTemplatesList(request) -> ImportTemplatesListBankResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.bank().importTemplatesList(
    ImportTemplatesListBankRequest
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

**sort:** `Optional<List<ImportTemplatesListBankRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<ImportTemplatesListBankRequestFilterItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `Optional<List<String>>` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.bank.matchRulesCreate(request) -> MatchRulesCreateBankResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.bank().matchRulesCreate(
    MatchRulesCreateBankRequest
        .builder()
        .name("name")
        .pattern("pattern")
        .build()
);
```
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

**provider:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**pattern:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**payoutIdPrefix:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**bankAccountId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**dateWindowDays:** `Optional<Long>` 
    
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

<details><summary><code>client.bank.matchRulesUpdate(request) -> MatchRulesUpdateBankResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.bank().matchRulesUpdate(
    MatchRulesUpdateBankRequest
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

**provider:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**pattern:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**payoutIdPrefix:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**bankAccountId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**dateWindowDays:** `Optional<Long>` 
    
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

<details><summary><code>client.bank.matchRulesDelete(request) -> MatchRulesDeleteBankResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.bank().matchRulesDelete(
    MatchRulesDeleteBankRequest
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

<details><summary><code>client.bank.matchRulesList(request) -> MatchRulesListBankResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.bank().matchRulesList(
    MatchRulesListBankRequest
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

<details><summary><code>client.bank.mandatesCreate(request) -> MandatesCreateBankResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.bank().mandatesCreate(
    MandatesCreateBankRequest
        .builder()
        .partnerId("partnerId")
        .iban("iban")
        .signatureDate("2026-07-01")
        .build()
);
```
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

**iban:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**bic:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**scheme:** `Optional<MandatesCreateBankRequestScheme>` 
    
</dd>
</dl>

<dl>
<dd>

**sequenceType:** `Optional<MandatesCreateBankRequestSequenceType>` 
    
</dd>
</dl>

<dl>
<dd>

**signatureDate:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**reference:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**debtorName:** `Optional<String>` 
    
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

<details><summary><code>client.bank.mandatesUpdate(request) -> MandatesUpdateBankResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.bank().mandatesUpdate(
    MandatesUpdateBankRequest
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

**bic:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**debtorName:** `Optional<String>` 
    
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

<details><summary><code>client.bank.mandatesCancel(request) -> MandatesCancelBankResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.bank().mandatesCancel(
    MandatesCancelBankRequest
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

<details><summary><code>client.bank.mandatesGet(request) -> MandatesGetBankResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.bank().mandatesGet(
    MandatesGetBankRequest
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

<details><summary><code>client.bank.mandatesList(request) -> MandatesListBankResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.bank().mandatesList(
    MandatesListBankRequest
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

**sort:** `Optional<List<MandatesListBankRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<MandatesListBankRequestFilterItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `Optional<List<String>>` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.bank.directDebitsExport(request) -> DirectDebitsExportBankResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.bank().directDebitsExport(
    DirectDebitsExportBankRequest
        .builder()
        .bankAccountId("bankAccountId")
        .saleInvoiceIds(
            Arrays.asList("saleInvoiceIds")
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

**saleInvoiceIds:** `List<String>` 
    
</dd>
</dl>

<dl>
<dd>

**collectionDate:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.bank.transactionsSuggestMatches(request) -> TransactionsSuggestMatchesBankResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.bank().transactionsSuggestMatches(
    TransactionsSuggestMatchesBankRequest
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

<details><summary><code>client.bank.settlementsImport(request) -> SettlementsImportBankResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.bank().settlementsImport(
    SettlementsImportBankRequest
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

**provider:** `Optional<SettlementsImportBankRequestProvider>` 
    
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

<details><summary><code>client.bank.settlementsList(request) -> SettlementsListBankResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.bank().settlementsList(
    SettlementsListBankRequest
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

**sort:** `Optional<List<SettlementsListBankRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<SettlementsListBankRequestFilterItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `Optional<List<String>>` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.bank.settlementsGet(request) -> SettlementsGetBankResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.bank().settlementsGet(
    SettlementsGetBankRequest
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

<details><summary><code>client.bank.settlementsMatch(request) -> SettlementsMatchBankResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.bank().settlementsMatch(
    SettlementsMatchBankRequest
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

<details><summary><code>client.bank.settlementsCommission(request) -> SettlementsCommissionBankResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

A line with its own rate or amount is split with that value when the batch is posted. A line without one falls back to the commissionPercent given to the posting call, and without that the amount goes to the suspense account. Send both fields as null to clear the line back to the fallback.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.bank().settlementsCommission(
    SettlementsCommissionBankRequest
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

**commissionPercent:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**commissionAmount:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.bank.settlementsLink(request) -> SettlementsLinkBankResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Attach the incoming bank-statement line that carries this payout to the settlement batch.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.bank().settlementsLink(
    SettlementsLinkBankRequest
        .builder()
        .id("id")
        .bankTransactionId("bankTransactionId")
        .build()
);
```
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

**bankTransactionId:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.bank.settlementsUnlink(request) -> SettlementsUnlinkBankResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Detach the bank-statement line from the settlement batch and return the line to unmatched.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.bank().settlementsUnlink(
    SettlementsUnlinkBankRequest
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

<details><summary><code>client.bank.settlementsPost(request) -> SettlementsPostBankResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.bank().settlementsPost(
    SettlementsPostBankRequest
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

<details><summary><code>client.bank.feedsBanksList(request) -> FeedsBanksListBankResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.bank().feedsBanksList(
    FeedsBanksListBankRequest
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

<details><summary><code>client.bank.feedsConnectionsStart(request) -> FeedsConnectionsStartBankResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.bank().feedsConnectionsStart(
    FeedsConnectionsStartBankRequest
        .builder()
        .aspspName("aspspName")
        .aspspCountry("aspspCountry")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**aspspName:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**aspspCountry:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**psuType:** `Optional<FeedsConnectionsStartBankRequestPsuType>` 
    
</dd>
</dl>

<dl>
<dd>

**redirectUrl:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**validForDays:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**language:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.bank.feedsConnectionsComplete(request) -> FeedsConnectionsCompleteBankResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.bank().feedsConnectionsComplete(
    FeedsConnectionsCompleteBankRequest
        .builder()
        .reference("reference")
        .code("code")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**reference:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**code:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.bank.feedsConnectionsGet(request) -> FeedsConnectionsGetBankResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.bank().feedsConnectionsGet(
    FeedsConnectionsGetBankRequest
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

<details><summary><code>client.bank.feedsConnectionsList(request) -> FeedsConnectionsListBankResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.bank().feedsConnectionsList(
    FeedsConnectionsListBankRequest
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

**sort:** `Optional<List<FeedsConnectionsListBankRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<FeedsConnectionsListBankRequestFilterItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `Optional<List<String>>` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.bank.feedsConnectionsDelete(request) -> FeedsConnectionsDeleteBankResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.bank().feedsConnectionsDelete(
    FeedsConnectionsDeleteBankRequest
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

<details><summary><code>client.bank.feedsAccountsLink(request) -> FeedsAccountsLinkBankResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.bank().feedsAccountsLink(
    FeedsAccountsLinkBankRequest
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

**bankAccountId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**createBankAccount:** `Optional<FeedsAccountsLinkBankRequestCreateBankAccount>` 
    
</dd>
</dl>

<dl>
<dd>

**syncFrom:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.bank.feedsAccountsConfigure(request) -> FeedsAccountsConfigureBankResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.bank().feedsAccountsConfigure(
    FeedsAccountsConfigureBankRequest
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

**importTemplateId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**syncSchedule:** `Optional<FeedsAccountsConfigureBankRequestSyncSchedule>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.bank.feedsSync(request) -> FeedsSyncBankResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.bank().feedsSync(
    FeedsSyncBankRequest
        .builder()
        .connectionId("connectionId")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**connectionId:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**feedAccountId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**dateFrom:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**dateTo:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## files
<details><summary><code>client.files.upload(request) -> UploadFilesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.files().upload(
    UploadFilesRequest
        .builder()
        .entity("entity")
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

**entityId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**fileName:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**mimeType:** `String` — Stored as the bare media type; only PNG, JPEG, GIF, WebP and PDF files are shown in the browser, every other type is downloaded
    
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

<details><summary><code>client.files.get(request) -> GetFilesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.files().get(
    GetFilesRequest
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

<details><summary><code>client.files.list(request) -> ListFilesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.files().list(
    ListFilesRequest
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

**sort:** `Optional<List<ListFilesRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<ListFilesRequestFilterItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `Optional<List<String>>` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.files.delete(request) -> DeleteFilesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.files().delete(
    DeleteFilesRequest
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

## reports
<details><summary><code>client.reports.trialBalance(request) -> TrialBalanceReportsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.reports().trialBalance(
    TrialBalanceReportsRequest
        .builder()
        .fromDate("2026-07-01")
        .toDate("2026-07-01")
        .build()
);
```
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

<details><summary><code>client.reports.sizeCategory(request) -> SizeCategoryReportsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.reports().sizeCategory(
    SizeCategoryReportsRequest
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

<details><summary><code>client.reports.financialStatements(request) -> FinancialStatementsReportsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.reports().financialStatements(
    FinancialStatementsReportsRequest
        .builder()
        .fromDate("2026-07-01")
        .toDate("2026-07-01")
        .build()
);
```
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

**category:** `Optional<FinancialStatementsReportsRequestCategory>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.reports.generalJournal(request) -> GeneralJournalReportsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.reports().generalJournal(
    GeneralJournalReportsRequest
        .builder()
        .fromDate("2026-07-01")
        .toDate("2026-07-01")
        .build()
);
```
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

<details><summary><code>client.reports.glDetail(request) -> GlDetailReportsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.reports().glDetail(
    GlDetailReportsRequest
        .builder()
        .accountCode("accountCode")
        .fromDate("2026-07-01")
        .toDate("2026-07-01")
        .build()
);
```
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

<details><summary><code>client.reports.partnerBalances(request) -> PartnerBalancesReportsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.reports().partnerBalances(
    PartnerBalancesReportsRequest
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

<details><summary><code>client.reports.debtAging(request) -> DebtAgingReportsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.reports().debtAging(
    DebtAgingReportsRequest
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

**side:** `Optional<DebtAgingReportsRequestSide>` 
    
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

<details><summary><code>client.reports.monthlySummary(request) -> MonthlySummaryReportsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.reports().monthlySummary(
    MonthlySummaryReportsRequest
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

<details><summary><code>client.reports.stockBalance(request) -> StockBalanceReportsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.reports().stockBalance(
    StockBalanceReportsRequest
        .builder()
        .asOf("2026-07-01")
        .build()
);
```
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

<details><summary><code>client.reports.stockMovement(request) -> StockMovementReportsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.reports().stockMovement(
    StockMovementReportsRequest
        .builder()
        .fromDate("2026-07-01")
        .toDate("2026-07-01")
        .build()
);
```
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

<details><summary><code>client.reports.vatSummary(request) -> VatSummaryReportsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.reports().vatSummary(
    VatSummaryReportsRequest
        .builder()
        .fromDate("2026-07-01")
        .toDate("2026-07-01")
        .build()
);
```
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

**side:** `Optional<VatSummaryReportsRequestSide>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.reports.cashFlow(request) -> CashFlowReportsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.reports().cashFlow(
    CashFlowReportsRequest
        .builder()
        .fromDate("2026-07-01")
        .toDate("2026-07-01")
        .build()
);
```
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

<details><summary><code>client.reports.stockAging(request) -> StockAgingReportsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.reports().stockAging(
    StockAgingReportsRequest
        .builder()
        .asOf("2026-07-01")
        .build()
);
```
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

<details><summary><code>client.reports.stockShortage(request) -> StockShortageReportsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.reports().stockShortage(
    StockShortageReportsRequest
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

<details><summary><code>client.reports.sie(request) -> SieReportsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Export the ledger of one financial year as an SIE file (the Swedish standard accounting interchange format, specification 4B). The file carries the chart of accounts, the opening and closing balance of every balance sheet account and the turnover of every result account for the year and the year before it, and, when asked for, every posted voucher of the year with its lines. Cost centres travel as dimension 1 and projects as dimension 6. Services that build a Swedish annual report read this file.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.reports().sie(
    SieReportsRequest
        .builder()
        .fromDate("2026-07-01")
        .toDate("2026-07-01")
        .build()
);
```
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

**includeTransactions:** `Optional<Boolean>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.reports.datev(request) -> DatevReportsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Export the posted ledger of a period as a DATEV Buchungsstapel file (DATEV format, category 21, version 700). Every transaction becomes one or more bookings of an amount between an account and a contra account; a transaction with more than two lines is split into pairs whose totals match it. The file is semicolon separated and written in the Windows-1252 character set DATEV expects.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.reports().datev(
    DatevReportsRequest
        .builder()
        .fromDate("2026-07-01")
        .toDate("2026-07-01")
        .build()
);
```
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

**consultantNumber:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**clientNumber:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.reports.fec(request) -> FecReportsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Export the posted ledger of a period as a French FEC file (fichier des écritures comptables, order of 29 July 2013). One line per journal entry line, with the eighteen fields the order names, in their order, after a header line. Tab separated, UTF-8, comma as the decimal separator.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.reports().fec(
    FecReportsRequest
        .builder()
        .fromDate("2026-07-01")
        .toDate("2026-07-01")
        .build()
);
```
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

<details><summary><code>client.reports.euPurchases(request) -> EuPurchasesReportsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.reports().euPurchases(
    EuPurchasesReportsRequest
        .builder()
        .fromDate("2026-07-01")
        .toDate("2026-07-01")
        .build()
);
```
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

<details><summary><code>client.reports.vatDetail(request) -> VatDetailReportsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.reports().vatDetail(
    VatDetailReportsRequest
        .builder()
        .fromDate("2026-07-01")
        .toDate("2026-07-01")
        .build()
);
```
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

**side:** `Optional<VatDetailReportsRequestSide>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.reports.posSales(request) -> PosSalesReportsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.reports().posSales(
    PosSalesReportsRequest
        .builder()
        .fromDate("2026-07-01")
        .toDate("2026-07-01")
        .build()
);
```
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

<details><summary><code>client.reports.onlineSales(request) -> OnlineSalesReportsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.reports().onlineSales(
    OnlineSalesReportsRequest
        .builder()
        .fromDate("2026-07-01")
        .toDate("2026-07-01")
        .build()
);
```
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

<details><summary><code>client.reports.oss(request) -> OssReportsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.reports().oss(
    OssReportsRequest
        .builder()
        .fromDate("2026-07-01")
        .toDate("2026-07-01")
        .build()
);
```
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

<details><summary><code>client.reports.advanceReconciliation(request) -> AdvanceReconciliationReportsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.reports().advanceReconciliation(
    AdvanceReconciliationReportsRequest
        .builder()
        .fromDate("2026-07-01")
        .toDate("2026-07-01")
        .build()
);
```
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

<details><summary><code>client.reports.writeOffActs(request) -> WriteOffActsReportsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.reports().writeOffActs(
    WriteOffActsReportsRequest
        .builder()
        .fromDate("2026-07-01")
        .toDate("2026-07-01")
        .build()
);
```
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

<details><summary><code>client.reports.costCenters(request) -> CostCentersReportsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.reports().costCenters(
    CostCentersReportsRequest
        .builder()
        .fromDate("2026-07-01")
        .toDate("2026-07-01")
        .build()
);
```
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

<details><summary><code>client.reports.costCenterActivity(request) -> CostCenterActivityReportsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.reports().costCenterActivity(
    CostCenterActivityReportsRequest
        .builder()
        .fromDate("2026-07-01")
        .toDate("2026-07-01")
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

<details><summary><code>client.reports.costCenterItems(request) -> CostCenterItemsReportsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.reports().costCenterItems(
    CostCenterItemsReportsRequest
        .builder()
        .fromDate("2026-07-01")
        .toDate("2026-07-01")
        .build()
);
```
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

<details><summary><code>client.reports.jobsCreate(request) -> JobsCreateReportsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.reports().jobsCreate(
    JobsCreateReportsRequest
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

**formats:** `Optional<List<JobsCreateReportsRequestFormatsItem>>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.reports.jobsGet(request) -> JobsGetReportsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.reports().jobsGet(
    JobsGetReportsRequest
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

<details><summary><code>client.reports.jobsList(request) -> JobsListReportsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.reports().jobsList(
    JobsListReportsRequest
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

**sort:** `Optional<List<JobsListReportsRequestSortItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**filter:** `Optional<List<JobsListReportsRequestFilterItem>>` 
    
</dd>
</dl>

<dl>
<dd>

**totals:** `Optional<List<String>>` — Numeric fields to sum over every row matching the filter (not only the current page)
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## consolidation
<details><summary><code>client.consolidation.groupsCreate(request) -> GroupsCreateConsolidationResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.consolidation().groupsCreate(
    GroupsCreateConsolidationRequest
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

<details><summary><code>client.consolidation.groupsList(request) -> GroupsListConsolidationResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.consolidation().groupsList(
    GroupsListConsolidationRequest
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

<details><summary><code>client.consolidation.groupsGet(request) -> GroupsGetConsolidationResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.consolidation().groupsGet(
    GroupsGetConsolidationRequest
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

<details><summary><code>client.consolidation.groupsUpdate(request) -> GroupsUpdateConsolidationResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.consolidation().groupsUpdate(
    GroupsUpdateConsolidationRequest
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

<details><summary><code>client.consolidation.groupsDelete(request) -> GroupsDeleteConsolidationResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.consolidation().groupsDelete(
    GroupsDeleteConsolidationRequest
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

<details><summary><code>client.consolidation.membersAdd(request) -> MembersAddConsolidationResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.consolidation().membersAdd(
    MembersAddConsolidationRequest
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

**method:** `Optional<MembersAddConsolidationRequestMethod>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.consolidation.membersRemove(request) -> MembersRemoveConsolidationResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.consolidation().membersRemove(
    MembersRemoveConsolidationRequest
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

<details><summary><code>client.consolidation.intercompanyCandidates(request) -> IntercompanyCandidatesConsolidationResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Partners in member companies that look like other members of the same group (matched on company code or VAT code), with any existing intercompany link. Confirming a candidate via intercompany/links/set enables invoice mirroring.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.consolidation().intercompanyCandidates(
    IntercompanyCandidatesConsolidationRequest
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

<details><summary><code>client.consolidation.intercompanyLinksSet(request) -> IntercompanyLinksSetConsolidationResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Confirm that a partner record in one member company represents another member company of the group. Once links exist in both directions, issuing an intercompany sale invoice automatically creates the matching draft purchase invoice in the counterparty.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.consolidation().intercompanyLinksSet(
    IntercompanyLinksSetConsolidationRequest
        .builder()
        .groupId("groupId")
        .partnerId("partnerId")
        .counterpartyCompanyId("counterpartyCompanyId")
        .build()
);
```
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

**partnerId:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**counterpartyCompanyId:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.consolidation.intercompanyLinksList(request) -> IntercompanyLinksListConsolidationResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.consolidation().intercompanyLinksList(
    IntercompanyLinksListConsolidationRequest
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

<details><summary><code>client.consolidation.intercompanyLinksRemove(request) -> IntercompanyLinksRemoveConsolidationResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.consolidation().intercompanyLinksRemove(
    IntercompanyLinksRemoveConsolidationRequest
        .builder()
        .groupId("groupId")
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

**groupId:** `String` 
    
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

<details><summary><code>client.consolidation.intercompanyReport(request) -> IntercompanyReportConsolidationResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Intercompany reconciliation for a period: every issued intercompany sale invoice with its mirrored or manually recorded counterpart, unmatched documents on both sides, and per-currency totals with differences. Confirmed pairs are the basis for consolidation eliminations.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.consolidation().intercompanyReport(
    IntercompanyReportConsolidationRequest
        .builder()
        .groupId("groupId")
        .fromDate("2026-07-01")
        .toDate("2026-07-01")
        .build()
);
```
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
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.consolidation.report(request) -> ReportConsolidationResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.consolidation().report(
    ReportConsolidationRequest
        .builder()
        .groupId("groupId")
        .fromDate("2026-07-01")
        .toDate("2026-07-01")
        .build()
);
```
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

**category:** `Optional<ReportConsolidationRequestCategory>` 
    
</dd>
</dl>

<dl>
<dd>

**eliminations:** `Optional<List<ReportConsolidationRequestEliminationsItem>>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## public
<details><summary><code>client.public_.integrationRequests(request) -> IntegrationRequestsPublicResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.public_().integrationRequests(
    IntegrationRequestsPublicRequest
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

<details><summary><code>client.public_.pay(token)</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.public_().pay(
    "token",
    PayPublicRequest
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

**token:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## billing
<details><summary><code>client.billing.accountGet(request) -> AccountGetBillingResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.billing().accountGet(
    AccountGetBillingRequest
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

<details><summary><code>client.billing.accountSetPlan(request) -> AccountSetPlanBillingResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.billing().accountSetPlan(
    AccountSetPlanBillingRequest
        .builder()
        .plan(AccountSetPlanBillingRequestPlan.STARTER)
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**plan:** `AccountSetPlanBillingRequestPlan` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.billing.topupCreate(request) -> TopupCreateBillingResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.billing().topupCreate(
    TopupCreateBillingRequest
        .builder()
        .amountCents(1000000L)
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**amountCents:** `Long` 
    
</dd>
</dl>

<dl>
<dd>

**locale:** `Optional<TopupCreateBillingRequestLocale>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.billing.portalCreate(request) -> PortalCreateBillingResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.billing().portalCreate(
    PortalCreateBillingRequest
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

**locale:** `Optional<PortalCreateBillingRequestLocale>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.billing.transactionsList(request) -> TransactionsListBillingResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.billing().transactionsList(
    TransactionsListBillingRequest
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

**limit:** `Optional<Long>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.billing.usageList(request) -> UsageListBillingResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.billing().usageList(
    UsageListBillingRequest
        .builder()
        .from("2026-07-01")
        .to("2026-07-01")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**from:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**to:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## account
<details><summary><code>client.account.loginLinkRequest(request) -> LoginLinkRequestAccountResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.account().loginLinkRequest(
    LoginLinkRequestAccountRequest
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

**locale:** `Optional<LoginLinkRequestAccountRequestLocale>` 
    
</dd>
</dl>

<dl>
<dd>

**acceptTerms:** `Optional<Boolean>` 
    
</dd>
</dl>

<dl>
<dd>

**acceptDpa:** `Optional<Boolean>` 
    
</dd>
</dl>

<dl>
<dd>

**referralCode:** `Optional<String>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.account.loginLinkConsume(request) -> LoginLinkConsumeAccountResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.account().loginLinkConsume(
    LoginLinkConsumeAccountRequest
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

<details><summary><code>client.account.logout(request) -> LogoutAccountResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.account().logout(
    LogoutAccountRequest
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

<details><summary><code>client.account.me(request) -> MeAccountResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.account().me(
    MeAccountRequest
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

<details><summary><code>client.account.membersList(request) -> MembersListAccountResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.account().membersList(
    MembersListAccountRequest
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

<details><summary><code>client.account.membersSetRole(request) -> MembersSetRoleAccountResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.account().membersSetRole(
    MembersSetRoleAccountRequest
        .builder()
        .userId("userId")
        .role(MembersSetRoleAccountRequestRole.ADMIN)
        .build()
);
```
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

**role:** `MembersSetRoleAccountRequestRole` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.account.membersTransferOwnership(request) -> MembersTransferOwnershipAccountResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.account().membersTransferOwnership(
    MembersTransferOwnershipAccountRequest
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

<dl>
<dd>

**movePayer:** `Optional<Boolean>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.account.membersRemove(request) -> MembersRemoveAccountResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.account().membersRemove(
    MembersRemoveAccountRequest
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

<details><summary><code>client.account.invitesCreate(request) -> InvitesCreateAccountResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.account().invitesCreate(
    InvitesCreateAccountRequest
        .builder()
        .email("email")
        .role(InvitesCreateAccountRequestRole.ADMIN)
        .build()
);
```
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

**role:** `InvitesCreateAccountRequestRole` 
    
</dd>
</dl>

<dl>
<dd>

**locale:** `Optional<InvitesCreateAccountRequestLocale>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.account.invitesList(request) -> InvitesListAccountResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.account().invitesList(
    InvitesListAccountRequest
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

<details><summary><code>client.account.invitesRevoke(request) -> InvitesRevokeAccountResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.account().invitesRevoke(
    InvitesRevokeAccountRequest
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

<details><summary><code>client.account.invitesGet(request) -> InvitesGetAccountResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.account().invitesGet(
    InvitesGetAccountRequest
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

<details><summary><code>client.account.invitesAccept(request) -> InvitesAcceptAccountResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.account().invitesAccept(
    InvitesAcceptAccountRequest
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

**locale:** `Optional<InvitesAcceptAccountRequestLocale>` 
    
</dd>
</dl>

<dl>
<dd>

**acceptTerms:** `Optional<Boolean>` 
    
</dd>
</dl>

<dl>
<dd>

**acceptDpa:** `Optional<Boolean>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.account.localeSet(request) -> LocaleSetAccountResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.account().localeSet(
    LocaleSetAccountRequest
        .builder()
        .locale(LocaleSetAccountRequestLocale.EN)
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**locale:** `LocaleSetAccountRequestLocale` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.account.companiesCreate(request) -> CompaniesCreateAccountResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.account().companiesCreate(
    CompaniesCreateAccountRequest
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

**smeExemptionNumber:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**isVatPayer:** `Optional<Boolean>` 
    
</dd>
</dl>

<dl>
<dd>

**vatPeriod:** `Optional<CompaniesCreateAccountRequestVatPeriod>` 
    
</dd>
</dl>

<dl>
<dd>

**fiscalYearEndMonth:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**timeZone:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**filingOptions:** `Optional<Map<String, String>>` 
    
</dd>
</dl>

<dl>
<dd>

**address:** `Optional<CompaniesCreateAccountRequestAddress>` 
    
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

**sepaCreditorId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**defaultInvoiceCurrency:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**legalForm:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**registryName:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**incorporatedOn:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**shareCapital:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**accountsKeptBy:** `Optional<CompaniesCreateAccountRequestAccountsKeptBy>` 
    
</dd>
</dl>

<dl>
<dd>

**bookkeeperName:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**auditorName:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**auditorRegistrationNumber:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**auditRequired:** `Optional<Boolean>` 
    
</dd>
</dl>

<dl>
<dd>

**countryCode:** `Optional<CompaniesCreateAccountRequestCountryCode>` — Jurisdiction the company is registered in (immutable after creation)
    
</dd>
</dl>

<dl>
<dd>

**baseCurrency:** `Optional<String>` — Currency the ledger is kept in; defaults to the national currency of countryCode (immutable after creation)
    
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

<details><summary><code>client.account.companiesSelect(request) -> CompaniesSelectAccountResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.account().companiesSelect(
    CompaniesSelectAccountRequest
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

<details><summary><code>client.account.companiesProfile(request) -> CompaniesProfileAccountResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.account().companiesProfile(
    CompaniesProfileAccountRequest
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

<details><summary><code>client.account.companiesUpdate(request) -> CompaniesUpdateAccountResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.account().companiesUpdate(
    CompaniesUpdateAccountRequest
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

**smeExemptionNumber:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**isVatPayer:** `Optional<Boolean>` 
    
</dd>
</dl>

<dl>
<dd>

**vatPeriod:** `Optional<CompaniesUpdateAccountRequestVatPeriod>` 
    
</dd>
</dl>

<dl>
<dd>

**fiscalYearEndMonth:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**timeZone:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**filingOptions:** `Optional<Map<String, Optional<String>>>` 
    
</dd>
</dl>

<dl>
<dd>

**address:** `Optional<CompaniesUpdateAccountRequestAddress>` 
    
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

**sepaCreditorId:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**defaultInvoiceCurrency:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**legalForm:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**registryName:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**incorporatedOn:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**shareCapital:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**accountsKeptBy:** `Optional<CompaniesUpdateAccountRequestAccountsKeptBy>` 
    
</dd>
</dl>

<dl>
<dd>

**bookkeeperName:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**auditorName:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**auditorRegistrationNumber:** `Optional<String>` 
    
</dd>
</dl>

<dl>
<dd>

**auditRequired:** `Optional<Boolean>` 
    
</dd>
</dl>

<dl>
<dd>

**logo:** `Optional<CompaniesUpdateAccountRequestLogo>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.account.companiesArchive(request) -> CompaniesArchiveAccountResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.account().companiesArchive(
    CompaniesArchiveAccountRequest
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

<details><summary><code>client.account.companiesDelete(request) -> CompaniesDeleteAccountResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.account().companiesDelete(
    CompaniesDeleteAccountRequest
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

<details><summary><code>client.account.companiesActivate(request) -> CompaniesActivateAccountResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.account().companiesActivate(
    CompaniesActivateAccountRequest
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

<details><summary><code>client.account.apiKeysCreate(request) -> ApiKeysCreateAccountResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.account().apiKeysCreate(
    ApiKeysCreateAccountRequest
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

<dl>
<dd>

**expiresInDays:** `Optional<Long>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.account.apiKeysList(request) -> ApiKeysListAccountResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.account().apiKeysList(
    ApiKeysListAccountRequest
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

<details><summary><code>client.account.apiKeysRotate(request) -> ApiKeysRotateAccountResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.account().apiKeysRotate(
    ApiKeysRotateAccountRequest
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

**overlapHours:** `Optional<Long>` 
    
</dd>
</dl>

<dl>
<dd>

**expiresInDays:** `Optional<Long>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.account.apiKeysRevoke(request) -> ApiKeysRevokeAccountResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.account().apiKeysRevoke(
    ApiKeysRevokeAccountRequest
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

<details><summary><code>client.account.consentAccept(request) -> ConsentAcceptAccountResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.account().consentAccept(
    ConsentAcceptAccountRequest
        .builder()
        .acceptTerms(true)
        .acceptDpa(true)
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**acceptTerms:** `Boolean` 
    
</dd>
</dl>

<dl>
<dd>

**acceptDpa:** `Boolean` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.account.profileUpdate(request) -> ProfileUpdateAccountResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.account().profileUpdate(
    ProfileUpdateAccountRequest
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
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.account.emailChangeRequest(request) -> EmailChangeRequestAccountResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.account().emailChangeRequest(
    EmailChangeRequestAccountRequest
        .builder()
        .newEmail("newEmail")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**newEmail:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**locale:** `Optional<EmailChangeRequestAccountRequestLocale>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.account.sessionsList(request) -> SessionsListAccountResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.account().sessionsList(
    SessionsListAccountRequest
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

<details><summary><code>client.account.sessionsRevoke(request) -> SessionsRevokeAccountResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.account().sessionsRevoke(
    SessionsRevokeAccountRequest
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

<details><summary><code>client.account.sessionsRevokeOthers(request) -> SessionsRevokeOthersAccountResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.account().sessionsRevokeOthers(
    SessionsRevokeOthersAccountRequest
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

<details><summary><code>client.account.export(request) -> ExportAccountResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.account().export(
    ExportAccountRequest
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

<details><summary><code>client.account.delete(request) -> DeleteAccountResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Removes the user: sessions, sign-in links, memberships and pending invitations are deleted at once; the email and name are replaced by an anonymous placeholder immediately and the remaining row is removed after 30 days. Refused while the user still owns or pays for a company that is not deleted.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.account().delete(
    DeleteAccountRequest
        .builder()
        .confirmEmail("confirmEmail")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**confirmEmail:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.account.referralGet(request) -> ReferralGetAccountResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.account().referralGet(
    ReferralGetAccountRequest
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

<details><summary><code>client.account.referralConvert(request) -> ReferralConvertAccountResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.account().referralConvert(
    ReferralConvertAccountRequest
        .builder()
        .points(1000000L)
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**points:** `Long` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.account.tableSettingsGet(request) -> TableSettingsGetAccountResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.account().tableSettingsGet(
    TableSettingsGetAccountRequest
        .builder()
        .tableKey("tableKey")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**tableKey:** `String` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.account.tableSettingsSet(request) -> TableSettingsSetAccountResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.account().tableSettingsSet(
    TableSettingsSetAccountRequest
        .builder()
        .tableKey("tableKey")
        .build()
);
```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**tableKey:** `String` 
    
</dd>
</dl>

<dl>
<dd>

**columns:** `Optional<List<String>>` 
    
</dd>
</dl>

<dl>
<dd>

**pageSize:** `Optional<Double>` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.account.tableSettingsList(request) -> TableSettingsListAccountResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```java
client.account().tableSettingsList(
    TableSettingsListAccountRequest
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

