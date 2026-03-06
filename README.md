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

# Server Metrics 2026-03-06 09:46:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.3

telemt_uptime_seconds 5777.7 (1h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11434
telemt_connections_bad_total 18
telemt_handshake_timeouts_total 77
telemt_upstream_connect_attempt_total 11013
telemt_upstream_connect_success_total 11012
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 11013
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10360
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 650
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11010
telemt_user_connections_current{user="hello"} 189
telemt_user_octets_from_client{user="hello"} 140882860 (134.36 MB)
telemt_user_octets_to_client{user="hello"} 6738445407 (6.28 GB)
telemt_user_msgs_from_client{user="hello"} 230811
telemt_user_msgs_to_client{user="hello"} 1112610
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## psb.hosting

```
telemt 3.3.3

telemt_uptime_seconds 5778.1 (1h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1759
telemt_connections_bad_total 64
telemt_handshake_timeouts_total 6
telemt_upstream_connect_attempt_total 1671
telemt_upstream_connect_success_total 1671
telemt_upstream_connect_attempts_per_request{bucket="1"} 1671
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1561
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 107
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1669
telemt_user_connections_current{user="hello"} 25
telemt_user_octets_from_client{user="hello"} 17657092 (16.84 MB)
telemt_user_octets_to_client{user="hello"} 519308296 (495.25 MB)
telemt_user_msgs_from_client{user="hello"} 35533
telemt_user_msgs_to_client{user="hello"} 175295
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## koara.io

```
telemt 3.3.3

telemt_uptime_seconds 5776.3 (1h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1881
telemt_connections_bad_total 73
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 1764
telemt_upstream_connect_success_total 1764
telemt_upstream_connect_attempts_per_request{bucket="1"} 1764
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1655
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 108
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1762
telemt_user_connections_current{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 124258962 (118.50 MB)
telemt_user_octets_to_client{user="hello"} 606018105 (577.94 MB)
telemt_user_msgs_from_client{user="hello"} 70775
telemt_user_msgs_to_client{user="hello"} 140797
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## landvps.ru

```
telemt 3.3.3

telemt_uptime_seconds 5778.5 (1h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3183
telemt_connections_bad_total 113
telemt_handshake_timeouts_total 37
telemt_upstream_connect_attempt_total 2793
telemt_upstream_connect_success_total 2785
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 2793
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2613
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 161
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2783
telemt_user_connections_current{user="hello"} 47
telemt_user_octets_from_client{user="hello"} 30498526 (29.09 MB)
telemt_user_octets_to_client{user="hello"} 844443247 (805.32 MB)
telemt_user_msgs_from_client{user="hello"} 44772
telemt_user_msgs_to_client{user="hello"} 224111
telemt_user_unique_ips_current{user="hello"} 10
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## rdp-onedash.ru

```
telemt 3.3.3

telemt_uptime_seconds 5780.3 (1h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3447
telemt_connections_bad_total 1585
telemt_handshake_timeouts_total 11
telemt_upstream_connect_attempt_total 1787
telemt_upstream_connect_success_total 1786
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 1787
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1583
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 202
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1784
telemt_user_connections_current{user="hello"} 25
telemt_user_octets_from_client{user="hello"} 113859786 (108.59 MB)
telemt_user_octets_to_client{user="hello"} 2222888134 (2.07 GB)
telemt_user_msgs_from_client{user="hello"} 80936
telemt_user_msgs_to_client{user="hello"} 404468
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 2
```