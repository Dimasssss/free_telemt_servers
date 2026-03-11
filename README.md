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

# Server Metrics 2026-03-11 20:20:45 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 12026.5 (3h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 43842
telemt_connections_bad_total 2482
telemt_handshake_timeouts_total 209
telemt_upstream_connect_attempt_total 39230
telemt_upstream_connect_success_total 39221
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 39230
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35465
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3654
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 102
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 39219
telemt_user_connections_current{user="hello"} 265
telemt_user_octets_from_client{user="hello"} 1287599300 (1.20 GB)
telemt_user_octets_to_client{user="hello"} 21819734866 (20.32 GB)
telemt_user_msgs_from_client{user="hello"} 1070037
telemt_user_msgs_to_client{user="hello"} 1883568
telemt_user_unique_ips_current{user="hello"} 71
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 12014.8 (3h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20251
telemt_connections_bad_total 38
telemt_handshake_timeouts_total 255
telemt_upstream_connect_attempt_total 18675
telemt_upstream_connect_success_total 18636
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 18675
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16045
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2267
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 324
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 18634
telemt_user_connections_current{user="hello"} 102
telemt_user_octets_from_client{user="hello"} 223487970 (213.13 MB)
telemt_user_octets_to_client{user="hello"} 9412818992 (8.77 GB)
telemt_user_msgs_from_client{user="hello"} 382195
telemt_user_msgs_to_client{user="hello"} 3723040
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 12034.6 (3h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 24470
telemt_connections_bad_total 29
telemt_handshake_timeouts_total 219
telemt_upstream_connect_attempt_total 22879
telemt_upstream_connect_success_total 22877
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 22879
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20835
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2024
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 22875
telemt_user_connections_current{user="hello"} 81
telemt_user_octets_from_client{user="hello"} 230907340 (220.21 MB)
telemt_user_octets_to_client{user="hello"} 9139331597 (8.51 GB)
telemt_user_msgs_from_client{user="hello"} 443165
telemt_user_msgs_to_client{user="hello"} 2301700
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 12030.2 (3h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 26747
telemt_connections_bad_total 1803
telemt_handshake_timeouts_total 391
telemt_upstream_connect_attempt_total 23424
telemt_upstream_connect_success_total 23353
telemt_upstream_connect_fail_total 71
telemt_upstream_connect_attempts_per_request{bucket="1"} 23424
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21115
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2164
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 14
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 71
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 23351
telemt_user_connections_current{user="hello"} 122
telemt_user_octets_from_client{user="hello"} 662421176 (631.73 MB)
telemt_user_octets_to_client{user="hello"} 12437316254 (11.58 GB)
telemt_user_msgs_from_client{user="hello"} 557742
telemt_user_msgs_to_client{user="hello"} 3549679
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 12038.2 (3h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 29358
telemt_connections_bad_total 2288
telemt_handshake_timeouts_total 171
telemt_upstream_connect_attempt_total 25992
telemt_upstream_connect_success_total 25991
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 25992
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22831
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3120
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 25989
telemt_user_connections_current{user="hello"} 135
telemt_user_octets_from_client{user="hello"} 480020958 (457.78 MB)
telemt_user_octets_to_client{user="hello"} 9848381266 (9.17 GB)
telemt_user_msgs_from_client{user="hello"} 591378
telemt_user_msgs_to_client{user="hello"} 3628648
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 86644.6 (24h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 741
telemt_connections_bad_total 493
telemt_handshake_timeouts_total 17
telemt_upstream_connect_attempt_total 225
telemt_upstream_connect_success_total 225
telemt_upstream_connect_attempts_per_request{bucket="1"} 225
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 172
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 53
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 217
telemt_user_connections_current{user="hello"} 7
telemt_user_octets_from_client{user="hello"} 1290710 (1.23 MB)
telemt_user_octets_to_client{user="hello"} 59875913 (57.10 MB)
telemt_user_msgs_from_client{user="hello"} 2728
telemt_user_msgs_to_client{user="hello"} 9726
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 2
```