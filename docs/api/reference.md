# REST API Reference

This API reference covers **core Statit functions** to publish metrics. Please head to user guide if you want to access metrics.

**Publishing series**:

- [putSerie](#putserie)
- [batchPutSerie](#batchputserie)
- [updateSerie](#updateserie)
- [deleteSerie](#deleteserie)

**Publishing collections**:

- [updateCollection](#updateCollection)

## **Errors**

Requests with errors return a response object with the following attributes:

- code: An explicit error code
- message: An explicit error message


## **putSerie**

**putSerie** is used to **put a serie inside a collection**

putSerie is used to publish a new serie. Every call to putSerie will replace the previously saved serie.

#### Parameters

- **action**: putSerie
- **input** - **Object**:
    - **id** - **String** - *required*. ID of the serie. Accepted characters: alphanumerical (A to z, 0 to 9) and ".", "-", "_" and "/"
    - **name** - **String** - *required*. Name of the serie
    - **frequency** - **String** - *required*. Frequency of the serie. Accepted values: D, W, M, Q, S, Y
    - **description** - **String** - *optional*. Description of the serie. Text format
    - **unit**- **String** - *optional*. Unit of the serie
    - **sources** - **String** - *optional*. Sources
    - **tags** - **Array** - *optional*. List of tags for the serie
    - **notes** - **String** - *optional*. Publication notes
    - **observations** - **String** - *optional*. A stringified array of individual observations, for instance "[\"2021-03-07\", 62.0], [\"2021-03-08\", 105.0]". Observation metadata can be added as a third element in each observation array ("[\"2021-03-08\", 105.0, \"value computed\"]"). If metadata is added, it must be added on everyline
    - **version** - **String** - *optional*. A short comment that will be recorded with the specific serie update


#### Response

- **input** - **Object**:
    - **id**: id of the serie




## **batchPutSerie**

**batchPutSerie** is used to put multiple series inside a collection.

Up to 25 series can be put in a single call.

#### Parameters

- **action**: batchPutSerie
- **input** - **Array**:
    - Serie object as in putSerie

#### Response

- **input** - Array:
    - **ids** of the series pushed







listSeries is used to get all children series under a single parent ID.

As an example, a/b/c is the parent ID of a/b/c/serie1 and a/b/c/serie2

#### Parameters

- **action**: listSeries
- **input** - **Object**:
    - **id** - *required* - **String**. ID of the parentID

#### Response

- **Items** - Array of Item (see get serie)



## **updateSerie**

**updateSerie** is used to **update a serie**

#### Parameters

- **action**: putSerie
- **input** - **Object**:
    - **id** - **String** - *required*. ID of the serie. Accepted characters: alphanumerical (A to z, 0 to 9) and ".", "-", "_" and "/"
    - **name** - **String** - *optional*. Name of the serie
    - **frequency** - **String** - *optional. Frequency of the serie. Accepted values: D, W, M, Q, S, Y
    - **description** - **String** - *optional*. Description of the serie. Text format
    - **unit**- **String** - *optional*. Unit of the serie
    - **sources** - **String** - *optional*. Sources
    - **tags** - **Array** - *optional*. List of tags for the serie
    - **notes** - **String** - *optional*. Publication notes
    - **observations** - **String** - *optional*. A stringified array of individual observations, for instance "[\"2021-03-07\", 62.0], [\"2021-03-08\", 105.0]". Observation metadata can be added as a third element in each observation array ("[\"2021-03-08\", 105.0, \"value computed\"]"). If metadata is added, it must be added on everyline


#### Response

- **input** - **Object**:
    - **id**: id of the serie



## **deleteSerie**

deleteSerie is used to remove a serie.

#### Parameters

- **action**: deleteSerie
- **input** - **Object**:
    - **id** - *required* - **String**. ID of the serie

#### Response

- **input** - **Object**:
    - **id**: id of the serie

## **updateCollection**

**updateCollection** is used to **update the properties of an existing collection**

#### Parameters

- **action**: updateCollection
- **input** - **Object**:
    - **id** - **String** - *required*. ID of the collection. Needs to be the id an existing collection.
    - **name** - **String** - *optional*. Name of the collection
    - **about** - **String** - *optional*. A field describing the collection in one sentence. Text format
    - **frequency** - **String** - *optional*. A descriptive field. Accepted values: D (day), W (week), M (month), Q (quarter), S (semester), Y (year)
    - **description** - **String** - *optional*. A descriptive field. Text or markdown format.
    - **tags** - **Array** - *optional*. Tags related to the collection

#### Response

- **input** - **Object**:
    - **id**: id the collection

