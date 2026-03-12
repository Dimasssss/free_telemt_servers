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

# Server Metrics 2026-03-12 06:24:42 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 31194.1 (8h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 83373
telemt_connections_bad_total 2117
telemt_handshake_timeouts_total 2288
telemt_upstream_connect_attempt_total 75245
telemt_upstream_connect_success_total 75187
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 75244
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 63522
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11544
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 121
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 75183
telemt_user_connections_current{user="hello"} 350
telemt_user_octets_from_client{user="hello"} 779606957 (743.49 MB)
telemt_user_octets_to_client{user="hello"} 22320367751 (20.79 GB)
telemt_user_msgs_from_client{user="hello"} 1141784
telemt_user_msgs_to_client{user="hello"} 2601922
telemt_user_unique_ips_current{user="hello"} 91
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 31182.3 (8h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 33845
telemt_connections_bad_total 210
telemt_handshake_timeouts_total 384
telemt_upstream_connect_attempt_total 32041
telemt_upstream_connect_success_total 32025
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 32041
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27671
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4307
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 32021
telemt_user_connections_current{user="hello"} 158
telemt_user_octets_from_client{user="hello"} 291806787 (278.29 MB)
telemt_user_octets_to_client{user="hello"} 15554453705 (14.49 GB)
telemt_user_msgs_from_client{user="hello"} 582188
telemt_user_msgs_to_client{user="hello"} 4913089
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 31156.0 (8h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 51106
telemt_connections_bad_total 675
telemt_handshake_timeouts_total 1108
telemt_upstream_connect_attempt_total 46151
telemt_upstream_connect_success_total 46133
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 46151
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38297
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7795
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 46129
telemt_user_connections_current{user="hello"} 184
telemt_user_octets_from_client{user="hello"} 5387725352 (5.02 GB)
telemt_user_octets_to_client{user="hello"} 28189936773 (26.25 GB)
telemt_user_msgs_from_client{user="hello"} 2660704
telemt_user_msgs_to_client{user="hello"} 5028884
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 31181.5 (8h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 55998
telemt_connections_bad_total 12967
telemt_handshake_timeouts_total 864
telemt_upstream_connect_attempt_total 39968
telemt_upstream_connect_success_total 38247
telemt_upstream_connect_fail_total 1721
telemt_upstream_connect_attempts_per_request{bucket="1"} 39968
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31749
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6383
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 106
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1721
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 38243
telemt_user_connections_current{user="hello"} 195
telemt_user_octets_from_client{user="hello"} 1364642275 (1.27 GB)
telemt_user_octets_to_client{user="hello"} 26181256886 (24.38 GB)
telemt_user_msgs_from_client{user="hello"} 1046726
telemt_user_msgs_to_client{user="hello"} 10874763
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 1373.7 (0h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2124
telemt_connections_bad_total 245
telemt_handshake_timeouts_total 79
telemt_upstream_connect_attempt_total 1708
telemt_upstream_connect_success_total 1696
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 1708
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1481
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 202
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1694
telemt_user_connections_current{user="hello"} 71
telemt_user_octets_from_client{user="hello"} 102553276 (97.80 MB)
telemt_user_octets_to_client{user="hello"} 724448495 (690.89 MB)
telemt_user_msgs_from_client{user="hello"} 53900
telemt_user_msgs_to_client{user="hello"} 108674
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 31182.1 (8h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 51701
telemt_connections_bad_total 766
telemt_handshake_timeouts_total 273
telemt_upstream_connect_attempt_total 48242
telemt_upstream_connect_success_total 48211
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 48242
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40146
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8000
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 48207
telemt_user_connections_current{user="hello"} 170
telemt_user_octets_from_client{user="hello"} 852764709 (813.26 MB)
telemt_user_octets_to_client{user="hello"} 44367063776 (41.32 GB)
telemt_user_msgs_from_client{user="hello"} 1252678
telemt_user_msgs_to_client{user="hello"} 5828100
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 31
```