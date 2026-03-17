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

# Server Metrics 2026-03-17 12:52:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 65205.1 (18h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 625193
telemt_connections_bad_total 5023
telemt_handshake_timeouts_total 19833
telemt_upstream_connect_attempt_total 16199
telemt_upstream_connect_success_total 15748
telemt_upstream_connect_fail_total 451
telemt_upstream_connect_attempts_per_request{bucket="1"} 16199
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8245
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7353
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 451
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 119
telemt_me_reconnect_attempts_total 12948
telemt_me_reconnect_success_total 10193
telemt_me_reader_eof_total 10831
telemt_me_idle_close_by_peer_total 10830
telemt_me_route_drop_no_conn_total 203382
telemt_me_route_drop_channel_closed_total 60
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 564341
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4231
telemt_desync_full_logged_total 1142
telemt_desync_suppressed_total 3089
telemt_desync_frames_bucket_total{bucket="1_2"} 1225
telemt_desync_frames_bucket_total{bucket="3_10"} 1753
telemt_desync_frames_bucket_total{bucket="gt_10"} 1253
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 10427
telemt_me_refill_failed_total 81
telemt_me_writer_restored_same_endpoint_total 10171
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 234
telemt_user_connections_total{user="hello"} 566232
telemt_user_connections_current{user="hello"} 968
telemt_user_octets_from_client{user="hello"} 7648306103 (7.12 GB)
telemt_user_octets_to_client{user="hello"} 201313810039 (187.49 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 330
telemt_user_unique_ips_recent_window{user="hello"} 173
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 65456.9 (18h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 367276
telemt_connections_bad_total 21220
telemt_handshake_timeouts_total 20119
telemt_upstream_connect_attempt_total 16569
telemt_upstream_connect_success_total 16307
telemt_upstream_connect_fail_total 262
telemt_upstream_connect_attempts_per_request{bucket="1"} 16569
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6978
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9010
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 319
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 262
telemt_me_keepalive_timeout_total 244
telemt_me_reconnect_attempts_total 25429
telemt_me_reconnect_success_total 13035
telemt_me_reader_eof_total 14012
telemt_me_idle_close_by_peer_total 14012
telemt_me_route_drop_no_conn_total 140800
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 306441
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1148
telemt_desync_full_logged_total 382
telemt_desync_suppressed_total 766
telemt_desync_frames_bucket_total{bucket="1_2"} 270
telemt_desync_frames_bucket_total{bucket="3_10"} 504
telemt_desync_frames_bucket_total{bucket="gt_10"} 374
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 13579
telemt_me_refill_failed_total 384
telemt_me_writer_restored_same_endpoint_total 13019
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 544
telemt_user_connections_total{user="hello"} 306419
telemt_user_connections_current{user="hello"} 717
telemt_user_octets_from_client{user="hello"} 3478160764 (3.24 GB)
telemt_user_octets_to_client{user="hello"} 110144185896 (102.58 GB)
telemt_user_unique_ips_current{user="hello"} 191
telemt_user_unique_ips_recent_window{user="hello"} 104
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 65232.6 (18h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 205778
telemt_connections_bad_total 7742
telemt_handshake_timeouts_total 16490
telemt_upstream_connect_attempt_total 17028
telemt_upstream_connect_success_total 16940
telemt_upstream_connect_fail_total 88
telemt_upstream_connect_attempts_per_request{bucket="1"} 17028
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7533
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9332
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 70
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 88
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 15524
telemt_me_reconnect_success_total 13647
telemt_me_reader_eof_total 14570
telemt_me_idle_close_by_peer_total 14570
telemt_me_route_drop_no_conn_total 69177
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 170593
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 665
telemt_desync_full_logged_total 177
telemt_desync_suppressed_total 488
telemt_desync_frames_bucket_total{bucket="1_2"} 257
telemt_desync_frames_bucket_total{bucket="3_10"} 282
telemt_desync_frames_bucket_total{bucket="gt_10"} 126
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 13900
telemt_me_refill_failed_total 56
telemt_me_writer_restored_same_endpoint_total 13636
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 253
telemt_user_connections_total{user="hello"} 170486
telemt_user_connections_current{user="hello"} 339
telemt_user_octets_from_client{user="hello"} 15183174524 (14.14 GB)
telemt_user_octets_to_client{user="hello"} 47721370556 (44.44 GB)
telemt_user_unique_ips_current{user="hello"} 125
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 65291.9 (18h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 469915
telemt_connections_bad_total 7731
telemt_handshake_timeouts_total 12486
telemt_upstream_connect_attempt_total 15766
telemt_upstream_connect_success_total 15626
telemt_upstream_connect_fail_total 140
telemt_upstream_connect_attempts_per_request{bucket="1"} 15766
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7756
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7761
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 140
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 14706
telemt_me_reconnect_success_total 11328
telemt_me_reader_eof_total 12092
telemt_me_idle_close_by_peer_total 12092
telemt_me_route_drop_no_conn_total 132994
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 395526
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1363
telemt_desync_full_logged_total 480
telemt_desync_suppressed_total 883
telemt_desync_frames_bucket_total{bucket="1_2"} 330
telemt_desync_frames_bucket_total{bucket="3_10"} 620
telemt_desync_frames_bucket_total{bucket="gt_10"} 413
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 11631
telemt_me_refill_failed_total 101
telemt_me_writer_restored_same_endpoint_total 11319
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 303
telemt_user_connections_total{user="hello"} 396403
telemt_user_connections_current{user="hello"} 769
telemt_user_octets_from_client{user="hello"} 5137802842 (4.78 GB)
telemt_user_octets_to_client{user="hello"} 138716613443 (129.19 GB)
telemt_user_msgs_from_client{user="hello"} 4070
telemt_user_msgs_to_client{user="hello"} 5224
telemt_user_unique_ips_current{user="hello"} 207
telemt_user_unique_ips_recent_window{user="hello"} 100
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 65263.7 (18h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 236463
telemt_connections_bad_total 52860
telemt_handshake_timeouts_total 3148
telemt_upstream_connect_attempt_total 19079
telemt_upstream_connect_success_total 18834
telemt_upstream_connect_fail_total 245
telemt_upstream_connect_attempts_per_request{bucket="1"} 19079
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8412
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10183
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 239
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 245
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 30097
telemt_me_reconnect_success_total 15442
telemt_me_reader_eof_total 16539
telemt_me_idle_close_by_peer_total 16539
telemt_me_route_drop_no_conn_total 63046
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 172210
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1004
telemt_desync_full_logged_total 208
telemt_desync_suppressed_total 796
telemt_desync_frames_bucket_total{bucket="1_2"} 510
telemt_desync_frames_bucket_total{bucket="3_10"} 373
telemt_desync_frames_bucket_total{bucket="gt_10"} 121
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 16104
telemt_me_refill_failed_total 455
telemt_me_writer_restored_same_endpoint_total 15434
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 662
telemt_user_connections_total{user="hello"} 172218
telemt_user_connections_current{user="hello"} 289
telemt_user_octets_from_client{user="hello"} 2303065635 (2.14 GB)
telemt_user_octets_to_client{user="hello"} 68443287318 (63.74 GB)
telemt_user_msgs_from_client{user="hello"} 265
telemt_user_msgs_to_client{user="hello"} 707
telemt_user_unique_ips_current{user="hello"} 90
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 65425.1 (18h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 562689
telemt_connections_bad_total 52090
telemt_handshake_timeouts_total 5322
telemt_upstream_connect_attempt_total 13149
telemt_upstream_connect_success_total 13078
telemt_upstream_connect_fail_total 71
telemt_upstream_connect_attempts_per_request{bucket="1"} 13149
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6473
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6585
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 71
telemt_me_keepalive_timeout_total 36
telemt_me_reconnect_attempts_total 13718
telemt_me_reconnect_success_total 9820
telemt_me_reader_eof_total 10575
telemt_me_idle_close_by_peer_total 10575
telemt_me_route_drop_no_conn_total 360504
telemt_me_route_drop_channel_closed_total 27
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 553576
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 829
telemt_desync_full_logged_total 303
telemt_desync_suppressed_total 526
telemt_desync_frames_bucket_total{bucket="1_2"} 209
telemt_desync_frames_bucket_total{bucket="3_10"} 317
telemt_desync_frames_bucket_total{bucket="gt_10"} 303
telemt_pool_swap_total 60
telemt_me_writer_removed_unexpected_total 10090
telemt_me_refill_failed_total 120
telemt_me_writer_restored_same_endpoint_total 9806
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 270
telemt_user_connections_total{user="hello"} 475241
telemt_user_connections_current{user="hello"} 989
telemt_user_octets_from_client{user="hello"} 7041474584 (6.56 GB)
telemt_user_octets_to_client{user="hello"} 227760536756 (212.12 GB)
telemt_user_unique_ips_current{user="hello"} 311
telemt_user_unique_ips_recent_window{user="hello"} 136
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 13192.0 (3h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10226
telemt_connections_bad_total 57
telemt_handshake_timeouts_total 40
telemt_upstream_connect_attempt_total 7292
telemt_upstream_connect_success_total 7228
telemt_upstream_connect_fail_total 64
telemt_upstream_connect_attempts_per_request{bucket="1"} 7292
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3844
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3381
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 64
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 9651
telemt_me_reconnect_success_total 6402
telemt_me_reader_eof_total 6689
telemt_me_idle_close_by_peer_total 6689
telemt_me_seq_mismatch_total 8
telemt_me_route_drop_no_conn_total 3744
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9839
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
telemt_me_writer_removed_unexpected_total 6566
telemt_me_refill_failed_total 100
telemt_me_writer_restored_same_endpoint_total 6390
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 164
telemt_user_connections_total{user="hello"} 9943
telemt_user_connections_current{user="hello"} 86
telemt_user_octets_from_client{user="hello"} 269884309 (257.38 MB)
telemt_user_octets_to_client{user="hello"} 20713961662 (19.29 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 19
telemt_user_unique_ips_recent_window{user="hello"} 10
```