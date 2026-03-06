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

# Server Metrics 2026-03-06 10:17:36 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.3

telemt_uptime_seconds 7625.4 (2h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14603
telemt_connections_bad_total 25
telemt_handshake_timeouts_total 96
telemt_upstream_connect_attempt_total 14093
telemt_upstream_connect_success_total 14092
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 14093
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13223
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 866
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 14090
telemt_user_connections_current{user="hello"} 147
telemt_user_octets_from_client{user="hello"} 1127461440 (1.05 GB)
telemt_user_octets_to_client{user="hello"} 8209219754 (7.65 GB)
telemt_user_msgs_from_client{user="hello"} 640850
telemt_user_msgs_to_client{user="hello"} 1369999
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## psb.hosting

```
telemt 3.3.3

telemt_uptime_seconds 7626.3 (2h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2301
telemt_connections_bad_total 68
telemt_handshake_timeouts_total 12
telemt_upstream_connect_attempt_total 2188
telemt_upstream_connect_success_total 2188
telemt_upstream_connect_attempts_per_request{bucket="1"} 2188
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2052
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 132
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2186
telemt_user_connections_current{user="hello"} 36
telemt_user_octets_from_client{user="hello"} 22410444 (21.37 MB)
telemt_user_octets_to_client{user="hello"} 684037031 (652.35 MB)
telemt_user_msgs_from_client{user="hello"} 47121
telemt_user_msgs_to_client{user="hello"} 231445
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## koara.io

```
telemt 3.3.3

telemt_uptime_seconds 7624.2 (2h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2473
telemt_connections_bad_total 76
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 2334
telemt_upstream_connect_success_total 2334
telemt_upstream_connect_attempts_per_request{bucket="1"} 2334
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2177
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 155
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2332
telemt_user_connections_current{user="hello"} 20
telemt_user_octets_from_client{user="hello"} 132692668 (126.55 MB)
telemt_user_octets_to_client{user="hello"} 1866831975 (1.74 GB)
telemt_user_msgs_from_client{user="hello"} 88826
telemt_user_msgs_to_client{user="hello"} 359356
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## landvps.ru

```
telemt 3.3.3

telemt_uptime_seconds 7626.8 (2h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4342
telemt_connections_bad_total 131
telemt_handshake_timeouts_total 52
telemt_upstream_connect_attempt_total 3824
telemt_upstream_connect_success_total 3812
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 3824
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3587
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 209
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3810
telemt_user_connections_current{user="hello"} 48
telemt_user_octets_from_client{user="hello"} 38418317 (36.64 MB)
telemt_user_octets_to_client{user="hello"} 1029577585 (981.88 MB)
telemt_user_msgs_from_client{user="hello"} 57864
telemt_user_msgs_to_client{user="hello"} 279280
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## rdp-onedash.ru

```
telemt 3.3.3

telemt_uptime_seconds 7628.5 (2h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4650
telemt_connections_bad_total 1919
telemt_handshake_timeouts_total 98
telemt_upstream_connect_attempt_total 2533
telemt_upstream_connect_success_total 2532
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 2533
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2258
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 272
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2530
telemt_user_connections_current{user="hello"} 15
telemt_user_octets_from_client{user="hello"} 121851552 (116.21 MB)
telemt_user_octets_to_client{user="hello"} 3403249585 (3.17 GB)
telemt_user_msgs_from_client{user="hello"} 101899
telemt_user_msgs_to_client{user="hello"} 617322
telemt_user_unique_ips_current{user="hello"} 2
telemt_user_unique_ips_recent_window{user="hello"} 1
```