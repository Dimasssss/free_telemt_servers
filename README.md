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

# Server Metrics 2026-03-10 17:13:22 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 10034.2 (2h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 42055
telemt_connections_bad_total 436
telemt_handshake_timeouts_total 1344
telemt_upstream_connect_attempt_total 37874
telemt_upstream_connect_success_total 37864
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 37874
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34803
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3055
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 37862
telemt_user_connections_current{user="hello"} 320
telemt_user_octets_from_client{user="hello"} 1169161007 (1.09 GB)
telemt_user_octets_to_client{user="hello"} 26637382831 (24.81 GB)
telemt_user_msgs_from_client{user="hello"} 1072844
telemt_user_msgs_to_client{user="hello"} 1834656
telemt_user_unique_ips_current{user="hello"} 81
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 10033.6 (2h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14368
telemt_connections_bad_total 141
telemt_handshake_timeouts_total 315
telemt_upstream_connect_attempt_total 12984
telemt_upstream_connect_success_total 12982
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 12984
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11159
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1774
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 12980
telemt_user_connections_current{user="hello"} 81
telemt_user_octets_from_client{user="hello"} 407818764 (388.93 MB)
telemt_user_octets_to_client{user="hello"} 7507655966 (6.99 GB)
telemt_user_msgs_from_client{user="hello"} 396179
telemt_user_msgs_to_client{user="hello"} 2348343
telemt_user_unique_ips_current{user="hello"} 19
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 10033.2 (2h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23133
telemt_connections_bad_total 10
telemt_handshake_timeouts_total 1964
telemt_upstream_connect_attempt_total 19735
telemt_upstream_connect_success_total 19735
telemt_upstream_connect_attempts_per_request{bucket="1"} 19735
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17598
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2114
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 19733
telemt_user_connections_current{user="hello"} 75
telemt_user_octets_from_client{user="hello"} 176508851 (168.33 MB)
telemt_user_octets_to_client{user="hello"} 9217708257 (8.58 GB)
telemt_user_msgs_from_client{user="hello"} 380682
telemt_user_msgs_to_client{user="hello"} 1996481
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 10032.2 (2h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 22647
telemt_connections_bad_total 17
telemt_handshake_timeouts_total 221
telemt_upstream_connect_attempt_total 21562
telemt_upstream_connect_success_total 21501
telemt_upstream_connect_fail_total 61
telemt_upstream_connect_attempts_per_request{bucket="1"} 21562
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18856
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2573
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 68
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 61
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 21499
telemt_user_connections_current{user="hello"} 126
telemt_user_octets_from_client{user="hello"} 316456843 (301.80 MB)
telemt_user_octets_to_client{user="hello"} 22567635758 (21.02 GB)
telemt_user_msgs_from_client{user="hello"} 461781
telemt_user_msgs_to_client{user="hello"} 3944703
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 10033.4 (2h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 30826
telemt_connections_bad_total 2042
telemt_handshake_timeouts_total 561
telemt_upstream_connect_attempt_total 26962
telemt_upstream_connect_success_total 26724
telemt_upstream_connect_fail_total 237
telemt_upstream_connect_attempts_per_request{bucket="1"} 26961
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23508
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3138
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 78
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 237
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 26722
telemt_user_connections_current{user="hello"} 254
telemt_user_octets_from_client{user="hello"} 1249916274 (1.16 GB)
telemt_user_octets_to_client{user="hello"} 17753229744 (16.53 GB)
telemt_user_msgs_from_client{user="hello"} 852609
telemt_user_msgs_to_client{user="hello"} 2594769
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 30
```