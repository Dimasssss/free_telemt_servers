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

# Server Metrics 2026-03-17 12:06:08 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 62451.9 (17h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 575211
telemt_connections_bad_total 4793
telemt_handshake_timeouts_total 17514
telemt_upstream_connect_attempt_total 15519
telemt_upstream_connect_success_total 15074
telemt_upstream_connect_fail_total 445
telemt_upstream_connect_attempts_per_request{bucket="1"} 15519
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7946
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6978
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 445
telemt_me_keepalive_timeout_total 110
telemt_me_reconnect_attempts_total 12411
telemt_me_reconnect_success_total 9658
telemt_me_reader_eof_total 10274
telemt_me_idle_close_by_peer_total 10273
telemt_me_route_drop_no_conn_total 187146
telemt_me_route_drop_channel_closed_total 52
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 519646
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3989
telemt_desync_full_logged_total 1063
telemt_desync_suppressed_total 2926
telemt_desync_frames_bucket_total{bucket="1_2"} 1151
telemt_desync_frames_bucket_total{bucket="3_10"} 1662
telemt_desync_frames_bucket_total{bucket="gt_10"} 1176
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 9884
telemt_me_refill_failed_total 81
telemt_me_writer_restored_same_endpoint_total 9636
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 226
telemt_user_connections_total{user="hello"} 521565
telemt_user_connections_current{user="hello"} 1003
telemt_user_octets_from_client{user="hello"} 7016360295 (6.53 GB)
telemt_user_octets_to_client{user="hello"} 188400415655 (175.46 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 357
telemt_user_unique_ips_recent_window{user="hello"} 143
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 62703.9 (17h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 325704
telemt_connections_bad_total 15396
telemt_handshake_timeouts_total 18509
telemt_upstream_connect_attempt_total 15872
telemt_upstream_connect_success_total 15649
telemt_upstream_connect_fail_total 223
telemt_upstream_connect_attempts_per_request{bucket="1"} 15872
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6736
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8661
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 252
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 223
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 24876
telemt_me_reconnect_success_total 12541
telemt_me_reader_eof_total 13516
telemt_me_idle_close_by_peer_total 13516
telemt_me_route_drop_no_conn_total 120118
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 275878
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 962
telemt_desync_full_logged_total 327
telemt_desync_suppressed_total 635
telemt_desync_frames_bucket_total{bucket="1_2"} 246
telemt_desync_frames_bucket_total{bucket="3_10"} 407
telemt_desync_frames_bucket_total{bucket="gt_10"} 309
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 13062
telemt_me_refill_failed_total 384
telemt_me_writer_restored_same_endpoint_total 12525
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 521
telemt_user_connections_total{user="hello"} 275867
telemt_user_connections_current{user="hello"} 604
telemt_user_octets_from_client{user="hello"} 3196445960 (2.98 GB)
telemt_user_octets_to_client{user="hello"} 100360523436 (93.47 GB)
telemt_user_unique_ips_current{user="hello"} 169
telemt_user_unique_ips_recent_window{user="hello"} 69
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 62479.8 (17h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 188647
telemt_connections_bad_total 7725
telemt_handshake_timeouts_total 15758
telemt_upstream_connect_attempt_total 16413
telemt_upstream_connect_success_total 16327
telemt_upstream_connect_fail_total 86
telemt_upstream_connect_attempts_per_request{bucket="1"} 16413
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7226
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9026
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 70
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 86
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 15047
telemt_me_reconnect_success_total 13173
telemt_me_reader_eof_total 14076
telemt_me_idle_close_by_peer_total 14076
telemt_me_route_drop_no_conn_total 56350
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 154580
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 567
telemt_desync_full_logged_total 149
telemt_desync_suppressed_total 418
telemt_desync_frames_bucket_total{bucket="1_2"} 236
telemt_desync_frames_bucket_total{bucket="3_10"} 248
telemt_desync_frames_bucket_total{bucket="gt_10"} 83
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 13422
telemt_me_refill_failed_total 56
telemt_me_writer_restored_same_endpoint_total 13162
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 249
telemt_user_connections_total{user="hello"} 154480
telemt_user_connections_current{user="hello"} 326
telemt_user_octets_from_client{user="hello"} 14905265008 (13.88 GB)
telemt_user_octets_to_client{user="hello"} 44038868420 (41.01 GB)
telemt_user_unique_ips_current{user="hello"} 121
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 62538.8 (17h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 427823
telemt_connections_bad_total 6900
telemt_handshake_timeouts_total 12211
telemt_upstream_connect_attempt_total 14272
telemt_upstream_connect_success_total 14138
telemt_upstream_connect_fail_total 134
telemt_upstream_connect_attempts_per_request{bucket="1"} 14272
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6604
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7443
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 83
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 134
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 14313
telemt_me_reconnect_success_total 10943
telemt_me_reader_eof_total 11685
telemt_me_idle_close_by_peer_total 11685
telemt_me_route_drop_no_conn_total 121119
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 358147
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1136
telemt_desync_full_logged_total 408
telemt_desync_suppressed_total 728
telemt_desync_frames_bucket_total{bucket="1_2"} 279
telemt_desync_frames_bucket_total{bucket="3_10"} 495
telemt_desync_frames_bucket_total{bucket="gt_10"} 362
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 11224
telemt_me_refill_failed_total 101
telemt_me_writer_restored_same_endpoint_total 10934
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 281
telemt_user_connections_total{user="hello"} 358069
telemt_user_connections_current{user="hello"} 683
telemt_user_octets_from_client{user="hello"} 4557525322 (4.24 GB)
telemt_user_octets_to_client{user="hello"} 129169069885 (120.30 GB)
telemt_user_msgs_from_client{user="hello"} 65
telemt_user_msgs_to_client{user="hello"} 189
telemt_user_unique_ips_current{user="hello"} 206
telemt_user_unique_ips_recent_window{user="hello"} 90
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 62510.8 (17h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 221545
telemt_connections_bad_total 52358
telemt_handshake_timeouts_total 3092
telemt_upstream_connect_attempt_total 18334
telemt_upstream_connect_success_total 18095
telemt_upstream_connect_fail_total 239
telemt_upstream_connect_attempts_per_request{bucket="1"} 18334
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8108
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9754
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 233
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 239
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 28501
telemt_me_reconnect_success_total 14842
telemt_me_reader_eof_total 15892
telemt_me_idle_close_by_peer_total 15892
telemt_me_route_drop_no_conn_total 58230
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 158585
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 920
telemt_desync_full_logged_total 181
telemt_desync_suppressed_total 739
telemt_desync_frames_bucket_total{bucket="1_2"} 480
telemt_desync_frames_bucket_total{bucket="3_10"} 337
telemt_desync_frames_bucket_total{bucket="gt_10"} 103
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 15455
telemt_me_refill_failed_total 424
telemt_me_writer_restored_same_endpoint_total 14834
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 613
telemt_user_connections_total{user="hello"} 158600
telemt_user_connections_current{user="hello"} 297
telemt_user_octets_from_client{user="hello"} 2155323987 (2.01 GB)
telemt_user_octets_to_client{user="hello"} 65751309534 (61.24 GB)
telemt_user_msgs_from_client{user="hello"} 265
telemt_user_msgs_to_client{user="hello"} 707
telemt_user_unique_ips_current{user="hello"} 102
telemt_user_unique_ips_recent_window{user="hello"} 59
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 62672.3 (17h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 524104
telemt_connections_bad_total 51927
telemt_handshake_timeouts_total 4824
telemt_upstream_connect_attempt_total 12636
telemt_upstream_connect_success_total 12568
telemt_upstream_connect_fail_total 68
telemt_upstream_connect_attempts_per_request{bucket="1"} 12636
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6213
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6335
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 68
telemt_me_keepalive_timeout_total 31
telemt_me_reconnect_attempts_total 13339
telemt_me_reconnect_success_total 9445
telemt_me_reader_eof_total 10185
telemt_me_idle_close_by_peer_total 10185
telemt_me_route_drop_no_conn_total 345079
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 516973
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 794
telemt_desync_full_logged_total 292
telemt_desync_suppressed_total 502
telemt_desync_frames_bucket_total{bucket="1_2"} 205
telemt_desync_frames_bucket_total{bucket="3_10"} 303
telemt_desync_frames_bucket_total{bucket="gt_10"} 286
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 9713
telemt_me_refill_failed_total 120
telemt_me_writer_restored_same_endpoint_total 9431
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 268
telemt_user_connections_total{user="hello"} 438651
telemt_user_connections_current{user="hello"} 896
telemt_user_octets_from_client{user="hello"} 6529230008 (6.08 GB)
telemt_user_octets_to_client{user="hello"} 216850315616 (201.96 GB)
telemt_user_unique_ips_current{user="hello"} 298
telemt_user_unique_ips_recent_window{user="hello"} 107
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 10439.0 (2h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8022
telemt_connections_bad_total 46
telemt_handshake_timeouts_total 37
telemt_upstream_connect_attempt_total 5910
telemt_upstream_connect_success_total 5859
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 5910
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3159
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2700
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 8411
telemt_me_reconnect_success_total 5169
telemt_me_reader_eof_total 5425
telemt_me_idle_close_by_peer_total 5425
telemt_me_seq_mismatch_total 5
telemt_me_route_drop_no_conn_total 2990
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7674
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 5319
telemt_me_refill_failed_total 100
telemt_me_writer_restored_same_endpoint_total 5160
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 150
telemt_user_connections_total{user="hello"} 7780
telemt_user_connections_current{user="hello"} 83
telemt_user_octets_from_client{user="hello"} 160342465 (152.91 MB)
telemt_user_octets_to_client{user="hello"} 19448541374 (18.11 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 22
telemt_user_unique_ips_recent_window{user="hello"} 7
```