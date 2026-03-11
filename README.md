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

# Server Metrics 2026-03-11 22:54:12 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 4164.8 (1h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6918
telemt_connections_bad_total 70
telemt_handshake_timeouts_total 57
telemt_upstream_connect_attempt_total 6615
telemt_upstream_connect_success_total 6611
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 6615
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5824
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 784
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6609
telemt_user_connections_current{user="hello"} 209
telemt_user_octets_from_client{user="hello"} 82761121 (78.93 MB)
telemt_user_octets_to_client{user="hello"} 2910496653 (2.71 GB)
telemt_user_msgs_from_client{user="hello"} 148908
telemt_user_msgs_to_client{user="hello"} 438378
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 4153.1 (1h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2663
telemt_connections_bad_total 3
telemt_handshake_timeouts_total 17
telemt_upstream_connect_attempt_total 2539
telemt_upstream_connect_success_total 2539
telemt_upstream_connect_attempts_per_request{bucket="1"} 2539
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2318
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 221
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2537
telemt_user_connections_current{user="hello"} 80
telemt_user_octets_from_client{user="hello"} 13878897 (13.24 MB)
telemt_user_octets_to_client{user="hello"} 349535206 (333.34 MB)
telemt_user_msgs_from_client{user="hello"} 34172
telemt_user_msgs_to_client{user="hello"} 156924
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 4126.7 (1h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5513
telemt_connections_bad_total 245
telemt_handshake_timeouts_total 108
telemt_upstream_connect_attempt_total 4474
telemt_upstream_connect_success_total 4474
telemt_upstream_connect_attempts_per_request{bucket="1"} 4474
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3895
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 579
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4472
telemt_user_connections_current{user="hello"} 32
telemt_user_octets_from_client{user="hello"} 25902959 (24.70 MB)
telemt_user_octets_to_client{user="hello"} 2356458230 (2.19 GB)
telemt_user_msgs_from_client{user="hello"} 84602
telemt_user_msgs_to_client{user="hello"} 633660
telemt_user_unique_ips_current{user="hello"} 22
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 4152.0 (1h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4107
telemt_connections_bad_total 10
telemt_handshake_timeouts_total 52
telemt_upstream_connect_attempt_total 3926
telemt_upstream_connect_success_total 3922
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 3926
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3365
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 543
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3920
telemt_user_connections_current{user="hello"} 86
telemt_user_octets_from_client{user="hello"} 34509262 (32.91 MB)
telemt_user_octets_to_client{user="hello"} 1282322629 (1.19 GB)
telemt_user_msgs_from_client{user="hello"} 62911
telemt_user_msgs_to_client{user="hello"} 488599
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 4153.3 (1h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4171
telemt_connections_bad_total 834
telemt_handshake_timeouts_total 5
telemt_upstream_connect_attempt_total 3272
telemt_upstream_connect_success_total 3272
telemt_upstream_connect_attempts_per_request{bucket="1"} 3272
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2962
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 301
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3270
telemt_user_connections_current{user="hello"} 61
telemt_user_octets_from_client{user="hello"} 41027011 (39.13 MB)
telemt_user_octets_to_client{user="hello"} 1355986865 (1.26 GB)
telemt_user_msgs_from_client{user="hello"} 48742
telemt_user_msgs_to_client{user="hello"} 246718
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 4153.0 (1h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4303
telemt_connections_bad_total 7
telemt_handshake_timeouts_total 89
telemt_upstream_connect_attempt_total 3607
telemt_upstream_connect_success_total 3607
telemt_upstream_connect_attempts_per_request{bucket="1"} 3607
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3012
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 595
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3605
telemt_user_connections_current{user="hello"} 42
telemt_user_octets_from_client{user="hello"} 73152485 (69.76 MB)
telemt_user_octets_to_client{user="hello"} 10655295058 (9.92 GB)
telemt_user_msgs_from_client{user="hello"} 125850
telemt_user_msgs_to_client{user="hello"} 707674
telemt_user_unique_ips_current{user="hello"} 11
telemt_user_unique_ips_recent_window{user="hello"} 5
```