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

# Server Metrics 2026-03-06 15:46:05 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.4

telemt_uptime_seconds 19448.0 (5h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 45703
telemt_connections_bad_total 3097
telemt_handshake_timeouts_total 177
telemt_upstream_connect_attempt_total 38964
telemt_upstream_connect_success_total 38954
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 38964
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36854
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2092
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 38952
telemt_user_connections_current{user="hello"} 152
telemt_user_octets_from_client{user="hello"} 2144023195 (2.00 GB)
telemt_user_octets_to_client{user="hello"} 24840494216 (23.13 GB)
telemt_user_msgs_from_client{user="hello"} 1409961
telemt_user_msgs_to_client{user="hello"} 3936313
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## psb.hosting

```
telemt 3.3.4

telemt_uptime_seconds 19447.4 (5h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8595
telemt_connections_bad_total 168
telemt_handshake_timeouts_total 96
telemt_upstream_connect_attempt_total 8109
telemt_upstream_connect_success_total 8091
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 8109
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7552
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 455
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 82
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 8089
telemt_user_connections_current{user="hello"} 58
telemt_user_octets_from_client{user="hello"} 90628550 (86.43 MB)
telemt_user_octets_to_client{user="hello"} 4799279909 (4.47 GB)
telemt_user_msgs_from_client{user="hello"} 167366
telemt_user_msgs_to_client{user="hello"} 1504517
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## koara.io

```
telemt 3.3.4

telemt_uptime_seconds 19446.7 (5h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7189
telemt_connections_bad_total 76
telemt_handshake_timeouts_total 16
telemt_upstream_connect_attempt_total 6963
telemt_upstream_connect_success_total 6961
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 6963
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6568
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 388
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6959
telemt_user_connections_current{user="hello"} 13
telemt_user_octets_from_client{user="hello"} 104337487 (99.50 MB)
telemt_user_octets_to_client{user="hello"} 4330407438 (4.03 GB)
telemt_user_msgs_from_client{user="hello"} 155993
telemt_user_msgs_to_client{user="hello"} 1019262
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.4

telemt_uptime_seconds 19445.9 (5h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10215
telemt_connections_bad_total 117
telemt_handshake_timeouts_total 51
telemt_upstream_connect_attempt_total 9451
telemt_upstream_connect_success_total 9419
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 9451
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8808
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 570
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9417
telemt_user_connections_current{user="hello"} 23
telemt_user_octets_from_client{user="hello"} 141195814 (134.65 MB)
telemt_user_octets_to_client{user="hello"} 3198940053 (2.98 GB)
telemt_user_msgs_from_client{user="hello"} 169634
telemt_user_msgs_to_client{user="hello"} 825915
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## rdp-onedash.ru

```
telemt 3.3.4

telemt_uptime_seconds 19447.3 (5h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14508
telemt_connections_bad_total 5055
telemt_handshake_timeouts_total 550
telemt_upstream_connect_attempt_total 8654
telemt_upstream_connect_success_total 8654
telemt_upstream_connect_attempts_per_request{bucket="1"} 8654
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7509
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1136
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 8652
telemt_user_connections_current{user="hello"} 26
telemt_user_octets_from_client{user="hello"} 224165427 (213.78 MB)
telemt_user_octets_to_client{user="hello"} 20747714390 (19.32 GB)
telemt_user_msgs_from_client{user="hello"} 365892
telemt_user_msgs_to_client{user="hello"} 3721663
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 4
```