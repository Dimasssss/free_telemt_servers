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

# Server Metrics 2026-03-04 09:09:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.2.0

telemt_uptime_seconds 2779.8 (0h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4940
telemt_connections_bad_total 7
telemt_handshake_timeouts_total 86
telemt_upstream_connect_attempt_total 4185
telemt_upstream_connect_success_total 4185
telemt_upstream_connect_attempts_per_request{bucket="1"} 4185
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3873
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 311
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4183
telemt_user_connections_current{user="hello"} 106
telemt_user_octets_from_client{user="hello"} 56953422 (54.32 MB)
telemt_user_octets_to_client{user="hello"} 2214585801 (2.06 GB)
telemt_user_msgs_from_client{user="hello"} 84853
telemt_user_msgs_to_client{user="hello"} 375758
telemt_user_unique_ips_current{user="hello"} 6
```

## psb.hosting

```
telemt 3.2.0

telemt_uptime_seconds 2790.9 (0h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 373
telemt_connections_bad_total 13
telemt_upstream_connect_attempt_total 356
telemt_upstream_connect_success_total 356
telemt_upstream_connect_attempts_per_request{bucket="1"} 356
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 344
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 354
telemt_user_connections_current{user="hello"} 17
telemt_user_octets_from_client{user="hello"} 4775960 (4.55 MB)
telemt_user_octets_to_client{user="hello"} 131588971 (125.49 MB)
telemt_user_msgs_from_client{user="hello"} 9416
telemt_user_msgs_to_client{user="hello"} 41403
telemt_user_unique_ips_current{user="hello"} 2
```

## koara.io

```
telemt 3.2.0

telemt_uptime_seconds 2775.4 (0h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 408
telemt_connections_bad_total 56
telemt_upstream_connect_attempt_total 340
telemt_upstream_connect_success_total 340
telemt_upstream_connect_attempts_per_request{bucket="1"} 340
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 308
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 338
telemt_user_connections_current{user="hello"} 10
telemt_user_octets_from_client{user="hello"} 2572224 (2.45 MB)
telemt_user_octets_to_client{user="hello"} 193376282 (184.42 MB)
telemt_user_msgs_from_client{user="hello"} 6734
telemt_user_msgs_to_client{user="hello"} 40142
telemt_user_unique_ips_current{user="hello"} 1
```

## landvps.ru

```
telemt 3.2.0

telemt_uptime_seconds 2766.1 (0h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 889
telemt_connections_bad_total 24
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 798
telemt_upstream_connect_success_total 798
telemt_upstream_connect_attempts_per_request{bucket="1"} 798
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 758
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 796
telemt_user_connections_current{user="hello"} 15
telemt_user_octets_from_client{user="hello"} 2807575 (2.68 MB)
telemt_user_octets_to_client{user="hello"} 91067156 (86.85 MB)
telemt_user_msgs_from_client{user="hello"} 5836
telemt_user_msgs_to_client{user="hello"} 30933
telemt_user_unique_ips_current{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.2.0

telemt_uptime_seconds 2777.5 (0h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1164
telemt_connections_bad_total 490
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 626
telemt_upstream_connect_success_total 626
telemt_upstream_connect_attempts_per_request{bucket="1"} 626
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 522
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 104
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 624
telemt_user_connections_current{user="hello"} 7
telemt_user_octets_from_client{user="hello"} 8791060 (8.38 MB)
telemt_user_octets_to_client{user="hello"} 341233199 (325.43 MB)
telemt_user_msgs_from_client{user="hello"} 19555
telemt_user_msgs_to_client{user="hello"} 89018
telemt_user_unique_ips_current{user="hello"} 2
```