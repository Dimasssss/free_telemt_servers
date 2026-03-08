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

# Server Metrics 2026-03-08 18:05:21 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 39399.7 (10h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 93324
telemt_connections_bad_total 5046
telemt_handshake_timeouts_total 1240
telemt_upstream_connect_attempt_total 83890
telemt_upstream_connect_success_total 83861
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 83890
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 78931
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4882
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 83855
telemt_user_connections_current{user="hello"} 223
telemt_user_octets_from_client{user="hello"} 2035751122 (1.90 GB)
telemt_user_octets_to_client{user="hello"} 52193556262 (48.61 GB)
telemt_user_msgs_from_client{user="hello"} 2017843
telemt_user_msgs_to_client{user="hello"} 2867552
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 39398.8 (10h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20749
telemt_connections_bad_total 188
telemt_handshake_timeouts_total 127
telemt_upstream_connect_attempt_total 20056
telemt_upstream_connect_success_total 20052
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 20056
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18585
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1352
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 115
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 20048
telemt_user_connections_current{user="hello"} 35
telemt_user_octets_from_client{user="hello"} 717561323 (684.32 MB)
telemt_user_octets_to_client{user="hello"} 19146716296 (17.83 GB)
telemt_user_msgs_from_client{user="hello"} 819154
telemt_user_msgs_to_client{user="hello"} 5247631
telemt_user_unique_ips_current{user="hello"} 11
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 39398.6 (10h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12959
telemt_connections_bad_total 164
telemt_handshake_timeouts_total 686
telemt_upstream_connect_attempt_total 11644
telemt_upstream_connect_success_total 11568
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 11644
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10657
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 839
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11564
telemt_user_connections_current{user="hello"} 4
telemt_user_octets_from_client{user="hello"} 235181659 (224.29 MB)
telemt_user_octets_to_client{user="hello"} 4175911559 (3.89 GB)
telemt_user_msgs_from_client{user="hello"} 201170
telemt_user_msgs_to_client{user="hello"} 739985
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 39398.5 (10h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16426
telemt_connections_bad_total 173
telemt_handshake_timeouts_total 56
telemt_upstream_connect_attempt_total 15701
telemt_upstream_connect_success_total 15667
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 15701
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14441
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1148
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 15663
telemt_user_connections_current{user="hello"} 43
telemt_user_octets_from_client{user="hello"} 1018488330 (971.31 MB)
telemt_user_octets_to_client{user="hello"} 5735630162 (5.34 GB)
telemt_user_msgs_from_client{user="hello"} 528769
telemt_user_msgs_to_client{user="hello"} 1295183
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 39398.7 (10h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23145
telemt_connections_bad_total 7478
telemt_handshake_timeouts_total 229
telemt_upstream_connect_attempt_total 15083
telemt_upstream_connect_success_total 15078
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 15083
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12618
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2439
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 15074
telemt_user_connections_current{user="hello"} 35
telemt_user_octets_from_client{user="hello"} 266102001 (253.77 MB)
telemt_user_octets_to_client{user="hello"} 11458915588 (10.67 GB)
telemt_user_msgs_from_client{user="hello"} 358429
telemt_user_msgs_to_client{user="hello"} 1519292
telemt_user_unique_ips_current{user="hello"} 10
telemt_user_unique_ips_recent_window{user="hello"} 3
```