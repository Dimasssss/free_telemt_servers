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

# Server Metrics 2026-03-04 14:17:16 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.2.1

telemt_uptime_seconds 10222.4 (2h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16811
telemt_connections_bad_total 39
telemt_handshake_timeouts_total 527
telemt_upstream_connect_attempt_total 15850
telemt_upstream_connect_success_total 15847
telemt_upstream_connect_attempts_per_request{bucket="1"} 15844
telemt_upstream_connect_attempts_per_request{bucket="2"} 3
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15143
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 698
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 15845
telemt_user_connections_current{user="hello"} 151
telemt_user_octets_from_client{user="hello"} 442334656 (421.84 MB)
telemt_user_octets_to_client{user="hello"} 14200302312 (13.23 GB)
telemt_user_msgs_from_client{user="hello"} 492563
telemt_user_msgs_to_client{user="hello"} 2240101
telemt_user_unique_ips_current{user="hello"} 7
```

## psb.hosting

```
telemt 3.2.1

telemt_uptime_seconds 10225.3 (2h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3658
telemt_connections_bad_total 74
telemt_handshake_timeouts_total 7
telemt_upstream_connect_attempt_total 3418
telemt_upstream_connect_success_total 3417
telemt_upstream_connect_attempts_per_request{bucket="1"} 3416
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3203
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 199
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3415
telemt_user_connections_current{user="hello"} 26
telemt_user_octets_from_client{user="hello"} 214150695 (204.23 MB)
telemt_user_octets_to_client{user="hello"} 3704919446 (3.45 GB)
telemt_user_msgs_from_client{user="hello"} 156079
telemt_user_msgs_to_client{user="hello"} 1179970
telemt_user_unique_ips_current{user="hello"} 3
```

## koara.io

```
telemt 3.2.1

telemt_uptime_seconds 10223.6 (2h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1775
telemt_connections_bad_total 26
telemt_handshake_timeouts_total 6
telemt_upstream_connect_attempt_total 1710
telemt_upstream_connect_success_total 1710
telemt_upstream_connect_attempts_per_request{bucket="1"} 1710
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1621
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 89
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1708
telemt_user_connections_current{user="hello"} 27
telemt_user_octets_from_client{user="hello"} 77345449 (73.76 MB)
telemt_user_octets_to_client{user="hello"} 723856017 (690.32 MB)
telemt_user_msgs_from_client{user="hello"} 66475
telemt_user_msgs_to_client{user="hello"} 182774
telemt_user_unique_ips_current{user="hello"} 3
```

## landvps.ru

```
telemt 3.2.1

telemt_uptime_seconds 10221.5 (2h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4087
telemt_connections_bad_total 28
telemt_handshake_timeouts_total 32
telemt_upstream_connect_attempt_total 3735
telemt_upstream_connect_success_total 3733
telemt_upstream_connect_attempts_per_request{bucket="1"} 3731
telemt_upstream_connect_attempts_per_request{bucket="2"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3421
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 283
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3731
telemt_user_connections_current{user="hello"} 25
telemt_user_octets_from_client{user="hello"} 33121199 (31.59 MB)
telemt_user_octets_to_client{user="hello"} 2902545073 (2.70 GB)
telemt_user_msgs_from_client{user="hello"} 66264
telemt_user_msgs_to_client{user="hello"} 640587
```

## rdp-onedash.ru

```
telemt 3.2.1

telemt_uptime_seconds 10223.2 (2h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4447
telemt_connections_bad_total 1836
telemt_handshake_timeouts_total 6
telemt_upstream_connect_attempt_total 2467
telemt_upstream_connect_success_total 2466
telemt_upstream_connect_attempts_per_request{bucket="1"} 2465
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2105
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 355
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2464
telemt_user_connections_current{user="hello"} 12
telemt_user_octets_from_client{user="hello"} 46564770 (44.41 MB)
telemt_user_octets_to_client{user="hello"} 6839885678 (6.37 GB)
telemt_user_msgs_from_client{user="hello"} 111569
telemt_user_msgs_to_client{user="hello"} 1246655
telemt_user_unique_ips_current{user="hello"} 1
```