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

# Server Metrics 2026-03-11 19:29:38 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 8959.5 (2h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 34659
telemt_connections_bad_total 1957
telemt_handshake_timeouts_total 138
telemt_upstream_connect_attempt_total 31256
telemt_upstream_connect_success_total 31247
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 31256
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28230
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2968
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 31245
telemt_user_connections_current{user="hello"} 298
telemt_user_octets_from_client{user="hello"} 811190368 (773.61 MB)
telemt_user_octets_to_client{user="hello"} 18890420388 (17.59 GB)
telemt_user_msgs_from_client{user="hello"} 804234
telemt_user_msgs_to_client{user="hello"} 1552572
telemt_user_unique_ips_current{user="hello"} 72
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 8947.9 (2h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16389
telemt_connections_bad_total 34
telemt_handshake_timeouts_total 246
telemt_upstream_connect_attempt_total 14976
telemt_upstream_connect_success_total 14974
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 14976
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12927
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1747
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 300
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 14972
telemt_user_connections_current{user="hello"} 148
telemt_user_octets_from_client{user="hello"} 201343456 (192.02 MB)
telemt_user_octets_to_client{user="hello"} 8485217934 (7.90 GB)
telemt_user_msgs_from_client{user="hello"} 328004
telemt_user_msgs_to_client{user="hello"} 3263642
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 8967.9 (2h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19255
telemt_connections_bad_total 24
telemt_handshake_timeouts_total 158
telemt_upstream_connect_attempt_total 17984
telemt_upstream_connect_success_total 17982
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 17984
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16397
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1568
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 17980
telemt_user_connections_current{user="hello"} 94
telemt_user_octets_from_client{user="hello"} 191101222 (182.25 MB)
telemt_user_octets_to_client{user="hello"} 8489259924 (7.91 GB)
telemt_user_msgs_from_client{user="hello"} 371507
telemt_user_msgs_to_client{user="hello"} 2086718
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 8963.2 (2h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20829
telemt_connections_bad_total 1501
telemt_handshake_timeouts_total 371
telemt_upstream_connect_attempt_total 18050
telemt_upstream_connect_success_total 17995
telemt_upstream_connect_fail_total 55
telemt_upstream_connect_attempts_per_request{bucket="1"} 18050
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16303
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1633
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 55
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 17993
telemt_user_connections_current{user="hello"} 141
telemt_user_octets_from_client{user="hello"} 575823189 (549.15 MB)
telemt_user_octets_to_client{user="hello"} 10585047503 (9.86 GB)
telemt_user_msgs_from_client{user="hello"} 454056
telemt_user_msgs_to_client{user="hello"} 2792391
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 8971.5 (2h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21851
telemt_connections_bad_total 1734
telemt_handshake_timeouts_total 157
telemt_upstream_connect_attempt_total 19197
telemt_upstream_connect_success_total 19196
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 19197
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16734
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2441
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 19194
telemt_user_connections_current{user="hello"} 128
telemt_user_octets_from_client{user="hello"} 334306285 (318.82 MB)
telemt_user_octets_to_client{user="hello"} 7214072299 (6.72 GB)
telemt_user_msgs_from_client{user="hello"} 420166
telemt_user_msgs_to_client{user="hello"} 2373874
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 83577.8 (23h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 527
telemt_connections_bad_total 491
telemt_handshake_timeouts_total 17
telemt_upstream_connect_attempt_total 22
telemt_upstream_connect_success_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 22
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 14
telemt_user_octets_from_client{user="hello"} 8621 (8.42 KB)
telemt_user_octets_to_client{user="hello"} 3281 (3.20 KB)
telemt_user_msgs_from_client{user="hello"} 26
telemt_user_msgs_to_client{user="hello"} 18
```