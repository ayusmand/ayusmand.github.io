Account Info
    Account name: ayusman-phoneix-test-1
    Account domain: foo.bar.com
    Site ID: ayusman-phoneix-test-1
    Account type: production
    Parent account: -
    Primary industry: Automotive
    Company name: ayusman-phoneix-test-1
    Company description: -
    Company address:
        100 Main St
        Seattle, Washington 98012
        United States
    Timezone: US/Pacific
    Pixels: ayusman-phoneix-test-1 - Pixel 3264 (2 subpixels)

Site Tags

//Created 16 Nov 2024
Tag Name: "ayusman-phoneix-test-1 - Pixel 3264"
Tag type: javascript
JavaScript code:
        <script async type="text/javascript">
            function zync_call() {
                var z = document.createElement("script");
                var PageUrl=encodeURIComponent(window.top.location.href).replace(/[!'()~]/g, escape).replace(/\*/g, "%2A");
                var zmpID="ayusman-phoneix-test-1";
                var cache_buster=Date.now();

                var z_src = "https://zync-kafka-external.dev.zetaglobal.io/sync?c=16b6410431b6374e780104abb0443ca8&p=e41d6c355f9838395cdbf54579bee838&k=ayusman-phoneix-test-1-pixel-3264&PageUrl="+PageUrl+"&zmpID="+zmpID+"&cache_buster="+cache_buster;
                z.setAttribute("src", z_src);
                document.body.appendChild(z);
            }

            if (['complete', 'interactive'].indexOf(document.readyState) >= 0) {
                zync_call();
            } else {
                window.addEventListener("DOMContentLoaded", function(){
                    zync_call();
                });
            }
        </script>

Tag redirects:
1.

Tag redirect name "Zeta 1st Party Data (P13N)"
JavaScript code:
        var SITEID='{zmpID}';
        (function(b, t, r, a, i, n) {
            b['bt']=b['bt'] || function() {
                (b['_bt']=b['_bt']||[]).push(arguments);
            },
            i = t.createElement(r),
            n = t.getElementsByTagName(r)[0];
            i.async = 1;
            i.src = a;
            n.parentNode.insertBefore(i, n);
        })(
            window,
            document,
            'script',
            'https://cdn.phoenix.boomtrain.com/p13n/'+SITEID+'/p13n.min.js'
        );
        bt('initialize', SITEID, {externalIds: {zync: '{zync_cookie}'}});
