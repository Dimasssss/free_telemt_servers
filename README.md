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

# Server Metrics 2026-03-20 01:03:32 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 27956.9 (7h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 533974
telemt_connections_bad_total 34658
telemt_connections_current 761
telemt_connections_me_current 761
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 7670
telemt_upstream_connect_attempt_total 5962
telemt_upstream_connect_success_total 5883
telemt_upstream_connect_fail_total 79
telemt_upstream_connect_attempts_per_request{bucket="1"} 5962
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3426
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2429
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 79
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 3394
telemt_me_reconnect_success_total 3360
telemt_me_reader_eof_total 3537
telemt_me_idle_close_by_peer_total 3536
telemt_me_route_drop_no_conn_total 156368
telemt_me_route_drop_channel_closed_total 56
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 425649
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2065
telemt_desync_full_logged_total 737
telemt_desync_suppressed_total 1328
telemt_desync_frames_bucket_total{bucket="1_2"} 420
telemt_desync_frames_bucket_total{bucket="3_10"} 704
telemt_desync_frames_bucket_total{bucket="gt_10"} 941
telemt_pool_swap_total 30
telemt_me_writer_close_signal_drop_total 39
telemt_me_writer_removed_unexpected_total 3379
telemt_me_writer_restored_same_endpoint_total 3347
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 447
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 427079
telemt_user_connections_current{user="hello"} 761
telemt_user_octets_from_client{user="hello"} 29513131736 (27.49 GB)
telemt_user_octets_to_client{user="hello"} 154162759869 (143.58 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 315
telemt_user_unique_ips_recent_window{user="hello"} 98
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 44411.5 (12h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2965752
telemt_connections_bad_total 125694
telemt_connections_current 1356
telemt_connections_me_current 1356
telemt_handshake_timeouts_total 64373
telemt_upstream_connect_attempt_total 8889
telemt_upstream_connect_success_total 8743
telemt_upstream_connect_fail_total 146
telemt_upstream_connect_attempts_per_request{bucket="1"} 8889
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5116
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3571
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 146
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 9525
telemt_me_reconnect_success_total 5286
telemt_me_reader_eof_total 5659
telemt_me_idle_close_by_peer_total 5659
telemt_me_route_drop_no_conn_total 1493347
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2539286
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10983
telemt_desync_full_logged_total 3614
telemt_desync_suppressed_total 7369
telemt_desync_frames_bucket_total{bucket="1_2"} 2092
telemt_desync_frames_bucket_total{bucket="3_10"} 4302
telemt_desync_frames_bucket_total{bucket="gt_10"} 4589
telemt_pool_swap_total 37
telemt_me_writer_close_signal_drop_total 51
telemt_me_writer_removed_unexpected_total 5475
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 5231
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 189
telemt_user_connections_total{user="hello"} 2539068
telemt_user_connections_current{user="hello"} 1356
telemt_user_octets_from_client{user="hello"} 39030038122 (36.35 GB)
telemt_user_octets_to_client{user="hello"} 926524335838 (862.89 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 623
telemt_user_unique_ips_recent_window{user="hello"} 124
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 44389.3 (12h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2905456
telemt_connections_bad_total 470529
telemt_connections_current 1111
telemt_connections_me_current 1111
telemt_handshake_timeouts_total 41803
telemt_upstream_connect_attempt_total 7138
telemt_upstream_connect_success_total 7086
telemt_upstream_connect_fail_total 52
telemt_upstream_connect_attempts_per_request{bucket="1"} 7138
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3612
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3458
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 52
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 5788
telemt_me_reconnect_success_total 4855
telemt_me_reader_eof_total 5090
telemt_me_idle_close_by_peer_total 5089
telemt_me_route_drop_no_conn_total 1909955
telemt_me_route_drop_channel_closed_total 172
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2008877
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7603
telemt_desync_full_logged_total 2304
telemt_desync_suppressed_total 5299
telemt_desync_frames_bucket_total{bucket="1_2"} 1873
telemt_desync_frames_bucket_total{bucket="3_10"} 2899
telemt_desync_frames_bucket_total{bucket="gt_10"} 2831
telemt_pool_swap_total 43
telemt_me_writer_close_signal_drop_total 69
telemt_me_writer_removed_unexpected_total 4902
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 4854
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 47
telemt_user_connections_total{user="hello"} 2004547
telemt_user_connections_current{user="hello"} 1111
telemt_user_octets_from_client{user="hello"} 29727533448 (27.69 GB)
telemt_user_octets_to_client{user="hello"} 764245932612 (711.76 GB)
telemt_user_unique_ips_current{user="hello"} 482
telemt_user_unique_ips_recent_window{user="hello"} 112
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 44377.2 (12h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2522484
telemt_connections_bad_total 114695
telemt_connections_current 1035
telemt_connections_me_current 1035
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 30861
telemt_upstream_connect_attempt_total 55093
telemt_upstream_connect_success_total 50832
telemt_upstream_connect_fail_total 4261
telemt_upstream_connect_attempts_per_request{bucket="1"} 55093
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42953
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7326
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 528
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4261
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 8184
telemt_me_reconnect_success_total 5357
telemt_me_reader_eof_total 5557
telemt_me_idle_close_by_peer_total 5556
telemt_me_route_drop_no_conn_total 1857920
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2113731
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8264
telemt_desync_full_logged_total 2608
telemt_desync_suppressed_total 5656
telemt_desync_frames_bucket_total{bucket="1_2"} 2029
telemt_desync_frames_bucket_total{bucket="3_10"} 3008
telemt_desync_frames_bucket_total{bucket="gt_10"} 3227
telemt_pool_swap_total 30
telemt_me_writer_close_signal_drop_total 476
telemt_me_writer_removed_unexpected_total 5975
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 5353
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 618
telemt_user_connections_total{user="hello"} 2155801
telemt_user_connections_current{user="hello"} 1035
telemt_user_octets_from_client{user="hello"} 35313551309 (32.89 GB)
telemt_user_octets_to_client{user="hello"} 603727182965 (562.26 GB)
telemt_user_msgs_from_client{user="hello"} 240837
telemt_user_msgs_to_client{user="hello"} 1741640
telemt_user_unique_ips_current{user="hello"} 418
telemt_user_unique_ips_recent_window{user="hello"} 98
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 98100.6 (27h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6236645
telemt_connections_bad_total 1040108
telemt_connections_current 1208
telemt_connections_me_current 1208
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_demotions_total 4345
telemt_relay_adaptive_hard_promotions_total 27
telemt_handshake_timeouts_total 112446
telemt_upstream_connect_attempt_total 127048
telemt_upstream_connect_success_total 93765
telemt_upstream_connect_fail_total 33283
telemt_upstream_connect_attempts_per_request{bucket="1"} 127048
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 80071
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12261
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1433
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33283
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 78239
telemt_me_reconnect_success_total 12569
telemt_me_reader_eof_total 13539
telemt_me_idle_close_by_peer_total 13525
telemt_me_route_drop_no_conn_total 2787196
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4415671
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
telemt_desync_total 19420
telemt_desync_full_logged_total 6140
telemt_desync_suppressed_total 13280
telemt_desync_frames_bucket_total{bucket="1_2"} 3409
telemt_desync_frames_bucket_total{bucket="3_10"} 7982
telemt_desync_frames_bucket_total{bucket="gt_10"} 8029
telemt_pool_swap_total 84
telemt_me_writer_removed_unexpected_total 12873
telemt_me_refill_failed_total 2047
telemt_me_writer_restored_same_endpoint_total 12544
telemt_me_writer_restored_fallback_total 25
telemt_me_no_writer_failfast_total 1489
telemt_me_async_recovery_trigger_total 7328
telemt_me_writer_removed_unexpected_minus_restored_total 304
telemt_user_connections_total{user="hello"} 4490885
telemt_user_connections_current{user="hello"} 1208
telemt_user_octets_from_client{user="hello"} 70420838856 (65.58 GB)
telemt_user_octets_to_client{user="hello"} 1731946186684 (1.58 TB)
telemt_user_msgs_from_client{user="hello"} 754082
telemt_user_msgs_to_client{user="hello"} 3090177
telemt_user_unique_ips_current{user="hello"} 520
telemt_user_unique_ips_recent_window{user="hello"} 114
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 44340.5 (12h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 699614
telemt_connections_bad_total 73139
telemt_connections_current 355
telemt_connections_me_current 355
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 12971
telemt_upstream_connect_attempt_total 13209
telemt_upstream_connect_success_total 12879
telemt_upstream_connect_fail_total 330
telemt_upstream_connect_attempts_per_request{bucket="1"} 13209
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5343
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6695
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 661
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 330
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 434
telemt_me_reconnect_attempts_total 6304
telemt_me_reconnect_success_total 6198
telemt_me_reader_eof_total 6499
telemt_me_idle_close_by_peer_total 6496
telemt_me_route_drop_no_conn_total 465716
telemt_me_route_drop_channel_closed_total 144
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 575474
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
telemt_pool_swap_total 39
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 150
telemt_me_writer_close_signal_channel_full_total 1
telemt_me_writer_removed_unexpected_total 6256
telemt_me_writer_restored_same_endpoint_total 6189
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 1203
telemt_me_async_recovery_trigger_total 1464
telemt_me_writer_removed_unexpected_minus_restored_total 58
telemt_user_connections_total{user="hello"} 563619
telemt_user_connections_current{user="hello"} 355
telemt_user_octets_from_client{user="hello"} 7247126851 (6.75 GB)
telemt_user_octets_to_client{user="hello"} 140876036162 (131.20 GB)
telemt_user_msgs_from_client{user="hello"} 11096
telemt_user_msgs_to_client{user="hello"} 16837
telemt_user_unique_ips_current{user="hello"} 143
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 44341.8 (12h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1996581
telemt_connections_bad_total 119596
telemt_connections_current 1146
telemt_connections_me_current 1146
telemt_handshake_timeouts_total 36950
telemt_upstream_connect_attempt_total 7869
telemt_upstream_connect_success_total 7810
telemt_upstream_connect_fail_total 59
telemt_upstream_connect_attempts_per_request{bucket="1"} 7869
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4203
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3570
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 59
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 5612
telemt_me_reconnect_success_total 5572
telemt_me_reader_eof_total 5882
telemt_me_idle_close_by_peer_total 5882
telemt_me_route_drop_no_conn_total 736622
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1720557
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9096
telemt_desync_full_logged_total 2920
telemt_desync_suppressed_total 6176
telemt_desync_frames_bucket_total{bucket="1_2"} 1696
telemt_desync_frames_bucket_total{bucket="3_10"} 3197
telemt_desync_frames_bucket_total{bucket="gt_10"} 4203
telemt_pool_swap_total 44
telemt_me_writer_close_signal_drop_total 38
telemt_me_writer_removed_unexpected_total 5657
telemt_me_writer_restored_same_endpoint_total 5555
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 85
telemt_user_connections_total{user="hello"} 1719674
telemt_user_connections_current{user="hello"} 1146
telemt_user_octets_from_client{user="hello"} 29483400204 (27.46 GB)
telemt_user_octets_to_client{user="hello"} 870696213476 (810.90 GB)
telemt_user_unique_ips_current{user="hello"} 467
telemt_user_unique_ips_recent_window{user="hello"} 105
```