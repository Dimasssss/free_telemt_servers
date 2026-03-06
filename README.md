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

# Server Metrics 2026-03-06 04:23:32 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.2

telemt_uptime_seconds 22090.8 (6h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 72721
telemt_connections_bad_total 51934
telemt_handshake_timeouts_total 2431
telemt_upstream_connect_attempt_total 16938
telemt_upstream_connect_success_total 16936
telemt_upstream_connect_attempts_per_request{bucket="1"} 16934
telemt_upstream_connect_attempts_per_request{bucket="2"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15930
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1002
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 16934
telemt_user_connections_current{user="hello"} 96
telemt_user_octets_from_client{user="hello"} 213590770 (203.70 MB)
telemt_user_octets_to_client{user="hello"} 15341094722 (14.29 GB)
telemt_user_msgs_from_client{user="hello"} 390772
telemt_user_msgs_to_client{user="hello"} 2260590
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## psb.hosting

```
telemt 3.3.2

telemt_uptime_seconds 22088.6 (6h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2172
telemt_connections_bad_total 142
telemt_handshake_timeouts_total 6
telemt_upstream_connect_attempt_total 2001
telemt_upstream_connect_success_total 2000
telemt_upstream_connect_attempts_per_request{bucket="1"} 1999
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1913
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 84
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1998
telemt_user_connections_current{user="hello"} 41
telemt_user_octets_from_client{user="hello"} 52047505 (49.64 MB)
telemt_user_octets_to_client{user="hello"} 962183839 (917.61 MB)
telemt_user_msgs_from_client{user="hello"} 69246
telemt_user_msgs_to_client{user="hello"} 302063
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## koara.io

```
telemt 3.3.2

telemt_uptime_seconds 22089.1 (6h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1442
telemt_connections_bad_total 195
telemt_handshake_timeouts_total 5
telemt_upstream_connect_attempt_total 1238
telemt_upstream_connect_success_total 1238
telemt_upstream_connect_attempts_per_request{bucket="1"} 1238
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1076
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 162
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1234
telemt_user_connections_current{user="hello"} 7
telemt_user_octets_from_client{user="hello"} 36776083 (35.07 MB)
telemt_user_octets_to_client{user="hello"} 1732896685 (1.61 GB)
telemt_user_msgs_from_client{user="hello"} 46746
telemt_user_msgs_to_client{user="hello"} 348055
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.2

telemt_uptime_seconds 22091.9 (6h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2989
telemt_connections_bad_total 131
telemt_handshake_timeouts_total 298
telemt_upstream_connect_attempt_total 2488
telemt_upstream_connect_success_total 2488
telemt_upstream_connect_attempts_per_request{bucket="1"} 2488
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2098
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 381
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2484
telemt_user_octets_from_client{user="hello"} 95363719 (90.95 MB)
telemt_user_octets_to_client{user="hello"} 5664510568 (5.28 GB)
telemt_user_msgs_from_client{user="hello"} 134497
telemt_user_msgs_to_client{user="hello"} 1189084
```

## rdp-onedash.ru

```
telemt 3.3.2

telemt_uptime_seconds 22091.8 (6h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7290
telemt_connections_bad_total 4024
telemt_handshake_timeouts_total 145
telemt_upstream_connect_attempt_total 3032
telemt_upstream_connect_success_total 3032
telemt_upstream_connect_attempts_per_request{bucket="1"} 3032
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2634
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 393
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3030
telemt_user_connections_current{user="hello"} 15
telemt_user_octets_from_client{user="hello"} 52622300 (50.18 MB)
telemt_user_octets_to_client{user="hello"} 11368671894 (10.59 GB)
telemt_user_msgs_from_client{user="hello"} 137056
telemt_user_msgs_to_client{user="hello"} 2070278
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 2
```