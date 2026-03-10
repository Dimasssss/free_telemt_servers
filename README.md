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

# Server Metrics 2026-03-10 04:56:14 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 106581.9 (29h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 197870
telemt_connections_bad_total 2380
telemt_handshake_timeouts_total 1864
telemt_upstream_connect_attempt_total 185843
telemt_upstream_connect_success_total 185786
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 185843
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 171161
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14561
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 185776
telemt_user_connections_current{user="hello"} 203
telemt_user_octets_from_client{user="hello"} 5121564620 (4.77 GB)
telemt_user_octets_to_client{user="hello"} 114280565255 (106.43 GB)
telemt_user_msgs_from_client{user="hello"} 4760203
telemt_user_msgs_to_client{user="hello"} 7111175
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 106580.7 (29h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 60144
telemt_connections_bad_total 3171
telemt_handshake_timeouts_total 904
telemt_upstream_connect_attempt_total 52873
telemt_upstream_connect_success_total 52831
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 52872
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 47290
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5175
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 366
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 52819
telemt_user_connections_current{user="hello"} 27
telemt_user_octets_from_client{user="hello"} 2160781562 (2.01 GB)
telemt_user_octets_to_client{user="hello"} 24806070382 (23.10 GB)
telemt_user_msgs_from_client{user="hello"} 1601579
telemt_user_msgs_to_client{user="hello"} 7119280
telemt_user_unique_ips_current{user="hello"} 13
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 106581.3 (29h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 87118
telemt_connections_bad_total 998
telemt_handshake_timeouts_total 4007
telemt_upstream_connect_attempt_total 57753
telemt_upstream_connect_success_total 57751
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 57753
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 50743
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6995
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 57741
telemt_user_connections_current{user="hello"} 49
telemt_user_octets_from_client{user="hello"} 6094213749 (5.68 GB)
telemt_user_octets_to_client{user="hello"} 56575843361 (52.69 GB)
telemt_user_msgs_from_client{user="hello"} 3638125
telemt_user_msgs_to_client{user="hello"} 8639434
telemt_user_unique_ips_current{user="hello"} 21
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 106576.1 (29h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 82180
telemt_connections_bad_total 584
telemt_handshake_timeouts_total 1083
telemt_upstream_connect_attempt_total 76094
telemt_upstream_connect_success_total 75923
telemt_upstream_connect_fail_total 171
telemt_upstream_connect_attempts_per_request{bucket="1"} 76094
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 66608
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9097
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 40
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 178
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 171
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 75911
telemt_user_connections_current{user="hello"} 87
telemt_user_octets_from_client{user="hello"} 2364433550 (2.20 GB)
telemt_user_octets_to_client{user="hello"} 54000723516 (50.29 GB)
telemt_user_msgs_from_client{user="hello"} 2043422
telemt_user_msgs_to_client{user="hello"} 12637270
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 106581.5 (29h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 134484
telemt_connections_bad_total 23337
telemt_handshake_timeouts_total 3090
telemt_upstream_connect_attempt_total 102626
telemt_upstream_connect_success_total 101835
telemt_upstream_connect_fail_total 791
telemt_upstream_connect_attempts_per_request{bucket="1"} 102626
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 87191
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14487
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 157
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 791
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 101825
telemt_user_connections_current{user="hello"} 80
telemt_user_octets_from_client{user="hello"} 1670819791 (1.56 GB)
telemt_user_octets_to_client{user="hello"} 91863261225 (85.55 GB)
telemt_user_msgs_from_client{user="hello"} 2290214
telemt_user_msgs_to_client{user="hello"} 12405381
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 17
```