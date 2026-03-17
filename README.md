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

# Server Metrics 2026-03-17 10:39:11 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 57229.2 (15h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 481644
telemt_connections_bad_total 3965
telemt_handshake_timeouts_total 13476
telemt_upstream_connect_attempt_total 14318
telemt_upstream_connect_success_total 13883
telemt_upstream_connect_fail_total 435
telemt_upstream_connect_attempts_per_request{bucket="1"} 14318
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7382
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6351
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 435
telemt_me_keepalive_timeout_total 104
telemt_me_reconnect_attempts_total 10266
telemt_me_reconnect_success_total 8735
telemt_me_reader_eof_total 9285
telemt_me_idle_close_by_peer_total 9284
telemt_me_route_drop_no_conn_total 152004
telemt_me_route_drop_channel_closed_total 42
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 436283
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3489
telemt_desync_full_logged_total 928
telemt_desync_suppressed_total 2561
telemt_desync_frames_bucket_total{bucket="1_2"} 947
telemt_desync_frames_bucket_total{bucket="3_10"} 1493
telemt_desync_frames_bucket_total{bucket="gt_10"} 1049
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 8915
telemt_me_refill_failed_total 43
telemt_me_writer_restored_same_endpoint_total 8713
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 180
telemt_user_connections_total{user="hello"} 438239
telemt_user_connections_current{user="hello"} 932
telemt_user_octets_from_client{user="hello"} 6292049247 (5.86 GB)
telemt_user_octets_to_client{user="hello"} 168354923367 (156.79 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 341
telemt_user_unique_ips_recent_window{user="hello"} 138
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 57480.8 (15h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 263398
telemt_connections_bad_total 5795
telemt_handshake_timeouts_total 15741
telemt_upstream_connect_attempt_total 14807
telemt_upstream_connect_success_total 14601
telemt_upstream_connect_fail_total 206
telemt_upstream_connect_attempts_per_request{bucket="1"} 14807
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6292
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8136
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 173
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 206
telemt_me_keepalive_timeout_total 6
telemt_me_reconnect_attempts_total 20475
telemt_me_reconnect_success_total 11761
telemt_me_reader_eof_total 12609
telemt_me_idle_close_by_peer_total 12609
telemt_me_route_drop_no_conn_total 95212
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 229285
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 612
telemt_desync_full_logged_total 232
telemt_desync_suppressed_total 380
telemt_desync_frames_bucket_total{bucket="1_2"} 181
telemt_desync_frames_bucket_total{bucket="3_10"} 266
telemt_desync_frames_bucket_total{bucket="gt_10"} 165
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 12158
telemt_me_refill_failed_total 271
telemt_me_writer_restored_same_endpoint_total 11745
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 397
telemt_user_connections_total{user="hello"} 229283
telemt_user_connections_current{user="hello"} 552
telemt_user_octets_from_client{user="hello"} 2772500924 (2.58 GB)
telemt_user_octets_to_client{user="hello"} 84913753096 (79.08 GB)
telemt_user_unique_ips_current{user="hello"} 176
telemt_user_unique_ips_recent_window{user="hello"} 72
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 57257.4 (15h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 159924
telemt_connections_bad_total 7611
telemt_handshake_timeouts_total 12169
telemt_upstream_connect_attempt_total 15262
telemt_upstream_connect_success_total 15182
telemt_upstream_connect_fail_total 80
telemt_upstream_connect_attempts_per_request{bucket="1"} 15262
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6701
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8413
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 80
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 14165
telemt_me_reconnect_success_total 12297
telemt_me_reader_eof_total 13147
telemt_me_idle_close_by_peer_total 13147
telemt_me_route_drop_no_conn_total 47794
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 130322
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 465
telemt_desync_full_logged_total 120
telemt_desync_suppressed_total 345
telemt_desync_frames_bucket_total{bucket="1_2"} 193
telemt_desync_frames_bucket_total{bucket="3_10"} 197
telemt_desync_frames_bucket_total{bucket="gt_10"} 75
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 12523
telemt_me_refill_failed_total 56
telemt_me_writer_restored_same_endpoint_total 12286
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 226
telemt_user_connections_total{user="hello"} 130234
telemt_user_connections_current{user="hello"} 302
telemt_user_octets_from_client{user="hello"} 10319443660 (9.61 GB)
telemt_user_octets_to_client{user="hello"} 39232931188 (36.54 GB)
telemt_user_unique_ips_current{user="hello"} 102
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 57315.9 (15h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 358433
telemt_connections_bad_total 6232
telemt_handshake_timeouts_total 11655
telemt_upstream_connect_attempt_total 13026
telemt_upstream_connect_success_total 12906
telemt_upstream_connect_fail_total 120
telemt_upstream_connect_attempts_per_request{bucket="1"} 13026
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6107
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6715
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 76
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 120
telemt_me_keepalive_timeout_total 6
telemt_me_reconnect_attempts_total 11079
telemt_me_reconnect_success_total 9983
telemt_me_reader_eof_total 10614
telemt_me_idle_close_by_peer_total 10614
telemt_me_route_drop_no_conn_total 100591
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 294156
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 739
telemt_desync_full_logged_total 282
telemt_desync_suppressed_total 457
telemt_desync_frames_bucket_total{bucket="1_2"} 174
telemt_desync_frames_bucket_total{bucket="3_10"} 324
telemt_desync_frames_bucket_total{bucket="gt_10"} 241
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 10173
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 9975
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 190
telemt_user_connections_total{user="hello"} 294109
telemt_user_connections_current{user="hello"} 738
telemt_user_octets_from_client{user="hello"} 3775052882 (3.52 GB)
telemt_user_octets_to_client{user="hello"} 112660266229 (104.92 GB)
telemt_user_msgs_from_client{user="hello"} 65
telemt_user_msgs_to_client{user="hello"} 189
telemt_user_unique_ips_current{user="hello"} 196
telemt_user_unique_ips_recent_window{user="hello"} 86
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 57287.9 (15h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 194712
telemt_connections_bad_total 51394
telemt_handshake_timeouts_total 2915
telemt_upstream_connect_attempt_total 17373
telemt_upstream_connect_success_total 17147
telemt_upstream_connect_fail_total 226
telemt_upstream_connect_attempts_per_request{bucket="1"} 17373
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7646
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9292
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 209
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 226
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 23689
telemt_me_reconnect_success_total 14165
telemt_me_reader_eof_total 15062
telemt_me_idle_close_by_peer_total 15062
telemt_me_route_drop_no_conn_total 50529
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 134363
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 610
telemt_desync_full_logged_total 132
telemt_desync_suppressed_total 478
telemt_desync_frames_bucket_total{bucket="1_2"} 305
telemt_desync_frames_bucket_total{bucket="3_10"} 220
telemt_desync_frames_bucket_total{bucket="gt_10"} 85
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 14640
telemt_me_refill_failed_total 295
telemt_me_writer_restored_same_endpoint_total 14157
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 475
telemt_user_connections_total{user="hello"} 134390
telemt_user_connections_current{user="hello"} 298
telemt_user_octets_from_client{user="hello"} 1947954407 (1.81 GB)
telemt_user_octets_to_client{user="hello"} 59929397030 (55.81 GB)
telemt_user_msgs_from_client{user="hello"} 265
telemt_user_msgs_to_client{user="hello"} 707
telemt_user_unique_ips_current{user="hello"} 103
telemt_user_unique_ips_recent_window{user="hello"} 52
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 57449.5 (15h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 453453
telemt_connections_bad_total 50938
telemt_handshake_timeouts_total 4471
telemt_upstream_connect_attempt_total 11585
telemt_upstream_connect_success_total 11521
telemt_upstream_connect_fail_total 64
telemt_upstream_connect_attempts_per_request{bucket="1"} 11585
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5665
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5836
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 64
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 12558
telemt_me_reconnect_success_total 8672
telemt_me_reader_eof_total 9365
telemt_me_idle_close_by_peer_total 9365
telemt_me_route_drop_no_conn_total 290523
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 452497
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 689
telemt_desync_full_logged_total 262
telemt_desync_suppressed_total 427
telemt_desync_frames_bucket_total{bucket="1_2"} 184
telemt_desync_frames_bucket_total{bucket="3_10"} 264
telemt_desync_frames_bucket_total{bucket="gt_10"} 241
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 8926
telemt_me_refill_failed_total 120
telemt_me_writer_restored_same_endpoint_total 8658
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 254
telemt_user_connections_total{user="hello"} 374365
telemt_user_connections_current{user="hello"} 936
telemt_user_octets_from_client{user="hello"} 5362067628 (4.99 GB)
telemt_user_octets_to_client{user="hello"} 197952701060 (184.36 GB)
telemt_user_unique_ips_current{user="hello"} 309
telemt_user_unique_ips_recent_window{user="hello"} 104
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 5216.1 (1h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4324
telemt_connections_bad_total 33
telemt_handshake_timeouts_total 32
telemt_upstream_connect_attempt_total 2259
telemt_upstream_connect_success_total 2230
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 2259
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1217
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1013
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_reconnect_attempts_total 1848
telemt_me_reconnect_success_total 1817
telemt_me_reader_eof_total 1900
telemt_me_idle_close_by_peer_total 1900
telemt_me_seq_mismatch_total 4
telemt_me_route_drop_no_conn_total 1723
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4030
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 1840
telemt_me_writer_restored_same_endpoint_total 1810
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 4137
telemt_user_connections_current{user="hello"} 97
telemt_user_octets_from_client{user="hello"} 78871657 (75.22 MB)
telemt_user_octets_to_client{user="hello"} 17721224538 (16.50 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 20
telemt_user_unique_ips_recent_window{user="hello"} 8
```