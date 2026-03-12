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

# Server Metrics 2026-03-12 14:50:59 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 26256.8 (7h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 139361
telemt_connections_bad_total 1442
telemt_handshake_timeouts_total 4557
telemt_upstream_connect_attempt_total 6371
telemt_upstream_connect_success_total 6346
telemt_upstream_connect_fail_total 25
telemt_upstream_connect_attempts_per_request{bucket="1"} 6371
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2827
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3513
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 25
telemt_me_keepalive_timeout_total 272
telemt_me_reconnect_attempts_total 5004
telemt_me_reconnect_success_total 4970
telemt_me_reader_eof_total 5226
telemt_me_idle_close_by_peer_total 5225
telemt_me_route_drop_no_conn_total 39955
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 121496
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 570
telemt_desync_full_logged_total 212
telemt_desync_suppressed_total 358
telemt_desync_frames_bucket_total{bucket="1_2"} 105
telemt_desync_frames_bucket_total{bucket="3_10"} 221
telemt_desync_frames_bucket_total{bucket="gt_10"} 244
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 5015
telemt_me_writer_restored_same_endpoint_total 4954
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 45
telemt_user_connections_total{user="hello"} 121458
telemt_user_connections_current{user="hello"} 368
telemt_user_octets_from_client{user="hello"} 2051508284 (1.91 GB)
telemt_user_octets_to_client{user="hello"} 45593101928 (42.46 GB)
telemt_user_unique_ips_current{user="hello"} 107
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 26149.8 (7h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 58362
telemt_connections_bad_total 446
telemt_handshake_timeouts_total 374
telemt_upstream_connect_attempt_total 8034
telemt_upstream_connect_success_total 7856
telemt_upstream_connect_fail_total 178
telemt_upstream_connect_attempts_per_request{bucket="1"} 8034
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3201
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4620
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 178
telemt_me_keepalive_timeout_total 173
telemt_me_reconnect_attempts_total 23460
telemt_me_reconnect_success_total 6538
telemt_me_reader_eof_total 7189
telemt_me_idle_close_by_peer_total 7189
telemt_me_route_drop_no_conn_total 25942
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 55687
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 31
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 7110
telemt_me_refill_failed_total 528
telemt_me_writer_restored_same_endpoint_total 6523
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 572
telemt_user_connections_total{user="hello"} 55679
telemt_user_connections_current{user="hello"} 154
telemt_user_octets_from_client{user="hello"} 624182904 (595.27 MB)
telemt_user_octets_to_client{user="hello"} 15932384260 (14.84 GB)
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 26113.5 (7h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 79849
telemt_connections_bad_total 1428
telemt_handshake_timeouts_total 1539
telemt_upstream_connect_attempt_total 7005
telemt_upstream_connect_success_total 7005
telemt_upstream_connect_attempts_per_request{bucket="1"} 7005
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3399
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3596
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 119
telemt_me_reconnect_attempts_total 5704
telemt_me_reconnect_success_total 5655
telemt_me_reader_eof_total 5981
telemt_me_idle_close_by_peer_total 5981
telemt_me_route_drop_no_conn_total 28149
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 73533
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 4
telemt_desync_frames_bucket_total{bucket="3_10"} 6
telemt_desync_frames_bucket_total{bucket="gt_10"} 4
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 5698
telemt_me_writer_restored_same_endpoint_total 5635
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 73509
telemt_user_connections_current{user="hello"} 212
telemt_user_octets_from_client{user="hello"} 1975383212 (1.84 GB)
telemt_user_octets_to_client{user="hello"} 40793534404 (37.99 GB)
telemt_user_unique_ips_current{user="hello"} 82
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 26089.1 (7h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 101068
telemt_connections_bad_total 2960
telemt_handshake_timeouts_total 745
telemt_upstream_connect_attempt_total 6618
telemt_upstream_connect_success_total 6443
telemt_upstream_connect_fail_total 175
telemt_upstream_connect_attempts_per_request{bucket="1"} 6618
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2909
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3511
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 175
telemt_me_keepalive_timeout_total 257
telemt_me_reconnect_attempts_total 20945
telemt_me_reconnect_success_total 5117
telemt_me_reader_eof_total 5746
telemt_me_idle_close_by_peer_total 5746
telemt_me_route_drop_no_conn_total 37506
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 91724
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 302
telemt_desync_full_logged_total 99
telemt_desync_suppressed_total 203
telemt_desync_frames_bucket_total{bucket="1_2"} 105
telemt_desync_frames_bucket_total{bucket="3_10"} 101
telemt_desync_frames_bucket_total{bucket="gt_10"} 96
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 5671
telemt_me_refill_failed_total 493
telemt_me_writer_restored_same_endpoint_total 5109
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 121
telemt_me_writer_removed_unexpected_minus_restored_total 554
telemt_user_connections_total{user="hello"} 91608
telemt_user_connections_current{user="hello"} 178
telemt_user_octets_from_client{user="hello"} 1755646488 (1.64 GB)
telemt_user_octets_to_client{user="hello"} 38055382880 (35.44 GB)
telemt_user_unique_ips_current{user="hello"} 64
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 26058.6 (7h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 60311
telemt_connections_bad_total 5059
telemt_handshake_timeouts_total 1050
telemt_upstream_connect_attempt_total 24865
telemt_upstream_connect_success_total 24546
telemt_upstream_connect_fail_total 319
telemt_upstream_connect_attempts_per_request{bucket="1"} 24865
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20027
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4490
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 319
telemt_me_keepalive_timeout_total 105
telemt_me_reconnect_attempts_total 34207
telemt_me_reconnect_success_total 3684
telemt_me_reader_eof_total 4634
telemt_me_idle_close_by_peer_total 4634
telemt_me_seq_mismatch_total 8
telemt_me_route_drop_no_conn_total 12478
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 33234
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 448
telemt_desync_full_logged_total 125
telemt_desync_suppressed_total 323
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 372
telemt_desync_frames_bucket_total{bucket="gt_10"} 59
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 4659
telemt_me_refill_failed_total 955
telemt_me_writer_restored_same_endpoint_total 3667
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 975
telemt_user_connections_total{user="hello"} 52771
telemt_user_connections_current{user="hello"} 156
telemt_user_octets_from_client{user="hello"} 438840782 (418.51 MB)
telemt_user_octets_to_client{user="hello"} 14317551186 (13.33 GB)
telemt_user_msgs_from_client{user="hello"} 288228
telemt_user_msgs_to_client{user="hello"} 1054678
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 26045.9 (7h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 160373
telemt_connections_bad_total 805
telemt_handshake_timeouts_total 1241
telemt_upstream_connect_attempt_total 5289
telemt_upstream_connect_success_total 5262
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 5289
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2499
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2761
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_keepalive_timeout_total 117
telemt_me_reconnect_attempts_total 3980
telemt_me_reconnect_success_total 3949
telemt_me_reader_eof_total 4160
telemt_me_idle_close_by_peer_total 4160
telemt_me_route_drop_no_conn_total 62359
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 153443
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 236
telemt_desync_full_logged_total 90
telemt_desync_suppressed_total 146
telemt_desync_frames_bucket_total{bucket="1_2"} 59
telemt_desync_frames_bucket_total{bucket="3_10"} 88
telemt_desync_frames_bucket_total{bucket="gt_10"} 89
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 3995
telemt_me_writer_restored_same_endpoint_total 3942
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 153409
telemt_user_connections_current{user="hello"} 452
telemt_user_octets_from_client{user="hello"} 3092586784 (2.88 GB)
telemt_user_octets_to_client{user="hello"} 69085909108 (64.34 GB)
telemt_user_unique_ips_current{user="hello"} 145
telemt_user_unique_ips_recent_window{user="hello"} 65
```