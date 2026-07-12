# protexdefense-blocklists

Este projeto compila listas de bloqueio a partir de diversas fontes públicas — cobrindo desde
anúncios, rastreadores e redes sociais até malware, phishing, ransomware e spyware — organizadas
por categoria para você usar só o que precisa no seu AdGuard Home, Pi-hole ou DNS de sua preferência.
O objetivo é simplificar o acesso a essas fontes, sem precisar caçar e manter cada uma manualmente.

Sugestões de novas fontes, atualizações ou fontes sem manutenção que devam ser removidas são
bem-vindas — abra uma issue ou um pull request.

Fontes sem manutenção ativa ou com taxa significativa de falsos positivos não são incluídas.

Última execução: **2026-07-12** — 8 lista(s) publicada(s) (0 sem nenhuma mudança), 0 falha(s).

## Como usar

Cada categoria abaixo vira um arquivo em `lists/<categoria>.txt`, pronto para ser usado
como URL de blocklist no AdGuard Home, Pi-hole, etc:

```
https://raw.githubusercontent.com/protexdefense/protexdefense-blocklists/main/lists/<categoria>.txt
```

## Blocklists

### ads

Arquivo: [`lists/ads.txt`](lists/ads.txt) — 19 fonte(s) ativas, 205077 regras após deduplicação. Atualizado em **2026-07-12**.

