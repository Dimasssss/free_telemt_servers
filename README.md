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

# Server Metrics 2026-03-11 00:19:07 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 35578.4 (9h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 102701
telemt_connections_bad_total 3340
telemt_handshake_timeouts_total 2489
telemt_upstream_connect_attempt_total 92326
telemt_upstream_connect_success_total 92293
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 92326
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 83926
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8314
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 92289
telemt_user_connections_current{user="hello"} 174
telemt_user_octets_from_client{user="hello"} 2679525141 (2.50 GB)
telemt_user_octets_to_client{user="hello"} 75459051942 (70.28 GB)
telemt_user_msgs_from_client{user="hello"} 2684334
telemt_user_msgs_to_client{user="hello"} 5151105
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 35578.0 (9h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 40456
telemt_connections_bad_total 340
telemt_handshake_timeouts_total 971
telemt_upstream_connect_attempt_total 36780
telemt_upstream_connect_success_total 36771
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 36780
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31053
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5496
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 222
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 36767
telemt_user_connections_current{user="hello"} 63
telemt_user_octets_from_client{user="hello"} 2007354001 (1.87 GB)
telemt_user_octets_to_client{user="hello"} 38420302196 (35.78 GB)
telemt_user_msgs_from_client{user="hello"} 1578912
telemt_user_msgs_to_client{user="hello"} 9484964
telemt_user_unique_ips_current{user="hello"} 22
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 35578.2 (9h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 63323
telemt_connections_bad_total 455
telemt_handshake_timeouts_total 4091
telemt_upstream_connect_attempt_total 55183
telemt_upstream_connect_success_total 55181
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 55183
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 49529
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5603
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 55177
telemt_user_connections_current{user="hello"} 49
telemt_user_octets_from_client{user="hello"} 7153800918 (6.66 GB)
telemt_user_octets_to_client{user="hello"} 57061099237 (53.14 GB)
telemt_user_msgs_from_client{user="hello"} 3395685
telemt_user_msgs_to_client{user="hello"} 8412887
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 35576.6 (9h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 60169
telemt_connections_bad_total 109
telemt_handshake_timeouts_total 526
telemt_upstream_connect_attempt_total 57569
telemt_upstream_connect_success_total 57416
telemt_upstream_connect_fail_total 153
telemt_upstream_connect_attempts_per_request{bucket="1"} 57569
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 50246
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6990
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 20
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 160
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 153
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 57412
telemt_user_connections_current{user="hello"} 79
telemt_user_octets_from_client{user="hello"} 845053752 (805.91 MB)
telemt_user_octets_to_client{user="hello"} 37985521133 (35.38 GB)
telemt_user_msgs_from_client{user="hello"} 1172230
telemt_user_msgs_to_client{user="hello"} 7348026
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 35578.0 (9h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 87401
telemt_connections_bad_total 8496
telemt_handshake_timeouts_total 1472
telemt_upstream_connect_attempt_total 74157
telemt_upstream_connect_success_total 73909
telemt_upstream_connect_fail_total 248
telemt_upstream_connect_attempts_per_request{bucket="1"} 74157
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 63917
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9776
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 216
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 248
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 73905
telemt_user_connections_current{user="hello"} 116
telemt_user_octets_from_client{user="hello"} 2100783966 (1.96 GB)
telemt_user_octets_to_client{user="hello"} 58315183370 (54.31 GB)
telemt_user_msgs_from_client{user="hello"} 2023887
telemt_user_msgs_to_client{user="hello"} 8451056
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 14547.3 (4h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 42
telemt_connections_bad_total 39
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 2
telemt_upstream_connect_success_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
```