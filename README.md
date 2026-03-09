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

# Server Metrics 2026-03-09 02:32:02 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 11532.8 (3h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9408
telemt_connections_bad_total 16
telemt_handshake_timeouts_total 184
telemt_upstream_connect_attempt_total 8655
telemt_upstream_connect_success_total 8652
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 8655
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7930
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 721
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 8650
telemt_user_connections_current{user="hello"} 97
telemt_user_octets_from_client{user="hello"} 104631641 (99.78 MB)
telemt_user_octets_to_client{user="hello"} 8397421140 (7.82 GB)
telemt_user_msgs_from_client{user="hello"} 206422
telemt_user_msgs_to_client{user="hello"} 335440
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 11531.0 (3h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 671
telemt_connections_bad_total 14
telemt_handshake_timeouts_total 7
telemt_upstream_connect_attempt_total 641
telemt_upstream_connect_success_total 641
telemt_upstream_connect_attempts_per_request{bucket="1"} 641
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 610
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 639
telemt_user_connections_current{user="hello"} 17
telemt_user_octets_from_client{user="hello"} 8297635 (7.91 MB)
telemt_user_octets_to_client{user="hello"} 465362603 (443.80 MB)
telemt_user_msgs_from_client{user="hello"} 23274
telemt_user_msgs_to_client{user="hello"} 93338
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 11531.6 (3h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 784
telemt_connections_bad_total 74
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 697
telemt_upstream_connect_success_total 697
telemt_upstream_connect_attempts_per_request{bucket="1"} 697
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 575
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 122
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 695
telemt_user_connections_current{user="hello"} 4
telemt_user_octets_from_client{user="hello"} 314105458 (299.55 MB)
telemt_user_octets_to_client{user="hello"} 134649761 (128.41 MB)
telemt_user_msgs_from_client{user="hello"} 118493
telemt_user_msgs_to_client{user="hello"} 47299
telemt_user_unique_ips_current{user="hello"} 4
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 11526.4 (3h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1590
telemt_connections_bad_total 13
telemt_handshake_timeouts_total 192
telemt_upstream_connect_attempt_total 1295
telemt_upstream_connect_success_total 1295
telemt_upstream_connect_attempts_per_request{bucket="1"} 1295
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 985
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 305
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1293
telemt_user_connections_current{user="hello"} 37
telemt_user_octets_from_client{user="hello"} 10423019 (9.94 MB)
telemt_user_octets_to_client{user="hello"} 685813355 (654.04 MB)
telemt_user_msgs_from_client{user="hello"} 26703
telemt_user_msgs_to_client{user="hello"} 196862
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 11531.9 (3h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3170
telemt_connections_bad_total 2087
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 1055
telemt_upstream_connect_success_total 1055
telemt_upstream_connect_attempts_per_request{bucket="1"} 1055
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 917
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 138
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1053
telemt_user_connections_current{user="hello"} 6
telemt_user_octets_from_client{user="hello"} 7600321 (7.25 MB)
telemt_user_octets_to_client{user="hello"} 1314410342 (1.22 GB)
telemt_user_msgs_from_client{user="hello"} 20962
telemt_user_msgs_to_client{user="hello"} 164720
telemt_user_unique_ips_current{user="hello"} 4
```