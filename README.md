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

# Server Metrics 2026-03-08 19:48:03 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 45561.6 (12h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 104438
telemt_connections_bad_total 5057
telemt_handshake_timeouts_total 1273
telemt_upstream_connect_attempt_total 94758
telemt_upstream_connect_success_total 94726
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 94758
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 89229
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5435
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 94720
telemt_user_connections_current{user="hello"} 214
telemt_user_octets_from_client{user="hello"} 2270988886 (2.12 GB)
telemt_user_octets_to_client{user="hello"} 59338069266 (55.26 GB)
telemt_user_msgs_from_client{user="hello"} 2293466
telemt_user_msgs_to_client{user="hello"} 3216064
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 45560.2 (12h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 24267
telemt_connections_bad_total 231
telemt_handshake_timeouts_total 129
telemt_upstream_connect_attempt_total 23479
telemt_upstream_connect_success_total 23474
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 23479
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21837
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1505
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 132
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 23470
telemt_user_connections_current{user="hello"} 42
telemt_user_octets_from_client{user="hello"} 792609839 (755.89 MB)
telemt_user_octets_to_client{user="hello"} 21368597993 (19.90 GB)
telemt_user_msgs_from_client{user="hello"} 913793
telemt_user_msgs_to_client{user="hello"} 5798938
telemt_user_unique_ips_current{user="hello"} 11
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 45559.9 (12h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14273
telemt_connections_bad_total 178
telemt_handshake_timeouts_total 686
telemt_upstream_connect_attempt_total 12937
telemt_upstream_connect_success_total 12861
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 12937
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11840
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 947
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 74
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 12855
telemt_user_connections_current{user="hello"} 6
telemt_user_octets_from_client{user="hello"} 418190108 (398.82 MB)
telemt_user_octets_to_client{user="hello"} 5430026002 (5.06 GB)
telemt_user_msgs_from_client{user="hello"} 287548
telemt_user_msgs_to_client{user="hello"} 904372
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 45559.8 (12h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18588
telemt_connections_bad_total 186
telemt_handshake_timeouts_total 59
telemt_upstream_connect_attempt_total 17790
telemt_upstream_connect_success_total 17753
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 17790
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16356
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1311
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 78
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 17749
telemt_user_connections_current{user="hello"} 36
telemt_user_octets_from_client{user="hello"} 1057184827 (1008.21 MB)
telemt_user_octets_to_client{user="hello"} 6283172521 (5.85 GB)
telemt_user_msgs_from_client{user="hello"} 556060
telemt_user_msgs_to_client{user="hello"} 1411081
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 45560.1 (12h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 26896
telemt_connections_bad_total 8604
telemt_handshake_timeouts_total 236
telemt_upstream_connect_attempt_total 17636
telemt_upstream_connect_success_total 17629
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 17636
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14540
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3057
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 17623
telemt_user_connections_current{user="hello"} 20
telemt_user_octets_from_client{user="hello"} 332192025 (316.80 MB)
telemt_user_octets_to_client{user="hello"} 15184403748 (14.14 GB)
telemt_user_msgs_from_client{user="hello"} 454991
telemt_user_msgs_to_client{user="hello"} 1971278
telemt_user_unique_ips_current{user="hello"} 10
telemt_user_unique_ips_recent_window{user="hello"} 2
```