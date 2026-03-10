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

# Server Metrics 2026-03-10 09:52:58 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 124386.0 (34h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 259708
telemt_connections_bad_total 3448
telemt_handshake_timeouts_total 2656
telemt_upstream_connect_attempt_total 243184
telemt_upstream_connect_success_total 243097
telemt_upstream_connect_fail_total 87
telemt_upstream_connect_attempts_per_request{bucket="1"} 243184
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 224480
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18539
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 78
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 87
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 243085
telemt_user_connections_current{user="hello"} 302
telemt_user_octets_from_client{user="hello"} 6042056205 (5.63 GB)
telemt_user_octets_to_client{user="hello"} 146176312178 (136.14 GB)
telemt_user_msgs_from_client{user="hello"} 5895376
telemt_user_msgs_to_client{user="hello"} 9270151
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 124384.8 (34h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 78202
telemt_connections_bad_total 3258
telemt_handshake_timeouts_total 1038
telemt_upstream_connect_attempt_total 69905
telemt_upstream_connect_success_total 69863
telemt_upstream_connect_fail_total 42
telemt_upstream_connect_attempts_per_request{bucket="1"} 69905
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 62868
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6594
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 400
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 42
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 69851
telemt_user_connections_current{user="hello"} 85
telemt_user_octets_from_client{user="hello"} 2328526714 (2.17 GB)
telemt_user_octets_to_client{user="hello"} 32575790603 (30.34 GB)
telemt_user_msgs_from_client{user="hello"} 1917860
telemt_user_msgs_to_client{user="hello"} 9322379
telemt_user_unique_ips_current{user="hello"} 21
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 124385.3 (34h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 112269
telemt_connections_bad_total 1149
telemt_handshake_timeouts_total 5543
telemt_upstream_connect_attempt_total 79836
telemt_upstream_connect_success_total 79834
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 79836
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 70727
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9084
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 79822
telemt_user_connections_current{user="hello"} 52
telemt_user_octets_from_client{user="hello"} 6369713056 (5.93 GB)
telemt_user_octets_to_client{user="hello"} 62199756116 (57.93 GB)
telemt_user_msgs_from_client{user="hello"} 4077989
telemt_user_msgs_to_client{user="hello"} 10004264
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 124380.1 (34h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 114115
telemt_connections_bad_total 959
telemt_handshake_timeouts_total 1312
telemt_upstream_connect_attempt_total 106208
telemt_upstream_connect_success_total 105972
telemt_upstream_connect_fail_total 236
telemt_upstream_connect_attempts_per_request{bucket="1"} 106208
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 93819
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11842
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 60
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 251
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 236
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 105960
telemt_user_connections_current{user="hello"} 136
telemt_user_octets_from_client{user="hello"} 2955201462 (2.75 GB)
telemt_user_octets_to_client{user="hello"} 79214841097 (73.77 GB)
telemt_user_msgs_from_client{user="hello"} 2735433
telemt_user_msgs_to_client{user="hello"} 18143635
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 124385.5 (34h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 173627
telemt_connections_bad_total 27273
telemt_handshake_timeouts_total 4430
telemt_upstream_connect_attempt_total 134605
telemt_upstream_connect_success_total 133799
telemt_upstream_connect_fail_total 806
telemt_upstream_connect_attempts_per_request{bucket="1"} 134605
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 115598
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18008
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 193
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 806
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 133787
telemt_user_connections_current{user="hello"} 160
telemt_user_octets_from_client{user="hello"} 2031972628 (1.89 GB)
telemt_user_octets_to_client{user="hello"} 105700673983 (98.44 GB)
telemt_user_msgs_from_client{user="hello"} 2816107
telemt_user_msgs_to_client{user="hello"} 14407728
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 16
```