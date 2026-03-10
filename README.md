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

# Server Metrics 2026-03-10 15:20:32 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 3264.0 (0h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15800
telemt_connections_bad_total 218
telemt_handshake_timeouts_total 50
telemt_upstream_connect_attempt_total 14798
telemt_upstream_connect_success_total 14795
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 14798
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13659
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1134
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 14793
telemt_user_connections_current{user="hello"} 364
telemt_user_octets_from_client{user="hello"} 222942396 (212.61 MB)
telemt_user_octets_to_client{user="hello"} 8405408307 (7.83 GB)
telemt_user_msgs_from_client{user="hello"} 310131
telemt_user_msgs_to_client{user="hello"} 542211
telemt_user_unique_ips_current{user="hello"} 72
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 3263.4 (0h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4622
telemt_connections_bad_total 45
telemt_handshake_timeouts_total 112
telemt_upstream_connect_attempt_total 4242
telemt_upstream_connect_success_total 4242
telemt_upstream_connect_attempts_per_request{bucket="1"} 4242
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3686
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 546
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4240
telemt_user_connections_current{user="hello"} 81
telemt_user_octets_from_client{user="hello"} 94654915 (90.27 MB)
telemt_user_octets_to_client{user="hello"} 4009600634 (3.73 GB)
telemt_user_msgs_from_client{user="hello"} 126179
telemt_user_msgs_to_client{user="hello"} 1184570
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 3263.0 (0h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7738
telemt_connections_bad_total 5
telemt_handshake_timeouts_total 247
telemt_upstream_connect_attempt_total 7173
telemt_upstream_connect_success_total 7173
telemt_upstream_connect_attempts_per_request{bucket="1"} 7173
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6342
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 831
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7171
telemt_user_connections_current{user="hello"} 95
telemt_user_octets_from_client{user="hello"} 52711906 (50.27 MB)
telemt_user_octets_to_client{user="hello"} 1384170374 (1.29 GB)
telemt_user_msgs_from_client{user="hello"} 107017
telemt_user_msgs_to_client{user="hello"} 355166
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 3261.9 (0h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7452
telemt_connections_bad_total 5
telemt_handshake_timeouts_total 116
telemt_upstream_connect_attempt_total 7094
telemt_upstream_connect_success_total 7076
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 7094
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6158
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 893
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7074
telemt_user_connections_current{user="hello"} 194
telemt_user_octets_from_client{user="hello"} 140476261 (133.97 MB)
telemt_user_octets_to_client{user="hello"} 5957614181 (5.55 GB)
telemt_user_msgs_from_client{user="hello"} 146008
telemt_user_msgs_to_client{user="hello"} 962968
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 3263.3 (0h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10597
telemt_connections_bad_total 831
telemt_handshake_timeouts_total 210
telemt_upstream_connect_attempt_total 9151
telemt_upstream_connect_success_total 9149
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 9151
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8150
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 988
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9147
telemt_user_connections_current{user="hello"} 208
telemt_user_octets_from_client{user="hello"} 572251734 (545.74 MB)
telemt_user_octets_to_client{user="hello"} 5596604736 (5.21 GB)
telemt_user_msgs_from_client{user="hello"} 331347
telemt_user_msgs_to_client{user="hello"} 625344
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 25
```