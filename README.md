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

# Server Metrics 2026-03-12 06:29:49 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 31500.9 (8h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 85039
telemt_connections_bad_total 2118
telemt_handshake_timeouts_total 2305
telemt_upstream_connect_attempt_total 76875
telemt_upstream_connect_success_total 76816
telemt_upstream_connect_fail_total 59
telemt_upstream_connect_attempts_per_request{bucket="1"} 76875
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 64975
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11704
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 137
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 59
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 76812
telemt_user_connections_current{user="hello"} 321
telemt_user_octets_from_client{user="hello"} 798283919 (761.30 MB)
telemt_user_octets_to_client{user="hello"} 22542255276 (20.99 GB)
telemt_user_msgs_from_client{user="hello"} 1161362
telemt_user_msgs_to_client{user="hello"} 2628999
telemt_user_unique_ips_current{user="hello"} 95
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 31489.1 (8h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 34714
telemt_connections_bad_total 210
telemt_handshake_timeouts_total 527
telemt_upstream_connect_attempt_total 32758
telemt_upstream_connect_success_total 32742
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 32758
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28240
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4453
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 32738
telemt_user_connections_current{user="hello"} 123
telemt_user_octets_from_client{user="hello"} 294573714 (280.93 MB)
telemt_user_octets_to_client{user="hello"} 15657375055 (14.58 GB)
telemt_user_msgs_from_client{user="hello"} 588397
telemt_user_msgs_to_client{user="hello"} 4946000
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 31462.5 (8h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 51881
telemt_connections_bad_total 676
telemt_handshake_timeouts_total 1110
telemt_upstream_connect_attempt_total 46878
telemt_upstream_connect_success_total 46860
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 46878
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38854
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7960
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 46856
telemt_user_connections_current{user="hello"} 186
telemt_user_octets_from_client{user="hello"} 5396897369 (5.03 GB)
telemt_user_octets_to_client{user="hello"} 28570923115 (26.61 GB)
telemt_user_msgs_from_client{user="hello"} 2675378
telemt_user_msgs_to_client{user="hello"} 5077912
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 31487.9 (8h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 56972
telemt_connections_bad_total 12967
telemt_handshake_timeouts_total 875
telemt_upstream_connect_attempt_total 40891
telemt_upstream_connect_success_total 39168
telemt_upstream_connect_fail_total 1723
telemt_upstream_connect_attempts_per_request{bucket="1"} 40891
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32462
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6586
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 111
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1723
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 39164
telemt_user_connections_current{user="hello"} 227
telemt_user_octets_from_client{user="hello"} 1372977313 (1.28 GB)
telemt_user_octets_to_client{user="hello"} 27140397245 (25.28 GB)
telemt_user_msgs_from_client{user="hello"} 1067937
telemt_user_msgs_to_client{user="hello"} 11315896
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 1680.4 (0h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2516
telemt_connections_bad_total 301
telemt_handshake_timeouts_total 79
telemt_upstream_connect_attempt_total 2035
telemt_upstream_connect_success_total 2023
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 2035
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1768
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 239
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2021
telemt_user_connections_current{user="hello"} 68
telemt_user_octets_from_client{user="hello"} 106085995 (101.17 MB)
telemt_user_octets_to_client{user="hello"} 1574555342 (1.47 GB)
telemt_user_msgs_from_client{user="hello"} 63646
telemt_user_msgs_to_client{user="hello"} 194999
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 31489.0 (8h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 52715
telemt_connections_bad_total 766
telemt_handshake_timeouts_total 307
telemt_upstream_connect_attempt_total 49204
telemt_upstream_connect_success_total 49173
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 49204
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40961
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8138
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 49169
telemt_user_connections_current{user="hello"} 187
telemt_user_octets_from_client{user="hello"} 861513437 (821.60 MB)
telemt_user_octets_to_client{user="hello"} 46573548871 (43.37 GB)
telemt_user_msgs_from_client{user="hello"} 1273326
telemt_user_msgs_to_client{user="hello"} 5997573
telemt_user_unique_ips_current{user="hello"} 77
telemt_user_unique_ips_recent_window{user="hello"} 37
```