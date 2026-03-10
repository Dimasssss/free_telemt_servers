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

# Server Metrics 2026-03-10 11:55:44 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 131751.9 (36h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 288747
telemt_connections_bad_total 3463
telemt_handshake_timeouts_total 3060
telemt_upstream_connect_attempt_total 270043
telemt_upstream_connect_success_total 269894
telemt_upstream_connect_fail_total 149
telemt_upstream_connect_attempts_per_request{bucket="1"} 270043
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 249411
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20396
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 87
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 149
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 269882
telemt_user_connections_current{user="hello"} 321
telemt_user_octets_from_client{user="hello"} 6426996072 (5.99 GB)
telemt_user_octets_to_client{user="hello"} 173272948164 (161.37 GB)
telemt_user_msgs_from_client{user="hello"} 6520718
telemt_user_msgs_to_client{user="hello"} 10514019
telemt_user_unique_ips_current{user="hello"} 69
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 131750.6 (36h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 88094
telemt_connections_bad_total 3270
telemt_handshake_timeouts_total 1244
telemt_upstream_connect_attempt_total 78993
telemt_upstream_connect_success_total 78949
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 78993
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 71119
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7413
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 416
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 78935
telemt_user_connections_current{user="hello"} 71
telemt_user_octets_from_client{user="hello"} 2755410978 (2.57 GB)
telemt_user_octets_to_client{user="hello"} 34451613473 (32.09 GB)
telemt_user_msgs_from_client{user="hello"} 2159791
telemt_user_msgs_to_client{user="hello"} 9930212
telemt_user_unique_ips_current{user="hello"} 16
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 131751.1 (36h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 125384
telemt_connections_bad_total 1203
telemt_handshake_timeouts_total 6278
telemt_upstream_connect_attempt_total 91504
telemt_upstream_connect_success_total 91502
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 91504
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 81022
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10453
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 91490
telemt_user_connections_current{user="hello"} 110
telemt_user_octets_from_client{user="hello"} 6487035163 (6.04 GB)
telemt_user_octets_to_client{user="hello"} 65889028655 (61.36 GB)
telemt_user_msgs_from_client{user="hello"} 4291690
telemt_user_msgs_to_client{user="hello"} 10931632
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 131746.1 (36h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 130372
telemt_connections_bad_total 1036
telemt_handshake_timeouts_total 2896
telemt_upstream_connect_attempt_total 120041
telemt_upstream_connect_success_total 119786
telemt_upstream_connect_fail_total 255
telemt_upstream_connect_attempts_per_request{bucket="1"} 120041
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 106298
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13112
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 74
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 302
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 255
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 119772
telemt_user_connections_current{user="hello"} 190
telemt_user_octets_from_client{user="hello"} 3394820290 (3.16 GB)
telemt_user_octets_to_client{user="hello"} 83499434300 (77.76 GB)
telemt_user_msgs_from_client{user="hello"} 3063965
telemt_user_msgs_to_client{user="hello"} 19098406
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 131751.3 (36h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 194144
telemt_connections_bad_total 28643
telemt_handshake_timeouts_total 5176
telemt_upstream_connect_attempt_total 152122
telemt_upstream_connect_success_total 151161
telemt_upstream_connect_fail_total 961
telemt_upstream_connect_attempts_per_request{bucket="1"} 152122
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 130757
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20192
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 212
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 961
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 151147
telemt_user_connections_current{user="hello"} 170
telemt_user_octets_from_client{user="hello"} 3370160534 (3.14 GB)
telemt_user_octets_to_client{user="hello"} 113178109474 (105.41 GB)
telemt_user_msgs_from_client{user="hello"} 3506562
telemt_user_msgs_to_client{user="hello"} 15394458
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 27
```