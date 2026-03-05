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

# Server Metrics 2026-03-05 06:28:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.2.1

telemt_uptime_seconds 68518.4 (19h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 91969
telemt_connections_bad_total 344
telemt_handshake_timeouts_total 3673
telemt_upstream_connect_attempt_total 81773
telemt_upstream_connect_success_total 81755
telemt_upstream_connect_attempts_per_request{bucket="1"} 81737
telemt_upstream_connect_attempts_per_request{bucket="2"} 18
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 76176
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5531
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 81747
telemt_user_connections_current{user="hello"} 131
telemt_user_octets_from_client{user="hello"} 2618470035 (2.44 GB)
telemt_user_octets_to_client{user="hello"} 62869198677 (58.55 GB)
telemt_user_msgs_from_client{user="hello"} 2506374
telemt_user_msgs_to_client{user="hello"} 10215077
telemt_user_unique_ips_current{user="hello"} 11
```

## psb.hosting

```
telemt 3.2.1

telemt_uptime_seconds 68521.2 (19h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18399
telemt_connections_bad_total 343
telemt_handshake_timeouts_total 43
telemt_upstream_connect_attempt_total 13758
telemt_upstream_connect_success_total 13756
telemt_upstream_connect_attempts_per_request{bucket="1"} 13754
telemt_upstream_connect_attempts_per_request{bucket="2"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12718
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 953
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 85
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 13750
telemt_user_connections_current{user="hello"} 10
telemt_user_octets_from_client{user="hello"} 1104555179 (1.03 GB)
telemt_user_octets_to_client{user="hello"} 12871578848 (11.99 GB)
telemt_user_msgs_from_client{user="hello"} 725449
telemt_user_msgs_to_client{user="hello"} 4175853
```

## koara.io

```
telemt 3.2.1

telemt_uptime_seconds 68520.2 (19h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13385
telemt_connections_bad_total 283
telemt_handshake_timeouts_total 18
telemt_upstream_connect_attempt_total 9346
telemt_upstream_connect_success_total 9346
telemt_upstream_connect_attempts_per_request{bucket="1"} 9346
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8716
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 629
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9338
telemt_user_connections_current{user="hello"} 15
telemt_user_octets_from_client{user="hello"} 384761037 (366.94 MB)
telemt_user_octets_to_client{user="hello"} 6938945557 (6.46 GB)
telemt_user_msgs_from_client{user="hello"} 338664
telemt_user_msgs_to_client{user="hello"} 1489953
telemt_user_unique_ips_current{user="hello"} 2
```

## landvps.ru

```
telemt 3.2.1

telemt_uptime_seconds 68517.3 (19h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 22621
telemt_connections_bad_total 895
telemt_handshake_timeouts_total 163
telemt_upstream_connect_attempt_total 19540
telemt_upstream_connect_success_total 19533
telemt_upstream_connect_attempts_per_request{bucket="1"} 19526
telemt_upstream_connect_attempts_per_request{bucket="2"} 7
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17859
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1553
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 12
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 19525
telemt_user_connections_current{user="hello"} 9
telemt_user_octets_from_client{user="hello"} 440016788 (419.63 MB)
telemt_user_octets_to_client{user="hello"} 9325485944 (8.69 GB)
telemt_user_msgs_from_client{user="hello"} 385943
telemt_user_msgs_to_client{user="hello"} 2186138
telemt_user_unique_ips_current{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.2.1

telemt_uptime_seconds 68519.1 (19h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 24933
telemt_connections_bad_total 12400
telemt_handshake_timeouts_total 51
telemt_upstream_connect_attempt_total 12097
telemt_upstream_connect_success_total 12093
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 12091
telemt_upstream_connect_attempts_per_request{bucket="2"} 3
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10202
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1858
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 12085
telemt_user_connections_current{user="hello"} 1
telemt_user_octets_from_client{user="hello"} 541607768 (516.52 MB)
telemt_user_octets_to_client{user="hello"} 23560951472 (21.94 GB)
telemt_user_msgs_from_client{user="hello"} 607855
telemt_user_msgs_to_client{user="hello"} 4502531
```