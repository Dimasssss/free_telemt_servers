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

## 4vps.su
- Локация: Польша, Варшава
- Тариф: PL-cx21
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 2 Gbit/s
- Цена в месяц: 770 RUB
- Оплачен до: 16 апреля
- Ссылка:
```bash
tg://proxy?server=s7.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-17 11:45:46 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 61229.6 (17h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 554868
telemt_connections_bad_total 4673
telemt_handshake_timeouts_total 16698
telemt_upstream_connect_attempt_total 15104
telemt_upstream_connect_success_total 14662
telemt_upstream_connect_fail_total 442
telemt_upstream_connect_attempts_per_request{bucket="1"} 15104
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7741
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6771
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 442
telemt_me_keepalive_timeout_total 110
telemt_me_reconnect_attempts_total 10864
telemt_me_reconnect_success_total 9328
telemt_me_reader_eof_total 9902
telemt_me_idle_close_by_peer_total 9901
telemt_me_route_drop_no_conn_total 180693
telemt_me_route_drop_channel_closed_total 49
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 500967
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3932
telemt_desync_full_logged_total 1043
telemt_desync_suppressed_total 2889
telemt_desync_frames_bucket_total{bucket="1_2"} 1138
telemt_desync_frames_bucket_total{bucket="3_10"} 1638
telemt_desync_frames_bucket_total{bucket="gt_10"} 1156
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 9511
telemt_me_refill_failed_total 43
telemt_me_writer_restored_same_endpoint_total 9306
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 183
telemt_user_connections_total{user="hello"} 502895
telemt_user_connections_current{user="hello"} 989
telemt_user_octets_from_client{user="hello"} 6832941899 (6.36 GB)
telemt_user_octets_to_client{user="hello"} 182597576379 (170.06 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 319
telemt_user_unique_ips_recent_window{user="hello"} 134
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 61481.1 (17h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 310513
telemt_connections_bad_total 13171
telemt_handshake_timeouts_total 17762
telemt_upstream_connect_attempt_total 15532
telemt_upstream_connect_success_total 15312
telemt_upstream_connect_fail_total 220
telemt_upstream_connect_attempts_per_request{bucket="1"} 15532
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6614
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8473
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 225
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 220
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 24582
telemt_me_reconnect_success_total 12247
telemt_me_reader_eof_total 13219
telemt_me_idle_close_by_peer_total 13219
telemt_me_route_drop_no_conn_total 114912
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 264369
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 834
telemt_desync_full_logged_total 296
telemt_desync_suppressed_total 538
telemt_desync_frames_bucket_total{bucket="1_2"} 232
telemt_desync_frames_bucket_total{bucket="3_10"} 349
telemt_desync_frames_bucket_total{bucket="gt_10"} 253
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 12765
telemt_me_refill_failed_total 384
telemt_me_writer_restored_same_endpoint_total 12231
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 518
telemt_user_connections_total{user="hello"} 264361
telemt_user_connections_current{user="hello"} 546
telemt_user_octets_from_client{user="hello"} 3100125748 (2.89 GB)
telemt_user_octets_to_client{user="hello"} 95383976828 (88.83 GB)
telemt_user_unique_ips_current{user="hello"} 171
telemt_user_unique_ips_recent_window{user="hello"} 77
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 61257.9 (17h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 182486
telemt_connections_bad_total 7724
telemt_handshake_timeouts_total 15001
telemt_upstream_connect_attempt_total 16050
telemt_upstream_connect_success_total 15965
telemt_upstream_connect_fail_total 85
telemt_upstream_connect_attempts_per_request{bucket="1"} 16050
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7063
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8829
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 68
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 85
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 14755
telemt_me_reconnect_success_total 12882
telemt_me_reader_eof_total 13766
telemt_me_idle_close_by_peer_total 13766
telemt_me_route_drop_no_conn_total 54679
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 149334
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 549
telemt_desync_full_logged_total 144
telemt_desync_suppressed_total 405
telemt_desync_frames_bucket_total{bucket="1_2"} 235
telemt_desync_frames_bucket_total{bucket="3_10"} 237
telemt_desync_frames_bucket_total{bucket="gt_10"} 77
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 13125
telemt_me_refill_failed_total 56
telemt_me_writer_restored_same_endpoint_total 12871
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 243
telemt_user_connections_total{user="hello"} 149236
telemt_user_connections_current{user="hello"} 330
telemt_user_octets_from_client{user="hello"} 14276112456 (13.30 GB)
telemt_user_octets_to_client{user="hello"} 42781210968 (39.84 GB)
telemt_user_unique_ips_current{user="hello"} 114
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 61316.5 (17h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 412678
telemt_connections_bad_total 6844
telemt_handshake_timeouts_total 12142
telemt_upstream_connect_attempt_total 14032
telemt_upstream_connect_success_total 13899
telemt_upstream_connect_fail_total 133
telemt_upstream_connect_attempts_per_request{bucket="1"} 14032
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6509
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7301
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 81
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 133
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 12901
telemt_me_reconnect_success_total 10748
telemt_me_reader_eof_total 11437
telemt_me_idle_close_by_peer_total 11437
telemt_me_route_drop_no_conn_total 116242
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 343597
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1022
telemt_desync_full_logged_total 370
telemt_desync_suppressed_total 652
telemt_desync_frames_bucket_total{bucket="1_2"} 241
telemt_desync_frames_bucket_total{bucket="3_10"} 443
telemt_desync_frames_bucket_total{bucket="gt_10"} 338
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 10988
telemt_me_refill_failed_total 63
telemt_me_writer_restored_same_endpoint_total 10739
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 240
telemt_user_connections_total{user="hello"} 343530
telemt_user_connections_current{user="hello"} 747
telemt_user_octets_from_client{user="hello"} 4466157410 (4.16 GB)
telemt_user_octets_to_client{user="hello"} 124488821269 (115.94 GB)
telemt_user_msgs_from_client{user="hello"} 65
telemt_user_msgs_to_client{user="hello"} 189
telemt_user_unique_ips_current{user="hello"} 209
telemt_user_unique_ips_recent_window{user="hello"} 88
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 61289.3 (17h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 215809
telemt_connections_bad_total 52138
telemt_handshake_timeouts_total 3056
telemt_upstream_connect_attempt_total 17985
telemt_upstream_connect_success_total 17749
telemt_upstream_connect_fail_total 236
telemt_upstream_connect_attempts_per_request{bucket="1"} 17985
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7963
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9566
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 220
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 236
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 28210
telemt_me_reconnect_success_total 14555
telemt_me_reader_eof_total 15588
telemt_me_idle_close_by_peer_total 15588
telemt_me_route_drop_no_conn_total 56813
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 153431
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 902
telemt_desync_full_logged_total 177
telemt_desync_suppressed_total 725
telemt_desync_frames_bucket_total{bucket="1_2"} 474
telemt_desync_frames_bucket_total{bucket="3_10"} 327
telemt_desync_frames_bucket_total{bucket="gt_10"} 101
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 15161
telemt_me_refill_failed_total 424
telemt_me_writer_restored_same_endpoint_total 14547
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 606
telemt_user_connections_total{user="hello"} 153446
telemt_user_connections_current{user="hello"} 250
telemt_user_octets_from_client{user="hello"} 2122600591 (1.98 GB)
telemt_user_octets_to_client{user="hello"} 64496497070 (60.07 GB)
telemt_user_msgs_from_client{user="hello"} 265
telemt_user_msgs_to_client{user="hello"} 707
telemt_user_unique_ips_current{user="hello"} 89
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 61449.7 (17h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 508591
telemt_connections_bad_total 51856
telemt_handshake_timeouts_total 4750
telemt_upstream_connect_attempt_total 12443
telemt_upstream_connect_success_total 12376
telemt_upstream_connect_fail_total 67
telemt_upstream_connect_attempts_per_request{bucket="1"} 12443
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6114
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6242
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 67
telemt_me_keepalive_timeout_total 31
telemt_me_reconnect_attempts_total 13192
telemt_me_reconnect_success_total 9299
telemt_me_reader_eof_total 10027
telemt_me_idle_close_by_peer_total 10027
telemt_me_route_drop_no_conn_total 338352
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 502210
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 751
telemt_desync_full_logged_total 281
telemt_desync_suppressed_total 470
telemt_desync_frames_bucket_total{bucket="1_2"} 199
telemt_desync_frames_bucket_total{bucket="3_10"} 292
telemt_desync_frames_bucket_total{bucket="gt_10"} 260
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 9565
telemt_me_refill_failed_total 120
telemt_me_writer_restored_same_endpoint_total 9285
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 266
telemt_user_connections_total{user="hello"} 423898
telemt_user_connections_current{user="hello"} 852
telemt_user_octets_from_client{user="hello"} 6250839140 (5.82 GB)
telemt_user_octets_to_client{user="hello"} 213672349444 (199.00 GB)
telemt_user_unique_ips_current{user="hello"} 289
telemt_user_unique_ips_recent_window{user="hello"} 105
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 9216.5 (2h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6886
telemt_connections_bad_total 42
telemt_handshake_timeouts_total 34
telemt_upstream_connect_attempt_total 5240
telemt_upstream_connect_success_total 5192
telemt_upstream_connect_fail_total 48
telemt_upstream_connect_attempts_per_request{bucket="1"} 5240
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2786
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2406
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 48
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 7787
telemt_me_reconnect_success_total 4549
telemt_me_reader_eof_total 4757
telemt_me_idle_close_by_peer_total 4757
telemt_me_seq_mismatch_total 5
telemt_me_route_drop_no_conn_total 2581
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6565
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 4699
telemt_me_refill_failed_total 100
telemt_me_writer_restored_same_endpoint_total 4540
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 150
telemt_user_connections_total{user="hello"} 6671
telemt_user_connections_current{user="hello"} 116
telemt_user_octets_from_client{user="hello"} 152547593 (145.48 MB)
telemt_user_octets_to_client{user="hello"} 19256206722 (17.93 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 12
```