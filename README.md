# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt  
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

-----

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

# Server Metrics 2026-03-06 03:47:35 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.2

telemt_uptime_seconds 19934.7 (5h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 69953
telemt_connections_bad_total 51933
telemt_handshake_timeouts_total 2423
telemt_upstream_connect_attempt_total 14246
telemt_upstream_connect_success_total 14244
telemt_upstream_connect_attempts_per_request{bucket="1"} 14242
telemt_upstream_connect_attempts_per_request{bucket="2"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13383
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 857
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 14242
telemt_user_connections_current{user="hello"} 85
telemt_user_octets_from_client{user="hello"} 191672642 (182.79 MB)
telemt_user_octets_to_client{user="hello"} 13325739290 (12.41 GB)
telemt_user_msgs_from_client{user="hello"} 341885
telemt_user_msgs_to_client{user="hello"} 1965848
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## psb.hosting

```
telemt 3.3.2

telemt_uptime_seconds 19932.6 (5h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1885
telemt_connections_bad_total 141
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 1719
telemt_upstream_connect_success_total 1718
telemt_upstream_connect_attempts_per_request{bucket="1"} 1717
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1660
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 55
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1716
telemt_user_connections_current{user="hello"} 39
telemt_user_octets_from_client{user="hello"} 49458311 (47.17 MB)
telemt_user_octets_to_client{user="hello"} 882227313 (841.36 MB)
telemt_user_msgs_from_client{user="hello"} 62850
telemt_user_msgs_to_client{user="hello"} 271114
telemt_user_unique_ips_current{user="hello"} 10
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## koara.io

```
telemt 3.3.2

telemt_uptime_seconds 19933.0 (5h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1290
telemt_connections_bad_total 194
telemt_handshake_timeouts_total 5
telemt_upstream_connect_attempt_total 1087
telemt_upstream_connect_success_total 1087
telemt_upstream_connect_attempts_per_request{bucket="1"} 1087
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 931
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 156
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1083
telemt_user_connections_current{user="hello"} 6
telemt_user_octets_from_client{user="hello"} 36197089 (34.52 MB)
telemt_user_octets_to_client{user="hello"} 1711985807 (1.59 GB)
telemt_user_msgs_from_client{user="hello"} 45129
telemt_user_msgs_to_client{user="hello"} 341353
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.2

telemt_uptime_seconds 19935.8 (5h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2568
telemt_connections_bad_total 127
telemt_handshake_timeouts_total 298
telemt_upstream_connect_attempt_total 2076
telemt_upstream_connect_success_total 2076
telemt_upstream_connect_attempts_per_request{bucket="1"} 2076
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1706
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 364
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2072
telemt_user_connections_current{user="hello"} 2
telemt_user_octets_from_client{user="hello"} 94403768 (90.03 MB)
telemt_user_octets_to_client{user="hello"} 5625300156 (5.24 GB)
telemt_user_msgs_from_client{user="hello"} 132073
telemt_user_msgs_to_client{user="hello"} 1177531
telemt_user_unique_ips_current{user="hello"} 2
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.3.2

telemt_uptime_seconds 19935.6 (5h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6448
telemt_connections_bad_total 3638
telemt_handshake_timeouts_total 142
telemt_upstream_connect_attempt_total 2606
telemt_upstream_connect_success_total 2606
telemt_upstream_connect_attempts_per_request{bucket="1"} 2606
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2284
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 320
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2604
telemt_user_connections_current{user="hello"} 16
telemt_user_octets_from_client{user="hello"} 50053455 (47.73 MB)
telemt_user_octets_to_client{user="hello"} 11286870983 (10.51 GB)
telemt_user_msgs_from_client{user="hello"} 132306
telemt_user_msgs_to_client{user="hello"} 2050468
telemt_user_unique_ips_current{user="hello"} 3
telemt_user_unique_ips_recent_window{user="hello"} 2
```