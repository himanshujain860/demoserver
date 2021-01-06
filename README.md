# demoserver

https://my-json-server.typicode.com/himanshujain860/demoserver/posts

curl --location --request GET 'https://my-json-server.typicode.com/himanshujain860/demoserver/posts' \
--header 'Cookie: __cfduid=de3007479c598c549edb62fe363b5a7b71609921112'

curl --location --request POST 'https://my-json-server.typicode.com/himanshujain860/demoserver/posts' \
--header 'Content-Type: application/json' \
--header 'Cookie: __cfduid=de3007479c598c549edb62fe363b5a7b71609921112' \
--data-raw '{
        "id": 2,
        "serviceName": "EBook",
        "displayName": "Hello"
    }'
