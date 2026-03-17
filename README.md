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

# Server Metrics 2026-03-17 12:36:43 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 64287.1 (17h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 608134
telemt_connections_bad_total 4861
telemt_handshake_timeouts_total 19530
telemt_upstream_connect_attempt_total 15933
telemt_upstream_connect_success_total 15486
telemt_upstream_connect_fail_total 447
telemt_upstream_connect_attempts_per_request{bucket="1"} 15933
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8137
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7199
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 447
telemt_me_keepalive_timeout_total 111
telemt_me_reconnect_attempts_total 12733
telemt_me_reconnect_success_total 9979
telemt_me_reader_eof_total 10613
telemt_me_idle_close_by_peer_total 10612
telemt_me_route_drop_no_conn_total 197405
telemt_me_route_drop_channel_closed_total 57
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 548329
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4140
telemt_desync_full_logged_total 1111
telemt_desync_suppressed_total 3029
telemt_desync_frames_bucket_total{bucket="1_2"} 1203
telemt_desync_frames_bucket_total{bucket="3_10"} 1716
telemt_desync_frames_bucket_total{bucket="gt_10"} 1221
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 10208
telemt_me_refill_failed_total 81
telemt_me_writer_restored_same_endpoint_total 9957
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 229
telemt_user_connections_total{user="hello"} 550224
telemt_user_connections_current{user="hello"} 862
telemt_user_octets_from_client{user="hello"} 7457691423 (6.95 GB)
telemt_user_octets_to_client{user="hello"} 197681699631 (184.11 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 313
telemt_user_unique_ips_recent_window{user="hello"} 141
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 64538.4 (17h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 350201
telemt_connections_bad_total 19300
telemt_handshake_timeouts_total 19722
telemt_upstream_connect_attempt_total 16296
telemt_upstream_connect_success_total 16063
telemt_upstream_connect_fail_total 233
telemt_upstream_connect_attempts_per_request{bucket="1"} 16296
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6874
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8904
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 285
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 233
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 25209
telemt_me_reconnect_success_total 12861
telemt_me_reader_eof_total 13850
telemt_me_idle_close_by_peer_total 13850
telemt_me_route_drop_no_conn_total 128593
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 293067
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1034
telemt_desync_full_logged_total 356
telemt_desync_suppressed_total 678
telemt_desync_frames_bucket_total{bucket="1_2"} 251
telemt_desync_frames_bucket_total{bucket="3_10"} 443
telemt_desync_frames_bucket_total{bucket="gt_10"} 340
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 13391
telemt_me_refill_failed_total 384
telemt_me_writer_restored_same_endpoint_total 12845
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 530
telemt_user_connections_total{user="hello"} 293044
telemt_user_connections_current{user="hello"} 646
telemt_user_octets_from_client{user="hello"} 3390344532 (3.16 GB)
telemt_user_octets_to_client{user="hello"} 106660605676 (99.34 GB)
telemt_user_unique_ips_current{user="hello"} 188
telemt_user_unique_ips_recent_window{user="hello"} 98
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 64314.5 (17h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 199436
telemt_connections_bad_total 7734
telemt_handshake_timeouts_total 16460
telemt_upstream_connect_attempt_total 16809
telemt_upstream_connect_success_total 16722
telemt_upstream_connect_fail_total 87
telemt_upstream_connect_attempts_per_request{bucket="1"} 16809
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7417
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9230
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 70
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 87
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 15354
telemt_me_reconnect_success_total 13479
telemt_me_reader_eof_total 14400
telemt_me_idle_close_by_peer_total 14400
telemt_me_route_drop_no_conn_total 62100
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 164453
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 621
telemt_desync_full_logged_total 165
telemt_desync_suppressed_total 456
telemt_desync_frames_bucket_total{bucket="1_2"} 253
telemt_desync_frames_bucket_total{bucket="3_10"} 266
telemt_desync_frames_bucket_total{bucket="gt_10"} 102
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 13731
telemt_me_refill_failed_total 56
telemt_me_writer_restored_same_endpoint_total 13468
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 252
telemt_user_connections_total{user="hello"} 164347
telemt_user_connections_current{user="hello"} 332
telemt_user_octets_from_client{user="hello"} 15149944148 (14.11 GB)
telemt_user_octets_to_client{user="hello"} 45582414180 (42.45 GB)
telemt_user_unique_ips_current{user="hello"} 123
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 64373.9 (17h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 456614
telemt_connections_bad_total 7710
telemt_handshake_timeouts_total 12396
telemt_upstream_connect_attempt_total 15534
telemt_upstream_connect_success_total 15396
telemt_upstream_connect_fail_total 138
telemt_upstream_connect_attempts_per_request{bucket="1"} 15534
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7652
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7639
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 138
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 14520
telemt_me_reconnect_success_total 11146
telemt_me_reader_eof_total 11898
telemt_me_idle_close_by_peer_total 11898
telemt_me_route_drop_no_conn_total 128833
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 383068
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1283
telemt_desync_full_logged_total 456
telemt_desync_suppressed_total 827
telemt_desync_frames_bucket_total{bucket="1_2"} 312
telemt_desync_frames_bucket_total{bucket="3_10"} 574
telemt_desync_frames_bucket_total{bucket="gt_10"} 397
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 11437
telemt_me_refill_failed_total 101
telemt_me_writer_restored_same_endpoint_total 11137
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 291
telemt_user_connections_total{user="hello"} 383940
telemt_user_connections_current{user="hello"} 806
telemt_user_octets_from_client{user="hello"} 5046122390 (4.70 GB)
telemt_user_octets_to_client{user="hello"} 135611291575 (126.30 GB)
telemt_user_msgs_from_client{user="hello"} 4070
telemt_user_msgs_to_client{user="hello"} 5224
telemt_user_unique_ips_current{user="hello"} 228
telemt_user_unique_ips_recent_window{user="hello"} 104
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 64345.7 (17h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 231127
telemt_connections_bad_total 52685
telemt_handshake_timeouts_total 3119
telemt_upstream_connect_attempt_total 18853
telemt_upstream_connect_success_total 18609
telemt_upstream_connect_fail_total 244
telemt_upstream_connect_attempts_per_request{bucket="1"} 18853
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8333
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10039
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 237
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 244
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 28926
telemt_me_reconnect_success_total 15264
telemt_me_reader_eof_total 16321
telemt_me_idle_close_by_peer_total 16321
telemt_me_route_drop_no_conn_total 61365
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 167470
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 985
telemt_desync_full_logged_total 201
telemt_desync_suppressed_total 784
telemt_desync_frames_bucket_total{bucket="1_2"} 507
telemt_desync_frames_bucket_total{bucket="3_10"} 362
telemt_desync_frames_bucket_total{bucket="gt_10"} 116
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 15886
telemt_me_refill_failed_total 424
telemt_me_writer_restored_same_endpoint_total 15256
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 622
telemt_user_connections_total{user="hello"} 167481
telemt_user_connections_current{user="hello"} 271
telemt_user_octets_from_client{user="hello"} 2245219895 (2.09 GB)
telemt_user_octets_to_client{user="hello"} 67441768918 (62.81 GB)
telemt_user_msgs_from_client{user="hello"} 265
telemt_user_msgs_to_client{user="hello"} 707
telemt_user_unique_ips_current{user="hello"} 99
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 64507.7 (17h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 549974
telemt_connections_bad_total 52083
telemt_handshake_timeouts_total 5033
telemt_upstream_connect_attempt_total 12942
telemt_upstream_connect_success_total 12873
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 12942
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6368
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6485
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 13557
telemt_me_reconnect_success_total 9662
telemt_me_reader_eof_total 10415
telemt_me_idle_close_by_peer_total 10415
telemt_me_route_drop_no_conn_total 355551
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 541473
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
telemt_me_writer_removed_unexpected_total 9931
telemt_me_refill_failed_total 120
telemt_me_writer_restored_same_endpoint_total 9648
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 269
telemt_user_connections_total{user="hello"} 463142
telemt_user_connections_current{user="hello"} 958
telemt_user_octets_from_client{user="hello"} 6885664768 (6.41 GB)
telemt_user_octets_to_client{user="hello"} 223769108008 (208.40 GB)
telemt_user_unique_ips_current{user="hello"} 304
telemt_user_unique_ips_recent_window{user="hello"} 121
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 12273.9 (3h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9463
telemt_connections_bad_total 56
telemt_handshake_timeouts_total 40
telemt_upstream_connect_attempt_total 6680
telemt_upstream_connect_success_total 6619
telemt_upstream_connect_fail_total 61
telemt_upstream_connect_attempts_per_request{bucket="1"} 6680
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3555
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3063
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 61
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 9085
telemt_me_reconnect_success_total 5839
telemt_me_reader_eof_total 6120
telemt_me_idle_close_by_peer_total 6120
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 3514
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9085
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 5994
telemt_me_refill_failed_total 100
telemt_me_writer_restored_same_endpoint_total 5828
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 155
telemt_user_connections_total{user="hello"} 9189
telemt_user_connections_current{user="hello"} 69
telemt_user_octets_from_client{user="hello"} 234723445 (223.85 MB)
telemt_user_octets_to_client{user="hello"} 20023938886 (18.65 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 19
telemt_user_unique_ips_recent_window{user="hello"} 5
```