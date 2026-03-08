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

# Server Metrics 2026-03-08 04:43:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.10

telemt_uptime_seconds 43117.3 (11h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 61801
telemt_connections_bad_total 6030
telemt_handshake_timeouts_total 455
telemt_upstream_connect_attempt_total 52128
telemt_upstream_connect_success_total 52121
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 52128
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 49421
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2677
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 52115
telemt_user_connections_current{user="hello"} 118
telemt_user_octets_from_client{user="hello"} 2413895510 (2.25 GB)
telemt_user_octets_to_client{user="hello"} 33788026444 (31.47 GB)
telemt_user_msgs_from_client{user="hello"} 1583619
telemt_user_msgs_to_client{user="hello"} 5300941
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## psb.hosting

```
telemt 3.3.10

telemt_uptime_seconds 43116.6 (11h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8438
telemt_connections_bad_total 370
telemt_handshake_timeouts_total 21
telemt_upstream_connect_attempt_total 7922
telemt_upstream_connect_success_total 7914
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 7922
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7215
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 649
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7908
telemt_user_connections_current{user="hello"} 27
telemt_user_octets_from_client{user="hello"} 195478225 (186.42 MB)
telemt_user_octets_to_client{user="hello"} 10973497016 (10.22 GB)
telemt_user_msgs_from_client{user="hello"} 355941
telemt_user_msgs_to_client{user="hello"} 2577798
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## koara.io

```
telemt 3.3.10

telemt_uptime_seconds 43116.4 (11h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5223
telemt_connections_bad_total 277
telemt_handshake_timeouts_total 103
telemt_upstream_connect_attempt_total 4761
telemt_upstream_connect_success_total 4761
telemt_upstream_connect_attempts_per_request{bucket="1"} 4761
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4037
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 722
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4757
telemt_user_connections_current{user="hello"} 6
telemt_user_octets_from_client{user="hello"} 125376936 (119.57 MB)
telemt_user_octets_to_client{user="hello"} 14518616412 (13.52 GB)
telemt_user_msgs_from_client{user="hello"} 229167
telemt_user_msgs_to_client{user="hello"} 3085301
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.10

telemt_uptime_seconds 42944.7 (11h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13907
telemt_connections_bad_total 213
telemt_handshake_timeouts_total 49
telemt_upstream_connect_attempt_total 13347
telemt_upstream_connect_success_total 13321
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 13347
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11129
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2121
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 13317
telemt_user_connections_current{user="hello"} 32
telemt_user_octets_from_client{user="hello"} 355554559 (339.08 MB)
telemt_user_octets_to_client{user="hello"} 12728828857 (11.85 GB)
telemt_user_msgs_from_client{user="hello"} 391683
telemt_user_msgs_to_client{user="hello"} 3574103
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.3.10

telemt_uptime_seconds 43116.6 (11h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17073
telemt_connections_bad_total 8013
telemt_handshake_timeouts_total 36
telemt_upstream_connect_attempt_total 8802
telemt_upstream_connect_success_total 8794
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 8802
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6890
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1843
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 8790
telemt_user_connections_current{user="hello"} 25
telemt_user_octets_from_client{user="hello"} 1631225912 (1.52 GB)
telemt_user_octets_to_client{user="hello"} 9277193258 (8.64 GB)
telemt_user_msgs_from_client{user="hello"} 831177
telemt_user_msgs_to_client{user="hello"} 2007768
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 4
```