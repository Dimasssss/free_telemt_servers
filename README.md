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

# Server Metrics 2026-03-09 18:42:07 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 69736.3 (19h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 132611
telemt_connections_bad_total 1800
telemt_handshake_timeouts_total 1112
telemt_upstream_connect_attempt_total 124112
telemt_upstream_connect_success_total 124069
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 124112
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 114321
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9687
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 124061
telemt_user_connections_current{user="hello"} 242
telemt_user_octets_from_client{user="hello"} 3523791687 (3.28 GB)
telemt_user_octets_to_client{user="hello"} 69063867996 (64.32 GB)
telemt_user_msgs_from_client{user="hello"} 3171763
telemt_user_msgs_to_client{user="hello"} 4400935
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 69735.0 (19h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 38381
telemt_connections_bad_total 233
telemt_handshake_timeouts_total 453
telemt_upstream_connect_attempt_total 36019
telemt_upstream_connect_success_total 35998
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 36019
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32456
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3230
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 312
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 35990
telemt_user_connections_current{user="hello"} 71
telemt_user_octets_from_client{user="hello"} 1079314392 (1.01 GB)
telemt_user_octets_to_client{user="hello"} 17789005259 (16.57 GB)
telemt_user_msgs_from_client{user="hello"} 963883
telemt_user_msgs_to_client{user="hello"} 5016798
telemt_user_unique_ips_current{user="hello"} 18
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 69735.8 (19h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 47936
telemt_connections_bad_total 699
telemt_handshake_timeouts_total 2338
telemt_upstream_connect_attempt_total 37429
telemt_upstream_connect_success_total 37429
telemt_upstream_connect_attempts_per_request{bucket="1"} 37429
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33315
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4108
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 37421
telemt_user_connections_current{user="hello"} 71
telemt_user_octets_from_client{user="hello"} 4649234465 (4.33 GB)
telemt_user_octets_to_client{user="hello"} 27367300753 (25.49 GB)
telemt_user_msgs_from_client{user="hello"} 2277403
telemt_user_msgs_to_client{user="hello"} 3873273
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 69730.3 (19h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 53948
telemt_connections_bad_total 253
telemt_handshake_timeouts_total 913
telemt_upstream_connect_attempt_total 49372
telemt_upstream_connect_success_total 49250
telemt_upstream_connect_fail_total 122
telemt_upstream_connect_attempts_per_request{bucket="1"} 49372
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42625
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6477
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 121
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 122
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 49242
telemt_user_connections_current{user="hello"} 89
telemt_user_octets_from_client{user="hello"} 2106634475 (1.96 GB)
telemt_user_octets_to_client{user="hello"} 38586465686 (35.94 GB)
telemt_user_msgs_from_client{user="hello"} 1495424
telemt_user_msgs_to_client{user="hello"} 9291989
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 69735.8 (19h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 87099
telemt_connections_bad_total 16460
telemt_handshake_timeouts_total 2254
telemt_upstream_connect_attempt_total 64505
telemt_upstream_connect_success_total 64503
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 64505
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 54807
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9627
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 69
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 64495
telemt_user_connections_current{user="hello"} 139
telemt_user_octets_from_client{user="hello"} 1095407522 (1.02 GB)
telemt_user_octets_to_client{user="hello"} 59140582830 (55.08 GB)
telemt_user_msgs_from_client{user="hello"} 1477015
telemt_user_msgs_to_client{user="hello"} 7649664
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 27
```