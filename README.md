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

# Server Metrics 2026-03-14 07:58:44 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 174324.0 (48h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 669335
telemt_connections_bad_total 32412
telemt_handshake_timeouts_total 13167
telemt_upstream_connect_attempt_total 44313
telemt_upstream_connect_success_total 44090
telemt_upstream_connect_fail_total 223
telemt_upstream_connect_attempts_per_request{bucket="1"} 44313
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20173
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23765
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 152
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 223
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 5699
telemt_me_reconnect_attempts_total 39725
telemt_me_reconnect_success_total 35030
telemt_me_reader_eof_total 37461
telemt_me_idle_close_by_peer_total 37460
telemt_me_route_drop_no_conn_total 221314
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 570524
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2197
telemt_desync_full_logged_total 746
telemt_desync_suppressed_total 1451
telemt_desync_frames_bucket_total{bucket="1_2"} 473
telemt_desync_frames_bucket_total{bucket="3_10"} 808
telemt_desync_frames_bucket_total{bucket="gt_10"} 916
telemt_pool_swap_total 161
telemt_me_writer_removed_unexpected_total 35551
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 35010
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 521
telemt_user_connections_total{user="hello"} 570407
telemt_user_connections_current{user="hello"} 313
telemt_user_octets_from_client{user="hello"} 16616746818 (15.48 GB)
telemt_user_octets_to_client{user="hello"} 273224768708 (254.46 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 102
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 174216.4 (48h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 336840
telemt_connections_bad_total 2328
telemt_handshake_timeouts_total 2668
telemt_upstream_connect_attempt_total 151474
telemt_upstream_connect_success_total 150186
telemt_upstream_connect_fail_total 1288
telemt_upstream_connect_attempts_per_request{bucket="1"} 151474
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 110334
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37425
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2427
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1288
telemt_me_keepalive_timeout_total 4036
telemt_me_reconnect_attempts_total 178798
telemt_me_reconnect_success_total 38202
telemt_me_reader_eof_total 43642
telemt_me_idle_close_by_peer_total 43642
telemt_me_route_drop_no_conn_total 112344
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 215605
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 43
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 33
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 42958
telemt_me_refill_failed_total 4387
telemt_me_writer_restored_same_endpoint_total 38185
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 4756
telemt_user_connections_total{user="hello"} 318711
telemt_user_connections_current{user="hello"} 104
telemt_user_octets_from_client{user="hello"} 3299808651 (3.07 GB)
telemt_user_octets_to_client{user="hello"} 103840505567 (96.71 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 174180.9 (48h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 393995
telemt_connections_bad_total 3181
telemt_handshake_timeouts_total 35308
telemt_upstream_connect_attempt_total 45972
telemt_upstream_connect_success_total 45963
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 45972
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21019
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24876
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3503
telemt_me_reconnect_attempts_total 38534
telemt_me_reconnect_success_total 37247
telemt_me_reader_eof_total 40054
telemt_me_idle_close_by_peer_total 40054
telemt_me_route_drop_no_conn_total 142502
telemt_me_route_drop_channel_closed_total 21
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 341698
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 112
telemt_desync_full_logged_total 52
telemt_desync_suppressed_total 60
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 38
telemt_desync_frames_bucket_total{bucket="gt_10"} 62
telemt_pool_swap_total 165
telemt_me_writer_removed_unexpected_total 37698
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 37226
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 451
telemt_user_connections_total{user="hello"} 341469
telemt_user_connections_current{user="hello"} 156
telemt_user_octets_from_client{user="hello"} 13607440304 (12.67 GB)
telemt_user_octets_to_client{user="hello"} 139818608848 (130.22 GB)
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 174155.7 (48h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 496166
telemt_connections_bad_total 16267
telemt_handshake_timeouts_total 4549
telemt_upstream_connect_attempt_total 76503
telemt_upstream_connect_success_total 65891
telemt_upstream_connect_fail_total 10612
telemt_upstream_connect_attempts_per_request{bucket="1"} 76503
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38721
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26818
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 343
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10612
telemt_me_keepalive_timeout_total 5453
telemt_me_reconnect_attempts_total 145302
telemt_me_reconnect_success_total 38183
telemt_me_reader_eof_total 42758
telemt_me_idle_close_by_peer_total 42750
telemt_me_route_drop_no_conn_total 179728
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 423102
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 33
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1825
telemt_desync_full_logged_total 543
telemt_desync_suppressed_total 1282
telemt_desync_frames_bucket_total{bucket="1_2"} 431
telemt_desync_frames_bucket_total{bucket="3_10"} 696
telemt_desync_frames_bucket_total{bucket="gt_10"} 698
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 41967
telemt_me_refill_failed_total 3340
telemt_me_writer_restored_same_endpoint_total 38173
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3784
telemt_user_connections_total{user="hello"} 441978
telemt_user_connections_current{user="hello"} 181
telemt_user_octets_from_client{user="hello"} 9500740015 (8.85 GB)
telemt_user_octets_to_client{user="hello"} 180695591276 (168.29 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 124327.3 (34h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 203271
telemt_connections_bad_total 30407
telemt_handshake_timeouts_total 1764
telemt_upstream_connect_attempt_total 43586
telemt_upstream_connect_success_total 43166
telemt_upstream_connect_fail_total 420
telemt_upstream_connect_attempts_per_request{bucket="1"} 43586
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21597
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21427
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 142
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 420
telemt_me_keepalive_timeout_total 2530
telemt_me_reconnect_attempts_total 45511
telemt_me_reconnect_success_total 32077
telemt_me_reader_eof_total 34341
telemt_me_idle_close_by_peer_total 34341
telemt_me_route_drop_no_conn_total 60817
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 160633
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 701
telemt_desync_full_logged_total 171
telemt_desync_suppressed_total 530
telemt_desync_frames_bucket_total{bucket="1_2"} 114
telemt_desync_frames_bucket_total{bucket="3_10"} 335
telemt_desync_frames_bucket_total{bucket="gt_10"} 252
telemt_pool_swap_total 96
telemt_me_writer_removed_unexpected_total 32794
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 32059
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 717
telemt_user_connections_total{user="hello"} 165393
telemt_user_connections_current{user="hello"} 77
telemt_user_octets_from_client{user="hello"} 2448090989 (2.28 GB)
telemt_user_octets_to_client{user="hello"} 78481104783 (73.09 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 174111.8 (48h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 999086
telemt_connections_bad_total 36130
telemt_handshake_timeouts_total 26199
telemt_upstream_connect_attempt_total 36091
telemt_upstream_connect_success_total 35899
telemt_upstream_connect_fail_total 191
telemt_upstream_connect_attempts_per_request{bucket="1"} 36090
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16887
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18971
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 191
telemt_me_keepalive_timeout_total 4725
telemt_me_reconnect_attempts_total 31967
telemt_me_reconnect_success_total 27285
telemt_me_reader_eof_total 29292
telemt_me_idle_close_by_peer_total 29289
telemt_me_route_drop_no_conn_total 469879
telemt_me_route_drop_channel_closed_total 25
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 925919
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 770
telemt_desync_full_logged_total 254
telemt_desync_suppressed_total 516
telemt_desync_frames_bucket_total{bucket="1_2"} 257
telemt_desync_frames_bucket_total{bucket="3_10"} 253
telemt_desync_frames_bucket_total{bucket="gt_10"} 260
telemt_pool_swap_total 166
telemt_me_writer_removed_unexpected_total 27778
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 27278
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 493
telemt_user_connections_total{user="hello"} 898557
telemt_user_connections_current{user="hello"} 391
telemt_user_octets_from_client{user="hello"} 15315873920 (14.26 GB)
telemt_user_octets_to_client{user="hello"} 449801160252 (418.91 GB)
telemt_user_unique_ips_current{user="hello"} 159
telemt_user_unique_ips_recent_window{user="hello"} 60
```