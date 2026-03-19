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

# Server Metrics 2026-03-19 18:12:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 3278.3 (0h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 103151
telemt_connections_bad_total 3103
telemt_connections_current 1640
telemt_connections_me_current 1640
telemt_handshake_timeouts_total 969
telemt_upstream_connect_attempt_total 486
telemt_upstream_connect_success_total 477
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 486
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 243
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 228
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_reconnect_attempts_total 281
telemt_me_reconnect_success_total 279
telemt_me_reader_eof_total 275
telemt_me_idle_close_by_peer_total 275
telemt_me_route_drop_no_conn_total 35500
telemt_me_route_drop_channel_closed_total 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 90378
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 413
telemt_desync_full_logged_total 139
telemt_desync_suppressed_total 274
telemt_desync_frames_bucket_total{bucket="1_2"} 92
telemt_desync_frames_bucket_total{bucket="3_10"} 125
telemt_desync_frames_bucket_total{bucket="gt_10"} 196
telemt_pool_swap_total 3
telemt_me_writer_close_signal_drop_total 24
telemt_me_writer_removed_unexpected_total 291
telemt_me_writer_restored_same_endpoint_total 266
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 267
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 90545
telemt_user_connections_current{user="hello"} 1640
telemt_user_octets_from_client{user="hello"} 1495302724 (1.39 GB)
telemt_user_octets_to_client{user="hello"} 30469295640 (28.38 GB)
telemt_user_unique_ips_current{user="hello"} 454
telemt_user_unique_ips_recent_window{user="hello"} 207
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 19734.0 (5h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1972265
telemt_connections_bad_total 96784
telemt_connections_current 3979
telemt_connections_me_current 3979
telemt_handshake_timeouts_total 36848
telemt_upstream_connect_attempt_total 4528
telemt_upstream_connect_success_total 4474
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 4528
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2992
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1450
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 6462
telemt_me_reconnect_success_total 2237
telemt_me_reader_eof_total 2419
telemt_me_idle_close_by_peer_total 2419
telemt_me_route_drop_no_conn_total 1136834
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1638548
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6595
telemt_desync_full_logged_total 2087
telemt_desync_suppressed_total 4508
telemt_desync_frames_bucket_total{bucket="1_2"} 1255
telemt_desync_frames_bucket_total{bucket="3_10"} 2631
telemt_desync_frames_bucket_total{bucket="gt_10"} 2709
telemt_pool_swap_total 13
telemt_me_writer_close_signal_drop_total 35
telemt_me_writer_removed_unexpected_total 2383
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 2182
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 146
telemt_user_connections_total{user="hello"} 1638538
telemt_user_connections_current{user="hello"} 3979
telemt_user_octets_from_client{user="hello"} 24044546742 (22.39 GB)
telemt_user_octets_to_client{user="hello"} 528713290606 (492.40 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1313
telemt_user_unique_ips_recent_window{user="hello"} 531
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 19712.2 (5h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1816243
telemt_connections_bad_total 218099
telemt_connections_current 2908
telemt_connections_me_current 2908
telemt_handshake_timeouts_total 19380
telemt_upstream_connect_attempt_total 3113
telemt_upstream_connect_success_total 3091
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 3113
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1659
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1423
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 3001
telemt_me_reconnect_success_total 2083
telemt_me_reader_eof_total 2117
telemt_me_idle_close_by_peer_total 2116
telemt_me_route_drop_no_conn_total 1579899
telemt_me_route_drop_channel_closed_total 97
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1379143
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4427
telemt_desync_full_logged_total 1318
telemt_desync_suppressed_total 3109
telemt_desync_frames_bucket_total{bucket="1_2"} 1148
telemt_desync_frames_bucket_total{bucket="3_10"} 1663
telemt_desync_frames_bucket_total{bucket="gt_10"} 1616
telemt_pool_swap_total 15
telemt_me_writer_close_signal_drop_total 45
telemt_me_writer_removed_unexpected_total 2073
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 2082
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_user_connections_total{user="hello"} 1376129
telemt_user_connections_current{user="hello"} 2908
telemt_user_octets_from_client{user="hello"} 17572644104 (16.37 GB)
telemt_user_octets_to_client{user="hello"} 429980638260 (400.45 GB)
telemt_user_unique_ips_current{user="hello"} 973
telemt_user_unique_ips_recent_window{user="hello"} 412
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 19699.5 (5h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1679003
telemt_connections_bad_total 59229
telemt_connections_current 2962
telemt_connections_me_current 2962
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 23082
telemt_upstream_connect_attempt_total 25097
telemt_upstream_connect_success_total 23921
telemt_upstream_connect_fail_total 1176
telemt_upstream_connect_attempts_per_request{bucket="1"} 25097
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19632
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3920
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 350
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1176
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 4858
telemt_me_reconnect_success_total 2488
telemt_me_reader_eof_total 2566
telemt_me_idle_close_by_peer_total 2565
telemt_me_route_drop_no_conn_total 1455232
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1446640
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5723
telemt_desync_full_logged_total 1795
telemt_desync_suppressed_total 3928
telemt_desync_frames_bucket_total{bucket="1_2"} 1519
telemt_desync_frames_bucket_total{bucket="3_10"} 2100
telemt_desync_frames_bucket_total{bucket="gt_10"} 2104
telemt_pool_swap_total 7
telemt_me_writer_close_signal_drop_total 200
telemt_me_writer_removed_unexpected_total 2893
telemt_me_refill_failed_total 59
telemt_me_writer_restored_same_endpoint_total 2484
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 405
telemt_user_connections_total{user="hello"} 1465990
telemt_user_connections_current{user="hello"} 2962
telemt_user_octets_from_client{user="hello"} 26204894553 (24.41 GB)
telemt_user_octets_to_client{user="hello"} 318080004165 (296.24 GB)
telemt_user_msgs_from_client{user="hello"} 49930
telemt_user_msgs_to_client{user="hello"} 93819
telemt_user_unique_ips_current{user="hello"} 934
telemt_user_unique_ips_recent_window{user="hello"} 386
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 73423.2 (20h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5324850
telemt_connections_bad_total 948438
telemt_connections_current 3544
telemt_connections_me_current 3544
telemt_relay_adaptive_promotions_total 22
telemt_relay_adaptive_demotions_total 1819
telemt_relay_adaptive_hard_promotions_total 20
telemt_handshake_timeouts_total 98331
telemt_upstream_connect_attempt_total 64743
telemt_upstream_connect_success_total 62251
telemt_upstream_connect_fail_total 2492
telemt_upstream_connect_attempts_per_request{bucket="1"} 64743
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52874
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8332
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1045
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2492
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 74798
telemt_me_reconnect_success_total 9391
telemt_me_reader_eof_total 9896
telemt_me_idle_close_by_peer_total 9893
telemt_me_route_drop_no_conn_total 2474357
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3718781
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
telemt_desync_total 16166
telemt_desync_full_logged_total 4931
telemt_desync_suppressed_total 11235
telemt_desync_frames_bucket_total{bucket="1_2"} 2652
telemt_desync_frames_bucket_total{bucket="3_10"} 6752
telemt_desync_frames_bucket_total{bucket="gt_10"} 6762
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 9632
telemt_me_refill_failed_total 2040
telemt_me_writer_restored_same_endpoint_total 9367
telemt_me_writer_restored_fallback_total 24
telemt_me_no_writer_failfast_total 1478
telemt_me_async_recovery_trigger_total 7229
telemt_me_writer_removed_unexpected_minus_restored_total 241
telemt_user_connections_total{user="hello"} 3766896
telemt_user_connections_current{user="hello"} 3544
telemt_user_octets_from_client{user="hello"} 58645829455 (54.62 GB)
telemt_user_octets_to_client{user="hello"} 1380794539148 (1.26 TB)
telemt_user_msgs_from_client{user="hello"} 549175
telemt_user_msgs_to_client{user="hello"} 1884577
telemt_user_unique_ips_current{user="hello"} 1188
telemt_user_unique_ips_recent_window{user="hello"} 519
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 19670.0 (5h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 463295
telemt_connections_bad_total 31046
telemt_connections_current 791
telemt_connections_me_current 791
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 9647
telemt_upstream_connect_attempt_total 6890
telemt_upstream_connect_success_total 6694
telemt_upstream_connect_fail_total 196
telemt_upstream_connect_attempts_per_request{bucket="1"} 6890
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2188
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3834
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 133
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 539
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 196
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 410
telemt_me_reconnect_attempts_total 2750
telemt_me_reconnect_success_total 2697
telemt_me_reader_eof_total 2759
telemt_me_idle_close_by_peer_total 2758
telemt_me_route_drop_no_conn_total 316852
telemt_me_route_drop_channel_closed_total 102
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 366147
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
telemt_desync_total 1019
telemt_desync_full_logged_total 322
telemt_desync_suppressed_total 697
telemt_desync_frames_bucket_total{bucket="1_2"} 159
telemt_desync_frames_bucket_total{bucket="3_10"} 412
telemt_desync_frames_bucket_total{bucket="gt_10"} 448
telemt_pool_swap_total 12
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 105
telemt_me_writer_close_signal_channel_full_total 1
telemt_me_writer_removed_unexpected_total 2701
telemt_me_writer_restored_same_endpoint_total 2688
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 1178
telemt_me_async_recovery_trigger_total 1239
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 384361
telemt_user_connections_current{user="hello"} 791
telemt_user_octets_from_client{user="hello"} 4579404080 (4.26 GB)
telemt_user_octets_to_client{user="hello"} 83972962286 (78.21 GB)
telemt_user_msgs_from_client{user="hello"} 7943
telemt_user_msgs_to_client{user="hello"} 12935
telemt_user_unique_ips_current{user="hello"} 268
telemt_user_unique_ips_recent_window{user="hello"} 104
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 19664.5 (5h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1306267
telemt_connections_bad_total 85073
telemt_connections_current 3186
telemt_connections_me_current 3186
telemt_handshake_timeouts_total 23509
telemt_upstream_connect_attempt_total 3254
telemt_upstream_connect_success_total 3230
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 3254
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1736
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1480
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_reconnect_attempts_total 2241
telemt_me_reconnect_success_total 2216
telemt_me_reader_eof_total 2320
telemt_me_idle_close_by_peer_total 2320
telemt_me_route_drop_no_conn_total 504289
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1125680
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6085
telemt_desync_full_logged_total 1845
telemt_desync_suppressed_total 4240
telemt_desync_frames_bucket_total{bucket="1_2"} 1193
telemt_desync_frames_bucket_total{bucket="3_10"} 2110
telemt_desync_frames_bucket_total{bucket="gt_10"} 2782
telemt_pool_swap_total 16
telemt_me_writer_close_signal_drop_total 30
telemt_me_writer_removed_unexpected_total 2261
telemt_me_writer_restored_same_endpoint_total 2199
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 45
telemt_user_connections_total{user="hello"} 1125190
telemt_user_connections_current{user="hello"} 3186
telemt_user_octets_from_client{user="hello"} 17455455184 (16.26 GB)
telemt_user_octets_to_client{user="hello"} 495640130464 (461.60 GB)
telemt_user_unique_ips_current{user="hello"} 1018
telemt_user_unique_ips_recent_window{user="hello"} 430
```