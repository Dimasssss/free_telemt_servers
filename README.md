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

# Server Metrics 2026-03-17 12:46:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 64899.4 (18h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 619022
telemt_connections_bad_total 4867
telemt_handshake_timeouts_total 19806
telemt_upstream_connect_attempt_total 16053
telemt_upstream_connect_success_total 15606
telemt_upstream_connect_fail_total 447
telemt_upstream_connect_attempts_per_request{bucket="1"} 16053
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8183
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7273
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 447
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 12832
telemt_me_reconnect_success_total 10077
telemt_me_reader_eof_total 10714
telemt_me_idle_close_by_peer_total 10713
telemt_me_route_drop_no_conn_total 201435
telemt_me_route_drop_channel_closed_total 60
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 558523
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4188
telemt_desync_full_logged_total 1131
telemt_desync_suppressed_total 3057
telemt_desync_frames_bucket_total{bucket="1_2"} 1217
telemt_desync_frames_bucket_total{bucket="3_10"} 1734
telemt_desync_frames_bucket_total{bucket="gt_10"} 1237
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 10309
telemt_me_refill_failed_total 81
telemt_me_writer_restored_same_endpoint_total 10055
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 232
telemt_user_connections_total{user="hello"} 560415
telemt_user_connections_current{user="hello"} 883
telemt_user_octets_from_client{user="hello"} 7599962855 (7.08 GB)
telemt_user_octets_to_client{user="hello"} 200290222431 (186.53 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 317
telemt_user_unique_ips_recent_window{user="hello"} 143
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 65151.7 (18h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 361063
telemt_connections_bad_total 20670
telemt_handshake_timeouts_total 20041
telemt_upstream_connect_attempt_total 16507
telemt_upstream_connect_success_total 16248
telemt_upstream_connect_fail_total 259
telemt_upstream_connect_attempts_per_request{bucket="1"} 16507
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6953
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8988
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 307
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 259
telemt_me_keepalive_timeout_total 244
telemt_me_reconnect_attempts_total 25367
telemt_me_reconnect_success_total 12983
telemt_me_reader_eof_total 13967
telemt_me_idle_close_by_peer_total 13967
telemt_me_route_drop_no_conn_total 137312
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 301750
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1121
telemt_desync_full_logged_total 376
telemt_desync_suppressed_total 745
telemt_desync_frames_bucket_total{bucket="1_2"} 268
telemt_desync_frames_bucket_total{bucket="3_10"} 488
telemt_desync_frames_bucket_total{bucket="gt_10"} 365
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 13527
telemt_me_refill_failed_total 384
telemt_me_writer_restored_same_endpoint_total 12967
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 544
telemt_user_connections_total{user="hello"} 301726
telemt_user_connections_current{user="hello"} 646
telemt_user_octets_from_client{user="hello"} 3451768860 (3.21 GB)
telemt_user_octets_to_client{user="hello"} 108734153620 (101.27 GB)
telemt_user_unique_ips_current{user="hello"} 177
telemt_user_unique_ips_recent_window{user="hello"} 94
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 64926.8 (18h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 203933
telemt_connections_bad_total 7734
telemt_handshake_timeouts_total 16477
telemt_upstream_connect_attempt_total 16918
telemt_upstream_connect_success_total 16830
telemt_upstream_connect_fail_total 88
telemt_upstream_connect_attempts_per_request{bucket="1"} 16918
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7473
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9282
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 70
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 88
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 15426
telemt_me_reconnect_success_total 13551
telemt_me_reader_eof_total 14472
telemt_me_idle_close_by_peer_total 14472
telemt_me_route_drop_no_conn_total 67804
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 168835
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 651
telemt_desync_full_logged_total 172
telemt_desync_suppressed_total 479
telemt_desync_frames_bucket_total{bucket="1_2"} 257
telemt_desync_frames_bucket_total{bucket="3_10"} 275
telemt_desync_frames_bucket_total{bucket="gt_10"} 119
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 13803
telemt_me_refill_failed_total 56
telemt_me_writer_restored_same_endpoint_total 13540
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 252
telemt_user_connections_total{user="hello"} 168729
telemt_user_connections_current{user="hello"} 365
telemt_user_octets_from_client{user="hello"} 15170861960 (14.13 GB)
telemt_user_octets_to_client{user="hello"} 46583951432 (43.38 GB)
telemt_user_unique_ips_current{user="hello"} 119
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 64986.3 (18h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 465182
telemt_connections_bad_total 7728
telemt_handshake_timeouts_total 12430
telemt_upstream_connect_attempt_total 15687
telemt_upstream_connect_success_total 15548
telemt_upstream_connect_fail_total 139
telemt_upstream_connect_attempts_per_request{bucket="1"} 15687
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7728
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7715
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 139
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 14627
telemt_me_reconnect_success_total 11252
telemt_me_reader_eof_total 12008
telemt_me_idle_close_by_peer_total 12008
telemt_me_route_drop_no_conn_total 131656
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 391232
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1346
telemt_desync_full_logged_total 474
telemt_desync_suppressed_total 872
telemt_desync_frames_bucket_total{bucket="1_2"} 329
telemt_desync_frames_bucket_total{bucket="3_10"} 609
telemt_desync_frames_bucket_total{bucket="gt_10"} 408
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 11547
telemt_me_refill_failed_total 101
telemt_me_writer_restored_same_endpoint_total 11243
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 295
telemt_user_connections_total{user="hello"} 392108
telemt_user_connections_current{user="hello"} 844
telemt_user_octets_from_client{user="hello"} 5112239094 (4.76 GB)
telemt_user_octets_to_client{user="hello"} 137742090591 (128.28 GB)
telemt_user_msgs_from_client{user="hello"} 4070
telemt_user_msgs_to_client{user="hello"} 5224
telemt_user_unique_ips_current{user="hello"} 204
telemt_user_unique_ips_recent_window{user="hello"} 120
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 64958.1 (18h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 234817
telemt_connections_bad_total 52795
telemt_handshake_timeouts_total 3135
telemt_upstream_connect_attempt_total 19037
telemt_upstream_connect_success_total 18792
telemt_upstream_connect_fail_total 245
telemt_upstream_connect_attempts_per_request{bucket="1"} 19037
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8398
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10157
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 237
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 245
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 29287
telemt_me_reconnect_success_total 15401
telemt_me_reader_eof_total 16469
telemt_me_idle_close_by_peer_total 16469
telemt_me_route_drop_no_conn_total 62563
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 170827
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1002
telemt_desync_full_logged_total 206
telemt_desync_suppressed_total 796
telemt_desync_frames_bucket_total{bucket="1_2"} 510
telemt_desync_frames_bucket_total{bucket="3_10"} 372
telemt_desync_frames_bucket_total{bucket="gt_10"} 120
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 16034
telemt_me_refill_failed_total 431
telemt_me_writer_restored_same_endpoint_total 15393
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 633
telemt_user_connections_total{user="hello"} 170835
telemt_user_connections_current{user="hello"} 310
telemt_user_octets_from_client{user="hello"} 2278048819 (2.12 GB)
telemt_user_octets_to_client{user="hello"} 68126739334 (63.45 GB)
telemt_user_msgs_from_client{user="hello"} 265
telemt_user_msgs_to_client{user="hello"} 707
telemt_user_unique_ips_current{user="hello"} 98
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 65119.5 (18h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 558348
telemt_connections_bad_total 52088
telemt_handshake_timeouts_total 5178
telemt_upstream_connect_attempt_total 13096
telemt_upstream_connect_success_total 13025
telemt_upstream_connect_fail_total 71
telemt_upstream_connect_attempts_per_request{bucket="1"} 13096
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6445
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6560
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 71
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 13665
telemt_me_reconnect_success_total 9767
telemt_me_reader_eof_total 10520
telemt_me_idle_close_by_peer_total 10520
telemt_me_route_drop_no_conn_total 358862
telemt_me_route_drop_channel_closed_total 27
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 549475
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
telemt_me_writer_removed_unexpected_total 10037
telemt_me_refill_failed_total 120
telemt_me_writer_restored_same_endpoint_total 9753
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 270
telemt_user_connections_total{user="hello"} 471140
telemt_user_connections_current{user="hello"} 930
telemt_user_octets_from_client{user="hello"} 6984706528 (6.51 GB)
telemt_user_octets_to_client{user="hello"} 226777763916 (211.20 GB)
telemt_user_unique_ips_current{user="hello"} 307
telemt_user_unique_ips_recent_window{user="hello"} 130
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 12886.2 (3h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9890
telemt_connections_bad_total 56
telemt_handshake_timeouts_total 40
telemt_upstream_connect_attempt_total 7091
telemt_upstream_connect_success_total 7028
telemt_upstream_connect_fail_total 63
telemt_upstream_connect_attempts_per_request{bucket="1"} 7091
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3763
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3263
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 63
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 9450
telemt_me_reconnect_success_total 6202
telemt_me_reader_eof_total 6489
telemt_me_idle_close_by_peer_total 6489
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 3661
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9510
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
telemt_me_writer_removed_unexpected_total 6364
telemt_me_refill_failed_total 100
telemt_me_writer_restored_same_endpoint_total 6191
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 162
telemt_user_connections_total{user="hello"} 9614
telemt_user_connections_current{user="hello"} 63
telemt_user_octets_from_client{user="hello"} 259572301 (247.55 MB)
telemt_user_octets_to_client{user="hello"} 20427555526 (19.02 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 17
telemt_user_unique_ips_recent_window{user="hello"} 8
```