| Blocklist | Descrição | Homepage | Licença | Raw |
|---|---|---|---|---|
| AdGuard DNS filter | Filtro combinado da AdGuard para bloqueio via DNS | [Link][AdGuard DNS filter] | GPLv3 | [Raw][AdGuard DNS filter.raw] |
| AdAway Default Blocklist | Blocklist padrão distribuída com o AdAway | [Link][AdAway Default Blocklist] | CC BY 3.0 | [Raw][AdAway Default Blocklist.raw] |
| AWAvenue Ads Rule | AWAvenue Ads Rule — foco em apps/sites chineses | [Link][AWAvenue Ads Rule] | GPLv3 | [Raw][AWAvenue Ads Rule.raw] |
| Dan Pollock's List | Lista hosts de Dan Pollock (someonewhocares.org) | [Link][Dan Pollock's List] | Uso pessoal livre | [Raw][Dan Pollock's List.raw] |
| Peter Lowe's Blocklist | Blocklist de servidores de anúncios mantida desde os anos 2000 | [Link][Peter Lowe's Blocklist] | CC BY-SA 4.0 | [Raw][Peter Lowe's Blocklist.raw] |
| Dandelion Sprout's Game Console Adblock List | Bloqueio de anúncios em consoles de videogame | [Link][Dandelion Sprout's Game Console Adblock List] | Dandelicence v1.4 | [Raw][Dandelion Sprout's Game Console Adblock List.raw] |
| HaGeZi's Pop-Up Ads DNS Blocklist | HaGeZi Pop-Up Ads DNS Blocklist | [Link][HaGeZi's Pop-Up Ads DNS Blocklist] | MIT | [Raw][HaGeZi's Pop-Up Ads DNS Blocklist.raw] |
| uBlock filters (2024) | Filtros gerais do uBlock Origin (safra 2024) | [Link][uBlock filters (2024)] | GPLv3 | [Raw][uBlock filters (2024).raw] |
| uBlock filters – Mobile | Filtros do uBlock Origin específicos para mobile | [Link][uBlock filters – Mobile] | GPLv3 | [Raw][uBlock filters – Mobile.raw] |
| uBlockOrigin filters.txt | Filtros gerais do uBlock Origin | [Link][uBlockOrigin filters.txt] | GPLv3 | [Raw][uBlockOrigin filters.txt.raw] |
| uBlockOrigin quick-fixes | Correções rápidas do uBlock Origin | [Link][uBlockOrigin quick-fixes] | GPLv3 | [Raw][uBlockOrigin quick-fixes.raw] |
| Adblock Plus - Unusual Ads | - | - | - | [Raw][Adblock Plus - Unusual Ads.raw] |
| EasyList Portuguese + EasyList | EasyList + EasyList Portuguese combinados | [Link][EasyList Portuguese + EasyList] | GPLv3 | [Raw][EasyList Portuguese + EasyList.raw] |
| Anti-Circumvention Filters | Filtros anti-circunvenção de bloqueadores de anúncio | [Link][Anti-Circumvention Filters] | GPLv3 | [Raw][Anti-Circumvention Filters.raw] |
| Adblock Plus (Anti-Adblock) | Filtros contra avisos de 'desative seu adblock' | [Link][Adblock Plus (Anti-Adblock)] | GPLv3 | [Raw][Adblock Plus (Anti-Adblock).raw] |
| MobileFilter | Regras específicas para apps mobile | [Link][MobileFilter] | GPLv3 | [Raw][MobileFilter.raw] |
| someonewhocares.org | Lista hosts de Dan Pollock | [Link][someonewhocares.org] | Uso pessoal livre | [Raw][someonewhocares.org.raw] |
| Adaway original | Blocklist padrão distribuída com o AdAway | [Link][Adaway original] | CC BY 3.0 | [Raw][Adaway original.raw] |
| BLOCK SPOTIFY SERVERS | Bloqueio de servidores de anúncio do Spotify | - | - | [Raw][BLOCK SPOTIFY SERVERS.raw] |

### full

Arquivo: [`lists/full.txt`](lists/full.txt) — 85 fonte(s) ativas, 2190397 regras após deduplicação. Atualizado em **2026-07-12**.

| Blocklist | Descrição | Homepage | Licença | Raw |
|---|---|---|---|---|
| AdGuard DNS filter | Filtro combinado da AdGuard para bloqueio via DNS | [Link][AdGuard DNS filter] | GPLv3 | [Raw][AdGuard DNS filter.raw] |
| AdAway Default Blocklist | Blocklist padrão distribuída com o AdAway | [Link][AdAway Default Blocklist] | CC BY 3.0 | [Raw][AdAway Default Blocklist.raw] |
| Dandelion Sprout's Anti Push Notifications | Bloqueio de solicitações de notificações push | [Link][Dandelion Sprout's Anti Push Notifications] | Dandelicence v1.4 | [Raw][Dandelion Sprout's Anti Push Notifications.raw] |
| WindowsSpyBlocker - Hosts spy rules | Regras para bloquear telemetria/spyware do Windows | [Link][WindowsSpyBlocker - Hosts spy rules] | MIT | [Raw][WindowsSpyBlocker - Hosts spy rules.raw] |
| CHN: AdRules DNS List | - | - | - | [Raw][CHN: AdRules DNS List.raw] |
| CHN: anti-AD | - | - | - | [Raw][CHN: anti-AD.raw] |
| HUN: Hufilter | - | - | - | [Raw][HUN: Hufilter.raw] |
| IDN: ABPindo | - | - | - | [Raw][IDN: ABPindo.raw] |
| IRN: PersianBlocker list | - | - | - | [Raw][IRN: PersianBlocker list.raw] |
| KOR: List-KR DNS | - | - | - | [Raw][KOR: List-KR DNS.raw] |
| KOR: YousList | - | - | - | [Raw][KOR: YousList.raw] |
| VNM: ABPVN List | - | - | - | [Raw][VNM: ABPVN List.raw] |
| TUR: Turkish Ad Hosts | - | - | - | [Raw][TUR: Turkish Ad Hosts.raw] |
| TUR: turk-adlist | - | - | - | [Raw][TUR: turk-adlist.raw] |
| SWE: Frellwit's Swedish Hosts File | - | - | - | [Raw][SWE: Frellwit's Swedish Hosts File.raw] |
| POL: Polish filters for Pi-hole | - | - | - | [Raw][POL: Polish filters for Pi-hole.raw] |
| POL: CERT Polska List of malicious domains | Lista de domínios maliciosos do CERT Polska | [Link][POL: CERT Polska List of malicious domains] | - | [Raw][POL: CERT Polska List of malicious domains.raw] |
| NOR: Dandelion Sprouts nordiske filtre | - | - | - | [Raw][NOR: Dandelion Sprouts nordiske filtre.raw] |
| MKD: Macedonian Pi-hole Blocklist | - | - | - | [Raw][MKD: Macedonian Pi-hole Blocklist.raw] |
| LIT: EasyList Lithuania | - | - | - | [Raw][LIT: EasyList Lithuania.raw] |
| Phishing URL Blocklist (PhishTank and OpenPhish) | - | - | - | [Raw][Phishing URL Blocklist (PhishTank and OpenPhish).raw] |
| Dandelion Sprout's Anti-Malware List | - | - | - | [Raw][Dandelion Sprout's Anti-Malware List.raw] |
| NoCoin Filter List | Bloqueio de mineração de criptomoedas via navegador | [Link][NoCoin Filter List] | MIT | [Raw][NoCoin Filter List.raw] |
| Scam Blocklist by DurableNapkin | - | - | - | [Raw][Scam Blocklist by DurableNapkin.raw] |
| ShadowWhisperer's Malware List | - | - | - | [Raw][ShadowWhisperer's Malware List.raw] |
| Stalkerware Indicators List | Indicadores de apps de stalkerware (monitoramento não consentido) | [Link][Stalkerware Indicators List] | - | [Raw][Stalkerware Indicators List.raw] |
| Malicious URL Blocklist (URLHaus) | - | - | - | [Raw][Malicious URL Blocklist (URLHaus).raw] |
| The Big List of Hacked Malware Web Sites | - | - | - | [Raw][The Big List of Hacked Malware Web Sites.raw] |
| Perflyst and Dandelion Sprout's Smart-TV Blocklist | Telemetria/anúncios de Smart TVs e consoles | [Link][Perflyst and Dandelion Sprout's Smart-TV Blocklist] | - | [Raw][Perflyst and Dandelion Sprout's Smart-TV Blocklist.raw] |
| Dandelion Sprout's Game Console Adblock List | Bloqueio de anúncios em consoles de videogame | [Link][Dandelion Sprout's Game Console Adblock List] | Dandelicence v1.4 | [Raw][Dandelion Sprout's Game Console Adblock List.raw] |
| Steven Black's List | Combinação de ads+malware mantida por Steven Black | [Link][Steven Black's List] | MIT | [Raw][Steven Black's List.raw] |
| Peter Lowe's Blocklist | Blocklist de servidores de anúncios mantida desde os anos 2000 | [Link][Peter Lowe's Blocklist] | CC BY-SA 4.0 | [Raw][Peter Lowe's Blocklist.raw] |
| OISD Blocklist Big | OISD Big — lista genérica agressiva (ads+tracking+malware) | [Link][OISD Blocklist Big] | Uso não comercial — ver oisd.nl/pages/faq | [Raw][OISD Blocklist Big.raw] |
| OISD Blocklist Small | OISD Small — versão enxuta do OISD | [Link][OISD Blocklist Small] | Uso não comercial — ver oisd.nl/pages/faq | [Raw][OISD Blocklist Small.raw] |
| The NoTracking blocklist | NoTracking — bloqueio de telemetria e rastreadores diversos | [Link][The NoTracking blocklist] | GPLv3 | [Raw][The NoTracking blocklist.raw] |
| HaGeZi Multi NORMAL | HaGeZi Multi NORMAL — combinação de ads/tracking/malware | [Link][HaGeZi Multi NORMAL] | MIT | [Raw][HaGeZi Multi NORMAL.raw] |
| Dan Pollock's List | Lista hosts de Dan Pollock (someonewhocares.org) | [Link][Dan Pollock's List] | Uso pessoal livre | [Raw][Dan Pollock's List.raw] |
| 1Hosts (Lite) | Versão enxuta do 1Hosts | [Link][1Hosts (Lite)] | MIT | [Raw][1Hosts (Lite).raw] |
| StevenBlack/hosts Pi-Hole | Combinação de ads+malware mantida por Steven Black | [Link][StevenBlack/hosts Pi-Hole] | MIT | [Raw][StevenBlack/hosts Pi-Hole.raw] |
| AWAvenue Ads Rule | AWAvenue Ads Rule — foco em apps/sites chineses | [Link][AWAvenue Ads Rule] | GPLv3 | [Raw][AWAvenue Ads Rule.raw] |
| HaGeZi's Pro Blocklist | HaGeZi Pro — bloqueio balanceado de ads/tracking/telemetria | [Link][HaGeZi's Pro Blocklist] | MIT | [Raw][HaGeZi's Pro Blocklist.raw] |
| HaGeZi's Pro++ Blocklist | HaGeZi Pro++ — mais agressivo que o Pro | [Link][HaGeZi's Pro++ Blocklist] | MIT | [Raw][HaGeZi's Pro++ Blocklist.raw] |
| HaGeZi's Ultimate Blocklist | HaGeZi Ultimate — o mais agressivo da série HaGeZi | [Link][HaGeZi's Ultimate Blocklist] | MIT | [Raw][HaGeZi's Ultimate Blocklist.raw] |
| HaGeZi's Threat Intelligence Feeds | HaGeZi Threat Intelligence Feeds | [Link][HaGeZi's Threat Intelligence Feeds] | MIT | [Raw][HaGeZi's Threat Intelligence Feeds.raw] |
| Phishing Army | - | - | - | [Raw][Phishing Army.raw] |
| uBlock₀ filters – Badware risks | - | - | - | [Raw][uBlock₀ filters – Badware risks.raw] |
| BLOCK SPOTIFY SERVERS | Bloqueio de servidores de anúncio do Spotify | - | - | [Raw][BLOCK SPOTIFY SERVERS.raw] |
| Adblock Plus - Unusual Ads | - | - | - | [Raw][Adblock Plus - Unusual Ads.raw] |
| add.Risk | Websites with risk content, malwares etc | [Link][add.Risk] | GPLv3+ | [Raw][add.Risk.raw] |
| Anti Malware List (alt) | DandelionSprout's Anti Malware Filter | [Link][Anti Malware List (alt)] | Dandelicence v1.4 | [Raw][Anti Malware List (alt).raw] |
| Anti-Malware Blocklists (notrack) | NoTrack project Anti-Malware Blocklists | [Link][Anti-Malware Blocklists (notrack)] | GPLv3 | [Raw][Anti-Malware Blocklists (notrack).raw] |
| Badd-Boyz-Hosts | A hosts file to block bad domains | [Link][Badd-Boyz-Hosts] | MIT | [Raw][Badd-Boyz-Hosts.raw] |
| blackbook | Blackbook of malware domains | [Link][blackbook] | Public Domain | [Raw][blackbook.raw] |
| eth-phishing-detect | Phishing domains targeting Ethereum users | [Link][eth-phishing-detect] | DON'T BE A DICK PUBLIC LICENSE | [Raw][eth-phishing-detect.raw] |
| Fraud block list | Lists of sites created to fraud | [Link][Fraud block list] | The Unlicense | [Raw][Fraud block list.raw] |
| GlobalAntiScamOrg-blocklist | Global Anti Scam Organization blocklist | [Link][GlobalAntiScamOrg-blocklist] | BSD-3-Clause | [Raw][GlobalAntiScamOrg-blocklist.raw] |
| OpenPhish | Phishing Intelligence (mirror do feed público, mais estável que openphish.com direto) | [Link][OpenPhish] | All rights reserved | [Raw][OpenPhish.raw] |
| Phishing Army Extended | The Extended Blocklist to filter Phishing | [Link][Phishing Army Extended] | CC BY-NC 4.0 | [Raw][Phishing Army Extended.raw] |
| Ransomware block list | Known sites that host or contain ransomware | [Link][Ransomware block list] | The Unlicense | [Raw][Ransomware block list.raw] |
| URLhaus | A project to share malicious URLs | [Link][URLhaus] | CC0 | [Raw][URLhaus.raw] |
| SPY BOT MCLX | ANTI-SPY HOSTS | [Link][SPY BOT MCLX] | - | [Raw][SPY BOT MCLX.raw] |
| EasyList Portuguese + EasyList | EasyList + EasyList Portuguese combinados | [Link][EasyList Portuguese + EasyList] | GPLv3 | [Raw][EasyList Portuguese + EasyList.raw] |
| Anti-Circumvention Filters | Filtros anti-circunvenção de bloqueadores de anúncio | [Link][Anti-Circumvention Filters] | GPLv3 | [Raw][Anti-Circumvention Filters.raw] |
| uBlock filters (2024) | Filtros gerais do uBlock Origin (safra 2024) | [Link][uBlock filters (2024)] | GPLv3 | [Raw][uBlock filters (2024).raw] |
| uBlock filters – Mobile | Filtros do uBlock Origin específicos para mobile | [Link][uBlock filters – Mobile] | GPLv3 | [Raw][uBlock filters – Mobile.raw] |
| uBlock filters – Cookie Notices | Avisos de cookies (annoyances) do uBlock Origin | [Link][uBlock filters – Cookie Notices] | GPLv3 | [Raw][uBlock filters – Cookie Notices.raw] |
| Online Malicious URL Blocklist (AdGuard) | Malicious URL blocklist baseado no URLhaus, formato AdGuard Home | [Link][Online Malicious URL Blocklist (AdGuard)] | CC BY-SA 4.0 | [Raw][Online Malicious URL Blocklist (AdGuard).raw] |
| Smart-TV Blocklist for AdGuard Home | Telemetria de Smart TVs, formato AdGuard Home | [Link][Smart-TV Blocklist for AdGuard Home] | - | [Raw][Smart-TV Blocklist for AdGuard Home.raw] |
| VeleSila | Blocklist hosts geral | [Link][VeleSila] | - | [Raw][VeleSila.raw] |
| Adaway original | Blocklist padrão distribuída com o AdAway | [Link][Adaway original] | CC BY 3.0 | [Raw][Adaway original.raw] |
| MobileFilter | Regras específicas para apps mobile | [Link][MobileFilter] | GPLv3 | [Raw][MobileFilter.raw] |
| someonewhocares.org | Lista hosts de Dan Pollock | [Link][someonewhocares.org] | Uso pessoal livre | [Raw][someonewhocares.org.raw] |
| Adblock Plus (Anti-Adblock) | Filtros contra avisos de 'desative seu adblock' | [Link][Adblock Plus (Anti-Adblock)] | GPLv3 | [Raw][Adblock Plus (Anti-Adblock).raw] |
| Fanboy Cookiemonster | Bloqueio de avisos de cookies (Fanboy) | [Link][Fanboy Cookiemonster] | GPLv3 | [Raw][Fanboy Cookiemonster.raw] |
| Firebog - Easyprivacy | Mirror do EasyPrivacy (bloqueio de rastreadores) | [Link][Firebog - Easyprivacy] | GPLv3 | [Raw][Firebog - Easyprivacy.raw] |
| Phishing URL Blocklist (AdGuard Home) | PhishTank/OpenPhish/Cert.pl based blocklist, formato AdGuard Home | [Link][Phishing URL Blocklist (AdGuard Home)] | CC BY-SA 4.0 | [Raw][Phishing URL Blocklist (AdGuard Home).raw] |
| URLhaus Host file | A project to share malicious URLs (via StevenBlack/hosts) | [Link][URLhaus Host file] | CC0 | [Raw][URLhaus Host file.raw] |
| Steven Black (data) | Combinação de ads+malware mantida por Steven Black | [Link][Steven Black (data)] | MIT | [Raw][Steven Black (data).raw] |
| ph00lt0 - Blocklist | Blocklist geral mantida pela comunidade | [Link][ph00lt0 - Blocklist] | - | [Raw][ph00lt0 - Blocklist.raw] |
| HaGeZi's Pop-Up Ads DNS Blocklist | HaGeZi Pop-Up Ads DNS Blocklist | [Link][HaGeZi's Pop-Up Ads DNS Blocklist] | MIT | [Raw][HaGeZi's Pop-Up Ads DNS Blocklist.raw] |
| uBlockOrigin filters.txt | Filtros gerais do uBlock Origin | [Link][uBlockOrigin filters.txt] | GPLv3 | [Raw][uBlockOrigin filters.txt.raw] |
| Fanboy Annoyance | Bloqueio de pop-ups e elementos irritantes (Fanboy) | [Link][Fanboy Annoyance] | GPLv3 | [Raw][Fanboy Annoyance.raw] |
| uBlockOrigin quick-fixes | Correções rápidas do uBlock Origin | [Link][uBlockOrigin quick-fixes] | GPLv3 | [Raw][uBlockOrigin quick-fixes.raw] |
| fanboy-social | Bloqueio de widgets de redes sociais (Fanboy) | [Link][fanboy-social] | GPLv3 | [Raw][fanboy-social.raw] |
| Adblock Plus (Exceptions/Allowlist) | Lista de exceções/allowlist padrão do Adblock Plus | [Link][Adblock Plus (Exceptions/Allowlist)] | GPLv3 | [Raw][Adblock Plus (Exceptions/Allowlist).raw] |

### lite

Arquivo: [`lists/lite.txt`](lists/lite.txt) — 6 fonte(s) ativas, 334511 regras após deduplicação. Atualizado em **2026-07-12**.

| Blocklist | Descrição | Homepage | Licença | Raw |
|---|---|---|---|---|
| AdGuard DNS filter | Filtro combinado da AdGuard para bloqueio via DNS | [Link][AdGuard DNS filter] | GPLv3 | [Raw][AdGuard DNS filter.raw] |
| OISD Blocklist Small | OISD Small — versão enxuta do OISD | [Link][OISD Blocklist Small] | Uso não comercial — ver oisd.nl/pages/faq | [Raw][OISD Blocklist Small.raw] |
| 1Hosts (Lite) | Versão enxuta do 1Hosts | [Link][1Hosts (Lite)] | MIT | [Raw][1Hosts (Lite).raw] |
| Peter Lowe's Blocklist | Blocklist de servidores de anúncios mantida desde os anos 2000 | [Link][Peter Lowe's Blocklist] | CC BY-SA 4.0 | [Raw][Peter Lowe's Blocklist.raw] |
| HaGeZi's Pro Blocklist | HaGeZi Pro — bloqueio balanceado de ads/tracking/telemetria | [Link][HaGeZi's Pro Blocklist] | MIT | [Raw][HaGeZi's Pro Blocklist.raw] |
| Dan Pollock's List | Lista hosts de Dan Pollock (someonewhocares.org) | [Link][Dan Pollock's List] | Uso pessoal livre | [Raw][Dan Pollock's List.raw] |

### malware

Arquivo: [`lists/malware.txt`](lists/malware.txt) — 17 fonte(s) ativas, 1531281 regras após deduplicação. Atualizado em **2026-07-12**.

| Blocklist | Descrição | Homepage | Licença | Raw |
|---|---|---|---|---|
| ShadowWhisperer's Malware List | - | - | - | [Raw][ShadowWhisperer's Malware List.raw] |
| Dandelion Sprout's Anti-Malware List | - | - | - | [Raw][Dandelion Sprout's Anti-Malware List.raw] |
| Malicious URL Blocklist (URLHaus) | - | - | - | [Raw][Malicious URL Blocklist (URLHaus).raw] |
| The Big List of Hacked Malware Web Sites | - | - | - | [Raw][The Big List of Hacked Malware Web Sites.raw] |
| POL: CERT Polska List of malicious domains | Lista de domínios maliciosos do CERT Polska | [Link][POL: CERT Polska List of malicious domains] | - | [Raw][POL: CERT Polska List of malicious domains.raw] |
| HaGeZi's Threat Intelligence Feeds | HaGeZi Threat Intelligence Feeds | [Link][HaGeZi's Threat Intelligence Feeds] | MIT | [Raw][HaGeZi's Threat Intelligence Feeds.raw] |
| uBlock₀ filters – Badware risks | - | - | - | [Raw][uBlock₀ filters – Badware risks.raw] |
| add.Risk | Websites with risk content, malwares etc | [Link][add.Risk] | GPLv3+ | [Raw][add.Risk.raw] |
| Anti Malware List (alt) | DandelionSprout's Anti Malware Filter | [Link][Anti Malware List (alt)] | Dandelicence v1.4 | [Raw][Anti Malware List (alt).raw] |
| Anti-Malware Blocklists (notrack) | NoTrack project Anti-Malware Blocklists | [Link][Anti-Malware Blocklists (notrack)] | GPLv3 | [Raw][Anti-Malware Blocklists (notrack).raw] |
| Badd-Boyz-Hosts | A hosts file to block bad domains | [Link][Badd-Boyz-Hosts] | MIT | [Raw][Badd-Boyz-Hosts.raw] |
| blackbook | Blackbook of malware domains | [Link][blackbook] | Public Domain | [Raw][blackbook.raw] |
| Ransomware block list | Known sites that host or contain ransomware | [Link][Ransomware block list] | The Unlicense | [Raw][Ransomware block list.raw] |
| URLhaus | A project to share malicious URLs | [Link][URLhaus] | CC0 | [Raw][URLhaus.raw] |
| URLhaus Host file | A project to share malicious URLs (via StevenBlack/hosts) | [Link][URLhaus Host file] | CC0 | [Raw][URLhaus Host file.raw] |
| Online Malicious URL Blocklist (AdGuard) | Malicious URL blocklist baseado no URLhaus, formato AdGuard Home | [Link][Online Malicious URL Blocklist (AdGuard)] | CC BY-SA 4.0 | [Raw][Online Malicious URL Blocklist (AdGuard).raw] |
| SPY BOT MCLX | ANTI-SPY HOSTS | [Link][SPY BOT MCLX] | - | [Raw][SPY BOT MCLX.raw] |

### phishing

Arquivo: [`lists/phishing.txt`](lists/phishing.txt) — 9 fonte(s) ativas, 280490 regras após deduplicação. Atualizado em **2026-07-12**.

| Blocklist | Descrição | Homepage | Licença | Raw |
|---|---|---|---|---|
| Phishing URL Blocklist (PhishTank and OpenPhish) | - | - | - | [Raw][Phishing URL Blocklist (PhishTank and OpenPhish).raw] |
| Scam Blocklist by DurableNapkin | - | - | - | [Raw][Scam Blocklist by DurableNapkin.raw] |
| Phishing Army | - | - | - | [Raw][Phishing Army.raw] |
| eth-phishing-detect | Phishing domains targeting Ethereum users | [Link][eth-phishing-detect] | DON'T BE A DICK PUBLIC LICENSE | [Raw][eth-phishing-detect.raw] |
| Fraud block list | Lists of sites created to fraud | [Link][Fraud block list] | The Unlicense | [Raw][Fraud block list.raw] |
| GlobalAntiScamOrg-blocklist | Global Anti Scam Organization blocklist | [Link][GlobalAntiScamOrg-blocklist] | BSD-3-Clause | [Raw][GlobalAntiScamOrg-blocklist.raw] |
| OpenPhish | Phishing Intelligence (mirror do feed público, mais estável que openphish.com direto) | [Link][OpenPhish] | All rights reserved | [Raw][OpenPhish.raw] |
| Phishing Army Extended | The Extended Blocklist to filter Phishing | [Link][Phishing Army Extended] | CC BY-NC 4.0 | [Raw][Phishing Army Extended.raw] |
| Phishing URL Blocklist (AdGuard Home) | PhishTank/OpenPhish/Cert.pl based blocklist, formato AdGuard Home | [Link][Phishing URL Blocklist (AdGuard Home)] | CC BY-SA 4.0 | [Raw][Phishing URL Blocklist (AdGuard Home).raw] |

### privacy

Arquivo: [`lists/privacy.txt`](lists/privacy.txt) — 8 fonte(s) ativas, 448045 regras após deduplicação. Atualizado em **2026-07-12**.

| Blocklist | Descrição | Homepage | Licença | Raw |
|---|---|---|---|---|
| WindowsSpyBlocker - Hosts spy rules | Regras para bloquear telemetria/spyware do Windows | [Link][WindowsSpyBlocker - Hosts spy rules] | MIT | [Raw][WindowsSpyBlocker - Hosts spy rules.raw] |
| Stalkerware Indicators List | Indicadores de apps de stalkerware (monitoramento não consentido) | [Link][Stalkerware Indicators List] | - | [Raw][Stalkerware Indicators List.raw] |
| The NoTracking blocklist | NoTracking — bloqueio de telemetria e rastreadores diversos | [Link][The NoTracking blocklist] | GPLv3 | [Raw][The NoTracking blocklist.raw] |
| Firebog - Easyprivacy | Mirror do EasyPrivacy (bloqueio de rastreadores) | [Link][Firebog - Easyprivacy] | GPLv3 | [Raw][Firebog - Easyprivacy.raw] |
| Perflyst and Dandelion Sprout's Smart-TV Blocklist | Telemetria/anúncios de Smart TVs e consoles | [Link][Perflyst and Dandelion Sprout's Smart-TV Blocklist] | - | [Raw][Perflyst and Dandelion Sprout's Smart-TV Blocklist.raw] |
| Smart-TV Blocklist for AdGuard Home | Telemetria de Smart TVs, formato AdGuard Home | [Link][Smart-TV Blocklist for AdGuard Home] | - | [Raw][Smart-TV Blocklist for AdGuard Home.raw] |
| Dandelion Sprout's Anti Push Notifications | Bloqueio de solicitações de notificações push | [Link][Dandelion Sprout's Anti Push Notifications] | Dandelicence v1.4 | [Raw][Dandelion Sprout's Anti Push Notifications.raw] |
| SPY BOT MCLX | ANTI-SPY HOSTS | [Link][SPY BOT MCLX] | - | [Raw][SPY BOT MCLX.raw] |

### social

Arquivo: [`lists/social.txt`](lists/social.txt) — 2 fonte(s) ativas, 457 regras após deduplicação. Atualizado em **2026-07-12**.

| Blocklist | Descrição | Homepage | Licença | Raw |
|---|---|---|---|---|
| fanboy-social | Bloqueio de widgets de redes sociais (Fanboy) | [Link][fanboy-social] | GPLv3 | [Raw][fanboy-social.raw] |
| BLOCK SPOTIFY SERVERS | Bloqueio de servidores de anúncio do Spotify | - | - | [Raw][BLOCK SPOTIFY SERVERS.raw] |

### trackers

Arquivo: [`lists/trackers.txt`](lists/trackers.txt) — 7 fonte(s) ativas, 273359 regras após deduplicação. Atualizado em **2026-07-12**.

| Blocklist | Descrição | Homepage | Licença | Raw |
|---|---|---|---|---|
| NoCoin Filter List | Bloqueio de mineração de criptomoedas via navegador | [Link][NoCoin Filter List] | MIT | [Raw][NoCoin Filter List.raw] |
| uBlock filters – Cookie Notices | Avisos de cookies (annoyances) do uBlock Origin | [Link][uBlock filters – Cookie Notices] | GPLv3 | [Raw][uBlock filters – Cookie Notices.raw] |
| Fanboy Cookiemonster | Bloqueio de avisos de cookies (Fanboy) | [Link][Fanboy Cookiemonster] | GPLv3 | [Raw][Fanboy Cookiemonster.raw] |
| Fanboy Annoyance | Bloqueio de pop-ups e elementos irritantes (Fanboy) | [Link][Fanboy Annoyance] | GPLv3 | [Raw][Fanboy Annoyance.raw] |
| HaGeZi Multi NORMAL | HaGeZi Multi NORMAL — combinação de ads/tracking/malware | [Link][HaGeZi Multi NORMAL] | MIT | [Raw][HaGeZi Multi NORMAL.raw] |
| HaGeZi's Pro++ Blocklist | HaGeZi Pro++ — mais agressivo que o Pro | [Link][HaGeZi's Pro++ Blocklist] | MIT | [Raw][HaGeZi's Pro++ Blocklist.raw] |
| HaGeZi's Ultimate Blocklist | HaGeZi Ultimate — o mais agressivo da série HaGeZi | [Link][HaGeZi's Ultimate Blocklist] | MIT | [Raw][HaGeZi's Ultimate Blocklist.raw] |

---
_Gerado automaticamente por `entrypoint.sh` — não editar manualmente, as alterações serão sobrescritas na próxima execução._

[1Hosts (Lite).raw]: https://adguardteam.github.io/HostlistsRegistry/assets/filter_24.txt
[1Hosts (Lite)]: https://github.com/badmojr/1Hosts
[AWAvenue Ads Rule.raw]: https://adguardteam.github.io/HostlistsRegistry/assets/filter_53.txt
[AWAvenue Ads Rule]: https://github.com/TG-Twilight/AWAvenue-Ads-Rule
[AdAway Default Blocklist.raw]: https://adguardteam.github.io/HostlistsRegistry/assets/filter_2.txt
[AdAway Default Blocklist]: https://adaway.org/
[AdGuard DNS filter.raw]: https://adguardteam.github.io/HostlistsRegistry/assets/filter_1.txt
[AdGuard DNS filter]: https://github.com/AdguardTeam/AdguardFilters
[Adaway original.raw]: https://adaway.org/hosts.txt
[Adaway original]: https://adaway.org/
[Adblock Plus (Anti-Adblock).raw]: https://easylist-downloads.adblockplus.org/antiadblockfilters.txt
[Adblock Plus (Anti-Adblock)]: https://easylist.to/
[Adblock Plus (Exceptions/Allowlist).raw]: https://easylist-downloads.adblockplus.org/exceptionrules.txt
[Adblock Plus (Exceptions/Allowlist)]: https://easylist.to/
[Adblock Plus - Unusual Ads.raw]: https://raw.githubusercontent.com/DandelionSprout/adfilt/master/AdRemovalListForUnusualAds.txt
[Anti Malware List (alt).raw]: https://raw.githubusercontent.com/DandelionSprout/adfilt/master/Alternate%20versions%20Anti-Malware%20List/AntiMalwareHosts.txt
[Anti Malware List (alt)]: https://github.com/DandelionSprout/adfilt
[Anti-Circumvention Filters.raw]: https://easylist-downloads.adblockplus.org/abp-filters-anti-cv.txt
[Anti-Circumvention Filters]: https://easylist.to/
[Anti-Malware Blocklists (notrack).raw]: https://gitlab.com/quidsup/notrack-blocklists/raw/master/notrack-malware.txt
[Anti-Malware Blocklists (notrack)]: https://gitlab.com/quidsup/notrack-blocklists
[BLOCK SPOTIFY SERVERS.raw]: https://gist.githubusercontent.com/opus-x/3e673a9d5db2a214df05929a4eee6a57/raw/162f2fe3ba71c010ea195de0feb261561cfd5672/Spotify_Eliminate_Advertisements
[Badd-Boyz-Hosts.raw]: https://raw.githubusercontent.com/mitchellkrogza/Badd-Boyz-Hosts/master/hosts
[Badd-Boyz-Hosts]: https://github.com/mitchellkrogza/Badd-Boyz-Hosts/
[CHN: AdRules DNS List.raw]: https://adguardteam.github.io/HostlistsRegistry/assets/filter_29.txt
[CHN: anti-AD.raw]: https://adguardteam.github.io/HostlistsRegistry/assets/filter_21.txt
[Dan Pollock's List.raw]: https://adguardteam.github.io/HostlistsRegistry/assets/filter_4.txt
[Dan Pollock's List]: https://someonewhocares.org/hosts/
[Dandelion Sprout's Anti Push Notifications.raw]: https://adguardteam.github.io/HostlistsRegistry/assets/filter_39.txt
[Dandelion Sprout's Anti Push Notifications]: https://github.com/DandelionSprout/adfilt
[Dandelion Sprout's Anti-Malware List.raw]: https://adguardteam.github.io/HostlistsRegistry/assets/filter_12.txt
[Dandelion Sprout's Game Console Adblock List.raw]: https://adguardteam.github.io/HostlistsRegistry/assets/filter_6.txt
[Dandelion Sprout's Game Console Adblock List]: https://github.com/DandelionSprout/adfilt
[EasyList Portuguese + EasyList.raw]: https://easylist-downloads.adblockplus.org/easylistportuguese+easylist.txt
[EasyList Portuguese + EasyList]: https://easylist.to/
[Fanboy Annoyance.raw]: https://secure.fanboy.co.nz/fanboy-annoyance.txt
[Fanboy Annoyance]: https://www.fanboy.co.nz/
[Fanboy Cookiemonster.raw]: https://secure.fanboy.co.nz/fanboy-cookiemonster.txt
[Fanboy Cookiemonster]: https://www.fanboy.co.nz/
[Firebog - Easyprivacy.raw]: https://v.firebog.net/hosts/Easyprivacy.txt
[Firebog - Easyprivacy]: https://easylist.to/
[Fraud block list.raw]: https://blocklistproject.github.io/Lists/fraud.txt
[Fraud block list]: https://github.com/blocklistproject/Lists/
[GlobalAntiScamOrg-blocklist.raw]: https://raw.githubusercontent.com/elliotwutingfeng/GlobalAntiScamOrg-blocklist/main/global-anti-scam-org-scam-urls-pihole.txt
[GlobalAntiScamOrg-blocklist]: https://github.com/elliotwutingfeng/GlobalAntiScamOrg-blocklist
[HUN: Hufilter.raw]: https://adguardteam.github.io/HostlistsRegistry/assets/filter_35.txt
[HaGeZi Multi NORMAL.raw]: https://adguardteam.github.io/HostlistsRegistry/assets/filter_34.txt
[HaGeZi Multi NORMAL]: https://github.com/hagezi/dns-blocklists
[HaGeZi's Pop-Up Ads DNS Blocklist.raw]: https://raw.githubusercontent.com/hagezi/dns-blocklists/refs/heads/main/adblock/popupads.txt
[HaGeZi's Pop-Up Ads DNS Blocklist]: https://github.com/hagezi/dns-blocklists
[HaGeZi's Pro Blocklist.raw]: https://adguardteam.github.io/HostlistsRegistry/assets/filter_48.txt
[HaGeZi's Pro Blocklist]: https://github.com/hagezi/dns-blocklists
[HaGeZi's Pro++ Blocklist.raw]: https://adguardteam.github.io/HostlistsRegistry/assets/filter_51.txt
[HaGeZi's Pro++ Blocklist]: https://github.com/hagezi/dns-blocklists
[HaGeZi's Threat Intelligence Feeds.raw]: https://adguardteam.github.io/HostlistsRegistry/assets/filter_44.txt
[HaGeZi's Threat Intelligence Feeds]: https://github.com/hagezi/dns-blocklists
[HaGeZi's Ultimate Blocklist.raw]: https://adguardteam.github.io/HostlistsRegistry/assets/filter_49.txt
[HaGeZi's Ultimate Blocklist]: https://github.com/hagezi/dns-blocklists
[IDN: ABPindo.raw]: https://adguardteam.github.io/HostlistsRegistry/assets/filter_22.txt
[IRN: PersianBlocker list.raw]: https://adguardteam.github.io/HostlistsRegistry/assets/filter_19.txt
[KOR: List-KR DNS.raw]: https://adguardteam.github.io/HostlistsRegistry/assets/filter_25.txt
[KOR: YousList.raw]: https://adguardteam.github.io/HostlistsRegistry/assets/filter_15.txt
[LIT: EasyList Lithuania.raw]: https://adguardteam.github.io/HostlistsRegistry/assets/filter_36.txt
[MKD: Macedonian Pi-hole Blocklist.raw]: https://adguardteam.github.io/HostlistsRegistry/assets/filter_20.txt
[Malicious URL Blocklist (URLHaus).raw]: https://adguardteam.github.io/HostlistsRegistry/assets/filter_11.txt
[MobileFilter.raw]: https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/MobileFilter/sections/specific_app.txt
[MobileFilter]: https://github.com/AdguardTeam/AdguardFilters
[NOR: Dandelion Sprouts nordiske filtre.raw]: https://adguardteam.github.io/HostlistsRegistry/assets/filter_13.txt
[NoCoin Filter List.raw]: https://adguardteam.github.io/HostlistsRegistry/assets/filter_8.txt
[NoCoin Filter List]: https://github.com/hoshsadiq/adblock-nocoin-list
[OISD Blocklist Big.raw]: https://adguardteam.github.io/HostlistsRegistry/assets/filter_27.txt
[OISD Blocklist Big]: https://oisd.nl/
[OISD Blocklist Small.raw]: https://adguardteam.github.io/HostlistsRegistry/assets/filter_5.txt
[OISD Blocklist Small]: https://oisd.nl/
[Online Malicious URL Blocklist (AdGuard).raw]: https://malware-filter.gitlab.io/malware-filter/urlhaus-filter-agh.txt
[Online Malicious URL Blocklist (AdGuard)]: https://gitlab.com/malware-filter/urlhaus-filter
[OpenPhish.raw]: https://raw.githubusercontent.com/openphish/public_feed/refs/heads/main/feed.txt
[OpenPhish]: https://openphish.com/
[POL: CERT Polska List of malicious domains.raw]: https://adguardteam.github.io/HostlistsRegistry/assets/filter_41.txt
[POL: CERT Polska List of malicious domains]: https://cert.pl/en/posts/2020/03/malicious_domains/
[POL: Polish filters for Pi-hole.raw]: https://adguardteam.github.io/HostlistsRegistry/assets/filter_14.txt
[Perflyst and Dandelion Sprout's Smart-TV Blocklist.raw]: https://adguardteam.github.io/HostlistsRegistry/assets/filter_7.txt
[Perflyst and Dandelion Sprout's Smart-TV Blocklist]: https://github.com/Perflyst/PiHoleBlocklist
[Peter Lowe's Blocklist.raw]: https://adguardteam.github.io/HostlistsRegistry/assets/filter_3.txt
[Peter Lowe's Blocklist]: https://pgl.yoyo.org/adservers/
[Phishing Army Extended.raw]: https://phishing.army/download/phishing_army_blocklist_extended.txt
[Phishing Army Extended]: https://www.phishing.army/
[Phishing Army.raw]: https://adguardteam.github.io/HostlistsRegistry/assets/filter_18.txt
[Phishing URL Blocklist (AdGuard Home).raw]: https://malware-filter.gitlab.io/malware-filter/phishing-filter-agh.txt
[Phishing URL Blocklist (AdGuard Home)]: https://gitlab.com/malware-filter/phishing-filter
[Phishing URL Blocklist (PhishTank and OpenPhish).raw]: https://adguardteam.github.io/HostlistsRegistry/assets/filter_30.txt
[Ransomware block list.raw]: https://blocklistproject.github.io/Lists/ransomware.txt
[Ransomware block list]: https://github.com/blocklistproject/Lists/
[SPY BOT MCLX.raw]: https://raw.githubusercontent.com/protexdefense/adguard-all-list/refs/heads/main/filter_anti-spy.txt
[SPY BOT MCLX]: https://github.com/protexdefense/adguard-all-list
[SWE: Frellwit's Swedish Hosts File.raw]: https://adguardteam.github.io/HostlistsRegistry/assets/filter_17.txt
[Scam Blocklist by DurableNapkin.raw]: https://adguardteam.github.io/HostlistsRegistry/assets/filter_10.txt
[ShadowWhisperer's Malware List.raw]: https://adguardteam.github.io/HostlistsRegistry/assets/filter_42.txt
[Smart-TV Blocklist for AdGuard Home.raw]: https://raw.githubusercontent.com/Perflyst/PiHoleBlocklist/master/SmartTV-AGH.txt
[Smart-TV Blocklist for AdGuard Home]: https://github.com/Perflyst/PiHoleBlocklist
[Stalkerware Indicators List.raw]: https://adguardteam.github.io/HostlistsRegistry/assets/filter_31.txt
[Stalkerware Indicators List]: https://github.com/AssoEchap/stalkerware-indicators
[Steven Black (data).raw]: https://raw.githubusercontent.com/StevenBlack/hosts/refs/heads/master/data/StevenBlack/hosts
[Steven Black (data)]: https://github.com/StevenBlack/hosts
[Steven Black's List.raw]: https://adguardteam.github.io/HostlistsRegistry/assets/filter_33.txt
[Steven Black's List]: https://github.com/StevenBlack/hosts
[StevenBlack/hosts Pi-Hole.raw]: https://raw.githubusercontent.com/StevenBlack/hosts/master/hosts
[StevenBlack/hosts Pi-Hole]: https://github.com/StevenBlack/hosts
[TUR: Turkish Ad Hosts.raw]: https://adguardteam.github.io/HostlistsRegistry/assets/filter_40.txt
[TUR: turk-adlist.raw]: https://adguardteam.github.io/HostlistsRegistry/assets/filter_26.txt
[The Big List of Hacked Malware Web Sites.raw]: https://adguardteam.github.io/HostlistsRegistry/assets/filter_9.txt
[The NoTracking blocklist.raw]: https://adguardteam.github.io/HostlistsRegistry/assets/filter_32.txt
[The NoTracking blocklist]: https://github.com/notracking/hosts-blocklists
[URLhaus Host file.raw]: https://raw.githubusercontent.com/StevenBlack/hosts/refs/heads/master/data/URLHaus/hosts
[URLhaus Host file]: https://urlhaus.abuse.ch/
[URLhaus.raw]: https://urlhaus.abuse.ch/downloads/hostfile/
[URLhaus]: https://urlhaus.abuse.ch/
[VNM: ABPVN List.raw]: https://adguardteam.github.io/HostlistsRegistry/assets/filter_16.txt
[VeleSila.raw]: https://raw.githubusercontent.com/VeleSila/yhosts/master/hosts
[VeleSila]: https://github.com/VeleSila/yhosts
[WindowsSpyBlocker - Hosts spy rules.raw]: https://adguardteam.github.io/HostlistsRegistry/assets/filter_23.txt
[WindowsSpyBlocker - Hosts spy rules]: https://github.com/crazy-max/WindowsSpyBlocker
[add.Risk.raw]: https://raw.githubusercontent.com/FadeMind/hosts.extras/master/add.Risk/hosts
[add.Risk]: https://github.com/FadeMind/hosts.extras/
[blackbook.raw]: https://raw.githubusercontent.com/stamparm/blackbook/master/blackbook.txt
[blackbook]: https://github.com/stamparm/blackbook
[eth-phishing-detect.raw]: https://raw.githubusercontent.com/MetaMask/eth-phishing-detect/master/src/hosts.txt
[eth-phishing-detect]: https://github.com/MetaMask/eth-phishing-detect/
[fanboy-social.raw]: https://easylist.to/easylist/fanboy-social.txt
[fanboy-social]: https://www.fanboy.co.nz/
[ph00lt0 - Blocklist.raw]: https://raw.githubusercontent.com/ph00lt0/blocklist/master/blocklist.txt
[ph00lt0 - Blocklist]: https://github.com/ph00lt0/blocklist
[someonewhocares.org.raw]: https://someonewhocares.org/hosts/zero/hosts
[someonewhocares.org]: https://someonewhocares.org/hosts/
[uBlock filters (2024).raw]: https://raw.githubusercontent.com/uBlockOrigin/uAssets/master/filters/filters-2024.txt
[uBlock filters (2024)]: https://github.com/uBlockOrigin/uAssets
[uBlock filters – Cookie Notices.raw]: https://raw.githubusercontent.com/uBlockOrigin/uAssets/master/filters/annoyances-cookies.txt
[uBlock filters – Cookie Notices]: https://github.com/uBlockOrigin/uAssets
[uBlock filters – Mobile.raw]: https://raw.githubusercontent.com/uBlockOrigin/uAssets/master/filters/filters-mobile.txt
[uBlock filters – Mobile]: https://github.com/uBlockOrigin/uAssets
[uBlockOrigin filters.txt.raw]: https://raw.githubusercontent.com/uBlockOrigin/uAssets/refs/heads/master/filters/filters.txt
[uBlockOrigin filters.txt]: https://github.com/uBlockOrigin/uAssets
[uBlockOrigin quick-fixes.raw]: https://raw.githubusercontent.com/uBlockOrigin/uAssets/refs/heads/master/filters/quick-fixes.txt
[uBlockOrigin quick-fixes]: https://github.com/uBlockOrigin/uAssets
[uBlock₀ filters – Badware risks.raw]: https://adguardteam.github.io/HostlistsRegistry/assets/filter_50.txt
