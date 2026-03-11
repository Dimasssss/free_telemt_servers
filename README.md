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

# Server Metrics 2026-03-11 09:04:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 67071.9 (18h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 192744
telemt_connections_bad_total 3558
telemt_handshake_timeouts_total 4199
telemt_upstream_connect_attempt_total 175934
telemt_upstream_connect_success_total 175880
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 175934
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 160496
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15327
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 175872
telemt_user_connections_current{user="hello"} 344
telemt_user_octets_from_client{user="hello"} 3889354084 (3.62 GB)
telemt_user_octets_to_client{user="hello"} 107481553536 (100.10 GB)
telemt_user_msgs_from_client{user="hello"} 4209878
telemt_user_msgs_to_client{user="hello"} 7881483
telemt_user_unique_ips_current{user="hello"} 93
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 67068.7 (18h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 74765
telemt_connections_bad_total 596
telemt_handshake_timeouts_total 3136
telemt_upstream_connect_attempt_total 67530
telemt_upstream_connect_success_total 67515
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 67530
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 58089
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 246
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 67509
telemt_user_connections_current{user="hello"} 76
telemt_user_octets_from_client{user="hello"} 4922434830 (4.58 GB)
telemt_user_octets_to_client{user="hello"} 53676551365 (49.99 GB)
telemt_user_msgs_from_client{user="hello"} 3092454
telemt_user_msgs_to_client{user="hello"} 13735707
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 67069.2 (18h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 103438
telemt_connections_bad_total 927
telemt_handshake_timeouts_total 5203
telemt_upstream_connect_attempt_total 91331
telemt_upstream_connect_success_total 91327
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 91330
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 81160
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10105
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 91319
telemt_user_connections_current{user="hello"} 182
telemt_user_octets_from_client{user="hello"} 11958047709 (11.14 GB)
telemt_user_octets_to_client{user="hello"} 78020579485 (72.66 GB)
telemt_user_msgs_from_client{user="hello"} 5542270
telemt_user_msgs_to_client{user="hello"} 15207413
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 67067.5 (18h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 114804
telemt_connections_bad_total 227
telemt_handshake_timeouts_total 1044
telemt_upstream_connect_attempt_total 109037
telemt_upstream_connect_success_total 108791
telemt_upstream_connect_fail_total 246
telemt_upstream_connect_attempts_per_request{bucket="1"} 109037
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 93828
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14612
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 56
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 295
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 246
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 108783
telemt_user_connections_current{user="hello"} 162
telemt_user_octets_from_client{user="hello"} 4666397367 (4.35 GB)
telemt_user_octets_to_client{user="hello"} 76889762116 (71.61 GB)
telemt_user_msgs_from_client{user="hello"} 3229145
telemt_user_msgs_to_client{user="hello"} 19617401
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 67068.7 (18h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 183533
telemt_connections_bad_total 14711
telemt_handshake_timeouts_total 3088
telemt_upstream_connect_attempt_total 146405
telemt_upstream_connect_success_total 146004
telemt_upstream_connect_fail_total 401
telemt_upstream_connect_attempts_per_request{bucket="1"} 146405
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 125150
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20579
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 275
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 401
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 145998
telemt_user_connections_current{user="hello"} 234
telemt_user_octets_from_client{user="hello"} 2883693794 (2.69 GB)
telemt_user_octets_to_client{user="hello"} 133290198304 (124.14 GB)
telemt_user_msgs_from_client{user="hello"} 3280060
telemt_user_msgs_to_client{user="hello"} 17291929
telemt_user_unique_ips_current{user="hello"} 72
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 46038.2 (12h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 420
telemt_connections_bad_total 398
telemt_handshake_timeouts_total 9
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