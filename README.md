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

# Server Metrics 2026-03-20 01:49:27 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 30712.5 (8h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 577298
telemt_connections_bad_total 37120
telemt_connections_current 805
telemt_connections_me_current 805
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 9058
telemt_upstream_connect_attempt_total 6470
telemt_upstream_connect_success_total 6385
telemt_upstream_connect_fail_total 85
telemt_upstream_connect_attempts_per_request{bucket="1"} 6470
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3665
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2692
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 85
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 3744
telemt_me_reconnect_success_total 3709
telemt_me_reader_eof_total 3913
telemt_me_idle_close_by_peer_total 3912
telemt_me_route_drop_no_conn_total 165709
telemt_me_route_drop_channel_closed_total 57
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 461083
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2153
telemt_desync_full_logged_total 774
telemt_desync_suppressed_total 1379
telemt_desync_frames_bucket_total{bucket="1_2"} 433
telemt_desync_frames_bucket_total{bucket="3_10"} 743
telemt_desync_frames_bucket_total{bucket="gt_10"} 977
telemt_pool_swap_total 34
telemt_me_writer_close_signal_drop_total 39
telemt_me_writer_removed_unexpected_total 3736
telemt_me_writer_restored_same_endpoint_total 3696
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 447
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 462511
telemt_user_connections_current{user="hello"} 805
telemt_user_octets_from_client{user="hello"} 29834558232 (27.79 GB)
telemt_user_octets_to_client{user="hello"} 163298219605 (152.08 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 318
telemt_user_unique_ips_recent_window{user="hello"} 91
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 47168.3 (13h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3012110
telemt_connections_bad_total 126358
telemt_connections_current 1349
telemt_connections_me_current 1349
telemt_handshake_timeouts_total 66393
telemt_upstream_connect_attempt_total 9385
telemt_upstream_connect_success_total 9228
telemt_upstream_connect_fail_total 157
telemt_upstream_connect_attempts_per_request{bucket="1"} 9385
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5352
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3819
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 157
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 9882
telemt_me_reconnect_success_total 5639
telemt_me_reader_eof_total 6035
telemt_me_idle_close_by_peer_total 6035
telemt_me_route_drop_no_conn_total 1506290
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2581921
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11190
telemt_desync_full_logged_total 3684
telemt_desync_suppressed_total 7506
telemt_desync_frames_bucket_total{bucket="1_2"} 2143
telemt_desync_frames_bucket_total{bucket="3_10"} 4377
telemt_desync_frames_bucket_total{bucket="gt_10"} 4670
telemt_pool_swap_total 40
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 51
telemt_me_writer_removed_unexpected_total 5835
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 5584
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 196
telemt_user_connections_total{user="hello"} 2581701
telemt_user_connections_current{user="hello"} 1349
telemt_user_octets_from_client{user="hello"} 39421991086 (36.71 GB)
telemt_user_octets_to_client{user="hello"} 948482146334 (883.34 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 635
telemt_user_unique_ips_recent_window{user="hello"} 145
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 47146.1 (13h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2962954
telemt_connections_bad_total 476229
telemt_connections_current 1109
telemt_connections_me_current 1109
telemt_handshake_timeouts_total 43726
telemt_upstream_connect_attempt_total 7635
telemt_upstream_connect_success_total 7577
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 7635
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3860
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3700
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 6148
telemt_me_reconnect_success_total 5215
telemt_me_reader_eof_total 5474
telemt_me_idle_close_by_peer_total 5473
telemt_me_route_drop_no_conn_total 1923446
telemt_me_route_drop_channel_closed_total 173
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2042090
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7671
telemt_desync_full_logged_total 2330
telemt_desync_suppressed_total 5341
telemt_desync_frames_bucket_total{bucket="1_2"} 1891
telemt_desync_frames_bucket_total{bucket="3_10"} 2920
telemt_desync_frames_bucket_total{bucket="gt_10"} 2860
telemt_pool_swap_total 46
telemt_me_writer_close_signal_drop_total 70
telemt_me_writer_removed_unexpected_total 5266
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 5214
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 2037712
telemt_user_connections_current{user="hello"} 1109
telemt_user_octets_from_client{user="hello"} 30107940516 (28.04 GB)
telemt_user_octets_to_client{user="hello"} 781959191804 (728.26 GB)
telemt_user_unique_ips_current{user="hello"} 474
telemt_user_unique_ips_recent_window{user="hello"} 100
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 47134.1 (13h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2578216
telemt_connections_bad_total 132557
telemt_connections_current 1159
telemt_connections_me_current 1159
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 31302
telemt_upstream_connect_attempt_total 55573
telemt_upstream_connect_success_total 51292
telemt_upstream_connect_fail_total 4281
telemt_upstream_connect_attempts_per_request{bucket="1"} 55573
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43188
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7551
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 528
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4281
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 8525
telemt_me_reconnect_success_total 5683
telemt_me_reader_eof_total 5910
telemt_me_idle_close_by_peer_total 5909
telemt_me_route_drop_no_conn_total 1865839
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2145800
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8356
telemt_desync_full_logged_total 2639
telemt_desync_suppressed_total 5717
telemt_desync_frames_bucket_total{bucket="1_2"} 2062
telemt_desync_frames_bucket_total{bucket="3_10"} 3035
telemt_desync_frames_bucket_total{bucket="gt_10"} 3259
telemt_pool_swap_total 33
telemt_me_writer_close_signal_drop_total 477
telemt_me_writer_removed_unexpected_total 6310
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 5679
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 627
telemt_user_connections_total{user="hello"} 2187873
telemt_user_connections_current{user="hello"} 1159
telemt_user_octets_from_client{user="hello"} 35677539285 (33.23 GB)
telemt_user_octets_to_client{user="hello"} 616204909089 (573.89 GB)
telemt_user_msgs_from_client{user="hello"} 240837
telemt_user_msgs_to_client{user="hello"} 1741640
telemt_user_unique_ips_current{user="hello"} 425
telemt_user_unique_ips_recent_window{user="hello"} 107
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 100857.2 (28h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6283533
telemt_connections_bad_total 1044341
telemt_connections_current 1323
telemt_connections_me_current 1323
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_demotions_total 4345
telemt_relay_adaptive_hard_promotions_total 27
telemt_handshake_timeouts_total 113726
telemt_upstream_connect_attempt_total 127544
telemt_upstream_connect_success_total 94258
telemt_upstream_connect_fail_total 33286
telemt_upstream_connect_attempts_per_request{bucket="1"} 127544
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 80340
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12485
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1433
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33286
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 78586
telemt_me_reconnect_success_total 12916
telemt_me_reader_eof_total 13910
telemt_me_idle_close_by_peer_total 13896
telemt_me_route_drop_no_conn_total 2799839
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4455246
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
telemt_desync_total 19564
telemt_desync_full_logged_total 6199
telemt_desync_suppressed_total 13365
telemt_desync_frames_bucket_total{bucket="1_2"} 3444
telemt_desync_frames_bucket_total{bucket="3_10"} 8054
telemt_desync_frames_bucket_total{bucket="gt_10"} 8066
telemt_pool_swap_total 87
telemt_me_writer_removed_unexpected_total 13225
telemt_me_refill_failed_total 2047
telemt_me_writer_restored_same_endpoint_total 12891
telemt_me_writer_restored_fallback_total 25
telemt_me_no_writer_failfast_total 1489
telemt_me_async_recovery_trigger_total 7328
telemt_me_writer_removed_unexpected_minus_restored_total 309
telemt_user_connections_total{user="hello"} 4530459
telemt_user_connections_current{user="hello"} 1323
telemt_user_octets_from_client{user="hello"} 72567534468 (67.58 GB)
telemt_user_octets_to_client{user="hello"} 1742542393400 (1.58 TB)
telemt_user_msgs_from_client{user="hello"} 754082
telemt_user_msgs_to_client{user="hello"} 3090177
telemt_user_unique_ips_current{user="hello"} 549
telemt_user_unique_ips_recent_window{user="hello"} 118
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 47097.2 (13h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 716291
telemt_connections_bad_total 76938
telemt_connections_current 359
telemt_connections_me_current 359
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 13056
telemt_upstream_connect_attempt_total 13769
telemt_upstream_connect_success_total 13439
telemt_upstream_connect_fail_total 330
telemt_upstream_connect_attempts_per_request{bucket="1"} 13769
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5579
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7019
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 661
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 330
telemt_me_keepalive_failed_total 58
telemt_me_keepalive_timeout_total 508
telemt_me_reconnect_attempts_total 6736
telemt_me_reconnect_success_total 6627
telemt_me_reader_eof_total 7008
telemt_me_idle_close_by_peer_total 7005
telemt_me_route_drop_no_conn_total 470873
telemt_me_route_drop_channel_closed_total 144
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 585597
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
telemt_desync_total 1397
telemt_desync_full_logged_total 523
telemt_desync_suppressed_total 874
telemt_desync_frames_bucket_total{bucket="1_2"} 218
telemt_desync_frames_bucket_total{bucket="3_10"} 576
telemt_desync_frames_bucket_total{bucket="gt_10"} 603
telemt_pool_swap_total 41
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 151
telemt_me_writer_close_signal_channel_full_total 1
telemt_me_writer_removed_unexpected_total 6689
telemt_me_writer_restored_same_endpoint_total 6618
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 1203
telemt_me_async_recovery_trigger_total 1464
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 576007
telemt_user_connections_current{user="hello"} 359
telemt_user_octets_from_client{user="hello"} 7388200279 (6.88 GB)
telemt_user_octets_to_client{user="hello"} 146390877834 (136.34 GB)
telemt_user_msgs_from_client{user="hello"} 11096
telemt_user_msgs_to_client{user="hello"} 16837
telemt_user_unique_ips_current{user="hello"} 161
telemt_user_unique_ips_recent_window{user="hello"} 73
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 47098.8 (13h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2030045
telemt_connections_bad_total 120188
telemt_connections_current 1184
telemt_connections_me_current 1184
telemt_handshake_timeouts_total 37688
telemt_upstream_connect_attempt_total 8451
telemt_upstream_connect_success_total 8391
telemt_upstream_connect_fail_total 60
telemt_upstream_connect_attempts_per_request{bucket="1"} 8451
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4524
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3830
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 60
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 6064
telemt_me_reconnect_success_total 6020
telemt_me_reader_eof_total 6358
telemt_me_idle_close_by_peer_total 6358
telemt_me_route_drop_no_conn_total 744987
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1745490
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9252
telemt_desync_full_logged_total 2974
telemt_desync_suppressed_total 6278
telemt_desync_frames_bucket_total{bucket="1_2"} 1742
telemt_desync_frames_bucket_total{bucket="3_10"} 3245
telemt_desync_frames_bucket_total{bucket="gt_10"} 4265
telemt_pool_swap_total 47
telemt_me_writer_close_signal_drop_total 41
telemt_me_writer_removed_unexpected_total 6112
telemt_me_writer_restored_same_endpoint_total 6003
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 92
telemt_user_connections_total{user="hello"} 1744597
telemt_user_connections_current{user="hello"} 1184
telemt_user_octets_from_client{user="hello"} 29801764920 (27.76 GB)
telemt_user_octets_to_client{user="hello"} 885033256232 (824.25 GB)
telemt_user_unique_ips_current{user="hello"} 475
telemt_user_unique_ips_recent_window{user="hello"} 95
```