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

# Server Metrics 2026-03-11 15:38:17 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 90727.4 (25h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 308139
telemt_connections_bad_total 5094
telemt_handshake_timeouts_total 5184
telemt_upstream_connect_attempt_total 284206
telemt_upstream_connect_success_total 284126
telemt_upstream_connect_fail_total 80
telemt_upstream_connect_attempts_per_request{bucket="1"} 284206
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 259750
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24315
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 80
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 284116
telemt_user_connections_current{user="hello"} 360
telemt_user_octets_from_client{user="hello"} 5333287342 (4.97 GB)
telemt_user_octets_to_client{user="hello"} 139057069787 (129.51 GB)
telemt_user_msgs_from_client{user="hello"} 6155028
telemt_user_msgs_to_client{user="hello"} 11207859
telemt_user_unique_ips_current{user="hello"} 93
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 90726.5 (25h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 122065
telemt_connections_bad_total 972
telemt_handshake_timeouts_total 3416
telemt_upstream_connect_attempt_total 112469
telemt_upstream_connect_success_total 112447
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 112469
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 97798
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14117
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 532
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 112437
telemt_user_connections_current{user="hello"} 160
telemt_user_octets_from_client{user="hello"} 6059368302 (5.64 GB)
telemt_user_octets_to_client{user="hello"} 69899396182 (65.10 GB)
telemt_user_msgs_from_client{user="hello"} 4062721
telemt_user_msgs_to_client{user="hello"} 20332823
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 90726.4 (25h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 167559
telemt_connections_bad_total 1436
telemt_handshake_timeouts_total 7213
telemt_upstream_connect_attempt_total 149639
telemt_upstream_connect_success_total 149625
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 149639
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 132828
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16691
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 105
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 149615
telemt_user_connections_current{user="hello"} 137
telemt_user_octets_from_client{user="hello"} 12745784919 (11.87 GB)
telemt_user_octets_to_client{user="hello"} 131919105576 (122.86 GB)
telemt_user_msgs_from_client{user="hello"} 6876041
telemt_user_msgs_to_client{user="hello"} 29649002
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 90725.5 (25h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 187676
telemt_connections_bad_total 9249
telemt_handshake_timeouts_total 2378
telemt_upstream_connect_attempt_total 168546
telemt_upstream_connect_success_total 168135
telemt_upstream_connect_fail_total 411
telemt_upstream_connect_attempts_per_request{bucket="1"} 168546
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 146590
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20999
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 93
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 453
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 411
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 168125
telemt_user_connections_current{user="hello"} 179
telemt_user_octets_from_client{user="hello"} 9924692242 (9.24 GB)
telemt_user_octets_to_client{user="hello"} 115787756004 (107.84 GB)
telemt_user_msgs_from_client{user="hello"} 5925169
telemt_user_msgs_to_client{user="hello"} 34665913
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 90726.5 (25h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 264286
telemt_connections_bad_total 19928
telemt_handshake_timeouts_total 6350
telemt_upstream_connect_attempt_total 215796
telemt_upstream_connect_success_total 215292
telemt_upstream_connect_fail_total 504
telemt_upstream_connect_attempts_per_request{bucket="1"} 215796
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 186535
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28394
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 363
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 504
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 215284
telemt_user_connections_current{user="hello"} 274
telemt_user_octets_from_client{user="hello"} 5126078087 (4.77 GB)
telemt_user_octets_to_client{user="hello"} 174135205489 (162.18 GB)
telemt_user_msgs_from_client{user="hello"} 5066340
telemt_user_msgs_to_client{user="hello"} 24316806
telemt_user_unique_ips_current{user="hello"} 84
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 69695.9 (19h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 470
telemt_connections_bad_total 447
telemt_handshake_timeouts_total 12
telemt_upstream_connect_attempt_total 19
telemt_upstream_connect_success_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 19
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 7489 (7.31 KB)
telemt_user_octets_to_client{user="hello"} 2462 (2.40 KB)
telemt_user_msgs_from_client{user="hello"} 23
telemt_user_msgs_to_client{user="hello"} 15
```