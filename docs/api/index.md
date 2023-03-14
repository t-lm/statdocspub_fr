# Getting started with the REST API

This page will help you get started publishing metrics using the Statit API.

- **Set-up and basic concepts**

- **Publishing metrics**
    - Putting a single metric
    - Putting multiple metrics


## **Set-up and basic concepts**

Please, refer to the [user guide](http://help_fr.gostatit.com) to learn about how to get started with the API. 


## **Publishing metrics**

### Putting a single metric

In Statit, metrics are held inside collections. 

If you already have a collection to put metrics, carry on. Otherwise, go in the web application and create a new collection (say for instance 'test). You will need to use the editor interface to achieve this. 

Now that the collection exists, let's add a serie inside. The required parameters for a serie are: id, name and frequency.


#### Example

```bash
### request

curl -X POST \
    -u username:apikey \
    -H "Content-Type: application/json" \
    -d '{"action": "putSerie", "input": {"id": "username/test/new-york", "name": "New York temperatures", "frequency": "D", "observations": [["2021-03-07", 10.0], ["2021-03-08", 11.4]] }}' \
    https://api.gostatit.com/core



### response

{
  "input": {
    "id": "username/temp/new-york"
  }
}
```

That's it. You have added the username/test/new-york serie to your collection. Congrats.


### Removing the serie

Now, let's remove the serie from the collection.


```bash
### request

curl -X POST \
    -u username:apikey \
    -H "Content-Type: application/json" \
    -d '{"action": "deleteSerie", "input": { "id": "username/temp/new-york" }}' \
    https://api.gostatit.com/core


### response

{
  "input": {
    "id": "username/temp/new-york",
  }
}
```

### Next steps

You will find the full API reference [here](reference.md)
