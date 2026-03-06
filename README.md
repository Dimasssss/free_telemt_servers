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

# Server Metrics 2026-03-06 05:35:20 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.2

telemt_uptime_seconds 26399.0 (7h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 78372
telemt_connections_bad_total 51938
telemt_handshake_timeouts_total 2444
telemt_upstream_connect_attempt_total 22447
telemt_upstream_connect_success_total 22444
telemt_upstream_connect_attempts_per_request{bucket="1"} 22441
telemt_upstream_connect_attempts_per_request{bucket="2"} 3
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21055
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1382
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 22440
telemt_user_connections_current{user="hello"} 101
telemt_user_octets_from_client{user="hello"} 298733380 (284.89 MB)
telemt_user_octets_to_client{user="hello"} 20143103147 (18.76 GB)
telemt_user_msgs_from_client{user="hello"} 557731
telemt_user_msgs_to_client{user="hello"} 3022502
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## psb.hosting

```
telemt 3.3.2

telemt_uptime_seconds 26396.9 (7h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2955
telemt_connections_bad_total 143
telemt_handshake_timeouts_total 17
telemt_upstream_connect_attempt_total 2760
telemt_upstream_connect_success_total 2759
telemt_upstream_connect_attempts_per_request{bucket="1"} 2758
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2651
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 105
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2757
telemt_user_connections_current{user="hello"} 26
telemt_user_octets_from_client{user="hello"} 58805940 (56.08 MB)
telemt_user_octets_to_client{user="hello"} 1249386568 (1.16 GB)
telemt_user_msgs_from_client{user="hello"} 83209
telemt_user_msgs_to_client{user="hello"} 396558
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## koara.io

```
telemt 3.3.2

telemt_uptime_seconds 26397.2 (7h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1857
telemt_connections_bad_total 214
telemt_handshake_timeouts_total 8
telemt_upstream_connect_attempt_total 1622
telemt_upstream_connect_success_total 1622
telemt_upstream_connect_attempts_per_request{bucket="1"} 1622
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1455
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 167
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1618
telemt_user_connections_current{user="hello"} 10
telemt_user_octets_from_client{user="hello"} 39878450 (38.03 MB)
telemt_user_octets_to_client{user="hello"} 1966407394 (1.83 GB)
telemt_user_msgs_from_client{user="hello"} 54526
telemt_user_msgs_to_client{user="hello"} 400853
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## landvps.ru

```
telemt 3.3.2

telemt_uptime_seconds 26399.9 (7h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3854
telemt_connections_bad_total 138
telemt_handshake_timeouts_total 309
telemt_upstream_connect_attempt_total 3259
telemt_upstream_connect_success_total 3259
telemt_upstream_connect_attempts_per_request{bucket="1"} 3259
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2817
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 423
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3255
telemt_user_connections_current{user="hello"} 20
telemt_user_octets_from_client{user="hello"} 98271361 (93.72 MB)
telemt_user_octets_to_client{user="hello"} 5768601945 (5.37 GB)
telemt_user_msgs_from_client{user="hello"} 141474
telemt_user_msgs_to_client{user="hello"} 1223136
telemt_user_unique_ips_current{user="hello"} 3
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## rdp-onedash.ru

```
telemt 3.3.2

telemt_uptime_seconds 26399.7 (7h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8893
telemt_connections_bad_total 4794
telemt_handshake_timeouts_total 159
telemt_upstream_connect_attempt_total 3836
telemt_upstream_connect_success_total 3836
telemt_upstream_connect_attempts_per_request{bucket="1"} 3836
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3276
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 555
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3832
telemt_user_connections_current{user="hello"} 12
telemt_user_octets_from_client{user="hello"} 78498067 (74.86 MB)
telemt_user_octets_to_client{user="hello"} 15948242388 (14.85 GB)
telemt_user_msgs_from_client{user="hello"} 200429
telemt_user_msgs_to_client{user="hello"} 3039855
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 3
```