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

# Server Metrics 2026-03-11 14:26:36 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 86427.2 (24h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 285422
telemt_connections_bad_total 3680
telemt_handshake_timeouts_total 4785
telemt_upstream_connect_attempt_total 264187
telemt_upstream_connect_success_total 264110
telemt_upstream_connect_fail_total 77
telemt_upstream_connect_attempts_per_request{bucket="1"} 264187
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 241677
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22372
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 77
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 264100
telemt_user_connections_current{user="hello"} 336
telemt_user_octets_from_client{user="hello"} 5030626597 (4.69 GB)
telemt_user_octets_to_client{user="hello"} 134102371488 (124.89 GB)
telemt_user_msgs_from_client{user="hello"} 5820970
telemt_user_msgs_to_client{user="hello"} 10645335
telemt_user_unique_ips_current{user="hello"} 100
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 86426.4 (24h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 112799
telemt_connections_bad_total 922
telemt_handshake_timeouts_total 3363
telemt_upstream_connect_attempt_total 103569
telemt_upstream_connect_success_total 103549
telemt_upstream_connect_fail_total 20
telemt_upstream_connect_attempts_per_request{bucket="1"} 103569
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 89731
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13366
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 452
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 103539
telemt_user_connections_current{user="hello"} 178
telemt_user_octets_from_client{user="hello"} 5945710467 (5.54 GB)
telemt_user_octets_to_client{user="hello"} 68071547070 (63.40 GB)
telemt_user_msgs_from_client{user="hello"} 3909024
telemt_user_msgs_to_client{user="hello"} 19465283
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 86426.5 (24h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 156942
telemt_connections_bad_total 1251
telemt_handshake_timeouts_total 6915
telemt_upstream_connect_attempt_total 140050
telemt_upstream_connect_success_total 140036
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 140050
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 124573
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15360
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 102
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 140026
telemt_user_connections_current{user="hello"} 141
telemt_user_octets_from_client{user="hello"} 12679369957 (11.81 GB)
telemt_user_octets_to_client{user="hello"} 127718586216 (118.95 GB)
telemt_user_msgs_from_client{user="hello"} 6695548
telemt_user_msgs_to_client{user="hello"} 28474632
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 86425.0 (24h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 174482
telemt_connections_bad_total 7173
telemt_handshake_timeouts_total 1961
telemt_upstream_connect_attempt_total 158348
telemt_upstream_connect_success_total 157963
telemt_upstream_connect_fail_total 385
telemt_upstream_connect_attempts_per_request{bucket="1"} 158348
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 137282
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20159
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 89
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 433
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 385
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 157953
telemt_user_connections_current{user="hello"} 172
telemt_user_octets_from_client{user="hello"} 9559011824 (8.90 GB)
telemt_user_octets_to_client{user="hello"} 110944468835 (103.33 GB)
telemt_user_msgs_from_client{user="hello"} 5664287
telemt_user_msgs_to_client{user="hello"} 32913075
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 86426.5 (24h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 249738
telemt_connections_bad_total 19121
telemt_handshake_timeouts_total 6293
telemt_upstream_connect_attempt_total 202593
telemt_upstream_connect_success_total 202090
telemt_upstream_connect_fail_total 503
telemt_upstream_connect_attempts_per_request{bucket="1"} 202593
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 174922
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26819
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 349
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 503
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 202082
telemt_user_connections_current{user="hello"} 331
telemt_user_octets_from_client{user="hello"} 4980690686 (4.64 GB)
telemt_user_octets_to_client{user="hello"} 162312496490 (151.17 GB)
telemt_user_msgs_from_client{user="hello"} 4770018
telemt_user_msgs_to_client{user="hello"} 22360881
telemt_user_unique_ips_current{user="hello"} 84
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 65395.8 (18h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 454
telemt_connections_bad_total 432
telemt_handshake_timeouts_total 10
telemt_upstream_connect_attempt_total 17
telemt_upstream_connect_success_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 17
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 7489 (7.31 KB)
telemt_user_octets_to_client{user="hello"} 2462 (2.40 KB)
telemt_user_msgs_from_client{user="hello"} 23
telemt_user_msgs_to_client{user="hello"} 15
```