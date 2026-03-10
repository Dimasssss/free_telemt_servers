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

# Server Metrics 2026-03-10 22:16:49 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 28241.2 (7h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 93686
telemt_connections_bad_total 3290
telemt_handshake_timeouts_total 2185
telemt_upstream_connect_attempt_total 84052
telemt_upstream_connect_success_total 84020
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 84052
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 76630
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7337
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 84016
telemt_user_connections_current{user="hello"} 171
telemt_user_octets_from_client{user="hello"} 2537253572 (2.36 GB)
telemt_user_octets_to_client{user="hello"} 66614002851 (62.04 GB)
telemt_user_msgs_from_client{user="hello"} 2430364
telemt_user_msgs_to_client{user="hello"} 4380927
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 28240.3 (7h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 35704
telemt_connections_bad_total 319
telemt_handshake_timeouts_total 716
telemt_upstream_connect_attempt_total 32526
telemt_upstream_connect_success_total 32517
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 32526
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27507
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4790
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 220
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 32513
telemt_user_connections_current{user="hello"} 49
telemt_user_octets_from_client{user="hello"} 1670160906 (1.56 GB)
telemt_user_octets_to_client{user="hello"} 33608384746 (31.30 GB)
telemt_user_msgs_from_client{user="hello"} 1342358
telemt_user_msgs_to_client{user="hello"} 8512479
telemt_user_unique_ips_current{user="hello"} 20
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 28240.2 (7h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 58138
telemt_connections_bad_total 430
telemt_handshake_timeouts_total 3978
telemt_upstream_connect_attempt_total 50428
telemt_upstream_connect_success_total 50426
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 50428
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45507
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4871
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 50422
telemt_user_connections_current{user="hello"} 80
telemt_user_octets_from_client{user="hello"} 768692405 (733.08 MB)
telemt_user_octets_to_client{user="hello"} 46932459654 (43.71 GB)
telemt_user_msgs_from_client{user="hello"} 1071495
telemt_user_msgs_to_client{user="hello"} 7073871
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 28239.0 (7h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 53209
telemt_connections_bad_total 83
telemt_handshake_timeouts_total 327
telemt_upstream_connect_attempt_total 51090
telemt_upstream_connect_success_total 50947
telemt_upstream_connect_fail_total 143
telemt_upstream_connect_attempts_per_request{bucket="1"} 51090
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44773
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6012
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 149
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 143
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 50943
telemt_user_connections_current{user="hello"} 73
telemt_user_octets_from_client{user="hello"} 819188483 (781.24 MB)
telemt_user_octets_to_client{user="hello"} 37075465015 (34.53 GB)
telemt_user_msgs_from_client{user="hello"} 1106776
telemt_user_msgs_to_client{user="hello"} 7073838
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 28240.4 (7h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 77194
telemt_connections_bad_total 7039
telemt_handshake_timeouts_total 1409
telemt_upstream_connect_attempt_total 65703
telemt_upstream_connect_success_total 65459
telemt_upstream_connect_fail_total 244
telemt_upstream_connect_attempts_per_request{bucket="1"} 65703
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 56660
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8589
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 210
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 244
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 65455
telemt_user_connections_current{user="hello"} 130
telemt_user_octets_from_client{user="hello"} 2027045406 (1.89 GB)
telemt_user_octets_to_client{user="hello"} 50632717615 (47.16 GB)
telemt_user_msgs_from_client{user="hello"} 1854971
telemt_user_msgs_to_client{user="hello"} 7442930
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 7209.7 (2h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 29
telemt_connections_bad_total 28
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 2
telemt_upstream_connect_success_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
```