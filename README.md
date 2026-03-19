# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 19 апреля
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

# Server Metrics 2026-03-19 19:13:34 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 6958.9 (1h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 225246
telemt_connections_bad_total 8795
telemt_connections_current 1340
telemt_connections_me_current 1340
telemt_handshake_timeouts_total 2330
telemt_upstream_connect_attempt_total 1027
telemt_upstream_connect_success_total 1013
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 1027
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 488
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 516
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 645
telemt_me_reconnect_success_total 641
telemt_me_reader_eof_total 659
telemt_me_idle_close_by_peer_total 659
telemt_me_route_drop_no_conn_total 68227
telemt_me_route_drop_channel_closed_total 29
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 173517
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 800
telemt_desync_full_logged_total 263
telemt_desync_suppressed_total 537
telemt_desync_frames_bucket_total{bucket="1_2"} 176
telemt_desync_frames_bucket_total{bucket="3_10"} 237
telemt_desync_frames_bucket_total{bucket="gt_10"} 387
telemt_pool_swap_total 7
telemt_me_writer_close_signal_drop_total 28
telemt_me_writer_removed_unexpected_total 660
telemt_me_writer_restored_same_endpoint_total 628
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 267
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 173744
telemt_user_connections_current{user="hello"} 1340
telemt_user_octets_from_client{user="hello"} 3508463252 (3.27 GB)
telemt_user_octets_to_client{user="hello"} 60390980464 (56.24 GB)
telemt_user_unique_ips_current{user="hello"} 404
telemt_user_unique_ips_recent_window{user="hello"} 159
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 23414.4 (6h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2254674
telemt_connections_bad_total 102551
telemt_connections_current 3719
telemt_connections_me_current 3719
telemt_handshake_timeouts_total 42750
telemt_upstream_connect_attempt_total 5114
telemt_upstream_connect_success_total 5048
telemt_upstream_connect_fail_total 66
telemt_upstream_connect_attempts_per_request{bucket="1"} 5114
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3300
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1712
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 66
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 6863
telemt_me_reconnect_success_total 2637
telemt_me_reader_eof_total 2845
telemt_me_idle_close_by_peer_total 2845
telemt_me_route_drop_no_conn_total 1248393
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1894467
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7769
telemt_desync_full_logged_total 2505
telemt_desync_suppressed_total 5264
telemt_desync_frames_bucket_total{bucket="1_2"} 1448
telemt_desync_frames_bucket_total{bucket="3_10"} 3073
telemt_desync_frames_bucket_total{bucket="gt_10"} 3248
telemt_pool_swap_total 16
telemt_me_writer_close_signal_drop_total 36
telemt_me_writer_removed_unexpected_total 2786
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 2582
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 149
telemt_user_connections_total{user="hello"} 1894452
telemt_user_connections_current{user="hello"} 3719
telemt_user_octets_from_client{user="hello"} 27760708126 (25.85 GB)
telemt_user_octets_to_client{user="hello"} 632018240078 (588.61 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1251
telemt_user_unique_ips_recent_window{user="hello"} 434
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 23393.8 (6h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2049332
telemt_connections_bad_total 246254
telemt_connections_current 2766
telemt_connections_me_current 2766
telemt_handshake_timeouts_total 23851
telemt_upstream_connect_attempt_total 3627
telemt_upstream_connect_success_total 3602
telemt_upstream_connect_fail_total 25
telemt_upstream_connect_attempts_per_request{bucket="1"} 3627
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1902
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1691
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 25
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 3338
telemt_me_reconnect_success_total 2420
telemt_me_reader_eof_total 2482
telemt_me_idle_close_by_peer_total 2481
telemt_me_route_drop_no_conn_total 1730780
telemt_me_route_drop_channel_closed_total 149
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1557922
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5442
telemt_desync_full_logged_total 1614
telemt_desync_suppressed_total 3828
telemt_desync_frames_bucket_total{bucket="1_2"} 1377
telemt_desync_frames_bucket_total{bucket="3_10"} 2060
telemt_desync_frames_bucket_total{bucket="gt_10"} 2005
telemt_pool_swap_total 19
telemt_me_writer_close_signal_drop_total 53
telemt_me_writer_removed_unexpected_total 2420
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 2419
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_user_connections_total{user="hello"} 1554283
telemt_user_connections_current{user="hello"} 2766
telemt_user_octets_from_client{user="hello"} 20742546960 (19.32 GB)
telemt_user_octets_to_client{user="hello"} 518213741260 (482.62 GB)
telemt_user_unique_ips_current{user="hello"} 912
telemt_user_unique_ips_recent_window{user="hello"} 317
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 23380.5 (6h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1921896
telemt_connections_bad_total 63428
telemt_connections_current 2844
telemt_connections_me_current 2844
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 24891
telemt_upstream_connect_attempt_total 25672
telemt_upstream_connect_success_total 24472
telemt_upstream_connect_fail_total 1200
telemt_upstream_connect_attempts_per_request{bucket="1"} 25672
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19909
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4190
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 354
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1200
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 5251
telemt_me_reconnect_success_total 2864
telemt_me_reader_eof_total 2969
telemt_me_idle_close_by_peer_total 2968
telemt_me_route_drop_no_conn_total 1659650
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1658865
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6601
telemt_desync_full_logged_total 2040
telemt_desync_suppressed_total 4561
telemt_desync_frames_bucket_total{bucket="1_2"} 1676
telemt_desync_frames_bucket_total{bucket="3_10"} 2415
telemt_desync_frames_bucket_total{bucket="gt_10"} 2510
telemt_pool_swap_total 10
telemt_me_writer_close_signal_drop_total 200
telemt_me_writer_removed_unexpected_total 3280
telemt_me_refill_failed_total 59
telemt_me_writer_restored_same_endpoint_total 2860
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 416
telemt_user_connections_total{user="hello"} 1678191
telemt_user_connections_current{user="hello"} 2844
telemt_user_octets_from_client{user="hello"} 28375919997 (26.43 GB)
telemt_user_octets_to_client{user="hello"} 376075674637 (350.25 GB)
telemt_user_msgs_from_client{user="hello"} 49930
telemt_user_msgs_to_client{user="hello"} 93819
telemt_user_unique_ips_current{user="hello"} 916
telemt_user_unique_ips_recent_window{user="hello"} 393
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 77103.8 (21h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5607001
telemt_connections_bad_total 1010825
telemt_connections_current 3224
telemt_connections_me_current 3224
telemt_relay_adaptive_promotions_total 22
telemt_relay_adaptive_demotions_total 1819
telemt_relay_adaptive_hard_promotions_total 20
telemt_handshake_timeouts_total 102425
telemt_upstream_connect_attempt_total 65237
telemt_upstream_connect_success_total 62741
telemt_upstream_connect_fail_total 2496
telemt_upstream_connect_attempts_per_request{bucket="1"} 65237
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53114
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8577
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1050
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2496
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 75116
telemt_me_reconnect_success_total 9706
telemt_me_reader_eof_total 10236
telemt_me_idle_close_by_peer_total 10233
telemt_me_route_drop_no_conn_total 2568657
telemt_me_route_drop_channel_closed_total 15
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3913521
telemt_me_writer_pick_total{mode="p2c",result="full"} 8278
telemt_me_writer_pick_total{mode="p2c",result="closed"} 806
telemt_me_writer_pick_blocking_fallback_total 9050
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 17284
telemt_desync_full_logged_total 5297
telemt_desync_suppressed_total 11987
telemt_desync_frames_bucket_total{bucket="1_2"} 2887
telemt_desync_frames_bucket_total{bucket="3_10"} 7160
telemt_desync_frames_bucket_total{bucket="gt_10"} 7237
telemt_pool_swap_total 62
telemt_me_writer_removed_unexpected_total 9955
telemt_me_refill_failed_total 2040
telemt_me_writer_restored_same_endpoint_total 9682
telemt_me_writer_restored_fallback_total 24
telemt_me_no_writer_failfast_total 1478
telemt_me_async_recovery_trigger_total 7229
telemt_me_writer_removed_unexpected_minus_restored_total 249
telemt_user_connections_total{user="hello"} 3961637
telemt_user_connections_current{user="hello"} 3224
telemt_user_octets_from_client{user="hello"} 61885139347 (57.64 GB)
telemt_user_octets_to_client{user="hello"} 1467085681708 (1.33 TB)
telemt_user_msgs_from_client{user="hello"} 549175
telemt_user_msgs_to_client{user="hello"} 1884577
telemt_user_unique_ips_current{user="hello"} 1086
telemt_user_unique_ips_recent_window{user="hello"} 407
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 23345.6 (6h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 529527
telemt_connections_bad_total 38376
telemt_connections_current 669
telemt_connections_me_current 669
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 10679
telemt_upstream_connect_attempt_total 7430
telemt_upstream_connect_success_total 7233
telemt_upstream_connect_fail_total 197
telemt_upstream_connect_attempts_per_request{bucket="1"} 7430
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2328
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4183
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 173
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 549
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 197
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 424
telemt_me_reconnect_attempts_total 3117
telemt_me_reconnect_success_total 3059
telemt_me_reader_eof_total 3149
telemt_me_idle_close_by_peer_total 3148
telemt_me_route_drop_no_conn_total 368243
telemt_me_route_drop_channel_closed_total 131
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 419848
telemt_me_writer_pick_total{mode="p2c",result="success_fallback"} 881
telemt_me_writer_pick_total{mode="p2c",result="full"} 7065
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_writer_pick_blocking_fallback_total 8012
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1116
telemt_desync_full_logged_total 352
telemt_desync_suppressed_total 764
telemt_desync_frames_bucket_total{bucket="1_2"} 176
telemt_desync_frames_bucket_total{bucket="3_10"} 454
telemt_desync_frames_bucket_total{bucket="gt_10"} 486
telemt_pool_swap_total 15
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 134
telemt_me_writer_close_signal_channel_full_total 1
telemt_me_writer_removed_unexpected_total 3084
telemt_me_writer_restored_same_endpoint_total 3050
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 1178
telemt_me_async_recovery_trigger_total 1239
telemt_me_writer_removed_unexpected_minus_restored_total 25
telemt_user_connections_total{user="hello"} 438491
telemt_user_connections_current{user="hello"} 669
telemt_user_octets_from_client{user="hello"} 5024037536 (4.68 GB)
telemt_user_octets_to_client{user="hello"} 91741355622 (85.44 GB)
telemt_user_msgs_from_client{user="hello"} 7943
telemt_user_msgs_to_client{user="hello"} 12935
telemt_user_unique_ips_current{user="hello"} 238
telemt_user_unique_ips_recent_window{user="hello"} 89
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 23345.1 (6h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1506713
telemt_connections_bad_total 90372
telemt_connections_current 3011
telemt_connections_me_current 3011
telemt_handshake_timeouts_total 25297
telemt_upstream_connect_attempt_total 3811
telemt_upstream_connect_success_total 3783
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 3811
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2023
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1738
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 2622
telemt_me_reconnect_success_total 2594
telemt_me_reader_eof_total 2722
telemt_me_idle_close_by_peer_total 2722
telemt_me_route_drop_no_conn_total 578142
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1308384
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6916
telemt_desync_full_logged_total 2131
telemt_desync_suppressed_total 4785
telemt_desync_frames_bucket_total{bucket="1_2"} 1317
telemt_desync_frames_bucket_total{bucket="3_10"} 2405
telemt_desync_frames_bucket_total{bucket="gt_10"} 3194
telemt_pool_swap_total 20
telemt_me_writer_close_signal_drop_total 33
telemt_me_writer_removed_unexpected_total 2648
telemt_me_writer_restored_same_endpoint_total 2577
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 54
telemt_user_connections_total{user="hello"} 1307631
telemt_user_connections_current{user="hello"} 3011
telemt_user_octets_from_client{user="hello"} 20930050216 (19.49 GB)
telemt_user_octets_to_client{user="hello"} 588675333088 (548.25 GB)
telemt_user_unique_ips_current{user="hello"} 948
telemt_user_unique_ips_recent_window{user="hello"} 359
```