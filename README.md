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

# Server Metrics 2026-03-17 10:28:58 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 56616.5 (15h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 471335
telemt_connections_bad_total 3887
telemt_handshake_timeouts_total 13051
telemt_upstream_connect_attempt_total 14201
telemt_upstream_connect_success_total 13766
telemt_upstream_connect_fail_total 435
telemt_upstream_connect_attempts_per_request{bucket="1"} 14201
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7329
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6287
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 435
telemt_me_keepalive_timeout_total 104
telemt_me_reconnect_attempts_total 10193
telemt_me_reconnect_success_total 8663
telemt_me_reader_eof_total 9206
telemt_me_idle_close_by_peer_total 9205
telemt_me_route_drop_no_conn_total 148816
telemt_me_route_drop_channel_closed_total 40
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 426956
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3435
telemt_desync_full_logged_total 911
telemt_desync_suppressed_total 2524
telemt_desync_frames_bucket_total{bucket="1_2"} 932
telemt_desync_frames_bucket_total{bucket="3_10"} 1471
telemt_desync_frames_bucket_total{bucket="gt_10"} 1032
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 8840
telemt_me_refill_failed_total 43
telemt_me_writer_restored_same_endpoint_total 8641
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 177
telemt_user_connections_total{user="hello"} 428925
telemt_user_connections_current{user="hello"} 975
telemt_user_octets_from_client{user="hello"} 6203933063 (5.78 GB)
telemt_user_octets_to_client{user="hello"} 165909207167 (154.51 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 335
telemt_user_unique_ips_recent_window{user="hello"} 135
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 56868.0 (15h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 256745
telemt_connections_bad_total 4702
telemt_handshake_timeouts_total 15247
telemt_upstream_connect_attempt_total 14636
telemt_upstream_connect_success_total 14430
telemt_upstream_connect_fail_total 206
telemt_upstream_connect_attempts_per_request{bucket="1"} 14636
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6224
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8037
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 169
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 206
telemt_me_keepalive_timeout_total 6
telemt_me_reconnect_attempts_total 20304
telemt_me_reconnect_success_total 11591
telemt_me_reader_eof_total 12438
telemt_me_idle_close_by_peer_total 12438
telemt_me_route_drop_no_conn_total 93418
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 224383
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 595
telemt_desync_full_logged_total 228
telemt_desync_suppressed_total 367
telemt_desync_frames_bucket_total{bucket="1_2"} 175
telemt_desync_frames_bucket_total{bucket="3_10"} 258
telemt_desync_frames_bucket_total{bucket="gt_10"} 162
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 11987
telemt_me_refill_failed_total 271
telemt_me_writer_restored_same_endpoint_total 11575
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 396
telemt_user_connections_total{user="hello"} 224382
telemt_user_connections_current{user="hello"} 538
telemt_user_octets_from_client{user="hello"} 2736231596 (2.55 GB)
telemt_user_octets_to_client{user="hello"} 84066112240 (78.29 GB)
telemt_user_unique_ips_current{user="hello"} 162
telemt_user_unique_ips_recent_window{user="hello"} 59
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 56643.9 (15h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 156592
telemt_connections_bad_total 7605
telemt_handshake_timeouts_total 11756
telemt_upstream_connect_attempt_total 15126
telemt_upstream_connect_success_total 15047
telemt_upstream_connect_fail_total 79
telemt_upstream_connect_attempts_per_request{bucket="1"} 15126
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6653
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8327
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 79
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 14073
telemt_me_reconnect_success_total 12206
telemt_me_reader_eof_total 13039
telemt_me_idle_close_by_peer_total 13039
telemt_me_route_drop_no_conn_total 46921
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 127524
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 436
telemt_desync_full_logged_total 114
telemt_desync_suppressed_total 322
telemt_desync_frames_bucket_total{bucket="1_2"} 176
telemt_desync_frames_bucket_total{bucket="3_10"} 185
telemt_desync_frames_bucket_total{bucket="gt_10"} 75
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 12429
telemt_me_refill_failed_total 56
telemt_me_writer_restored_same_endpoint_total 12195
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 223
telemt_user_connections_total{user="hello"} 127436
telemt_user_connections_current{user="hello"} 361
telemt_user_octets_from_client{user="hello"} 9704758044 (9.04 GB)
telemt_user_octets_to_client{user="hello"} 38700281720 (36.04 GB)
telemt_user_unique_ips_current{user="hello"} 112
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 56703.0 (15h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 350727
telemt_connections_bad_total 6217
telemt_handshake_timeouts_total 11570
telemt_upstream_connect_attempt_total 12885
telemt_upstream_connect_success_total 12766
telemt_upstream_connect_fail_total 119
telemt_upstream_connect_attempts_per_request{bucket="1"} 12885
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6045
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6638
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 119
telemt_me_keepalive_timeout_total 6
telemt_me_reconnect_attempts_total 10983
telemt_me_reconnect_success_total 9889
telemt_me_reader_eof_total 10513
telemt_me_idle_close_by_peer_total 10513
telemt_me_route_drop_no_conn_total 98131
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 286907
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 695
telemt_desync_full_logged_total 268
telemt_desync_suppressed_total 427
telemt_desync_frames_bucket_total{bucket="1_2"} 164
telemt_desync_frames_bucket_total{bucket="3_10"} 311
telemt_desync_frames_bucket_total{bucket="gt_10"} 220
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 10077
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 9881
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 188
telemt_user_connections_total{user="hello"} 286862
telemt_user_connections_current{user="hello"} 737
telemt_user_octets_from_client{user="hello"} 3613298222 (3.37 GB)
telemt_user_octets_to_client{user="hello"} 110503963465 (102.91 GB)
telemt_user_msgs_from_client{user="hello"} 65
telemt_user_msgs_to_client{user="hello"} 189
telemt_user_unique_ips_current{user="hello"} 209
telemt_user_unique_ips_recent_window{user="hello"} 102
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 56674.8 (15h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 191364
telemt_connections_bad_total 51228
telemt_handshake_timeouts_total 2885
telemt_upstream_connect_attempt_total 17250
telemt_upstream_connect_success_total 17027
telemt_upstream_connect_fail_total 223
telemt_upstream_connect_attempts_per_request{bucket="1"} 17250
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7590
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9228
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 209
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 223
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 22237
telemt_me_reconnect_success_total 14089
telemt_me_reader_eof_total 14943
telemt_me_idle_close_by_peer_total 14943
telemt_me_route_drop_no_conn_total 49697
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 131450
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 549
telemt_desync_full_logged_total 124
telemt_desync_suppressed_total 425
telemt_desync_frames_bucket_total{bucket="1_2"} 272
telemt_desync_frames_bucket_total{bucket="3_10"} 198
telemt_desync_frames_bucket_total{bucket="gt_10"} 79
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 14521
telemt_me_refill_failed_total 252
telemt_me_writer_restored_same_endpoint_total 14081
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 432
telemt_user_connections_total{user="hello"} 131478
telemt_user_connections_current{user="hello"} 285
telemt_user_octets_from_client{user="hello"} 1929623043 (1.80 GB)
telemt_user_octets_to_client{user="hello"} 58818072386 (54.78 GB)
telemt_user_msgs_from_client{user="hello"} 265
telemt_user_msgs_to_client{user="hello"} 707
telemt_user_unique_ips_current{user="hello"} 107
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 56836.5 (15h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 445284
telemt_connections_bad_total 50311
telemt_handshake_timeouts_total 4436
telemt_upstream_connect_attempt_total 11507
telemt_upstream_connect_success_total 11443
telemt_upstream_connect_fail_total 64
telemt_upstream_connect_attempts_per_request{bucket="1"} 11507
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5627
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5796
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 64
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 12480
telemt_me_reconnect_success_total 8596
telemt_me_reader_eof_total 9281
telemt_me_idle_close_by_peer_total 9281
telemt_me_route_drop_no_conn_total 287405
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 445275
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 669
telemt_desync_full_logged_total 256
telemt_desync_suppressed_total 413
telemt_desync_frames_bucket_total{bucket="1_2"} 181
telemt_desync_frames_bucket_total{bucket="3_10"} 256
telemt_desync_frames_bucket_total{bucket="gt_10"} 232
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 8848
telemt_me_refill_failed_total 120
telemt_me_writer_restored_same_endpoint_total 8582
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 252
telemt_user_connections_total{user="hello"} 367145
telemt_user_connections_current{user="hello"} 917
telemt_user_octets_from_client{user="hello"} 5283315108 (4.92 GB)
telemt_user_octets_to_client{user="hello"} 196119885680 (182.65 GB)
telemt_user_unique_ips_current{user="hello"} 311
telemt_user_unique_ips_recent_window{user="hello"} 103
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 4603.0 (1h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3932
telemt_connections_bad_total 26
telemt_handshake_timeouts_total 32
telemt_upstream_connect_attempt_total 2031
telemt_upstream_connect_success_total 2003
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 2030
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1108
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 895
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_reconnect_attempts_total 1626
telemt_me_reconnect_success_total 1596
telemt_me_reader_eof_total 1643
telemt_me_idle_close_by_peer_total 1643
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 1470
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3647
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 1616
telemt_me_writer_restored_same_endpoint_total 1590
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 3753
telemt_user_connections_current{user="hello"} 75
telemt_user_octets_from_client{user="hello"} 68186589 (65.03 MB)
telemt_user_octets_to_client{user="hello"} 16852596898 (15.70 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 18
telemt_user_unique_ips_recent_window{user="hello"} 10
```