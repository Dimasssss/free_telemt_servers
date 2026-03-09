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

# Server Metrics 2026-03-09 02:47:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 12449.7 (3h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9991
telemt_connections_bad_total 20
telemt_handshake_timeouts_total 185
telemt_upstream_connect_attempt_total 9184
telemt_upstream_connect_success_total 9181
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 9184
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8425
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 755
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9179
telemt_user_connections_current{user="hello"} 112
telemt_user_octets_from_client{user="hello"} 108171023 (103.16 MB)
telemt_user_octets_to_client{user="hello"} 8434710928 (7.86 GB)
telemt_user_msgs_from_client{user="hello"} 213966
telemt_user_msgs_to_client{user="hello"} 343392
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 12448.1 (3h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 708
telemt_connections_bad_total 16
telemt_handshake_timeouts_total 7
telemt_upstream_connect_attempt_total 675
telemt_upstream_connect_success_total 675
telemt_upstream_connect_attempts_per_request{bucket="1"} 675
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 644
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 673
telemt_user_connections_current{user="hello"} 17
telemt_user_octets_from_client{user="hello"} 8491216 (8.10 MB)
telemt_user_octets_to_client{user="hello"} 467406492 (445.75 MB)
telemt_user_msgs_from_client{user="hello"} 23934
telemt_user_msgs_to_client{user="hello"} 94644
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 12448.7 (3h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 816
telemt_connections_bad_total 74
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 729
telemt_upstream_connect_success_total 729
telemt_upstream_connect_attempts_per_request{bucket="1"} 729
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 602
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 126
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 727
telemt_user_connections_current{user="hello"} 4
telemt_user_octets_from_client{user="hello"} 314176647 (299.62 MB)
telemt_user_octets_to_client{user="hello"} 136302872 (129.99 MB)
telemt_user_msgs_from_client{user="hello"} 118735
telemt_user_msgs_to_client{user="hello"} 48018
telemt_user_unique_ips_current{user="hello"} 4
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 12443.3 (3h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1694
telemt_connections_bad_total 16
telemt_handshake_timeouts_total 197
telemt_upstream_connect_attempt_total 1375
telemt_upstream_connect_success_total 1375
telemt_upstream_connect_attempts_per_request{bucket="1"} 1375
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1035
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 335
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1373
telemt_user_connections_current{user="hello"} 34
telemt_user_octets_from_client{user="hello"} 11517472 (10.98 MB)
telemt_user_octets_to_client{user="hello"} 745337471 (710.81 MB)
telemt_user_msgs_from_client{user="hello"} 29609
telemt_user_msgs_to_client{user="hello"} 212350
telemt_user_unique_ips_current{user="hello"} 5
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 12448.9 (3h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3411
telemt_connections_bad_total 2267
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 1115
telemt_upstream_connect_success_total 1115
telemt_upstream_connect_attempts_per_request{bucket="1"} 1115
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 970
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 145
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1113
telemt_user_connections_current{user="hello"} 20
telemt_user_octets_from_client{user="hello"} 8922743 (8.51 MB)
telemt_user_octets_to_client{user="hello"} 1545367570 (1.44 GB)
telemt_user_msgs_from_client{user="hello"} 23641
telemt_user_msgs_to_client{user="hello"} 185466
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 1
```