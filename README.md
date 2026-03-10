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

# Server Metrics 2026-03-10 17:03:08 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 9420.7 (2h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 39828
telemt_connections_bad_total 339
telemt_handshake_timeouts_total 1332
telemt_upstream_connect_attempt_total 35843
telemt_upstream_connect_success_total 35834
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 35843
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32971
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2857
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 35832
telemt_user_connections_current{user="hello"} 315
telemt_user_octets_from_client{user="hello"} 1127752193 (1.05 GB)
telemt_user_octets_to_client{user="hello"} 24630479245 (22.94 GB)
telemt_user_msgs_from_client{user="hello"} 1014267
telemt_user_msgs_to_client{user="hello"} 1624358
telemt_user_unique_ips_current{user="hello"} 76
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 9420.1 (2h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13344
telemt_connections_bad_total 98
telemt_handshake_timeouts_total 314
telemt_upstream_connect_attempt_total 12047
telemt_upstream_connect_success_total 12045
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 12047
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10455
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1544
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 12043
telemt_user_connections_current{user="hello"} 104
telemt_user_octets_from_client{user="hello"} 357573516 (341.01 MB)
telemt_user_octets_to_client{user="hello"} 7199951091 (6.71 GB)
telemt_user_msgs_from_client{user="hello"} 372646
telemt_user_msgs_to_client{user="hello"} 2252925
telemt_user_unique_ips_current{user="hello"} 22
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 9419.8 (2h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21805
telemt_connections_bad_total 10
telemt_handshake_timeouts_total 1778
telemt_upstream_connect_attempt_total 18674
telemt_upstream_connect_success_total 18674
telemt_upstream_connect_attempts_per_request{bucket="1"} 18674
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16651
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2000
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 18672
telemt_user_connections_current{user="hello"} 74
telemt_user_octets_from_client{user="hello"} 169676017 (161.82 MB)
telemt_user_octets_to_client{user="hello"} 9016038575 (8.40 GB)
telemt_user_msgs_from_client{user="hello"} 361832
telemt_user_msgs_to_client{user="hello"} 1952383
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 9418.8 (2h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21173
telemt_connections_bad_total 16
telemt_handshake_timeouts_total 211
telemt_upstream_connect_attempt_total 20167
telemt_upstream_connect_success_total 20109
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 20167
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17626
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2413
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 20107
telemt_user_connections_current{user="hello"} 155
telemt_user_octets_from_client{user="hello"} 286990730 (273.70 MB)
telemt_user_octets_to_client{user="hello"} 20561636556 (19.15 GB)
telemt_user_msgs_from_client{user="hello"} 421898
telemt_user_msgs_to_client{user="hello"} 3407555
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 9420.0 (2h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 28930
telemt_connections_bad_total 1931
telemt_handshake_timeouts_total 550
telemt_upstream_connect_attempt_total 25243
telemt_upstream_connect_success_total 25004
telemt_upstream_connect_fail_total 236
telemt_upstream_connect_attempts_per_request{bucket="1"} 25240
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22034
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2896
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 74
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 236
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 25002
telemt_user_connections_current{user="hello"} 235
telemt_user_octets_from_client{user="hello"} 1238393096 (1.15 GB)
telemt_user_octets_to_client{user="hello"} 17380281125 (16.19 GB)
telemt_user_msgs_from_client{user="hello"} 825031
telemt_user_msgs_to_client{user="hello"} 2484080
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 27
```