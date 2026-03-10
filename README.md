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

# Server Metrics 2026-03-10 12:31:34 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 133902.2 (37h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 297270
telemt_connections_bad_total 3468
telemt_handshake_timeouts_total 3092
telemt_upstream_connect_attempt_total 278314
telemt_upstream_connect_success_total 278161
telemt_upstream_connect_fail_total 153
telemt_upstream_connect_attempts_per_request{bucket="1"} 278314
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 257159
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20914
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 88
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 153
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 278149
telemt_user_connections_current{user="hello"} 319
telemt_user_octets_from_client{user="hello"} 6580764386 (6.13 GB)
telemt_user_octets_to_client{user="hello"} 186308242360 (173.51 GB)
telemt_user_msgs_from_client{user="hello"} 6753395
telemt_user_msgs_to_client{user="hello"} 10934498
telemt_user_unique_ips_current{user="hello"} 74
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 133900.9 (37h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 91079
telemt_connections_bad_total 3270
telemt_handshake_timeouts_total 1267
telemt_upstream_connect_attempt_total 81791
telemt_upstream_connect_success_total 81747
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 81791
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 73638
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7687
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 421
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 81733
telemt_user_connections_current{user="hello"} 85
telemt_user_octets_from_client{user="hello"} 2774020416 (2.58 GB)
telemt_user_octets_to_client{user="hello"} 35149757663 (32.74 GB)
telemt_user_msgs_from_client{user="hello"} 2201761
telemt_user_msgs_to_client{user="hello"} 10142107
telemt_user_unique_ips_current{user="hello"} 21
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 133901.4 (37h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 129357
telemt_connections_bad_total 1217
telemt_handshake_timeouts_total 6293
telemt_upstream_connect_attempt_total 95249
telemt_upstream_connect_success_total 95246
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 95249
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 84360
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10855
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 95234
telemt_user_connections_current{user="hello"} 68
telemt_user_octets_from_client{user="hello"} 6604731862 (6.15 GB)
telemt_user_octets_to_client{user="hello"} 66801821170 (62.21 GB)
telemt_user_msgs_from_client{user="hello"} 4379454
telemt_user_msgs_to_client{user="hello"} 11128372
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 133896.2 (37h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 134537
telemt_connections_bad_total 1053
telemt_handshake_timeouts_total 2907
telemt_upstream_connect_attempt_total 123982
telemt_upstream_connect_success_total 123713
telemt_upstream_connect_fail_total 269
telemt_upstream_connect_attempts_per_request{bucket="1"} 123982
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 109898
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13418
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 79
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 318
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 269
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 123699
telemt_user_connections_current{user="hello"} 177
telemt_user_octets_from_client{user="hello"} 3994602043 (3.72 GB)
telemt_user_octets_to_client{user="hello"} 86048656528 (80.14 GB)
telemt_user_msgs_from_client{user="hello"} 3340071
telemt_user_msgs_to_client{user="hello"} 19601576
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 133901.6 (37h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 199486
telemt_connections_bad_total 29095
telemt_handshake_timeouts_total 5323
telemt_upstream_connect_attempt_total 156646
telemt_upstream_connect_success_total 155685
telemt_upstream_connect_fail_total 961
telemt_upstream_connect_attempts_per_request{bucket="1"} 156646
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 134827
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20639
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 219
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 961
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 155671
telemt_user_connections_current{user="hello"} 194
telemt_user_octets_from_client{user="hello"} 3429092165 (3.19 GB)
telemt_user_octets_to_client{user="hello"} 115094010319 (107.19 GB)
telemt_user_msgs_from_client{user="hello"} 3602123
telemt_user_msgs_to_client{user="hello"} 15684913
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 21
```