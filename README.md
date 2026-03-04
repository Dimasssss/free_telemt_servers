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

# Server Metrics 2026-03-04 09:55:35 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.2.0

telemt_uptime_seconds 5550.2 (1h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9684
telemt_connections_bad_total 7
telemt_handshake_timeouts_total 155
telemt_upstream_connect_attempt_total 8572
telemt_upstream_connect_success_total 8572
telemt_upstream_connect_attempts_per_request{bucket="1"} 8572
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8032
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 539
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 8570
telemt_user_connections_current{user="hello"} 105
telemt_user_octets_from_client{user="hello"} 116029663 (110.65 MB)
telemt_user_octets_to_client{user="hello"} 3896783625 (3.63 GB)
telemt_user_msgs_from_client{user="hello"} 184001
telemt_user_msgs_to_client{user="hello"} 677307
telemt_user_unique_ips_current{user="hello"} 10
```

## psb.hosting

```
telemt 3.2.0

telemt_uptime_seconds 5561.3 (1h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1055
telemt_connections_bad_total 35
telemt_handshake_timeouts_total 22
telemt_upstream_connect_attempt_total 961
telemt_upstream_connect_success_total 961
telemt_upstream_connect_attempts_per_request{bucket="1"} 961
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 934
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 959
telemt_user_connections_current{user="hello"} 21
telemt_user_octets_from_client{user="hello"} 37755410 (36.01 MB)
telemt_user_octets_to_client{user="hello"} 364860931 (347.96 MB)
telemt_user_msgs_from_client{user="hello"} 34217
telemt_user_msgs_to_client{user="hello"} 116101
telemt_user_unique_ips_current{user="hello"} 1
```

## koara.io

```
telemt 3.2.0

telemt_uptime_seconds 5545.8 (1h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1098
telemt_connections_bad_total 65
telemt_upstream_connect_attempt_total 1011
telemt_upstream_connect_success_total 1011
telemt_upstream_connect_attempts_per_request{bucket="1"} 1011
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 882
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 129
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1009
telemt_user_connections_current{user="hello"} 19
telemt_user_octets_from_client{user="hello"} 16608983 (15.84 MB)
telemt_user_octets_to_client{user="hello"} 1745938299 (1.63 GB)
telemt_user_msgs_from_client{user="hello"} 47298
telemt_user_msgs_to_client{user="hello"} 318567
telemt_user_unique_ips_current{user="hello"} 5
```

## landvps.ru

```
telemt 3.2.0

telemt_uptime_seconds 5536.3 (1h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2215
telemt_connections_bad_total 44
telemt_handshake_timeouts_total 11
telemt_upstream_connect_attempt_total 1984
telemt_upstream_connect_success_total 1983
telemt_upstream_connect_attempts_per_request{bucket="1"} 1982
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1912
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 50
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1981
telemt_user_connections_current{user="hello"} 29
telemt_user_octets_from_client{user="hello"} 7682371 (7.33 MB)
telemt_user_octets_to_client{user="hello"} 254252271 (242.47 MB)
telemt_user_msgs_from_client{user="hello"} 17282
telemt_user_msgs_to_client{user="hello"} 84135
telemt_user_unique_ips_current{user="hello"} 3
```

## rdp-onedash.ru

```
telemt 3.2.0

telemt_uptime_seconds 5547.7 (1h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1968
telemt_connections_bad_total 972
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 942
telemt_upstream_connect_success_total 942
telemt_upstream_connect_attempts_per_request{bucket="1"} 942
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 796
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 146
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 940
telemt_user_connections_current{user="hello"} 9
telemt_user_octets_from_client{user="hello"} 13270698 (12.66 MB)
telemt_user_octets_to_client{user="hello"} 490857570 (468.12 MB)
telemt_user_msgs_from_client{user="hello"} 29912
telemt_user_msgs_to_client{user="hello"} 127484
telemt_user_unique_ips_current{user="hello"} 2
```