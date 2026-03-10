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

# Server Metrics 2026-03-10 21:10:30 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 24262.5 (6h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 87855
telemt_connections_bad_total 3270
telemt_handshake_timeouts_total 2147
telemt_upstream_connect_attempt_total 78504
telemt_upstream_connect_success_total 78473
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 78504
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 71602
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6820
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 78469
telemt_user_connections_current{user="hello"} 250
telemt_user_octets_from_client{user="hello"} 2469218379 (2.30 GB)
telemt_user_octets_to_client{user="hello"} 60721141773 (56.55 GB)
telemt_user_msgs_from_client{user="hello"} 2305292
telemt_user_msgs_to_client{user="hello"} 4141184
telemt_user_unique_ips_current{user="hello"} 64
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 24261.6 (6h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 33575
telemt_connections_bad_total 316
telemt_handshake_timeouts_total 615
telemt_upstream_connect_attempt_total 30618
telemt_upstream_connect_success_total 30610
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 30618
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25846
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4545
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 219
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 30606
telemt_user_connections_current{user="hello"} 85
telemt_user_octets_from_client{user="hello"} 1571271574 (1.46 GB)
telemt_user_octets_to_client{user="hello"} 26499731038 (24.68 GB)
telemt_user_msgs_from_client{user="hello"} 1221159
telemt_user_msgs_to_client{user="hello"} 7574842
telemt_user_unique_ips_current{user="hello"} 21
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 24261.7 (6h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 53718
telemt_connections_bad_total 301
telemt_handshake_timeouts_total 3728
telemt_upstream_connect_attempt_total 46626
telemt_upstream_connect_success_total 46624
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 46626
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42165
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4413
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 46620
telemt_user_connections_current{user="hello"} 90
telemt_user_octets_from_client{user="hello"} 735567157 (701.49 MB)
telemt_user_octets_to_client{user="hello"} 42519471719 (39.60 GB)
telemt_user_msgs_from_client{user="hello"} 995893
telemt_user_msgs_to_client{user="hello"} 6392642
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 24260.3 (6h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 47983
telemt_connections_bad_total 72
telemt_handshake_timeouts_total 315
telemt_upstream_connect_attempt_total 46070
telemt_upstream_connect_success_total 45938
telemt_upstream_connect_fail_total 132
telemt_upstream_connect_attempts_per_request{bucket="1"} 46070
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40452
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5340
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 135
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 132
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 45934
telemt_user_connections_current{user="hello"} 119
telemt_user_octets_from_client{user="hello"} 775902165 (739.96 MB)
telemt_user_octets_to_client{user="hello"} 35489789525 (33.05 GB)
telemt_user_msgs_from_client{user="hello"} 1028285
telemt_user_msgs_to_client{user="hello"} 6705153
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 24261.5 (6h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 68818
telemt_connections_bad_total 6250
telemt_handshake_timeouts_total 1396
telemt_upstream_connect_attempt_total 58352
telemt_upstream_connect_success_total 58108
telemt_upstream_connect_fail_total 244
telemt_upstream_connect_attempts_per_request{bucket="1"} 58352
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 50756
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7161
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 191
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 244
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 58104
telemt_user_connections_current{user="hello"} 173
telemt_user_octets_from_client{user="hello"} 1838761934 (1.71 GB)
telemt_user_octets_to_client{user="hello"} 45319457882 (42.21 GB)
telemt_user_msgs_from_client{user="hello"} 1661460
telemt_user_msgs_to_client{user="hello"} 6237576
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 3231.0 (0h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17
telemt_connections_bad_total 17
telemt_upstream_connect_attempt_total 2
telemt_upstream_connect_success_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
```