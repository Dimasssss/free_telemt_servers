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

# Server Metrics 2026-03-11 07:32:06 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 61557.0 (17h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 168594
telemt_connections_bad_total 3538
telemt_handshake_timeouts_total 4011
telemt_upstream_connect_attempt_total 152676
telemt_upstream_connect_success_total 152629
telemt_upstream_connect_fail_total 47
telemt_upstream_connect_attempts_per_request{bucket="1"} 152676
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 139222
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13350
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 47
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 152621
telemt_user_connections_current{user="hello"} 313
telemt_user_octets_from_client{user="hello"} 3579382851 (3.33 GB)
telemt_user_octets_to_client{user="hello"} 99535183377 (92.70 GB)
telemt_user_msgs_from_client{user="hello"} 3814169
telemt_user_msgs_to_client{user="hello"} 7155523
telemt_user_unique_ips_current{user="hello"} 84
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 61556.4 (17h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 66316
telemt_connections_bad_total 477
telemt_handshake_timeouts_total 3071
telemt_upstream_connect_attempt_total 59530
telemt_upstream_connect_success_total 59516
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 59530
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 50940
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8344
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 232
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 59510
telemt_user_connections_current{user="hello"} 80
telemt_user_octets_from_client{user="hello"} 4671903207 (4.35 GB)
telemt_user_octets_to_client{user="hello"} 50993846196 (47.49 GB)
telemt_user_msgs_from_client{user="hello"} 2902917
telemt_user_msgs_to_client{user="hello"} 12450505
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 61556.2 (17h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 91184
telemt_connections_bad_total 869
telemt_handshake_timeouts_total 5090
telemt_upstream_connect_attempt_total 79814
telemt_upstream_connect_success_total 79811
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 79814
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 70979
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8771
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 79805
telemt_user_connections_current{user="hello"} 68
telemt_user_octets_from_client{user="hello"} 11878602749 (11.06 GB)
telemt_user_octets_to_client{user="hello"} 74642067358 (69.52 GB)
telemt_user_msgs_from_client{user="hello"} 5361291
telemt_user_msgs_to_client{user="hello"} 14372952
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 61555.2 (17h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 97943
telemt_connections_bad_total 218
telemt_handshake_timeouts_total 669
telemt_upstream_connect_attempt_total 93859
telemt_upstream_connect_success_total 93651
telemt_upstream_connect_fail_total 208
telemt_upstream_connect_attempts_per_request{bucket="1"} 93859
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 80961
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12377
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 50
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 263
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 208
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 93643
telemt_user_connections_current{user="hello"} 144
telemt_user_octets_from_client{user="hello"} 2493777965 (2.32 GB)
telemt_user_octets_to_client{user="hello"} 63537460395 (59.17 GB)
telemt_user_msgs_from_client{user="hello"} 2249390
telemt_user_msgs_to_client{user="hello"} 15762054
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 61556.4 (17h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 164383
telemt_connections_bad_total 13560
telemt_handshake_timeouts_total 1866
telemt_upstream_connect_attempt_total 130919
telemt_upstream_connect_success_total 130669
telemt_upstream_connect_fail_total 250
telemt_upstream_connect_attempts_per_request{bucket="1"} 130919
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 112149
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18278
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 242
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 250
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 130663
telemt_user_connections_current{user="hello"} 213
telemt_user_octets_from_client{user="hello"} 2583111538 (2.41 GB)
telemt_user_octets_to_client{user="hello"} 126965621423 (118.25 GB)
telemt_user_msgs_from_client{user="hello"} 3002198
telemt_user_msgs_to_client{user="hello"} 16148853
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 40525.7 (11h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 221
telemt_connections_bad_total 201
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