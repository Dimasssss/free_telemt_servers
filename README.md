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

# Server Metrics 2026-03-11 20:00:18 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 10799.6 (2h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 40467
telemt_connections_bad_total 2366
telemt_handshake_timeouts_total 204
telemt_upstream_connect_attempt_total 36242
telemt_upstream_connect_success_total 36233
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 36242
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32787
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3366
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 80
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 36231
telemt_user_connections_current{user="hello"} 316
telemt_user_octets_from_client{user="hello"} 994872261 (948.78 MB)
telemt_user_octets_to_client{user="hello"} 20356899991 (18.96 GB)
telemt_user_msgs_from_client{user="hello"} 937596
telemt_user_msgs_to_client{user="hello"} 1738475
telemt_user_unique_ips_current{user="hello"} 75
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 10787.8 (2h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19102
telemt_connections_bad_total 38
telemt_handshake_timeouts_total 253
telemt_upstream_connect_attempt_total 17578
telemt_upstream_connect_success_total 17539
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 17578
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15017
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2200
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 322
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 17537
telemt_user_connections_current{user="hello"} 98
telemt_user_octets_from_client{user="hello"} 216443181 (206.42 MB)
telemt_user_octets_to_client{user="hello"} 8965709955 (8.35 GB)
telemt_user_msgs_from_client{user="hello"} 363483
telemt_user_msgs_to_client{user="hello"} 3498583
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 10807.6 (3h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 22404
telemt_connections_bad_total 25
telemt_handshake_timeouts_total 184
telemt_upstream_connect_attempt_total 20912
telemt_upstream_connect_success_total 20910
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 20912
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19000
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1892
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 20908
telemt_user_connections_current{user="hello"} 85
telemt_user_octets_from_client{user="hello"} 206743184 (197.17 MB)
telemt_user_octets_to_client{user="hello"} 9009427277 (8.39 GB)
telemt_user_msgs_from_client{user="hello"} 416994
telemt_user_msgs_to_client{user="hello"} 2249054
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 10802.9 (3h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 24466
telemt_connections_bad_total 1791
telemt_handshake_timeouts_total 378
telemt_upstream_connect_attempt_total 21303
telemt_upstream_connect_success_total 21240
telemt_upstream_connect_fail_total 63
telemt_upstream_connect_attempts_per_request{bucket="1"} 21303
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19241
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1932
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 63
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 21238
telemt_user_connections_current{user="hello"} 122
telemt_user_octets_from_client{user="hello"} 622156135 (593.33 MB)
telemt_user_octets_to_client{user="hello"} 11453038295 (10.67 GB)
telemt_user_msgs_from_client{user="hello"} 513730
telemt_user_msgs_to_client{user="hello"} 3168391
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 10811.2 (3h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 26772
telemt_connections_bad_total 2064
telemt_handshake_timeouts_total 165
telemt_upstream_connect_attempt_total 23684
telemt_upstream_connect_success_total 23683
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 23684
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20765
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2887
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 23681
telemt_user_connections_current{user="hello"} 144
telemt_user_octets_from_client{user="hello"} 446654331 (425.96 MB)
telemt_user_octets_to_client{user="hello"} 8487603205 (7.90 GB)
telemt_user_msgs_from_client{user="hello"} 533369
telemt_user_msgs_to_client{user="hello"} 2933593
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 85417.5 (23h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 600
telemt_connections_bad_total 493
telemt_handshake_timeouts_total 17
telemt_upstream_connect_attempt_total 88
telemt_upstream_connect_success_total 88
telemt_upstream_connect_attempts_per_request{bucket="1"} 88
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 65
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 80
telemt_user_connections_current{user="hello"} 1
telemt_user_octets_from_client{user="hello"} 269416 (263.10 KB)
telemt_user_octets_to_client{user="hello"} 3930922 (3.75 MB)
telemt_user_msgs_from_client{user="hello"} 437
telemt_user_msgs_to_client{user="hello"} 1042
telemt_user_unique_ips_current{user="hello"} 1
```