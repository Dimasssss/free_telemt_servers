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

# Server Metrics 2026-03-12 15:01:13 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 26870.6 (7h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 142809
telemt_connections_bad_total 1544
telemt_handshake_timeouts_total 4563
telemt_upstream_connect_attempt_total 6528
telemt_upstream_connect_success_total 6503
telemt_upstream_connect_fail_total 25
telemt_upstream_connect_attempts_per_request{bucket="1"} 6528
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2907
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3590
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 25
telemt_me_keepalive_timeout_total 275
telemt_me_reconnect_attempts_total 5161
telemt_me_reconnect_success_total 5126
telemt_me_reader_eof_total 5383
telemt_me_idle_close_by_peer_total 5382
telemt_me_route_drop_no_conn_total 40901
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 124286
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 573
telemt_desync_full_logged_total 215
telemt_desync_suppressed_total 358
telemt_desync_frames_bucket_total{bucket="1_2"} 105
telemt_desync_frames_bucket_total{bucket="3_10"} 224
telemt_desync_frames_bucket_total{bucket="gt_10"} 244
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 5172
telemt_me_writer_restored_same_endpoint_total 5110
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 124249
telemt_user_connections_current{user="hello"} 352
telemt_user_octets_from_client{user="hello"} 2072733456 (1.93 GB)
telemt_user_octets_to_client{user="hello"} 46246161860 (43.07 GB)
telemt_user_unique_ips_current{user="hello"} 102
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 26763.9 (7h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 59717
telemt_connections_bad_total 446
telemt_handshake_timeouts_total 379
telemt_upstream_connect_attempt_total 8195
telemt_upstream_connect_success_total 8017
telemt_upstream_connect_fail_total 178
telemt_upstream_connect_attempts_per_request{bucket="1"} 8195
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3262
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4720
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 178
telemt_me_keepalive_timeout_total 177
telemt_me_reconnect_attempts_total 23585
telemt_me_reconnect_success_total 6662
telemt_me_reader_eof_total 7340
telemt_me_idle_close_by_peer_total 7340
telemt_me_route_drop_no_conn_total 26637
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 56983
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
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 7236
telemt_me_refill_failed_total 528
telemt_me_writer_restored_same_endpoint_total 6647
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 574
telemt_user_connections_total{user="hello"} 56974
telemt_user_connections_current{user="hello"} 145
telemt_user_octets_from_client{user="hello"} 634863160 (605.45 MB)
telemt_user_octets_to_client{user="hello"} 16169857644 (15.06 GB)
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 26727.1 (7h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 81590
telemt_connections_bad_total 1429
telemt_handshake_timeouts_total 1545
telemt_upstream_connect_attempt_total 7233
telemt_upstream_connect_success_total 7233
telemt_upstream_connect_attempts_per_request{bucket="1"} 7233
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3519
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3704
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 125
telemt_me_reconnect_attempts_total 5885
telemt_me_reconnect_success_total 5833
telemt_me_reader_eof_total 6164
telemt_me_idle_close_by_peer_total 6164
telemt_me_route_drop_no_conn_total 28935
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 75215
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
telemt_me_writer_removed_unexpected_total 5881
telemt_me_writer_restored_same_endpoint_total 5813
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 48
telemt_user_connections_total{user="hello"} 75186
telemt_user_connections_current{user="hello"} 229
telemt_user_octets_from_client{user="hello"} 2024226824 (1.89 GB)
telemt_user_octets_to_client{user="hello"} 41389813352 (38.55 GB)
telemt_user_unique_ips_current{user="hello"} 83
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 26702.7 (7h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 107595
telemt_connections_bad_total 7111
telemt_handshake_timeouts_total 771
telemt_upstream_connect_attempt_total 6710
telemt_upstream_connect_success_total 6530
telemt_upstream_connect_fail_total 180
telemt_upstream_connect_attempts_per_request{bucket="1"} 6710
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2957
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3550
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 180
telemt_me_keepalive_timeout_total 257
telemt_me_reconnect_attempts_total 22300
telemt_me_reconnect_success_total 5160
telemt_me_reader_eof_total 5830
telemt_me_idle_close_by_peer_total 5830
telemt_me_route_drop_no_conn_total 38322
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 93903
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 322
telemt_desync_full_logged_total 104
telemt_desync_suppressed_total 218
telemt_desync_frames_bucket_total{bucket="1_2"} 106
telemt_desync_frames_bucket_total{bucket="3_10"} 112
telemt_desync_frames_bucket_total{bucket="gt_10"} 104
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 5755
telemt_me_refill_failed_total 534
telemt_me_writer_restored_same_endpoint_total 5152
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 121
telemt_me_writer_removed_unexpected_minus_restored_total 595
telemt_user_connections_total{user="hello"} 93786
telemt_user_connections_current{user="hello"} 292
telemt_user_octets_from_client{user="hello"} 1774688120 (1.65 GB)
telemt_user_octets_to_client{user="hello"} 38424253200 (35.79 GB)
telemt_user_unique_ips_current{user="hello"} 85
telemt_user_unique_ips_recent_window{user="hello"} 50
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 26672.2 (7h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 62197
telemt_connections_bad_total 5173
telemt_handshake_timeouts_total 1054
telemt_upstream_connect_attempt_total 26442
telemt_upstream_connect_success_total 26113
telemt_upstream_connect_fail_total 329
telemt_upstream_connect_attempts_per_request{bucket="1"} 26442
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21440
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4641
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 329
telemt_me_keepalive_timeout_total 105
telemt_me_reconnect_attempts_total 35583
telemt_me_reconnect_success_total 3684
telemt_me_reader_eof_total 4677
telemt_me_idle_close_by_peer_total 4677
telemt_me_seq_mismatch_total 8
telemt_me_route_drop_no_conn_total 12517
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 33443
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
telemt_me_writer_removed_unexpected_total 4702
telemt_me_refill_failed_total 998
telemt_me_writer_restored_same_endpoint_total 3667
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 1018
telemt_user_connections_total{user="hello"} 54503
telemt_user_connections_current{user="hello"} 166
telemt_user_octets_from_client{user="hello"} 458911886 (437.65 MB)
telemt_user_octets_to_client{user="hello"} 16076344069 (14.97 GB)
telemt_user_msgs_from_client{user="hello"} 322550
telemt_user_msgs_to_client{user="hello"} 1341546
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 26660.0 (7h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 164884
telemt_connections_bad_total 895
telemt_handshake_timeouts_total 1255
telemt_upstream_connect_attempt_total 5484
telemt_upstream_connect_success_total 5456
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 5484
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2597
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2856
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 4130
telemt_me_reconnect_success_total 4099
telemt_me_reader_eof_total 4311
telemt_me_idle_close_by_peer_total 4311
telemt_me_route_drop_no_conn_total 64042
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 157714
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 242
telemt_desync_full_logged_total 94
telemt_desync_suppressed_total 148
telemt_desync_frames_bucket_total{bucket="1_2"} 63
telemt_desync_frames_bucket_total{bucket="3_10"} 88
telemt_desync_frames_bucket_total{bucket="gt_10"} 91
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 4146
telemt_me_writer_restored_same_endpoint_total 4092
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 47
telemt_user_connections_total{user="hello"} 157678
telemt_user_connections_current{user="hello"} 488
telemt_user_octets_from_client{user="hello"} 3161898616 (2.94 GB)
telemt_user_octets_to_client{user="hello"} 72732922256 (67.74 GB)
telemt_user_unique_ips_current{user="hello"} 150
telemt_user_unique_ips_recent_window{user="hello"} 81
```