# Barcode-New-Product
$ curl -X POST -H "user_key: only_for_dev_or_pro" -H "key_type: 3scale" -H "Content-Type: application/json" -H "Accept: application/json" -d "{
  \"upc\": \"4002293401102\"
}" "https://api.upcitemdb.com/prod/v1/lookup"
