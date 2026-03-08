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

# Server Metrics 2026-03-08 04:23:16 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.10

telemt_uptime_seconds 41886.0 (11h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 60203
telemt_connections_bad_total 6026
telemt_handshake_timeouts_total 439
telemt_upstream_connect_attempt_total 50576
telemt_upstream_connect_success_total 50569
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 50576
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 47965
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2583
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 50565
telemt_user_connections_current{user="hello"} 127
telemt_user_octets_from_client{user="hello"} 2389611646 (2.23 GB)
telemt_user_octets_to_client{user="hello"} 33305085955 (31.02 GB)
telemt_user_msgs_from_client{user="hello"} 1556213
telemt_user_msgs_to_client{user="hello"} 5218548
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## psb.hosting

```
telemt 3.3.10

telemt_uptime_seconds 41885.2 (11h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8134
telemt_connections_bad_total 368
telemt_handshake_timeouts_total 20
telemt_upstream_connect_attempt_total 7627
telemt_upstream_connect_success_total 7619
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 7627
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6952
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 617
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7613
telemt_user_connections_current{user="hello"} 8
telemt_user_octets_from_client{user="hello"} 191356516 (182.49 MB)
telemt_user_octets_to_client{user="hello"} 10815842987 (10.07 GB)
telemt_user_msgs_from_client{user="hello"} 347600
telemt_user_msgs_to_client{user="hello"} 2528749
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## koara.io

```
telemt 3.3.10

telemt_uptime_seconds 41885.0 (11h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5054
telemt_connections_bad_total 259
telemt_handshake_timeouts_total 60
telemt_upstream_connect_attempt_total 4656
telemt_upstream_connect_success_total 4656
telemt_upstream_connect_attempts_per_request{bucket="1"} 4656
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3937
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 717
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4652
telemt_user_connections_current{user="hello"} 5
telemt_user_octets_from_client{user="hello"} 124758311 (118.98 MB)
telemt_user_octets_to_client{user="hello"} 14484403417 (13.49 GB)
telemt_user_msgs_from_client{user="hello"} 227521
telemt_user_msgs_to_client{user="hello"} 3075582
telemt_user_unique_ips_current{user="hello"} 5
```

## landvps.ru

```
telemt 3.3.10

telemt_uptime_seconds 41713.3 (11h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13718
telemt_connections_bad_total 212
telemt_handshake_timeouts_total 49
telemt_upstream_connect_attempt_total 13163
telemt_upstream_connect_success_total 13137
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 13163
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10974
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2093
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 13133
telemt_user_connections_current{user="hello"} 38
telemt_user_octets_from_client{user="hello"} 351854859 (335.55 MB)
telemt_user_octets_to_client{user="hello"} 11843008455 (11.03 GB)
telemt_user_msgs_from_client{user="hello"} 381309
telemt_user_msgs_to_client{user="hello"} 3397605
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## rdp-onedash.ru

```
telemt 3.3.10

telemt_uptime_seconds 41885.2 (11h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16505
telemt_connections_bad_total 7698
telemt_handshake_timeouts_total 36
telemt_upstream_connect_attempt_total 8552
telemt_upstream_connect_success_total 8544
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 8552
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6701
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1782
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 8540
telemt_user_connections_current{user="hello"} 16
telemt_user_octets_from_client{user="hello"} 1624214729 (1.51 GB)
telemt_user_octets_to_client{user="hello"} 7939677434 (7.39 GB)
telemt_user_msgs_from_client{user="hello"} 814263
telemt_user_msgs_to_client{user="hello"} 1781187
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 2
```