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

# Server Metrics 2026-03-17 13:07:20 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 66122.7 (18h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 644258
telemt_connections_bad_total 5146
telemt_handshake_timeouts_total 20080
telemt_upstream_connect_attempt_total 16437
telemt_upstream_connect_success_total 15985
telemt_upstream_connect_fail_total 452
telemt_upstream_connect_attempts_per_request{bucket="1"} 16437
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8348
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7487
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 452
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 119
telemt_me_reconnect_attempts_total 14195
telemt_me_reconnect_success_total 10383
telemt_me_reader_eof_total 11057
telemt_me_idle_close_by_peer_total 11056
telemt_me_route_drop_no_conn_total 212014
telemt_me_route_drop_channel_closed_total 66
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 582081
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4326
telemt_desync_full_logged_total 1177
telemt_desync_suppressed_total 3149
telemt_desync_frames_bucket_total{bucket="1_2"} 1246
telemt_desync_frames_bucket_total{bucket="3_10"} 1786
telemt_desync_frames_bucket_total{bucket="gt_10"} 1294
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 10653
telemt_me_refill_failed_total 114
telemt_me_writer_restored_same_endpoint_total 10361
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 270
telemt_user_connections_total{user="hello"} 583973
telemt_user_connections_current{user="hello"} 1128
telemt_user_octets_from_client{user="hello"} 8275035887 (7.71 GB)
telemt_user_octets_to_client{user="hello"} 206959032507 (192.75 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 339
telemt_user_unique_ips_recent_window{user="hello"} 175
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 66376.4 (18h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 383575
telemt_connections_bad_total 22889
telemt_handshake_timeouts_total 20250
telemt_upstream_connect_attempt_total 16756
telemt_upstream_connect_success_total 16487
telemt_upstream_connect_fail_total 269
telemt_upstream_connect_attempts_per_request{bucket="1"} 16756
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7079
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9066
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 342
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 269
telemt_me_keepalive_timeout_total 244
telemt_me_reconnect_attempts_total 26241
telemt_me_reconnect_success_total 13165
telemt_me_reader_eof_total 14158
telemt_me_idle_close_by_peer_total 14158
telemt_me_route_drop_no_conn_total 153288
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 320273
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1228
telemt_desync_full_logged_total 405
telemt_desync_suppressed_total 823
telemt_desync_frames_bucket_total{bucket="1_2"} 277
telemt_desync_frames_bucket_total{bucket="3_10"} 548
telemt_desync_frames_bucket_total{bucket="gt_10"} 403
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 13734
telemt_me_refill_failed_total 405
telemt_me_writer_restored_same_endpoint_total 13149
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 569
telemt_user_connections_total{user="hello"} 320248
telemt_user_connections_current{user="hello"} 660
telemt_user_octets_from_client{user="hello"} 3559967068 (3.32 GB)
telemt_user_octets_to_client{user="hello"} 113481842260 (105.69 GB)
telemt_user_unique_ips_current{user="hello"} 183
telemt_user_unique_ips_recent_window{user="hello"} 105
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 66150.3 (18h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 211606
telemt_connections_bad_total 7748
telemt_handshake_timeouts_total 16562
telemt_upstream_connect_attempt_total 17372
telemt_upstream_connect_success_total 17283
telemt_upstream_connect_fail_total 89
telemt_upstream_connect_attempts_per_request{bucket="1"} 17372
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7689
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9519
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 70
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 89
telemt_me_keepalive_timeout_total 28
telemt_me_reconnect_attempts_total 15819
telemt_me_reconnect_success_total 13939
telemt_me_reader_eof_total 14863
telemt_me_idle_close_by_peer_total 14863
telemt_me_route_drop_no_conn_total 72438
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 176064
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 692
telemt_desync_full_logged_total 185
telemt_desync_suppressed_total 507
telemt_desync_frames_bucket_total{bucket="1_2"} 263
telemt_desync_frames_bucket_total{bucket="3_10"} 295
telemt_desync_frames_bucket_total{bucket="gt_10"} 134
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 14194
telemt_me_refill_failed_total 56
telemt_me_writer_restored_same_endpoint_total 13928
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 255
telemt_user_connections_total{user="hello"} 175953
telemt_user_connections_current{user="hello"} 356
telemt_user_octets_from_client{user="hello"} 15214105268 (14.17 GB)
telemt_user_octets_to_client{user="hello"} 49685319008 (46.27 GB)
telemt_user_unique_ips_current{user="hello"} 125
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 66209.6 (18h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 483999
telemt_connections_bad_total 7880
telemt_handshake_timeouts_total 12561
telemt_upstream_connect_attempt_total 15960
telemt_upstream_connect_success_total 15816
telemt_upstream_connect_fail_total 144
telemt_upstream_connect_attempts_per_request{bucket="1"} 15960
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7861
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7841
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 105
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 144
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 15422
telemt_me_reconnect_success_total 11462
telemt_me_reader_eof_total 12245
telemt_me_idle_close_by_peer_total 12245
telemt_me_route_drop_no_conn_total 137746
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 408281
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1447
telemt_desync_full_logged_total 505
telemt_desync_suppressed_total 942
telemt_desync_frames_bucket_total{bucket="1_2"} 353
telemt_desync_frames_bucket_total{bucket="3_10"} 652
telemt_desync_frames_bucket_total{bucket="gt_10"} 442
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 11789
telemt_me_refill_failed_total 119
telemt_me_writer_restored_same_endpoint_total 11453
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 327
telemt_user_connections_total{user="hello"} 409154
telemt_user_connections_current{user="hello"} 804
telemt_user_octets_from_client{user="hello"} 5245057766 (4.88 GB)
telemt_user_octets_to_client{user="hello"} 141306245615 (131.60 GB)
telemt_user_msgs_from_client{user="hello"} 4070
telemt_user_msgs_to_client{user="hello"} 5224
telemt_user_unique_ips_current{user="hello"} 202
telemt_user_unique_ips_recent_window{user="hello"} 125
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 66181.5 (18h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 242014
telemt_connections_bad_total 53651
telemt_handshake_timeouts_total 3204
telemt_upstream_connect_attempt_total 19240
telemt_upstream_connect_success_total 18993
telemt_upstream_connect_fail_total 247
telemt_upstream_connect_attempts_per_request{bucket="1"} 19240
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8478
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10271
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 244
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 247
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 31423
telemt_me_reconnect_success_total 15551
telemt_me_reader_eof_total 16684
telemt_me_idle_close_by_peer_total 16684
telemt_me_route_drop_no_conn_total 64357
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 176463
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1053
telemt_desync_full_logged_total 216
telemt_desync_suppressed_total 837
telemt_desync_frames_bucket_total{bucket="1_2"} 526
telemt_desync_frames_bucket_total{bucket="3_10"} 399
telemt_desync_frames_bucket_total{bucket="gt_10"} 128
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 16252
telemt_me_refill_failed_total 493
telemt_me_writer_restored_same_endpoint_total 15543
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 701
telemt_user_connections_total{user="hello"} 176467
telemt_user_connections_current{user="hello"} 287
telemt_user_octets_from_client{user="hello"} 2319831935 (2.16 GB)
telemt_user_octets_to_client{user="hello"} 69064507974 (64.32 GB)
telemt_user_msgs_from_client{user="hello"} 265
telemt_user_msgs_to_client{user="hello"} 707
telemt_user_unique_ips_current{user="hello"} 91
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 66342.8 (18h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 577166
telemt_connections_bad_total 52362
telemt_handshake_timeouts_total 5571
telemt_upstream_connect_attempt_total 13407
telemt_upstream_connect_success_total 13336
telemt_upstream_connect_fail_total 71
telemt_upstream_connect_attempts_per_request{bucket="1"} 13407
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6615
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6701
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 71
telemt_me_keepalive_timeout_total 37
telemt_me_reconnect_attempts_total 13927
telemt_me_reconnect_success_total 10024
telemt_me_reader_eof_total 10783
telemt_me_idle_close_by_peer_total 10783
telemt_me_route_drop_no_conn_total 378596
telemt_me_route_drop_channel_closed_total 29
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 573595
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 835
telemt_desync_full_logged_total 307
telemt_desync_suppressed_total 528
telemt_desync_frames_bucket_total{bucket="1_2"} 210
telemt_desync_frames_bucket_total{bucket="3_10"} 320
telemt_desync_frames_bucket_total{bucket="gt_10"} 305
telemt_pool_swap_total 60
telemt_me_writer_removed_unexpected_total 10299
telemt_me_refill_failed_total 120
telemt_me_writer_restored_same_endpoint_total 10010
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 275
telemt_user_connections_total{user="hello"} 488861
telemt_user_connections_current{user="hello"} 963
telemt_user_octets_from_client{user="hello"} 7197796568 (6.70 GB)
telemt_user_octets_to_client{user="hello"} 233343682988 (217.32 GB)
telemt_user_unique_ips_current{user="hello"} 303
telemt_user_unique_ips_recent_window{user="hello"} 152
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 14109.7 (3h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10950
telemt_connections_bad_total 58
telemt_handshake_timeouts_total 44
telemt_upstream_connect_attempt_total 7881
telemt_upstream_connect_success_total 7815
telemt_upstream_connect_fail_total 66
telemt_upstream_connect_attempts_per_request{bucket="1"} 7881
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4133
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3677
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 66
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 11090
telemt_me_reconnect_success_total 6942
telemt_me_reader_eof_total 7264
telemt_me_idle_close_by_peer_total 7264
telemt_me_seq_mismatch_total 8
telemt_me_route_drop_no_conn_total 3934
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10557
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 10
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 7142
telemt_me_refill_failed_total 128
telemt_me_writer_restored_same_endpoint_total 6930
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 200
telemt_user_connections_total{user="hello"} 10660
telemt_user_connections_current{user="hello"} 76
telemt_user_octets_from_client{user="hello"} 298929069 (285.08 MB)
telemt_user_octets_to_client{user="hello"} 21132183126 (19.68 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 21
telemt_user_unique_ips_recent_window{user="hello"} 11
```