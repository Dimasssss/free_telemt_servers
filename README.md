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

# Server Metrics 2026-03-08 22:58:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 56957.4 (15h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 119211
telemt_connections_bad_total 5801
telemt_handshake_timeouts_total 1282
telemt_upstream_connect_attempt_total 108269
telemt_upstream_connect_success_total 108231
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 108269
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 101619
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6543
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 69
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 108225
telemt_user_connections_current{user="hello"} 129
telemt_user_octets_from_client{user="hello"} 2617293598 (2.44 GB)
telemt_user_octets_to_client{user="hello"} 76682864053 (71.42 GB)
telemt_user_msgs_from_client{user="hello"} 2726707
telemt_user_msgs_to_client{user="hello"} 4103726
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 56956.5 (15h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 27597
telemt_connections_bad_total 320
telemt_handshake_timeouts_total 131
telemt_upstream_connect_attempt_total 26672
telemt_upstream_connect_success_total 26665
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 26672
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24859
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1670
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 136
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 26659
telemt_user_connections_current{user="hello"} 20
telemt_user_octets_from_client{user="hello"} 841899994 (802.90 MB)
telemt_user_octets_to_client{user="hello"} 22926730517 (21.35 GB)
telemt_user_msgs_from_client{user="hello"} 987371
telemt_user_msgs_to_client{user="hello"} 6210022
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 56956.2 (15h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15696
telemt_connections_bad_total 250
telemt_handshake_timeouts_total 686
telemt_upstream_connect_attempt_total 14261
telemt_upstream_connect_success_total 14185
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 14261
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13035
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1076
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 74
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 14179
telemt_user_connections_current{user="hello"} 3
telemt_user_octets_from_client{user="hello"} 1576065778 (1.47 GB)
telemt_user_octets_to_client{user="hello"} 5707511162 (5.32 GB)
telemt_user_msgs_from_client{user="hello"} 706594
telemt_user_msgs_to_client{user="hello"} 982953
telemt_user_unique_ips_current{user="hello"} 3
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 56956.1 (15h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21608
telemt_connections_bad_total 225
telemt_handshake_timeouts_total 60
telemt_upstream_connect_attempt_total 20724
telemt_upstream_connect_success_total 20683
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 20724
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19003
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1575
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 12
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 93
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 20677
telemt_user_connections_current{user="hello"} 25
telemt_user_octets_from_client{user="hello"} 1068870529 (1019.35 MB)
telemt_user_octets_to_client{user="hello"} 6652377409 (6.20 GB)
telemt_user_msgs_from_client{user="hello"} 578645
telemt_user_msgs_to_client{user="hello"} 1517382
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 56956.4 (15h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 32513
telemt_connections_bad_total 10823
telemt_handshake_timeouts_total 241
telemt_upstream_connect_attempt_total 20933
telemt_upstream_connect_success_total 20926
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 20933
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17437
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3453
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 20920
telemt_user_connections_current{user="hello"} 12
telemt_user_octets_from_client{user="hello"} 383784418 (366.01 MB)
telemt_user_octets_to_client{user="hello"} 18277133321 (17.02 GB)
telemt_user_msgs_from_client{user="hello"} 559591
telemt_user_msgs_to_client{user="hello"} 2360294
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 1
```