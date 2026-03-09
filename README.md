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

# Server Metrics 2026-03-09 03:38:18 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 15508.5 (4h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12516
telemt_connections_bad_total 23
telemt_handshake_timeouts_total 193
telemt_upstream_connect_attempt_total 11393
telemt_upstream_connect_success_total 11390
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 11393
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10469
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 920
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11388
telemt_user_connections_current{user="hello"} 92
telemt_user_octets_from_client{user="hello"} 120665393 (115.08 MB)
telemt_user_octets_to_client{user="hello"} 8826540611 (8.22 GB)
telemt_user_msgs_from_client{user="hello"} 244399
telemt_user_msgs_to_client{user="hello"} 380172
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 15506.7 (4h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1195
telemt_connections_bad_total 19
telemt_handshake_timeouts_total 50
telemt_upstream_connect_attempt_total 1113
telemt_upstream_connect_success_total 1113
telemt_upstream_connect_attempts_per_request{bucket="1"} 1113
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1047
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 66
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1111
telemt_user_connections_current{user="hello"} 26
telemt_user_octets_from_client{user="hello"} 21390683 (20.40 MB)
telemt_user_octets_to_client{user="hello"} 1038302672 (990.20 MB)
telemt_user_msgs_from_client{user="hello"} 42353
telemt_user_msgs_to_client{user="hello"} 200993
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 15507.2 (4h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1052
telemt_connections_bad_total 82
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 956
telemt_upstream_connect_success_total 956
telemt_upstream_connect_attempts_per_request{bucket="1"} 956
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 770
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 185
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 954
telemt_user_connections_current{user="hello"} 5
telemt_user_octets_from_client{user="hello"} 384195501 (366.40 MB)
telemt_user_octets_to_client{user="hello"} 923935252 (881.13 MB)
telemt_user_msgs_from_client{user="hello"} 156278
telemt_user_msgs_to_client{user="hello"} 176014
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 15502.1 (4h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1986
telemt_connections_bad_total 26
telemt_handshake_timeouts_total 201
telemt_upstream_connect_attempt_total 1643
telemt_upstream_connect_success_total 1643
telemt_upstream_connect_attempts_per_request{bucket="1"} 1643
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1215
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 422
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1641
telemt_user_connections_current{user="hello"} 33
telemt_user_octets_from_client{user="hello"} 14111380 (13.46 MB)
telemt_user_octets_to_client{user="hello"} 1116668675 (1.04 GB)
telemt_user_msgs_from_client{user="hello"} 36592
telemt_user_msgs_to_client{user="hello"} 278417
telemt_user_unique_ips_current{user="hello"} 6
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 15507.6 (4h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4177
telemt_connections_bad_total 2818
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 1327
telemt_upstream_connect_success_total 1327
telemt_upstream_connect_attempts_per_request{bucket="1"} 1327
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1158
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 169
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1325
telemt_user_connections_current{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 9892427 (9.43 MB)
telemt_user_octets_to_client{user="hello"} 1591554448 (1.48 GB)
telemt_user_msgs_from_client{user="hello"} 25927
telemt_user_msgs_to_client{user="hello"} 192976
telemt_user_unique_ips_current{user="hello"} 6
```