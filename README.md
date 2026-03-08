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

# Server Metrics 2026-03-08 08:55:18 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 6395.8 (1h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13821
telemt_connections_bad_total 2313
telemt_handshake_timeouts_total 55
telemt_upstream_connect_attempt_total 10916
telemt_upstream_connect_success_total 10909
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 10916
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10288
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 614
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 10907
telemt_user_connections_current{user="hello"} 121
telemt_user_octets_from_client{user="hello"} 278979079 (266.06 MB)
telemt_user_octets_to_client{user="hello"} 6752911449 (6.29 GB)
telemt_user_msgs_from_client{user="hello"} 254762
telemt_user_msgs_to_client{user="hello"} 341789
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 6395.1 (1h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2973
telemt_connections_bad_total 48
telemt_handshake_timeouts_total 7
telemt_upstream_connect_attempt_total 2828
telemt_upstream_connect_success_total 2828
telemt_upstream_connect_attempts_per_request{bucket="1"} 2828
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2655
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 158
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2826
telemt_user_connections_current{user="hello"} 29
telemt_user_octets_from_client{user="hello"} 37671784 (35.93 MB)
telemt_user_octets_to_client{user="hello"} 2093470666 (1.95 GB)
telemt_user_msgs_from_client{user="hello"} 70268
telemt_user_msgs_to_client{user="hello"} 522115
telemt_user_unique_ips_current{user="hello"} 10
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 6394.8 (1h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2498
telemt_connections_bad_total 9
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 2429
telemt_upstream_connect_success_total 2429
telemt_upstream_connect_attempts_per_request{bucket="1"} 2429
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2194
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 233
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2427
telemt_user_connections_current{user="hello"} 7
telemt_user_octets_from_client{user="hello"} 26102011 (24.89 MB)
telemt_user_octets_to_client{user="hello"} 483439480 (461.04 MB)
telemt_user_msgs_from_client{user="hello"} 22176
telemt_user_msgs_to_client{user="hello"} 91583
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 6394.5 (1h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2317
telemt_connections_bad_total 28
telemt_handshake_timeouts_total 19
telemt_upstream_connect_attempt_total 2221
telemt_upstream_connect_success_total 2217
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 2221
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2065
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 141
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2215
telemt_user_connections_current{user="hello"} 28
telemt_user_octets_from_client{user="hello"} 50852505 (48.50 MB)
telemt_user_octets_to_client{user="hello"} 684608340 (652.89 MB)
telemt_user_msgs_from_client{user="hello"} 38430
telemt_user_msgs_to_client{user="hello"} 182322
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 6394.8 (1h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4009
telemt_connections_bad_total 1190
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 2787
telemt_upstream_connect_success_total 2787
telemt_upstream_connect_attempts_per_request{bucket="1"} 2787
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2259
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 526
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2785
telemt_user_connections_current{user="hello"} 22
telemt_user_octets_from_client{user="hello"} 36868931 (35.16 MB)
telemt_user_octets_to_client{user="hello"} 2796132674 (2.60 GB)
telemt_user_msgs_from_client{user="hello"} 62271
telemt_user_msgs_to_client{user="hello"} 291864
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 2
```