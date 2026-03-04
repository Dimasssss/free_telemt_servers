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

# Server Metrics 2026-03-04 16:46:12 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.2.1

telemt_uptime_seconds 19159.0 (5h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 30454
telemt_connections_bad_total 63
telemt_handshake_timeouts_total 715
telemt_upstream_connect_attempt_total 29067
telemt_upstream_connect_success_total 29061
telemt_upstream_connect_attempts_per_request{bucket="1"} 29055
telemt_upstream_connect_attempts_per_request{bucket="2"} 6
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27686
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1363
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 29059
telemt_user_connections_current{user="hello"} 122
telemt_user_octets_from_client{user="hello"} 1180377044 (1.10 GB)
telemt_user_octets_to_client{user="hello"} 23881461431 (22.24 GB)
telemt_user_msgs_from_client{user="hello"} 981984
telemt_user_msgs_to_client{user="hello"} 3757787
telemt_user_unique_ips_current{user="hello"} 7
```

## psb.hosting

```
telemt 3.2.1

telemt_uptime_seconds 19162.0 (5h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7120
telemt_connections_bad_total 94
telemt_handshake_timeouts_total 26
telemt_upstream_connect_attempt_total 6608
telemt_upstream_connect_success_total 6606
telemt_upstream_connect_attempts_per_request{bucket="1"} 6604
telemt_upstream_connect_attempts_per_request{bucket="2"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6164
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 391
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6604
telemt_user_connections_current{user="hello"} 25
telemt_user_octets_from_client{user="hello"} 426506210 (406.75 MB)
telemt_user_octets_to_client{user="hello"} 8145080129 (7.59 GB)
telemt_user_msgs_from_client{user="hello"} 321664
telemt_user_msgs_to_client{user="hello"} 2654343
```

## koara.io

```
telemt 3.2.1

telemt_uptime_seconds 19160.1 (5h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4095
telemt_connections_bad_total 38
telemt_handshake_timeouts_total 8
telemt_upstream_connect_attempt_total 3957
telemt_upstream_connect_success_total 3957
telemt_upstream_connect_attempts_per_request{bucket="1"} 3957
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3710
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 246
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3955
telemt_user_connections_current{user="hello"} 18
telemt_user_octets_from_client{user="hello"} 129391432 (123.40 MB)
telemt_user_octets_to_client{user="hello"} 2963152144 (2.76 GB)
telemt_user_msgs_from_client{user="hello"} 129584
telemt_user_msgs_to_client{user="hello"} 633855
telemt_user_unique_ips_current{user="hello"} 2
```

## landvps.ru

```
telemt 3.2.1

telemt_uptime_seconds 19158.1 (5h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7283
telemt_connections_bad_total 342
telemt_handshake_timeouts_total 43
telemt_upstream_connect_attempt_total 6460
telemt_upstream_connect_success_total 6456
telemt_upstream_connect_attempts_per_request{bucket="1"} 6452
telemt_upstream_connect_attempts_per_request{bucket="2"} 4
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5945
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 458
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6454
telemt_user_connections_current{user="hello"} 9
telemt_user_octets_from_client{user="hello"} 71580814 (68.26 MB)
telemt_user_octets_to_client{user="hello"} 3608470035 (3.36 GB)
telemt_user_msgs_from_client{user="hello"} 105568
telemt_user_msgs_to_client{user="hello"} 836602
telemt_user_unique_ips_current{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.2.1

telemt_uptime_seconds 19159.8 (5h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8173
telemt_connections_bad_total 3424
telemt_handshake_timeouts_total 14
telemt_upstream_connect_attempt_total 4555
telemt_upstream_connect_success_total 4554
telemt_upstream_connect_attempts_per_request{bucket="1"} 4553
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3905
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 641
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4552
telemt_user_connections_current{user="hello"} 36
telemt_user_octets_from_client{user="hello"} 133257314 (127.08 MB)
telemt_user_octets_to_client{user="hello"} 8373958732 (7.80 GB)
telemt_user_msgs_from_client{user="hello"} 199338
telemt_user_msgs_to_client{user="hello"} 1593577
telemt_user_unique_ips_current{user="hello"} 4
```