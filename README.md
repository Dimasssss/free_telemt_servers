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

# Server Metrics 2026-03-11 18:12:49 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 4350.0 (1h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18206
telemt_connections_bad_total 937
telemt_handshake_timeouts_total 84
telemt_upstream_connect_attempt_total 16349
telemt_upstream_connect_success_total 16346
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 16349
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14783
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1546
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 16344
telemt_user_connections_current{user="hello"} 318
telemt_user_octets_from_client{user="hello"} 454823657 (433.75 MB)
telemt_user_octets_to_client{user="hello"} 10088306881 (9.40 GB)
telemt_user_msgs_from_client{user="hello"} 400050
telemt_user_msgs_to_client{user="hello"} 732552
telemt_user_unique_ips_current{user="hello"} 85
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 4338.0 (1h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9276
telemt_connections_bad_total 27
telemt_handshake_timeouts_total 158
telemt_upstream_connect_attempt_total 8447
telemt_upstream_connect_success_total 8446
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 8447
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7196
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1048
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 202
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 8444
telemt_user_connections_current{user="hello"} 173
telemt_user_octets_from_client{user="hello"} 147556454 (140.72 MB)
telemt_user_octets_to_client{user="hello"} 5318601141 (4.95 GB)
telemt_user_msgs_from_client{user="hello"} 199811
telemt_user_msgs_to_client{user="hello"} 2020883
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 4357.4 (1h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10299
telemt_connections_bad_total 19
telemt_handshake_timeouts_total 101
telemt_upstream_connect_attempt_total 9639
telemt_upstream_connect_success_total 9638
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 9639
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8749
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 889
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9636
telemt_user_connections_current{user="hello"} 105
telemt_user_octets_from_client{user="hello"} 78901510 (75.25 MB)
telemt_user_octets_to_client{user="hello"} 4096945911 (3.82 GB)
telemt_user_msgs_from_client{user="hello"} 200071
telemt_user_msgs_to_client{user="hello"} 1178382
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 4353.2 (1h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9890
telemt_connections_bad_total 511
telemt_handshake_timeouts_total 186
telemt_upstream_connect_attempt_total 8855
telemt_upstream_connect_success_total 8834
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 8855
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7931
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 878
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 8832
telemt_user_connections_current{user="hello"} 116
telemt_user_octets_from_client{user="hello"} 438515672 (418.20 MB)
telemt_user_octets_to_client{user="hello"} 4087168643 (3.81 GB)
telemt_user_msgs_from_client{user="hello"} 263681
telemt_user_msgs_to_client{user="hello"} 978275
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 4361.3 (1h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10997
telemt_connections_bad_total 898
telemt_handshake_timeouts_total 72
telemt_upstream_connect_attempt_total 9705
telemt_upstream_connect_success_total 9705
telemt_upstream_connect_attempts_per_request{bucket="1"} 9705
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8310
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1388
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9703
telemt_user_connections_current{user="hello"} 154
telemt_user_octets_from_client{user="hello"} 64470523 (61.48 MB)
telemt_user_octets_to_client{user="hello"} 1455264378 (1.36 GB)
telemt_user_msgs_from_client{user="hello"} 138069
telemt_user_msgs_to_client{user="hello"} 472393
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 78967.8 (21h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 496
telemt_connections_bad_total 472
telemt_handshake_timeouts_total 14
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