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

# Server Metrics 2026-03-08 17:24:16 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 36935.0 (10h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 88444
telemt_connections_bad_total 5045
telemt_handshake_timeouts_total 1111
telemt_upstream_connect_attempt_total 79317
telemt_upstream_connect_success_total 79290
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 79317
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 74566
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4679
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 79284
telemt_user_connections_current{user="hello"} 169
telemt_user_octets_from_client{user="hello"} 1976521803 (1.84 GB)
telemt_user_octets_to_client{user="hello"} 47194825976 (43.95 GB)
telemt_user_msgs_from_client{user="hello"} 1894983
telemt_user_msgs_to_client{user="hello"} 2663566
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 36934.0 (10h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19314
telemt_connections_bad_total 145
telemt_handshake_timeouts_total 125
telemt_upstream_connect_attempt_total 18704
telemt_upstream_connect_success_total 18700
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 18704
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17308
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1286
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 106
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 18696
telemt_user_connections_current{user="hello"} 39
telemt_user_octets_from_client{user="hello"} 680601519 (649.07 MB)
telemt_user_octets_to_client{user="hello"} 18422005541 (17.16 GB)
telemt_user_msgs_from_client{user="hello"} 732672
telemt_user_msgs_to_client{user="hello"} 5017563
telemt_user_unique_ips_current{user="hello"} 14
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 36933.7 (10h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11772
telemt_connections_bad_total 163
telemt_handshake_timeouts_total 37
telemt_upstream_connect_attempt_total 11114
telemt_upstream_connect_success_total 11038
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 11114
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10205
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 761
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11034
telemt_user_connections_current{user="hello"} 12
telemt_user_octets_from_client{user="hello"} 229068378 (218.46 MB)
telemt_user_octets_to_client{user="hello"} 3967416387 (3.69 GB)
telemt_user_msgs_from_client{user="hello"} 191103
telemt_user_msgs_to_client{user="hello"} 697503
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 36933.5 (10h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15664
telemt_connections_bad_total 171
telemt_handshake_timeouts_total 56
telemt_upstream_connect_attempt_total 14951
telemt_upstream_connect_success_total 14919
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 14951
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13768
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1077
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 67
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 14915
telemt_user_connections_current{user="hello"} 24
telemt_user_octets_from_client{user="hello"} 1014839164 (967.83 MB)
telemt_user_octets_to_client{user="hello"} 5290890387 (4.93 GB)
telemt_user_msgs_from_client{user="hello"} 518887
telemt_user_msgs_to_client{user="hello"} 1199621
telemt_user_unique_ips_current{user="hello"} 4
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 36933.9 (10h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21152
telemt_connections_bad_total 6825
telemt_handshake_timeouts_total 228
telemt_upstream_connect_attempt_total 13784
telemt_upstream_connect_success_total 13780
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 13784
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11543
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2223
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 13776
telemt_user_connections_current{user="hello"} 26
telemt_user_octets_from_client{user="hello"} 259145023 (247.14 MB)
telemt_user_octets_to_client{user="hello"} 11264527629 (10.49 GB)
telemt_user_msgs_from_client{user="hello"} 342033
telemt_user_msgs_to_client{user="hello"} 1476561
telemt_user_unique_ips_current{user="hello"} 10
telemt_user_unique_ips_recent_window{user="hello"} 3
```