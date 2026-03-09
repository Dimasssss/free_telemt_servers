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

# Server Metrics 2026-03-09 00:34:51 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 4501.3 (1h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3754
telemt_connections_bad_total 6
telemt_handshake_timeouts_total 168
telemt_upstream_connect_attempt_total 3254
telemt_upstream_connect_success_total 3253
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 3254
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2922
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 330
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3251
telemt_user_connections_current{user="hello"} 128
telemt_user_octets_from_client{user="hello"} 40834700 (38.94 MB)
telemt_user_octets_to_client{user="hello"} 5554134138 (5.17 GB)
telemt_user_msgs_from_client{user="hello"} 100115
telemt_user_msgs_to_client{user="hello"} 179343
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 4499.4 (1h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 284
telemt_connections_bad_total 4
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 276
telemt_upstream_connect_success_total 276
telemt_upstream_connect_attempts_per_request{bucket="1"} 276
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 268
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 274
telemt_user_connections_current{user="hello"} 21
telemt_user_octets_from_client{user="hello"} 1851491 (1.77 MB)
telemt_user_octets_to_client{user="hello"} 46344799 (44.20 MB)
telemt_user_msgs_from_client{user="hello"} 5232
telemt_user_msgs_to_client{user="hello"} 14629
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 4500.2 (1h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 342
telemt_connections_bad_total 28
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 305
telemt_upstream_connect_success_total 305
telemt_upstream_connect_attempts_per_request{bucket="1"} 305
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 266
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 303
telemt_user_connections_current{user="hello"} 5
telemt_user_octets_from_client{user="hello"} 15891508 (15.16 MB)
telemt_user_octets_to_client{user="hello"} 27823122 (26.53 MB)
telemt_user_msgs_from_client{user="hello"} 8740
telemt_user_msgs_to_client{user="hello"} 10583
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 4494.9 (1h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 577
telemt_connections_bad_total 3
telemt_upstream_connect_attempt_total 568
telemt_upstream_connect_success_total 568
telemt_upstream_connect_attempts_per_request{bucket="1"} 568
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 473
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 91
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 566
telemt_user_connections_current{user="hello"} 26
telemt_user_octets_from_client{user="hello"} 3743691 (3.57 MB)
telemt_user_octets_to_client{user="hello"} 181103001 (172.71 MB)
telemt_user_msgs_from_client{user="hello"} 9221
telemt_user_msgs_to_client{user="hello"} 35756
telemt_user_unique_ips_current{user="hello"} 6
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 4500.4 (1h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1430
telemt_connections_bad_total 806
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 613
telemt_upstream_connect_success_total 613
telemt_upstream_connect_attempts_per_request{bucket="1"} 613
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 519
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 94
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 611
telemt_user_connections_current{user="hello"} 10
telemt_user_octets_from_client{user="hello"} 6213947 (5.93 MB)
telemt_user_octets_to_client{user="hello"} 1259955209 (1.17 GB)
telemt_user_msgs_from_client{user="hello"} 17507
telemt_user_msgs_to_client{user="hello"} 152932
telemt_user_unique_ips_current{user="hello"} 8
```