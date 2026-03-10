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

# Server Metrics 2026-03-10 08:15:45 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 118552.7 (32h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 235556
telemt_connections_bad_total 2461
telemt_handshake_timeouts_total 2075
telemt_upstream_connect_attempt_total 221756
telemt_upstream_connect_success_total 221688
telemt_upstream_connect_fail_total 68
telemt_upstream_connect_attempts_per_request{bucket="1"} 221756
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 204425
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17197
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 68
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 221676
telemt_user_connections_current{user="hello"} 236
telemt_user_octets_from_client{user="hello"} 5635653409 (5.25 GB)
telemt_user_octets_to_client{user="hello"} 132993474742 (123.86 GB)
telemt_user_msgs_from_client{user="hello"} 5435742
telemt_user_msgs_to_client{user="hello"} 8341965
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 118552.0 (32h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 70846
telemt_connections_bad_total 3219
telemt_handshake_timeouts_total 1012
telemt_upstream_connect_attempt_total 62911
telemt_upstream_connect_success_total 62869
telemt_upstream_connect_fail_total 42
telemt_upstream_connect_attempts_per_request{bucket="1"} 62911
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 56492
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6003
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 374
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 42
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 62857
telemt_user_connections_current{user="hello"} 79
telemt_user_octets_from_client{user="hello"} 2273576860 (2.12 GB)
telemt_user_octets_to_client{user="hello"} 28391457684 (26.44 GB)
telemt_user_msgs_from_client{user="hello"} 1787194
telemt_user_msgs_to_client{user="hello"} 8239620
telemt_user_unique_ips_current{user="hello"} 23
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 118552.7 (32h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 103697
telemt_connections_bad_total 1127
telemt_handshake_timeouts_total 5037
telemt_upstream_connect_attempt_total 72074
telemt_upstream_connect_success_total 72072
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 72074
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 63663
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8388
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 72060
telemt_user_connections_current{user="hello"} 60
telemt_user_octets_from_client{user="hello"} 6304689691 (5.87 GB)
telemt_user_octets_to_client{user="hello"} 59994703583 (55.87 GB)
telemt_user_msgs_from_client{user="hello"} 3924867
telemt_user_msgs_to_client{user="hello"} 9497762
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 118547.1 (32h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 101870
telemt_connections_bad_total 901
telemt_handshake_timeouts_total 1225
telemt_upstream_connect_attempt_total 94628
telemt_upstream_connect_success_total 94429
telemt_upstream_connect_fail_total 199
telemt_upstream_connect_attempts_per_request{bucket="1"} 94628
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 83355
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10800
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 54
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 220
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 199
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 94417
telemt_user_connections_current{user="hello"} 159
telemt_user_octets_from_client{user="hello"} 2630174181 (2.45 GB)
telemt_user_octets_to_client{user="hello"} 69415387468 (64.65 GB)
telemt_user_msgs_from_client{user="hello"} 2430312
telemt_user_msgs_to_client{user="hello"} 15677973
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 118552.5 (32h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 158920
telemt_connections_bad_total 25769
telemt_handshake_timeouts_total 4083
telemt_upstream_connect_attempt_total 122370
telemt_upstream_connect_success_total 121575
telemt_upstream_connect_fail_total 795
telemt_upstream_connect_attempts_per_request{bucket="1"} 122370
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 104597
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16810
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 168
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 795
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 121563
telemt_user_connections_current{user="hello"} 162
telemt_user_octets_from_client{user="hello"} 1891519345 (1.76 GB)
telemt_user_octets_to_client{user="hello"} 103188476305 (96.10 GB)
telemt_user_msgs_from_client{user="hello"} 2634128
telemt_user_msgs_to_client{user="hello"} 13908611
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 24
```