# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt  
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### [Итог по хостингам](Reviews.md)

---

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

## hostvds.com
- Локация: Нидерланды, Амстердам
- Тариф: Burstable
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 10 Gbit/s
- Цена в месяц: €7.98
- Оплачен до: 13 апреля
- Ссылка:
```bash
tg://proxy?server=s6.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-14 15:47:18 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.17

telemt_uptime_seconds 9058.3 (2h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 53027
telemt_connections_bad_total 10564
telemt_handshake_timeouts_total 245
telemt_upstream_connect_attempt_total 2326
telemt_upstream_connect_success_total 2324
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 2326
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1097
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1157
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 70
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 71
telemt_me_reconnect_attempts_total 1841
telemt_me_reconnect_success_total 1818
telemt_me_reader_eof_total 1894
telemt_me_idle_close_by_peer_total 1894
telemt_me_route_drop_no_conn_total 19806
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 40963
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 111
telemt_desync_full_logged_total 44
telemt_desync_suppressed_total 67
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 52
telemt_desync_frames_bucket_total{bucket="gt_10"} 46
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 1855
telemt_me_writer_restored_same_endpoint_total 1800
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 72
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 40899
telemt_user_connections_current{user="hello"} 326
telemt_user_octets_from_client{user="hello"} 701751968 (669.24 MB)
telemt_user_octets_to_client{user="hello"} 14386204392 (13.40 GB)
telemt_user_unique_ips_current{user="hello"} 101
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## psb.hosting

```
telemt 3.3.17

telemt_uptime_seconds 9056.7 (2h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20595
telemt_connections_bad_total 40
telemt_handshake_timeouts_total 500
telemt_upstream_connect_attempt_total 2489
telemt_upstream_connect_success_total 2461
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 2489
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 989
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1452
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 43
telemt_me_reconnect_attempts_total 4523
telemt_me_reconnect_success_total 1966
telemt_me_reader_eof_total 2101
telemt_me_idle_close_by_peer_total 2101
telemt_me_route_drop_no_conn_total 11122
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 19353
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 2074
telemt_me_refill_failed_total 79
telemt_me_writer_restored_same_endpoint_total 1961
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 120
telemt_me_writer_removed_unexpected_minus_restored_total 108
telemt_user_connections_total{user="hello"} 19336
telemt_user_connections_current{user="hello"} 166
telemt_user_octets_from_client{user="hello"} 261486992 (249.37 MB)
telemt_user_octets_to_client{user="hello"} 7983294384 (7.44 GB)
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## koara.io

```
telemt 3.3.17

telemt_uptime_seconds 9061.0 (2h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20613
telemt_connections_bad_total 214
telemt_handshake_timeouts_total 989
telemt_upstream_connect_attempt_total 3908
telemt_upstream_connect_success_total 3874
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 3907
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1932
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1941
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_keepalive_timeout_total 66
telemt_me_reconnect_attempts_total 96940
telemt_me_reconnect_success_total 3060
telemt_me_reader_eof_total 3198
telemt_me_idle_close_by_peer_total 3198
telemt_me_route_drop_no_conn_total 7958
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 18039
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 3184
telemt_me_refill_failed_total 3045
telemt_me_writer_restored_same_endpoint_total 3022
telemt_me_writer_restored_fallback_total 38
telemt_me_async_recovery_trigger_total 1685
telemt_me_writer_removed_unexpected_minus_restored_total 124
telemt_user_connections_total{user="hello"} 18331
telemt_user_connections_current{user="hello"} 188
telemt_user_octets_from_client{user="hello"} 550960205 (525.44 MB)
telemt_user_octets_to_client{user="hello"} 8701323414 (8.10 GB)
telemt_user_msgs_from_client{user="hello"} 3762
telemt_user_msgs_to_client{user="hello"} 18362
telemt_user_unique_ips_current{user="hello"} 69
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## landvps.ru

```
telemt 3.3.17

telemt_uptime_seconds 9066.1 (2h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 28925
telemt_connections_bad_total 77
telemt_handshake_timeouts_total 193
telemt_upstream_connect_attempt_total 2466
telemt_upstream_connect_success_total 2451
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 2466
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1100
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1335
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 52
telemt_me_reconnect_attempts_total 1970
telemt_me_reconnect_success_total 1957
telemt_me_reader_eof_total 2018
telemt_me_idle_close_by_peer_total 2018
telemt_me_route_drop_no_conn_total 13742
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 27534
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 318
telemt_desync_full_logged_total 87
telemt_desync_suppressed_total 231
telemt_desync_frames_bucket_total{bucket="1_2"} 48
telemt_desync_frames_bucket_total{bucket="3_10"} 132
telemt_desync_frames_bucket_total{bucket="gt_10"} 138
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 1968
telemt_me_writer_restored_same_endpoint_total 1955
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 60
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 27416
telemt_user_connections_current{user="hello"} 251
telemt_user_octets_from_client{user="hello"} 329457768 (314.20 MB)
telemt_user_octets_to_client{user="hello"} 10526963960 (9.80 GB)
telemt_user_unique_ips_current{user="hello"} 73
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## rdp-onedash.ru

```
telemt 3.3.17

telemt_uptime_seconds 9058.9 (2h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20323
telemt_connections_bad_total 1819
telemt_handshake_timeouts_total 890
telemt_upstream_connect_attempt_total 2019
telemt_upstream_connect_success_total 1990
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 2019
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 811
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1177
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 42
telemt_me_reconnect_attempts_total 7998
telemt_me_reconnect_success_total 1490
telemt_me_reader_eof_total 1683
telemt_me_idle_close_by_peer_total 1683
telemt_me_route_drop_no_conn_total 7154
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16655
telemt_me_writer_pick_total{mode="p2c",result="full"} 2
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 65
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 56
telemt_desync_frames_bucket_total{bucket="1_2"} 10
telemt_desync_frames_bucket_total{bucket="3_10"} 28
telemt_desync_frames_bucket_total{bucket="gt_10"} 27
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 1692
telemt_me_refill_failed_total 203
telemt_me_writer_restored_same_endpoint_total 1486
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 202
telemt_user_connections_total{user="hello"} 16650
telemt_user_connections_current{user="hello"} 84
telemt_user_octets_from_client{user="hello"} 138589544 (132.17 MB)
telemt_user_octets_to_client{user="hello"} 4038305276 (3.76 GB)
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## hostvds.com

```
telemt 3.3.17

telemt_uptime_seconds 9058.3 (2h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 70413
telemt_connections_bad_total 201
telemt_handshake_timeouts_total 480
telemt_upstream_connect_attempt_total 2053
telemt_upstream_connect_success_total 2009
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 2053
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1001
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1007
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_keepalive_timeout_total 38
telemt_me_reconnect_attempts_total 2536
telemt_me_reconnect_success_total 1512
telemt_me_reader_eof_total 1566
telemt_me_idle_close_by_peer_total 1566
telemt_me_route_drop_no_conn_total 35717
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 65357
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 4
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 4
telemt_desync_frames_bucket_total{bucket="3_10"} 3
telemt_desync_frames_bucket_total{bucket="gt_10"} 7
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 1557
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 1508
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 45
telemt_user_connections_total{user="hello"} 65259
telemt_user_connections_current{user="hello"} 484
telemt_user_octets_from_client{user="hello"} 1077231384 (1.00 GB)
telemt_user_octets_to_client{user="hello"} 25167967928 (23.44 GB)
telemt_user_unique_ips_current{user="hello"} 190
telemt_user_unique_ips_recent_window{user="hello"} 70
```