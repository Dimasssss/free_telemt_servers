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

# Server Metrics 2026-03-04 12:08:58 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.2.1

telemt_uptime_seconds 2524.5 (0h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4068
telemt_connections_bad_total 6
telemt_handshake_timeouts_total 110
telemt_upstream_connect_attempt_total 3870
telemt_upstream_connect_success_total 3870
telemt_upstream_connect_attempts_per_request{bucket="1"} 3870
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3675
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 194
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3868
telemt_user_connections_current{user="hello"} 110
telemt_user_octets_from_client{user="hello"} 211671778 (201.87 MB)
telemt_user_octets_to_client{user="hello"} 5605739181 (5.22 GB)
telemt_user_msgs_from_client{user="hello"} 171847
telemt_user_msgs_to_client{user="hello"} 805108
telemt_user_unique_ips_current{user="hello"} 7
```

## psb.hosting

```
telemt 3.2.1

telemt_uptime_seconds 2527.2 (0h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1026
telemt_connections_bad_total 12
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 900
telemt_upstream_connect_success_total 900
telemt_upstream_connect_attempts_per_request{bucket="1"} 900
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 818
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 80
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 898
telemt_user_connections_current{user="hello"} 32
telemt_user_octets_from_client{user="hello"} 10296188 (9.82 MB)
telemt_user_octets_to_client{user="hello"} 1156876190 (1.08 GB)
telemt_user_msgs_from_client{user="hello"} 22762
telemt_user_msgs_to_client{user="hello"} 348872
telemt_user_unique_ips_current{user="hello"} 1
```

## koara.io

```
telemt 3.2.1

telemt_uptime_seconds 2525.7 (0h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 243
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 232
telemt_upstream_connect_success_total 232
telemt_upstream_connect_attempts_per_request{bucket="1"} 232
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 232
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 230
telemt_user_connections_current{user="hello"} 7
telemt_user_octets_from_client{user="hello"} 1040619 (1016.23 KB)
telemt_user_octets_to_client{user="hello"} 36473589 (34.78 MB)
telemt_user_msgs_from_client{user="hello"} 2862
telemt_user_msgs_to_client{user="hello"} 12842
telemt_user_unique_ips_current{user="hello"} 1
```

## landvps.ru

```
telemt 3.2.1

telemt_uptime_seconds 2523.4 (0h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 879
telemt_connections_bad_total 18
telemt_handshake_timeouts_total 7
telemt_upstream_connect_attempt_total 797
telemt_upstream_connect_success_total 797
telemt_upstream_connect_attempts_per_request{bucket="1"} 797
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 755
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 795
telemt_user_connections_current{user="hello"} 14
telemt_user_octets_from_client{user="hello"} 4068941 (3.88 MB)
telemt_user_octets_to_client{user="hello"} 244223068 (232.91 MB)
telemt_user_msgs_from_client{user="hello"} 10284
telemt_user_msgs_to_client{user="hello"} 75526
telemt_user_unique_ips_current{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.2.1

telemt_uptime_seconds 2525.2 (0h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1140
telemt_connections_bad_total 456
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 680
telemt_upstream_connect_success_total 679
telemt_upstream_connect_attempts_per_request{bucket="1"} 678
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 584
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 92
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 677
telemt_user_connections_current{user="hello"} 31
telemt_user_octets_from_client{user="hello"} 14735528 (14.05 MB)
telemt_user_octets_to_client{user="hello"} 2402122746 (2.24 GB)
telemt_user_msgs_from_client{user="hello"} 34031
telemt_user_msgs_to_client{user="hello"} 435365
telemt_user_unique_ips_current{user="hello"} 3
```