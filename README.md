## Sample Audience Data and Taxonomy Files
These audeince data and taxonomy files are provided as examples only. For parameter definitions and data types, see the data flow PDF.
## Formatting note
In the data and taxonomy files, you _must_ put each JSON object on a separate line.

##Audience data file example
Your data file could look similar to the mock data below.

```JSON
{"device_id":"5f4b0df4-13aa-a262-e792-e331a8163fae","device_id_type":"THIRDPARTY","audience_ids":[{"audience_id":"1344768","advertiser_ids":[1234]}],"operation":{"updated_at":"2015-01-01T00:00:00Z","action":1}}
{"device_id":"5f4b0df4-13aa-a262-e792-e331a8163fae","device_id_type":"THIRDPARTY","audience_ids":[{"audience_id":"1344768","advertiser_ids":[1234]}],"operation":{"updated_at":"2015-01-01T00:00:00Z","action":1}
{"device_id":"c4f844be-b006-2fc1-3490-3fe2259db90a","device_id_type":"THIRDPARTY","audience_ids":[{"audience_id":"3478418","advertiser_ids":[]}],"operation":{"updated_at":"2015-01-01T00:00:00Z","action":1}}
{"device_id":"93da234e-b2af-9a08-dc6f-ce2177dca2fb","device_id_type":"THIRDPARTY","audience_ids":[{"audience_id":"2467814","advertiser_ids":[1234,5678]}],"operation":{"updated_at":"2015-01-01T00:00:00Z","action":1}}
{"device_id":"4f8e1031-c0fc-8aa0-b17c-0fe89a6a74e7","device_id_type":"THIRDPARTY","audience_ids":[{"audience_id":"1344768","advertiser_ids":[1234]}],"operation":{"updated_at":"2015-01-01T00:00:00Z","action":3}}
{"device_id":"184d0e92-c291-49b3-c456-bf4c3c516fce","device_id_type":"THIRDPARTY","audience_ids":[{"audience_id":"3697584","advertiser_ids":[5678]}],"operation":{"updated_at":"2015-01-01T00:00:00Z","action":1}}
```
## Audience Taxononmy File
Your taxonomy file could look similar to the mock data below.

```JSON
{"audience_id":"123","advertiser_ids":[1],"name":"Sample name 1","description":"Sample description 1"}
{"audience_id":"456","advertiser_ids":[2],"name":"Sample name 2","description":"Sample description 2"}
{"audience_id":"789","advertiser_ids":[3],"name":"Sample name 3","description":"Sample description 3"}
```
