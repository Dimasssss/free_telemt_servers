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

# Server Metrics 2026-03-06 09:51:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.3

telemt_uptime_seconds 6085.6 (1h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12014
telemt_connections_bad_total 20
telemt_handshake_timeouts_total 80
telemt_upstream_connect_attempt_total 11561
telemt_upstream_connect_success_total 11560
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 11561
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10854
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 704
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11558
telemt_user_connections_current{user="hello"} 183
telemt_user_octets_from_client{user="hello"} 156270528 (149.03 MB)
telemt_user_octets_to_client{user="hello"} 7079561570 (6.59 GB)
telemt_user_msgs_from_client{user="hello"} 251532
telemt_user_msgs_to_client{user="hello"} 1170626
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## psb.hosting

```
telemt 3.3.3

telemt_uptime_seconds 6086.0 (1h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1847
telemt_connections_bad_total 64
telemt_handshake_timeouts_total 6
telemt_upstream_connect_attempt_total 1755
telemt_upstream_connect_success_total 1755
telemt_upstream_connect_attempts_per_request{bucket="1"} 1755
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1637
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 115
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1753
telemt_user_connections_current{user="hello"} 27
telemt_user_octets_from_client{user="hello"} 18819205 (17.95 MB)
telemt_user_octets_to_client{user="hello"} 566960114 (540.70 MB)
telemt_user_msgs_from_client{user="hello"} 37618
telemt_user_msgs_to_client{user="hello"} 189887
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## koara.io

```
telemt 3.3.3

telemt_uptime_seconds 6084.1 (1h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1950
telemt_connections_bad_total 74
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 1830
telemt_upstream_connect_success_total 1830
telemt_upstream_connect_attempts_per_request{bucket="1"} 1830
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1716
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 113
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1828
telemt_user_connections_current{user="hello"} 15
telemt_user_octets_from_client{user="hello"} 125684630 (119.86 MB)
telemt_user_octets_to_client{user="hello"} 961860859 (917.30 MB)
telemt_user_msgs_from_client{user="hello"} 74897
telemt_user_msgs_to_client{user="hello"} 195115
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.3

telemt_uptime_seconds 6086.5 (1h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3390
telemt_connections_bad_total 115
telemt_handshake_timeouts_total 37
telemt_upstream_connect_attempt_total 2989
telemt_upstream_connect_success_total 2980
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 2989
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2801
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 167
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2978
telemt_user_connections_current{user="hello"} 37
telemt_user_octets_from_client{user="hello"} 31631481 (30.17 MB)
telemt_user_octets_to_client{user="hello"} 881097732 (840.28 MB)
telemt_user_msgs_from_client{user="hello"} 47983
telemt_user_msgs_to_client{user="hello"} 235160
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## rdp-onedash.ru

```
telemt 3.3.3

telemt_uptime_seconds 6088.2 (1h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3681
telemt_connections_bad_total 1643
telemt_handshake_timeouts_total 65
telemt_upstream_connect_attempt_total 1872
telemt_upstream_connect_success_total 1871
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 1872
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1660
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 210
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1869
telemt_user_connections_current{user="hello"} 8
telemt_user_octets_from_client{user="hello"} 115198774 (109.86 MB)
telemt_user_octets_to_client{user="hello"} 2392569703 (2.23 GB)
telemt_user_msgs_from_client{user="hello"} 84626
telemt_user_msgs_to_client{user="hello"} 434483
telemt_user_unique_ips_current{user="hello"} 4
```