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

# Server Metrics 2026-03-09 07:48:05 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 30495.1 (8h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 32882
telemt_connections_bad_total 69
telemt_handshake_timeouts_total 581
telemt_upstream_connect_attempt_total 30525
telemt_upstream_connect_success_total 30516
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 30525
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28143
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2363
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 30512
telemt_user_connections_current{user="hello"} 125
telemt_user_octets_from_client{user="hello"} 295344649 (281.66 MB)
telemt_user_octets_to_client{user="hello"} 15892209190 (14.80 GB)
telemt_user_msgs_from_client{user="hello"} 580959
telemt_user_msgs_to_client{user="hello"} 861220
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 30493.2 (8h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5917
telemt_connections_bad_total 137
telemt_handshake_timeouts_total 96
telemt_upstream_connect_attempt_total 5546
telemt_upstream_connect_success_total 5544
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 5546
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5180
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 364
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5540
telemt_user_connections_current{user="hello"} 41
telemt_user_octets_from_client{user="hello"} 93339927 (89.02 MB)
telemt_user_octets_to_client{user="hello"} 4708913232 (4.39 GB)
telemt_user_msgs_from_client{user="hello"} 169309
telemt_user_msgs_to_client{user="hello"} 936650
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 30493.7 (8h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2775
telemt_connections_bad_total 110
telemt_handshake_timeouts_total 6
telemt_upstream_connect_attempt_total 2618
telemt_upstream_connect_success_total 2618
telemt_upstream_connect_attempts_per_request{bucket="1"} 2618
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2274
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 343
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2614
telemt_user_connections_current{user="hello"} 8
telemt_user_octets_from_client{user="hello"} 1002524367 (956.08 MB)
telemt_user_octets_to_client{user="hello"} 1545849045 (1.44 GB)
telemt_user_msgs_from_client{user="hello"} 394249
telemt_user_msgs_to_client{user="hello"} 296517
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 30488.4 (8h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5604
telemt_connections_bad_total 78
telemt_handshake_timeouts_total 353
telemt_upstream_connect_attempt_total 4658
telemt_upstream_connect_success_total 4653
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 4658
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3851
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 780
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4649
telemt_user_connections_current{user="hello"} 33
telemt_user_octets_from_client{user="hello"} 155752998 (148.54 MB)
telemt_user_octets_to_client{user="hello"} 5643014199 (5.26 GB)
telemt_user_msgs_from_client{user="hello"} 119975
telemt_user_msgs_to_client{user="hello"} 1414570
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 30493.9 (8h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12614
telemt_connections_bad_total 6678
telemt_handshake_timeouts_total 30
telemt_upstream_connect_attempt_total 5560
telemt_upstream_connect_success_total 5560
telemt_upstream_connect_attempts_per_request{bucket="1"} 5560
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4524
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1028
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5556
telemt_user_connections_current{user="hello"} 16
telemt_user_octets_from_client{user="hello"} 66589879 (63.51 MB)
telemt_user_octets_to_client{user="hello"} 3316003588 (3.09 GB)
telemt_user_msgs_from_client{user="hello"} 106137
telemt_user_msgs_to_client{user="hello"} 476618
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 5
```