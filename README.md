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

# Server Metrics 2026-03-11 01:20:12 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 39244.0 (10h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 107606
telemt_connections_bad_total 3351
telemt_handshake_timeouts_total 2514
telemt_upstream_connect_attempt_total 96997
telemt_upstream_connect_success_total 96962
telemt_upstream_connect_fail_total 35
telemt_upstream_connect_attempts_per_request{bucket="1"} 96997
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 88216
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8692
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 35
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 96958
telemt_user_connections_current{user="hello"} 181
telemt_user_octets_from_client{user="hello"} 2736296348 (2.55 GB)
telemt_user_octets_to_client{user="hello"} 77835032587 (72.49 GB)
telemt_user_msgs_from_client{user="hello"} 2774786
telemt_user_msgs_to_client{user="hello"} 5345625
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 39243.4 (10h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 43393
telemt_connections_bad_total 354
telemt_handshake_timeouts_total 1377
telemt_upstream_connect_attempt_total 39171
telemt_upstream_connect_success_total 39162
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 39171
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33177
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5762
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 223
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 39158
telemt_user_connections_current{user="hello"} 50
telemt_user_octets_from_client{user="hello"} 2019569497 (1.88 GB)
telemt_user_octets_to_client{user="hello"} 38616052996 (35.96 GB)
telemt_user_msgs_from_client{user="hello"} 1608809
telemt_user_msgs_to_client{user="hello"} 9578801
telemt_user_unique_ips_current{user="hello"} 22
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 39243.0 (10h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 65820
telemt_connections_bad_total 583
telemt_handshake_timeouts_total 4124
telemt_upstream_connect_attempt_total 57398
telemt_upstream_connect_success_total 57396
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 57398
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 51309
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6038
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 57392
telemt_user_connections_current{user="hello"} 46
telemt_user_octets_from_client{user="hello"} 8507527225 (7.92 GB)
telemt_user_octets_to_client{user="hello"} 64194445577 (59.79 GB)
telemt_user_msgs_from_client{user="hello"} 3937463
telemt_user_msgs_to_client{user="hello"} 11048741
telemt_user_unique_ips_current{user="hello"} 21
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 39242.1 (10h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 63692
telemt_connections_bad_total 122
telemt_handshake_timeouts_total 531
telemt_upstream_connect_attempt_total 60937
telemt_upstream_connect_success_total 60782
telemt_upstream_connect_fail_total 155
telemt_upstream_connect_attempts_per_request{bucket="1"} 60937
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53158
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7434
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 26
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 164
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 155
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 60778
telemt_user_connections_current{user="hello"} 115
telemt_user_octets_from_client{user="hello"} 1231716778 (1.15 GB)
telemt_user_octets_to_client{user="hello"} 41185414720 (38.36 GB)
telemt_user_msgs_from_client{user="hello"} 1370856
telemt_user_msgs_to_client{user="hello"} 7995704
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 39243.3 (10h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 92138
telemt_connections_bad_total 9221
telemt_handshake_timeouts_total 1490
telemt_upstream_connect_attempt_total 78052
telemt_upstream_connect_success_total 77804
telemt_upstream_connect_fail_total 248
telemt_upstream_connect_attempts_per_request{bucket="1"} 78052
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 67478
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10107
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 219
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 248
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 77800
telemt_user_connections_current{user="hello"} 101
telemt_user_octets_from_client{user="hello"} 2128795158 (1.98 GB)
telemt_user_octets_to_client{user="hello"} 62242130953 (57.97 GB)
telemt_user_msgs_from_client{user="hello"} 2091142
telemt_user_msgs_to_client{user="hello"} 9055644
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 18212.6 (5h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 53
telemt_connections_bad_total 49
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 2
telemt_upstream_connect_success_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
```