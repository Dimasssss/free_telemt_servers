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

# Server Metrics 2026-03-09 18:57:28 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 70656.8 (19h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 134438
telemt_connections_bad_total 1800
telemt_handshake_timeouts_total 1114
telemt_upstream_connect_attempt_total 125880
telemt_upstream_connect_success_total 125837
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 125880
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 115906
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9870
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 125829
telemt_user_connections_current{user="hello"} 234
telemt_user_octets_from_client{user="hello"} 3648405760 (3.40 GB)
telemt_user_octets_to_client{user="hello"} 69632125794 (64.85 GB)
telemt_user_msgs_from_client{user="hello"} 3246028
telemt_user_msgs_to_client{user="hello"} 4453771
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 70655.5 (19h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 39572
telemt_connections_bad_total 233
telemt_handshake_timeouts_total 457
telemt_upstream_connect_attempt_total 37171
telemt_upstream_connect_success_total 37150
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 37171
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33460
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3365
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 325
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 37142
telemt_user_connections_current{user="hello"} 92
telemt_user_octets_from_client{user="hello"} 1090881437 (1.02 GB)
telemt_user_octets_to_client{user="hello"} 18157083851 (16.91 GB)
telemt_user_msgs_from_client{user="hello"} 998805
telemt_user_msgs_to_client{user="hello"} 5127680
telemt_user_unique_ips_current{user="hello"} 22
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 70656.2 (19h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 49176
telemt_connections_bad_total 699
telemt_handshake_timeouts_total 2552
telemt_upstream_connect_attempt_total 38373
telemt_upstream_connect_success_total 38373
telemt_upstream_connect_attempts_per_request{bucket="1"} 38373
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34159
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4208
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 38365
telemt_user_connections_current{user="hello"} 55
telemt_user_octets_from_client{user="hello"} 4666515998 (4.35 GB)
telemt_user_octets_to_client{user="hello"} 27736471568 (25.83 GB)
telemt_user_msgs_from_client{user="hello"} 2321063
telemt_user_msgs_to_client{user="hello"} 3980158
telemt_user_unique_ips_current{user="hello"} 22
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 70650.8 (19h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 55025
telemt_connections_bad_total 253
telemt_handshake_timeouts_total 920
telemt_upstream_connect_attempt_total 50423
telemt_upstream_connect_success_total 50296
telemt_upstream_connect_fail_total 127
telemt_upstream_connect_attempts_per_request{bucket="1"} 50423
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43583
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6564
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 122
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 127
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 50288
telemt_user_connections_current{user="hello"} 120
telemt_user_octets_from_client{user="hello"} 2113456992 (1.97 GB)
telemt_user_octets_to_client{user="hello"} 38846010239 (36.18 GB)
telemt_user_msgs_from_client{user="hello"} 1512603
telemt_user_msgs_to_client{user="hello"} 9347823
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 70656.3 (19h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 89118
telemt_connections_bad_total 16625
telemt_handshake_timeouts_total 2344
telemt_upstream_connect_attempt_total 66186
telemt_upstream_connect_success_total 66183
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 66185
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 56194
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9906
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 83
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 66175
telemt_user_connections_current{user="hello"} 124
telemt_user_octets_from_client{user="hello"} 1148872247 (1.07 GB)
telemt_user_octets_to_client{user="hello"} 59791033797 (55.68 GB)
telemt_user_msgs_from_client{user="hello"} 1523076
telemt_user_msgs_to_client{user="hello"} 7840687
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 21
```