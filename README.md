# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt  
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-40
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 марта
- Ссылка:
```bash
tg://proxy?server=s1.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## psb.hosting
- Локация: Finland
- Тариф: FI-200
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 12$
- Оплачен до: 25 марта
- Ссылка:
```bash
tg://proxy?server=s2.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## koara.io
- Локация: Германия, Франкфурт-на-Майне
- Тариф: DE-2
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 639 RUB
- Оплачен до: 25 марта
- Ссылка:
```bash
tg://proxy?server=s3.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## landvps.ru
- Локация: Финляндия
- Тариф: FL-2
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 200 Mbps/s
- Цена в месяц: 800 RUB
- Оплачен до: 26 марта
- Ссылка:
```bash
tg://proxy?server=s4.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## rdp-onedash.ru
- Локация: Нидерланды
- Тариф: Mini
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 844 RUB
- Оплачен до: 14 апреля
- Ссылка:
```bash
tg://proxy?server=s5.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## hostvds.com
- Локация: Нидерланды, Амстердам
- Тариф: Burstable
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 10 Gbit/s
- Цена в месяц: €7.98
- Оплачен до: 13 апреля
- Ссылка:
```bash
tg://proxy?server=s6.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-11 19:39:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 9573.2 (2h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 36600
telemt_connections_bad_total 2057
telemt_handshake_timeouts_total 139
telemt_upstream_connect_attempt_total 33031
telemt_upstream_connect_success_total 33022
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 33031
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29843
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3116
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 33020
telemt_user_connections_current{user="hello"} 301
telemt_user_octets_from_client{user="hello"} 824980669 (786.76 MB)
telemt_user_octets_to_client{user="hello"} 19458683217 (18.12 GB)
telemt_user_msgs_from_client{user="hello"} 832851
telemt_user_msgs_to_client{user="hello"} 1608558
telemt_user_unique_ips_current{user="hello"} 74
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 9561.6 (2h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17723
telemt_connections_bad_total 35
telemt_handshake_timeouts_total 248
telemt_upstream_connect_attempt_total 16269
telemt_upstream_connect_success_total 16251
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 16269
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13882
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2053
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 316
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 16249
telemt_user_connections_current{user="hello"} 161
telemt_user_octets_from_client{user="hello"} 209508064 (199.80 MB)
telemt_user_octets_to_client{user="hello"} 8674291069 (8.08 GB)
telemt_user_msgs_from_client{user="hello"} 345915
telemt_user_msgs_to_client{user="hello"} 3344462
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 9581.6 (2h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20368
telemt_connections_bad_total 25
telemt_handshake_timeouts_total 172
telemt_upstream_connect_attempt_total 19023
telemt_upstream_connect_success_total 19021
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 19023
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17330
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1673
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 19019
telemt_user_connections_current{user="hello"} 110
telemt_user_octets_from_client{user="hello"} 198179284 (189.00 MB)
telemt_user_octets_to_client{user="hello"} 8845256198 (8.24 GB)
telemt_user_msgs_from_client{user="hello"} 390277
telemt_user_msgs_to_client{user="hello"} 2185876
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 9576.8 (2h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 22291
telemt_connections_bad_total 1754
telemt_handshake_timeouts_total 374
telemt_upstream_connect_attempt_total 19226
telemt_upstream_connect_success_total 19167
telemt_upstream_connect_fail_total 59
telemt_upstream_connect_attempts_per_request{bucket="1"} 19226
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17350
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1754
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 59
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 19165
telemt_user_connections_current{user="hello"} 95
telemt_user_octets_from_client{user="hello"} 599669641 (571.89 MB)
telemt_user_octets_to_client{user="hello"} 10950227992 (10.20 GB)
telemt_user_msgs_from_client{user="hello"} 479664
telemt_user_msgs_to_client{user="hello"} 2954346
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 9585.0 (2h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23320
telemt_connections_bad_total 1844
telemt_handshake_timeouts_total 159
telemt_upstream_connect_attempt_total 20517
telemt_upstream_connect_success_total 20516
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 20517
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17916
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2575
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 20514
telemt_user_connections_current{user="hello"} 167
telemt_user_octets_from_client{user="hello"} 352619533 (336.28 MB)
telemt_user_octets_to_client{user="hello"} 7664189602 (7.14 GB)
telemt_user_msgs_from_client{user="hello"} 450730
telemt_user_msgs_to_client{user="hello"} 2637333
telemt_user_unique_ips_current{user="hello"} 69
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 84191.5 (23h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 566
telemt_connections_bad_total 491
telemt_handshake_timeouts_total 17
telemt_upstream_connect_attempt_total 59
telemt_upstream_connect_success_total 59
telemt_upstream_connect_attempts_per_request{bucket="1"} 59
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 47
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 51
telemt_user_octets_from_client{user="hello"} 201572 (196.85 KB)
telemt_user_octets_to_client{user="hello"} 1307210 (1.25 MB)
telemt_user_msgs_from_client{user="hello"} 250
telemt_user_msgs_to_client{user="hello"} 389
```