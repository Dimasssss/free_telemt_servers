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

# Server Metrics 2026-03-11 00:03:51 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 34662.7 (9h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 101469
telemt_connections_bad_total 3325
telemt_handshake_timeouts_total 2477
telemt_upstream_connect_attempt_total 91160
telemt_upstream_connect_success_total 91128
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 91160
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 82883
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8192
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 91124
telemt_user_connections_current{user="hello"} 150
telemt_user_octets_from_client{user="hello"} 2659168196 (2.48 GB)
telemt_user_octets_to_client{user="hello"} 74294866357 (69.19 GB)
telemt_user_msgs_from_client{user="hello"} 2650856
telemt_user_msgs_to_client{user="hello"} 5095834
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 34662.1 (9h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 39677
telemt_connections_bad_total 339
telemt_handshake_timeouts_total 952
telemt_upstream_connect_attempt_total 36051
telemt_upstream_connect_success_total 36042
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 36051
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30447
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5373
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 222
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 36038
telemt_user_connections_current{user="hello"} 53
telemt_user_octets_from_client{user="hello"} 2002714892 (1.87 GB)
telemt_user_octets_to_client{user="hello"} 38234366264 (35.61 GB)
telemt_user_msgs_from_client{user="hello"} 1567627
telemt_user_msgs_to_client{user="hello"} 9419148
telemt_user_unique_ips_current{user="hello"} 21
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 34662.0 (9h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 62643
telemt_connections_bad_total 455
telemt_handshake_timeouts_total 4085
telemt_upstream_connect_attempt_total 54527
telemt_upstream_connect_success_total 54525
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 54527
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 48997
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5480
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 54521
telemt_user_connections_current{user="hello"} 72
telemt_user_octets_from_client{user="hello"} 1103774993 (1.03 GB)
telemt_user_octets_to_client{user="hello"} 56714385040 (52.82 GB)
telemt_user_msgs_from_client{user="hello"} 1278139
telemt_user_msgs_to_client{user="hello"} 8354137
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 34660.8 (9h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 59305
telemt_connections_bad_total 97
telemt_handshake_timeouts_total 519
telemt_upstream_connect_attempt_total 56755
telemt_upstream_connect_success_total 56602
telemt_upstream_connect_fail_total 153
telemt_upstream_connect_attempts_per_request{bucket="1"} 56755
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 49582
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6844
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 157
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 153
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 56598
telemt_user_connections_current{user="hello"} 86
telemt_user_octets_from_client{user="hello"} 840913622 (801.96 MB)
telemt_user_octets_to_client{user="hello"} 37876053623 (35.27 GB)
telemt_user_msgs_from_client{user="hello"} 1161867
telemt_user_msgs_to_client{user="hello"} 7308717
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 34662.1 (9h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 85994
telemt_connections_bad_total 8276
telemt_handshake_timeouts_total 1470
telemt_upstream_connect_attempt_total 73004
telemt_upstream_connect_success_total 72756
telemt_upstream_connect_fail_total 248
telemt_upstream_connect_attempts_per_request{bucket="1"} 73004
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 62944
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9597
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 215
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 248
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 72752
telemt_user_connections_current{user="hello"} 112
telemt_user_octets_from_client{user="hello"} 2092547396 (1.95 GB)
telemt_user_octets_to_client{user="hello"} 57831802931 (53.86 GB)
telemt_user_msgs_from_client{user="hello"} 2004204
telemt_user_msgs_to_client{user="hello"} 8392184
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 13631.6 (3h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 40
telemt_connections_bad_total 38
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 2
telemt_upstream_connect_success_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
```