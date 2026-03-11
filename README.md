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

# Server Metrics 2026-03-11 08:02:43 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 63394.7 (17h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 176528
telemt_connections_bad_total 3540
telemt_handshake_timeouts_total 4058
telemt_upstream_connect_attempt_total 160414
telemt_upstream_connect_success_total 160363
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 160414
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 146429
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13877
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 160355
telemt_user_connections_current{user="hello"} 343
telemt_user_octets_from_client{user="hello"} 3676095705 (3.42 GB)
telemt_user_octets_to_client{user="hello"} 102142988091 (95.13 GB)
telemt_user_msgs_from_client{user="hello"} 3933269
telemt_user_msgs_to_client{user="hello"} 7385569
telemt_user_unique_ips_current{user="hello"} 89
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 63394.1 (17h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 68744
telemt_connections_bad_total 584
telemt_handshake_timeouts_total 3087
telemt_upstream_connect_attempt_total 61763
telemt_upstream_connect_success_total 61749
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 61763
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52985
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8528
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 236
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 61743
telemt_user_connections_current{user="hello"} 109
telemt_user_octets_from_client{user="hello"} 4831167199 (4.50 GB)
telemt_user_octets_to_client{user="hello"} 51902564825 (48.34 GB)
telemt_user_msgs_from_client{user="hello"} 2986576
telemt_user_msgs_to_client{user="hello"} 12869102
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 63393.9 (17h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 95674
telemt_connections_bad_total 896
telemt_handshake_timeouts_total 5160
telemt_upstream_connect_attempt_total 83974
telemt_upstream_connect_success_total 83971
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 83974
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 74557
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9352
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 83965
telemt_user_connections_current{user="hello"} 89
telemt_user_octets_from_client{user="hello"} 11913186622 (11.10 GB)
telemt_user_octets_to_client{user="hello"} 75121000226 (69.96 GB)
telemt_user_msgs_from_client{user="hello"} 5422892
telemt_user_msgs_to_client{user="hello"} 14574126
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 63392.7 (17h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 103289
telemt_connections_bad_total 222
telemt_handshake_timeouts_total 700
telemt_upstream_connect_attempt_total 98742
telemt_upstream_connect_success_total 98519
telemt_upstream_connect_fail_total 219
telemt_upstream_connect_attempts_per_request{bucket="1"} 98738
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 85213
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12983
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 52
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 271
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 219
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 98511
telemt_user_connections_current{user="hello"} 160
telemt_user_octets_from_client{user="hello"} 4428835208 (4.12 GB)
telemt_user_octets_to_client{user="hello"} 66673531923 (62.09 GB)
telemt_user_msgs_from_client{user="hello"} 2983773
telemt_user_msgs_to_client{user="hello"} 16553958
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 63394.0 (17h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 171159
telemt_connections_bad_total 14036
telemt_handshake_timeouts_total 2120
telemt_upstream_connect_attempt_total 136260
telemt_upstream_connect_success_total 136010
telemt_upstream_connect_fail_total 250
telemt_upstream_connect_attempts_per_request{bucket="1"} 136260
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 116787
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18979
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 244
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 250
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 136004
telemt_user_connections_current{user="hello"} 234
telemt_user_octets_from_client{user="hello"} 2623418947 (2.44 GB)
telemt_user_octets_to_client{user="hello"} 128574880651 (119.74 GB)
telemt_user_msgs_from_client{user="hello"} 3070904
telemt_user_msgs_to_client{user="hello"} 16433133
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 42363.4 (11h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 234
telemt_connections_bad_total 213
telemt_handshake_timeouts_total 9
telemt_upstream_connect_attempt_total 15
telemt_upstream_connect_success_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 15
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 7489 (7.31 KB)
telemt_user_octets_to_client{user="hello"} 2462 (2.40 KB)
telemt_user_msgs_from_client{user="hello"} 23
telemt_user_msgs_to_client{user="hello"} 15
```