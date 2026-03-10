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

# Server Metrics 2026-03-10 04:40:53 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 105661.8 (29h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 195510
telemt_connections_bad_total 2379
telemt_handshake_timeouts_total 1859
telemt_upstream_connect_attempt_total 183531
telemt_upstream_connect_success_total 183474
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 183531
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 168997
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14413
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 183464
telemt_user_connections_current{user="hello"} 239
telemt_user_octets_from_client{user="hello"} 5087946909 (4.74 GB)
telemt_user_octets_to_client{user="hello"} 113152160098 (105.38 GB)
telemt_user_msgs_from_client{user="hello"} 4718092
telemt_user_msgs_to_client{user="hello"} 7034369
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 105660.8 (29h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 59649
telemt_connections_bad_total 3145
telemt_handshake_timeouts_total 899
telemt_upstream_connect_attempt_total 52432
telemt_upstream_connect_success_total 52391
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 52432
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 46911
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5114
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 366
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 52381
telemt_user_connections_current{user="hello"} 31
telemt_user_octets_from_client{user="hello"} 2157870390 (2.01 GB)
telemt_user_octets_to_client{user="hello"} 24706129504 (23.01 GB)
telemt_user_msgs_from_client{user="hello"} 1594972
telemt_user_msgs_to_client{user="hello"} 7089541
telemt_user_unique_ips_current{user="hello"} 10
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 105661.2 (29h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 86502
telemt_connections_bad_total 993
telemt_handshake_timeouts_total 3995
telemt_upstream_connect_attempt_total 57193
telemt_upstream_connect_success_total 57191
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 57193
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 50198
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6980
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 57181
telemt_user_connections_current{user="hello"} 27
telemt_user_octets_from_client{user="hello"} 6088632181 (5.67 GB)
telemt_user_octets_to_client{user="hello"} 56520318639 (52.64 GB)
telemt_user_msgs_from_client{user="hello"} 3611868
telemt_user_msgs_to_client{user="hello"} 8604905
telemt_user_unique_ips_current{user="hello"} 17
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 105656.0 (29h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 81060
telemt_connections_bad_total 582
telemt_handshake_timeouts_total 1067
telemt_upstream_connect_attempt_total 75143
telemt_upstream_connect_success_total 74975
telemt_upstream_connect_fail_total 168
telemt_upstream_connect_attempts_per_request{bucket="1"} 75143
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 65793
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8966
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 40
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 176
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 168
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 74963
telemt_user_connections_current{user="hello"} 69
telemt_user_octets_from_client{user="hello"} 2350003665 (2.19 GB)
telemt_user_octets_to_client{user="hello"} 51603204452 (48.06 GB)
telemt_user_msgs_from_client{user="hello"} 2003898
telemt_user_msgs_to_client{user="hello"} 12301509
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 105661.4 (29h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 133437
telemt_connections_bad_total 23172
telemt_handshake_timeouts_total 3080
telemt_upstream_connect_attempt_total 101776
telemt_upstream_connect_success_total 100985
telemt_upstream_connect_fail_total 791
telemt_upstream_connect_attempts_per_request{bucket="1"} 101776
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 86466
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14362
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 157
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 791
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 100975
telemt_user_connections_current{user="hello"} 39
telemt_user_octets_from_client{user="hello"} 1651187473 (1.54 GB)
telemt_user_octets_to_client{user="hello"} 91641031225 (85.35 GB)
telemt_user_msgs_from_client{user="hello"} 2273482
telemt_user_msgs_to_client{user="hello"} 12367125
telemt_user_unique_ips_current{user="hello"} 21
telemt_user_unique_ips_recent_window{user="hello"} 21
```