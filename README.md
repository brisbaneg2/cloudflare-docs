# Cloudflare Docs

## Publishing

Clone the engine somewhere and set it up to be NPM linked:

```bash
git clone git@github.com:adamschwartz/cloudflare-docs-engine.git
npm link
```

For each product, `cd` into `products/$productName` and then run:

```bash
npm link cloudflare-docs-engine && npm run bootstrap && npm run build && wrangler publish
```

## Live test pages

- [1.1.1.1](https://cloudflare-docs-testing.ruthless.design/1-1-1-1) — [Example page](https://cloudflare-docs-testing.ruthless.design/1-1-1-1/what-is-1.1.1.1)
- [Access](https://cloudflare-docs-testing.ruthless.design/access) — [Example page](https://cloudflare-docs-testing.ruthless.design/access/about)
- [Analytics](https://cloudflare-docs-testing.ruthless.design/analytics) — [Example page](https://cloudflare-docs-testing.ruthless.design/analytics/graphql-api)
- [Argo Tunnel](https://cloudflare-docs-testing.ruthless.design/argo-tunnel) — [Example page](https://cloudflare-docs-testing.ruthless.design/argo-tunnel/trycloudflare)
- [BYOIP](https://cloudflare-docs-testing.ruthless.design/byoip) — [Example page](https://cloudflare-docs-testing.ruthless.design/byoip/about)
- [Distributed Web Gateway](https://cloudflare-docs-testing.ruthless.design/distributed-web) — [Example page](https://cloudflare-docs-testing.ruthless.design/distributed-web/ethereum-gateway/about-eth)
- [Firewall](https://cloudflare-docs-testing.ruthless.design/firewall) — [Example page](https://cloudflare-docs-testing.ruthless.design/firewall/cf-firewall-language)
- [Gateway](https://cloudflare-docs-testing.ruthless.design/gateway) — [Example page](https://cloudflare-docs-testing.ruthless.design/gateway/about)
- [HTTP3](https://cloudflare-docs-testing.ruthless.design/http3) — [Example page](https://cloudflare-docs-testing.ruthless.design/http3/intro)
- [Image Resizing](https://cloudflare-docs-testing.ruthless.design/images) — [Example page](https://cloudflare-docs-testing.ruthless.design/images/protected-origin)
- [Life of a Request](https://cloudflare-docs-testing.ruthless.design/internet) — [Example page](https://cloudflare-docs-testing.ruthless.design/internet/intro)
- [Load Balancing](https://cloudflare-docs-testing.ruthless.design/load-balancing) — [Example page](https://cloudflare-docs-testing.ruthless.design/load-balancing/about)
- [Logs](https://cloudflare-docs-testing.ruthless.design/logs) — [Example page](https://cloudflare-docs-testing.ruthless.design/logs/about)
- [Magic Transit](https://cloudflare-docs-testing.ruthless.design/magic-transit) — [Example page](https://cloudflare-docs-testing.ruthless.design/magic-transit/about)
- [Mobile SDK](https://cloudflare-docs-testing.ruthless.design/mobile-sdk) — [Example page](https://cloudflare-docs-testing.ruthless.design/mobile-sdk/getting_started)
- [Network Interconnect](https://cloudflare-docs-testing.ruthless.design/network-interconnect) — [Example page](https://cloudflare-docs-testing.ruthless.design/network-interconnect/about)
- [Randomness Beacon](https://cloudflare-docs-testing.ruthless.design/randomness-beacon) — [Example page](https://cloudflare-docs-testing.ruthless.design/randomness-beacon/about/Background)
- [Registrar](https://cloudflare-docs-testing.ruthless.design/registrar) — [Example page](https://cloudflare-docs-testing.ruthless.design/registrar/about)
- [Spectrum](https://cloudflare-docs-testing.ruthless.design/spectrum) — [Example page](https://cloudflare-docs-testing.ruthless.design/spectrum/getting-started)
- [SSL](https://cloudflare-docs-testing.ruthless.design/ssl/ssl-tls) — [Example page](https://cloudflare-docs-testing.ruthless.design/ssl/ssl-tls/supported-browsers)
- [Stream](https://cloudflare-docs-testing.ruthless.design/stream) — [Example page](https://cloudflare-docs-testing.ruthless.design/stream/faq)
- [Tenant](https://cloudflare-docs-testing.ruthless.design/tenant) — [Example page](https://cloudflare-docs-testing.ruthless.design/tenant/tutorial/accounts)
- [Terraform](https://cloudflare-docs-testing.ruthless.design/terraform) — [Example page](https://cloudflare-docs-testing.ruthless.design/terraform/tutorial/source-control)
- [Time Services](https://cloudflare-docs-testing.ruthless.design/time-services) — [Example page](https://cloudflare-docs-testing.ruthless.design/time-services/ntp/usage)
- [Waf](https://cloudflare-docs-testing.ruthless.design/waf) — [Example page](https://cloudflare-docs-testing.ruthless.design/waf/change-log/2019-10-17---emergency-release)

## Migration progress

| Product              | Builds | Icon | Prod | Test                                                                                         |
| :------------------- | :----- | :--- | :--- | :------------------------------------------------------------------------------------------- |
| 1.1.1.1              | ✕      |      |      | [1.1.1.1](https://cloudflare-docs-testing.ruthless.design/1-1-1-1)                           |
| access               | ✕      | ✕    |      | [Access](https://cloudflare-docs-testing.ruthless.design/access)                             |
| analytics            | ✕      |      |      | [Analytics](https://cloudflare-docs-testing.ruthless.design/analytics)                       |
| argo-tunnel          | ✕      |      |      | [Argo Tunnel](https://cloudflare-docs-testing.ruthless.design/argo-tunnel)                   |
| byoip                | ✕      |      |      | [BYOIP](https://cloudflare-docs-testing.ruthless.design/byoip)                               |
| distributed-web      | ✕      |      |      | [Distributed Web Gateway](https://cloudflare-docs-testing.ruthless.design/distributed-web)   |
| firewall             | ✕      |      |      | [Firewall](https://cloudflare-docs-testing.ruthless.design/firewall)                         |
| gateway              | ✕      |      |      | [Gateway](https://cloudflare-docs-testing.ruthless.design/gateway)                           |
| http3                | ✕      |      |      | [HTTP3](https://cloudflare-docs-testing.ruthless.design/http3)                               |
| images               | ✕      |      |      | [Image Resizing](https://cloudflare-docs-testing.ruthless.design/images)                     |
| internet             | ✕      |      |      | [Life of a Request](https://cloudflare-docs-testing.ruthless.design/internet)                |
| load-balancing       | ✕      |      |      | [Load Balancing](https://cloudflare-docs-testing.ruthless.design/load-balancing)             |
| logs                 | ✕      |      |      | [Logs](https://cloudflare-docs-testing.ruthless.design/logs)                                 |
| magic-transit        | ✕      |      |      | [Magic Transit](https://cloudflare-docs-testing.ruthless.design/magic-transit)               |
| mobile-sdk           | ✕      |      |      | [Mobile SDK](https://cloudflare-docs-testing.ruthless.design/mobile-sdk)                     |
| network-interconnect | ✕      |      |      | [Network Interconnect](https://cloudflare-docs-testing.ruthless.design/network-interconnect) |
| randomness-beacon    | ✕      |      |      | [Randomness Beacon](https://cloudflare-docs-testing.ruthless.design/randomness-beacon)       |
| registrar            | ✕      | ✕    |      | [Registrar](https://cloudflare-docs-testing.ruthless.design/registrar)                       |
| spectrum             | ✕      | ✕    |      | [Spectrum](https://cloudflare-docs-testing.ruthless.design/spectrum)                         |
| ssl                  | ✕      | ✕    |      | [SSL](https://cloudflare-docs-testing.ruthless.design/ssl/ssl-tls)                           |
| stream               | ✕      | ✕    |      | [Stream](https://cloudflare-docs-testing.ruthless.design/stream)                             |
| tenant               | ✕      |      |      | [Tenant](https://cloudflare-docs-testing.ruthless.design/tenant)                             |
| terraform            | ✕      | ✕    |      | [Terraform](https://cloudflare-docs-testing.ruthless.design/terraform)                       |
| time-services        | ✕      | ✕    |      | [Time Services](https://cloudflare-docs-testing.ruthless.design/time-services)               |
| waf                  | ✕      | ✕    |      | [Waf](https://cloudflare-docs-testing.ruthless.design/waf)                                   |
