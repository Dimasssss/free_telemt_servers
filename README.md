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

# Server Metrics 2026-03-17 14:08:43 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 69806.7 (19h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 723478
telemt_connections_bad_total 5694
telemt_handshake_timeouts_total 20768
telemt_upstream_connect_attempt_total 17061
telemt_upstream_connect_success_total 16606
telemt_upstream_connect_fail_total 455
telemt_upstream_connect_attempts_per_request{bucket="1"} 17061
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8693
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7763
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 455
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 121
telemt_me_reconnect_attempts_total 20002
telemt_me_reconnect_success_total 10813
telemt_me_reader_eof_total 11656
telemt_me_idle_close_by_peer_total 11655
telemt_me_route_drop_no_conn_total 278536
telemt_me_route_drop_channel_closed_total 72
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 657290
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4623
telemt_desync_full_logged_total 1301
telemt_desync_suppressed_total 3322
telemt_desync_frames_bucket_total{bucket="1_2"} 1294
telemt_desync_frames_bucket_total{bucket="3_10"} 1895
telemt_desync_frames_bucket_total{bucket="gt_10"} 1434
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 11253
telemt_me_refill_failed_total 282
telemt_me_writer_restored_same_endpoint_total 10791
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 440
telemt_user_connections_total{user="hello"} 659172
telemt_user_connections_current{user="hello"} 1014
telemt_user_octets_from_client{user="hello"} 10831394715 (10.09 GB)
telemt_user_octets_to_client{user="hello"} 223902571923 (208.53 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 347
telemt_user_unique_ips_recent_window{user="hello"} 165
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 70058.1 (19h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 450963
telemt_connections_bad_total 28282
telemt_handshake_timeouts_total 22609
telemt_upstream_connect_attempt_total 37321
telemt_upstream_connect_success_total 36937
telemt_upstream_connect_fail_total 383
telemt_upstream_connect_attempts_per_request{bucket="1"} 37320
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24049
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10140
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2748
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 383
telemt_me_keepalive_timeout_total 326
telemt_me_reconnect_attempts_total 31753
telemt_me_reconnect_success_total 13349
telemt_me_reader_eof_total 14487
telemt_me_idle_close_by_peer_total 14487
telemt_me_route_drop_no_conn_total 186951
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 357854
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1427
telemt_desync_full_logged_total 450
telemt_desync_suppressed_total 977
telemt_desync_frames_bucket_total{bucket="1_2"} 318
telemt_desync_frames_bucket_total{bucket="3_10"} 623
telemt_desync_frames_bucket_total{bucket="gt_10"} 486
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 14087
telemt_me_refill_failed_total 571
telemt_me_writer_restored_same_endpoint_total 13333
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 738
telemt_user_connections_total{user="hello"} 377846
telemt_user_connections_current{user="hello"} 629
telemt_user_octets_from_client{user="hello"} 4120280079 (3.84 GB)
telemt_user_octets_to_client{user="hello"} 120898674568 (112.60 GB)
telemt_user_msgs_from_client{user="hello"} 320422
telemt_user_msgs_to_client{user="hello"} 918947
telemt_user_unique_ips_current{user="hello"} 179
telemt_user_unique_ips_recent_window{user="hello"} 86
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 69833.9 (19h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 237774
telemt_connections_bad_total 7809
telemt_handshake_timeouts_total 16907
telemt_upstream_connect_attempt_total 18471
telemt_upstream_connect_success_total 18377
telemt_upstream_connect_fail_total 94
telemt_upstream_connect_attempts_per_request{bucket="1"} 18471
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8182
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10118
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 94
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 21773
telemt_me_reconnect_success_total 14835
telemt_me_reader_eof_total 15924
telemt_me_idle_close_by_peer_total 15924
telemt_me_route_drop_no_conn_total 95710
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 200605
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 748
telemt_desync_full_logged_total 213
telemt_desync_suppressed_total 535
telemt_desync_frames_bucket_total{bucket="1_2"} 275
telemt_desync_frames_bucket_total{bucket="3_10"} 332
telemt_desync_frames_bucket_total{bucket="gt_10"} 141
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 15259
telemt_me_refill_failed_total 214
telemt_me_writer_restored_same_endpoint_total 14824
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 424
telemt_user_connections_total{user="hello"} 200478
telemt_user_connections_current{user="hello"} 338
telemt_user_octets_from_client{user="hello"} 15404117720 (14.35 GB)
telemt_user_octets_to_client{user="hello"} 53131258036 (49.48 GB)
telemt_user_unique_ips_current{user="hello"} 117
telemt_user_unique_ips_recent_window{user="hello"} 60
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 69893.4 (19h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 545709
telemt_connections_bad_total 8102
telemt_handshake_timeouts_total 12999
telemt_upstream_connect_attempt_total 16482
telemt_upstream_connect_success_total 16332
telemt_upstream_connect_fail_total 150
telemt_upstream_connect_attempts_per_request{bucket="1"} 16482
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8172
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8043
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 108
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 150
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 21153
telemt_me_reconnect_success_total 11782
telemt_me_reader_eof_total 12733
telemt_me_idle_close_by_peer_total 12733
telemt_me_route_drop_no_conn_total 178389
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 466208
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1610
telemt_desync_full_logged_total 554
telemt_desync_suppressed_total 1056
telemt_desync_frames_bucket_total{bucket="1_2"} 404
telemt_desync_frames_bucket_total{bucket="3_10"} 721
telemt_desync_frames_bucket_total{bucket="gt_10"} 485
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 12280
telemt_me_refill_failed_total 288
telemt_me_writer_restored_same_endpoint_total 11773
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 498
telemt_user_connections_total{user="hello"} 467041
telemt_user_connections_current{user="hello"} 866
telemt_user_octets_from_client{user="hello"} 5812384194 (5.41 GB)
telemt_user_octets_to_client{user="hello"} 155279795127 (144.62 GB)
telemt_user_msgs_from_client{user="hello"} 4070
telemt_user_msgs_to_client{user="hello"} 5224
telemt_user_unique_ips_current{user="hello"} 226
telemt_user_unique_ips_recent_window{user="hello"} 155
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 69865.2 (19h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 268191
telemt_connections_bad_total 56617
telemt_handshake_timeouts_total 3377
telemt_upstream_connect_attempt_total 20446
telemt_upstream_connect_success_total 19995
telemt_upstream_connect_fail_total 451
telemt_upstream_connect_attempts_per_request{bucket="1"} 20446
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9039
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10676
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 280
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 451
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 36105
telemt_me_reconnect_success_total 16087
telemt_me_reader_eof_total 17298
telemt_me_idle_close_by_peer_total 17296
telemt_me_route_drop_no_conn_total 75681
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 197298
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
telemt_me_writer_removed_unexpected_total 16983
telemt_me_refill_failed_total 621
telemt_me_writer_restored_same_endpoint_total 16079
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 896
telemt_user_connections_total{user="hello"} 197751
telemt_user_connections_current{user="hello"} 295
telemt_user_octets_from_client{user="hello"} 2558273487 (2.38 GB)
telemt_user_octets_to_client{user="hello"} 72634951995 (67.65 GB)
telemt_user_msgs_from_client{user="hello"} 1159
telemt_user_msgs_to_client{user="hello"} 2341
telemt_user_unique_ips_current{user="hello"} 93
telemt_user_unique_ips_recent_window{user="hello"} 52
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 70027.9 (19h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 641806
telemt_connections_bad_total 53641
telemt_handshake_timeouts_total 6334
telemt_upstream_connect_attempt_total 14072
telemt_upstream_connect_success_total 13997
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 14072
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6903
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7071
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 19530
telemt_me_reconnect_success_total 10498
telemt_me_reader_eof_total 11419
telemt_me_idle_close_by_peer_total 11419
telemt_me_route_drop_no_conn_total 447905
telemt_me_route_drop_channel_closed_total 35
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 644494
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 855
telemt_desync_full_logged_total 318
telemt_desync_suppressed_total 537
telemt_desync_frames_bucket_total{bucket="1_2"} 215
telemt_desync_frames_bucket_total{bucket="3_10"} 332
telemt_desync_frames_bucket_total{bucket="gt_10"} 308
telemt_pool_swap_total 60
telemt_me_writer_removed_unexpected_total 10940
telemt_me_refill_failed_total 280
telemt_me_writer_restored_same_endpoint_total 10484
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 442
telemt_user_connections_total{user="hello"} 548976
telemt_user_connections_current{user="hello"} 924
telemt_user_octets_from_client{user="hello"} 8312746392 (7.74 GB)
telemt_user_octets_to_client{user="hello"} 252162683128 (234.84 GB)
telemt_user_unique_ips_current{user="hello"} 311
telemt_user_unique_ips_recent_window{user="hello"} 141
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 17793.3 (4h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14286
telemt_connections_bad_total 62
telemt_handshake_timeouts_total 127
telemt_upstream_connect_attempt_total 10058
telemt_upstream_connect_success_total 9977
telemt_upstream_connect_fail_total 81
telemt_upstream_connect_attempts_per_request{bucket="1"} 10058
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5439
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4529
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 81
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 17999
telemt_me_reconnect_success_total 8918
telemt_me_reader_eof_total 9401
telemt_me_idle_close_by_peer_total 9401
telemt_me_seq_mismatch_total 10
telemt_me_route_drop_no_conn_total 4993
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13728
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
telemt_me_writer_removed_unexpected_total 9288
telemt_me_refill_failed_total 282
telemt_me_writer_restored_same_endpoint_total 8903
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 370
telemt_user_connections_total{user="hello"} 13829
telemt_user_connections_current{user="hello"} 71
telemt_user_octets_from_client{user="hello"} 386208345 (368.32 MB)
telemt_user_octets_to_client{user="hello"} 22440100094 (20.90 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 18
telemt_user_unique_ips_recent_window{user="hello"} 9
```