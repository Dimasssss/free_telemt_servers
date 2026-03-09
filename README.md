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

# Server Metrics 2026-03-09 18:37:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 69429.1 (19h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 131847
telemt_connections_bad_total 1800
telemt_handshake_timeouts_total 1108
telemt_upstream_connect_attempt_total 123377
telemt_upstream_connect_success_total 123334
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 123377
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 113644
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9629
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 123326
telemt_user_connections_current{user="hello"} 211
telemt_user_octets_from_client{user="hello"} 3514495351 (3.27 GB)
telemt_user_octets_to_client{user="hello"} 68876409150 (64.15 GB)
telemt_user_msgs_from_client{user="hello"} 3159590
telemt_user_msgs_to_client{user="hello"} 4382455
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 69427.9 (19h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 38033
telemt_connections_bad_total 233
telemt_handshake_timeouts_total 452
telemt_upstream_connect_attempt_total 35676
telemt_upstream_connect_success_total 35655
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 35676
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32144
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3202
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 309
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 35647
telemt_user_connections_current{user="hello"} 61
telemt_user_octets_from_client{user="hello"} 1077139762 (1.00 GB)
telemt_user_octets_to_client{user="hello"} 17726733231 (16.51 GB)
telemt_user_msgs_from_client{user="hello"} 957473
telemt_user_msgs_to_client{user="hello"} 4994962
telemt_user_unique_ips_current{user="hello"} 19
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 69428.5 (19h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 47591
telemt_connections_bad_total 697
telemt_handshake_timeouts_total 2278
telemt_upstream_connect_attempt_total 37154
telemt_upstream_connect_success_total 37154
telemt_upstream_connect_attempts_per_request{bucket="1"} 37154
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33054
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4094
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 37146
telemt_user_connections_current{user="hello"} 54
telemt_user_octets_from_client{user="hello"} 4646575030 (4.33 GB)
telemt_user_octets_to_client{user="hello"} 27231074914 (25.36 GB)
telemt_user_msgs_from_client{user="hello"} 2266170
telemt_user_msgs_to_client{user="hello"} 3843509
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 69423.2 (19h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 53687
telemt_connections_bad_total 253
telemt_handshake_timeouts_total 913
telemt_upstream_connect_attempt_total 49116
telemt_upstream_connect_success_total 48996
telemt_upstream_connect_fail_total 120
telemt_upstream_connect_attempts_per_request{bucket="1"} 49116
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42393
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6455
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 121
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 120
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 48988
telemt_user_connections_current{user="hello"} 97
telemt_user_octets_from_client{user="hello"} 2105067820 (1.96 GB)
telemt_user_octets_to_client{user="hello"} 38570354032 (35.92 GB)
telemt_user_msgs_from_client{user="hello"} 1490839
telemt_user_msgs_to_client{user="hello"} 9284915
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 69428.6 (19h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 86361
telemt_connections_bad_total 16405
telemt_handshake_timeouts_total 2242
telemt_upstream_connect_attempt_total 63849
telemt_upstream_connect_success_total 63847
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 63849
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 54271
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9510
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 63839
telemt_user_connections_current{user="hello"} 108
telemt_user_octets_from_client{user="hello"} 1086305397 (1.01 GB)
telemt_user_octets_to_client{user="hello"} 58926820024 (54.88 GB)
telemt_user_msgs_from_client{user="hello"} 1462858
telemt_user_msgs_to_client{user="hello"} 7597761
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 15
```