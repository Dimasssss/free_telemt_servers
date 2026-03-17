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

# Server Metrics 2026-03-17 14:13:49 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 70112.6 (19h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 730523
telemt_connections_bad_total 5706
telemt_handshake_timeouts_total 20834
telemt_upstream_connect_attempt_total 17092
telemt_upstream_connect_success_total 16637
telemt_upstream_connect_fail_total 455
telemt_upstream_connect_attempts_per_request{bucket="1"} 17092
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8711
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7776
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 455
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 121
telemt_me_reconnect_attempts_total 20033
telemt_me_reconnect_success_total 10844
telemt_me_reader_eof_total 11687
telemt_me_idle_close_by_peer_total 11686
telemt_me_route_drop_no_conn_total 287182
telemt_me_route_drop_channel_closed_total 72
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 663991
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4636
telemt_desync_full_logged_total 1306
telemt_desync_suppressed_total 3330
telemt_desync_frames_bucket_total{bucket="1_2"} 1296
telemt_desync_frames_bucket_total{bucket="3_10"} 1899
telemt_desync_frames_bucket_total{bucket="gt_10"} 1441
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 11284
telemt_me_refill_failed_total 282
telemt_me_writer_restored_same_endpoint_total 10822
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 440
telemt_user_connections_total{user="hello"} 665870
telemt_user_connections_current{user="hello"} 1045
telemt_user_octets_from_client{user="hello"} 10987109071 (10.23 GB)
telemt_user_octets_to_client{user="hello"} 225360633991 (209.88 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 348
telemt_user_unique_ips_recent_window{user="hello"} 159
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 70364.1 (19h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 457488
telemt_connections_bad_total 28824
telemt_handshake_timeouts_total 22861
telemt_upstream_connect_attempt_total 40721
telemt_upstream_connect_success_total 40328
telemt_upstream_connect_fail_total 391
telemt_upstream_connect_attempts_per_request{bucket="1"} 40719
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26975
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10326
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3027
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 391
telemt_me_keepalive_timeout_total 326
telemt_me_reconnect_attempts_total 32276
telemt_me_reconnect_success_total 13358
telemt_me_reader_eof_total 14511
telemt_me_idle_close_by_peer_total 14511
telemt_me_route_drop_no_conn_total 187905
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 360021
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1437
telemt_desync_full_logged_total 452
telemt_desync_suppressed_total 985
telemt_desync_frames_bucket_total{bucket="1_2"} 321
telemt_desync_frames_bucket_total{bucket="3_10"} 627
telemt_desync_frames_bucket_total{bucket="gt_10"} 489
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 14112
telemt_me_refill_failed_total 587
telemt_me_writer_restored_same_endpoint_total 13342
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 754
telemt_user_connections_total{user="hello"} 383358
telemt_user_connections_current{user="hello"} 441
telemt_user_octets_from_client{user="hello"} 4182064070 (3.89 GB)
telemt_user_octets_to_client{user="hello"} 121502760447 (113.16 GB)
telemt_user_msgs_from_client{user="hello"} 360895
telemt_user_msgs_to_client{user="hello"} 1077816
telemt_user_unique_ips_current{user="hello"} 107
telemt_user_unique_ips_recent_window{user="hello"} 140
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 70139.9 (19h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 239625
telemt_connections_bad_total 7809
telemt_handshake_timeouts_total 16951
telemt_upstream_connect_attempt_total 18527
telemt_upstream_connect_success_total 18433
telemt_upstream_connect_fail_total 94
telemt_upstream_connect_attempts_per_request{bucket="1"} 18527
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8212
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10142
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 74
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 94
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 21829
telemt_me_reconnect_success_total 14891
telemt_me_reader_eof_total 15979
telemt_me_idle_close_by_peer_total 15979
telemt_me_route_drop_no_conn_total 97602
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 202330
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 750
telemt_desync_full_logged_total 215
telemt_desync_suppressed_total 535
telemt_desync_frames_bucket_total{bucket="1_2"} 275
telemt_desync_frames_bucket_total{bucket="3_10"} 334
telemt_desync_frames_bucket_total{bucket="gt_10"} 141
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 15315
telemt_me_refill_failed_total 214
telemt_me_writer_restored_same_endpoint_total 14880
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 424
telemt_user_connections_total{user="hello"} 202203
telemt_user_connections_current{user="hello"} 297
telemt_user_octets_from_client{user="hello"} 15414497600 (14.36 GB)
telemt_user_octets_to_client{user="hello"} 53325778024 (49.66 GB)
telemt_user_unique_ips_current{user="hello"} 116
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 70199.5 (19h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 555116
telemt_connections_bad_total 8103
telemt_handshake_timeouts_total 13058
telemt_upstream_connect_attempt_total 16495
telemt_upstream_connect_success_total 16345
telemt_upstream_connect_fail_total 150
telemt_upstream_connect_attempts_per_request{bucket="1"} 16495
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8179
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8049
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 108
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 150
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 21166
telemt_me_reconnect_success_total 11795
telemt_me_reader_eof_total 12745
telemt_me_idle_close_by_peer_total 12745
telemt_me_route_drop_no_conn_total 195617
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 475071
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1624
telemt_desync_full_logged_total 559
telemt_desync_suppressed_total 1065
telemt_desync_frames_bucket_total{bucket="1_2"} 407
telemt_desync_frames_bucket_total{bucket="3_10"} 729
telemt_desync_frames_bucket_total{bucket="gt_10"} 488
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 12293
telemt_me_refill_failed_total 288
telemt_me_writer_restored_same_endpoint_total 11786
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 498
telemt_user_connections_total{user="hello"} 475904
telemt_user_connections_current{user="hello"} 777
telemt_user_octets_from_client{user="hello"} 5916892350 (5.51 GB)
telemt_user_octets_to_client{user="hello"} 156516419139 (145.77 GB)
telemt_user_msgs_from_client{user="hello"} 4070
telemt_user_msgs_to_client{user="hello"} 5224
telemt_user_unique_ips_current{user="hello"} 210
telemt_user_unique_ips_recent_window{user="hello"} 122
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 70172.4 (19h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 269876
telemt_connections_bad_total 56671
telemt_handshake_timeouts_total 3402
telemt_upstream_connect_attempt_total 20512
telemt_upstream_connect_success_total 20061
telemt_upstream_connect_fail_total 451
telemt_upstream_connect_attempts_per_request{bucket="1"} 20512
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9066
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10715
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 280
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 451
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 36171
telemt_me_reconnect_success_total 16152
telemt_me_reader_eof_total 17364
telemt_me_idle_close_by_peer_total 17362
telemt_me_route_drop_no_conn_total 76174
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 198710
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1095
telemt_desync_full_logged_total 229
telemt_desync_suppressed_total 866
telemt_desync_frames_bucket_total{bucket="1_2"} 546
telemt_desync_frames_bucket_total{bucket="3_10"} 420
telemt_desync_frames_bucket_total{bucket="gt_10"} 129
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 17049
telemt_me_refill_failed_total 621
telemt_me_writer_restored_same_endpoint_total 16144
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 897
telemt_user_connections_total{user="hello"} 199167
telemt_user_connections_current{user="hello"} 289
telemt_user_octets_from_client{user="hello"} 2565716291 (2.39 GB)
telemt_user_octets_to_client{user="hello"} 72929184083 (67.92 GB)
telemt_user_msgs_from_client{user="hello"} 1159
telemt_user_msgs_to_client{user="hello"} 2341
telemt_user_unique_ips_current{user="hello"} 92
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 70332.9 (19h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 646775
telemt_connections_bad_total 53844
telemt_handshake_timeouts_total 6440
telemt_upstream_connect_attempt_total 14139
telemt_upstream_connect_success_total 14064
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 14139
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6936
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7105
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 19840
telemt_me_reconnect_success_total 10520
telemt_me_reader_eof_total 11453
telemt_me_idle_close_by_peer_total 11453
telemt_me_route_drop_no_conn_total 452248
telemt_me_route_drop_channel_closed_total 35
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 649071
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 856
telemt_desync_full_logged_total 319
telemt_desync_suppressed_total 537
telemt_desync_frames_bucket_total{bucket="1_2"} 215
telemt_desync_frames_bucket_total{bucket="3_10"} 333
telemt_desync_frames_bucket_total{bucket="gt_10"} 308
telemt_pool_swap_total 60
telemt_me_writer_removed_unexpected_total 10974
telemt_me_refill_failed_total 289
telemt_me_writer_restored_same_endpoint_total 10506
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 454
telemt_user_connections_total{user="hello"} 553553
telemt_user_connections_current{user="hello"} 837
telemt_user_octets_from_client{user="hello"} 8350063024 (7.78 GB)
telemt_user_octets_to_client{user="hello"} 253220342052 (235.83 GB)
telemt_user_unique_ips_current{user="hello"} 311
telemt_user_unique_ips_recent_window{user="hello"} 121
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 18099.5 (5h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14577
telemt_connections_bad_total 63
telemt_handshake_timeouts_total 188
telemt_upstream_connect_attempt_total 10211
telemt_upstream_connect_success_total 10130
telemt_upstream_connect_fail_total 81
telemt_upstream_connect_attempts_per_request{bucket="1"} 10211
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5523
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4598
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 81
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 18121
telemt_me_reconnect_success_total 9041
telemt_me_reader_eof_total 9523
telemt_me_idle_close_by_peer_total 9523
telemt_me_seq_mismatch_total 10
telemt_me_route_drop_no_conn_total 5119
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13939
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 9410
telemt_me_refill_failed_total 282
telemt_me_writer_restored_same_endpoint_total 9026
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 369
telemt_user_connections_total{user="hello"} 14040
telemt_user_connections_current{user="hello"} 75
telemt_user_octets_from_client{user="hello"} 392446813 (374.27 MB)
telemt_user_octets_to_client{user="hello"} 22579800954 (21.03 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 17
telemt_user_unique_ips_recent_window{user="hello"} 11
```