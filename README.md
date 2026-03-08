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

# Server Metrics 2026-03-08 06:31:35 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.10

telemt_uptime_seconds 49585.9 (13h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 73102
telemt_connections_bad_total 6649
telemt_handshake_timeouts_total 752
telemt_upstream_connect_attempt_total 62230
telemt_upstream_connect_success_total 62111
telemt_upstream_connect_fail_total 119
telemt_upstream_connect_attempts_per_request{bucket="1"} 62230
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 58843
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3226
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 119
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 62105
telemt_user_connections_current{user="hello"} 130
telemt_user_octets_from_client{user="hello"} 2596061993 (2.42 GB)
telemt_user_octets_to_client{user="hello"} 39755776274 (37.03 GB)
telemt_user_msgs_from_client{user="hello"} 1823705
telemt_user_msgs_to_client{user="hello"} 6249741
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## psb.hosting

```
telemt 3.3.10

telemt_uptime_seconds 49585.0 (13h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10808
telemt_connections_bad_total 371
telemt_handshake_timeouts_total 30
telemt_upstream_connect_attempt_total 10245
telemt_upstream_connect_success_total 10236
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 10245
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9383
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 803
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 10230
telemt_user_connections_current{user="hello"} 17
telemt_user_octets_from_client{user="hello"} 283795386 (270.65 MB)
telemt_user_octets_to_client{user="hello"} 15613636662 (14.54 GB)
telemt_user_msgs_from_client{user="hello"} 511324
telemt_user_msgs_to_client{user="hello"} 3618491
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## koara.io

```
telemt 3.3.10

telemt_uptime_seconds 49584.6 (13h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6856
telemt_connections_bad_total 306
telemt_handshake_timeouts_total 260
telemt_upstream_connect_attempt_total 6160
telemt_upstream_connect_success_total 6160
telemt_upstream_connect_attempts_per_request{bucket="1"} 6160
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5357
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 801
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6154
telemt_user_connections_current{user="hello"} 2
telemt_user_octets_from_client{user="hello"} 135859936 (129.57 MB)
telemt_user_octets_to_client{user="hello"} 14748709983 (13.74 GB)
telemt_user_msgs_from_client{user="hello"} 246126
telemt_user_msgs_to_client{user="hello"} 3157456
telemt_user_unique_ips_current{user="hello"} 2
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.10

telemt_uptime_seconds 49412.9 (13h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15578
telemt_connections_bad_total 244
telemt_handshake_timeouts_total 64
telemt_upstream_connect_attempt_total 14938
telemt_upstream_connect_success_total 14912
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 14938
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12577
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2258
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 69
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 14906
telemt_user_connections_current{user="hello"} 33
telemt_user_octets_from_client{user="hello"} 479653000 (457.43 MB)
telemt_user_octets_to_client{user="hello"} 13544715039 (12.61 GB)
telemt_user_msgs_from_client{user="hello"} 462428
telemt_user_msgs_to_client{user="hello"} 3785435
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.3.10

telemt_uptime_seconds 49584.8 (13h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20554
telemt_connections_bad_total 9171
telemt_handshake_timeouts_total 43
telemt_upstream_connect_attempt_total 11096
telemt_upstream_connect_success_total 11088
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 11096
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8625
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2399
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11082
telemt_user_connections_current{user="hello"} 23
telemt_user_octets_from_client{user="hello"} 1656320383 (1.54 GB)
telemt_user_octets_to_client{user="hello"} 10715334594 (9.98 GB)
telemt_user_msgs_from_client{user="hello"} 884379
telemt_user_msgs_to_client{user="hello"} 2326495
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 5
```