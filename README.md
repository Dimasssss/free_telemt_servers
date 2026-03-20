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

# Server Metrics 2026-03-20 03:16:10 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 35914.7 (9h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 663566
telemt_connections_bad_total 44391
telemt_connections_current 865
telemt_connections_me_current 865
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 14842
telemt_upstream_connect_attempt_total 7326
telemt_upstream_connect_success_total 7235
telemt_upstream_connect_fail_total 91
telemt_upstream_connect_attempts_per_request{bucket="1"} 7326
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4080
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3127
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 91
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 4379
telemt_me_reconnect_success_total 4339
telemt_me_reader_eof_total 4584
telemt_me_idle_close_by_peer_total 4583
telemt_me_route_drop_no_conn_total 186539
telemt_me_route_drop_channel_closed_total 60
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 526067
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2483
telemt_desync_full_logged_total 902
telemt_desync_suppressed_total 1581
telemt_desync_frames_bucket_total{bucket="1_2"} 513
telemt_desync_frames_bucket_total{bucket="3_10"} 888
telemt_desync_frames_bucket_total{bucket="gt_10"} 1082
telemt_pool_swap_total 39
telemt_me_writer_close_signal_drop_total 40
telemt_me_writer_removed_unexpected_total 4376
telemt_me_writer_restored_same_endpoint_total 4326
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 447
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 527499
telemt_user_connections_current{user="hello"} 865
telemt_user_octets_from_client{user="hello"} 30958037104 (28.83 GB)
telemt_user_octets_to_client{user="hello"} 180467553749 (168.07 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 358
telemt_user_unique_ips_recent_window{user="hello"} 123
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 52369.3 (14h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3188798
telemt_connections_bad_total 178372
telemt_connections_current 2066
telemt_connections_me_current 2066
telemt_handshake_timeouts_total 69656
telemt_upstream_connect_attempt_total 10248
telemt_upstream_connect_success_total 10067
telemt_upstream_connect_fail_total 181
telemt_upstream_connect_attempts_per_request{bucket="1"} 10248
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5745
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4263
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 181
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 10463
telemt_me_reconnect_success_total 6215
telemt_me_reader_eof_total 6651
telemt_me_idle_close_by_peer_total 6651
telemt_me_route_drop_no_conn_total 1541102
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2699347
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11532
telemt_desync_full_logged_total 3809
telemt_desync_suppressed_total 7723
telemt_desync_frames_bucket_total{bucket="1_2"} 2213
telemt_desync_frames_bucket_total{bucket="3_10"} 4502
telemt_desync_frames_bucket_total{bucket="gt_10"} 4817
telemt_pool_swap_total 46
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 53
telemt_me_writer_removed_unexpected_total 6419
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 6160
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 204
telemt_user_connections_total{user="hello"} 2699080
telemt_user_connections_current{user="hello"} 2066
telemt_user_octets_from_client{user="hello"} 41013702118 (38.20 GB)
telemt_user_octets_to_client{user="hello"} 1003837884202 (934.90 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 800
telemt_user_unique_ips_recent_window{user="hello"} 225
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 52347.4 (14h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3063994
telemt_connections_bad_total 480618
telemt_connections_current 1754
telemt_connections_me_current 1754
telemt_handshake_timeouts_total 48983
telemt_upstream_connect_attempt_total 8570
telemt_upstream_connect_success_total 8509
telemt_upstream_connect_fail_total 61
telemt_upstream_connect_attempts_per_request{bucket="1"} 8570
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4308
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4184
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 61
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 6822
telemt_me_reconnect_success_total 5886
telemt_me_reader_eof_total 6184
telemt_me_idle_close_by_peer_total 6183
telemt_me_route_drop_no_conn_total 1962481
telemt_me_route_drop_channel_closed_total 174
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2123485
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7953
telemt_desync_full_logged_total 2437
telemt_desync_suppressed_total 5516
telemt_desync_frames_bucket_total{bucket="1_2"} 1952
telemt_desync_frames_bucket_total{bucket="3_10"} 3014
telemt_desync_frames_bucket_total{bucket="gt_10"} 2987
telemt_pool_swap_total 52
telemt_me_writer_close_signal_drop_total 71
telemt_me_writer_removed_unexpected_total 5944
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 5885
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 58
telemt_user_connections_total{user="hello"} 2118509
telemt_user_connections_current{user="hello"} 1754
telemt_user_octets_from_client{user="hello"} 32264862504 (30.05 GB)
telemt_user_octets_to_client{user="hello"} 824092906980 (767.50 GB)
telemt_user_unique_ips_current{user="hello"} 642
telemt_user_unique_ips_recent_window{user="hello"} 185
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 52335.4 (14h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2746467
telemt_connections_bad_total 207574
telemt_connections_current 1408
telemt_connections_me_current 1408
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 32621
telemt_upstream_connect_attempt_total 58527
telemt_upstream_connect_success_total 54117
telemt_upstream_connect_fail_total 4410
telemt_upstream_connect_attempts_per_request{bucket="1"} 58527
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45453
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8091
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 548
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4410
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 9166
telemt_me_reconnect_success_total 6259
telemt_me_reader_eof_total 6517
telemt_me_idle_close_by_peer_total 6516
telemt_me_route_drop_no_conn_total 1889545
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2224553
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8610
telemt_desync_full_logged_total 2741
telemt_desync_suppressed_total 5869
telemt_desync_frames_bucket_total{bucket="1_2"} 2124
telemt_desync_frames_bucket_total{bucket="3_10"} 3140
telemt_desync_frames_bucket_total{bucket="gt_10"} 3346
telemt_pool_swap_total 39
telemt_me_writer_close_signal_drop_total 540
telemt_me_writer_removed_unexpected_total 6927
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 6255
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 668
telemt_user_connections_total{user="hello"} 2268622
telemt_user_connections_current{user="hello"} 1408
telemt_user_octets_from_client{user="hello"} 36511283772 (34.00 GB)
telemt_user_octets_to_client{user="hello"} 651502574441 (606.76 GB)
telemt_user_msgs_from_client{user="hello"} 245686
telemt_user_msgs_to_client{user="hello"} 1753278
telemt_user_unique_ips_current{user="hello"} 541
telemt_user_unique_ips_recent_window{user="hello"} 148
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 106058.4 (29h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6407903
telemt_connections_bad_total 1073330
telemt_connections_current 1676
telemt_connections_me_current 1676
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_demotions_total 4345
telemt_relay_adaptive_hard_promotions_total 27
telemt_handshake_timeouts_total 115517
telemt_upstream_connect_attempt_total 128507
telemt_upstream_connect_success_total 95217
telemt_upstream_connect_fail_total 33290
telemt_upstream_connect_attempts_per_request{bucket="1"} 128507
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 80809
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12971
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1437
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33290
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 79303
telemt_me_reconnect_success_total 13630
telemt_me_reader_eof_total 14672
telemt_me_idle_close_by_peer_total 14658
telemt_me_route_drop_no_conn_total 2830402
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4545520
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
telemt_desync_total 19859
telemt_desync_full_logged_total 6304
telemt_desync_suppressed_total 13555
telemt_desync_frames_bucket_total{bucket="1_2"} 3504
telemt_desync_frames_bucket_total{bucket="3_10"} 8209
telemt_desync_frames_bucket_total{bucket="gt_10"} 8146
telemt_pool_swap_total 93
telemt_me_writer_removed_unexpected_total 13945
telemt_me_refill_failed_total 2047
telemt_me_writer_restored_same_endpoint_total 13605
telemt_me_writer_restored_fallback_total 25
telemt_me_no_writer_failfast_total 1489
telemt_me_async_recovery_trigger_total 7328
telemt_me_writer_removed_unexpected_minus_restored_total 315
telemt_user_connections_total{user="hello"} 4620593
telemt_user_connections_current{user="hello"} 1676
telemt_user_octets_from_client{user="hello"} 73533926164 (68.48 GB)
telemt_user_octets_to_client{user="hello"} 1795609928948 (1.63 TB)
telemt_user_msgs_from_client{user="hello"} 754082
telemt_user_msgs_to_client{user="hello"} 3090177
telemt_user_unique_ips_current{user="hello"} 673
telemt_user_unique_ips_recent_window{user="hello"} 194
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 52298.3 (14h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1002718
telemt_connections_bad_total 86118
telemt_connections_current 492
telemt_connections_me_current 492
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 13401
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
telemt_me_keepalive_timeout_total 546
telemt_me_reconnect_attempts_total 6736
telemt_me_reconnect_success_total 6627
telemt_me_reader_eof_total 7008
telemt_me_idle_close_by_peer_total 7005
telemt_me_route_drop_no_conn_total 472667
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
telemt_desync_total 1421
telemt_desync_full_logged_total 543
telemt_desync_suppressed_total 878
telemt_desync_frames_bucket_total{bucket="1_2"} 219
telemt_desync_frames_bucket_total{bucket="3_10"} 599
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
telemt_user_connections_total{user="hello"} 849834
telemt_user_connections_current{user="hello"} 492
telemt_user_octets_from_client{user="hello"} 7826671095 (7.29 GB)
telemt_user_octets_to_client{user="hello"} 146587209622 (136.52 GB)
telemt_user_msgs_from_client{user="hello"} 11096
telemt_user_msgs_to_client{user="hello"} 16837
telemt_user_unique_ips_current{user="hello"} 168
telemt_user_unique_ips_recent_window{user="hello"} 142
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 52299.7 (14h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2124555
telemt_connections_bad_total 124701
telemt_connections_current 1477
telemt_connections_me_current 1477
telemt_handshake_timeouts_total 39548
telemt_upstream_connect_attempt_total 9450
telemt_upstream_connect_success_total 9385
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 9450
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5064
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4284
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 6797
telemt_me_reconnect_success_total 6752
telemt_me_reader_eof_total 7129
telemt_me_idle_close_by_peer_total 7129
telemt_me_route_drop_no_conn_total 768164
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1809372
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9433
telemt_desync_full_logged_total 3042
telemt_desync_suppressed_total 6391
telemt_desync_frames_bucket_total{bucket="1_2"} 1809
telemt_desync_frames_bucket_total{bucket="3_10"} 3298
telemt_desync_frames_bucket_total{bucket="gt_10"} 4326
telemt_pool_swap_total 53
telemt_me_writer_close_signal_drop_total 41
telemt_me_writer_removed_unexpected_total 6848
telemt_me_writer_restored_same_endpoint_total 6735
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 96
telemt_user_connections_total{user="hello"} 1808473
telemt_user_connections_current{user="hello"} 1477
telemt_user_octets_from_client{user="hello"} 30639623496 (28.54 GB)
telemt_user_octets_to_client{user="hello"} 926706622288 (863.06 GB)
telemt_user_unique_ips_current{user="hello"} 587
telemt_user_unique_ips_recent_window{user="hello"} 146
```