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

# Server Metrics 2026-03-09 15:17:36 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 57466.0 (15h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 102919
telemt_connections_bad_total 1655
telemt_handshake_timeouts_total 948
telemt_upstream_connect_attempt_total 95932
telemt_upstream_connect_success_total 95894
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 95932
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 88533
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7302
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 95888
telemt_user_connections_current{user="hello"} 255
telemt_user_octets_from_client{user="hello"} 2505360675 (2.33 GB)
telemt_user_octets_to_client{user="hello"} 50586301245 (47.11 GB)
telemt_user_msgs_from_client{user="hello"} 2347860
telemt_user_msgs_to_client{user="hello"} 3331516
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 57464.5 (15h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 25796
telemt_connections_bad_total 208
telemt_handshake_timeouts_total 325
telemt_upstream_connect_attempt_total 24228
telemt_upstream_connect_success_total 24211
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 24228
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22195
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1852
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 164
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 24205
telemt_user_connections_current{user="hello"} 77
telemt_user_octets_from_client{user="hello"} 818717669 (780.79 MB)
telemt_user_octets_to_client{user="hello"} 13741143052 (12.80 GB)
telemt_user_msgs_from_client{user="hello"} 713965
telemt_user_msgs_to_client{user="hello"} 3755976
telemt_user_unique_ips_current{user="hello"} 15
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 57465.7 (15h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 32386
telemt_connections_bad_total 644
telemt_handshake_timeouts_total 1575
telemt_upstream_connect_attempt_total 23542
telemt_upstream_connect_success_total 23542
telemt_upstream_connect_attempts_per_request{bucket="1"} 23542
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21201
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2336
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 23536
telemt_user_connections_current{user="hello"} 56
telemt_user_octets_from_client{user="hello"} 4358483287 (4.06 GB)
telemt_user_octets_to_client{user="hello"} 14859234592 (13.84 GB)
telemt_user_msgs_from_client{user="hello"} 1865127
telemt_user_msgs_to_client{user="hello"} 2049298
telemt_user_unique_ips_current{user="hello"} 23
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 57459.8 (15h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 35158
telemt_connections_bad_total 187
telemt_handshake_timeouts_total 815
telemt_upstream_connect_attempt_total 32256
telemt_upstream_connect_success_total 32172
telemt_upstream_connect_fail_total 84
telemt_upstream_connect_attempts_per_request{bucket="1"} 32256
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28024
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4052
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 12
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 84
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 84
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 32166
telemt_user_connections_current{user="hello"} 90
telemt_user_octets_from_client{user="hello"} 1853777773 (1.73 GB)
telemt_user_octets_to_client{user="hello"} 26100155470 (24.31 GB)
telemt_user_msgs_from_client{user="hello"} 1131221
telemt_user_msgs_to_client{user="hello"} 6674087
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 57465.3 (15h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 62959
telemt_connections_bad_total 13851
telemt_handshake_timeouts_total 1542
telemt_upstream_connect_attempt_total 44594
telemt_upstream_connect_success_total 44592
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 44594
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37534
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7018
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 44586
telemt_user_connections_current{user="hello"} 109
telemt_user_octets_from_client{user="hello"} 752574671 (717.71 MB)
telemt_user_octets_to_client{user="hello"} 46569264034 (43.37 GB)
telemt_user_msgs_from_client{user="hello"} 1005952
telemt_user_msgs_to_client{user="hello"} 5625117
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 11
```