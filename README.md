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

# Server Metrics 2026-03-04 10:41:45 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.2.0

telemt_uptime_seconds 8320.1 (2h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14264
telemt_connections_bad_total 28
telemt_handshake_timeouts_total 193
telemt_upstream_connect_attempt_total 12981
telemt_upstream_connect_success_total 12980
telemt_upstream_connect_attempts_per_request{bucket="1"} 12979
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12107
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 871
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 12978
telemt_user_connections_current{user="hello"} 105
telemt_user_octets_from_client{user="hello"} 168283381 (160.49 MB)
telemt_user_octets_to_client{user="hello"} 6246739295 (5.82 GB)
telemt_user_msgs_from_client{user="hello"} 279707
telemt_user_msgs_to_client{user="hello"} 1050371
telemt_user_unique_ips_current{user="hello"} 9
```

## psb.hosting

```
telemt 3.2.0

telemt_uptime_seconds 8331.4 (2h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1917
telemt_connections_bad_total 66
telemt_handshake_timeouts_total 33
telemt_upstream_connect_attempt_total 1754
telemt_upstream_connect_success_total 1752
telemt_upstream_connect_attempts_per_request{bucket="1"} 1750
telemt_upstream_connect_attempts_per_request{bucket="2"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1690
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 55
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1750
telemt_user_connections_current{user="hello"} 9
telemt_user_octets_from_client{user="hello"} 71337118 (68.03 MB)
telemt_user_octets_to_client{user="hello"} 818534109 (780.61 MB)
telemt_user_msgs_from_client{user="hello"} 62570
telemt_user_msgs_to_client{user="hello"} 255671
```

## koara.io

```
telemt 3.2.0

telemt_uptime_seconds 8316.1 (2h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1657
telemt_connections_bad_total 78
telemt_upstream_connect_attempt_total 1552
telemt_upstream_connect_success_total 1552
telemt_upstream_connect_attempts_per_request{bucket="1"} 1552
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1362
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 190
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1550
telemt_user_connections_current{user="hello"} 9
telemt_user_octets_from_client{user="hello"} 42359906 (40.40 MB)
telemt_user_octets_to_client{user="hello"} 3272750566 (3.05 GB)
telemt_user_msgs_from_client{user="hello"} 90986
telemt_user_msgs_to_client{user="hello"} 615293
telemt_user_unique_ips_current{user="hello"} 2
```

## landvps.ru

```
telemt 3.2.0

telemt_uptime_seconds 8306.8 (2h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3125
telemt_connections_bad_total 67
telemt_handshake_timeouts_total 15
telemt_upstream_connect_attempt_total 2809
telemt_upstream_connect_success_total 2808
telemt_upstream_connect_attempts_per_request{bucket="1"} 2807
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2703
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 75
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2806
telemt_user_connections_current{user="hello"} 33
telemt_user_octets_from_client{user="hello"} 19692095 (18.78 MB)
telemt_user_octets_to_client{user="hello"} 881237672 (840.41 MB)
telemt_user_msgs_from_client{user="hello"} 32661
telemt_user_msgs_to_client{user="hello"} 246881
telemt_user_unique_ips_current{user="hello"} 3
```

## rdp-onedash.ru

```
telemt 3.2.0

telemt_uptime_seconds 8318.1 (2h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2882
telemt_connections_bad_total 1489
telemt_handshake_timeouts_total 5
telemt_upstream_connect_attempt_total 1327
telemt_upstream_connect_success_total 1327
telemt_upstream_connect_attempts_per_request{bucket="1"} 1327
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1147
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 179
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1325
telemt_user_connections_current{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 20457815 (19.51 MB)
telemt_user_octets_to_client{user="hello"} 745069778 (710.55 MB)
telemt_user_msgs_from_client{user="hello"} 41091
telemt_user_msgs_to_client{user="hello"} 185338
telemt_user_unique_ips_current{user="hello"} 1
```