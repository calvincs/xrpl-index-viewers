# Demo Viewers
  These are examples on how to access the data created from the https://github.com/calvincs/xrpl-account-index repo.
  
#### Example that uses an IPNS dns linked gateway to the index data on IPFS

This uses a dnslinked DNS record which redirects https://index.xmpl.cloud to the cloudflare ipfs gateway.<br/>
This helps non-ipfs enabled devices/browsers access indexed data as well as IPFS data.<br/>
This example does suffer from a lag due to cache of IPNS records on cloudflare.<br/>
It also suffers from a central point of failure, where if the gateway goes down (cloudflare) so does ones access to the data.<br/>
Other examples will show how to get around this issue.<br/>
This example also only utilizes IPFS distribution links.  Objects may have other distribution methods like BitTorrent / WebTorrent.<br/>
<br/>
  - [ipns-https-gateway](https://github.com/calvincs/xrpl-index-viewers/tree/main/ipns-https-gateway)
