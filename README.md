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

# Server Metrics 2026-03-09 16:39:15 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 62364.4 (17h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 114937
telemt_connections_bad_total 1656
telemt_handshake_timeouts_total 974
telemt_upstream_connect_attempt_total 107604
telemt_upstream_connect_success_total 107565
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 107604
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 99340
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8166
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 107559
telemt_user_connections_current{user="hello"} 251
telemt_user_octets_from_client{user="hello"} 2875878732 (2.68 GB)
telemt_user_octets_to_client{user="hello"} 56329657460 (52.46 GB)
telemt_user_msgs_from_client{user="hello"} 2663331
telemt_user_msgs_to_client{user="hello"} 3751764
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 62363.5 (17h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 30642
telemt_connections_bad_total 220
telemt_handshake_timeouts_total 354
telemt_upstream_connect_attempt_total 28906
telemt_upstream_connect_success_total 28888
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 28906
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26179
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2485
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 224
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 28882
telemt_user_connections_current{user="hello"} 79
telemt_user_octets_from_client{user="hello"} 1000954585 (954.58 MB)
telemt_user_octets_to_client{user="hello"} 15743869326 (14.66 GB)
telemt_user_msgs_from_client{user="hello"} 843853
telemt_user_msgs_to_client{user="hello"} 4350778
telemt_user_unique_ips_current{user="hello"} 18
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 62364.2 (17h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 38497
telemt_connections_bad_total 655
telemt_handshake_timeouts_total 1680
telemt_upstream_connect_attempt_total 29185
telemt_upstream_connect_success_total 29185
telemt_upstream_connect_attempts_per_request{bucket="1"} 29185
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26065
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3115
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 29179
telemt_user_connections_current{user="hello"} 55
telemt_user_octets_from_client{user="hello"} 4427702658 (4.12 GB)
telemt_user_octets_to_client{user="hello"} 18302719498 (17.05 GB)
telemt_user_msgs_from_client{user="hello"} 1962690
telemt_user_msgs_to_client{user="hello"} 2404844
telemt_user_unique_ips_current{user="hello"} 22
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 62358.5 (17h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 44277
telemt_connections_bad_total 198
telemt_handshake_timeouts_total 877
telemt_upstream_connect_attempt_total 40463
telemt_upstream_connect_success_total 40364
telemt_upstream_connect_fail_total 99
telemt_upstream_connect_attempts_per_request{bucket="1"} 40463
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34527
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5718
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 21
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 98
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 99
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 40356
telemt_user_connections_current{user="hello"} 103
telemt_user_octets_from_client{user="hello"} 1950391247 (1.82 GB)
telemt_user_octets_to_client{user="hello"} 31070342684 (28.94 GB)
telemt_user_msgs_from_client{user="hello"} 1275281
telemt_user_msgs_to_client{user="hello"} 7855417
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 62364.0 (17h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 72429
telemt_connections_bad_total 15143
telemt_handshake_timeouts_total 1647
telemt_upstream_connect_attempt_total 52287
telemt_upstream_connect_success_total 52285
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 52287
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44271
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7964
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 52279
telemt_user_connections_current{user="hello"} 80
telemt_user_octets_from_client{user="hello"} 885821444 (844.79 MB)
telemt_user_octets_to_client{user="hello"} 55131882358 (51.35 GB)
telemt_user_msgs_from_client{user="hello"} 1215394
telemt_user_msgs_to_client{user="hello"} 6708013
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 11
```