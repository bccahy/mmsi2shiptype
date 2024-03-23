# mmsi2shiptype

curl -X POST https://www.shipfinder.com/ship/GetShip \
     -H "Content-Type: application/x-www-form-urlencoded; charset=UTF-8" \
     -H "Accept: application/json, text/javascript, */*; q=0.01" \
     -H "Accept-Language: zh-CN,zh;q=0.9" \
     -H "Origin: https://www.shipfinder.com" \
     -H "Referer: https://www.shipfinder.com/" \
     -H "Sec-Fetch-Dest: empty" \
     -H "Sec-Fetch-Mode: cors" \
     -H "Sec-Fetch-Site: same-origin" \
     -H "User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/123.0.0.0 Safari/537.36" \
     -H "X-Requested-With: XMLHttpRequest" \
     --data "mmsi=413235960" \
     --compressed
