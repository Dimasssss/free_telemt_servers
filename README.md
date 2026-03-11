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

# Server Metrics 2026-03-11 15:12:40 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 89191.3 (24h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 300414
telemt_connections_bad_total 4410
telemt_handshake_timeouts_total 5021
telemt_upstream_connect_attempt_total 277522
telemt_upstream_connect_success_total 277442
telemt_upstream_connect_fail_total 80
telemt_upstream_connect_attempts_per_request{bucket="1"} 277522
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 253694
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23687
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 80
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 277432
telemt_user_connections_current{user="hello"} 373
telemt_user_octets_from_client{user="hello"} 5127574070 (4.78 GB)
telemt_user_octets_to_client{user="hello"} 137706006343 (128.25 GB)
telemt_user_msgs_from_client{user="hello"} 6010700
telemt_user_msgs_to_client{user="hello"} 11033549
telemt_user_unique_ips_current{user="hello"} 92
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 89190.5 (24h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 118800
telemt_connections_bad_total 966
telemt_handshake_timeouts_total 3399
telemt_upstream_connect_attempt_total 109317
telemt_upstream_connect_success_total 109296
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 109317
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 94965
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13833
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 498
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 109286
telemt_user_connections_current{user="hello"} 172
telemt_user_octets_from_client{user="hello"} 6004291752 (5.59 GB)
telemt_user_octets_to_client{user="hello"} 69325276145 (64.56 GB)
telemt_user_msgs_from_client{user="hello"} 4002881
telemt_user_msgs_to_client{user="hello"} 20074544
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 89190.2 (24h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 163638
telemt_connections_bad_total 1251
telemt_handshake_timeouts_total 7085
telemt_upstream_connect_attempt_total 146180
telemt_upstream_connect_success_total 146166
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 146180
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 129830
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16233
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 102
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 146156
telemt_user_connections_current{user="hello"} 142
telemt_user_octets_from_client{user="hello"} 12717888035 (11.84 GB)
telemt_user_octets_to_client{user="hello"} 129634745742 (120.73 GB)
telemt_user_msgs_from_client{user="hello"} 6803682
telemt_user_msgs_to_client{user="hello"} 29001707
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 89189.4 (24h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 182325
telemt_connections_bad_total 8044
telemt_handshake_timeouts_total 2107
telemt_upstream_connect_attempt_total 164930
telemt_upstream_connect_success_total 164524
telemt_upstream_connect_fail_total 404
telemt_upstream_connect_attempts_per_request{bucket="1"} 164928
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 143245
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20738
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 91
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 450
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 404
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 164514
telemt_user_connections_current{user="hello"} 173
telemt_user_octets_from_client{user="hello"} 9790600267 (9.12 GB)
telemt_user_octets_to_client{user="hello"} 114414531017 (106.56 GB)
telemt_user_msgs_from_client{user="hello"} 5834684
telemt_user_msgs_to_client{user="hello"} 34201572
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 89190.4 (24h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 259033
telemt_connections_bad_total 19651
telemt_handshake_timeouts_total 6327
telemt_upstream_connect_attempt_total 211038
telemt_upstream_connect_success_total 210534
telemt_upstream_connect_fail_total 504
telemt_upstream_connect_attempts_per_request{bucket="1"} 211038
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 182337
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27840
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 357
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 504
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 210526
telemt_user_connections_current{user="hello"} 323
telemt_user_octets_from_client{user="hello"} 5080222994 (4.73 GB)
telemt_user_octets_to_client{user="hello"} 172727946243 (160.87 GB)
telemt_user_msgs_from_client{user="hello"} 4980612
telemt_user_msgs_to_client{user="hello"} 24008016
telemt_user_unique_ips_current{user="hello"} 79
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 68159.8 (18h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 463
telemt_connections_bad_total 441
telemt_handshake_timeouts_total 10
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