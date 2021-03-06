| Field | Value | Type |
| -- | -- | -- |
| Action | The code of the first-class action the Cloudflare Firewall took on this request, possible values are: <em>unknown</em> \| <em>allow</em> \| <em>drop</em> \| <em>challenge</em> \| <em>jschallenge</em> \| <em>simulate</em> \| <em>connection_close</em> \| <em>log</em> \| <em>challenge_solved</em> \| <em>challenge_failed</em> \| <em>challenge_bypassed</em> \| <em>jschallenge_solved</em> \| <em>jschallenge_failed</em> \| <em>jschallenge_bypassed</em> \| <em>bypass</em> \| <em>managed_challenge</em> \| <em>managed_challenge_skipped</em> \| <em>managed_challenge_non_interactive_solved</em> \| <em>managed_challenge_interactive_solved</em> \| <em>managed_challenge_bypassed</em> | string |
| ClientASN | The ASN number of the visitor | int |
| ClientASNDescription | The ASN of the visitor as string | string |
| ClientCountry | Country from which request originated | string |
| ClientIP | The visitor's IP address (IPv4 or IPv6) | string |
| ClientIPClass | The classification of the visitor's IP address, possible values are: <em>unknown</em> \| <em>clean</em> \| <em>badHost</em> \| <em>searchEngine</em> \| <em>whitelist</em> \| <em>greylist</em> \| <em>monitoringService</em> \| <em>securityScanner</em> \| <em>noRecord</em> \| <em>scan</em> \| <em>backupService</em> \| <em>mobilePlatform</em> \| <em>tor</em> | string |
| ClientRefererHost | The referer host | string |
| ClientRefererPath | The referer path requested by visitor | string |
| ClientRefererQuery | The referer query-string was requested by the visitor | string |
| ClientRefererScheme | The referer url scheme requested by the visitor | string |
| ClientRequestHost | The HTTP hostname requested by the visitor | string |
| ClientRequestMethod | The HTTP method used by the visitor | string |
| ClientRequestPath | The path requested by visitor | string |
| ClientRequestProtocol | The version of HTTP protocol requested by the visitor | string |
| ClientRequestQuery | The query-string was requested by the visitor | string |
| ClientRequestScheme | The url scheme requested by the visitor | string |
| ClientRequestUserAgent | Visitor's user-agent string | string |
| Datetime | The date and time the event occurred at the edge | int or string |
| EdgeColoCode | The airport code of the Cloudflare datacenter that served this request | string |
| EdgeResponseStatus | HTTP response status code returned to browser | int |
| Kind | The kind of event, currently only possible values are: <em>firewall</em> | string |
| MatchIndex | Rules match index in the chain | int |
| Metadata | Additional product-specific information. Metadata is organized in key:value pairs. Key and Value formats can vary by Cloudflare security product and can change over time | object |
| OriginResponseStatus | HTTP origin response status code returned to browser | int |
| OriginatorRayID | The RayID of the request that issued the challenge/jschallenge | string |
| RayID | The RayID of the request | string |
| RuleID | The Cloudflare security product-specific RuleID triggered by this request | string |
| Source | The Cloudflare security product triggered by this request, possible values are: <em>unknown</em> \| <em>asn</em> \| <em>country</em> \| <em>ip</em> \| <em>iprange</em> \| <em>securitylevel</em> \| <em>zonelockdown</em> \| <em>waf</em> \| <em>firewallrules</em> \| <em>uablock</em> \| <em>ratelimit</em> \| <em>bic</em> \| <em>hot</em> \| <em>l7ddos</em> \| <em>sanitycheck</em> \| <em>botFight</em> | string |
