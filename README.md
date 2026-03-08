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

# Server Metrics 2026-03-08 03:26:49 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.10

telemt_uptime_seconds 38499.3 (10h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 54437
telemt_connections_bad_total 5988
telemt_handshake_timeouts_total 381
telemt_upstream_connect_attempt_total 45809
telemt_upstream_connect_success_total 45802
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 45809
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43427
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2355
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 45798
telemt_user_connections_current{user="hello"} 95
telemt_user_octets_from_client{user="hello"} 2322904399 (2.16 GB)
telemt_user_octets_to_client{user="hello"} 32173703577 (29.96 GB)
telemt_user_msgs_from_client{user="hello"} 1476041
telemt_user_msgs_to_client{user="hello"} 5011766
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## psb.hosting

```
telemt 3.3.10

telemt_uptime_seconds 38498.6 (10h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7645
telemt_connections_bad_total 332
telemt_handshake_timeouts_total 18
telemt_upstream_connect_attempt_total 7182
telemt_upstream_connect_success_total 7175
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 7182
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6523
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 602
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7169
telemt_user_connections_current{user="hello"} 13
telemt_user_octets_from_client{user="hello"} 177846307 (169.61 MB)
telemt_user_octets_to_client{user="hello"} 10592518793 (9.87 GB)
telemt_user_msgs_from_client{user="hello"} 333830
telemt_user_msgs_to_client{user="hello"} 2466109
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## koara.io

```
telemt 3.3.10

telemt_uptime_seconds 38498.3 (10h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4708
telemt_connections_bad_total 248
telemt_handshake_timeouts_total 7
telemt_upstream_connect_attempt_total 4377
telemt_upstream_connect_success_total 4377
telemt_upstream_connect_attempts_per_request{bucket="1"} 4377
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3717
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 658
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4373
telemt_user_connections_current{user="hello"} 9
telemt_user_octets_from_client{user="hello"} 119364322 (113.83 MB)
telemt_user_octets_to_client{user="hello"} 14027887125 (13.06 GB)
telemt_user_msgs_from_client{user="hello"} 214107
telemt_user_msgs_to_client{user="hello"} 2964097
telemt_user_unique_ips_current{user="hello"} 3
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.10

telemt_uptime_seconds 38326.5 (10h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13193
telemt_connections_bad_total 211
telemt_handshake_timeouts_total 49
telemt_upstream_connect_attempt_total 12646
telemt_upstream_connect_success_total 12620
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 12646
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10562
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1989
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 12616
telemt_user_connections_current{user="hello"} 22
telemt_user_octets_from_client{user="hello"} 340112709 (324.36 MB)
telemt_user_octets_to_client{user="hello"} 10844449225 (10.10 GB)
telemt_user_msgs_from_client{user="hello"} 356276
telemt_user_msgs_to_client{user="hello"} 3189657
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.3.10

telemt_uptime_seconds 38498.5 (10h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15430
telemt_connections_bad_total 7083
telemt_handshake_timeouts_total 35
telemt_upstream_connect_attempt_total 8109
telemt_upstream_connect_success_total 8101
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 8109
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6325
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1715
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 8097
telemt_user_connections_current{user="hello"} 3
telemt_user_octets_from_client{user="hello"} 1620231370 (1.51 GB)
telemt_user_octets_to_client{user="hello"} 7735809920 (7.20 GB)
telemt_user_msgs_from_client{user="hello"} 803937
telemt_user_msgs_to_client{user="hello"} 1725981
telemt_user_unique_ips_current{user="hello"} 3
```