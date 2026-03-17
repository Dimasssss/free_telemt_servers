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

# Server Metrics 2026-03-17 12:11:13 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 62757.5 (17h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 580721
telemt_connections_bad_total 4793
telemt_handshake_timeouts_total 18196
telemt_upstream_connect_attempt_total 15570
telemt_upstream_connect_success_total 15125
telemt_upstream_connect_fail_total 445
telemt_upstream_connect_attempts_per_request{bucket="1"} 15570
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7972
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7003
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 445
telemt_me_keepalive_timeout_total 111
telemt_me_reconnect_attempts_total 12462
telemt_me_reconnect_success_total 9709
telemt_me_reader_eof_total 10325
telemt_me_idle_close_by_peer_total 10324
telemt_me_route_drop_no_conn_total 188735
telemt_me_route_drop_channel_closed_total 53
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 524366
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4000
telemt_desync_full_logged_total 1066
telemt_desync_suppressed_total 2934
telemt_desync_frames_bucket_total{bucket="1_2"} 1157
telemt_desync_frames_bucket_total{bucket="3_10"} 1666
telemt_desync_frames_bucket_total{bucket="gt_10"} 1177
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 9935
telemt_me_refill_failed_total 81
telemt_me_writer_restored_same_endpoint_total 9687
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 226
telemt_user_connections_total{user="hello"} 526283
telemt_user_connections_current{user="hello"} 950
telemt_user_octets_from_client{user="hello"} 7075951943 (6.59 GB)
telemt_user_octets_to_client{user="hello"} 190096435107 (177.04 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 338
telemt_user_unique_ips_recent_window{user="hello"} 150
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 63010.1 (17h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 329771
telemt_connections_bad_total 15939
telemt_handshake_timeouts_total 18724
telemt_upstream_connect_attempt_total 15941
telemt_upstream_connect_success_total 15718
telemt_upstream_connect_fail_total 223
telemt_upstream_connect_attempts_per_request{bucket="1"} 15941
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6753
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8709
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 256
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 223
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 24945
telemt_me_reconnect_success_total 12610
telemt_me_reader_eof_total 13587
telemt_me_idle_close_by_peer_total 13587
telemt_me_route_drop_no_conn_total 121421
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 278747
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 971
telemt_desync_full_logged_total 332
telemt_desync_suppressed_total 639
telemt_desync_frames_bucket_total{bucket="1_2"} 246
telemt_desync_frames_bucket_total{bucket="3_10"} 409
telemt_desync_frames_bucket_total{bucket="gt_10"} 316
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 13133
telemt_me_refill_failed_total 384
telemt_me_writer_restored_same_endpoint_total 12594
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 523
telemt_user_connections_total{user="hello"} 278733
telemt_user_connections_current{user="hello"} 641
telemt_user_octets_from_client{user="hello"} 3217253020 (3.00 GB)
telemt_user_octets_to_client{user="hello"} 101040560432 (94.10 GB)
telemt_user_unique_ips_current{user="hello"} 183
telemt_user_unique_ips_recent_window{user="hello"} 94
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 62785.2 (17h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 190404
telemt_connections_bad_total 7725
telemt_handshake_timeouts_total 15900
telemt_upstream_connect_attempt_total 16452
telemt_upstream_connect_success_total 16366
telemt_upstream_connect_fail_total 86
telemt_upstream_connect_attempts_per_request{bucket="1"} 16452
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7247
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9044
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 70
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 86
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 15086
telemt_me_reconnect_success_total 13212
telemt_me_reader_eof_total 14115
telemt_me_idle_close_by_peer_total 14115
telemt_me_route_drop_no_conn_total 56839
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 156152
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 582
telemt_desync_full_logged_total 153
telemt_desync_suppressed_total 429
telemt_desync_frames_bucket_total{bucket="1_2"} 238
telemt_desync_frames_bucket_total{bucket="3_10"} 255
telemt_desync_frames_bucket_total{bucket="gt_10"} 89
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 13461
telemt_me_refill_failed_total 56
telemt_me_writer_restored_same_endpoint_total 13201
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 249
telemt_user_connections_total{user="hello"} 156050
telemt_user_connections_current{user="hello"} 315
telemt_user_octets_from_client{user="hello"} 14916034580 (13.89 GB)
telemt_user_octets_to_client{user="hello"} 44263486980 (41.22 GB)
telemt_user_unique_ips_current{user="hello"} 122
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 62844.5 (17h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 434113
telemt_connections_bad_total 7184
telemt_handshake_timeouts_total 12252
telemt_upstream_connect_attempt_total 15186
telemt_upstream_connect_success_total 15050
telemt_upstream_connect_fail_total 136
telemt_upstream_connect_attempts_per_request{bucket="1"} 15186
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7448
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7505
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 88
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 136
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 14331
telemt_me_reconnect_success_total 10961
telemt_me_reader_eof_total 11705
telemt_me_idle_close_by_peer_total 11705
telemt_me_route_drop_no_conn_total 122433
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 362579
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1157
telemt_desync_full_logged_total 415
telemt_desync_suppressed_total 742
telemt_desync_frames_bucket_total{bucket="1_2"} 284
telemt_desync_frames_bucket_total{bucket="3_10"} 506
telemt_desync_frames_bucket_total{bucket="gt_10"} 367
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 11244
telemt_me_refill_failed_total 101
telemt_me_writer_restored_same_endpoint_total 10952
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 283
telemt_user_connections_total{user="hello"} 363395
telemt_user_connections_current{user="hello"} 724
telemt_user_octets_from_client{user="hello"} 4688217505 (4.37 GB)
telemt_user_octets_to_client{user="hello"} 130147926833 (121.21 GB)
telemt_user_msgs_from_client{user="hello"} 3934
telemt_user_msgs_to_client{user="hello"} 4814
telemt_user_unique_ips_current{user="hello"} 201
telemt_user_unique_ips_recent_window{user="hello"} 110
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 62816.3 (17h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 223199
telemt_connections_bad_total 52413
telemt_handshake_timeouts_total 3096
telemt_upstream_connect_attempt_total 18380
telemt_upstream_connect_success_total 18141
telemt_upstream_connect_fail_total 239
telemt_upstream_connect_attempts_per_request{bucket="1"} 18380
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8123
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9783
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 235
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 239
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 28547
telemt_me_reconnect_success_total 14888
telemt_me_reader_eof_total 15939
telemt_me_idle_close_by_peer_total 15939
telemt_me_route_drop_no_conn_total 58623
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 160118
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 935
telemt_desync_full_logged_total 185
telemt_desync_suppressed_total 750
telemt_desync_frames_bucket_total{bucket="1_2"} 487
telemt_desync_frames_bucket_total{bucket="3_10"} 344
telemt_desync_frames_bucket_total{bucket="gt_10"} 104
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 15502
telemt_me_refill_failed_total 424
telemt_me_writer_restored_same_endpoint_total 14880
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 614
telemt_user_connections_total{user="hello"} 160133
telemt_user_connections_current{user="hello"} 312
telemt_user_octets_from_client{user="hello"} 2167029155 (2.02 GB)
telemt_user_octets_to_client{user="hello"} 66069878386 (61.53 GB)
telemt_user_msgs_from_client{user="hello"} 265
telemt_user_msgs_to_client{user="hello"} 707
telemt_user_unique_ips_current{user="hello"} 104
telemt_user_unique_ips_recent_window{user="hello"} 52
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 62977.6 (17h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 528312
telemt_connections_bad_total 51952
telemt_handshake_timeouts_total 4879
telemt_upstream_connect_attempt_total 12659
telemt_upstream_connect_success_total 12591
telemt_upstream_connect_fail_total 68
telemt_upstream_connect_attempts_per_request{bucket="1"} 12659
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6226
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6345
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 68
telemt_me_keepalive_timeout_total 32
telemt_me_reconnect_attempts_total 13362
telemt_me_reconnect_success_total 9468
telemt_me_reader_eof_total 10208
telemt_me_idle_close_by_peer_total 10208
telemt_me_route_drop_no_conn_total 346883
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 520877
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 796
telemt_desync_full_logged_total 293
telemt_desync_suppressed_total 503
telemt_desync_frames_bucket_total{bucket="1_2"} 205
telemt_desync_frames_bucket_total{bucket="3_10"} 304
telemt_desync_frames_bucket_total{bucket="gt_10"} 287
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 9736
telemt_me_refill_failed_total 120
telemt_me_writer_restored_same_endpoint_total 9454
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 268
telemt_user_connections_total{user="hello"} 442560
telemt_user_connections_current{user="hello"} 882
telemt_user_octets_from_client{user="hello"} 6648030324 (6.19 GB)
telemt_user_octets_to_client{user="hello"} 217834147320 (202.87 GB)
telemt_user_unique_ips_current{user="hello"} 296
telemt_user_unique_ips_recent_window{user="hello"} 131
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 10744.4 (2h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8373
telemt_connections_bad_total 46
telemt_handshake_timeouts_total 37
telemt_upstream_connect_attempt_total 5997
telemt_upstream_connect_success_total 5946
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 5997
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3207
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2739
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 8498
telemt_me_reconnect_success_total 5256
telemt_me_reader_eof_total 5513
telemt_me_idle_close_by_peer_total 5513
telemt_me_seq_mismatch_total 5
telemt_me_route_drop_no_conn_total 3168
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8024
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
telemt_me_writer_removed_unexpected_total 5407
telemt_me_refill_failed_total 100
telemt_me_writer_restored_same_endpoint_total 5247
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 151
telemt_user_connections_total{user="hello"} 8130
telemt_user_connections_current{user="hello"} 94
telemt_user_octets_from_client{user="hello"} 166390905 (158.68 MB)
telemt_user_octets_to_client{user="hello"} 19573666774 (18.23 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 21
telemt_user_unique_ips_recent_window{user="hello"} 10
```