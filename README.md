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

# Server Metrics 2026-03-11 20:25:53 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 12333.8 (3h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 44823
telemt_connections_bad_total 2484
telemt_handshake_timeouts_total 211
telemt_upstream_connect_attempt_total 40183
telemt_upstream_connect_success_total 40173
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 40183
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36340
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3726
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 107
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 40171
telemt_user_connections_current{user="hello"} 346
telemt_user_octets_from_client{user="hello"} 1371329396 (1.28 GB)
telemt_user_octets_to_client{user="hello"} 22568143210 (21.02 GB)
telemt_user_msgs_from_client{user="hello"} 1109836
telemt_user_msgs_to_client{user="hello"} 1925146
telemt_user_unique_ips_current{user="hello"} 78
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 12322.7 (3h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20578
telemt_connections_bad_total 38
telemt_handshake_timeouts_total 255
telemt_upstream_connect_attempt_total 18987
telemt_upstream_connect_success_total 18948
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 18987
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16352
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2271
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 325
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 18946
telemt_user_connections_current{user="hello"} 97
telemt_user_octets_from_client{user="hello"} 225853856 (215.39 MB)
telemt_user_octets_to_client{user="hello"} 9704350376 (9.04 GB)
telemt_user_msgs_from_client{user="hello"} 388964
telemt_user_msgs_to_client{user="hello"} 3860194
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 12341.7 (3h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 24899
telemt_connections_bad_total 29
telemt_handshake_timeouts_total 228
telemt_upstream_connect_attempt_total 23287
telemt_upstream_connect_success_total 23285
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 23287
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21201
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2066
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 23283
telemt_user_connections_current{user="hello"} 86
telemt_user_octets_from_client{user="hello"} 233248601 (222.44 MB)
telemt_user_octets_to_client{user="hello"} 9419617383 (8.77 GB)
telemt_user_msgs_from_client{user="hello"} 450754
telemt_user_msgs_to_client{user="hello"} 2354114
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 12337.4 (3h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 27291
telemt_connections_bad_total 1803
telemt_handshake_timeouts_total 392
telemt_upstream_connect_attempt_total 23929
telemt_upstream_connect_success_total 23855
telemt_upstream_connect_fail_total 74
telemt_upstream_connect_attempts_per_request{bucket="1"} 23929
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21551
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2228
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 15
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 74
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 23853
telemt_user_connections_current{user="hello"} 114
telemt_user_octets_from_client{user="hello"} 665834111 (634.99 MB)
telemt_user_octets_to_client{user="hello"} 12932130691 (12.04 GB)
telemt_user_msgs_from_client{user="hello"} 566688
telemt_user_msgs_to_client{user="hello"} 3721936
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 12345.3 (3h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 29920
telemt_connections_bad_total 2351
telemt_handshake_timeouts_total 171
telemt_upstream_connect_attempt_total 26478
telemt_upstream_connect_success_total 26477
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 26478
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23235
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3197
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 26475
telemt_user_connections_current{user="hello"} 115
telemt_user_octets_from_client{user="hello"} 484575442 (462.13 MB)
telemt_user_octets_to_client{user="hello"} 10295921700 (9.59 GB)
telemt_user_msgs_from_client{user="hello"} 604517
telemt_user_msgs_to_client{user="hello"} 3821131
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 86951.8 (24h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 775
telemt_connections_bad_total 493
telemt_handshake_timeouts_total 17
telemt_upstream_connect_attempt_total 258
telemt_upstream_connect_success_total 258
telemt_upstream_connect_attempts_per_request{bucket="1"} 258
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 204
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 54
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 250
telemt_user_connections_current{user="hello"} 10
telemt_user_octets_from_client{user="hello"} 1548793 (1.48 MB)
telemt_user_octets_to_client{user="hello"} 63629768 (60.68 MB)
telemt_user_msgs_from_client{user="hello"} 3401
telemt_user_msgs_to_client{user="hello"} 10623
telemt_user_unique_ips_current{user="hello"} 6
```