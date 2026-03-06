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

# Server Metrics 2026-03-06 16:01:29 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.4

telemt_uptime_seconds 20371.5 (5h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 47813
telemt_connections_bad_total 3100
telemt_handshake_timeouts_total 179
telemt_upstream_connect_attempt_total 41031
telemt_upstream_connect_success_total 41019
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 41031
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38813
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2198
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 41017
telemt_user_connections_current{user="hello"} 194
telemt_user_octets_from_client{user="hello"} 2301793299 (2.14 GB)
telemt_user_octets_to_client{user="hello"} 25902883648 (24.12 GB)
telemt_user_msgs_from_client{user="hello"} 1493562
telemt_user_msgs_to_client{user="hello"} 4110967
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## psb.hosting

```
telemt 3.3.4

telemt_uptime_seconds 20370.9 (5h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9024
telemt_connections_bad_total 169
telemt_handshake_timeouts_total 96
telemt_upstream_connect_attempt_total 8537
telemt_upstream_connect_success_total 8519
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 8537
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7945
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 486
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 84
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 8517
telemt_user_connections_current{user="hello"} 67
telemt_user_octets_from_client{user="hello"} 93879166 (89.53 MB)
telemt_user_octets_to_client{user="hello"} 4904801375 (4.57 GB)
telemt_user_msgs_from_client{user="hello"} 172906
telemt_user_msgs_to_client{user="hello"} 1536244
telemt_user_unique_ips_current{user="hello"} 11
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## koara.io

```
telemt 3.3.4

telemt_uptime_seconds 20370.1 (5h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7539
telemt_connections_bad_total 129
telemt_handshake_timeouts_total 16
telemt_upstream_connect_attempt_total 7256
telemt_upstream_connect_success_total 7254
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 7256
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6841
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 408
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7252
telemt_user_connections_current{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 109200005 (104.14 MB)
telemt_user_octets_to_client{user="hello"} 4440437979 (4.14 GB)
telemt_user_msgs_from_client{user="hello"} 163698
telemt_user_msgs_to_client{user="hello"} 1047540
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.4

telemt_uptime_seconds 20369.4 (5h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10587
telemt_connections_bad_total 119
telemt_handshake_timeouts_total 51
telemt_upstream_connect_attempt_total 9820
telemt_upstream_connect_success_total 9785
telemt_upstream_connect_fail_total 35
telemt_upstream_connect_attempts_per_request{bucket="1"} 9820
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9126
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 616
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 35
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9783
telemt_user_connections_current{user="hello"} 29
telemt_user_octets_from_client{user="hello"} 143837330 (137.17 MB)
telemt_user_octets_to_client{user="hello"} 3303469672 (3.08 GB)
telemt_user_msgs_from_client{user="hello"} 175107
telemt_user_msgs_to_client{user="hello"} 855457
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## rdp-onedash.ru

```
telemt 3.3.4

telemt_uptime_seconds 20370.8 (5h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15053
telemt_connections_bad_total 5220
telemt_handshake_timeouts_total 550
telemt_upstream_connect_attempt_total 9017
telemt_upstream_connect_success_total 9017
telemt_upstream_connect_attempts_per_request{bucket="1"} 9017
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7806
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1202
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9015
telemt_user_connections_current{user="hello"} 20
telemt_user_octets_from_client{user="hello"} 226135544 (215.66 MB)
telemt_user_octets_to_client{user="hello"} 20852275189 (19.42 GB)
telemt_user_msgs_from_client{user="hello"} 370314
telemt_user_msgs_to_client{user="hello"} 3745656
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 4
```