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

# Server Metrics 2026-03-15 08:35:46 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 37277.7 (10h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 134994
telemt_connections_bad_total 1091
telemt_handshake_timeouts_total 3455
telemt_upstream_connect_attempt_total 8982
telemt_upstream_connect_success_total 8928
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 8982
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4005
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4916
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 7092
telemt_me_reconnect_success_total 7065
telemt_me_reader_eof_total 7552
telemt_me_idle_close_by_peer_total 7552
telemt_me_route_drop_no_conn_total 262504
telemt_me_route_drop_channel_closed_total 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 163390
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1002
telemt_desync_full_logged_total 421
telemt_desync_suppressed_total 581
telemt_desync_frames_bucket_total{bucket="1_2"} 173
telemt_desync_frames_bucket_total{bucket="3_10"} 408
telemt_desync_frames_bucket_total{bucket="gt_10"} 421
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 7127
telemt_me_writer_restored_same_endpoint_total 7034
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 125459
telemt_user_connections_current{user="hello"} 365
telemt_user_octets_from_client{user="hello"} 1713197084 (1.60 GB)
telemt_user_octets_to_client{user="hello"} 118516320004 (110.38 GB)
telemt_user_unique_ips_current{user="hello"} 104
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 37284.7 (10h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 41359
telemt_connections_bad_total 267
telemt_handshake_timeouts_total 1904
telemt_upstream_connect_attempt_total 10184
telemt_upstream_connect_success_total 10184
telemt_upstream_connect_attempts_per_request{bucket="1"} 10184
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4372
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5780
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 9424
telemt_me_reconnect_success_total 8300
telemt_me_reader_eof_total 8904
telemt_me_idle_close_by_peer_total 8904
telemt_me_route_drop_no_conn_total 21077
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 37742
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 8415
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 8284
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 115
telemt_user_connections_total{user="hello"} 37744
telemt_user_connections_current{user="hello"} 170
telemt_user_octets_from_client{user="hello"} 867404252 (827.22 MB)
telemt_user_octets_to_client{user="hello"} 13945028000 (12.99 GB)
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 37277.2 (10h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 51370
telemt_connections_bad_total 481
telemt_handshake_timeouts_total 1910
telemt_upstream_connect_attempt_total 9927
telemt_upstream_connect_success_total 9926
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 9927
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4362
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5555
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 8087
telemt_me_reconnect_success_total 8047
telemt_me_reader_eof_total 8702
telemt_me_idle_close_by_peer_total 8702
telemt_me_route_drop_no_conn_total 17863
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 46773
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 20
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 10
telemt_desync_frames_bucket_total{bucket="3_10"} 10
telemt_desync_frames_bucket_total{bucket="gt_10"} 10
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 8125
telemt_me_writer_restored_same_endpoint_total 8043
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 78
telemt_user_connections_total{user="hello"} 46706
telemt_user_connections_current{user="hello"} 126
telemt_user_octets_from_client{user="hello"} 8976172616 (8.36 GB)
telemt_user_octets_to_client{user="hello"} 30528602520 (28.43 GB)
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 37276.8 (10h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 62358
telemt_connections_bad_total 164
telemt_handshake_timeouts_total 408
telemt_upstream_connect_attempt_total 8876
telemt_upstream_connect_success_total 8875
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 8876
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4195
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4654
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 7041
telemt_me_reconnect_success_total 7011
telemt_me_reader_eof_total 7498
telemt_me_idle_close_by_peer_total 7498
telemt_me_route_drop_no_conn_total 26999
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 56477
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 116
telemt_desync_full_logged_total 33
telemt_desync_suppressed_total 83
telemt_desync_frames_bucket_total{bucket="1_2"} 26
telemt_desync_frames_bucket_total{bucket="3_10"} 51
telemt_desync_frames_bucket_total{bucket="gt_10"} 39
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 7083
telemt_me_writer_restored_same_endpoint_total 7000
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 72
telemt_user_connections_total{user="hello"} 56409
telemt_user_connections_current{user="hello"} 277
telemt_user_octets_from_client{user="hello"} 1116325180 (1.04 GB)
telemt_user_octets_to_client{user="hello"} 35079371140 (32.67 GB)
telemt_user_unique_ips_current{user="hello"} 83
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 12348.4 (3h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19595
telemt_connections_bad_total 2360
telemt_handshake_timeouts_total 240
telemt_upstream_connect_attempt_total 4378
telemt_upstream_connect_success_total 4339
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 4378
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1908
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2419
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_reconnect_attempts_total 97945
telemt_me_reconnect_success_total 3545
telemt_me_reader_eof_total 3637
telemt_me_idle_close_by_peer_total 3637
telemt_me_route_drop_no_conn_total 5867
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16447
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8
telemt_desync_full_logged_total 2
telemt_desync_suppressed_total 6
telemt_desync_frames_bucket_total{bucket="3_10"} 5
telemt_desync_frames_bucket_total{bucket="gt_10"} 3
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 3500
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 3441
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_user_connections_total{user="hello"} 16587
telemt_user_connections_current{user="hello"} 82
telemt_user_octets_from_client{user="hello"} 133891341 (127.69 MB)
telemt_user_octets_to_client{user="hello"} 10141176891 (9.44 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 37276.3 (10h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 162994
telemt_connections_bad_total 21281
telemt_handshake_timeouts_total 871
telemt_upstream_connect_attempt_total 8091
telemt_upstream_connect_success_total 8042
telemt_upstream_connect_fail_total 49
telemt_upstream_connect_attempts_per_request{bucket="1"} 8091
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4078
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3963
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 49
telemt_me_reconnect_attempts_total 6201
telemt_me_reconnect_success_total 6171
telemt_me_reader_eof_total 6581
telemt_me_idle_close_by_peer_total 6581
telemt_me_route_drop_no_conn_total 77691
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 136473
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 41
telemt_desync_full_logged_total 18
telemt_desync_suppressed_total 23
telemt_desync_frames_bucket_total{bucket="1_2"} 9
telemt_desync_frames_bucket_total{bucket="3_10"} 18
telemt_desync_frames_bucket_total{bucket="gt_10"} 14
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 6206
telemt_me_writer_restored_same_endpoint_total 6144
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 135016
telemt_user_connections_current{user="hello"} 429
telemt_user_octets_from_client{user="hello"} 3635810668 (3.39 GB)
telemt_user_octets_to_client{user="hello"} 71781142964 (66.85 GB)
telemt_user_unique_ips_current{user="hello"} 180
telemt_user_unique_ips_recent_window{user="hello"} 61
```