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

# Server Metrics 2026-03-14 16:17:59 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.17

telemt_uptime_seconds 10899.2 (3h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 63624
telemt_connections_bad_total 12271
telemt_handshake_timeouts_total 299
telemt_upstream_connect_attempt_total 2799
telemt_upstream_connect_success_total 2797
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 2799
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1347
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1379
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 88
telemt_me_reconnect_attempts_total 2208
telemt_me_reconnect_success_total 2182
telemt_me_reader_eof_total 2279
telemt_me_idle_close_by_peer_total 2279
telemt_me_route_drop_no_conn_total 23317
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 49342
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 143
telemt_desync_full_logged_total 61
telemt_desync_suppressed_total 82
telemt_desync_frames_bucket_total{bucket="1_2"} 19
telemt_desync_frames_bucket_total{bucket="3_10"} 66
telemt_desync_frames_bucket_total{bucket="gt_10"} 58
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 2228
telemt_me_writer_restored_same_endpoint_total 2164
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 72
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 49276
telemt_user_connections_current{user="hello"} 354
telemt_user_octets_from_client{user="hello"} 812565772 (774.92 MB)
telemt_user_octets_to_client{user="hello"} 17882260008 (16.65 GB)
telemt_user_unique_ips_current{user="hello"} 107
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## psb.hosting

```
telemt 3.3.17

telemt_uptime_seconds 10897.3 (3h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 25737
telemt_connections_bad_total 392
telemt_handshake_timeouts_total 547
telemt_upstream_connect_attempt_total 3112
telemt_upstream_connect_success_total 3083
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 3112
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1250
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1794
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 39
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 48
telemt_me_reconnect_attempts_total 5031
telemt_me_reconnect_success_total 2467
telemt_me_reader_eof_total 2610
telemt_me_idle_close_by_peer_total 2610
telemt_me_route_drop_no_conn_total 13080
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 23968
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
telemt_me_writer_removed_unexpected_total 2585
telemt_me_refill_failed_total 79
telemt_me_writer_restored_same_endpoint_total 2462
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 120
telemt_me_writer_removed_unexpected_minus_restored_total 118
telemt_user_connections_total{user="hello"} 23951
telemt_user_connections_current{user="hello"} 253
telemt_user_octets_from_client{user="hello"} 314503888 (299.93 MB)
telemt_user_octets_to_client{user="hello"} 9844351048 (9.17 GB)
telemt_user_unique_ips_current{user="hello"} 70
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## koara.io

```
telemt 3.3.17

telemt_uptime_seconds 10901.6 (3h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 25307
telemt_connections_bad_total 228
telemt_handshake_timeouts_total 1355
telemt_upstream_connect_attempt_total 4454
telemt_upstream_connect_success_total 4409
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 4453
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2197
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2211
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_keepalive_timeout_total 73
telemt_me_reconnect_attempts_total 97371
telemt_me_reconnect_success_total 3488
telemt_me_reader_eof_total 3650
telemt_me_idle_close_by_peer_total 3650
telemt_me_route_drop_no_conn_total 9673
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 22072
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1
telemt_desync_full_logged_total 1
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 3616
telemt_me_refill_failed_total 3045
telemt_me_writer_restored_same_endpoint_total 3450
telemt_me_writer_restored_fallback_total 38
telemt_me_async_recovery_trigger_total 1685
telemt_me_writer_removed_unexpected_minus_restored_total 128
telemt_user_connections_total{user="hello"} 22364
telemt_user_connections_current{user="hello"} 165
telemt_user_octets_from_client{user="hello"} 852471429 (812.98 MB)
telemt_user_octets_to_client{user="hello"} 10390337606 (9.68 GB)
telemt_user_msgs_from_client{user="hello"} 3762
telemt_user_msgs_to_client{user="hello"} 18362
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## landvps.ru

```
telemt 3.3.17

telemt_uptime_seconds 10906.3 (3h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 34474
telemt_connections_bad_total 102
telemt_handshake_timeouts_total 226
telemt_upstream_connect_attempt_total 3145
telemt_upstream_connect_success_total 3129
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 3145
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1424
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1686
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 68
telemt_me_reconnect_attempts_total 2530
telemt_me_reconnect_success_total 2514
telemt_me_reader_eof_total 2582
telemt_me_idle_close_by_peer_total 2582
telemt_me_route_drop_no_conn_total 16239
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 32823
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 337
telemt_desync_full_logged_total 91
telemt_desync_suppressed_total 246
telemt_desync_frames_bucket_total{bucket="1_2"} 54
telemt_desync_frames_bucket_total{bucket="3_10"} 137
telemt_desync_frames_bucket_total{bucket="gt_10"} 146
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 2535
telemt_me_writer_restored_same_endpoint_total 2512
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 60
telemt_me_writer_removed_unexpected_minus_restored_total 21
telemt_user_connections_total{user="hello"} 32705
telemt_user_connections_current{user="hello"} 172
telemt_user_octets_from_client{user="hello"} 369544068 (352.42 MB)
telemt_user_octets_to_client{user="hello"} 11788464040 (10.98 GB)
telemt_user_unique_ips_current{user="hello"} 64
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## rdp-onedash.ru

```
telemt 3.3.17

telemt_uptime_seconds 10899.4 (3h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 24284
telemt_connections_bad_total 2183
telemt_handshake_timeouts_total 1054
telemt_upstream_connect_attempt_total 2527
telemt_upstream_connect_success_total 2491
telemt_upstream_connect_fail_total 35
telemt_upstream_connect_attempts_per_request{bucket="1"} 2526
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1075
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1407
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 35
telemt_me_keepalive_timeout_total 57
telemt_me_reconnect_attempts_total 8393
telemt_me_reconnect_success_total 1878
telemt_me_reader_eof_total 2090
telemt_me_idle_close_by_peer_total 2090
telemt_me_route_drop_no_conn_total 8437
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 19899
telemt_me_writer_pick_total{mode="p2c",result="full"} 2
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 96
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 85
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 36
telemt_desync_frames_bucket_total{bucket="gt_10"} 47
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 2087
telemt_me_refill_failed_total 203
telemt_me_writer_restored_same_endpoint_total 1874
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 209
telemt_user_connections_total{user="hello"} 19894
telemt_user_connections_current{user="hello"} 82
telemt_user_octets_from_client{user="hello"} 183078336 (174.60 MB)
telemt_user_octets_to_client{user="hello"} 5499511764 (5.12 GB)
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## hostvds.com

```
telemt 3.3.17

telemt_uptime_seconds 10899.0 (3h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 84312
telemt_connections_bad_total 236
telemt_handshake_timeouts_total 898
telemt_upstream_connect_attempt_total 2375
telemt_upstream_connect_success_total 2326
telemt_upstream_connect_fail_total 49
telemt_upstream_connect_attempts_per_request{bucket="1"} 2375
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1172
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1153
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 49
telemt_me_keepalive_timeout_total 48
telemt_me_reconnect_attempts_total 5367
telemt_me_reconnect_success_total 1717
telemt_me_reader_eof_total 1854
telemt_me_idle_close_by_peer_total 1854
telemt_me_route_drop_no_conn_total 43145
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 78294
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 4
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 20
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 11
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 5
telemt_desync_frames_bucket_total{bucket="gt_10"} 9
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 1847
telemt_me_refill_failed_total 113
telemt_me_writer_restored_same_endpoint_total 1713
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 130
telemt_user_connections_total{user="hello"} 78187
telemt_user_connections_current{user="hello"} 555
telemt_user_octets_from_client{user="hello"} 1315289660 (1.22 GB)
telemt_user_octets_to_client{user="hello"} 33586063388 (31.28 GB)
telemt_user_unique_ips_current{user="hello"} 222
telemt_user_unique_ips_recent_window{user="hello"} 82
```