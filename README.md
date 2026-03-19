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

# Server Metrics 2026-03-19 04:26:18 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 23870.9 (6h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 328891
telemt_connections_bad_total 35276
telemt_connections_current 834
telemt_connections_me_current 834
telemt_handshake_timeouts_total 19518
telemt_upstream_connect_attempt_total 4688
telemt_upstream_connect_success_total 4615
telemt_upstream_connect_fail_total 73
telemt_upstream_connect_attempts_per_request{bucket="1"} 4688
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2243
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2369
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 73
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 3430
telemt_me_reconnect_success_total 3414
telemt_me_reader_eof_total 3593
telemt_me_idle_close_by_peer_total 3593
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 83274
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 238904
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1710
telemt_desync_full_logged_total 462
telemt_desync_suppressed_total 1248
telemt_desync_frames_bucket_total{bucket="1_2"} 636
telemt_desync_frames_bucket_total{bucket="3_10"} 700
telemt_desync_frames_bucket_total{bucket="gt_10"} 374
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 3441
telemt_me_writer_restored_same_endpoint_total 3397
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 236152
telemt_user_connections_current{user="hello"} 834
telemt_user_octets_from_client{user="hello"} 2659472356 (2.48 GB)
telemt_user_octets_to_client{user="hello"} 70795536988 (65.93 GB)
telemt_user_unique_ips_current{user="hello"} 339
telemt_user_unique_ips_recent_window{user="hello"} 111
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 23874.9 (6h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 600868
telemt_connections_bad_total 39020
telemt_connections_current 2425
telemt_connections_me_current 2425
telemt_handshake_timeouts_total 16815
telemt_upstream_connect_attempt_total 4518
telemt_upstream_connect_success_total 4436
telemt_upstream_connect_fail_total 82
telemt_upstream_connect_attempts_per_request{bucket="1"} 4518
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2123
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2303
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 82
telemt_me_reconnect_attempts_total 3243
telemt_me_reconnect_success_total 3226
telemt_me_reader_eof_total 3400
telemt_me_idle_close_by_peer_total 3400
telemt_me_seq_mismatch_total 8
telemt_me_route_drop_no_conn_total 179832
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 495245
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 30
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1902
telemt_desync_full_logged_total 644
telemt_desync_suppressed_total 1258
telemt_desync_frames_bucket_total{bucket="1_2"} 382
telemt_desync_frames_bucket_total{bucket="3_10"} 692
telemt_desync_frames_bucket_total{bucket="gt_10"} 828
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 3281
telemt_me_writer_restored_same_endpoint_total 3208
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 495193
telemt_user_connections_current{user="hello"} 2425
telemt_user_octets_from_client{user="hello"} 14370788880 (13.38 GB)
telemt_user_octets_to_client{user="hello"} 216255885044 (201.40 GB)
telemt_user_unique_ips_current{user="hello"} 919
telemt_user_unique_ips_recent_window{user="hello"} 307
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 23872.1 (6h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 506178
telemt_connections_bad_total 103947
telemt_connections_current 1933
telemt_connections_me_current 1933
telemt_handshake_timeouts_total 15601
telemt_upstream_connect_attempt_total 4429
telemt_upstream_connect_success_total 4429
telemt_upstream_connect_attempts_per_request{bucket="1"} 4429
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2231
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2191
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 3233
telemt_me_reconnect_success_total 3223
telemt_me_reader_eof_total 3410
telemt_me_idle_close_by_peer_total 3410
telemt_me_route_drop_no_conn_total 149106
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 361970
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1714
telemt_desync_full_logged_total 636
telemt_desync_suppressed_total 1078
telemt_desync_frames_bucket_total{bucket="1_2"} 294
telemt_desync_frames_bucket_total{bucket="3_10"} 704
telemt_desync_frames_bucket_total{bucket="gt_10"} 716
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 3274
telemt_me_writer_restored_same_endpoint_total 3207
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 361969
telemt_user_connections_current{user="hello"} 1933
telemt_user_octets_from_client{user="hello"} 7909044892 (7.37 GB)
telemt_user_octets_to_client{user="hello"} 224855279956 (209.41 GB)
telemt_user_unique_ips_current{user="hello"} 724
telemt_user_unique_ips_recent_window{user="hello"} 234
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 23925.4 (6h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 598855
telemt_connections_bad_total 72062
telemt_connections_current 1614
telemt_connections_me_current 1614
telemt_handshake_timeouts_total 11974
telemt_upstream_connect_attempt_total 4306
telemt_upstream_connect_success_total 4306
telemt_upstream_connect_attempts_per_request{bucket="1"} 4306
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2166
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2132
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 3115
telemt_me_reconnect_success_total 3104
telemt_me_reader_eof_total 3271
telemt_me_idle_close_by_peer_total 3270
telemt_me_route_drop_no_conn_total 149038
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 360796
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1041
telemt_desync_full_logged_total 386
telemt_desync_suppressed_total 655
telemt_desync_frames_bucket_total{bucket="1_2"} 202
telemt_desync_frames_bucket_total{bucket="3_10"} 452
telemt_desync_frames_bucket_total{bucket="gt_10"} 387
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 3138
telemt_me_writer_restored_same_endpoint_total 3080
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 272
telemt_me_writer_removed_unexpected_minus_restored_total 34
telemt_user_connections_total{user="hello"} 360552
telemt_user_connections_current{user="hello"} 1614
telemt_user_octets_from_client{user="hello"} 4330757704 (4.03 GB)
telemt_user_octets_to_client{user="hello"} 139328134116 (129.76 GB)
telemt_user_unique_ips_current{user="hello"} 610
telemt_user_unique_ips_recent_window{user="hello"} 199
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 23868.8 (6h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 673278
telemt_connections_bad_total 190325
telemt_connections_current 1936
telemt_connections_me_current 1936
telemt_handshake_timeouts_total 19257
telemt_upstream_connect_attempt_total 4435
telemt_upstream_connect_success_total 4407
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 4435
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2198
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2194
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_reconnect_attempts_total 3215
telemt_me_reconnect_success_total 3197
telemt_me_reader_eof_total 3376
telemt_me_idle_close_by_peer_total 3376
telemt_me_route_drop_no_conn_total 163741
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 392044
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1720
telemt_desync_full_logged_total 667
telemt_desync_suppressed_total 1053
telemt_desync_frames_bucket_total{bucket="1_2"} 412
telemt_desync_frames_bucket_total{bucket="3_10"} 716
telemt_desync_frames_bucket_total{bucket="gt_10"} 592
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 3226
telemt_me_writer_restored_same_endpoint_total 3173
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 391961
telemt_user_connections_current{user="hello"} 1936
telemt_user_octets_from_client{user="hello"} 11468222100 (10.68 GB)
telemt_user_octets_to_client{user="hello"} 229462814608 (213.70 GB)
telemt_user_unique_ips_current{user="hello"} 774
telemt_user_unique_ips_recent_window{user="hello"} 264
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 23880.4 (6h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 117938
telemt_connections_bad_total 10271
telemt_connections_current 534
telemt_connections_me_current 534
telemt_handshake_timeouts_total 538
telemt_upstream_connect_attempt_total 6625
telemt_upstream_connect_success_total 6443
telemt_upstream_connect_fail_total 182
telemt_upstream_connect_attempts_per_request{bucket="1"} 6625
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3034
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3409
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 182
telemt_me_reconnect_attempts_total 7081
telemt_me_reconnect_success_total 5241
telemt_me_reader_eof_total 5497
telemt_me_idle_close_by_peer_total 5497
telemt_me_route_drop_no_conn_total 48797
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 103133
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 86
telemt_desync_full_logged_total 31
telemt_desync_suppressed_total 55
telemt_desync_frames_bucket_total{bucket="1_2"} 36
telemt_desync_frames_bucket_total{bucket="3_10"} 30
telemt_desync_frames_bucket_total{bucket="gt_10"} 20
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 5311
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 5211
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 70
telemt_user_connections_total{user="hello"} 103123
telemt_user_connections_current{user="hello"} 534
telemt_user_octets_from_client{user="hello"} 1917902664 (1.79 GB)
telemt_user_octets_to_client{user="hello"} 66360713104 (61.80 GB)
telemt_user_unique_ips_current{user="hello"} 198
telemt_user_unique_ips_recent_window{user="hello"} 56
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 23871.3 (6h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 380506
telemt_connections_bad_total 39981
telemt_connections_current 1658
telemt_connections_me_current 1658
telemt_handshake_timeouts_total 19909
telemt_upstream_connect_attempt_total 4994
telemt_upstream_connect_success_total 4994
telemt_upstream_connect_attempts_per_request{bucket="1"} 4994
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2644
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2347
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 3802
telemt_me_reconnect_success_total 3792
telemt_me_reader_eof_total 4000
telemt_me_idle_close_by_peer_total 4000
telemt_me_route_drop_no_conn_total 108175
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 308745
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1579
telemt_desync_full_logged_total 600
telemt_desync_suppressed_total 979
telemt_desync_frames_bucket_total{bucket="1_2"} 320
telemt_desync_frames_bucket_total{bucket="3_10"} 615
telemt_desync_frames_bucket_total{bucket="gt_10"} 644
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 3832
telemt_me_writer_restored_same_endpoint_total 3777
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 40
telemt_user_connections_total{user="hello"} 308762
telemt_user_connections_current{user="hello"} 1658
telemt_user_octets_from_client{user="hello"} 3666423548 (3.41 GB)
telemt_user_octets_to_client{user="hello"} 176144854388 (164.05 GB)
telemt_user_unique_ips_current{user="hello"} 611
telemt_user_unique_ips_recent_window{user="hello"} 200
```