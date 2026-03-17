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

# Server Metrics 2026-03-17 10:18:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 56004.6 (15h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 461885
telemt_connections_bad_total 3840
telemt_handshake_timeouts_total 12707
telemt_upstream_connect_attempt_total 14145
telemt_upstream_connect_success_total 13710
telemt_upstream_connect_fail_total 435
telemt_upstream_connect_attempts_per_request{bucket="1"} 14145
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7305
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6255
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 435
telemt_me_keepalive_timeout_total 104
telemt_me_reconnect_attempts_total 10137
telemt_me_reconnect_success_total 8606
telemt_me_reader_eof_total 9150
telemt_me_idle_close_by_peer_total 9149
telemt_me_route_drop_no_conn_total 146001
telemt_me_route_drop_channel_closed_total 40
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 418272
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3344
telemt_desync_full_logged_total 892
telemt_desync_suppressed_total 2452
telemt_desync_frames_bucket_total{bucket="1_2"} 890
telemt_desync_frames_bucket_total{bucket="3_10"} 1443
telemt_desync_frames_bucket_total{bucket="gt_10"} 1011
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 8784
telemt_me_refill_failed_total 43
telemt_me_writer_restored_same_endpoint_total 8584
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 178
telemt_user_connections_total{user="hello"} 420233
telemt_user_connections_current{user="hello"} 943
telemt_user_octets_from_client{user="hello"} 6124215599 (5.70 GB)
telemt_user_octets_to_client{user="hello"} 163452060771 (152.23 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 329
telemt_user_unique_ips_recent_window{user="hello"} 131
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 56256.2 (15h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 250711
telemt_connections_bad_total 3597
telemt_handshake_timeouts_total 14756
telemt_upstream_connect_attempt_total 14488
telemt_upstream_connect_success_total 14285
telemt_upstream_connect_fail_total 203
telemt_upstream_connect_attempts_per_request{bucket="1"} 14488
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6157
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7966
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 162
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 203
telemt_me_keepalive_timeout_total 6
telemt_me_reconnect_attempts_total 20205
telemt_me_reconnect_success_total 11493
telemt_me_reader_eof_total 12337
telemt_me_idle_close_by_peer_total 12337
telemt_me_route_drop_no_conn_total 91933
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 220091
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 591
telemt_desync_full_logged_total 225
telemt_desync_suppressed_total 366
telemt_desync_frames_bucket_total{bucket="1_2"} 173
telemt_desync_frames_bucket_total{bucket="3_10"} 256
telemt_desync_frames_bucket_total{bucket="gt_10"} 162
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 11886
telemt_me_refill_failed_total 271
telemt_me_writer_restored_same_endpoint_total 11477
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 393
telemt_user_connections_total{user="hello"} 220090
telemt_user_connections_current{user="hello"} 472
telemt_user_octets_from_client{user="hello"} 2675766824 (2.49 GB)
telemt_user_octets_to_client{user="hello"} 83060924216 (77.36 GB)
telemt_user_unique_ips_current{user="hello"} 159
telemt_user_unique_ips_recent_window{user="hello"} 59
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 56032.4 (15h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 153359
telemt_connections_bad_total 7602
telemt_handshake_timeouts_total 11406
telemt_upstream_connect_attempt_total 15015
telemt_upstream_connect_success_total 14936
telemt_upstream_connect_fail_total 79
telemt_upstream_connect_attempts_per_request{bucket="1"} 15015
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6626
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8244
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 65
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 79
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 13962
telemt_me_reconnect_success_total 12095
telemt_me_reader_eof_total 12925
telemt_me_idle_close_by_peer_total 12925
telemt_me_route_drop_no_conn_total 45920
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 124717
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 419
telemt_desync_full_logged_total 110
telemt_desync_suppressed_total 309
telemt_desync_frames_bucket_total{bucket="1_2"} 166
telemt_desync_frames_bucket_total{bucket="3_10"} 178
telemt_desync_frames_bucket_total{bucket="gt_10"} 75
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 12315
telemt_me_refill_failed_total 56
telemt_me_writer_restored_same_endpoint_total 12084
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 220
telemt_user_connections_total{user="hello"} 124630
telemt_user_connections_current{user="hello"} 327
telemt_user_octets_from_client{user="hello"} 9687516200 (9.02 GB)
telemt_user_octets_to_client{user="hello"} 38213924340 (35.59 GB)
telemt_user_unique_ips_current{user="hello"} 116
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 56091.3 (15h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 342317
telemt_connections_bad_total 6211
telemt_handshake_timeouts_total 11501
telemt_upstream_connect_attempt_total 12833
telemt_upstream_connect_success_total 12714
telemt_upstream_connect_fail_total 119
telemt_upstream_connect_attempts_per_request{bucket="1"} 12833
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6017
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6614
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 119
telemt_me_keepalive_timeout_total 6
telemt_me_reconnect_attempts_total 10931
telemt_me_reconnect_success_total 9837
telemt_me_reader_eof_total 10459
telemt_me_idle_close_by_peer_total 10459
telemt_me_route_drop_no_conn_total 95695
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 278984
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 646
telemt_desync_full_logged_total 256
telemt_desync_suppressed_total 390
telemt_desync_frames_bucket_total{bucket="1_2"} 158
telemt_desync_frames_bucket_total{bucket="3_10"} 285
telemt_desync_frames_bucket_total{bucket="gt_10"} 203
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 10023
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 9829
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 186
telemt_user_connections_total{user="hello"} 278939
telemt_user_connections_current{user="hello"} 736
telemt_user_octets_from_client{user="hello"} 3399619222 (3.17 GB)
telemt_user_octets_to_client{user="hello"} 108335584249 (100.90 GB)
telemt_user_msgs_from_client{user="hello"} 65
telemt_user_msgs_to_client{user="hello"} 189
telemt_user_unique_ips_current{user="hello"} 199
telemt_user_unique_ips_recent_window{user="hello"} 99
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 56063.2 (15h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 188552
telemt_connections_bad_total 51111
telemt_handshake_timeouts_total 2879
telemt_upstream_connect_attempt_total 17151
telemt_upstream_connect_success_total 16928
telemt_upstream_connect_fail_total 223
telemt_upstream_connect_attempts_per_request{bucket="1"} 17151
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7557
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9162
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 209
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 223
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 22106
telemt_me_reconnect_success_total 13990
telemt_me_reader_eof_total 14843
telemt_me_idle_close_by_peer_total 14843
telemt_me_route_drop_no_conn_total 48800
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 128864
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 481
telemt_desync_full_logged_total 114
telemt_desync_suppressed_total 367
telemt_desync_frames_bucket_total{bucket="1_2"} 236
telemt_desync_frames_bucket_total{bucket="3_10"} 176
telemt_desync_frames_bucket_total{bucket="gt_10"} 69
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 14421
telemt_me_refill_failed_total 251
telemt_me_writer_restored_same_endpoint_total 13982
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 431
telemt_user_connections_total{user="hello"} 128893
telemt_user_connections_current{user="hello"} 338
telemt_user_octets_from_client{user="hello"} 1911465195 (1.78 GB)
telemt_user_octets_to_client{user="hello"} 57624758398 (53.67 GB)
telemt_user_msgs_from_client{user="hello"} 265
telemt_user_msgs_to_client{user="hello"} 707
telemt_user_unique_ips_current{user="hello"} 117
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 56224.7 (15h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 438079
telemt_connections_bad_total 49913
telemt_handshake_timeouts_total 4408
telemt_upstream_connect_attempt_total 11405
telemt_upstream_connect_success_total 11343
telemt_upstream_connect_fail_total 62
telemt_upstream_connect_attempts_per_request{bucket="1"} 11405
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5575
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5748
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 62
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 12425
telemt_me_reconnect_success_total 8541
telemt_me_reader_eof_total 9226
telemt_me_idle_close_by_peer_total 9226
telemt_me_route_drop_no_conn_total 284704
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 438581
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 663
telemt_desync_full_logged_total 254
telemt_desync_suppressed_total 409
telemt_desync_frames_bucket_total{bucket="1_2"} 179
telemt_desync_frames_bucket_total{bucket="3_10"} 255
telemt_desync_frames_bucket_total{bucket="gt_10"} 229
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 8793
telemt_me_refill_failed_total 120
telemt_me_writer_restored_same_endpoint_total 8527
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 252
telemt_user_connections_total{user="hello"} 360455
telemt_user_connections_current{user="hello"} 855
telemt_user_octets_from_client{user="hello"} 5196475160 (4.84 GB)
telemt_user_octets_to_client{user="hello"} 194299779776 (180.96 GB)
telemt_user_unique_ips_current{user="hello"} 276
telemt_user_unique_ips_recent_window{user="hello"} 105
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 3991.4 (1h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3457
telemt_connections_bad_total 7
telemt_handshake_timeouts_total 32
telemt_upstream_connect_attempt_total 1707
telemt_upstream_connect_success_total 1680
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 1707
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 935
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 745
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_reconnect_attempts_total 1342
telemt_me_reconnect_success_total 1312
telemt_me_reader_eof_total 1354
telemt_me_idle_close_by_peer_total 1354
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 1233
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3196
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 1327
telemt_me_writer_restored_same_endpoint_total 1306
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 15
telemt_user_connections_total{user="hello"} 3302
telemt_user_connections_current{user="hello"} 73
telemt_user_octets_from_client{user="hello"} 52167861 (49.75 MB)
telemt_user_octets_to_client{user="hello"} 14391922206 (13.40 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 19
telemt_user_unique_ips_recent_window{user="hello"} 5
```