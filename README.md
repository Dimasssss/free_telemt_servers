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

# Server Metrics 2026-03-18 15:02:16 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.20

telemt_uptime_seconds 22875.6 (6h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 855260
telemt_connections_bad_total 64333
telemt_handshake_timeouts_total 23760
telemt_upstream_connect_attempt_total 67251
telemt_upstream_connect_success_total 66278
telemt_upstream_connect_fail_total 973
telemt_upstream_connect_attempts_per_request{bucket="1"} 67251
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 61028
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4667
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 583
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 973
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 519991
telemt_me_reconnect_success_total 3125
telemt_me_reader_eof_total 3461
telemt_me_idle_close_by_peer_total 3459
telemt_me_route_drop_no_conn_total 462703
telemt_me_route_drop_channel_closed_total 179
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 652914
telemt_me_writer_pick_total{mode="p2c",result="full"} 21
telemt_me_writer_pick_total{mode="p2c",result="closed"} 54
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2951
telemt_desync_full_logged_total 1020
telemt_desync_suppressed_total 1931
telemt_desync_frames_bucket_total{bucket="1_2"} 827
telemt_desync_frames_bucket_total{bucket="3_10"} 992
telemt_desync_frames_bucket_total{bucket="gt_10"} 1132
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 3466
telemt_me_refill_failed_total 16834
telemt_me_writer_restored_same_endpoint_total 3019
telemt_me_writer_restored_fallback_total 106
telemt_me_async_recovery_trigger_total 11769
telemt_me_writer_removed_unexpected_minus_restored_total 341
telemt_user_connections_total{user="hello"} 710993
telemt_user_connections_current{user="hello"} 1664
telemt_user_octets_from_client{user="hello"} 10542204120 (9.82 GB)
telemt_user_octets_to_client{user="hello"} 187109788469 (174.26 GB)
telemt_user_msgs_from_client{user="hello"} 846607
telemt_user_msgs_to_client{user="hello"} 1165163
telemt_user_unique_ips_current{user="hello"} 537
telemt_user_unique_ips_recent_window{user="hello"} 267
```

## psb.hosting

```
telemt 3.3.22

telemt_uptime_seconds 3443.7 (0h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 353648
telemt_connections_bad_total 20891
telemt_connections_current 4143
telemt_connections_me_current 4143
telemt_handshake_timeouts_total 8158
telemt_upstream_connect_attempt_total 538
telemt_upstream_connect_success_total 535
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 538
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 325
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 337
telemt_me_reconnect_success_total 332
telemt_me_reader_eof_total 239
telemt_me_idle_close_by_peer_total 238
telemt_me_route_drop_no_conn_total 200000
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 307439
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 982
telemt_desync_full_logged_total 281
telemt_desync_suppressed_total 701
telemt_desync_frames_bucket_total{bucket="1_2"} 219
telemt_desync_frames_bucket_total{bucket="3_10"} 395
telemt_desync_frames_bucket_total{bucket="gt_10"} 368
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 252
telemt_me_writer_restored_same_endpoint_total 330
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 2874
telemt_user_connections_total{user="hello"} 306686
telemt_user_connections_current{user="hello"} 4143
telemt_user_octets_from_client{user="hello"} 3333982896 (3.11 GB)
telemt_user_octets_to_client{user="hello"} 97669519760 (90.96 GB)
telemt_user_unique_ips_current{user="hello"} 1298
telemt_user_unique_ips_recent_window{user="hello"} 758
```

## koara.io

```
telemt 3.3.22

telemt_uptime_seconds 3372.4 (0h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 241912
telemt_connections_bad_total 15160
telemt_connections_current 3327
telemt_connections_me_current 3327
telemt_handshake_timeouts_total 4958
telemt_upstream_connect_attempt_total 449
telemt_upstream_connect_success_total 446
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 449
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 239
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 206
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 248
telemt_me_reconnect_success_total 246
telemt_me_reader_eof_total 241
telemt_me_idle_close_by_peer_total 241
telemt_me_route_drop_no_conn_total 91957
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 208708
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 659
telemt_desync_full_logged_total 192
telemt_desync_suppressed_total 467
telemt_desync_frames_bucket_total{bucket="1_2"} 130
telemt_desync_frames_bucket_total{bucket="3_10"} 221
telemt_desync_frames_bucket_total{bucket="gt_10"} 308
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 254
telemt_me_writer_restored_same_endpoint_total 229
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 652
telemt_me_writer_removed_unexpected_minus_restored_total 8
telemt_user_connections_total{user="hello"} 208682
telemt_user_connections_current{user="hello"} 3327
telemt_user_octets_from_client{user="hello"} 4060789548 (3.78 GB)
telemt_user_octets_to_client{user="hello"} 81972591468 (76.34 GB)
telemt_user_unique_ips_current{user="hello"} 1008
telemt_user_unique_ips_recent_window{user="hello"} 576
```

## landvps.ru

```
telemt 3.3.22

telemt_uptime_seconds 4086.7 (1h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 392068
telemt_connections_bad_total 1935
telemt_connections_current 3338
telemt_connections_me_current 3338
telemt_handshake_timeouts_total 6650
telemt_upstream_connect_attempt_total 682
telemt_upstream_connect_success_total 679
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 682
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 343
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 332
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 432
telemt_me_reconnect_success_total 426
telemt_me_reader_eof_total 394
telemt_me_idle_close_by_peer_total 393
telemt_me_route_drop_no_conn_total 569156
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 352733
telemt_me_writer_pick_total{mode="p2c",result="full"} 30
telemt_me_writer_pick_total{mode="p2c",result="closed"} 61
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1001
telemt_desync_full_logged_total 269
telemt_desync_suppressed_total 732
telemt_desync_frames_bucket_total{bucket="1_2"} 189
telemt_desync_frames_bucket_total{bucket="3_10"} 476
telemt_desync_frames_bucket_total{bucket="gt_10"} 336
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 403
telemt_me_writer_restored_same_endpoint_total 415
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 1000
telemt_user_connections_total{user="hello"} 352683
telemt_user_connections_current{user="hello"} 3338
telemt_user_octets_from_client{user="hello"} 2713594004 (2.53 GB)
telemt_user_octets_to_client{user="hello"} 58973208028 (54.92 GB)
telemt_user_unique_ips_current{user="hello"} 903
telemt_user_unique_ips_recent_window{user="hello"} 701
```

## rdp-onedash.ru

```
telemt 3.3.20

telemt_uptime_seconds 22746.3 (6h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1863050
telemt_connections_bad_total 153604
telemt_handshake_timeouts_total 29189
telemt_upstream_connect_attempt_total 15580
telemt_upstream_connect_success_total 15552
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 15580
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12626
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2120
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 806
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 70
telemt_me_reconnect_attempts_total 2987151
telemt_me_reconnect_success_total 2706
telemt_me_reader_eof_total 2827
telemt_me_idle_close_by_peer_total 2827
telemt_me_route_drop_no_conn_total 1914412
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1545457
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4389
telemt_desync_full_logged_total 1550
telemt_desync_suppressed_total 2839
telemt_desync_frames_bucket_total{bucket="1_2"} 721
telemt_desync_frames_bucket_total{bucket="3_10"} 1705
telemt_desync_frames_bucket_total{bucket="gt_10"} 1963
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 2782
telemt_me_refill_failed_total 107230
telemt_me_writer_restored_same_endpoint_total 2591
telemt_me_writer_restored_fallback_total 115
telemt_me_async_recovery_trigger_total 267383
telemt_me_writer_removed_unexpected_minus_restored_total 76
telemt_user_connections_total{user="hello"} 1547285
telemt_user_connections_current{user="hello"} 3153
telemt_user_octets_from_client{user="hello"} 24203065171 (22.54 GB)
telemt_user_octets_to_client{user="hello"} 517343832765 (481.81 GB)
telemt_user_msgs_from_client{user="hello"} 89703
telemt_user_msgs_to_client{user="hello"} 269409
telemt_user_unique_ips_current{user="hello"} 1021
telemt_user_unique_ips_recent_window{user="hello"} 557
```

## hostvds.com

```
telemt 3.3.22

telemt_uptime_seconds 3534.9 (0h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 79714
telemt_connections_bad_total 4771
telemt_connections_current 933
telemt_connections_me_current 933
telemt_relay_adaptive_promotions_total 18
telemt_relay_adaptive_hard_promotions_total 18
telemt_handshake_timeouts_total 819
telemt_upstream_connect_attempt_total 4681
telemt_upstream_connect_success_total 4675
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 4681
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2744
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1901
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 22
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_reconnect_attempts_total 330105
telemt_me_reconnect_success_total 650
telemt_me_reader_eof_total 561
telemt_me_idle_close_by_peer_total 561
telemt_me_route_drop_no_conn_total 46114
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 66819
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 9
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 149
telemt_desync_full_logged_total 52
telemt_desync_suppressed_total 97
telemt_desync_frames_bucket_total{bucket="1_2"} 30
telemt_desync_frames_bucket_total{bucket="3_10"} 62
telemt_desync_frames_bucket_total{bucket="gt_10"} 57
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 567
telemt_me_refill_failed_total 10448
telemt_me_writer_restored_same_endpoint_total 639
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 40876
telemt_user_connections_total{user="hello"} 70588
telemt_user_connections_current{user="hello"} 933
telemt_user_octets_from_client{user="hello"} 1171210089 (1.09 GB)
telemt_user_octets_to_client{user="hello"} 11835127009 (11.02 GB)
telemt_user_msgs_from_client{user="hello"} 38712
telemt_user_msgs_to_client{user="hello"} 31668
telemt_user_unique_ips_current{user="hello"} 320
telemt_user_unique_ips_recent_window{user="hello"} 179
```

## 4vps.su

```
telemt 3.3.22

telemt_uptime_seconds 2605.7 (0h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 187819
telemt_connections_bad_total 7162
telemt_connections_current 2709
telemt_connections_me_current 2709
telemt_handshake_timeouts_total 1504
telemt_upstream_connect_attempt_total 511
telemt_upstream_connect_success_total 511
telemt_upstream_connect_attempts_per_request{bucket="1"} 511
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 297
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 213
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 14641
telemt_me_reconnect_success_total 353
telemt_me_reader_eof_total 244
telemt_me_idle_close_by_peer_total 244
telemt_me_route_drop_no_conn_total 161223
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="base"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 164584
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 416
telemt_desync_full_logged_total 142
telemt_desync_suppressed_total 274
telemt_desync_frames_bucket_total{bucket="1_2"} 95
telemt_desync_frames_bucket_total{bucket="3_10"} 139
telemt_desync_frames_bucket_total{bucket="gt_10"} 182
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 262
telemt_me_refill_failed_total 703
telemt_me_writer_restored_same_endpoint_total 292
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 9552
telemt_user_connections_total{user="hello"} 165435
telemt_user_connections_current{user="hello"} 2709
telemt_user_octets_from_client{user="hello"} 1677600732 (1.56 GB)
telemt_user_octets_to_client{user="hello"} 53204098912 (49.55 GB)
telemt_user_unique_ips_current{user="hello"} 830
telemt_user_unique_ips_recent_window{user="hello"} 414
```