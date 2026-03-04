# Информация

Покупаю сервера у разных хостингов для тестов и запуска прокси для Telegram

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
```tg://proxy?server=s1.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d```

-----

## psb.hosting
- Локация: Finland
- Тариф: FI-200
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 12$
- Оплачен до: 25 марта
- Ссылка:
```tg://proxy?server=s2.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d```

-----

## koara.io
- Локация: Германия, Франкфурт-на-Майне
- Тариф: DE-2
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 639 RUB
- Оплачен до: 25 марта
- Ссылка:
```tg://proxy?server=s3.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d```

-----

## landvps.ru
- Локация: Финляндия
- Тариф: FL-2
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 200 Mbps/s
- Цена в месяц: 800 RUB
- Оплачен до: 26 марта
- Ссылка:
```tg://proxy?server=s4.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d```

-----

## rdp-onedash.ru
- Локация: Нидерланды
- Тариф: Mini
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 844 RUB
- Оплачен до: 14 апреля
- Ссылка:
```tg://proxy?server=s5.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d```

-----

# Server Metrics 2026-03-04 07:51:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.1.6

telemt_uptime_seconds 38402.3 (10h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 53776
telemt_connections_bad_total 191
telemt_handshake_timeouts_total 622
telemt_upstream_connect_attempt_total 24767
telemt_upstream_connect_success_total 24760
telemt_upstream_connect_attempts_per_request{bucket="1"} 24753
telemt_upstream_connect_attempts_per_request{bucket="2"} 7
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23308
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1440
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 24756
telemt_user_connections_current{user="hello"} 66
telemt_user_octets_from_client{user="hello"} 356617990 (340.10 MB)
telemt_user_octets_to_client{user="hello"} 22298245930 (20.77 GB)
telemt_user_msgs_from_client{user="hello"} 625044
telemt_user_msgs_to_client{user="hello"} 3337988
telemt_user_unique_ips_current{user="hello"} 4
```

## psb.hosting

```
telemt 3.1.6

telemt_uptime_seconds 38404.7 (10h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4054
telemt_connections_bad_total 145
telemt_handshake_timeouts_total 38
telemt_upstream_connect_attempt_total 3749
telemt_upstream_connect_success_total 3746
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 3745
telemt_upstream_connect_attempts_per_request{bucket="2"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3492
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 250
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3742
telemt_user_connections_current{user="hello"} 8
telemt_user_octets_from_client{user="hello"} 54729136 (52.19 MB)
telemt_user_octets_to_client{user="hello"} 2970275079 (2.77 GB)
telemt_user_msgs_from_client{user="hello"} 105082
telemt_user_msgs_to_client{user="hello"} 792965
```

## koara.io

```
telemt 3.1.6

telemt_uptime_seconds 38401.0 (10h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2632
telemt_connections_bad_total 191
telemt_handshake_timeouts_total 11
telemt_upstream_connect_attempt_total 2369
telemt_upstream_connect_success_total 2369
telemt_upstream_connect_attempts_per_request{bucket="1"} 2369
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2169
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 197
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2365
telemt_user_connections_current{user="hello"} 9
telemt_user_octets_from_client{user="hello"} 38872832 (37.07 MB)
telemt_user_octets_to_client{user="hello"} 2538998535 (2.36 GB)
telemt_user_msgs_from_client{user="hello"} 75699
telemt_user_msgs_to_client{user="hello"} 554496
telemt_user_unique_ips_current{user="hello"} 1
```

## landvps.ru

```
telemt 3.1.6

telemt_uptime_seconds 38402.9 (10h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8523
telemt_connections_bad_total 135
telemt_handshake_timeouts_total 2839
telemt_upstream_connect_attempt_total 5173
telemt_upstream_connect_success_total 5171
telemt_upstream_connect_attempts_per_request{bucket="1"} 5169
telemt_upstream_connect_attempts_per_request{bucket="2"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4906
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 221
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 39
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5165
telemt_user_connections_current{user="hello"} 25
telemt_user_octets_from_client{user="hello"} 63974665 (61.01 MB)
telemt_user_octets_to_client{user="hello"} 2893938408 (2.70 GB)
telemt_user_msgs_from_client{user="hello"} 75010
telemt_user_msgs_to_client{user="hello"} 649249
telemt_user_unique_ips_current{user="hello"} 9
```

## rdp-onedash.ru

```
telemt 3.1.6

telemt_uptime_seconds 38402.7 (10h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9698
telemt_connections_bad_total 6973
telemt_handshake_timeouts_total 17
telemt_upstream_connect_attempt_total 2591
telemt_upstream_connect_success_total 2590
telemt_upstream_connect_attempts_per_request{bucket="1"} 2589
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2185
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 399
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2586
telemt_user_connections_current{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 80378075 (76.65 MB)
telemt_user_octets_to_client{user="hello"} 10361749797 (9.65 GB)
telemt_user_msgs_from_client{user="hello"} 150231
telemt_user_msgs_to_client{user="hello"} 1871126
```