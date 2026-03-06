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

# Server Metrics 2026-03-06 04:49:11 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.2

telemt_uptime_seconds 23630.1 (6h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 74743
telemt_connections_bad_total 51935
telemt_handshake_timeouts_total 2441
telemt_upstream_connect_attempt_total 18874
telemt_upstream_connect_success_total 18872
telemt_upstream_connect_attempts_per_request{bucket="1"} 18870
telemt_upstream_connect_attempts_per_request{bucket="2"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17722
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1146
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 18868
telemt_user_connections_current{user="hello"} 103
telemt_user_octets_from_client{user="hello"} 250604350 (238.99 MB)
telemt_user_octets_to_client{user="hello"} 16911631538 (15.75 GB)
telemt_user_msgs_from_client{user="hello"} 459914
telemt_user_msgs_to_client{user="hello"} 2518701
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## psb.hosting

```
telemt 3.3.2

telemt_uptime_seconds 23627.6 (6h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2501
telemt_connections_bad_total 142
telemt_handshake_timeouts_total 12
telemt_upstream_connect_attempt_total 2315
telemt_upstream_connect_success_total 2314
telemt_upstream_connect_attempts_per_request{bucket="1"} 2313
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2218
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 93
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2312
telemt_user_connections_current{user="hello"} 32
telemt_user_octets_from_client{user="hello"} 54753900 (52.22 MB)
telemt_user_octets_to_client{user="hello"} 1058318227 (1009.29 MB)
telemt_user_msgs_from_client{user="hello"} 75279
telemt_user_msgs_to_client{user="hello"} 338105
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## koara.io

```
telemt 3.3.2

telemt_uptime_seconds 23628.0 (6h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1520
telemt_connections_bad_total 196
telemt_handshake_timeouts_total 5
telemt_upstream_connect_attempt_total 1311
telemt_upstream_connect_success_total 1311
telemt_upstream_connect_attempts_per_request{bucket="1"} 1311
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1147
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 164
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1307
telemt_user_connections_current{user="hello"} 4
telemt_user_octets_from_client{user="hello"} 37315798 (35.59 MB)
telemt_user_octets_to_client{user="hello"} 1774510321 (1.65 GB)
telemt_user_msgs_from_client{user="hello"} 48095
telemt_user_msgs_to_client{user="hello"} 357291
telemt_user_unique_ips_current{user="hello"} 4
```

## landvps.ru

```
telemt 3.3.2

telemt_uptime_seconds 23630.9 (6h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3165
telemt_connections_bad_total 134
telemt_handshake_timeouts_total 303
telemt_upstream_connect_attempt_total 2650
telemt_upstream_connect_success_total 2650
telemt_upstream_connect_attempts_per_request{bucket="1"} 2650
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2252
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 387
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2646
telemt_user_connections_current{user="hello"} 1
telemt_user_octets_from_client{user="hello"} 96160365 (91.71 MB)
telemt_user_octets_to_client{user="hello"} 5686849415 (5.30 GB)
telemt_user_msgs_from_client{user="hello"} 136255
telemt_user_msgs_to_client{user="hello"} 1196512
telemt_user_unique_ips_current{user="hello"} 1
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.3.2

telemt_uptime_seconds 23630.6 (6h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7969
telemt_connections_bad_total 4300
telemt_handshake_timeouts_total 153
telemt_upstream_connect_attempt_total 3424
telemt_upstream_connect_success_total 3424
telemt_upstream_connect_attempts_per_request{bucket="1"} 3424
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2934
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 485
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3422
telemt_user_connections_current{user="hello"} 27
telemt_user_octets_from_client{user="hello"} 67336855 (64.22 MB)
telemt_user_octets_to_client{user="hello"} 12985571347 (12.09 GB)
telemt_user_msgs_from_client{user="hello"} 171247
telemt_user_msgs_to_client{user="hello"} 2423867
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 2
```