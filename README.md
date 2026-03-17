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

# Server Metrics 2026-03-17 11:40:40 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 60924.2 (16h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 549350
telemt_connections_bad_total 4648
telemt_handshake_timeouts_total 16321
telemt_upstream_connect_attempt_total 15049
telemt_upstream_connect_success_total 14607
telemt_upstream_connect_fail_total 442
telemt_upstream_connect_attempts_per_request{bucket="1"} 15049
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7712
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6745
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 442
telemt_me_keepalive_timeout_total 110
telemt_me_reconnect_attempts_total 10816
telemt_me_reconnect_success_total 9281
telemt_me_reader_eof_total 9855
telemt_me_idle_close_by_peer_total 9854
telemt_me_route_drop_no_conn_total 179364
telemt_me_route_drop_channel_closed_total 49
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 496160
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3917
telemt_desync_full_logged_total 1036
telemt_desync_suppressed_total 2881
telemt_desync_frames_bucket_total{bucket="1_2"} 1134
telemt_desync_frames_bucket_total{bucket="3_10"} 1630
telemt_desync_frames_bucket_total{bucket="gt_10"} 1153
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 9464
telemt_me_refill_failed_total 43
telemt_me_writer_restored_same_endpoint_total 9259
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 183
telemt_user_connections_total{user="hello"} 498092
telemt_user_connections_current{user="hello"} 976
telemt_user_octets_from_client{user="hello"} 6795958891 (6.33 GB)
telemt_user_octets_to_client{user="hello"} 181665083419 (169.19 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 331
telemt_user_unique_ips_recent_window{user="hello"} 126
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 61175.4 (16h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 307320
telemt_connections_bad_total 12631
telemt_handshake_timeouts_total 17685
telemt_upstream_connect_attempt_total 15409
telemt_upstream_connect_success_total 15191
telemt_upstream_connect_fail_total 218
telemt_upstream_connect_attempts_per_request{bucket="1"} 15409
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6555
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8418
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 218
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 218
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 24505
telemt_me_reconnect_success_total 12170
telemt_me_reader_eof_total 13142
telemt_me_idle_close_by_peer_total 13142
telemt_me_route_drop_no_conn_total 114150
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 261932
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 804
telemt_desync_full_logged_total 287
telemt_desync_suppressed_total 517
telemt_desync_frames_bucket_total{bucket="1_2"} 227
telemt_desync_frames_bucket_total{bucket="3_10"} 342
telemt_desync_frames_bucket_total{bucket="gt_10"} 235
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 12688
telemt_me_refill_failed_total 384
telemt_me_writer_restored_same_endpoint_total 12154
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 518
telemt_user_connections_total{user="hello"} 261924
telemt_user_connections_current{user="hello"} 508
telemt_user_octets_from_client{user="hello"} 3081433220 (2.87 GB)
telemt_user_octets_to_client{user="hello"} 94756325012 (88.25 GB)
telemt_user_unique_ips_current{user="hello"} 170
telemt_user_unique_ips_recent_window{user="hello"} 77
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 60951.6 (16h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 180880
telemt_connections_bad_total 7721
telemt_handshake_timeouts_total 14833
telemt_upstream_connect_attempt_total 15994
telemt_upstream_connect_success_total 15912
telemt_upstream_connect_fail_total 82
telemt_upstream_connect_attempts_per_request{bucket="1"} 15994
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7040
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8801
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 68
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 82
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 14720
telemt_me_reconnect_success_total 12848
telemt_me_reader_eof_total 13730
telemt_me_idle_close_by_peer_total 13730
telemt_me_route_drop_no_conn_total 54021
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 147942
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 543
telemt_desync_full_logged_total 143
telemt_desync_suppressed_total 400
telemt_desync_frames_bucket_total{bucket="1_2"} 235
telemt_desync_frames_bucket_total{bucket="3_10"} 232
telemt_desync_frames_bucket_total{bucket="gt_10"} 76
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 13088
telemt_me_refill_failed_total 56
telemt_me_writer_restored_same_endpoint_total 12837
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 240
telemt_user_connections_total{user="hello"} 147844
telemt_user_connections_current{user="hello"} 299
telemt_user_octets_from_client{user="hello"} 14142471732 (13.17 GB)
telemt_user_octets_to_client{user="hello"} 42555356976 (39.63 GB)
telemt_user_unique_ips_current{user="hello"} 110
telemt_user_unique_ips_recent_window{user="hello"} 59
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 61010.8 (16h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 408908
telemt_connections_bad_total 6816
telemt_handshake_timeouts_total 12135
telemt_upstream_connect_attempt_total 13930
telemt_upstream_connect_success_total 13800
telemt_upstream_connect_fail_total 130
telemt_upstream_connect_attempts_per_request{bucket="1"} 13930
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6469
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7243
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 80
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 130
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 12717
telemt_me_reconnect_success_total 10694
telemt_me_reader_eof_total 11379
telemt_me_idle_close_by_peer_total 11379
telemt_me_route_drop_no_conn_total 115028
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 339933
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1010
telemt_desync_full_logged_total 367
telemt_desync_suppressed_total 643
telemt_desync_frames_bucket_total{bucket="1_2"} 240
telemt_desync_frames_bucket_total{bucket="3_10"} 434
telemt_desync_frames_bucket_total{bucket="gt_10"} 336
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 10930
telemt_me_refill_failed_total 59
telemt_me_writer_restored_same_endpoint_total 10685
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 236
telemt_user_connections_total{user="hello"} 339866
telemt_user_connections_current{user="hello"} 683
telemt_user_octets_from_client{user="hello"} 4437257710 (4.13 GB)
telemt_user_octets_to_client{user="hello"} 123366195269 (114.89 GB)
telemt_user_msgs_from_client{user="hello"} 65
telemt_user_msgs_to_client{user="hello"} 189
telemt_user_unique_ips_current{user="hello"} 205
telemt_user_unique_ips_recent_window{user="hello"} 101
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 60983.0 (16h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 214573
telemt_connections_bad_total 52083
telemt_handshake_timeouts_total 3049
telemt_upstream_connect_attempt_total 17932
telemt_upstream_connect_success_total 17697
telemt_upstream_connect_fail_total 235
telemt_upstream_connect_attempts_per_request{bucket="1"} 17932
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7939
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9544
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 214
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 235
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 28188
telemt_me_reconnect_success_total 14533
telemt_me_reader_eof_total 15566
telemt_me_idle_close_by_peer_total 15566
telemt_me_route_drop_no_conn_total 56478
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 152289
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 902
telemt_desync_full_logged_total 177
telemt_desync_suppressed_total 725
telemt_desync_frames_bucket_total{bucket="1_2"} 474
telemt_desync_frames_bucket_total{bucket="3_10"} 327
telemt_desync_frames_bucket_total{bucket="gt_10"} 101
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 15139
telemt_me_refill_failed_total 424
telemt_me_writer_restored_same_endpoint_total 14525
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 606
telemt_user_connections_total{user="hello"} 152304
telemt_user_connections_current{user="hello"} 270
telemt_user_octets_from_client{user="hello"} 2116173847 (1.97 GB)
telemt_user_octets_to_client{user="hello"} 64407773846 (59.98 GB)
telemt_user_msgs_from_client{user="hello"} 265
telemt_user_msgs_to_client{user="hello"} 707
telemt_user_unique_ips_current{user="hello"} 86
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 61144.5 (16h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 504541
telemt_connections_bad_total 51682
telemt_handshake_timeouts_total 4729
telemt_upstream_connect_attempt_total 12356
telemt_upstream_connect_success_total 12290
telemt_upstream_connect_fail_total 66
telemt_upstream_connect_attempts_per_request{bucket="1"} 12356
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6075
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6195
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 66
telemt_me_keepalive_timeout_total 31
telemt_me_reconnect_attempts_total 13149
telemt_me_reconnect_success_total 9256
telemt_me_reader_eof_total 9980
telemt_me_idle_close_by_peer_total 9980
telemt_me_route_drop_no_conn_total 336902
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 498533
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 746
telemt_desync_full_logged_total 278
telemt_desync_suppressed_total 468
telemt_desync_frames_bucket_total{bucket="1_2"} 197
telemt_desync_frames_bucket_total{bucket="3_10"} 292
telemt_desync_frames_bucket_total{bucket="gt_10"} 257
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 9522
telemt_me_refill_failed_total 120
telemt_me_writer_restored_same_endpoint_total 9242
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 266
telemt_user_connections_total{user="hello"} 420222
telemt_user_connections_current{user="hello"} 862
telemt_user_octets_from_client{user="hello"} 6192645508 (5.77 GB)
telemt_user_octets_to_client{user="hello"} 212850379268 (198.23 GB)
telemt_user_unique_ips_current{user="hello"} 297
telemt_user_unique_ips_recent_window{user="hello"} 110
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 8910.9 (2h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6576
telemt_connections_bad_total 42
telemt_handshake_timeouts_total 34
telemt_upstream_connect_attempt_total 5016
telemt_upstream_connect_success_total 4972
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 5016
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2656
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2316
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 6491
telemt_me_reconnect_success_total 4373
telemt_me_reader_eof_total 4541
telemt_me_idle_close_by_peer_total 4541
telemt_me_seq_mismatch_total 5
telemt_me_route_drop_no_conn_total 2488
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6257
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 4483
telemt_me_refill_failed_total 65
telemt_me_writer_restored_same_endpoint_total 4364
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 110
telemt_user_connections_total{user="hello"} 6363
telemt_user_connections_current{user="hello"} 101
telemt_user_octets_from_client{user="hello"} 149914313 (142.97 MB)
telemt_user_octets_to_client{user="hello"} 19172580562 (17.86 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 9
```