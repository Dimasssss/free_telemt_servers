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

# Server Metrics 2026-03-08 11:34:50 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 15951.2 (4h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 33784
telemt_connections_bad_total 2571
telemt_handshake_timeouts_total 200
telemt_upstream_connect_attempt_total 29665
telemt_upstream_connect_success_total 29647
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 29665
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27950
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1683
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 29645
telemt_user_connections_current{user="hello"} 203
telemt_user_octets_from_client{user="hello"} 1003465278 (956.98 MB)
telemt_user_octets_to_client{user="hello"} 16641160566 (15.50 GB)
telemt_user_msgs_from_client{user="hello"} 801518
telemt_user_msgs_to_client{user="hello"} 967696
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 15950.8 (4h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8327
telemt_connections_bad_total 73
telemt_handshake_timeouts_total 97
telemt_upstream_connect_attempt_total 7966
telemt_upstream_connect_success_total 7966
telemt_upstream_connect_attempts_per_request{bucket="1"} 7966
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7353
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 553
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7964
telemt_user_connections_current{user="hello"} 35
telemt_user_octets_from_client{user="hello"} 115591877 (110.24 MB)
telemt_user_octets_to_client{user="hello"} 5412270219 (5.04 GB)
telemt_user_msgs_from_client{user="hello"} 209736
telemt_user_msgs_to_client{user="hello"} 1395182
telemt_user_unique_ips_current{user="hello"} 10
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## koara.io

Не удалось получить метрики для этого сервера.

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 15950.2 (4h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7456
telemt_connections_bad_total 80
telemt_handshake_timeouts_total 37
telemt_upstream_connect_attempt_total 7120
telemt_upstream_connect_success_total 7107
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 7120
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6617
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 454
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7105
telemt_user_connections_current{user="hello"} 26
telemt_user_octets_from_client{user="hello"} 882685844 (841.79 MB)
telemt_user_octets_to_client{user="hello"} 2871874196 (2.67 GB)
telemt_user_msgs_from_client{user="hello"} 376027
telemt_user_msgs_to_client{user="hello"} 628344
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 15950.4 (4h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9922
telemt_connections_bad_total 2970
telemt_handshake_timeouts_total 18
telemt_upstream_connect_attempt_total 6798
telemt_upstream_connect_success_total 6797
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 6798
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5384
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1407
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6795
telemt_user_connections_current{user="hello"} 25
telemt_user_octets_from_client{user="hello"} 112364113 (107.16 MB)
telemt_user_octets_to_client{user="hello"} 5701374183 (5.31 GB)
telemt_user_msgs_from_client{user="hello"} 170294
telemt_user_msgs_to_client{user="hello"} 809643
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 3
```