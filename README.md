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

# Server Metrics 2026-03-17 22:23:43 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 99506.4 (27h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1207623
telemt_connections_bad_total 8727
telemt_handshake_timeouts_total 31675
telemt_upstream_connect_attempt_total 22520
telemt_upstream_connect_success_total 22026
telemt_upstream_connect_fail_total 494
telemt_upstream_connect_attempts_per_request{bucket="1"} 22520
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11356
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10462
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 494
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 31890
telemt_me_reconnect_success_total 14758
telemt_me_reader_eof_total 16037
telemt_me_idle_close_by_peer_total 16036
telemt_me_route_drop_no_conn_total 537868
telemt_me_route_drop_channel_closed_total 155
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1108352
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7316
telemt_desync_full_logged_total 2118
telemt_desync_suppressed_total 5198
telemt_desync_frames_bucket_total{bucket="1_2"} 1955
telemt_desync_frames_bucket_total{bucket="3_10"} 2762
telemt_desync_frames_bucket_total{bucket="gt_10"} 2599
telemt_pool_swap_total 79
telemt_me_writer_removed_unexpected_total 15510
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 14736
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 752
telemt_user_connections_total{user="hello"} 1102577
telemt_user_connections_current{user="hello"} 522
telemt_user_octets_from_client{user="hello"} 20102308215 (18.72 GB)
telemt_user_octets_to_client{user="hello"} 395044071091 (367.91 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 210
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 99757.5 (27h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1275006
telemt_connections_bad_total 60285
telemt_handshake_timeouts_total 44910
telemt_upstream_connect_attempt_total 457929
telemt_upstream_connect_success_total 457029
telemt_upstream_connect_fail_total 900
telemt_upstream_connect_attempts_per_request{bucket="1"} 457929
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 382979
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30757
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43291
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 900
telemt_me_keepalive_timeout_total 342
telemt_me_reconnect_attempts_total 58212
telemt_me_reconnect_success_total 15056
telemt_me_reader_eof_total 17053
telemt_me_idle_close_by_peer_total 17053
telemt_me_route_drop_no_conn_total 329659
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 668029
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2983
telemt_desync_full_logged_total 971
telemt_desync_suppressed_total 2012
telemt_desync_frames_bucket_total{bucket="1_2"} 568
telemt_desync_frames_bucket_total{bucket="3_10"} 1223
telemt_desync_frames_bucket_total{bucket="gt_10"} 1192
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 16591
telemt_me_refill_failed_total 1344
telemt_me_writer_restored_same_endpoint_total 15040
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 1535
telemt_user_connections_total{user="hello"} 1104464
telemt_user_connections_current{user="hello"} 780
telemt_user_octets_from_client{user="hello"} 15189918154 (14.15 GB)
telemt_user_octets_to_client{user="hello"} 374284261486 (348.58 GB)
telemt_user_msgs_from_client{user="hello"} 7417237
telemt_user_msgs_to_client{user="hello"} 31692884
telemt_user_unique_ips_current{user="hello"} 282
telemt_user_unique_ips_recent_window{user="hello"} 66
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 99533.6 (27h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 734643
telemt_connections_bad_total 45297
telemt_handshake_timeouts_total 23295
telemt_upstream_connect_attempt_total 23595
telemt_upstream_connect_success_total 23456
telemt_upstream_connect_fail_total 139
telemt_upstream_connect_attempts_per_request{bucket="1"} 23595
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10744
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12618
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 139
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 39114
telemt_me_reconnect_success_total 18435
telemt_me_reader_eof_total 20105
telemt_me_idle_close_by_peer_total 20098
telemt_me_route_drop_no_conn_total 305296
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 629874
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2083
telemt_desync_full_logged_total 656
telemt_desync_suppressed_total 1427
telemt_desync_frames_bucket_total{bucket="1_2"} 578
telemt_desync_frames_bucket_total{bucket="3_10"} 810
telemt_desync_frames_bucket_total{bucket="gt_10"} 695
telemt_pool_swap_total 76
telemt_me_writer_removed_unexpected_total 19333
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 18423
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 898
telemt_user_connections_total{user="hello"} 628138
telemt_user_connections_current{user="hello"} 744
telemt_user_octets_from_client{user="hello"} 30905222752 (28.78 GB)
telemt_user_octets_to_client{user="hello"} 273371700912 (254.60 GB)
telemt_user_unique_ips_current{user="hello"} 246
telemt_user_unique_ips_recent_window{user="hello"} 55
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 99593.1 (27h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1230019
telemt_connections_bad_total 42966
telemt_handshake_timeouts_total 21576
telemt_upstream_connect_attempt_total 83220
telemt_upstream_connect_success_total 82789
telemt_upstream_connect_fail_total 431
telemt_upstream_connect_attempts_per_request{bucket="1"} 83220
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 70075
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12340
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 29
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 345
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 431
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 315
telemt_me_reconnect_attempts_total 34762
telemt_me_reconnect_success_total 14440
telemt_me_reader_eof_total 15919
telemt_me_idle_close_by_peer_total 15917
telemt_me_route_drop_no_conn_total 508069
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1005180
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3697
telemt_desync_full_logged_total 1207
telemt_desync_suppressed_total 2490
telemt_desync_frames_bucket_total{bucket="1_2"} 905
telemt_desync_frames_bucket_total{bucket="3_10"} 1550
telemt_desync_frames_bucket_total{bucket="gt_10"} 1242
telemt_pool_swap_total 74
telemt_me_writer_removed_unexpected_total 15342
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 14431
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 902
telemt_user_connections_total{user="hello"} 1067676
telemt_user_connections_current{user="hello"} 729
telemt_user_octets_from_client{user="hello"} 16735272427 (15.59 GB)
telemt_user_octets_to_client{user="hello"} 468681147841 (436.49 GB)
telemt_user_msgs_from_client{user="hello"} 734453
telemt_user_msgs_to_client{user="hello"} 5166140
telemt_user_unique_ips_current{user="hello"} 243
telemt_user_unique_ips_recent_window{user="hello"} 62
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 99565.0 (27h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 787551
telemt_connections_bad_total 94157
telemt_handshake_timeouts_total 6415
telemt_upstream_connect_attempt_total 42165
telemt_upstream_connect_success_total 41595
telemt_upstream_connect_fail_total 570
telemt_upstream_connect_attempts_per_request{bucket="1"} 42165
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26598
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14597
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 400
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 570
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 55085
telemt_me_reconnect_success_total 20134
telemt_me_reader_eof_total 21955
telemt_me_idle_close_by_peer_total 21953
telemt_me_route_drop_no_conn_total 249130
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 629936
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2874
telemt_desync_full_logged_total 850
telemt_desync_suppressed_total 2024
telemt_desync_frames_bucket_total{bucket="1_2"} 920
telemt_desync_frames_bucket_total{bucket="3_10"} 1155
telemt_desync_frames_bucket_total{bucket="gt_10"} 799
telemt_pool_swap_total 49
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 21566
telemt_me_refill_failed_total 1087
telemt_me_writer_restored_same_endpoint_total 20126
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1432
telemt_user_connections_total{user="hello"} 646546
telemt_user_connections_current{user="hello"} 659
telemt_user_octets_from_client{user="hello"} 12463044556 (11.61 GB)
telemt_user_octets_to_client{user="hello"} 319801716464 (297.84 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 240
telemt_user_unique_ips_recent_window{user="hello"} 66
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 99725.8 (27h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1019658
telemt_connections_bad_total 82412
telemt_handshake_timeouts_total 9500
telemt_upstream_connect_attempt_total 19701
telemt_upstream_connect_success_total 19588
telemt_upstream_connect_fail_total 113
telemt_upstream_connect_attempts_per_request{bucket="1"} 19701
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9355
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10116
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 107
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 113
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 25895
telemt_me_reconnect_success_total 14617
telemt_me_reader_eof_total 15873
telemt_me_idle_close_by_peer_total 15871
telemt_me_route_drop_no_conn_total 691974
telemt_me_route_drop_channel_closed_total 86
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1000904
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2081
telemt_desync_full_logged_total 724
telemt_desync_suppressed_total 1357
telemt_desync_frames_bucket_total{bucket="1_2"} 461
telemt_desync_frames_bucket_total{bucket="3_10"} 786
telemt_desync_frames_bucket_total{bucket="gt_10"} 834
telemt_pool_swap_total 85
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 15211
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 14603
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 594
telemt_user_connections_total{user="hello"} 863933
telemt_user_connections_current{user="hello"} 468
telemt_user_octets_from_client{user="hello"} 13370292340 (12.45 GB)
telemt_user_octets_to_client{user="hello"} 367813281560 (342.55 GB)
telemt_user_unique_ips_current{user="hello"} 177
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 47493.2 (13h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 355195
telemt_connections_bad_total 44386
telemt_handshake_timeouts_total 10552
telemt_upstream_connect_attempt_total 18473
telemt_upstream_connect_success_total 18299
telemt_upstream_connect_fail_total 174
telemt_upstream_connect_attempts_per_request{bucket="1"} 18473
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9780
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8426
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 93
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 174
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 27359
telemt_me_reconnect_success_total 15765
telemt_me_reader_eof_total 16661
telemt_me_idle_close_by_peer_total 16661
telemt_me_seq_mismatch_total 21
telemt_me_route_drop_no_conn_total 88427
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 269338
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 920
telemt_desync_full_logged_total 278
telemt_desync_suppressed_total 642
telemt_desync_frames_bucket_total{bucket="1_2"} 212
telemt_desync_frames_bucket_total{bucket="3_10"} 371
telemt_desync_frames_bucket_total{bucket="gt_10"} 337
telemt_pool_swap_total 26
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 16311
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 15736
telemt_me_writer_restored_fallback_total 29
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 546
telemt_user_connections_total{user="hello"} 269277
telemt_user_connections_current{user="hello"} 383
telemt_user_octets_from_client{user="hello"} 21295108649 (19.83 GB)
telemt_user_octets_to_client{user="hello"} 221473687854 (206.26 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 146
telemt_user_unique_ips_recent_window{user="hello"} 33
```