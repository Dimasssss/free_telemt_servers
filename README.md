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

# Server Metrics 2026-03-19 11:41:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 49953.1 (13h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1205791
telemt_connections_bad_total 101216
telemt_connections_current 1657
telemt_connections_me_current 1657
telemt_handshake_timeouts_total 42253
telemt_upstream_connect_attempt_total 9590
telemt_upstream_connect_success_total 9425
telemt_upstream_connect_fail_total 165
telemt_upstream_connect_attempts_per_request{bucket="1"} 9590
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4619
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4803
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 165
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 95
telemt_me_reconnect_attempts_total 8797
telemt_me_reconnect_success_total 6911
telemt_me_reader_eof_total 7318
telemt_me_idle_close_by_peer_total 7315
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 503883
telemt_me_route_drop_channel_closed_total 196
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 943383
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 35
telemt_me_endpoint_quarantine_total 33
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5287
telemt_desync_full_logged_total 1606
telemt_desync_suppressed_total 3681
telemt_desync_frames_bucket_total{bucket="1_2"} 1712
telemt_desync_frames_bucket_total{bucket="3_10"} 1921
telemt_desync_frames_bucket_total{bucket="gt_10"} 1654
telemt_pool_swap_total 40
telemt_pool_stale_pick_total 3
telemt_me_writer_removed_unexpected_total 7068
telemt_me_refill_failed_total 58
telemt_me_writer_restored_same_endpoint_total 6890
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 157
telemt_user_connections_total{user="hello"} 937317
telemt_user_connections_current{user="hello"} 1657
telemt_user_octets_from_client{user="hello"} 14406370988 (13.42 GB)
telemt_user_octets_to_client{user="hello"} 284816795388 (265.26 GB)
telemt_user_unique_ips_current{user="hello"} 594
telemt_user_unique_ips_recent_window{user="hello"} 271
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 49957.3 (13h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3288016
telemt_connections_bad_total 213502
telemt_connections_current 4205
telemt_connections_me_current 4205
telemt_handshake_timeouts_total 61170
telemt_upstream_connect_attempt_total 9445
telemt_upstream_connect_success_total 9273
telemt_upstream_connect_fail_total 172
telemt_upstream_connect_attempts_per_request{bucket="1"} 9445
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4690
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4553
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 172
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 15489
telemt_me_reconnect_success_total 6728
telemt_me_reader_eof_total 7318
telemt_me_idle_close_by_peer_total 7317
telemt_me_seq_mismatch_total 14
telemt_me_route_drop_no_conn_total 2442405
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2761747
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 36
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11090
telemt_desync_full_logged_total 3709
telemt_desync_suppressed_total 7381
telemt_desync_frames_bucket_total{bucket="1_2"} 2153
telemt_desync_frames_bucket_total{bucket="3_10"} 4353
telemt_desync_frames_bucket_total{bucket="gt_10"} 4584
telemt_pool_swap_total 33
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 7120
telemt_me_refill_failed_total 273
telemt_me_writer_restored_same_endpoint_total 6705
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 392
telemt_user_connections_total{user="hello"} 2761355
telemt_user_connections_current{user="hello"} 4205
telemt_user_octets_from_client{user="hello"} 36675231292 (34.16 GB)
telemt_user_octets_to_client{user="hello"} 833820595428 (776.56 GB)
telemt_user_unique_ips_current{user="hello"} 1386
telemt_user_unique_ips_recent_window{user="hello"} 1010
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 49954.9 (13h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2544788
telemt_connections_bad_total 298319
telemt_connections_current 3470
telemt_connections_me_current 3470
telemt_handshake_timeouts_total 52063
telemt_upstream_connect_attempt_total 9010
telemt_upstream_connect_success_total 9010
telemt_upstream_connect_attempts_per_request{bucket="1"} 9010
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4675
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4318
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 7657
telemt_me_reconnect_success_total 6463
telemt_me_reader_eof_total 6858
telemt_me_idle_close_by_peer_total 6857
telemt_me_route_drop_no_conn_total 1563734
telemt_me_route_drop_channel_closed_total 80
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2002709
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8321
telemt_desync_full_logged_total 2638
telemt_desync_suppressed_total 5683
telemt_desync_frames_bucket_total{bucket="1_2"} 1891
telemt_desync_frames_bucket_total{bucket="3_10"} 3050
telemt_desync_frames_bucket_total{bucket="gt_10"} 3380
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 6610
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 6447
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 147
telemt_user_connections_total{user="hello"} 2000498
telemt_user_connections_current{user="hello"} 3470
telemt_user_octets_from_client{user="hello"} 27987425664 (26.07 GB)
telemt_user_octets_to_client{user="hello"} 852957257160 (794.38 GB)
telemt_user_unique_ips_current{user="hello"} 1131
telemt_user_unique_ips_recent_window{user="hello"} 489
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 50007.7 (13h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2617392
telemt_connections_bad_total 137437
telemt_connections_current 3024
telemt_connections_me_current 3024
telemt_relay_adaptive_promotions_total 1
telemt_relay_adaptive_hard_promotions_total 1
telemt_handshake_timeouts_total 64675
telemt_upstream_connect_attempt_total 17306
telemt_upstream_connect_success_total 17131
telemt_upstream_connect_fail_total 175
telemt_upstream_connect_attempts_per_request{bucket="1"} 17306
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11922
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5040
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 167
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 175
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 10771
telemt_me_reconnect_success_total 6425
telemt_me_reader_eof_total 6845
telemt_me_idle_close_by_peer_total 6844
telemt_me_route_drop_no_conn_total 1719862
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2024250
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7139
telemt_desync_full_logged_total 2375
telemt_desync_suppressed_total 4764
telemt_desync_frames_bucket_total{bucket="1_2"} 1516
telemt_desync_frames_bucket_total{bucket="3_10"} 2800
telemt_desync_frames_bucket_total{bucket="gt_10"} 2823
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 6894
telemt_me_refill_failed_total 128
telemt_me_writer_restored_same_endpoint_total 6401
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 295
telemt_me_writer_removed_unexpected_minus_restored_total 469
telemt_user_connections_total{user="hello"} 2030377
telemt_user_connections_current{user="hello"} 3024
telemt_user_octets_from_client{user="hello"} 22708538108 (21.15 GB)
telemt_user_octets_to_client{user="hello"} 544157155174 (506.79 GB)
telemt_user_msgs_from_client{user="hello"} 28643
telemt_user_msgs_to_client{user="hello"} 76631
telemt_user_unique_ips_current{user="hello"} 1012
telemt_user_unique_ips_recent_window{user="hello"} 455
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 49951.2 (13h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3025711
telemt_connections_bad_total 654648
telemt_connections_current 3593
telemt_connections_me_current 3593
telemt_handshake_timeouts_total 60751
telemt_upstream_connect_attempt_total 8926
telemt_upstream_connect_success_total 8861
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 8926
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4572
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4255
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 19
telemt_me_reconnect_attempts_total 7539
telemt_me_reconnect_success_total 6334
telemt_me_reader_eof_total 6721
telemt_me_idle_close_by_peer_total 6720
telemt_me_route_drop_no_conn_total 1134998
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2007866
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8732
telemt_desync_full_logged_total 2710
telemt_desync_suppressed_total 6022
telemt_desync_frames_bucket_total{bucket="1_2"} 1641
telemt_desync_frames_bucket_total{bucket="3_10"} 3792
telemt_desync_frames_bucket_total{bucket="gt_10"} 3299
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 6464
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 6310
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 130
telemt_user_connections_total{user="hello"} 2006477
telemt_user_connections_current{user="hello"} 3593
telemt_user_octets_from_client{user="hello"} 34505512436 (32.14 GB)
telemt_user_octets_to_client{user="hello"} 808643827572 (753.11 GB)
telemt_user_unique_ips_current{user="hello"} 1248
telemt_user_unique_ips_recent_window{user="hello"} 565
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 49963.6 (13h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 524539
telemt_connections_bad_total 18684
telemt_connections_current 1037
telemt_connections_me_current 1037
telemt_handshake_timeouts_total 4085
telemt_upstream_connect_attempt_total 12382
telemt_upstream_connect_success_total 12065
telemt_upstream_connect_fail_total 317
telemt_upstream_connect_attempts_per_request{bucket="1"} 12382
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5943
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6120
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 317
telemt_me_keepalive_timeout_total 22
telemt_me_reconnect_attempts_total 17125
telemt_me_reconnect_success_total 9534
telemt_me_reader_eof_total 10170
telemt_me_idle_close_by_peer_total 10170
telemt_me_route_drop_no_conn_total 273029
telemt_me_route_drop_channel_closed_total 34
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 476258
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1034
telemt_desync_full_logged_total 360
telemt_desync_suppressed_total 674
telemt_desync_frames_bucket_total{bucket="1_2"} 214
telemt_desync_frames_bucket_total{bucket="3_10"} 418
telemt_desync_frames_bucket_total{bucket="gt_10"} 402
telemt_pool_swap_total 24
telemt_pool_stale_pick_total 194
telemt_me_writer_removed_unexpected_total 9861
telemt_me_refill_failed_total 235
telemt_me_writer_restored_same_endpoint_total 9503
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 327
telemt_user_connections_total{user="hello"} 476197
telemt_user_connections_current{user="hello"} 1037
telemt_user_octets_from_client{user="hello"} 7623898004 (7.10 GB)
telemt_user_octets_to_client{user="hello"} 174513124732 (162.53 GB)
telemt_user_unique_ips_current{user="hello"} 359
telemt_user_unique_ips_recent_window{user="hello"} 141
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 49953.5 (13h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2123510
telemt_connections_bad_total 176274
telemt_connections_current 3213
telemt_connections_me_current 3213
telemt_handshake_timeouts_total 72844
telemt_upstream_connect_attempt_total 10024
telemt_upstream_connect_success_total 10023
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 10024
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5443
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4577
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 86
telemt_me_reconnect_attempts_total 8848
telemt_me_reconnect_success_total 7478
telemt_me_reader_eof_total 7917
telemt_me_idle_close_by_peer_total 7916
telemt_me_route_drop_no_conn_total 1068695
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1774032
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9647
telemt_desync_full_logged_total 3111
telemt_desync_suppressed_total 6536
telemt_desync_frames_bucket_total{bucket="1_2"} 1837
telemt_desync_frames_bucket_total{bucket="3_10"} 3678
telemt_desync_frames_bucket_total{bucket="gt_10"} 4132
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 7620
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 7463
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 142
telemt_user_connections_total{user="hello"} 1772727
telemt_user_connections_current{user="hello"} 3213
telemt_user_octets_from_client{user="hello"} 23355715236 (21.75 GB)
telemt_user_octets_to_client{user="hello"} 787778480088 (733.68 GB)
telemt_user_unique_ips_current{user="hello"} 1035
telemt_user_unique_ips_recent_window{user="hello"} 474
```