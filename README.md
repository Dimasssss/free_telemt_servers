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

# Server Metrics 2026-03-08 07:33:10 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 1468.5 (0h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2523
telemt_connections_bad_total 18
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 2424
telemt_upstream_connect_success_total 2423
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 2424
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2288
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 133
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2421
telemt_user_connections_current{user="hello"} 174
telemt_user_octets_from_client{user="hello"} 40846281 (38.95 MB)
telemt_user_octets_to_client{user="hello"} 751210855 (716.41 MB)
telemt_user_msgs_from_client{user="hello"} 53282
telemt_user_msgs_to_client{user="hello"} 61396
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 1467.7 (0h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 433
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 420
telemt_upstream_connect_success_total 420
telemt_upstream_connect_attempts_per_request{bucket="1"} 420
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 403
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 418
telemt_user_connections_current{user="hello"} 9
telemt_user_octets_from_client{user="hello"} 6263225 (5.97 MB)
telemt_user_octets_to_client{user="hello"} 275997132 (263.21 MB)
telemt_user_msgs_from_client{user="hello"} 11069
telemt_user_msgs_to_client{user="hello"} 66288
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 1467.3 (0h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 421
telemt_connections_bad_total 3
telemt_upstream_connect_attempt_total 408
telemt_upstream_connect_success_total 408
telemt_upstream_connect_attempts_per_request{bucket="1"} 408
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 374
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 406
telemt_user_connections_current{user="hello"} 15
telemt_user_octets_from_client{user="hello"} 1893415 (1.81 MB)
telemt_user_octets_to_client{user="hello"} 164305665 (156.69 MB)
telemt_user_msgs_from_client{user="hello"} 4238
telemt_user_msgs_to_client{user="hello"} 22399
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 1467.3 (0h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 561
telemt_connections_bad_total 2
telemt_handshake_timeouts_total 9
telemt_upstream_connect_attempt_total 539
telemt_upstream_connect_success_total 539
telemt_upstream_connect_attempts_per_request{bucket="1"} 539
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 501
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 537
telemt_user_connections_current{user="hello"} 29
telemt_user_octets_from_client{user="hello"} 22911009 (21.85 MB)
telemt_user_octets_to_client{user="hello"} 112026597 (106.84 MB)
telemt_user_msgs_from_client{user="hello"} 7923
telemt_user_msgs_to_client{user="hello"} 32141
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 1467.6 (0h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1109
telemt_connections_bad_total 263
telemt_upstream_connect_attempt_total 838
telemt_upstream_connect_success_total 838
telemt_upstream_connect_attempts_per_request{bucket="1"} 838
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 700
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 137
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 836
telemt_user_connections_current{user="hello"} 16
telemt_user_octets_from_client{user="hello"} 6621203 (6.31 MB)
telemt_user_octets_to_client{user="hello"} 222932245 (212.60 MB)
telemt_user_msgs_from_client{user="hello"} 11046
telemt_user_msgs_to_client{user="hello"} 34019
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 2
```