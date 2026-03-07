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

# Server Metrics 2026-03-07 17:05:35 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.10

telemt_uptime_seconds 1225.9 (0h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2743
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 25
telemt_upstream_connect_attempt_total 2652
telemt_upstream_connect_success_total 2652
telemt_upstream_connect_attempts_per_request{bucket="1"} 2652
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2505
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 146
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2650
telemt_user_connections_current{user="hello"} 173
telemt_user_octets_from_client{user="hello"} 39500956 (37.67 MB)
telemt_user_octets_to_client{user="hello"} 820329969 (782.33 MB)
telemt_user_msgs_from_client{user="hello"} 50739
telemt_user_msgs_to_client{user="hello"} 140147
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## psb.hosting

```
telemt 3.3.10

telemt_uptime_seconds 1224.9 (0h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 624
telemt_connections_bad_total 3
telemt_upstream_connect_attempt_total 615
telemt_upstream_connect_success_total 615
telemt_upstream_connect_attempts_per_request{bucket="1"} 615
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 563
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 46
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 613
telemt_user_connections_current{user="hello"} 70
telemt_user_octets_from_client{user="hello"} 11619883 (11.08 MB)
telemt_user_octets_to_client{user="hello"} 506764403 (483.29 MB)
telemt_user_msgs_from_client{user="hello"} 18828
telemt_user_msgs_to_client{user="hello"} 144906
telemt_user_unique_ips_current{user="hello"} 10
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## koara.io

```
telemt 3.3.10

telemt_uptime_seconds 1224.7 (0h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 216
telemt_connections_bad_total 1
telemt_upstream_connect_attempt_total 215
telemt_upstream_connect_success_total 215
telemt_upstream_connect_attempts_per_request{bucket="1"} 215
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 193
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 213
telemt_user_connections_current{user="hello"} 10
telemt_user_octets_from_client{user="hello"} 1545698 (1.47 MB)
telemt_user_octets_to_client{user="hello"} 128341923 (122.40 MB)
telemt_user_msgs_from_client{user="hello"} 4097
telemt_user_msgs_to_client{user="hello"} 25474
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.10

telemt_uptime_seconds 1053.0 (0h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 304
telemt_connections_bad_total 2
telemt_upstream_connect_attempt_total 298
telemt_upstream_connect_success_total 298
telemt_upstream_connect_attempts_per_request{bucket="1"} 298
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 253
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 296
telemt_user_connections_current{user="hello"} 29
telemt_user_octets_from_client{user="hello"} 3124596 (2.98 MB)
telemt_user_octets_to_client{user="hello"} 114769386 (109.45 MB)
telemt_user_msgs_from_client{user="hello"} 4471
telemt_user_msgs_to_client{user="hello"} 30510
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.10

telemt_uptime_seconds 1224.9 (0h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 750
telemt_connections_bad_total 224
telemt_handshake_timeouts_total 6
telemt_upstream_connect_attempt_total 504
telemt_upstream_connect_success_total 504
telemt_upstream_connect_attempts_per_request{bucket="1"} 504
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 341
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 153
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 502
telemt_user_connections_current{user="hello"} 27
telemt_user_octets_from_client{user="hello"} 5116313 (4.88 MB)
telemt_user_octets_to_client{user="hello"} 238596593 (227.54 MB)
telemt_user_msgs_from_client{user="hello"} 12623
telemt_user_msgs_to_client{user="hello"} 56326
telemt_user_unique_ips_current{user="hello"} 10
telemt_user_unique_ips_recent_window{user="hello"} 6
```