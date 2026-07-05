# protexdefense-blocklists

Listas de bloqueio compiladas automaticamente com [HostlistCompiler](https://github.com/AdguardTeam/HostlistCompiler),
com cache HTTP condicional por fonte (ETag/Last-Modified) — cada fonte só é rebaixada quando o servidor de origem confirma que mudou.

Última execução: **2026-07-05** — 6 lista(s) publicada(s) (6 sem nenhuma mudança), 2 falha(s).

## Como usar

Cada categoria abaixo vira um arquivo em `lists/<categoria>.txt`, pronto para ser usado
como URL de blocklist no AdGuard Home, Pi-hole, etc:

```
https://raw.githubusercontent.com/protexdefense/protexdefense-blocklists/main/lists/<categoria>.txt
```

## lite

Arquivo: [`lists/lite.txt`](lists/lite.txt) — 6 fonte(s) ativas, 325772 regras após deduplicação. Atualizado em **2026-07-05**.

| Blocklist | Descrição | Homepage | Licença | Raw |
|---|---|---|---|---|
| AdGuard DNS filter | Filtro combinado da AdGuard para bloqueio via DNS | https://github.com/AdguardTeam/AdguardFilters | GPLv3 | https://adguardteam.github.io/HostlistsRegistry/assets/filter_1.txt |
| OISD Blocklist Small | OISD Small — versão enxuta do OISD | https://oisd.nl/ | Uso não comercial — ver oisd.nl/pages/faq | https://adguardteam.github.io/HostlistsRegistry/assets/filter_5.txt |
| 1Hosts (Lite) | Versão enxuta do 1Hosts | https://github.com/badmojr/1Hosts | MIT | https://adguardteam.github.io/HostlistsRegistry/assets/filter_24.txt |
| Peter Lowe's Blocklist | Blocklist de servidores de anúncios mantida desde os anos 2000 | https://pgl.yoyo.org/adservers/ | CC BY-SA 4.0 | https://adguardteam.github.io/HostlistsRegistry/assets/filter_3.txt |
| HaGeZi's Pro Blocklist | HaGeZi Pro — bloqueio balanceado de ads/tracking/telemetria | https://github.com/hagezi/dns-blocklists | MIT | https://adguardteam.github.io/HostlistsRegistry/assets/filter_48.txt |
| Dan Pollock's List | Lista hosts de Dan Pollock (someonewhocares.org) | https://someonewhocares.org/hosts/ | Uso pessoal livre | https://adguardteam.github.io/HostlistsRegistry/assets/filter_4.txt |

## malware

Arquivo: [`lists/malware.txt`](lists/malware.txt) — 17 fonte(s) ativas, 1742236 regras após deduplicação. Atualizado em **2026-07-05**.

| Blocklist | Descrição | Homepage | Licença | Raw |
|---|---|---|---|---|
| ShadowWhisperer's Malware List | - | - | - | https://adguardteam.github.io/HostlistsRegistry/assets/filter_42.txt |
| Dandelion Sprout's Anti-Malware List | - | - | - | https://adguardteam.github.io/HostlistsRegistry/assets/filter_12.txt |
| Malicious URL Blocklist (URLHaus) | - | - | - | https://adguardteam.github.io/HostlistsRegistry/assets/filter_11.txt |
| The Big List of Hacked Malware Web Sites | - | - | - | https://adguardteam.github.io/HostlistsRegistry/assets/filter_9.txt |
| POL: CERT Polska List of malicious domains | Lista de domínios maliciosos do CERT Polska | https://cert.pl/en/posts/2020/03/malicious_domains/ | - | https://adguardteam.github.io/HostlistsRegistry/assets/filter_41.txt |
| HaGeZi's Threat Intelligence Feeds | HaGeZi Threat Intelligence Feeds | https://github.com/hagezi/dns-blocklists | MIT | https://adguardteam.github.io/HostlistsRegistry/assets/filter_44.txt |
| uBlock₀ filters – Badware risks | - | - | - | https://adguardteam.github.io/HostlistsRegistry/assets/filter_50.txt |
| add.Risk | Websites with risk content, malwares etc | https://github.com/FadeMind/hosts.extras/ | GPLv3+ | https://raw.githubusercontent.com/FadeMind/hosts.extras/master/add.Risk/hosts |
| Anti Malware List (alt) | DandelionSprout's Anti Malware Filter | https://github.com/DandelionSprout/adfilt | Dandelicence v1.4 | https://raw.githubusercontent.com/DandelionSprout/adfilt/master/Alternate%20versions%20Anti-Malware%20List/AntiMalwareHosts.txt |
| Anti-Malware Blocklists (notrack) | NoTrack project Anti-Malware Blocklists | https://gitlab.com/quidsup/notrack-blocklists | GPLv3 | https://gitlab.com/quidsup/notrack-blocklists/raw/master/notrack-malware.txt |
| Badd-Boyz-Hosts | A hosts file to block bad domains | https://github.com/mitchellkrogza/Badd-Boyz-Hosts/ | MIT | https://raw.githubusercontent.com/mitchellkrogza/Badd-Boyz-Hosts/master/hosts |
| blackbook | Blackbook of malware domains | https://github.com/stamparm/blackbook | Public Domain | https://raw.githubusercontent.com/stamparm/blackbook/master/blackbook.txt |
| Ransomware block list | Known sites that host or contain ransomware | https://github.com/blocklistproject/Lists/ | The Unlicense | https://blocklistproject.github.io/Lists/ransomware.txt |
| URLhaus | A project to share malicious URLs | https://urlhaus.abuse.ch/ | CC0 | https://urlhaus.abuse.ch/downloads/hostfile/ |
| URLhaus Host file | A project to share malicious URLs (via StevenBlack/hosts) | https://urlhaus.abuse.ch/ | CC0 | https://raw.githubusercontent.com/StevenBlack/hosts/refs/heads/master/data/URLHaus/hosts |
| Online Malicious URL Blocklist (AdGuard) | Malicious URL blocklist baseado no URLhaus, formato AdGuard Home | https://gitlab.com/malware-filter/urlhaus-filter | CC BY-SA 4.0 | https://malware-filter.gitlab.io/malware-filter/urlhaus-filter-agh.txt |
| SPY BOT MCLX | ANTI-SPY HOSTS | https://github.com/protexdefense/adguard-all-list | - | https://raw.githubusercontent.com/protexdefense/adguard-all-list/refs/heads/main/filter_anti-spy.txt |

## phishing

Arquivo: [`lists/phishing.txt`](lists/phishing.txt) — 9 fonte(s) ativas, 280634 regras após deduplicação. Atualizado em **2026-07-05**.

| Blocklist | Descrição | Homepage | Licença | Raw |
|---|---|---|---|---|
| Phishing URL Blocklist (PhishTank and OpenPhish) | - | - | - | https://adguardteam.github.io/HostlistsRegistry/assets/filter_30.txt |
| Scam Blocklist by DurableNapkin | - | - | - | https://adguardteam.github.io/HostlistsRegistry/assets/filter_10.txt |
| Phishing Army | - | - | - | https://adguardteam.github.io/HostlistsRegistry/assets/filter_18.txt |
| eth-phishing-detect | Phishing domains targeting Ethereum users | https://github.com/MetaMask/eth-phishing-detect/ | DON'T BE A DICK PUBLIC LICENSE | https://raw.githubusercontent.com/MetaMask/eth-phishing-detect/master/src/hosts.txt |
| Fraud block list | Lists of sites created to fraud | https://github.com/blocklistproject/Lists/ | The Unlicense | https://blocklistproject.github.io/Lists/fraud.txt |
| GlobalAntiScamOrg-blocklist | Global Anti Scam Organization blocklist | https://github.com/elliotwutingfeng/GlobalAntiScamOrg-blocklist | BSD-3-Clause | https://raw.githubusercontent.com/elliotwutingfeng/GlobalAntiScamOrg-blocklist/main/global-anti-scam-org-scam-urls-pihole.txt |
| OpenPhish | Phishing Intelligence (mirror do feed público, mais estável que openphish.com direto) | https://openphish.com/ | All rights reserved | https://raw.githubusercontent.com/openphish/public_feed/refs/heads/main/feed.txt |
| Phishing Army Extended | The Extended Blocklist to filter Phishing | https://www.phishing.army/ | CC BY-NC 4.0 | https://phishing.army/download/phishing_army_blocklist_extended.txt |
| Phishing URL Blocklist (AdGuard Home) | PhishTank/OpenPhish/Cert.pl based blocklist, formato AdGuard Home | https://gitlab.com/malware-filter/phishing-filter | CC BY-SA 4.0 | https://malware-filter.gitlab.io/malware-filter/phishing-filter-agh.txt |

## privacy

Arquivo: [`lists/privacy.txt`](lists/privacy.txt) — 8 fonte(s) ativas, 448031 regras após deduplicação. Atualizado em **2026-07-05**.

| Blocklist | Descrição | Homepage | Licença | Raw |
|---|---|---|---|---|
| WindowsSpyBlocker - Hosts spy rules | Regras para bloquear telemetria/spyware do Windows | https://github.com/crazy-max/WindowsSpyBlocker | MIT | https://adguardteam.github.io/HostlistsRegistry/assets/filter_23.txt |
| Stalkerware Indicators List | Indicadores de apps de stalkerware (monitoramento não consentido) | https://github.com/AssoEchap/stalkerware-indicators | - | https://adguardteam.github.io/HostlistsRegistry/assets/filter_31.txt |
| The NoTracking blocklist | NoTracking — bloqueio de telemetria e rastreadores diversos | https://github.com/notracking/hosts-blocklists | GPLv3 | https://adguardteam.github.io/HostlistsRegistry/assets/filter_32.txt |
| Firebog - Easyprivacy | Mirror do EasyPrivacy (bloqueio de rastreadores) | https://easylist.to/ | GPLv3 | https://v.firebog.net/hosts/Easyprivacy.txt |
| Perflyst and Dandelion Sprout's Smart-TV Blocklist | Telemetria/anúncios de Smart TVs e consoles | https://github.com/Perflyst/PiHoleBlocklist | - | https://adguardteam.github.io/HostlistsRegistry/assets/filter_7.txt |
| Smart-TV Blocklist for AdGuard Home | Telemetria de Smart TVs, formato AdGuard Home | https://github.com/Perflyst/PiHoleBlocklist | - | https://raw.githubusercontent.com/Perflyst/PiHoleBlocklist/master/SmartTV-AGH.txt |
| Dandelion Sprout's Anti Push Notifications | Bloqueio de solicitações de notificações push | https://github.com/DandelionSprout/adfilt | Dandelicence v1.4 | https://adguardteam.github.io/HostlistsRegistry/assets/filter_39.txt |
| SPY BOT MCLX | ANTI-SPY HOSTS | https://github.com/protexdefense/adguard-all-list | - | https://raw.githubusercontent.com/protexdefense/adguard-all-list/refs/heads/main/filter_anti-spy.txt |

## social

Arquivo: [`lists/social.txt`](lists/social.txt) — 2 fonte(s) ativas, 457 regras após deduplicação. Atualizado em **2026-07-05**.

| Blocklist | Descrição | Homepage | Licença | Raw |
|---|---|---|---|---|
| fanboy-social | Bloqueio de widgets de redes sociais (Fanboy) | https://www.fanboy.co.nz/ | GPLv3 | https://easylist.to/easylist/fanboy-social.txt |
| BLOCK SPOTIFY SERVERS | Bloqueio de servidores de anúncio do Spotify | - | - | https://gist.githubusercontent.com/opus-x/3e673a9d5db2a214df05929a4eee6a57/raw/162f2fe3ba71c010ea195de0feb261561cfd5672/Spotify_Eliminate_Advertisements |

## trackers

Arquivo: [`lists/trackers.txt`](lists/trackers.txt) — 7 fonte(s) ativas, 284823 regras após deduplicação. Atualizado em **2026-07-05**.

| Blocklist | Descrição | Homepage | Licença | Raw |
|---|---|---|---|---|
| NoCoin Filter List | Bloqueio de mineração de criptomoedas via navegador | https://github.com/hoshsadiq/adblock-nocoin-list | MIT | https://adguardteam.github.io/HostlistsRegistry/assets/filter_8.txt |
| uBlock filters – Cookie Notices | Avisos de cookies (annoyances) do uBlock Origin | https://github.com/uBlockOrigin/uAssets | GPLv3 | https://raw.githubusercontent.com/uBlockOrigin/uAssets/master/filters/annoyances-cookies.txt |
| Fanboy Cookiemonster | Bloqueio de avisos de cookies (Fanboy) | https://www.fanboy.co.nz/ | GPLv3 | https://secure.fanboy.co.nz/fanboy-cookiemonster.txt |
| Fanboy Annoyance | Bloqueio de pop-ups e elementos irritantes (Fanboy) | https://www.fanboy.co.nz/ | GPLv3 | https://secure.fanboy.co.nz/fanboy-annoyance.txt |
| HaGeZi Multi NORMAL | HaGeZi Multi NORMAL — combinação de ads/tracking/malware | https://github.com/hagezi/dns-blocklists | MIT | https://adguardteam.github.io/HostlistsRegistry/assets/filter_34.txt |
| HaGeZi's Pro++ Blocklist | HaGeZi Pro++ — mais agressivo que o Pro | https://github.com/hagezi/dns-blocklists | MIT | https://adguardteam.github.io/HostlistsRegistry/assets/filter_51.txt |
| HaGeZi's Ultimate Blocklist | HaGeZi Ultimate — o mais agressivo da série HaGeZi | https://github.com/hagezi/dns-blocklists | MIT | https://adguardteam.github.io/HostlistsRegistry/assets/filter_49.txt |

## ⚠️ Categorias com falha nesta execução

Mantidas as últimas versões publicadas com sucesso: ads(erro-compilacao) full(erro-compilacao)

---
_Gerado automaticamente por `entrypoint.sh` — não editar manualmente, as alterações serão sobrescritas na próxima execução._
